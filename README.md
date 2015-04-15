# DigitalOcean Speed Test CLI

*v0.5.8*

## Features

- Download tests.
- Latency tests.
- Simple to use.
- Currently tests: AMS1-3, NYC1-3, LON1, SFO1, and SGP1.

## Requirements

- Bash
- Wget
- Ping
- Curl (Optional if you want to quickly run it off the CDN)

## Run It Now

To run the speed test, do:

    curl -s https://i.destroy.tokyo/dostcli | bash

or for a 10MB test, run:

    curl -s https://i.destroy.tokyo/dostcli | bash -s - 10mb

## Notices

- This currently does not test upload speed.
