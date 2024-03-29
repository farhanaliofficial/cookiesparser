# cookiesparser

[![GitHub](https://img.shields.io/github/license/farhanaliofficial/cookiesparser)](https://github.com/farhanaliofficial/cookiesparser/blob/main/LICENSE)
[![GitHub release (latest by date)](https://img.shields.io/github/v/release/farhanaliofficial/cookiesparser)](https://github.com/farhanaliofficial/cookiesparser/releases)
[![PyPI](https://img.shields.io/pypi/v/cookiesparser)](https://pypi.org/project/cookiesparser/)

# Description
cookiesparser is a Mini Module for Parsing Cookies.

# Installation
You can install cookiesparser using pip:
```
pip install cookiesparser
```

# Usage
```python
from cookiesparser import (parse, encode_cookies)

c = "foo=bar; id=191002929; key=avjwowuejbnwoqo; bar=foo;"
parsed = parse(c)
encoded = encode_cookies(parsed)

print("Orignal: %s" % (c))
print("Parsed: %s" % (parsed))
print("Encoded: %s" % (encoded))
```
 # Output
 ```
Orignal: foo=bar; id=191002929; key=avjwowuejbnwoqo; bar=foo;
Parsed: {'foo': 'bar', 'id': '191002929', 'key': 'avjwowuejbnwoqo', 'bar': 'foo'}
Encoded: foo=bar; id=191002929; key=avjwowuejbnwoqo; bar=foo
```

# Contributing
Contributions are welcome! If you encounter any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request on the [GitHub repository](https://github.com/farhanaliofficial/cookiesparser).

# License
cookiesparser is released under the [Apache License](https://github.com/farhanaliofficial/cookiesparser/blob/main/LICENSE).
