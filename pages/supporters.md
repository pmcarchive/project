---
title: Supporters
layout: page
permalink: /supporters.html
# include CollectionBuilder info at bottom
credits: false
# featured-image value can be one objectid for a photo object in this collection, a relative path to an image in this project, or a full url to any image. If left blank, no featured image will appear at top of About page.
about-featured-image: /assets/img/PMCThinBanner.png
# set background-position for featured image, "center", "top", "bottom"
position: top
# major heading to display over featured image
heading: Our Supporters
# paragraph text below heading in featured image
sub-heading: 
# additional padding added to the feature to increase size. Give value in em or px, e.g. "5em".
padding: 2.5em
# Edit the markdown on in this file to describe your collection
# Look in _includes/feature for options to easily add features to the page
---
<br>

### The Printer's Marks and Chops Archive is thankful to our supporters who have made this project possible.

<br>

<div class="row">
  <div class="col-md-6">
    {% capture left %} 

{% include feature/image.html objectid="https://printscholars.org/wp-content/uploads/2014/10/APS_logo_web.png" link="https://printscholars.org/" width=50 %}

The APS Collaboration Grant provided funding for site development and deployment using Collection Builder. 

<br>

{% include feature/image.html objectid="/assets/img/swann_logo.jpeg" link="https://www.swanngalleries.com/" width=50 %}
Swann Auction Galleries continues to share images and identifications of marks found by their staff.

<br>

{% include feature/image.html objectid="/assets/img/annex_logo.png" link="https://www.annexgalleries.com/" width=75 %}
Scans of several sources used to launch this resource were provided by Annex Galleries.

<br>

    {% endcapture %}
    {{ left | markdownify }}
  </div>

  <div class="col-md-6">
    {% capture right %}

{% include feature/image.html objectid="/assets/img/syr_logo.jpeg" link="https://undergraduateresearch.syracuse.edu/" width=50 %}

Funding support for Syracuse University research assistants was provided by the Syracuse Office of Undergraduate Research & Creative Engagement (The SOURCE). 

<br>
{% include feature/image.html objectid="/assets/img/des-moines-logo.png" link="https://desmoinesartcenter.org/" width=25 %}
Des Moines Art Center's Registrar, Sydney Royal Welch, shared images and identifications of marks found by the museum's staff.

<br>

{% include feature/image.html objectid="/assets/img/SamekLogo_Transparent Large.jpeg" link="https://museum.bucknell.edu" width=50 %}
Many of the marks and chops were found in the Samek Art Museum collection and were researched using resources available at Bucknell University. 

   {% endcapture %}
    {{ right | markdownify }}
