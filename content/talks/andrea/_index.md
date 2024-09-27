---
title: "Hypermedia driven maps"
draft: false
date: 2024-08-12T10:45:00+02:00
talk_date: 2024-10-04T13:35:00+02:00
talk_by: "Andrea Guerra"
img_name: "andrea.jpeg"
layout: "single"
remote: false
stage: true
fediverse: "@andywar65@opalstack.social"
fediverse_url: "https://opalstack.social/@andywar65"
description: "Hypermedia driven maps"
type: "talk"
---

Using Django, Leaflet.js and HTMX to seamlessly manage a CRUD geolocation app. In Hypermedia Driven Applications, content and user interface share the same data structure: HTML. Some JavaScript "islands of interactivity" can coexist with the HDA. In our case the "island" is a Leaflet Map, initialized just once. HTML fragments sent by server do all the work, transporting data, links, state, triggering events, everything without reloading the page.

The code example for the talk can be found at [https://github.com/andywar65/map_swap_example](https://github.com/andywar65/map_swap_example).
