# pyalgotrade_ctp
ctp interface trading support based on pyalgotrde

支持ctp接口直接交易。

1、修改pyalgotrade\pyalgotrade\dataseries\__init__.py 中的参数：
DEFAULT_MAX_LEN = 1024
DEFAULT_MAX_LEN = 8000000

8000000是tbplus中的数据最大限额。应该够用了。
