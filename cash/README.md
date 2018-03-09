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

> √ 0.81 (EUR) Euro

$ node bin/index.js --save aud eur

> Saved default currencies to C:\Users\Antoine\AppData\Local\cash-nodejs\Config\config.json
```
Once default currencies are saved, you just have to specify the amount

```
$ node bin/index.js 200

> √ 125.69 (EUR) Euro
> √ 156.12 (USD) US Dollar
>  Conversion of AUD 200
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

