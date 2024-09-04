---
title: "Versioning data in Django"
date: 2024-08-12T10:45:00+02:00
talk_date: 2024-10-04T09:45:00+02:00
talk_by: "Joseph Victor Zammit"
img_name: "joseph.jpeg"
layout: "single"
remote: false
stage: true
linkedin_url: "https://www.linkedin.com/in/jvzammit"
fediverse: "@jvzammit@fosstodon.org"
fediverse_url: "https://fosstodon.org/@jvzammit"
twitter: "jvzammit"

description: "Versioning data in Django"
published: true
type: "talk"

# youtube_id: "lF1eCH7p5qw"

# slides: "https://docs.google.com/presentation/d/1OTI--ZQLLR3N8ixl4OktEwbXfiau_0BNXicl_3j5uYc/edit?usp=sharing"
# notes: "andrew.jpeg"
---
What does "versioning" mean? It means tracking the evolution of a specific record in our database. This talk is about ways to version data in a Django project. The aim is to create a balance between two, sometimes opposing goals. First goal is to have an easy-to-understand data model for product and engineering. The second is for our code to make efficient use of the database.

## Example scenario:

* Your company sells widgets. We track orders in the `Order` model and customers in the `Customer` model.
* Management uses a report to show locations for orders delivered for customers.
* A customer with past orders wants to update their address. How to handle this without breaking the report just described?
* What performance considerations come into play?
* What does the Django ecosystem offer? Any alternatives? And why?

## About Joseph

I’m Joseph. Or “Joe” in short. I am in software engineering since the ‘00s. Working professionally since ‘06.

Most of the time my roles were “backend”. Where working with data and relational databases is a key part of backend.

From ‘08 onwards I worked a lot with Python. And the framework I worked with most is Django.

Website: [https://www.untangled.dev/](https://www.untangled.dev/)

