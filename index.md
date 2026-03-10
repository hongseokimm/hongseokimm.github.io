---
layout: homepage
title: Home
---

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

<p class="bio">I am a fifth-year Ph.D. Candidate in Economics at Iowa State University. Before beginning my Ph.D., I received my bachelor's and master's degrees from <a href="https://www.hanyang.ac.kr/">Hanyang University</a> in Seoul, South Korea.</p>

<p class="bio">My research focuses on macroeconomics, demographic change, and family economics. I study how retirement behavior, fertility decisions, and related household choices shape aggregate outcomes and the distributional effects of public policy.</p>

<p class="bio">My current work includes a job market paper on retirement and Social Security financing, and a second project on ambiguity aversion and fertility decisions. Additional details are available on the <a href="{{ '/research' | relative_url }}">research page</a>, and my CV is available <a href="{{ site.cv_link | relative_url }}">here</a>.</p>

<hr class="content-divider">
