# Pipenv Cheat Sheet

## Taken From

```
Traversy Media
Cheat Sheet: https://gist.github.com/bradtraversy/c70a93d6536ed63786c434707b898d55#file-pipenv_cheat_sheet-md
Youtube: https://www.youtube.com/channel/UC29ju8bIPH5as8OGnQzwJyA
```

## Pipenv Doc

```
Documentation: [link](https://pipenv.readthedocs.io/en/latest/)
Basic_Usage: [link](https://pipenv.readthedocs.io/en/latest/basics/#general-recommendations-version-control)
```

## Install pipenv

```
pip3 install pipenv
```

## Activate

```
pipenv shell
```

## Check version of Python

```
python --version
```

## Check path

```
python
>>> import sys
>>> sys.executable
quit()
```

## Install a package

```
pipenv install camelcase
```

## Install from Pipfile
```
pipenv install
```

## Check local packages

```
pipenv lock -r
```

## Uninstall a package

```
pipenv uninstall camelcase
```

## Install a dev package

```
pipenv install nose --dev
```

## Install from requirements.txt

```
pipenv install -r ./requirements.txt
```

## Check security vulnerabilities

```
pipenv check
```

## Check dependency graph

```
pipenv graph
```

## Ignore pipfile

```
pipenv install --ignore-pipfile
```

## Set lockfile - before deployment

```
pipenv lock
```

## Exiting the virtualenv

```
exit
```

## Run with pipenv

```
pipenv run *
```
