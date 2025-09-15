---
title: FUNtastic Paradise
permalink: /funtastic-paradise/
variant: markdown
description: ""
third_nav_title: Joyful Learning
---
<div style="max-width: 900px; margin: 0 auto; text-align: center; font-family: Arial, sans-serif;">

  
  <img style="width:100%; border-radius: 12px; margin-bottom: 20px;" alt="Header Image" src="/images/2025/MK/Header.jpg">

  
  <div style="margin: 30px 0;">
    <iframe style="border-radius: 12px;" allowfullscreen="" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" frameborder="0" title="YouTube video player" src="https://www.youtube.com/embed/9Nm3PjobQvw?si=eaQtq3LDo_Ov-qT7" height="500" width="100%">
    </iframe>
  </div>

  
  <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); gap: 15px;">
    <a style="display:block;" href="#lb1"><img style="width:100%; border-radius: 12px; cursor:pointer;" alt="Image 1" src="/images/2025/MK/1.jpg"></a>
    <a style="display:block;" href="#lb2"><img style="width:100%; border-radius: 12px; cursor:pointer;" alt="Image 2" src="/images/2025/MK/2.jpg"></a>
    <a style="display:block;" href="#lb3"><img style="width:100%; border-radius: 12px; cursor:pointer;" alt="Image 3" src="/images/2025/MK/3.jpg"></a>
  </div>
</div>


<div class="lightbox" id="lb1">
  <a aria-label="Close" class="lb-backdrop" href="#"></a>
  <img alt="Image 1 large" src="/images/2025/MK/1.jpg">
  <a aria-label="Close" class="lb-close" href="#">×</a>
</div>

<div class="lightbox" id="lb2">
  <a aria-label="Close" class="lb-backdrop" href="#"></a>
  <img alt="Image 2 large" src="/images/2025/MK/2.jpg">
  <a aria-label="Close" class="lb-close" href="#">×</a>
</div>

<div class="lightbox" id="lb3">
  <a aria-label="Close" class="lb-backdrop" href="#"></a>
  <img alt="Image 3 large" src="/images/2025/MK/3.jpg">
  <a aria-label="Close" class="lb-close" href="#">×</a>
</div>

<style>
  /* Base overlay (hidden by default) */
  .lightbox {
    position: fixed;
    inset: 0;
    display: flex;
    align-items: center;
    justify-content: center;
    background: rgba(0,0,0,.9);
    opacity: 0;
    visibility: hidden;
    pointer-events: none;
    transition: opacity .2s ease;
    z-index: 9999;
  }

  /* Show when targeted */
  .lightbox:target {
    opacity: 1;
    visibility: visible;
    pointer-events: auto;
  }

  /* Image styling */
  .lightbox img {
    max-width: 90vw;
    max-height: 80vh;
    border-radius: 12px;
    box-shadow: 0 10px 30px rgba(0,0,0,.5);
  }

  /* Clickable backdrop to close */
  .lb-backdrop {
    position: absolute;
    inset: 0;
    display: block;
    content: "";
  }

  /* Close button */
  .lb-close {
    position: absolute;
    top: 16px;
    right: 24px;
    font-size: 40px;
    line-height: 1;
    color: #fff;
    text-decoration: none;
    padding: 4px 10px;
  }
</style>
