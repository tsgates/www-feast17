---
layout: default
title: Accommodations
group: Venue

hotels:
- id: luskin
  name: UCLA Meyer and Renee Luskin Conference Center
  deadline: July 20, 2017
  rates: [$240 plus tax single, $240 plus tax double, 35$/day charge for each additional person beyond double occupancy]
  amenities: [Free WiFi]
  address: 425 Westwood Plaza, Los Angeles, CA 90095, USA
  url: http://luskinconferencecenter.ucla.edu/
  phone: +1 (855) LCC-UCLA / +1 (855) 522-8252
  distance: Conference hotel
  reservation-info: More info and reservation code will be available soon
  reservation-link: http://luskinconferencecenter.webhotel.microsdc.us/bp/search_rooms.jsp?corporateId=%20&groupCode=TO-BE-ASSIGNED&promoCode=
  map: https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d1904.822615352086!2d-118.44710017759802!3d34.06914894754994!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x80c2bc8602a90341%3A0xd73874d4f138751a!2sUCLA+Meyer+and+Renee+Luskin+Conference+Center!5e0!3m2!1sen!2sus!4v1473056429590
  note: All reservations must be guaranteed with a major credit card and accompanied by a first night room deposit.

- id: angeleno
  name: Hotel Angeleno
  deadline: July 31, 2017
  rates: [$199 plus tax single, $199 plus tax double]
  amenities: [Free WiFi, Free parking, Free shuttle within 3-mile radius]
  address: 170 N Church Ln, Los Angeles, CA 90049
  url: http://www.hotelangeleno.com/
  phone: +1 (310) 476-6411
  distance: 2 miles
  <!-- rating: 3.5 stars (4.0/5 hotels.com review) -->
  rating: 3.5
  reservation-info: More info and reservation code will be available soon
  reservation-link: https://bookings.ihotelier.com/Hotel-Angeleno-Los-Angeles/bookings.jsp?arrivaldate=08/20/2017&HotelID=76958&DateOut=8/25/2017&DateIn=08/20/2017&LanguageID=1&Rooms=1&departuredate=8/25/2017
  map: https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3304.821030037545!2d-118.4662930833109!3d34.074101821638116!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x80c2bcc0b6c77eb7%3A0xfa7b1be3d9922e2e!2sHotel+Angeleno!5e0!3m2!1sen!2sus!4v1474581392575
  note: All reservations must be guaranteed by a valid credit card at the time of reservation.
---

# {{ page.title }}

The main conference venue is [UCLA Meyer and Renee Luskin Conference Center](http://luskinconferencecenter.ucla.edu/).
However, there are many other options for accommodation, including AirBnB, available within walking distance or using public transportation.

Below is a list of conference hotels:

{% for hotel in page.hotels %}
{% include hotel.html %}
{% endfor %}

Note that the conference will provide breakfast and lunch.
