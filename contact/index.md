---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Our lab is part of the Department of Molecular Medicine at the University of South Florida Morsani College of Medicine in beautiful Tampa, Florida. Feel free to contact us for job opportunities, potential collaborations, reagents, and more! 

{%
  include button.html
  type="email"
  text="krishnareddy@usf.edu"
  link="krishnareddy@usf.edu"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://maps.app.goo.gl/VfksCz65UiqrEgTBA"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/USF.jpg"
  caption="University of South Florida"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/Tampa.jpg"
  caption="Tampa, FL"
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
