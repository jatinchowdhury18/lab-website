---
title: Contact
nav:
  order: 6
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Please get in touch with us if you are interested in research
collaboration or studying with us in the future!

{%
  include button.html
  type="email"
  text="mrau@mit.edu"
  link="mrau@mit.edu"
%}
{%
  include button.html
  type="phone"
  text="(617) 253-3210"
  link="+1-617-253-3210"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://www.google.com/maps/place/MIT+Building+W18/@42.357895,-71.0984224,17z/data=!3m1!4b1!4m6!3m5!1s0x89e37bb4d1323815:0xa7b20397d97e1856!8m2!3d42.3578911!4d-71.0958475!16s%2Fg%2F11l2p57m28"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/W18.jpg"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/studio_b_2.png"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

<!--{% capture col1 %}
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
{% endcapture %}-->

<!--{% include cols.html col1=col1 col2=col2 col3=col3 %}-->
