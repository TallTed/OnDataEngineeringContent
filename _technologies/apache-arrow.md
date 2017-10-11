---
title: "Apache Arrow"
description: "In-memory data structure specification for building columnar based data systems. Provides a standard interchange format to allow sharing of data between processes on a node without the overhead of moving or transforming the data, permits O(1) random access and has the ability to represent both flat relational structures and complex hierarchical nested data. Data is organised using a columnar structure memory-layout making it cache efficient for analytical workloads (which typically group all data relevant to a column operation together) and allows execution engines to take advantage of modern CPU SIMD (Single Instruction Multiple Data) instructions which work on multiple data values simultaneously in a single CPU clock cycle. Comes with reference implementations in Java and C++ and a Python interface to the C++ libraries (Ruby and JavaScript language bindings are in progress). Seeded from the Apache Drill project and promoted directly to a top level Apache project in February 2016 followed by an initial 0.1 release in October 2016. Used in a range of other projects including Drill, Spark, Impala, Kudu, Pandas and others. Has not yet reached a v1.0 milestone, but is still under active development with a range of contributors from a number of other Apache and non-Apache data projects."
alt-titles: [Arrow]
vendors: [Apache]
type: "Commercial Open Source"
date: 2017-10-02 07:45
version: "v0.7"
---
# Links

* <https://arrow.apache.org/> - home page
* <http://git.apache.org/arrow.git/> - source code

* <http://info.dataengconf.com/the-future-of-column-oriented-data-processing-with-arrow-and-parquet> - introduction to Arrow
* <https://blogs.apache.org/foundation/entry/the_apache_software_foundation_announces87> - top level project announcement

## News

* <https://arrow.apache.org/blog/> - blog
* <https://arrow.apache.org/release/> - release and change summary