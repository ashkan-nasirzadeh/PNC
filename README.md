# PNC

programming naming convention

you want to choose a name for a column in a user_table in a database? you may use `fname` but sometimes `firstName` or  `fn` or what! I want to be solid in these kinds of issues so actually we need a convention for most common names that we frequently use in variables, functions, classes, project directories and even for naming a column in a table of a database

here I want (I wish) to write down this convention with the aid of the programmers in all over the world

## general rules
### single letter prefixes
single letter prefixes is about abstracting traditional prefixes that many developers use in their programs for example we may use `newUser`,`newShoppingCard`,`newIP` and so on , so from now on we'll use `nUser`,`nShoppingCard`,`nIP`,...

rule #1: single letter prefixes should use only in camelCase style (e.g. nuser is wrong while nUser is valid)
| abbreviation |                           meaning                            |
| :----------: | :----------------------------------------------------------: |
| n | new |

## project directories

## variables
### preserved variables
we use this variable names just for one purpose in through the entire program
| abbreviation |                           meaning                            |
| :----------: | :----------------------------------------------------------: |
| result | just for the returned value from a method |
## database columns

| abbreviation |                           meaning                            |
| :----------: | :----------------------------------------------------------: |
|    fname     |                          first name                          |
|    lname     |                     last name / surname                      |
|    mname     |                         middle name                          |
|    phone     |                         phone number                         |
|     cell     |                       cellphone number                       |
|    ssnum     |      social security number / personal identity number       |
|    price     |             price of an item / cost of a service             |
|    prices    |     total costs of a shopping bag / total services costs     |
|   birthTS    |                    birthday in timestamp                     |
|      ID      | *point is to use "ID" (CAPITAL) everywhere in a database not "id"* |

## functions

## classes

