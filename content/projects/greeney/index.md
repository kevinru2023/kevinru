---
title: "Greeney"
description: "A carbon footprint tracker that helps users measure, understand, and reduce transportation-related emissions using Next.js, TypeScript, and Flask."
date: "2025-04-01"
showAuthor: true
showDate: true
---

![header](greeney-image.jpg)

## What?

**Greeney** is a carbon footprint tracker that helps users measure, understand, and reduce their transportation-related emissions. It calculates CO₂e from activities such as ridesharing, food deliveries, and flights, providing insights and visualizations to encourage more eco-conscious decisions.  

The application uses **Next.js**, **TypeScript**, and **Tailwind CSS** on the frontend, while the backend API is powered by **Flask** and **Python**.

## Why?

During a period of growing interest in environmental sustainability, me and my friends wanted to create a project that combines data visualization and practical impact. **Greeney** was designed to empower individuals to better understand their transportation footprint and make more informed daily decisions to reduce emissions.

The goal was to create a sleek, accessible tool that not only educates users about their impact but also motivates them to make small, measurable changes for a greener future.

## How?

The app estimates a user’s carbon footprint using the formula:

> **Carbon Emissions (CO₂e)** = *Carbon Intensity (g CO₂/kWh)* × *Energy Consumed (kWh)*  

It leverages **Google APIs** (Distance Matrix, Geocoding, and Gmail OAuth 2.0) to calculate travel distances and authenticate users. The backend Flask API performs emissions calculations and stores user activity data, while the Next.js frontend visualizes trends in CO₂e, kWh, and miles traveled through interactive charts and metrics.  

The interface is built with **ShadCN UI** and styled with **Tailwind CSS**, providing a responsive and visually engaging experience. Together, these technologies create a seamless user experience for tracking and managing personal emissions.

## Github Link

Feel free to check out the project on [Github](https://github.com/kevinru2023/greeney/)
