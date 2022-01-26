---
title: 'A better knowledge base'
description: 'We provides the means for the collection, organization and computerized retrieval of knowledge'
headerTheme: light
url: 'documentation'
heroBg: "/images/hero.jpg"
latestVer:
  heading: "Fluent Bit v1.8.2 is out!"
  subHeading: "New release on Jul 20, 2021,"
  smallText: "We are part of a wide community, <br> <strong>no vendor lock-in.</strong>"
  text:
  btnText: "Download Now"
  btnUrl: "https://docs.fluentbit.io/manual/installation/getting-started-with-fluent-bit"
  bottomText: ""
  bottomUrl: "#"
---

###### KNOWLEDGE BASE

### Release Notes v1.8.3

Fluent Bit is a Fast and Lightweight Data Processor and Forwarder for Linux, BSD and OSX. We are proud to announce the availability of Fluent Bit v1.8.3.

For people upgrading from previous versions you must read the Upgrading Notes section of our documentation:
https://docs.fluentbit.io/manual/installation/upgrade_notes

###### Fluent Bit v1.8.3 is the stable release!, new changes on this version:

**Core**

- multiline: always validate stream_id with lru_parser
- multiline: fix states rules handling
- output_thread: fixed multiple initialization of local_thread_instance in emulated TLS
- http_client: log allocation failures for request headers
- http_client: warn when flb_http_do() fails due to malformed data
- aws_util: added index recognition for flb_get_s3_key
- lib: fix race between flb_start and flb_destroy

**Libraries**

1. cmetrics: upgrade to v0.1.6

**Plugins**

- Tail (Input) 
  *Add custom keys to multiline payload*
- Multiline (Filter)
  *Flush before return and added new option ‘debug_flush’*
- S3 (Output)
  *Re-added static file path configuration option*
  *Added file permission fix and flb_errno to read / write file*
  *Fixed potential segfault on file discard*
  *Added data ordering preservation feature*
  *Added sequential index feature*
  *Log_key configuration option implemented*
  *Added static file path configuration option*

**Loki (Output)**

- Delay mp_sbuf->data derefence (#3796)

**Prometheus_Remote_Write (Output)**

- Concatenate cmetrics buffers

{{< contributor-list >}}

#### Contributors

On every release, there are many people involved doing contributions on different areas like bug reporting, troubleshooting, documentation and coding, without these contributions from the community, the project won’t be the same and won’t be in the good shape that it is now. So THANK YOU! to everyone who takes part of this journey!

- Stephen Lee
- Eduardo Silva
- Leonardo Alminana
- Jesse Rittner
- Aaron Jacobs
- Richard Burakowski

{{< /contributor-list >}}

{{% button href="/documentation/older-versions/"  position="center" text-transform="" class="" margin="0px 0px 30px"  %}}See Older Versions{{% /button %}}
