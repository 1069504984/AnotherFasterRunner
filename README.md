# FasterRunner

[![LICENSE](https://img.shields.io/github/license/yinquanwang/FasterRunner.svg)](https://github.com/yinquanwang/FasterRunner/blob/master/LICENSE) [![travis-ci](https://travis-ci.org/yinquanwang/FasterRunner.svg?branch=master)](https://travis-ci.org/yinquanwang/FasterRunner) ![pyversions](https://img.shields.io/pypi/pyversions/Django.svg)

> FasterRunner that depends FasterWeb


## Build Development

``` bash
# install requirements.txt
pip install -r requirements.txt

# make migrations for fastuser、fastrunner
python manage.py makemigrations fastrunner fastuser

# migrate for database
python manage.py migrate

# runserver in dev
python manage.py runserver

```



