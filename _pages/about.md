---
layout:    about
permalink: "/about"
author:    dramalamas
keywords:  about person dramalamas
title:     DramaLamas Team
menutitle: Über
weight:    90
excerpt:   Das Team DramaLamas stellt sich vor.
---
<script async defer src="https://buttons.github.io/buttons.js"></script>

<!--
    Data files with jekyll
    https://jekyllrb.com/docs/datafiles/
-->

{% assign cv = site.data.cv[page.author] %}

<div class="md-card no-border">
    <p>{{cv.profile}}</p>
</div>

{% assign cv = site.data.cv["thomas"] %}
<div class="md-card shadow">
    <div class="title icon-stats-bars">
        <h2>Thomas</h2>
    </div>
    <div class="content">
        <ul>
            {% for skill in cv.skills %}
            <li>{{ skill }}</li>
            {% endfor %}
        </ul>
    </div>
</div>

{% assign cv = site.data.cv["cdecker"] %}
<div class="md-card shadow">
    <div class="title icon-stats-bars">
        <h2>Christian</h2>
    </div>
    <div class="content">
        <ul>
            {% for skill in cv.skills %}
            <li>{{ skill }}</li>
            {% endfor %}
        </ul>
    </div>
</div>

{% assign cv = site.data.cv["rabea"] %}
<div class="md-card shadow">
    <div class="title icon-stats-bars">
        <h2>Rabea</h2>
    </div>
    <div class="content">
        <ul>
            {% for skill in cv.skills %}
            <li>{{ skill }}</li>
            {% endfor %}
        </ul>
    </div>
</div>

{% assign cv = site.data.cv["laura"] %}
<div class="md-card shadow">
    <div class="title icon-stats-bars">
        <h2>Laura</h2>
    </div>
    <div class="content">
        <ul>
            {% for skill in cv.skills %}
            <li>{{ skill }}</li>
            {% endfor %}
        </ul>
    </div>
</div>

{% assign cv = site.data.cv["milchbroetchen"] %}
<div class="md-card shadow">
    <div class="title icon-stats-bars">
        <h2>Milchbrötchen</h2>
    </div>
    <div class="content">
        <ul>
            {% for skill in cv.skills %}
            <li>{{ skill }}</li>
            {% endfor %}
        </ul>
    </div>
</div>


<!--
<p class="github-button-container">
<a class="github-button" href="https://github.com/jwillmer/jekyllDecent" data-size="large" data-show-count="true" aria-label="Star jwillmer/jekyllDecent on GitHub">jekyllDecent</a>
</p>
-->
