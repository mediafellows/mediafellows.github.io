---
layout: features
title: Secure Video Screening
identifier: streaming
description: Our adaptive video streaming is AES-encrypted by default and offers advanced protection features including DRM, visible and forensic watermarking, and two-factor authentication.
icon: /assets/img/icons/film-solid.svg
image: /assets/img/features/streaming.jpg
header_image: "/assets/img/bg/features.jpg"

text: "Our state-of-the-art video streaming engine adapts to the user's bandwidth for a seamless viewing experience. And even when dealing with sensitive pre-release material, you can rest assured that your videos are fully secured. All streaming video is delivered via HLS with AES encryption by default, while additional security measures can optionally be added."

subtitle_1: Additional security measures
subimage_1: /assets/img/features/details/streaming-video.png
subtext_1: "Our standard client-facing platform comes with all the features you need to showcase your catalogue, offer personal screening links, provide post-sales asset downloads, and much more. Just provide us with some details and specifications (logo, colours, email texts, etc.) and we'll get your bespoke version up and running swiftly. Need customization beyond the scope of our key configuration options? No problem, the design is flexible enough to add, change or remove elements. CMS functionality is available to easily manage presentational elements such as sliders, contact pages, news and much more."

subtitle_2: Shared screening links
subimage_2: /assets/img/features/details/security-screening_link.png
subtext_2: "Targeted screening links can be sent to anyone, whether they're already a user of your client platform or not. Trigger a screening recommendation from a single title immediately or compile a package first, then simply define the recipient(s) and key validity parameters such as an expiry date, login/registration requirement and, optionally, the maximum number of views. Each recipient will get their own private screening link accessible immediately through the email, or at any time in their logged-in client dashboard."

---

<div class="row">
    <div class="col-md-12">
        <div class="service-details mb-40">
            <p>{{ page.text }}</p>
        </div>
    </div>
</div>
<div class="row">
    <div class="col-xl-6 col-lg-12">
        <div class="s-details-img mb-30">
          <img src="{{ page.subimage_1 }}" alt="{{ page.title }}">  
        </div>
    </div>
    <div class="col-xl-6 col-lg-12">
        <div class="service-details mb-40">
            <h3>{{ page.subtitle_1 }}</h3>
            <p>{{ page.subtext_1 }}</p>
        </div>
    </div>
</div>
<div class="row">
    <div class="col-xl-6 col-lg-12">
        <div class="service-details mb-40">
            <h3>{{ page.subtitle_2 }}</h3>
            <p>{{ page.subtext_2 }}</p>
        </div>
    </div>
    <div class="col-xl-6 col-lg-12">
        <div class="s-details-img mb-30">
          <img src="{{ page.subimage_2 }}" alt="{{ page.title }}">
        </div>
    </div>
</div>
