<p align="center">
  <img src="./logo/flask.svg" width="100" height="100" alt="Sample logo" />
</p>

# flask-session-pymongo

로그인 없이 사용자를 구분하여 사용자 정보를 관리하는 방식을 `Session`이라는 개념을 통하여 구현해 보자.
<br />

## Features
- 세션 정보를 몽고 DB에 저장
- 세션 쿠키에 저장

## Getting Started
- Create virtual environment
    ```bash
    $ mkdir .venv
    $ python -m virtualenv .venv
    $ source ./.venv/bin/activate
    ```

- Install python packages
    ```bash
    (venv)$ pip install -r requirements.txt
    ```

- Run server
    ```bash
    (venv)$ python src/app.py
    ```

## Contributor
- hsboee@gmail.com

## License
MIT.
