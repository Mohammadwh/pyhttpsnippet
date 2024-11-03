# pyhttpsnippet
simpel lib to convert raw http request to python object.

``` python
from pyhttpsnippet import HttpToRequestsConverter

raw = open("request.txt",'r').read()
py = HttpToRequestsConverter(raw)
print(py.headers)
print(py.cookies)
print(py.body)
print(py.url)
print(py.method)

```
```
pip install pyhttpsnippet
```
enjoy it :D
