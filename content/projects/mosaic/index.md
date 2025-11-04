---
title: "Mosaic"
description: "A mobile group travel planner built with React Native, Flask, and ElasticSearch that personalizes trip recommendations using vector-based similarity search."
date: "2025-10-01"
showAuthor: true
showDate: true
---

![header](mosaic-image.jpg)

## What?

**Mosaic** is a group travel planning app that helps friends plan their next trip together, all in one place. It combines a custom recommendation system, interactive mapping, and collaborative planning features to create a seamless mobile experience.  

The app is built with **React Native** on the frontend, while the backend leverages **Flask**, **ElasticSearch**, and **Supabase** to deliver personalized, data-driven recommendations.

## Why?

Mosaic started as an attempt to solve a common frustration: planning trips with friends often meant juggling group chats, Google Docs, and random links. We wanted to create something that could *feel intelligent*, a single app that understands what your group enjoys and curates destination ideas to match those shared interests.

By blending vector-based recommendation systems with familiar mobile UX patterns, Mosaic transforms group trip planning into a more social and effortless experience.

## How?

The backend is powered by **ElasticSearch** and **OpenAI embeddings**, which together create a custom recommendation engine. Each user and location is represented as a vector, allowing Mosaic to suggest new places based on semantic similarity to past preferences.

The app integrates several APIs:
- **Google Places API** for fetching real-world location details.
- **Google Maps API** for trip visualization.
- **Supabase** for authentication and data management.
- **OpenAI API** for generating and refining vector embeddings.

The frontend, built in **React Native** with **TypeScript** and styled using **Expo** and **Tailwind**, provides a clean, modern mobile interface. The experience is optimized for collaboration — users can easily create shared itineraries, explore personalized location feeds, and view travel routes with just a few taps.

Mosaic is bundled in a single mobile app powered by an AI-enhanced backend, creating a truly end-to-end group travel companion.

## Github Link

Feel free to check out the project on [Github](https://github.com/kevinru2023/Mosaic)
