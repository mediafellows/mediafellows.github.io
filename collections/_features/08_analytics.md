---
layout: features
title: Comprehensive Analytics
identifier: analytics
description: Boost your sales initiatives with detailed, actionable, real-time analytics. Review in MediaStore, or delivered to your current CRM or third party analysis tools. 
icon: /assets/img/icons/chart-bar-solid.svg
image: /assets/img/features/analytics.jpg
header_image: "/assets/img/bg/features.jpg"

text: "Never miss an opportunity to drive growth. All activity is captured fast using metrics which can be reviewed for any time range and filtered granularly for a full profile of metrics includes log-in, page views, video screening, duration, downloads and more. We track registered users as well as external email addresses and even the IP of those who haven’t signed up to your system, so you can review every single click."

subtitle: Unlock Business Insights
subimage: /assets/img/features/details/analytics-screen.png
subtext_1: "You can review this data in a range of ways, including the MediaStore dashboard, weekly email reports, or delivered directly to your CRM or analytics tool. Review our one-stop dashboards for a glance at overall activity and the most viewed titles and videos, or dive into deep links to any object's dedicated analytics page in order to review activity more specifically - e.g. which titles a specific user viewed or who watched the most minutes of a specific screener." 
subtext_2: "Excel exports provide deeper insights, down to individual view traces, for further offline analysis and processing. Sign up for the platform's analytics reports for a weekly email summarizing key activity, including week-on-week trends. For a more specific view of activity made by clients who are allocated to a specific sales agent, a separate email report is available, as well as an optional spreadsheet attachment of video views segmenting clients by responsible sales agent. Integrate with your current CRM systems like Salesforce or third-party services like Google Analytics or Hotjar via our advanced APIs."

example_text: Take a look at our projects showcasing our comprehensive analytics
example_link: projects#itvstudios

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
        <div class="service-details mb-40">
            <h3>{{ page.subtitle }}</h3>
            <p>{{ page.subtext_1 }}</p>
        </div>
    </div>
    <div class="col-xl-6 col-lg-12">
        <div class="s-details-img mb-30">
          <a href="{{ page.subimage }}" class="view">
            <img src="{{ page.subimage }}" class="border" alt="{{ page.title }}">  
          </a>
        </div>
    </div>
</div>
<div class="row">
    <div class="col-md-12">
        <div class="service-details mb-40">
            <p>{{ page.subtext_2 }}</p>
        </div>
    </div>
</div>
