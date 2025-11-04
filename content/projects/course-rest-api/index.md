---
title: "Course REST API"
description: "A FastAPI service that provides Oregon college course articulation data by scraping transfer credit information from OSU's admissions pages. Data is updated weekly to minimize requests to college websites"
date: "2025-06-01"
showAuthor: true
showDate: true
---

![header](course-rest-api-image.jpg)

## What?

A **FastAPI** service that provides Oregon college course articulation data by scraping transfer credit information from OSU's admissions pages. Data is updated weekly to minimize requests to college websites.

## Why?

During my sophomore year of college, the App Club wanted to create a chrome extension that would allow OSU students to get more information out of their course planner. This API was created in order to provide information about what courses have a direct community college equivalent to show in the students course planner.

## How?

This project utilizes python in order to use libraries such as beautiful soup to gather information from Oregon State University websites that contain a list of courses from various community colleges that have a direct OSU course equivalent. Once this information is gathered I utilized some regex expressions to parse the data (as the data was stored in a pre tag) and output this information in an API. The API service utlizies FastAPI to create an easy to use REST API that contains easy to understand documentation. Finally, in order to make it easy to spin up this API, I put everything into a docker file to allow for easy deployment of the API service.


## Github Link
Feel free to check out the project on [Github](https://github.com/kevinru2023/course-rest-api/)