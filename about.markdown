---
layout: page
title: About
permalink: /about/
---

<h2 id="intro">Introduction</h2>

Christian Life Church is an independent, conservative, evangelical church located at 207 Broad St in the Village of Waverly, New York. The main entrance is at the corner of Clark St and Broad St. We are in the old Capitol Theater. We share our building with [The Bridge of the Penn-York Valley Churches](https://www.thevalleybridge.com/){:target="_blank"}.

Our worship services start at 11:05 AM and last just under one hour. We sing both contemporary music and traditional hymns. We take Communion together on the first Sunday of each month. We meet for lunch and fellowship most months on the third Sunday of the month after the morning service. Doug Paul, our current Council Chaiman, leads our services. 

<h2 id="leadership">Leadership</h2>

We govern ourselves as a congregational church. Our members annually elect representatives to our Prayer Council. We hold multiple congregational business meetings each year. The current membership of our Council is as follows:
* Stacy Garrity
* Ron Hunsinger
* Doug Paul (Council Chairman)
* Kim Paul (Secretary and Treasurer)
* Maria Richman

<h2 id="contact">Contact Us</h2>

Here are various ways to contact us.<br><br>

{%- if site.address -%}
  **Address:**  
  {{ site.address | escape }}<br><br>
{%- endif -%}

{%- if site.phone -%}
  **Phone:**  
  {{ site.phone | escape }}<br><br>
{%- endif -%}

{%- if site.email -%}
  **Email:**  
  <a href="mailto:{{ site.email }}">{{ site.email }}</a><br><br>
{%- endif -%}

**Contact Form:** 

<form action="https://api.staticforms.dev/submit" method="POST">
    <input type="hidden" name="apiKey" value="sf_6f312597h23h24ld4jd14dc8" />
    <input type="hidden" name="redirectTo" value="https://clcwaverly.org/thank-you.html/" />
    <label for="name">Name</label><br>
    <input name="Name" id="name" type="text" /><br><br>
    <label for="email">Email Address (required)</label><br>
    <input name="Email" required id="email" type="email" /><br><br>
    <label for="message">Message (required)</label><br>
    <textarea id="message" name="Message" rows="7" cols="30"></textarea><br><br>
    <button type="submit">Submit</button><br><br>
</form>
