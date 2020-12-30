[![pypi](https://img.shields.io/pypi/v/pybadges.svg)](https://pypi.org/project/diem/)
![Apache V2 License](https://img.shields.io/badge/license-Apache%20V2-blue.svg)

[Documentation](diem/index.html)

## Example

```python

>>> from diem import jsonrpc, testnet
>>> client = jsonrpc.Client(testnet.JSON_RPC_URL)
>>> client.get_metadata()
version: 3300304
timestamp: 1601492912847973
chain_id: 2

```
