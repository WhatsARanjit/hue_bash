# hue_bash

Control hue router with bash script

## Setup

1. Follow instructions [here](https://www.developers.meethue.com/documentation/getting-started) to get an authorized user key
1. Place this key in `hue` script like so:

```
KEY='ewrojblkn4fdkcbk6;oqe=welkjdfklh.mm4;lfd'
```

## Usage

```
Usage: hue method endpoint [data]...

Options:
  method            choose from GET, POST, PUT
  endpoint          from hue docs, choose lights, state, scene, etc.
  data              when posting, use quoted JSON format
```
