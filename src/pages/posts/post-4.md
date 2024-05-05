---
layout: ../../layouts/MarkdownPostLayout.astro
title: My Fourth Blog Post
author: Astro Learner
description: "This post will show up on its own!"
image:
    url: "https://docs.astro.build/default-og-image.png"
    alt: "The word astro against an illustration of planets and stars."
pubDate: 2022-08-08
tags: ["astro", "successes"]
---
<style>
  body {
    text-align: center;
    font-size: 1.23rem;
    font-family: "Roboto", sans-serif;
    font-weight: 400;
    color: #333;
    line-height: 1.6;
    margin: 0;
    padding: 0;
    background-image: url("/public/notep.jpg");
    background-repeat: no-repeat;
    background-attachment: scroll;
    background-position: center;
    background-size: cover;
  }

  .container {
    max-width: 800px;
    margin: 0 auto;
    padding: 20px;
    background-color: #fff;
    border-radius: 8px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
  }

  h1, h2, h3 {
    color: #333;
  }

  a {
    color: #007bff;
    text-decoration: none;
  }

  a:hover {
    text-decoration: underline;
  }

  blockquote {
    margin: 0;
    padding: 10px 20px;
    background-color: #f9f9f9;
    border-left: 4px solid #007bff;
  }

  ul {
    list-style-type: none;
    padding-left: 0;
  }

  li {
    margin-bottom: 10px;
  }

  li:before {
    content: "\2022";
    color: #007bff;
    display: inline-block;
    width: 1em;
    margin-left: -1em;
  }

  input[type="checkbox"] {
    margin-right: 10px;
  }

  p {
    margin-bottom: 20px;
  }
</style>

[Back to Blog](https://gryn-astro-demo.netlify.app/blog/)

This post should show up with my other blog posts, because `Astro.glob()` is returning a list of all my posts in order to create my list.