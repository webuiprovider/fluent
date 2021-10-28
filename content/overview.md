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
 heading: "An example of sending data to Kafka and Splunk"
 image: "/images/preffered.svg"
lists:
- icon: "/images/event-driven.svg"
  heading: Event Driven
  text: "Fluent Bit is fully event-driven, Using asynchronous operations to collect and deliver data at high speed and performance."
- icon: "/images/flexible-routing.svg"
  heading: Flexible Routing
  text: "Ship your data to multiple end destinations, with advanced options based on content and data types."
- icon: "/images/configuration.svg"
  heading: Configuration
  text: "Simple configuration for all plugins that let’s you get started in a couple of minutes."
- icon: "/images/io-handler.svg"
  heading: Reliability and Buffering
  text: "Built-in I/O handlers to store data in case of end destination disruptions, and buffered output."
- icon: "/images/upstream-manager.svg"
  heading: High availability
  text: "Simplified Upstream configuration that automatically takes care of high availability with timeout and keep alive management."
- icon: "/images/security.svg"
  heading: Security & TLS
  text: "Full TLS capabilities for plugins, as well as advanced certificate and Kerberos features depending on plugin."
history:
  heading: "A Brief History of Fluent Bit"
  image: "/images/history.svg"
  text: "In 2014, the Fluentd team at Treasure Data saw the need of a lightweight log processor for environments like embedded Linux. The team created Fluent Bit, a fully open source and available under the terms of the Apache License v2.0.  <br>  <br> 
  Since then Fluent Bit has also found a home in container based environments and is used by major cloud providers to solve tough data routing challenges."
---

## Overview

It has been designed as a lightweight solution with high performance in mind. From a design perspective, it's fully asynchronous (event-driven) and take the most of the operating systems API for performance and reliability.
