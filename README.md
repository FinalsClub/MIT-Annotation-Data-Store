#  MIT Annotation Data Store
Data Store and RESTful web API for Annotation Studio, compatible with OKFN Annotator. See: https://github.com/okfn/annotator

##  Derivation
### An alternative to OKFN annotator-store
https://github.com/okfn/annotator-store

## Setup
### Using Heroku
+ Create a heroku app `heroku apps:create $appname`
+ Add the Heroku add-on MongoLab `heroku addons:add mongolab`
+ Get MongoLab configuration settings `heroku config:pull`

There may be times during development that you will want to use
a MongoDB server other than the one hosted by mongolab. To do this,
remove the `MONGOLAB_URI=` line in your `.env` file and add a `DB=`
line with your new URI. The `MONGOLAB_URI` variable takes precedence
over `DB`.

## Dependencies
### OKFN Annotator
https://github.com/okfn/annotator/

## Other
See package.json (NOTE: you will need the versions of node and npm specified in that package file).

## Installation
See https://github.com/hyperstudio/MIT-Annotation-Data-Store/wiki/Installation

## Author
- Lab: MIT HyperStudio
- http://hyperstudio.mit.edu/
- Developer: Jamie Folsom
- jfolsom@mit.edu

## License
GPL2
&copy; MIT 2013
