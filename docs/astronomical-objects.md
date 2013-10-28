---
layout: docs
title: Astronomical Objects
prev_section: ...
next_section: System
permalink: /docs/astro-objects/
---

OECPy structures the objects in a heirarchacal system in the same way the the Open Exoplanet Catalogue. The types of objects and their associations are shown in the next section.

## Objects and Heirarchy

The table below lists the available astronimcal objects in OECPY, along with the <code
class="option">parent</code> and <code
class="flag">children</code> objects they can have.

<div class="mobile-side-scroller">
<table>
  <thead>
    <tr>
      <th>Object Type</th>
      <th>
        <span class="option">Parent</span> and <span class="flag">Child</span>
      </th>
    </tr>
  </thead>
  <tbody>
    <tr class='setting'>
      <td>
        <p class='name'><strong>System</strong></p>
        <p class='description'>A System, contains the coordinates</p>
      </td>
      <td class="align-center">
        <p><code class="option">None</code></p>
        <p><code class="flag">Binary, Star</code></p>
      </td>
    </tr>
    <tr class='setting'>
      <td>
        <p class='name'><strong>Binary</strong></p>
      </td>
      <td class="align-center">
        <p><code class="option">System, Binary</code></p>
        <p><code class="flag">Binary, Star, Planet</code></p>
      </td>
    </tr>
    <tr class='setting'>
      <td>
        <p class='name'><strong>Star</strong></p>
      </td>
      <td class="align-center">
        <p><code class="option">System, Binary</code></p>
        <p><code class="flag">Planet</code></p>
      </td>
    </tr>
    <tr class='setting'>
      <td>
        <p class='name'><strong>Planet</strong></p>
      </td>
      <td class="align-center">
        <p><code class="option">Binary, Star</code></p>
        <p><code class="flag">None</code></p>
      </td>
    </tr>
  </tbody>
</table>
</div>