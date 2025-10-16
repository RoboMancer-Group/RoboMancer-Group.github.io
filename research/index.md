---
title: Research
nav:
  order: 1
  tooltip: Learn about our research
---
# {% include icon.html icon="fa-solid fa-gears" %}Research

<!-- ........................................... -->
{% capture text %}

Description for dexterous hand.

{%
  include button.html
  link="dexterous-hand"
  text="Dexterous Hand"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.svg"
  link="dexterous-hand"
  title="Dexterous Hand"
  text=text
%}

<!-- ........................................... -->
{% capture text %}

Description for exoskeleton.

{%
  include button.html
  link="exoskeleton"
  text="Exoskeleton"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.svg"
  link="exoskeleton"
  title="Exoskeleton"
  text=text
  flip=true
%}
<!-- ........................................... -->

{% capture text %}

Description for humanoid robot.

{%
  include button.html
  link="humanoid-robot"
  text="Humanoid Robot"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.svg"
  link="humanoid-robot"
  title="Humanoid Robot"
  text=text
%}
<!-- ........................................... -->

{% capture text %}

Description for wheeled robot.

{%
  include button.html
  link="wheeled-robot"
  text="Wheeled Robot"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.svg"
  link="wheeled-robot"
  title="Wheeled Robot"
  text=text
  flip=true
%}


{% include section.html %}
