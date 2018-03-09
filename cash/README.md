# The programm cash converts currencies.

## Installation

First, you need to install node.js and npm.
Then you will need some dependencies to use the programm.
There are the dependencies you need: 

```
npm install con
npm install chalk
npm install update-notifier
npm install got
npm install money
npm install ora
```

## Usage

Here are the usage of the programm

```
$ node bin/index.js <amount> <currencyFrom> <currencyTo>
$ node bin/index.js <command> 
```

Here are the commands

```
--save, -s Save currencies as default currencies
--help, -h Display help message
--version, -v Display version number
```

## Example

```
$ node bin/index.js 1 usd
$ node bin/index.js --save usd eur pln
```

