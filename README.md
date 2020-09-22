<img src="https://user-images.githubusercontent.com/9434884/43697219-3cb4ef3a-9975-11e8-9a9c-73f4f537442d.png" alt="Sentinel Logo" width="50%">

# Sentinel: The Sentinel of Your Microservices

[![Travis Build Status](https://travis-ci.org/alibaba/Sentinel.svg?branch=master)](https://travis-ci.org/alibaba/Sentinel)
[![Codecov](https://codecov.io/gh/alibaba/Sentinel/branch/master/graph/badge.svg)](https://codecov.io/gh/alibaba/Sentinel)
[![Maven Central](https://img.shields.io/maven-central/v/com.alibaba.csp/sentinel-core.svg?label=Maven%20Central)](https://search.maven.org/search?q=g:com.alibaba.csp%20AND%20a:sentinel-core)
[![License](https://img.shields.io/badge/license-Apache%202-4EB1BA.svg)](https://www.apache.org/licenses/LICENSE-2.0.html)
[![Gitter](https://badges.gitter.im/alibaba/Sentinel.svg)](https://gitter.im/alibaba/Sentinel)

## Introduction

As distributed systems become increasingly popular, the reliability between services is becoming more important than ever before.
Sentinel takes "flow" as breakthrough point, and works on multiple fields including **flow control**,
**traffic shaping**, **circuit breaking** and **system adaptive protection**, to guarantee reliability and resilience for microservices.

Sentinel has the following features:

- **Rich applicable scenarios**: Sentinel has been wildly used in Alibaba, and has covered almost all the core-scenarios in Double-11 (11.11) Shopping Festivals in the past 10 years, such as “Second Kill” which needs to limit burst flow traffic to meet the system capacity, message peak clipping and valley fills, circuit breaking for unreliable downstream services, cluster flow control, etc.
- **Real-time monitoring**: Sentinel also provides real-time monitoring ability. You can see the runtime information of a single machine in real-time, and the aggregated runtime info of a cluster with less than 500 nodes.
- **Widespread open-source ecosystem**: Sentinel provides out-of-box integrations with commonly-used frameworks and libraries such as Spring Cloud, Dubbo and gRPC. You can easily use Sentinel by simply add the adapter dependency to your services.
- **Polyglot support**: Sentinel has provided native support for Java, [Go](https://github.com/alibaba/sentinel-golang) and [C++](https://github.com/alibaba/sentinel-cpp).
- **Various SPI extensions**: Sentinel provides easy-to-use SPI extension interfaces that allow you to quickly customize your logic, for example, custom rule management, adapting data sources, and so on.

Features overview:

## Documentation

See the [中文文档](https://github.com/alibaba/Sentinel/wiki/%E4%BB%8B%E7%BB%8D) for document in Chinese.

