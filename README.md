# Dart DSA Broker [![Slack](https://dsa-slack.herokuapp.com/badge.svg)](https://dsa-slack.herokuapp.com/)

## Getting Started

### Prerequisites

- [Git](https://git-scm.com/downloads)
- [Dart SDK](https://www.dartlang.org/downloads/)

### Install

```bash
# Globally install the Dart DSA Broker
pub global activate -s git https://github.com/IOT-DSA/broker-dart.git
```

### Start a Broker

```bash
# If you have the pub global executable path setup.
dsbroker
```

**OR**

```bash
# If you do not have the pub global executable path setup.
pub global run broker_dart:broker
```

You can edit the server configuration using `broker.json`. For more information about broker configuration, see
[Configuring a Broker](https://github.com/IOT-DSA/broker-dart/wiki).

## Links

- [DSA Site](http://iot-dsa.org/)
- [DSA Wiki](https://github.com/IOT-DSA/docs/wiki)
- [Dart DSLink SDK](https://github.com/IOT-DSA/sdk-dslink-dart)
