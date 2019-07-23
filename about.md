---
    layout: page
    title: About Us
---

<div class="container">
    <div class="row">
        <div class="col-lg-12 ">
            <h2 class="section-heading">Our Leaders</h2>
            <h3 class="section-subheading text-muted">Without them, what could we do?</h3>
        </div>
    </div>
    <div class="row">
        {% for member in site.data.team %}
        <div class="col-xs-6">
            <div class="team-member">
                <img src="/img/{{ member.photo }}" class="img-responsive img-circle" alt="{{ member.name }}">
                <h4>{{ member.name }}</h4>
                <p class="text-muted">{{ member.bio }}</p>      
            </div>
        </div>
        {% endfor %}
    </div>
    <div class="row">
        <div class="col-lg-8 col-lg-offset-2 ">
            <p class="large text-muted">The leadership team has great things planned this year for the club 
            <br>and can't wait to make this the best club in Wheeler in 2020!</p>
        </div>
    </div>
</div>
    