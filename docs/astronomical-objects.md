---
layout: docs
title: Astronomical Objects
prev_section: database
next_section: system
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

## Common Variables and Methods

The table below lists the available <code
class="option">variables</code> and <code
class="flag">methods</code> that can be used on all astronmical objects.

<div class="mobile-side-scroller">
<table>
  <thead>
    <tr>
      <th>Name and Description</th>
      <th>
        <span class="option">Variable</span> or <span class="flag">Method</span>
      </th>
    </tr>
  </thead>
  <tbody>
    <tr class='setting'>
      <td>
        <p class='name'><strong>Name</strong></p>
        <p class='description'>Returns the name of the object. i.e for the Gilese 1214 system this will be Gilese 1214, the planet will be Gilese 1214 b</p>
      </td>
      <td class="align-center">
        <p><code class="option">.name</code></p>
      </td>
    </tr>
    <tr class='setting'>
      <td>
        <p class='name'><strong>Parent Object</strong></p>
        <p class='description'>Returns the parent object of the current object. This is Not valid for systems. An object may only have one parent but that parent could be of multiple classes.</p>
      </td>
      <td class="align-center">
        <p><code class="option">.parent</code></p>
      </td>
    </tr>
    <tr class='setting'>
      <td>
        <p class='name'><strong>Child Objects</strong></p>
        <p class='description'>Returns a list of child objects of the current class.</p>
      </td>
      <td class="align-center">
        <p><code class="option">.children</code></p>
      </td>
    </tr>
    <tr class='setting'>
      <td>
        <p class='name'><strong>Flags</strong></p>
        <p class='description'>Returns the flags for the current object as a flag object. <a href="">Read more about flags</a></p>
      </td>
      <td class="align-center">
        <p><code class="option">.flags</code></p>
      </td>
    </tr>
  </tbody>
</table>
</div>