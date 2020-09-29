# KFS-School


## Setup

``` bash
$ git clone https://github.com/AcidicNic/KFS-School.git
```

To create a branch:

``` bash
$ git switch -c branch_name
```

To switch to an existing branch:

``` bash
$ git switch branch_name
```

``` bash
$ python3 -m venv .venv
```

``` bash
$ source .venv/bin/activate
```

``` bash
$ pip3 install -r requirements.txt
```

``` bash
$ cd KFS_School
```

``` bash
$ touch .env
```
- Inside .env define your [secret key](https://miniwebtool.com/django-secret-key-generator/) like this:

- ```SECRET_KEY=some_random_key```

``` bash
$ python3 manage.py runserver
```

## Before Pushing

- cd back into the root directory! (the one with README.md)

- If you installed any pip packages:

 - Make sure you're using your virtualenv, then run:

``` bash
$ pip3 freeze > requirements.txt
```
