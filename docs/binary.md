---
layout: docs
title: Binary Object
prev_section: system
next_section: star
permalink: /docs/binary/
---

The Binary object can hold star and binay objects. This allows the representation of multiple stars systems accuratly.

Binaries inheirt variables from the system class and can hold the orbital parameters of the binary.

The table below lists the available <code
class="option">variables</code> and <code
class="flag">methods</code> of the Binary object.

<div class="mobile-side-scroller">
<table>
  <thead>
    <tr>
      <th>Object Type</th>
      <th>
        <span class="option">Variable</span> or <span class="flag">Method</span>
      </th>
    </tr>
  </thead>
  <tbody>
    <tr class='setting'>
      <td>
        <p class='name'><strong>Right Ascension</strong></p>
      </td>
      <td class="align-center">
        <p><code class="option">.ra</code></p>
      </td>
    </tr>
    <tr class='setting'>
      <td>
        <p class='name'><strong>Declination</strong></p>
      </td>
      <td class="align-center">
        <p><code class="option">.dec</code></p>
      </td>
    </tr>
    <tr class='setting'>
      <td>
        <p class='name'><strong>Distance</strong></p>
        <p class='description'>To the system (parsecs)</p>
      </td>
      <td class="align-center">
        <p><code class="option">.d</code></p>
      </td>
    </tr>
    <tr class='setting'>
      <td>
        <p class='name'><strong>Child Stars and Binaries</strong></p>
        <p class='description'>List of stars and binaries within the binary</p>
      </td>
      <td class="align-center">
        <p><code class="option">.stars</code></p>
      </td>
    </tr>
  </tbody>
</table>
</div>