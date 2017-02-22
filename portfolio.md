---
layout: page
title:  My projects
---



<ul class="list-reset">
    {% for project in site.projects %}
    <li>
        <div class="clearfix">
            <div class="col col-6 left-align pl1">
                <a href="{{ project.url | relative_url }}">
                    {{ project.title }}
                </a>
            </div>
        </div>
    </li>
    {% endfor %}
</ul>