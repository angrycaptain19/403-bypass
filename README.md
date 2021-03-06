# 403-bypass

[![GitHub issues](https://img.shields.io/github/issues/channyein1337/403-bypass)](https://github.com/channyein1337/403-bypass/issues)
[![GitHub forks](https://img.shields.io/github/forks/channyein1337/403-bypass)](https://github.com/channyein1337/403-bypass/network)
[![GitHub stars](https://img.shields.io/github/stars/channyein1337/403-bypass)](https://github.com/channyein1337/403-bypass/stargazers)
[![GitHub license](https://img.shields.io/github/license/channyein1337/403-bypass)](https://github.com/channyein1337/403-bypass)

## Introduction

This is the tool that I wrote when I was working for pentest. 

## Usage 

![](https://raw.githubusercontent.com/channyein1337/403-bypass/main/image/usage.png)

To display help message use the -h flag:

$ python3 403-bypass.py -h

```
___ ___ ___    _____
| | |   |_  |  | __  |_ _ ___ ___ ___ ___ ___ ___
|_  | | |_  |  | __ -| | | . | .'|_ -|_ -| -_|  _|
  |_|___|___|  |_____|_  |  _|__,|___|___|___|_|
                     |___|_|

                         @channyeinwai(1.0)

usage: 403-bypass.py [-h] -u URL -p PATH

403 Bypasser : python 403-bypass.py -u https://www.example.com -p admin

optional arguments:
  -h, --help            show this help message and exit
  -u URL, --url URL     Provide url
  -p PATH, --path PATH  Provide the path
```
## How To Run
$ python3 403-bypass.py -u https://www.google.com -p admin
![](https://raw.githubusercontent.com/channyein1337/403-bypass/main/image/run.png)

## Installation

- git clone https://github.com/channyein1337/403-bypass.git
- cd 403-bypass
- pip3 install -r requirements.txt

## Features
- Bypass using HTTP Verbs(GET , HEAD , POST , PUT , DELETE , PATCH)
- Bypass using payloads
- Bypass using headers
- Allow Redirects
