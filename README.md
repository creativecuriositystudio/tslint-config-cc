# TSLint Config - Creative Curiosity Studio

## Introduction

This is the TSLint configuration file used by Creative Curiosity
projects we work on, both open-source and ones for our clients.

## Installation

```sh
npm install --save-dev tslint-config-ccs
```

## Usage

Just extend `tslint-config-ccs` in your `tslint.json` file, like so:

```json
{
  "extends": "tslint-config-ccs" 
}
```

Don't forget to override any rules if required.
