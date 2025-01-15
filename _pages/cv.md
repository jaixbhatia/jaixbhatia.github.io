---
layout: page
permalink: /cv/
title: cv
nav: true
nav_order: 5
cv_pdf: /assets/pdf/CV_2025.pdf
---

<style>
  .pdf-container {
    position: relative;
    width: 100%;
    height: 85vh;
    margin: 20px 0;
  }
  .pdf-viewer {
    width: 100%;
    height: 100%;
    border: 1px solid #ddd;
  }
  .button-container {
    text-align: center;
    margin-bottom: 20px;
  }
  .cv-button {
    display: inline-block;
    padding: 10px 20px;
    background-color: #4285f4;
    color: white;
    text-decoration: none;
    border-radius: 4px;
    margin: 0 10px;
  }
  .cv-button:hover {
    background-color: #3367d6;
  }
</style>

<div class="button-container">
  <a href="{{ page.cv_pdf }}" class="cv-button" target="_blank">View CV in New Tab</a>
</div>

<div class="pdf-container">
  <object
    data="{{ page.cv_pdf }}"
    type="application/pdf"
    class="pdf-viewer">
    <div>
      <p>It appears you don't have a PDF plugin for this browser. 
      You can <a href="{{ page.cv_pdf }}">click here to download the PDF file.</a></p>
    </div>
  </object>
</div>
