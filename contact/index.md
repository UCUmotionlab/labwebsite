---
title: Contact
nav_title: Contact
lang: en
ref: contact
nav:
  order: 4
  tooltip: How to reach us
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

We would love to hear from you!

{%
  include button.html
  type="email"
  text="pablo.iturralde@ucu.edu.uy"
  link="pablo.iturralde@ucu.edu.uy"
%}
{%
  include button.html
  type="email"
  text="enrique.ferreira@ucu.edu.uy"
  link="enrique.ferreira@ucu.edu.uy"
%}

{% include section.html %}

## Location

Universidad Católica del Uruguay
Facultad de Ingeniería y Tecnologías
Av. 8 de Octubre 2738
Montevideo, Uruguay

{% include section.html %}

## Our Team

{% include list.html data="members" component="portrait" filters="role: pi" %}
