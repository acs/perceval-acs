# perceval-acs

Bundle of experimental Perceval backends from acs

## Backends

The backends currently managed by this package support the next repositories:

* OpenFDA

## Requirements

* Python >= 3.4
* python3-requests >= 2.7
* perceval > 0.4

## Installation

To install this package you will need to clone the repository first:

```
$ git clone https://github.com/acs/perceval-acs.git
```

In this case, [setuptools](http://setuptools.readthedocs.io/en/latest/) package will be required.
Make sure it is installed before running the next commands:

```
$ pip3 install -r requirements.txt
$ python3 setup.py install
```

## Examples

### OpenFDA

```
$ perceval openfda --from-date 2017-01-01
```

## License

Licensed under GNU General Public License (GPL), version 3 or later.
