
# Restaurant Reviews App Stage 1

## Table of Contents

* [Description](#description)
* [Instructions and How to run](#instructions-and-how-to-run)
* [Leaflet.js and Mapbox](#leafletjs-and-Mapbox)
* [Note about ES6](#note-about-es6)

## Description

A starter code has been provided from Udacity. The code has a lot of issues. It’s barely usable on a desktop browser, much less a mobile device. It also doesn’t include any standard accessibility features, and it doesn’t work offline at all. I need take a static design that lacks accessibility and convert the design to be responsive on different sized displays and accessible for screen reader use. You will also add a service worker to begin the process of creating a seamless offline experience for your users.

## Instructions and How to run

1.**[Run it Live](https://amazingbkb.github.io/Restaurant-Reviews-App/)**

2.To run it locally, download or clone this repository.

In this folder, start up a simple HTTP server to serve up the site files on your local computer. Python has some simple tools to do this. For most people, it's already installed on your computer.

Check if python is installed in your computer by typing python -V or py -V. If you have Python 2.x, spin up the server with `python -m SimpleHTTPServer 8000` (or some other port, if port 8000 is already in use). For Python 3.x, you can use `python3 -m http.server 8000`. If you don't have Python installed, navigate to Python's [website](https://www.python.org/) to download and install the software. Visit the site http://localhost:8000.

## Leaflet.js and Mapbox

This repository uses [leafletjs](https://leafletjs.com/) with [Mapbox](https://www.mapbox.com/). You need to replace `<your MAPBOX API KEY HERE>` with a token from [Mapbox](https://www.mapbox.com/). Mapbox is free to use, and does not require any payment information.

## Note about ES6

Most of the code in this project has been written to the ES6 JavaScript specification for compatibility with modern web browsers and future-proofing JavaScript code. As much as possible, try to maintain use of ES6 in any additional JavaScript you write.
