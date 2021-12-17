# Auto Login Rewards

This script logs in to each account specified in `accounts.yml` and acquires the daily login rewards.

## Assumptions

- The 1920x1280 Fullscreen resolution is used
- User's machine isn't unreasonably slow
- User uses windows

## Requirements

- poetry (can be installed
  with `(Invoke-WebRequest -Uri https://raw.githubusercontent.com/python-poetry/poetry/master/get-poetry.py -UseBasicParsing).Content | python -
  ` in powershell on Windows)

## How to run

- create and fill `accounts.yml` with your credentials (example file: `accounts.example.yml`)
- run `poetry run python main.py`