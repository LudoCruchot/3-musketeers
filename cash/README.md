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
--save -s Save currencies as default currencies
--help -h Display help message
--version -v Display version number
```

## Example

```
$ node bin/index.js 1 usd eur
$ node bin/index.js --save usd eur pln
```
## Information

Here are all the currencies you can use

```
AUD: Australian Dollar
  RUB: Russian Rouble
  EUR: Euro
  BGN: Bulgarian Lev
  BRL: Real Brazilian
  CAD: Canadian Dollar
  CHF: Swiss Franc
  CNY: Chinese Yuan
  CZK: Czech Koruna
  DKK: Danish Krone
  GBP: Pound Sterling
  HKD: Hong Kong Dollar
  HRK: Croatian Kuna
  HUF: Hungarian Forint
  IDR: Indonesian Rupiah
  ILS: Israeli Shekel
  INR: Indian Rupee
  JPY: Japanes Yen
  KRW: South Korean Won
  MXN: Mexican Peso
  MYR: Malaysian Ringgit
  NOK: Norwegian Krone
  PHP: Philippine Peso
  PLN: Polish Zloty
  RON: Romanian New Leu
  SEK: Swedish Krona
  SGD: Singapore Dollar
  THB: Thai Baht
  TRY: Turkish Lira
  USD: US Dollar
  ZAR: South African Rand
  NZD: New Zealand Dollar
 ```

