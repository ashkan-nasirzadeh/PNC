# PNC

programming naming convention

you want to choose a name for a column in a user_table in a database? you may use `fname` but sometimes `firstName` or  `fn` or what! I want to be solid in these kinds of issues so actually we need a convention for most common names that we frequently use in variables, functions, classes, project directories and even for naming a column in a table of a database

here I want (I wish) to write down this convention with the aid of the programmers in all over the world

## general rules

## project directories
---
| directory name |                    meaning          |
| :----------: | :---------------------------------: |
| vendor | the conventional location for all **third-party codes** in a project |
| assets | - | 
| includes | - |
| libs | - |
| test | - |
| demo | - |
| src | - |
| dist | - |
| docs | - |
## variables
---
### single and two letter prefixes
single letter prefixes is about abstracting traditional prefixes that many developers use in their programs for example we may use `newUser`,`newShoppingCard`,`newIP` and so on , so from now on we'll use `nUser`,`nShoppingCard`,`nIP`,...

rule #1: single letter prefixes should use only in camelCase style (e.g. nuser is wrong while nUser is valid)
| abbreviation |                    meaning          | example |
| :----------: | :---------------------------------: | :-----: |
| n | new | nRoff = new roff |
| r | response | rCode = response code |
| re | requested | reItem = requested item |
| s | status | sCode = status code |
### preserved variables
we use this variable names just for one purpose in through the entire program
| abbreviation |                           meaning                            |
| :----------: | :----------------------------------------------------------: |
| result | just for the returned value from a method |
| db | data base |
| pass | password |
| conn | connection |
## database columns
---
| abbreviation |                           meaning                            |
| :----------: | :----------------------------------------------------------: |
|    fName     |                          first name                          |
|    sName     |     last name / surname (we don't use lname becase l(L lowercase) and I(i uppercase) are indistinguishable) |
|    uName     |                         user name                          |
|    phone     |                         phone number                         |
|     cell     |                       cellphone number                       |
|    ssNum     |      social security number / personal identity number       |
|    price     |             price of an item / cost of a service             |
|    cost    |     total costs of a shopping bag / total services costs     |
|   birth    |                    birthday in timestamp                     |
|      ID      | *the point is to use "ID" (CAPITAL) everywhere in a database not "id"* |

## functions
---
## classes
---
## README.md files
---
the key point in these kind of files is that we should use specific unit headers:
| header |                           meaning                            |
| :----------: | :----------------------------------------------------------: |
| Installation | the instruction of how to install/use this source code |
| Basic Usage | a quick sample code to illustrate how this tool works |
| Documentation | the specifications, manuals, documents and tutorials about this source code |
| About | requirements, how bug submission, author, license, acknowledgements, etc |

