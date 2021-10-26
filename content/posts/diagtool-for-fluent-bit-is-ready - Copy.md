---
title: 'Diagtool for  Fluent Bit is ready 22'
date: 2021-01-25
description: "Diatool now supports 'Fluent Bit'! Tool was just released as v.1.0, and now you can automate your troubleshooting process for both Fluentd and Fluent Bit."
image: "https://placeimg.com/640/480/people/sepia"
---

##### Fluentd vs Fluent Bit

Fluent Bit is an open source and multi-platform Log Processor and Forwarder. Both Fluentd and Fluent Bit have been developed by Treasure Data to solve the data collection problem but they have different features. Fluent Bit is light-weight and less dependencies compared to Fluentd, so that Fluent Bit is good for the environment where the system resource for applications are limited such as container and IoT use cases. The following table describe a comparison of features between Fluentd and Fluent Bit.

{{< table "" >}}
|         | Fluentd | Fluent Bit |
|---------|--------|--------|
| Scope     | Containers / Servers   | [Embedded Linux / Containers / Servers](#)   |
| Language     | C & Ruby   | C   |
| Memory | ~40MB  | ~650MB  |
| Dependencies | Built as a Ruby Gem, it requires a certain number of gems.  | Zero dependencies, unless some special plugin requires them.   |
| Plugins | More than 1000 plugins available  | Around 70 plugins available   |
{{< /table >}}

##### How Diagtool works for Fluent Bit

Fluentd and Fluent Bit have similar concepts, both have pluggable input and output modules and data process functions, however the format of configuration is not same. Diatool version 1.0 was released and now Diagtool is able to interpret the configuration of Fluent Bit and gather/validate required information as well as Fluentd. The new option ‘—type/-t‘ enables you to switch Fluentd and Fluent Bit. Here is sample usage of Diagtool for Fluent Bit.