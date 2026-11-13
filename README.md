# CRAB job monitoring

This is a simple tool for quick and easy monitoring of a large number of CRAB jobs.
It is essentially just a wrapper around the `crab status` command, but structures the results into an easy-to-navigate overview like this one:

<img src="docs/images/status_screen.png" width="1200"/>

### Prerequisites

- **Packages:** The `crabmon` package itself is lightweight and has few dependencies. It needs `bash` and `python` with a few basic packages (todo: make detailed list).
- **Environment:** `crabmon` needs to run from an environment with access to your CRAB working directories. So far, it has been tested on `lxplus` only. 
- **[Optional] web hosting:** `crabmon` produces the status overview page in the form of a bunch of html files, which you can open using any web browser.
However, to view them from multiple devices (e.g. check from your phone once in a while) without having to copy over the html files, you can host them somewhere on the web.
This is easy if you're working on `lxplus`, just follow [these instructions](https://webeos.docs.cern.ch/).
After having gone through those steps, it's as simple as copying the folder with html files to a specified location on `/eos` (can be done automatically after each run).

### What it does

### How to run

### Automatic updates using crontab
