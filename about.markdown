---
layout: page
title: About
permalink: /about/
---

<h2 id="intro">Introduction</h2>

Christian Life Church Waverly is an independent, conservative, evangelical church located at 207 Broad St in the Village of Waverly, New York. The main entrance is at the corner of Clark St and Broad St. We are in the old Capitol Theater. We share our building with [The Bridge of the Penn-York Valley Churches](https://www.thevalleybridge.com/){:target="_blank"}.

*add details such as comments about music, length of service, Communion frequency, etc.*

<h2 id="leadership">Leadership</h2>

*information to be added: list Council members?*
*information to be added: bio?*

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
