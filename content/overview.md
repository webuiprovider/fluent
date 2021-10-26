---
title: 'Overview'
description: 'Fluent Bit has been designed with performance and <br> low resources consumption in mind.'
type: overview
hero:
 heading: "We aim to be a generic Swiss knife <br>  for logs and metrics"
 desc: "Fluent Bit has been designed with performance and <br> low resources consumption in mind."
 image: "/images/overview.svg"
 text: "An open source Log Processor and Forwarder which allows you to collect any data like metrics and logs from different sources, enrich them with filters and send them to multiple destinations."
preferred:
 heading: "The preferred choice <br>  for containerized environments"
 image: "/images/preffered.svg"
lists:
- icon: "/images/event-driven.svg"
  heading: Event Driven
  text: "Fluent Bit as a service is fully event-driven, it only use asynchronous operations to collect and deliver data."
- icon: "/images/flexible-routing.svg"
  heading: Flexible Routing
  text: "The data that comes in the pipeline, can be routed to multiple places using custom routing rules. Ship your data to multiple places with zero-copy strategy."
- icon: "/images/configuration.svg"
  heading: Configuration
  text: "It configuration is very simple and human-readable, it allow to specify how it will behave, which features to enable and how Routing is performed."
- icon: "/images/io-handler.svg"
  heading: I/O Handler
  text: "The Input/Output layer provides an abstraction that allow to perform read/write operations in an asynchronous way."
- icon: "/images/upstream-manager.svg"
  heading: Upstream Manager
  text: "Our Upstream manager simplify the connection process and take care of timeout/network exceptions and Keepalive states."
- icon: "/images/security.svg"
  heading: Security & TLS
  text: "When delivering data to destinations, output connectors inherit full TLS capabilities in an abstracted way. Add your certificates as required."
history:
  heading: "A Brief History of Fluent Bit"
  image: "/images/history.svg"
  text: "On 2014, the Fluentd team at Treasure Data forecasted the need of a lightweight log processor for constraint environments like Embedded Linux and Gateways, the project aimed to be part of the Fluentd Ecosystem and we called it Fluent Bit, fully open source and available under the terms of the Apache License v2.0.   <br>  <br> 
  After the project was around for some time, it got some traction in the Embedded market but we also started getting requests for several features from the Cloud community like more inputs, filters, and outputs. Not so long after that, Fluent Bit becomes one of the preferred solutions to solve the logging challenges in Cloud environments"
---

## Overview

It has been designed as a lightweight solution with high performance in mind. From a design perspective, it's fully asynchronous (event-driven) and take the most of the operating systems API for performance and reliability.
