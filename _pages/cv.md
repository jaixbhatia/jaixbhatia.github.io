---
layout: page
permalink: /cv/
title: cv
nav: true
nav_order: 5
---

<style>
  .pdf-container {
    position: relative;
    width: 100%;
    height: 0;
    padding-top: 141.4%; /* A4 aspect ratio (1:1.414) */
    overflow: hidden;
  }
  .pdf-container object {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
  }
  @media (max-width: 767px) {
    .pdf-container {
      padding-top: 150%; /* Slightly taller on mobile for better visibility */
    }
  }
</style>

<div class="pdf-container">
  <object data="{{ site.baseurl }}/assets/pdf/CV_2025.pdf" type="application/pdf">
    <p>It appears you don't have a PDF plugin for this browser. 
    You can <a href="{{ site.baseurl }}/assets/pdf/CV_2025.pdf">click here to download the PDF file.</a></p>
  </object>
</div>
