# rangecalc

[![Build Status](https://travis-ci.org/clpo13/rangecalc-js.svg?branch=master)](https://travis-ci.org/clpo13/rangecalc-js)
[![Dependency Status](https://david-dm.org/clpo13/rangecalc-js.svg)](https://david-dm.org/clpo13/rangecalc-js)
[![devDependency Status](https://david-dm.org/clpo13/rangecalc-js/dev-status.svg)](https://david-dm.org/clpo13/rangecalc-js#info=devDependencies)
[![codecov](https://codecov.io/gh/clpo13/rangecalc-js/branch/master/graph/badge.svg)](https://codecov.io/gh/clpo13/rangecalc-js)
[![npm](https://img.shields.io/npm/v/rangecalc.svg)](https://www.npmjs.com/package/rangecalc)

Find the CIDR range of a set of IPv4 addresses. Requires [Node.js](https://nodejs.org).

## Get it

Install with `npm install -g rangecalc`. Use it in your code with `var rangecalc = require('rangecalc');`.

A simple CLI program is included to demonstrate range calculation. Run with `rangecalc-cli`.

## Use it

- `getCIDR`: Calculate the CIDR range of two IP addresses.
- `getInt`: Calculate an integer representation of an IP address.
- `sort`: Sort an array of IP addresses.

More information on the functions available can be found [here](https://clpo13.github.io/rangecalc-js).

## Improve it

Install the devDependencies with `npm install`. Run tests with `npm test`.

## To do

- [ ] Show how many addresses are in a range
- [ ] Calculate IPv6 addresses

## License

Copyright &copy; 2017–2018 Cody Logan

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

A copy of the GNU General Public License can be found in [LICENSE](LICENSE) and at <http://www.gnu.org/licenses/>.
