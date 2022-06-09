---
layout: ../../layouts/project.astro
title: Palmer
subtitle: School Website
tag: portfolio project
date: 2022-06-07
image: /images/chapter-01.jpg
author: Amy Henke
description: School Website | Web Developer Portfolio
subheading: A school website built using Silverstripe, SCSS and PHP.
technical: PHP, MySQL, HTML5, Silverstripe, MAMP, CSS3, SCSS, Gulp, NPM, Javascript, JQuery, Plesk, Adobe Illustrator, InDesign, Photoshop
design: /assets/PalmerDesign.pdf
website: https://www.tpc.academy/
---

Similarly to Chosen Hill, this website is also a multi-homepage site. Dropdown selectors have been added cross the CMS, specifically to dataobjects, to ensure that only information relevant to that part of the school is shown. This was the case for the _Celebrating Success_ module which usually requires the same data across the entire website so I adapted the PHP to seperate them.

A unique feature to this site is the 'School Ambassadors' section which other clients have since requested. The code has therefore been added to our core code base. This section consists of a data object for each student, with the various information and image. It has been made using only CSS as to avoid issues for users on old computers (common in schools). This was built using radio inputs. Typically, we try to only use JavaScript for visual features and aim to use CSS only for navigational purposes.
