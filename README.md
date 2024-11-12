# README
## Requirements
~~This experiment is done [Debian 12](https://www.debian.org/) OS.~~
- Docker
- Docker Compose

## Setup Environment
```bash
$ cd /path/t/source
$ docker-compose up -d
```

```additional
$ python3 -m venv --prompt major .venv  # Create virtual environment.
$ source .venv/bin/activate  # Activate virtual environment.
(major) $ python3 -m pip install pipenv
(major) $ pipenv install  # Install dependencies.
(major) $ jupyter-lab
```

Close setup.
```
$ docker-compose down
```
