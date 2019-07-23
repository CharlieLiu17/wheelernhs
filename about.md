---
    layout: page
    title: About Us
---
<body>
<div class="container">
    <div class="row">
        Our Leaders
    </div>
    <div class="row">
        {% for member in site.data.team %}
        <div class="col-xs-6">
            <div class="team-member">
                <img src="/img/{{ member.photo }}" class="img-responsive img-circle" alt="{{ member.name }}">
                <h4>{{ member.name }}</h4>
                <p >{{ member.bio }}</p>      
            </div>
        </div>
        {% endfor %}
    </div>
    <div class="row">
        **The leadership team has great things planned this year for the club and can't wait to make this the best club in Wheeler in 2020!**
    </div>
</div>
</body>
    