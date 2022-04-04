---
title: Home
---

# Yan's lab

[Our lab](https://github.com/greenelab/lab-website-template) is an MRI research group on arterial spin labelling imaging for [labs](https://www.greenelab.com/), with adds-on processing tools and well-suited pulse sequence for MRI imaging. 
Our research focused on ... . 

<!-- {%
  include link.html
  type="github"
  icon=""
  text="See the template on GitHub"
  link="greenelab/lab-website-template"
  style="button"
%} -->
<!-- {%
  include link.html
  type="docs"
  icon=""
  text="See the documentation"
  link="https://github.com/greenelab/lab-website-template/wiki"
  style="button"
%} -->
<!-- {:.center} -->

{% include section.html full=true %}

{% include banner.html image="images/banner.jpg" %}

{% include section.html %}

# Highlights

{% capture text %}
we need content to capture other researcher's interest 


{%
  include link.html
  link="research"
  text="See our publication"
  icon="fas fa-arrow-right"
  flip=true
%}
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}
resources for ASL imaging processing 

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
  image="images/photo.jpg"
  link="resources"
  title="Our Resources"
  flip=true
  text=text
%}

{% capture text %}
open position will be coming soon

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
  image="images/photo.jpg"
  link="team"
  title="Our Team"
  text=text
%}

The website is still under-developed. Currently is maintained by Yining HE, heyining@northwestern.edu 