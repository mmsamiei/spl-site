---
title: "SPL Lab - People"
layout: default
permalink: /people
---
{% for member in site.data.master_students %}
{{member.first_name }}
{% endfor %}

{% for member in site.data.phd_students %}
{{member.first_name }}

{% endfor %}
