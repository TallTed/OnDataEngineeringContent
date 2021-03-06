---
title: "Hortonworks Data Platform"
description: "A distribution of Hadoop based on a commitment to the Apache open source ecosystem.  All bundled projects are Apache open source projects based on official Apache project releases, with any patches for bug fixes or new features being official Apache project patches pulled from later releases of the relevant project.    Available as RPMs, through Apache Ambari (for local installs) or Cloudbreak (for installation on cloud platforms), and as managed cloud offerings on Azure (as HDInsight, a Microsoft branded offering) and on AWS (as Hortonworks Data Cloud for AWS). Comes with a number of add-ons that aren't part of the core product, including HDP Search, Hortonworks HDB and ODBC and JDBC drivers for Hive, Spark SQL and Apache Phoenix.  The HDP software is available free of charge, with training, consultancy and support available from Hortonworks (including a flex support subscription that covers the usage of HDP on-premise via Ambari, or cloud infrastructure via Cloudbreak, or when used as HDCloud on AWS).  Also available for IBM Power Systems.  A version of the Hortonworks Data Platform for Windows was available, however was discontinued in August 2016 with the last release being HDP 2.4.  The Hortonworks Data Platform was first released in June 2012."
alt-titles: [HDP]
vendors: [Hortonworks]
categories: [Hadoop Distributions]
tech-relationships: [[packages, Hadoop, Hive, Tez, Pig, Spark, HBase, Atlas, Oozie, Sqoop, Knox, Ranger, ZooKeeper, Zeppelin, Phoenix, Calcite, DataFu, Livy, Druid], [packages (but deprecated), Falcon, Flume, Mahout, Slider, Hue, Accumulo, Kafka, Storm], [add ons, HDP Search, Hortonworks HDB, Hortonworks Cybersecurity Package, SmartSense], [manageable via, Ambari, Cloudbreak], [also available as, HDCloud for AWS, HDP for Windows]]
type: "Commercial Open Source"
date: 2017-02-17 07:30
last_updated: 2017-06-14
version: "2.6"
---
## Bundled Technologies

The base Apache project versions bundled with each version of HDP are shown on the HDP home page, as well as on the first page of the release notes (see [Links](#links) section below for link to latest release notes).  Details of the features in these releases that Hortonworks don't support, and the patches that have been applied to these releases are also available in the release notes, along with known vulnerabilities, fixes from previous versions and known issues.

As of HDP 2.6:

* [Druid](/technologies/druid) was added in tech preview
* The following components were deprecated and will be removed in HDP 3.0: [Apache Falcon](/technologies/apache-falcon), [Apache Flume](/technologies/apache-flume) (advice is to consider [HDF](/technologies/hortonworks-data-flow) instead), [Apache Mahout](/technologies/apache-mahout) (advice is to consider [Spark MLLib](/technologies/apache-spark/mllib) instead), [Apache Slider](/technologies/apache-slider) (being folded into YARN) and [Hue](/technologies/hue) (advice is to consider [Ambari Views](/technologies/apache-ambari/ambari-views) instead).
* The following components were deprecated from HDP as they're being moved into other Hortonworks products/offerings: [Apache Accumulo](/technologies/apache-accumulo), [Apache Kafka](/technologies/apache-kafka) and [Apache Storm](/technologies/apache-storm).

Note that:

* Although Solr is referenced on the HDP home page and in the release note, it is only available via the HDP Search add-on to HDP
* Hortonworks HDB is Pivotal HDB, with support and consultancy provided by Hortonworks, and is distributed as an add-on to HDP
* Apache Calcite, Apache DataFu, Apache Mahout and Hue are not referenced on the HDP home page, but are part of HDP (they are referenced in the release notes)
* Livy is not mentioned on the HDP home page or the release notes, but is part of HDP (it's in the HDP rpm repo and included Zeppelin installation steps)
* Cascading is referenced in the release notes, but isn't part of HDP (it's not in the HDP repo and isn't covered by the installation guide), as is now deprecated anyway and will be removed in HDP 3.0

## Release History

| version | release date | release links | release comment
| 2.6 | 2017-02-28 | [announcement](https://hortonworks.com/blog/announcing-the-general-availability-of-hortonworks-data-platform-2-6/) [new features](http://docs.hortonworks.com/HDPDocuments/HDP2/HDP-2.6.0/bk_release-notes/content/new_features.html) | See notes above for tech changes

## Links

* <http://hortonworks.com/products/data-center/hdp/> - homepage
* <http://docs.hortonworks.com/HDPDocuments/HDP2/HDP-2.6.0/index.html> - HDP 2.6.0 documentation
* <http://docs.hortonworks.com/HDPDocuments/HDP2/HDP-2.6.0/bk_release-notes/content/ch_relnotes.html> - HDP 2.6.0 release notes

## News

* <http://docs.hortonworks.com/index.html> - shows latest Hortonworks release version
* <https://hortonworks.com/blog/category/hdp/> - Hortonworks blog posts