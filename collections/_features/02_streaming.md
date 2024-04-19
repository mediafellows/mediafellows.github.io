---
layout: features
title: Secure Video Screening
identifier: streaming
description: Our adaptive video streaming is AES-encrypted by default and offers advanced protection features including DRM, visible and forensic watermarking, and two-factor authentication.
icon: /assets/img/icons/film-solid.svg
image: /assets/img/features/streaming.jpg
header_image: "/assets/img/bg/features.jpg"

text: "Your content sales can showcase video online, anywhere – without having to worry about leaks, piracy or embargoed content.
Our state-of-the-art engine provides industry-verified video security. Even when dealing with sensitive pre-release material, you can rest assured that your videos are fully secured. All streaming video is delivered via HLS with AES encryption and authentication-based stream access by default, while additional security measures can optionally be added."

subtitle_1: Additional security measures
subimage_1: /assets/img/features/details/watermark.jpg
subtext_1: "Optional additional features for sensitive content, like visible watermarking and DRM, give you multiple safety nets. Streaming is delivered via a global content delivery network which provides optimal content quality and no latency across the globe. We have multi-bitrate streaming, so even users with poor internet connection or bandwidth can stream content continuously."

subtitle_2: Two-factor authentication
subimage_2: /assets/img/features/details/2fa-spc.png
subtext_2: "In an era where targeted phishing scams are causing multi-billion dollar losses in the digital world, the inclusion of additional security measures like two-factor authentication (2FA) is becoming increasingly necessary — and may even be non-negotiable for your company. We offer 2FA options via email code or integration with industry-leading authenticator apps such as Google Authenticator and NordPass. To ensure a seamless workflow, MediaStore provides admins with the option to enable a 'trust this browser' setting, temporarily disabling 2FA for a predetermined amount of time."

example_text: Take a look at our projects showcasing our secure video screening features
example_link: projects#rx-online

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
