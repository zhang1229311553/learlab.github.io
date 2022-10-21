---
title: Home
---

# Knowledge is data-driven

We use data science to generate insights about learning that support AI-driven education interventions.

{%
  include link.html
  type="github"
  icon=""
  text="Find us on GitHub"
  link="learlab"
  style="button"
%}
{%
  include link.html
  type="docs"
  icon=""
  text="See the documentation"
  link="https://github.com/greenelab/lab-website-template/wiki"
  style="button"
%}
{:.center}

{% include section.html full=true %}

{% include banner.html image="images/banner.jpg" %}

{% include section.html %}

# Highlights

{% capture text %}
Our research makes sense of big datasets.

{%
  include link.html
  link="research"
  text="See what we've published"
  icon="fas fa-arrow-right"
  flip=true
%}
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/research.svg"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}
We are developing tools that will benefit the research community.

{%
  include link.html
  link="tools"
  text="Browse our tools"
  icon="fas fa-arrow-right"
  flip=true
%}
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/tools.svg"
  link="resources"
  title="Our Resources"
  flip=true
  text=text
%}

{% capture text %}
We are a diverse and multidisciplinary group of researchers. Our team is awesome. 

{%
  include link.html
  link="team"
  text="Meet our team"
  icon="fas fa-arrow-right"
  flip=true
%}
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/team.svg"
  link="team"
  title="Our Team"
  text=text
%}

{% comment %}
Text can go here.
{% endcomment %}
