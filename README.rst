Django Day Copenhagen 2024 website
==================================

WIP: Until the event is announced, this is where we can work on the new website

Live version: https://2024.djangoday.dk


Local development
-----------------

This website is developed with `Hugo (a static site generator) <https://gohugo.io/>`__.

Why not Django? Django is our favorite web framework for database-driven solutions.
But when making an event where we want the whole site to be archived forever, it's a
great advantage to be able to have a tech stack with nothing more than an HTTP server
serving a static website.

Development guide
-----------------

This guide is quite bad currently and we know. Please reach out if you are interested
in developing something for the website.

To download and install Hugo on Ubuntu/Debian, use the following commands::

  wget -O hugo.deb https://github.com/gohugoio/hugo/releases/download/v0.125.4/hugo_extended_0.125.4_linux-amd64.deb
  sudo apt install ./hugo.deb

You can install and run Hugo on other systems, too, see their `list of releases <https://github.com/gohugoio/hugo/releases/download/>`__

After installing Hugo, you can view the site on your local laptop, by running the command ``hugo server`` directly in the root folder of this repository.
