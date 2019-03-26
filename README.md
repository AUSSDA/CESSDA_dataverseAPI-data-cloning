# CESSDA Dataverse API data cloning (Proof of Concept)

A python script to show, that a Dataverse instance can be cloned via it's API. For this, we downloaded a set of datafiles with it's parent datasets, and with their parent dataverses to the local storage. The metadata then gets transformed to the needed file-format for the upload of the dataverses, datasets and data files. Developed by [Stefan Kasberger](http://stefankasberger.at) for [AUSSDA - The Austrian Social Science Data Archive](http://aussda.at/).

**Copyright**

* Code:  [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
* Documentation:  [![License: CC BY 4.0](https://licensebuttons.net/l/by/4.0/80x15.png)](https://creativecommons.org/licenses/by/4.0/)

## INSTALL

```bash
virtualenv --python=/usr/bin/python3 venv
source venv/bin/activate
pip install -r requirements.txt
```

## USE

**Download data**

Pass api token

```bash
API_TOKEN_DOWN=<TOKEN>
API_HOST_DOWN=<HOST>
API_TOKEN_UP=<TOKEN>
API_HOST_UP=<HOST>

```


**Upload data**

