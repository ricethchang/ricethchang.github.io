---
layout: profiles
permalink: /people/
title: people
description: members of the lab or group
nav: true
nav_order: 7
display categories: [PI, Current members, Alumni]

# categorise people in my lab
categories:
 - name: "Principal Investigator"
   id: "pi"
   description: "Lab principle investigator"
 - name: "Current Students"
   id: "Current"
   description: "Lab students atm"
 - name: "Alumni"
   id: "alumni"
   description: "Friends from thereafter, graduated students, and staffs"
profiles:
  # if you want to include more than one profile, just replicate the following block
  # and create one content file for each profile inside _pages/
  - category: "pi"
    align: right
    image: prof_pic.jpg
    content: about_pi.md
    image_circular: true # crops the image to make it circular
    more_info: >
      <p>Dr Tao-Ho Chang (Dr Rice)</p>
      <p>email: thchang@nchu.edu.tw</p>
  - category: "current"
    align: left
    image: prof_pic.jpg
    content: about_einstein.md
    image_circular: false # crops the image to make it circular
    more_info: >
      <p>555 your office number</p>
      <p>123 your address street</p>
      <p>Your City, State 12345</p>
  - category: "alumni"
    align: left
    image: prof_pic.jpg
    content: about_einstein.md
    image_circular: false # crops the image to make it circular
    more_info: >
      <p>555 your office number</p>
      <p>123 your address street</p>
      <p>Your City, State 12345</p> 
---
