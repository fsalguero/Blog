---
layout: default
title: Checklists
private: true
all_lists:
- biking
- hiking
- software
- commuting
scripts:
- checklists-index
sitemap: false
---

<div class="container-fluid">
    <div class="row">
    <div class="col-xs-12 col-sm-6 well shadow">
            <h1>Checklists</h1>
            <ul class="">
                {% for list in page.all_lists %}
                <li><a href="/checklists/{{ list }}/">{{ list }}</a></li>
                {% endfor %}
            </ul>
        </div>

        <div class="col-xs-12 col-sm-5 col-sm-offset-1 well shadow">
            <h1>Other</h1>
            <button class="btn btn-primary shadow" type="button" id="opt-button">Opt-out analytics</button>
        </div>
    </div>

</div>
