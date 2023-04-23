---
layout: post
title: "新页面测试"
name: 2023-04-20-test-everything-post
img: cover.jpg # Add image post (optional)
date: 2023-04-20 14:41 +0400
description: You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. # Add post description (optional)
tag: [Travel, Blogging, Mountains]
---


<!-- ## 滚动横幅窗口 -->

<!-- <div class="rotating-banner"> -->
<!--     <img src="{{ "/assets/img/" | prepend: site.baseurl }}cover1.jpg" alt="Image 1"> -->
<!--     <img src="{{ "/assets/img/" | prepend: site.baseurl }}canyon.jpg" alt="Image 2"> -->
<!--     <img src="{{ "/assets/img/" | prepend: site.baseurl }}sweden.jpg" alt="Image 3"> -->
<!--     <img src="{{ "/assets/img/" | prepend: site.baseurl }}nevada.jpg" alt="Image 3"> -->
<!--     <img src="{{ "/assets/img/" | prepend: site.baseurl }}himalayan.jpg" alt="Image 3"> -->
<!-- </div> -->

<!-- <script> -->
<!--     $(document).ready(function() { -->
<!--         var initImg = $('.rotating-banner img:first-child'); -->
<!--         initImg.addClass('active'); -->
<!--         setInterval(function() { -->
<!--             var currentImg = $('.rotating-banner img.active'); -->
<!--             var nextImg = currentImg.next(); -->
<!--             if (nextImg.length == 0) { -->
<!--                 nextImg = $('.rotating-banner img:first-child'); -->
<!--             } -->
<!--             currentImg.removeClass('active'); -->
<!--             nextImg.addClass('active'); -->
<!--         }, 3000); -->
<!--     }); -->
<!-- </script> -->

## Title 大标题

paragraph test paragraph test paragraph test paragraph test paragraph test paragraph test
paragraph test paragraph test paragraph test paragraph test paragraph test paragraph test
中文测试段落 中文测试段落 中文测试段落 中文测试段落 中文测试段落 中文测试段落 中文测试段落 中文测试段落 中文测试段落
中文测试段落 中文测试段落 中文测试段落 中文测试段落 中文测试段落 中文测试段落 中文测试段落 中文测试段落 中文测试段落

### Sub Title 小标题

paragraph test paragraph test paragraph test paragraph test paragraph test paragraph test
paragraph test paragraph test paragraph test paragraph test paragraph test paragraph test
中文测试段落 中文测试段落 中文测试段落 中文测试段落 中文测试段落 中文测试段落 中文测试段落 中文测试段落 中文测试段落
中文测试段落 中文测试段落 中文测试段落 中文测试段落 中文测试段落 中文测试段落 中文测试段落 中文测试段落 中文测试段落

> 引用样式测试 blockquote 

## 图片展示样式测试 Image display test 
    
### 上图下文 Top img down caption (class = "blog-img-td")

<div class = "blog-img-td">
    <div>
        <img src= "{{ "/assets/img/" | prepend: site.baseurl | append:page.name}}/cover.jpg">
    </div>
    <div>
        <legend>description description description description description description description
            文字描述 文字描述 文字描述 文字描述 文字描述 文字描述 文字描述 文字描述 文字描述 文字描述 文字描述</legend>
    </div>
</div>

### 仅图片 Pure img (class = "blog-img-only")

<div class = "blog-img-only">
    <div>
        <img src= "{{ "/assets/img/" | prepend: site.baseurl | append:page.name}}/cover.jpg">
    </div>
</div>

## 视频展示测试 Video display test (class = "blog-video")

<div class = "blog-video">
    <video  controls>
        <source src="https://drive.google.com/uc?export=download&id=1WafTItDAKgdysiMkJcpHL7TzRup1Ztjk" type='video/mp4'>
    </video>
</div>



