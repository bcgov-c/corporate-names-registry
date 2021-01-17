# Namer #
![License Apache 2.0](https://img.shields.io/badge/license-Apache%202.0-blue.svg)

[![img](https://img.shields.io/badge/Lifecycle-Retired-d45500)](https://github.com/bcgov/repomountie/blob/master/doc/lifecycle-badges.md) 
The project is no longer being used and/or supported.

Rapid Name Search

## Dependencies ##

- npm
- python 3.6

## Installation ##

### Docker ###

1. `docker build . -t namer`
2. `docker run --rm -it -p 5000:5000 namer`
3. Visit the URL mentioned after "Serving corporate names on "

### Manual ###

For Namer to work, both the front-end and back-end must be started.

**NPM (Front End)**

1. `cd namer/static/js/app`
2. `npm install`
3. Run the following depending on your environment:
    - Deployment: `npm run build`
    - Development: `npm start`

**Python (Back End)**

1. Change to root repository folder (`cd ../../../..`)
2. `pip install -r requirements.txt`
3. `python namer/wsgi.py`
4. Visit the URL mentioned after "Serving corporate names on "

## Tests ##

To Be Determined
