---
layout: homepage
title: Home
---

<section class="profile" aria-labelledby="profile-name">
  <img class="profile-photo" src="{{ site.avatar | relative_url }}" alt="{{ site.title }} portrait" width="1070" height="940">
  <div class="profile-details">
    <h1 id="profile-name">{{ site.title }}</h1>
    <p class="profile-position">{{ site.position }}</p>
    <p class="profile-affiliation">{{ site.department }}<br><a href="{{ site.affiliation_link }}">{{ site.affiliation }}</a></p>
    <address class="profile-contact">
      {{ site.office }}<br>
      {{ site.address }}<br>
      <a href="mailto:hongseok@iastate.edu">hongseok@iastate.edu</a>
    </address>
  </div>
</section>

<p class="job-market-notice"><strong>I am on the 2026-2027 academic job market</strong></p>

<p class="bio">I am a sixth-year Ph.D. Candidate in Economics at Iowa State University. Before beginning my Ph.D., I received my bachelor's and master's degrees from <a class="quiet-link" href="https://www.hanyang.ac.kr/">Hanyang University</a> in Seoul, South Korea.</p>

<p class="bio">My research interests are in <strong>macroeconomics and public economics</strong>, with a particular focus on aging economy. I study how demographic change and public policy shape household decisions and broader macroeconomic outcomes. More information is available on my <a href="{{ '/research' | relative_url }}">research page</a>.</p>

<p class="bio">My job market paper, <a href="{{ site.job_market_paper_link | relative_url }}" download aria-label="Download job market paper PDF"><strong>The Intergenerational Welfare Cost of Social Security Insolvency</strong></a>, examines which generations are most harmed by Social Security insolvency and why.</p>
