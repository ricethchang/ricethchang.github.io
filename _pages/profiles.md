---
layout: profiles
permalink: /people/
title: Members
description: The wee PSRLab mates
nav: true
nav_order: 7
display categories: [Principal Investigator, Current Members, Alumni]

# categorise people in my lab
categories:
  - name: "Principal Investigator"
    id: "pi"
    description: "Lab principle investigator"
  - name: "Current Members"
    id: "current"
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
    image: Fusarium.png
    content: member_jeff_huang.md
    image_circular: false # crops the image to make it circular

  - category: "current"
    align: left
    image: Fusarium.png
    content: member_wen_ting_tseng.md
    image_circular: false # crops the image to make it circular

  - category: "alumni"
    align: right
    image: Fusarium.png
    content: alumni_jun_ze_zheng.md
    image_circular: false # crops the image to make it circular
    more_info: >

  - category: "alumni"
    align: right
    image: Arabidopsis.png
    content: alumni_chia_cheng_hsieh.md
    image_circular: false # crops the image to make it circular
    more_info: >
---
