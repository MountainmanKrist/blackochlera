---
layout: default
title: "Bläck och lera"
desc: "Tatueringar och keramik"
startpage: true
---

<div class="text-center">
    {% assign kristin = site.pages | where: 'title', "Kristin" | map: "url" %}
    {% assign ingrid = site.pages | where: 'title', "Ingrid" | map: "url" %}
    {% assign kerstin = site.pages | where: 'title', "Kerstin" | map: "url" %}
    <p><h2> <a href="{{ site.baseurl }}{{ kristin }}">Tatueringar</a></h2> </p>
    <p><h2> och </h2> </p>
    <p><h2> Keramik </h2> </p>
    <p>(<a href="{{ site.baseurl }}{{ ingrid }}">Ingrid</a>, <a href="{{ site.baseurl }}{{ kerstin }}">Kerstin</a>) </p>
</div>