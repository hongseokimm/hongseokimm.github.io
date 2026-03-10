---
layout: homepage
title: Home
---

<div class="profile-wrap">
  <table class="profile-table">
    <tr>
      <td class="photo-cell">
        <img src="{{ site.avatar | relative_url }}" alt="{{ site.title }} portrait">
      </td>
      <td>
        <p class="profile-info">{{ site.title }}</p>
        <blockquote>
          <p class="bio">
            {{ site.position }}<br>
            {{ site.department }}<br>
            <a href="{{ site.affiliation_link }}">{{ site.affiliation }}</a><br><br>
            {{ site.office }}<br>
            {{ site.address }}<br><br>
            <a href="mailto:hongseok@iastate.edu">hongseok@iastate.edu</a>
          </p>
        </blockquote>
      </td>
    </tr>
  </table>
</div>

<p class="bio">I am a fifth-year Ph.D. Candidate in Economics at Iowa State University. Before beginning my Ph.D., I received my bachelor's and master's degrees from <a class="quiet-link" href="https://www.hanyang.ac.kr/">Hanyang University</a> in Seoul, South Korea.</p>

<p class="bio">My research interests are in <strong>macroeconomics</strong>, with a particular focus on retirement and Social Security. I am especially interested in how retirement behavior and Social Security policy shape household decisions and broader macroeconomic outcomes.</p>

<p class="bio">My current work studies retirement and Social Security financing. Additional details are available on the <a href="{{ '/research' | relative_url }}">research page</a>, and my CV is available <a href="{{ site.cv_link | relative_url }}">here</a>.</p>

<hr class="content-divider">
