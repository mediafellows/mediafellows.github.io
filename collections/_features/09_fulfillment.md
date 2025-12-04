---
layout: features
title: Fulfillment & Distribution
identifier: fulfillment
description: Offer pull fulfillment with easy self-service downloads (direct, ZIP, or Aspera), or push fulfillment through automated, profile-based deliveries using the MediaStore Delivery Manager.
icon: /assets/img/icons/shopping-basket-solid.svg
image: /assets/img/features/fulfillment.jpg
header_image: "/assets/img/bg/features.jpg"

text: "Host, review, and distribute your assets flexibly. MediaStore extends its functionality beyond sales and marketing by facilitating asset delivery to your licensees. Once your assets are hosted in MediaStore, distribution becomes effortless — eliminating the need to compile from scratch each time or reliance on external file transfer tools."

subtitle_1: Content Delivery
subimage_1: /assets/img/features/details/content_delivery.png
subtext_1: "MediaStore delivers your content through simple point-to-point methods (SFTP, S3, or Aspera) or via our Delivery Manager. The Delivery Manager lets users configure deliveries using specific recipient profiles. Since recipients (such as licensees, clients, platforms, or destination points) often have unique metadata and packaging requirements, these profiles make it easy to trigger new deliveries and select the right content for each destination."

subtitle_2: Self-Service Download
subimage_2: /assets/img/features/details/nbcu-downloads.png
subtext_2: "Using our flexible access controls, you can grant timed access to specific clients, allowing them to retrieve assets from your catalog using various self-service download options such as ZIP package delivery and Aspera Faspex file transfer. Clients can easily browse, search, and filter assets with the same quality of presentation you expect from MediaStore. You can compile Collections or allow clients to show you which assets they need with fully flexible Wish Lists, Baskets and more. Additionally, you can send email-based download links directly from the platform to minimize their effort further."

example_text: Take a look at our projects showcasing our fulfillment and distribution solutions
example_link: projects#nbcu

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