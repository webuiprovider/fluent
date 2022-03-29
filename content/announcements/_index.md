---
title: 'A better knowledge base'
description: 'We provides the means for the collection, organization and computerized retrieval of knowledge'
headerTheme: light
url: 'announcements'
heroBg: "/images/hero.jpg"
latestVer: true
---


###### KNOWLEDGE BASE

### Release Notes v1.9.1

[Fluent Bit](https://fluentbit.io) is a Fast and Lightweight Data Processor and Forwarder for Linux, BSD and OSX. We are proud to announce the availability of **Fluent Bit v1.9.1**.

For people upgrading from previous versions you **must read** the Upgrading Notes section of our documentation:

[https://docs.fluentbit.io/manual/installation/upgrade_notes](https://docs.fluentbit.io/manual/installation/upgrade_notes)

#### News

[Fluent Bit](https://fluentbit.io) v1.9.1 is the stable release!, new changes on this version:

- __Core__
   - engine: print to log Fluent Bit version and Git commit
   - bin: do not print hash on start
   - task: fixed wrong assumed type for data in flb_task_retry_count
   - parser: always destroy or link config format context
   - storage: enhance version and init message
   - config_map: add check if flb_env_var_translate failed (#5124)
   - io: fixed write event monitoring for recycled keep_alive connections
   - config_format: on exception return NULL
   - config_format: add new optional head for linked list
   - upstream: replaced non thread safe release call in flb_upstream_conn_release
   - config: add new config format list

- __Plugins__
   - [Nightfall (Filter)](https://docs.fluentbit.io/manual/pipeline/filters/nightfall/)
      - Fix for loop variable syntax (#5119)
      - Capitalize flag in cmakelists (#5107)
   - [Kubernetes (Filter)](https://docs.fluentbit.io/manual/pipeline/filters/kubernetes/)
      - Fix leak on journal mode when excluding records
   - [Opensearch (Output)](https://docs.fluentbit.io/manual/pipeline/outputs/opensearch/)
      - Fix double free on index header (#5132)
   - [Kafka (Output)](https://docs.fluentbit.io/manual/pipeline/outputs/kafka/)
      - Fix broken config map (#5097)

{{< contributor-list >}}

#### Contributors

On every release, there are many people involved doing contributions on different areas like bug reporting, troubleshooting, documentation and coding, without these contributions from the community, the project won't be the same and won't be in the good shape that it is now. So THANK YOU! to everyone who takes part of this journey!

{{< /contributor-list >}}

#### Join us

We want to hear about you, our community is growing and you can be part of it!, you can contact us at:

* Slack: [http://slack.fluentd.org](http://slack.fluentd.org)
* Mailing list: [https://groups.google.com/forum/#!forum/fluent-bit](https://groups.google.com/forum/#!forum/fluent-bit)
* Github: [http://github.com/fluent/fluent-bit](https://github.com/fluent/fluent-bit)
* IRC: irc.freenode.net #fluentbit
* Twitter: [@fluentbit](https://twitter.com/fluentbit)


{{% button href="/announcements/older-versions/"  position="center" text-transform="" class="btn-gradient" margin="0px 0px 30px"  %}}See Older Versions{{% /button %}}
