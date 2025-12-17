---
layout: features
title: Subtitles, Audio and Pre-Rolls
identifier: subassets
description: Component-based videos with separate audio tracks, subtitles, or pre-rolls simplify asset management. Next-gen AI tools offer fast, preview-quality subtitles in mutliple languages.
icon: /assets/img/icons/layer-group-solid.svg
image: /assets/img/features/subtitles.png
header_image: "/assets/img/bg/features.jpg"

text: "Introduce your content to the world with multiple audio and subtitle tracks, region-specific ads and easy-to-update pre-rolls. Users can switch between audio languages or subtitles directly within the video player, with preferred languages for the user's region displayed automatically. Component-based asset management reduces clutter and simplifies workflows while keeping all related assets connected. Auto-generated transcriptions and translations offer near instantaneous subtitles in any language, making content more usable across global teams and workflows — from product buyer reviews to sales team pitches and even third-party compliance audits."

subtitle_1: Modular asset management 
subimage_1: /assets/img/features/details/modular.png
subtext_1: "Upload and assign audio tracks, subtitle files, and secondary video assets (such as pre-rolls, disclaimers, or teaser trailers) directly to a single video asset. The system’s flexible, modular design supports fully customizable presentation in the client interface, enabling teams to tailor how assets are displayed and managed while maintaining seamless collaboration across projects. Manage language and accessibility assets in one place, streamline updates, and reduce the risk of multiple file conflicts."


subtitle_2: Subtitle generation
subimage_2: /assets/img/features/details/french_subs.png
subtext_2: "Original-language transcripts are created in minutes, enhancing accessibility without heavy costs or time-consuming manual transcription. Once finalized, these transcripts become the foundation for translations, making it easy to generate automated multilingual subtitles. MediaStore integrates a curated selection of powerful next-gen AI/ML services, providing an easy-to-use interface for fast, on-demand subtitle creation and translation. All AI/ML-generated subtitles are clearly flagged in the system, so users know which translations are auto-generated."


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