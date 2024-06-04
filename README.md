# Leap Year Kata

## Requirements

> Every year that is exactly divisible by four is a leap year, except
> for years that are exactly divisible by 100, but these centurial years
> are leap years if they are exactly divisible by 400. For example, the
> years 1700, 1800, and 1900 are not leap years, but the years 1600 and
> 2000 are.

- 2024 is a leap year - True/False
- 1821 is not a leap year - Typical Normal Year (Not Divisible by 4)
- 1600 is a leap year - Divisible by 100
- 1900 is an atypical non-leap year (Divisible by 100, but not 400)
- 1500 is a...

## Useful commands

Getting poetry using [pipx](https://pipx.pypa.io/stable/installation/)

``` shell
pipx ensurepath # Make sure you will be able to run `poetry` and not `pipx run poetry`
pipx install poetry
```

Running the tests

``` shell
poetry run pytest
```

Running the linter

``` shell
poetry run mypy . 
poetry run ruff check . 
```

Automated fixers

``` shell
poetry run ruff check --fix . 
poetry run ruff format . 
```
