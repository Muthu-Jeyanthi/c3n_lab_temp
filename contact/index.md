---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

## Contact

Inquiries should be directed to [stefanie.liebe@uni-tuebingen.de](mailto:stefanie.liebe@uni-tuebingen.de).

## How to find us

Maria-von-Linden-Str. 6, 4th floor, 72076 Tübingen

<!-- Google Maps Embed -->
<iframe 
  src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2241.109204759983!2d9.06540731591981!3d48.52007837927437!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x4799a3b4efde5a77%3A0xe9e18e0f1e7c8374!2sMaria-von-Linden-Str.%206%2C%2072076%20T%C3%BCbingen!5e0!3m2!1sen!2sde!4v1682767690561!5m2!1sen!2sde" 
  width="600" 
  height="450" 
  style="border:0;" 
  allowfullscreen="" 
  loading="lazy" 
  referrerpolicy="no-referrer-when-downgrade">
</iframe>


{%
  include button.html
  type="email"
  text="stefanie.liebe@uni-tuebingen.de"
  link="stefanie.liebe@uni-tuebingen.de"
%}
{%
  include button.html
  type="phone"
  text="07071 29-80442"
  link="07071 29-80442"
%}

//{%
 // include button.html
  //type="address"
  //tooltip="Our location on Google Maps for easy navigation"
  //link="https://www.google.com/maps"
//%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col2 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col3 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
