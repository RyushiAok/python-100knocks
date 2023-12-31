[![Checked with mypy](https://www.mypy-lang.org/static/mypy_badge.svg)](https://mypy-lang.org/)
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)
[![Imports: isort](https://img.shields.io/badge/%20imports-isort-%231674b1?style=flat&labelColor=ef8336)](https://pycqa.github.io/isort/)

# Python 100 Knocks
## Installation
```sh
pyenv local 3.11.x
poetry install
poetry run pre-commit install
```
## Run
```sh
# polars 100knocks
poetry run task polars100

# nlp 100knocks
poetry run task nlp100
```
## Test
```sh
poetry run task test
# or
poetry run pytest
```

# Links
- データサイエンス100本ノック（構造化データ加工編）
  - https://github.com/The-Japan-DataScientist-Society/100knocks-preprocess
  - [問題](https://github.com/The-Japan-DataScientist-Society/100knocks-preprocess/blob/3a42834163382c38362f4554be47ac3324fbe400/docker/work/answer/ans_preprocess_knock_Python.ipynb)
- 解答は以下を参考にしています
  - https://qiita.com/_jinta/items/28442d25bba067c13bb7
  - https://qiita.com/_jinta/items/394b1682893e5991d592
  - https://qiita.com/hkzm/items/8427829f6aa7853e6ad8
