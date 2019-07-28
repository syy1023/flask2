有一个报错是：


解决方法是在代码中加入：
# encoding=utf8
import sys
reload(sys)
sys.setdefaultencoding('utf-8')


posts.db文件可以用sqite可视化工具打开


同时：
twcns-MacBook-Pro-102:flask2 yuanyuan.shao$ python
Python 2.7.10 (default, Oct  6 2017, 22:29:07)
[GCC 4.2.1 Compatible Apple LLVM 9.0.0 (clang-900.0.31)] on darwin
Type "help", "copyright", "credits" or "license" for more information.
>>> from main import init_db
>>> init_db()


