# Data Pipeline Health Monitor

<img src="banner.svg" alt="Data Pipeline Health Monitor project illustration" width="100%">

A lightweight tracker for dataset references, recorded check outcomes, and pipeline incident notes.

## Public web app

**Open the app:** https://ayushkjha.github.io/Data-Pipeline-Health-Monitor/

The hosted app saves records in this browser on this device. Records are not sent to a server or synchronized across devices. Use **Export JSON** for backups or to move records.

## Features

- Create, search, edit, and delete dataset, check-result, and incident records.
- Import CSV or JSON and export JSON backups.

## Limits

It records checks and file paths you provide; it does not connect to or run checks against a real pipeline.

## Run the private local version

Requires Node.js 24 or newer. From this repository, run:

```sh
npm test
node server.mjs
```

The local Node.js version stores records in SQLite under `data/`. The public browser version does not access this database.
