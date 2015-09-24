# DigitalOcean Speed Test CLI

*v0.6.1*

## Features

- Download tests.
- Latency tests.
- Simple to use.
- Currently tests: AMS1-3, FRA1, LON1, NYC1-3, SFO1, SGP1, and TOR1.

## Requirements

- Bash
- Wget
- Ping
- Curl (Optional if you want to quickly run it off the CDN)

## Run It Now

To run the speed test, do:
```shell
curl -s https://i.destroy.tokyo/dostcli | bash
```

or if you want to opt out of tracking, run
```shell
curl -s https://i.destroy.tokyo/dostcli | bash -s 100mb true
```
or for a 10MB test, run:
```shell
curl -s https://i.destroy.tokyo/dostcli | bash -s - 10mb
```
and again, to opt out of tracking, run
```shell
curl -s https://i.destroy.tokyo/dostcli | bash -s - 10mb true
```

## Notices

- This currently does not test upload speed (Soon!).
