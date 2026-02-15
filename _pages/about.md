---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi, I'm Zhang Yuehan, a researcher at the *Graphics & Image Intelligence Lab, Huawei Singapore Research Center*. Previously, I obtained my Ph.D degree from National University of Singapore, supervised by **Associate Professor Angela Yao**. 

## Research Interests
My research focused on the most challenging problems in the low-level vision area, including solving the confilicts between regression and generation and achieving stable video/image super-resolution performance in changing real-world conditions. 

Now I expand my explorations to image and video generation tasks, specifically, how to measure the generation quality and give effective rewards.


## Experience

* **AIGC Researcher** | *Huawei Singapore Research Center* | May 2025 – Present
  * Text-to-Video generation
  * Text-to-Image generation

---
## Education

* **Ph.D. in Computer Science** | *National University of Singapore* | 2020 – 2025
  * Dissertation: *Improving Super-Resolution Methods for
Real-World Requirements*
  * Advisor: Prof. Angela Yao

* **B.Sc. in Computer Science and Technology** | *Huazhong University of Science and Technology, China* | 2016 – 2020


## Selected Publications
{% assign sorted_publications = site.publications | sort: 'weight' %}
{% for post in sorted_publications limit:3 %}
  {% include archive-single.html type="list" %}
{% endfor %}

<div style="clear: both;"></div>
[View all publications](/publications/){: .btn .btn--info}

<style>
  /* Container for each publication item - thumbnail on left, content on right */
  .list__item {
    margin-bottom: 20px !important;
    border-bottom: 1px solid #eee;
    padding-bottom: 15px;
  }

  .list__item .archive__item {
    display: flex !important;
    align-items: flex-start !important;
  }

  /* Thumbnail on the left - larger size */
  .list__item .archive__item-teaser {
    flex: 0 0 160px !important;
    margin-right: 20px !important;
    margin-bottom: 0 !important;
    max-height: 120px;
    overflow: hidden;
    display: block !important;
  }

  .list__item .archive__item-teaser img {
    width: 100% !important;
    height: auto !important;
    border-radius: 4px;
    margin: 0 !important;
  }

  /* Text content on the right - smaller font */
  .list__item .archive__item-body {
    flex: 1;
    font-size: 0.85rem !important;
  }

  .list__item .archive__item-body p {
    font-size: 0.8rem !important;
    margin: 2px 0 !important;
  }

  .list__item .archive__item-title {
    font-size: 0.95rem !important;
    margin-top: 0 !important;
    line-height: 1.2 !important;
  }

  /* Hide paper description on about page */
  .list__item .archive__item-excerpt {
    display: none !important;
  }
</style>