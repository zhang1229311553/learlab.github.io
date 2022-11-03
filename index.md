---
title: Home
---

# What We Do

We use data science to generate insights about language, learning, and education that support AI-driven theory, applications, research, and interventions.

Our work generally focuses on the use of natural language processing (NLP) techniques and the application of computational tools and machine learning algorithms to better understand language learning, student writing, and text comprehensibility as means to understand underlying cognitive functions. The LEAR lab works with collaborators to develop NLP tools for use by researchers, industry patterns, and educational administrators. We also assess the application of NLP techniques like Large Language Models in educational settings (K-12 and adults) as a means of generating and testing student domain knowledge.

{%
  include link.html
  type="github"
  icon=""
  text="Find us on GitHub"
  link="learlab"
  style="button"
%}
{:.center}

{% include section.html full=true %}

<!-- {% include banner.html image="images/banner.jpg" %} -->

{% include section.html %}

# Highlights

{% capture text %}
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

{%
  include link.html
  link="data"
  text="See our Datasets and Competitions"
  icon="fas fa-arrow-right"
  flip=true
%}
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/data.svg"
  link="data"
  title="Datasets"
  flip=true
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
