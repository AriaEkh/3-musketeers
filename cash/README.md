



# Cash 

The project purpose is to write the README.md file of the cash program. This program can give you the change of over 30 differents currencies into US Dollars, Euro and Pound Sterling.
You can also save a default currency, so you only have to write the amount you want to change 

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

First of all you need to go into your directory thanks to the terminal.

```sh
❯ cd /path/to/workspace/3-musketeers/cash/bin
```

### Installing

Then install some packages here thanks to the following command:

```sh
❯ npm install
```

## Running the tests

Finally you can run the program with the following command:

```sh
❯ node index.js
```

If you want to know the change of a currency into another one you can write it like this: 

```sh
❯ node index.js 10 CZK
```


It will give you the change in USD, GBP and EUR



If you need to know what currencies you can know the change of, you can go into : 

cash/lib 

Then open the currencies json file.


## Save your default currency

To save your default currency you have to use the following command (You can replace USD by the currency you want to have as default)

```sh
❯ node index.js --save USD
```

Now if you write 

```sh
❯ node index.js 10 
```

It will give you the change of 10 USD into EUR



## Authors

Aria Ekhteraei
ESILV, A4
IBO3

