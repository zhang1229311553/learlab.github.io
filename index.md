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
Our research team creates large datasets that are publicly available. We lead analyses of these and other datasets using NLP techniques and host competitions to attract world-wide talent into learning analytics. We also use large datasets to fine-tune and domain adapt language models to inform educational interventions. A few of our current projects include



**Dataset Development

*The CommonLit EAse of Readability (CLEAR) Corpus

The CLEAR corpus provides unique readability scores for ~5,000 excerpts leveled for 3rd-12th grade readers along with information about the excerpts’ year of publishing, genre, and other meta-data. 

*Persuasive Essays for Rating, Selecting, and Understanding Argumentative and Discourse Elements (PERSUADE) corpus

The PERSUADE corpus is an open-source corpus comprising over 25,000 essays annotated for argumentative and discourse elements and relationships between these elements. In addition, the corpus includes holistic quality scores for each essay and for each argumentative and discourse element. Lastly, the PERSUADE corpus includes detailed demographic information for the writers 

*English Language Learner Insight, Proficiency and Skills Evaluation (ELLIPSE) Corpus

The ELLIPSE corpus comprises ~7,000 essays written by English Language Learners (ELL). The essays were written on 29 different independent prompts that required no background knowledge on the part of the writer. Individual difference information is made available for each essay to include economic status, gender, grade level (8-12), and race/ethnicity. Each essay was scored by two normed human raters for English language proficiency including an overall score of English proficiency and analytic scores for cohesion, syntax, vocabulary, phraseology, grammar, and conventions. 

**Data Analytics Competitions hosted

*CommonLit Readability Prize
https://www.kaggle.com/c/commonlitreadabilityprize

*Feedback Prize - Evaluating Student Writing
https://www.kaggle.com/competitions/feedback-prize-2021

*Feedback Prize - Predicting Effective Arguments
https://www.kaggle.com/competitions/feedback-prize-effectiveness/discussion

*Feedback Prize - English Language Learning

https://www.kaggle.com/competitions/feedback-prize-english-language-learning/

**Tool Development

Along with colleagues at the University of Oregon (Kris Kyle), Arizona State University (Danielle McNamara), and Georgia State University (Joon Suh Choi), we have developed a number of tools that can be used to automatically extract linguistic features, language components, and readability formulas from texts.

The tools focus on the following features
- Lexical sophistication (TAALES)
- Text Cohesion (TAACO)
- Syntactic Complexity (TAASSC)
- Lexical Diversity (TAALED)
- Sentiment Analysis (SEANCE)
- Text Readability (ARTE)
- Grammatical Complexity (GAMET)

The developed tools are freely available on linguisticanalysistool.org


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
