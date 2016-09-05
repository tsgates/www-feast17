---
layout: default
title: Accommodations
group: Venue

hotels:
- id: luskin
  name: UCLA Meyer and Renee Luskin Conference Center
  url: http://luskinconferencecenter.ucla.edu/
  address: 425 Westwood Plaza, Los Angeles, CA 90095, USA
  distance: 
  rating:
  reservation:
  rates: 
  deadline: TBD
  map: https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d1904.822615352086!2d-118.44710017759802!3d34.06914894754994!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x80c2bc8602a90341%3A0xd73874d4f138751a!2sUCLA+Meyer+and+Renee+Luskin+Conference+Center!5e0!3m2!1sen!2sus!4v1473056429590
---

# {{ page.title }}

The main conference venue is [UCLA Meyer and Renee Luskin Conference Center](http://luskinconferencecenter.ucla.edu/).
However, there are many other options for accommodation, including AirBnB, available within walking distance or using public transportation.

Below is a list of nearby hotels with special offers for conference attendees.

{% for hotel in page.hotels %}
{% include hotel.html %}
{% endfor %}
