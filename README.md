# tsplit - Trivial split for strings with escaped charactes and quotes

## Usage
```python
from tsplit import tsplit

tsplit('qqqqq/qqq"qqq/qq"qqq/qqqqqq|/qqqqq', quote='"', delimiter='/', escape='|')

```