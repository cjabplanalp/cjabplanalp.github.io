---
permalink: /
title: Welcome!
classes: wide
---

I'm Cameron, a recent graduate at the University of Wisconsin-Madison with degrees in Data Science, Information Science, and a minor in Computer Science. I'm an aspiring DS professional looking to code bridges between data and people.

Give a quick read of <a href='https://cdis.wisc.edu/2024-graduation-spotlight-cameron-abplanalp/'>this article</a> about my time at UW-Madison written by the School of Computer, Data, and Information Science!

<style>

    .button-container {
      text-align: center;
      margin-top: 50px;
    }

    button {
      padding: 15px 30px;
      font-size: 16px;
      background-color: rgb(255,120,76);
      color: #fff;
      border: none;
      border-radius: 4px;
      cursor: pointer;
      margin: 0 20px;


      --fc-border-color: #ECEFF9;
      --fc-normal-text-color: #0E0B3D;
      --fc-normal-placeholder-color: #B3B8D0;

      /* PRIMARY COLOR | HSL FORMAT*/
      --fc-primary-color-hue: 18;
      --fc-error-color-hue: 356;
      --fc-primary-hsl: var(--fc-primary-color-hue), 93%, 62%;
      --fc-error-hsl: var(--fc-error-color-hue), 100%, 54%;

      /* HOVER */
      --fc-field-hover-bg-color: #F7F9FC;
      --fc-border-hover-color: #DDE0EE;
      --fc-field-hover-text-color: #B3B8D0;

      --fc-border-active-color: #1463FF;
    }

    button:hover {
      background: linear-gradient(0deg, rgba(0, 0, 0, 0.1), rgba(0, 0, 0, 0.1)), hsla(var(--fc-primary-hsl));
    }

    button:focus {
      background: linear-gradient(0deg, rgba(0, 0, 0, 0.2), rgba(0, 0, 0, 0.2)), hsla(var(--fc-primary-hsl));
      border-inline: 1px solid inline rgba(255, 255, 255, 0.6);
      box-shadow: 0px 0px 0px 3px rgba(var(--fc-primary-hsl), 12%);
    }

    button:active {
      background: linear-gradient(0deg, rgba(0, 0, 0, 0.2), rgba(0, 0, 0, 0.2)), hsla(var(--fc-primary-hsl));
    }

    button:disabled {
      background-color: hsla(var(--fc-primary-hsl), 40%);
      cursor: not-allowed;
    }

    @media (max-width: 600px) {
      .button-container {
        text-align: center;
      }

      button {
        margin: 20px auto;
        display: block;
        padding: 20px;
      }
    }

  </style>

  <script>
    function redirectToPage(pageUrl) {
      window.location.href = pageUrl;
    }
  </script>

<div class="button-container">
    <button onclick="redirectToPage('../assets/files/abplanalp_resume.pdf')">View Resume</button>
    <button onclick="redirectToPage('/projects/')">Explore Projects</button>
    <button onclick="redirectToPage('/contact/')">Contact Me!</button>
</div>
