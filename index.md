---
title: Andrew Mundy
layout: default
---

<div class="wrapper grid">
    <div class="grid__item one-whole desk-six-tenths">
        <div class="lead">
            Andrew Mundy is a cyclist, an engineer and PhD student at the University of Manchester.
        </div>

        <ol class="block-list">
            {% for post in site.posts %}
            <li>
                <a href="{{ post.url }}"><h2>{{ post.title }}</h2></a>
                {{ post.excerpt }}
            </li>
            {% endfor %}
        </ol>

    </div>

    <hr class="visuallyhidden--desk" />

    <div class="grid__item one-whole desk-three-tenths desk-push--one-sixth">
        <h2>Projects &amp; Code</h2>
        <ul class="block-list">
            <li>
                <h3>Unofficial Beamer theme for the University of Manchester</h3>
            </li>
            <li>
                <h3>ttybotron</h3>
            </li>
        </ul>
    </div>
</div>
