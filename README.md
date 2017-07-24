# rangecalc

[![Build Status](https://travis-ci.org/clpo13/rangecalc-js.svg?branch=master)](https://travis-ci.org/clpo13/rangecalc-js)
[![Dependency Status](https://david-dm.org/clpo13/rangecalc-js.svg)](https://david-dm.org/clpo13/rangecalc-js)
[![devDependency Status](https://david-dm.org/clpo13/rangecalc-js/dev-status.svg)](https://david-dm.org/clpo13/rangecalc-js#info=devDependencies)
[![codecov](https://codecov.io/gh/clpo13/rangecalc-js/branch/master/graph/badge.svg)](https://codecov.io/gh/clpo13/rangecalc-js)

Find the CIDR range of a set of IPv4 addresses. Requires [Node.js](https://nodejs.org).

## Get it

Install with `npm install -g rangecalc`. Use it in your code with `var rangecalc = require('rangecalc');`.

A simple CLI program is included to demonstrate range calculation. Run with `rangecalc-cli`.

## Use it

- `getCIDR`: Calculate the CIDR range of two IP addresses. Uses the address objects provided by [ipaddr.js](https://github.com/whitequark/ipaddr.js).
- `getInt`: Calculate an integer representation of an IP address.
- `sort`: Sort an array of IP addresses.

## Improve it

Install the devDependencies with `npm install`. Run tests with `npm test`.

## To do
- [ ] Show how many addresses are in a range
- [ ] Calculate IPv6 addresses

## License

This program is licensed under [GPLv3](LICENSE).
