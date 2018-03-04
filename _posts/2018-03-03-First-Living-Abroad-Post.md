---
layout: default
category: LIVING-ABROAD
post-image: https://source.unsplash.com/random
subject: Visas
title: How to get a work visa in Amsterdam
sample-content: This is a blurb that will make the person interested enough to read the story. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
intro-content: This section is the introduction to the subject of the story.In ornare quam viverra orci sagittis. In nibh mauris cursus mattis molestie a. Condimentum lacinia quis vel eros donec.
history-content: This section is the history of the subject of the story.In ornare quam viverra orci sagittis. In nibh mauris cursus mattis molestie a. Condimentum lacinia quis vel eros donec.
history-image: /images/DanJames.jpg
history-blockquote: "THIS IS THE QUOTE FROM THE STORY."
tp-content: This is the part where the story has a turning point. In ornare quam viverra orci sagittis. In nibh mauris cursus mattis molestie a. Condimentum lacinia quis vel eros donec.
life-now-content: This is the section that discusses the person's life in present day.  Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Sed sed risus pretium quam vulputate dignissim. Volutpat blandit aliquam etiam erat velit. In ornare quam viverra orci sagittis. In nibh mauris cursus mattis molestie a. Condimentum lacinia quis vel eros donec.
life-now-image: /images/girls.jpg
wrap-up-content: This is the wrap up/ending to the article. In ornare quam viverra orci sagittis. In nibh mauris cursus mattis molestie a. Condimentum lacinia quis vel eros donec.
call-to-action: This is a call to action or how to contact the person if relevant.
author-image: /images/back-view.jpg
about-author: ABOUT AUTHOR CONTENT
---
<!--ARTICLE TITLE AND BY LINE-->
<section class="grid">
  <div class="col-3">{{page.category}}</div>
  <div class="col-9">
    <h2>{{page.title}}</h2>
  </div>
</section>
<!--BODY OF ARTICLE-->
<section>
  {{page.intro-content}}
</section>
<section class="grid">
  <div class="col-8">{{page.history-content}}</div>
  <div class="col-4">
    <div class="bg-img" style="background-image: url({{page.history-image}})"> </div>
  </div>
  <div class="col-4">
    <blockquote>{{page.history-blockquote}}</blockquote>
  </div>
  <div class="col-8">{{page.tp-content}}</div>
  <div class="col-12">{{page.life-now-content}}</div>
  <div class="col-12">
    <div class="bg-img" style="background-image: url({{page.life-now-image}})"></div>
  </div>
  <div class="col-6">{{page.wrap-up-content}}</div>
  <div class="col-6">{{page.call-to-action}}</div>
</section>
<!--AUTHOR INFO AND SHARE ON SOCIAL BANNER-->
<section class="grid">
  <div class="col-2">
    <div class="bg-img" style="background-image: url({{page.author-image}})"></div>
  </div>
  <div class="col-2">{{page.about-author}}</div>
  <div class="col-10">
    <h3>LOVE AND SHARE THIS CONTENT</h3>
    <a class="button"><i class="far fa-heart"></i></a>
    <a class="button"><i class="far fa-envelope"></i> </a>
    <a class="button"><i class="fab fa-facebook-square"></i></a>
    <a class="button"><i class="fab fa-twitter-square"></i></a>
    <a class="button"><i class="fab fa-pinterest"></i></a>
    <a class="button"><i class="fab fa-flipboard"></i></a>
    <a class="button"><i class="fab fa-facebook-messenger"></i></a>
    <a class="button"><i class="fab fa-whatsapp-square"></i></a>
  </div>  
</section>
