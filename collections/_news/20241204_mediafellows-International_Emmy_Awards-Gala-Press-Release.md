---
layout: news
header_image: "/assets/img/bg/news.jpg"
title: mediafellows at the 52nd Annual International Emmy® Awards Gala
release_date: 04.12.2024
image: /assets/img/news/iEmmys/20241204_mediafellows-International_Emmy_Awards-Gala-Press-Release_1.png
image_border:
image_credits: mediafellows' representatives on the red carpet at the 52nd International Emmy® Awards
description: Torsten Graf-Oettel, José Sanches, Mark Bernado and Dr. Holger Hendel represent mediafellows and Pixelogic on the 52nd International Emmy® Gala red carpet. As proud sponsors of the International Emmy® Awards, mediafellows extends its gratitude once again for the opportunity to support and honor outstanding achievements in international television.
images_path: "/assets/img/news/iEmmys/"
images: 
 - "20241204_mediafellows-International_Emmy_Awards-Gala-Press-Release_2.png"
 - "20241204_mediafellows-International_Emmy_Awards-Gala-Press-Release_3.jpg"
 - "20241204_mediafellows-International_Emmy_Awards-Gala-Press-Release_4.jpg"
 - "20241204_mediafellows-International_Emmy_Awards-Gala-Press-Release_5.jpg"
 - "20241204_mediafellows-International_Emmy_Awards-Gala-Press-Release_6.png"
 - "20241204_mediafellows-International_Emmy_Awards-Gala-Press-Release_7.jpg"
 - "20241204_mediafellows-International_Emmy_Awards-Gala-Press-Release_8.jpg"

---

<div class="row">
    <div class="col-xl-4 col-lg-4 col-md-12">
        <div class="s-details-img mb-30">
          {% if page.image %}
          <a href="{{ page.image }}" class="view">
            <img src="{{ page.image }}" alt="{{ page.title }}">  
          </a>
          {% endif %}
          {% if page.image_credits %}
          <p>{{ page.image_credits }}</p>
          {% endif %}
        </div>
    </div>
    <div class="col-xl-8 col-lg-8 col-md-12">
        <div class="service-details mb-40">
          <div class="meta-info">
              <ul>
                  <li class="posts-time">{{page.release_date | date_to_long_string}}</li>
              </ul>
          </div>
          <br>
          <p>{{ page.description }}</p>
          <p>
The ongoing partnership between the International Academy of Television Arts & Sciences and mediafellows continues to be a tremendous source of pride, so we were delighted to see our name prominently featured in a glossy full-page spread in the accompanying awards magazine (shown in the gallery below).
          </p>
          <p>
Our heartfelt thanks to everyone at the International Emmy® Awards organization for making this spectacular event possible. The team at mediafellows and our guests enjoyed an unforgettable evening, from the red carpet to the gala after-party.  
          </p>
        </div>
    </div>
</div>
<div class="row">
    <div class="col-xl-12 col-lg-12">
        <div class="service-details mb-40">
          <p>
Congratulations to all the <a href="https://www.iemmys.tv/international-emmy-awards/nominees/" target="blank">winners and nominees</a> at the 52nd Annual International Emmy® Awards!
          </p>
          <hr>
          <p>
mediafellows founder <strong>Torsten Graf-Oettel</strong> remarked, <i>“Building on last year’s memorable debut as sponsors of the International Emmy® Awards, mediafellows was honored to be part of this prestigious event once more. Our shared commitment with the Academy to celebrating excellence in global entertainment media makes this partnership especially meaningful, and we’re deeply grateful for another incredible evening filled with inspiration and celebration.”</i>
          </p>
          <hr>
        </div>
    </div>
</div>

<div class="row">
    <div class="col-xl-12 col-lg-12">
        <div class="news-images owl-carousel">
          {% for img in page.images %}
            {% assign src = page.images_path | append: img %}
            <div class="col-sm-12">
              <a href="{{ src }}" class="view">
                <img src="{{ src }}">
              </a>
            </div>
          {% endfor %}
        </div>
        <hr>
    </div>
</div>

<div class="row">
    <div class="col-xl-12 col-lg-12">
        <div class="service-details mb-40">
          <p>
<strong>For more information on how mediafellows can support your organisation with website solutions, please contact the team at <a href="mailto:info@mediafellows.com">info@mediafellows.com</a></strong>
          </p>
          <hr>
          <p>
<strong>ABOUT THE INTERNATIONAL ACADEMY OF TELEVISION ARTS & SCIENCES</strong>
<br>
The International Academy of Television Arts & Sciences is a membership-based organization comprised of leading media and entertainment figures from over 60 countries and 500 companies from all sectors of television including internet, mobile and technology. The Academy’s yearly schedule of events includes the prestigious International Emmy® Awards held in New York and a series of industry events such as Academy Day, The International Emmy® World Television Festival and Panels on substantive industry topics. The International Academy of Television Arts & Sciences recognizes excellence in television produced outside of the United States with the prestigious Emmy® Award. Currently celebrating programming across varied areas including Arts Programming, Current Affairs, Comedy, Documentary, Drama Series, News, Non-Scripted Entertainment, Short-Form Series, Telenovela, and TV Movie/Mini-Series, it also recognizes excellence in Performances and Kids programming. For more information go to <a href="https://www.iemmys.tv/" target="blank">www.iemmys.tv</a>
          </p>
        </div>
    </div>
</div>