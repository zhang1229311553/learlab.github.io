---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# <i class="fas fa-users"></i>Team

We have a diverse and supportive team with a wide range of skillsets and backgrounds. 

{% include section.html %}

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: pi"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: phd"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: ma"
%}
{:.center}

{% include section.html background="images/banner.jpg" dark=true%}

Teamwork makes the dream work.

{% include section.html %}

## Join

### Post Dogtoral Researcher

We would like a post dog.

- 3+ (dog) years experience managing bone portfolios
- Strong desire to learn tricks and go on walkies
- Aptitude to sit and stay

{% include link.html type="external" link="https://google.com/" text="Apply Now" icon="" style="button" %}
{:.center}

{% include section.html %}

## Funding

Our work is made possible by funding from several organizations.
{:.center}

{%
  include gallery.html
  style="square"

  image1="images/ai-aloe.jpg"
  link1="https://aialoe.org/"
  tooltip1="AI-ALOE"

  image2="images/learning-agency.png"
  link2="https://www.the-learning-agency.com/"
  tooltip2="The Learning Agency"

  image3="images/nsf.png"
  link3="https://beta.nsf.gov/funding/opportunities/national-artificial-intelligence-research"
  tooltip3="National Science Foundation"
%}
