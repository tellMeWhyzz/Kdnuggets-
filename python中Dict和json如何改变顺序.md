最近在做导师的网站项目，在对json文件中的键的顺序改变问题，进一步进行探讨
===

json.dumps({}, sort_keys=True)<br>

from collections import OrderedDict<br>
json.dumps(OrderedDict({}))<br>

参考链接
---
https://stackoverflow.com/questions/10844064/items-in-json-object-are-out-of-order-using-json-dumps
