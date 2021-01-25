## Overview ##
The hub-rest-api-python provides Python bindings for Hub REST API.

This is the Synamedia fork of this Open Source repository. The default branch is synamedia. The master branch is the original repo default branch.

```
git clone https://github.com/synamedia/hub-rest-api-python.git
cd hub-rest-api-python
pip3 install -r requirements.txt
pip3 install .
```
### Configure your connection
Create a token in BlackDuck for your user or generic account

`cp restconfig.json.api_token.example .restconfig.json`

Update restconfig.json with your credentials

## Migrating Synamedia pipeline scripts
We have migrated the `generate_reports.py` script to the internal GitHub Enterprise server. OSCP organisation, scripts repository.
Please update your pipelines to use the script from there as there will not be any more updates to the version here.

## Documentation ##
Documentation for hub-rest-api-python can be found on the base project:  [Hub REST API Python Wiki](https://github.com/blackducksoftware/hub-rest-api-python/wiki)

