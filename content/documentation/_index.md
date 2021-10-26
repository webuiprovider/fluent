---
title: 'A better <br> knowledge base'
description: 'We provides the means for the collection, organization and computerized retrieval of knowledge'
url: 'documentation'
latestVer:
  heading: "Fluent Bit v1.8.2 is out!"
  subHeading: "New release on Jul 20, 2021,"
  text: "Check out the Release Notes, read the Updated Documentation or jump directly to the Downloads Section."
  smallText: "We are part of a wide community, <strong>no vendor lock-in.</strong>"
  btnText: "Download Now"
  btnUrl: "https://docs.fluentbit.io/manual/installation/getting-started-with-fluent-bit"
  bottomText: ":: Read Documentation"
  bottomUrl: "#"
releaseNotes:
  heading: "Release Notes v1.8.3"
  version: "v1.8.3"
  text: "Fluent Bit is a Fast and Lightweight Data Processor and Forwarder for Linux, BSD and OSX. We are proud to announce the availability of Fluent Bit v1.8.3. <br>
  For people upgrading from previous versions you must read the Upgrading Notes section of our documentation:
  https://docs.fluentbit.io/manual/installation/upgrade_notes"
newChnagesColLeft:
  - heading: core
    lists:
    - "multiline: always validate stream_id with lru_parser"  
    - "multiline: fix states rules handling"
    - "output_thread: fixed multiple initialization of local_thread_instance in emulated TLS"
    - "http_client: log allocation failures for request headers" 
    - "http_client: warn when flb_http_do() fails due to malformed data"
    - "aws_util: added index recognition for flb_get_s3_key" 
    - "lib: fix race between flb_start and flb_destroy"
  - heading: Libraries
    lists:
    - "cmetrics: upgrade to v0.1.6"
newChnagesColRight:
  - heading: Plugins
    lists:
    - "Tail (Input) <i> Add custom keys to multiline payload</i>"
    - "Multiline (Filter) <i> Flush before return and added new option ‘debug_flush’</i>"
    - "S3 (Output) <i> Flush before return and added new option ‘debug_flush’ <br> Re-added static file path configuration option<br>Added file permission fix and flb_errno to read / write file<br>Fixed potential segfault on file discard<br>Added data ordering preservation feature<br>Added sequential index feature<br>Log_key configuration option implemented<br>Added static file path configuration option
    - </i>"
  - heading: "Loki (Output)"
    lists:
    - Delay mp_sbuf->data derefence (#3796)
  - heading: "Prometheus_Remote_Write (Output)"
    lists:
    - Concatenate cmetrics buffers
contributor: 
  heading: "Contributors"
  text: "On every release, there are many people involved doing contributions on different areas like bug reporting, troubleshooting, documentation and coding, without these contributions from the community, the project won’t be the same and won’t be in the good shape that it is now. <br> So THANK YOU! to everyone who takes part of this journey!"
  name:
  - Stephen Lee
  - Eduardo Silva
  - Leonardo Alminana
  - Jesse Rittner
  - Aaron Jacobs
  - Richard Burakowski
---