# PNC

programming naming convention

there are many advices for how to naming things in your code and there are great books and many good articles about this but eventually what name do you use when you want to choose a name for a user first name in a database table?
the task that you have done it maybe over 100 times and you are sad because you are thinking about this again and again and this double thinking is really a time waster for a very common and easy (actually that's not easy at all) task. a clean and pro programmer won't use something like `fn` at all! but you may want to use `fname` since it's easy for minds to discover the meaning of that and a short meaningfull name is far better than a long one like `firstName`. I want to be **solid** in these kinds of issues so actually we need a convention **for most common names that we frequently use** in variables, functions, classes, project directories and even for naming a column/key in a database

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
| src | The source is used for development. This will usually originate from a source code repository, such as git. |
| dist | The dist is a packaged version of the package data, same source code after minimizing or transplinig or ... |
| docs | - |
| build | this directory will hold the package/software/application when it's created |
## variables
---
these rules can be combined together (e.g. nConnArr(new connection array) or reQueriesCount(requested queries count))
### single/two letter prefixes
single letter prefixes is about abstracting traditional prefixes that many developers use in their programs for example we may use `newUser`,`newShoppingCard`,`newIP` and so on , so from now on we'll use `nUser`,`nShoppingCard`,`nIP`,...

rule #1: single letter prefixes should use only in camelCase style (e.g. nuser is wrong while nUser is valid)
| abbreviation/word |                    meaning          | example |
| :----------: | :---------------------------------: | :-----: |
| n | new | nRoff = new roff |
| r | response | rCode = response code |
| re | requested | reItem = requested item |
| s | status | sCode = status code |
### suffix
| abbreviation/word |                           meaning                            |
| :----------: | :----------------------------------------------------------: |
| arr | only to declare that the variable type is array |
| obj | only to declare that the variable type is object |
| num | only to declare that the variable type is numeric |
| count | only to declare that the variable type is numeric |
| float | only to declare that the variable type is float |
| int | only to declare that the variable type is integer |
| str | only to declare that the variable type is string |
| prop | property |
| props | properties |
### preserved variables
we use this variable names just for one purpose in through the entire program
| abbreviation/word |                           meaning                            |
| :----------: | :----------------------------------------------------------: |
| result | just for the returned value from a method |
| output | only to declare the calculated/determined value of a process |
| auth | authentication/authenticate/authenticated/... |
| val | value |
| var | variable |
| tmp | temporary |
| db | data base |
| pass | password |
| conn | connection |
## database columns/keys
---
| abbreviation/word |                           meaning                            |
| :----------: | :----------------------------------------------------------: |
|    fName     |                          first name                          |
|    sName     |     last name / surname (we don't use lname becase l(L lowercase) and I(i uppercase) are indistinguishable) |
|    uName     |                         user name                          |
|    phone     |                         phone number                         |
|     cell     |                       cellphone number                       |
|    socialSecurityNum     |      social security number / personal identity number       |
| IDCardNum | ID card Number |
|    price     |             price of an item or product / cost of a service             |
|    totalCost    |     total costs of a shopping bag / total services costs     |
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

