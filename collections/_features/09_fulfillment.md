---
layout: features
title: Fulfillment & Distribution
identifier: fulfillment
description: Pull fulfillment with self-service downloads for direct, ZIP or Aspera downloads, or push fulfillment with our industry-first intuitive Delivery Wizard.
icon: /assets/img/icons/shopping-basket-solid.svg
image: /assets/img/features/fulfillment.jpg
header_image: "/assets/img/bg/features.jpg"

text: "Host, review, and distribute your assets flexibly. MediaStore extends its functionality beyond sales and marketing by facilitating asset delivery to your licensees. Once your assets are hosted in MediaStore, distribution becomes effortless — eliminating the need to compile from scratch each time or reliance on external file transfer tools."

subtitle_1: Delivery Wizard
subimage_1: /assets/img/features/details/delivery-wizard.png
subtext_1: "Deliver your content seamlessly in just three steps with our new Delivery Wizard. Our intuitive delivery wizard makes content delivery easy. Manage your content sharing preferences effortlessly. Select your preferred transfer solution including Aspera, AWS, Signiant and Google Cloud. Review your assets and execute instant deliveries or schedule for later."

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