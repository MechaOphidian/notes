# Python Package Management

## Interacting with `pip` as a **python module**

### NOTE: **_Required_** for updating `pip` on Windows

`python -m pip`

## Checking for updates to `pip` and installed packages
`pip list -o`

## Updating `pip` with `pip` (Windows Only!)

#### NOTE: `pip` gets updated before anything else!

`python -m pip install -U pip`

## Updating packages

### `wheel` and `setuptools` ***ALWAYS*** get installed and updated before other packages!

`python -m pip install -U wheel setuptools`

## Updating & Installing package lists with `pip`

### NOTE: Version controlled lists are accepted, otherwise tries newest versions. 

`python -m pip install -r requirements.txt`

## Using `pip` to freeze relevant packages for `requirements.txt`, overwriting existing file in pwd.

`pip freeze > requirements.txt`