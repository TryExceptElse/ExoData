---
layout: docs
title: System Object
prev_section: astro-objects
next_section: binary
permalink: /docs/system/
---

The System object is the base of all planet-star systems. It contains the coordinates to the system along with the distance. A full list of methods and variables are given in the table.

<div class="note">
  <h5>Tip: all values are quanity objects and can be rescaled</h5>
  <p>
    Whilst the units given in the table are the default returned, all values are returned as a quantity object with a unit. Changing the unit is then as easy as <code>myvar.rescale(aq.M_s)</code>.<br>
    <em><a href="../units/">Find out more about units</a></em>
  </p>
</div>

The table below lists the available <code
class="option">variables</code> and <code
class="flag">methods</code> of the System object.

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
        <p class='name'><strong>Right Asse</strong></p>
        <p class='description'>A System, contains the coordinates</p>
      </td>
      <td class="align-center">
        <p><code class="option">None</code></p>
        <p><code class="flag">Binary, Star</code></p>
      </td>
    </tr>
  </tbody>
</table>
</div>