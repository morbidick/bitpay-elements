# Polymer 2 Bitpay Elements

[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/morbidick/bitpay-elements)
[![Build Status](https://travis-ci.org/morbidick/bitpay-elements.svg?branch=master)](https://travis-ci.org/morbidick/bitpay-elements)

Create and show [bitpay](https://bitpay.com) invoices.

## Components

```html
<bitpay-invoice-create
  auto
  testnet
  amount="12.34"
  token="B75pQ5ZyM2CUCJbnH6zajY5pndzpgVxG1YpVd6a3Ljqh"
  invoice="{{ invoice }}"
></bitpay-invoice-create>
<bitpay-invoice-frame
  invoice="{{ invoice }}"
></bitpay-invoice-frame>
```

### \<bitpay-invoice-create\>

Create invoices in your SPA, requires a [non-signing POS bitpay token](https://bitpay.com/dashboard/merchant/api-tokens). Set the testnet attribute to use [bitpays testing infrastructure](https://bitpay.com/docs/testing).

### \<bitpay-invoice-frame\>

Show the invoice you created with the previous element inside an iframe and listen for status updates.

## Development

```bash
# Get dependencies
$ npm install

# Demo site
$ npm start
```
