<!--Important for markdown to render! Also make sure the page has a .md extension-->
{% include content_block.html do="open" identifier="markdown" %} <div markdown="1">

The 2020 Bioinformatics Community Conference is pleased to announce our exceptional keynote speakers for BCC2020:

<!-- Sorts the array randomly -->
{% assign n = site.data.speakers | size %}
{% assign speakers = site.data.speakers | sample: n %}

{% for speaker in speakers %}
<h4>{{ speaker.name }} {{ speaker.surname }}</h4>
<h5>{{ speaker.title }} at {{ speaker.company }}</h5>
<div class="pull-right">
  <img src="{{ site.baseurl | append: '/img/people/' | append: speaker.thumbnailUrl }}" alt="{{ speaker.name }} {{ speaker.surname }}" />
</div>

{{  speaker.bio }}

{% endfor %}

</div> {% include content_block.html do="close" identifier="markdown" %}
