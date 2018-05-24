---
title: Internet of Dingus
author: Ryan Parsley
tags:
  - iot
  - arduino
  - dingus
exerpt: "The making of an IOT ecosystem."
header:
  teaser: "The making of an IOT ecosystem."
  overlay_image: "/assets/images/nlp-ben.jpg"
  show_overlay_excerpt: false
---

In this month’s Technically Speaking, Ryan demystifies the internet of things by creating an example to illustrate all the parts that make it work.

## What's a dingus?
A dingus is... a kind of a thing. For the purposes of this talk, a dingus has:

1. Wifi
2. One actuator
3. One sensor

I happened to make my first one from a Huzzah Feather from a company called Adafruit. It's compatible with Arduino, but has wifi built in.

## What's an Internet of Dingus?

1. One or more dingus
2. An MQTT broker (I used Adafruit.io)
3. A Drupal instance for registering a dingus and handling user auth
4. A decoupled frontend to tie the experience together (I opted to use Vue for this)

[Slides are posted here](https://ryanparsley.github.io/iod-technicallySpeaking/)

## Links
* [Frontend App](http://iod-client.herokuapp.com/)
* [Drupal Server](http://iod-server.herokuapp.com/)
* [MQTT Broker used (adafruit.io)](https://io.adafruit.com/ryanparsley/dashboards)
* [Blog post introducing the project](https://passport.vml.com/post/introducing-internet-dingus)
* [Blog post I wrote on passport digging into the arduino part](https://passport.vml.com/post/internet-dingus-arduino-breakdown)