---
layout: default
title: Home
---

# Welcome to My GitHub Pages Site

This is a demo of embedding images and video in Markdown.

---

## Image Embed

Here's an image stored in your repository under `assets/images/example.jpg`:

![An example image](/assets/images/example.jpg)

---

## Local Video Embed

If you have an MP4 in `assets/videos/demo.mp4`, you can use the HTML5 `<video>` tag:

<video controls width="640" height="360">
  <source src="/assets/videos/demo.mp4" type="video/mp4">
  <!-- Fallback text: -->
  Your browser doesn’t support HTML5 video.
</video>

---

## YouTube Embed

To embed a YouTube video, you can drop in an `<iframe>`:

<iframe width="560" height="315"
  src="https://www.youtube.com/embed/VIDEO_ID"
  frameborder="0"
  allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
  allowfullscreen>
</iframe>
