# Name of the project

DILI database development

Extraction, curation and integration of Biologics clinical data; creating a SQL database and developing a web application for accessing data to build a predictive model for drug induced liver injury 

Any reviewer or researcher within CDER interested in pre-clinical data elements associated with drug induced liver injury in biologics can access the data by creating an account and using the web application developed in this project.

## Installing / Getting started

A quick introduction of the minimal setup you need to get up &
running.

- Python 2.7.11 or latest version
- Pandas, os, fnmatch, xlrd, difflib, re, odo
- Jupyter notebook or copy paste the code into any .py file and run from command line using python
- PostgreSQL 9.6 or higher


Additional requirement:
-Need access to PORTES or EDR data scource


## Developing

Here's a brief intro about what a developer must do in order to start developing
the project further:

```shell
git clone https://github.com/shamszaman99/DILI_database.git
cd DILI_database/
packagemanager install
```

And state what happens step-by-step.

### Building

If your project needs some additional steps for the developer to build the
project after some code changes, state them here:

```
Not applicable
```



### Deploying / Publishing

In case there's some step you have to take that publishes this project to a
server, this is the right time to state it.

```Not applicable
```



## Features

What's all the bells and whistles this project can perform?

* Will find all the xpt files in a given application    
* Extract data from 21 clinical domains
* Will check for SDTM conformity in desired variables within these 21 domains
* Will convert the non-SDTM varable to SDTM variable where variable descriptions have more than 90% similarity
* Will generate a file with desired variables not found in a given application
* Will push the curated datasets to PostgreSQL database
* Finally a web2py based web application will access data from the database and make available to the end users with few query option

## Configuration

Here you should write what are all of the configurations a user can enter when
using the project.

#### Argument 1

Type: `String`  
Default: `'BLA12345'`

```


## Contributing


"If you'd like to contribute, please fork the repository and use a feature
branch. Pull requests are warmly welcome."


## Licensing

One really important part: Give your project a proper license. Here you should
state what the license is and how to find the text version of the license.
Something like:

"This database is solely to be used by the researchers and reviewers within FDA."
