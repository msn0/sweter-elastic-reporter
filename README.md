# Elastic reporter for Sweter

This project refers to ``sweter``. If you are not familiar with ``sweter`` then take a look at [Sweter](https://github.com/msn0/sweter) first.

> `sweter-elastic-reporter` reports web performance timings to Elastic instance.

## Installation

Just install `sweter`

```sh
$ npm install sweter -g
```

## Usage

```
$ sweter google.com \ 
    --reporter elastic \ 
    --elastic-host 127.0.0.1 \ 
    --elastic-index my-index
```
