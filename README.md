# ioBroker.rika-firenet

[![NPM version](http://img.shields.io/npm/v/iobroker.rika-firenet.svg)](https://www.npmjs.com/package/iobroker.rika-firenet)
[![Downloads](https://img.shields.io/npm/dm/iobroker.rika-firenet.svg)](https://www.npmjs.com/package/iobroker.rika-firenet)
![Number of Installations (latest)](http://iobroker.live/badges/rika-firenet-installed.svg)
![Number of Installations (stable)](http://iobroker.live/badges/rika-firenet-stable.svg)
[![Dependency Status](https://img.shields.io/david/xsawa32/iobroker.rika-firenet.svg)](https://david-dm.org/xsawa32/iobroker.rika-firenet)
[![Known Vulnerabilities](https://snyk.io/test/github/xsawa32/ioBroker.rika-firenet/badge.svg)](https://snyk.io/test/github/xsawa32/ioBroker.rika-firenet)

[![NPM](https://nodei.co/npm/iobroker.rika-firenet.png?downloads=true)](https://nodei.co/npm/iobroker.rika-firenet/)

**Tests:** ![Test and Release](https://github.com/xsawa32/ioBroker.rika-firenet/workflows/Test%20and%20Release/badge.svg)

## RIKA-Firenet adapter for ioBroker

Control your RIKA stove

## Information
Adapter in this first initial release, only polling values from your stove. Setting-actions will follow soon.
Polling-intervall minimum is 1 minute so that you do not appear to be a DOS-Attacker

Fill textboxes in Adapter-Config
* Username: (E-Mail for your Rika account)
* Password: (Password for your Rika account)
* Stove-ID: (go to your Rika account and find out)
* Polling-Interval: (min 1 Minute)

## Changelog

### 0.0.1
* (xsawa32) initial release

## License
MIT License

Copyright (c) 2020 Andreas Wass <a.wass@sbg.at>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
