# @engammar111/nostring

[
![npm  (scoped)](https://img.shields.io/github/license/engammar111/nostring?style=social)
]
[![npm bundle size (minified)](https://img.shields.io/badge/nostring-nostring-green)
]



# moves all spaces from a string.

# Install
\$ npm install @engammar111/nostring

# Usage

const nostring = require("@engammar111/nostring");

nostring("So much space!");

//=> "So, much space!"

nostring(1337);

//=> Uncaught TypeError: nostring wants a string!
// at tiny (<anonymous>:2:41)
// at <anonymous>:1:1

# nospace between strings
