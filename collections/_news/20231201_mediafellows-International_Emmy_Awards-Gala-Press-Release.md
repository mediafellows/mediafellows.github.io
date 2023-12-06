---
layout: news
header_image: "/assets/img/bg/news.jpg"
title: mediafellows goes to the 51st Annual International Emmy® Awards Gala
release_date: 01.12.2023
image: /assets/img/news/20231201_mediafellows-International_Emmy_Awards-Gala-Press-Release_1.jpeg
image_border:
image_credits: mediafellows' representatives on the red carpet at the 51st International Emmy® Awards
description: Dr. Holger Hendel, Jose Sanchez, Torsten Graf-Oettel and his daughter Leni Graf representing mediafellows on the 51st International Emmy® Gala. As proud sponsors of the International Emmy® Awards, mediafellows extends heartfelt appreciation for the opportunity to take part in this prestigious event. 
images_path: "/assets/img/news/iEmmys/"
images: 
 - "20231201_mediafellows-International_Emmy_Awards-Gala-Press-Release_2.jpg"
 - "20231201_mediafellows-International_Emmy_Awards-Gala-Press-Release_3.jpg"
 - "20231201_mediafellows-International_Emmy_Awards-Gala-Press-Release_7.jpg"
 - "20231201_mediafellows-International_Emmy_Awards-Gala-Press-Release_5.jpg"
 - "20231201_mediafellows-International_Emmy_Awards-Gala-Press-Release_8.jpg"
 - "20231201_mediafellows-International_Emmy_Awards-Gala-Press-Release_6.jpg"
 - "20231201_mediafellows-International_Emmy_Awards-Gala-Press-Release_4.jpg"

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
We were delighted at the prominent showcase of our sponsorship and extremely proud to attend in support of the Academy, which has proved to be not only a highly esteemed organization but a treasured partner to us.
          </p>
          <p>
The team at mediafellows enjoyed an unforgettable experience, from the red carpet to the gala after-party! 
          </p>
        </div>
    </div>
</div>
<div class="row">
    <div class="col-xl-12 col-lg-12">
        <div class="service-details mb-40">
          <p>
Many thanks to all at the International Emmy® Awards organization that make the gala such a celebrated event year after year, and our sincere congratulations to all <a href="https://www.iemmys.tv/international-emmy-awards/nominees/" target="blank">winners and nominees</a> at the 51st Annual International Emmy® Awards. Cheers!
          </p>
          <hr>
          <p>
mediafellows founder <strong>Torsten Graf-Oettel</strong> added, <i>“mediafellows is highly proud to be a first-time sponsor of the International Emmy Awards. Many thanks to the International Academy of Television Arts & Sciences for such an amazing evening — it was an experience to treasure!”</i>
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