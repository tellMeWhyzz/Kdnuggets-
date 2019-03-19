最近在做导师的网站项目，在对json文件中的键的顺序改变问题，进一步进行探讨
===

json.dumps({}, sort_keys=True)

from collections import OrderedDict
json.dumps(OrderedDict({}))
