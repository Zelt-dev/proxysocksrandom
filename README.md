# proxysocksrandom

[![PyPI](https://img.shields.io/pypi/v/proxysocksrandom.svg)](https://pypi.org/project/proxysocksrandom/)

`proxysocksrandom` is a Python module that provides functionality to fetch and use random SOCKS5 and HTTPS proxies from various sources.

## Installation

```pip install proxysocksrandom```

## Usage

```python
from proxysocksrandom import Proxies

proxies = Proxies()
proxies.initialize()

proxy = proxies.get_proxy('socks5')
print(proxy)
```
