### 依赖包

#### jieba分词

#### matplotlib画图pyplot

#### pyecharts

[pyecharts中文手册](https://pyecharts.org/#/zh-cn/intro)

#### wordcloud词云

#### snownlp情感分析

#### selenium模拟浏览器

[查找带空格的class name](https://stackoverflow.com/questions/47660523/selenium-python-finding-elements-by-class-name-with-spaces)  需要变换driver.find_element_by_css_selector('.class1.class2.class3')

[输入退格删除键](https://stackoverflow.com/questions/27338742/how-do-i-send-a-delete-keystroke-to-a-text-field-using-selenium-with-python)   send_keys(Keys.BACKSPACE)  另外一个是删除光标后的send_keys(Keys.DELETE)

#### numpy

[中文网站](https://www.numpy.org.cn/)

> NumPy是使用Python进行科学计算的基础软件包



#### openpyxl 读写excel 2010

[主页](https://openpyxl.readthedocs.io/en/stable/)

#### xlrd/xlwt

 xlrd是读excel，xlwt是写excel的库。

> **openpyxl 与xlrd/xlwt比较：**两者都是对于excel文件的操作插件，两者的主要区别在于写入操作，其中xlwt针对Ecxec2007之前的版本，即.xls文件，其要求单个sheet不超过65535行，而openpyxl则主要针对Excel2007之后的版本（.xlsx），它对文件大小没有限制。另外还有区别就是二者在读写速度上的差异，xlrd/xlwt在读写方面的速度都要优于openpyxl，但因为xlwt无法生成xlsx是个硬伤，所以想要尽量提高效率又不影响结果时，可以考虑用xlrd读取，用openpyxl写入。
>
> 使用实例：[例子](http://wenqiang-china.github.io/2016/05/13/python-opetating-excel/)



#### pandas

[pandas中文网](https://www.pypandas.cn/)

> Pandas是一个强大的分析结构化数据的工具集；DataFrame是Pandas中的一个表格型的数据结构

[官方教程](https://www.pypandas.cn/docs/getting_started/tutorials.html#%E5%AE%98%E6%96%B9%E6%8C%87%E5%8D%97)  [在线手册](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.Series.value_counts.html#pandas.Series.value_counts) [离线手册](D:\Python\pandas)

#### request



#### beautifuSoup

> [Beautiful Soup](http://www.crummy.com/software/BeautifulSoup/) 是一个可以从HTML或XML文件中提取数据的Python库.它能够通过你喜欢的转换器实现惯用的文档导航,查找,修改文档的方式.

[beautifulSoup中文手册](https://www.crummy.com/software/BeautifulSoup/bs4/doc.zh/)

> 用法：from bs4 import BeautifulSoup

### 安装

1. 写入requirements.txt文件中

2. 切换到豆瓣的pip源
3. pip install -r requirements.txt -i  https://pypi.doubanio.com/simple



### 资料

[Python常用模块](https://vimsky.com/examples/list/python-module-page-1.html)  **列举了各种常用的库和函数在github的使用代码**

[pycharm快捷键](https://www.cnblogs.com/insane-Mr-Li/p/9698994.html)

> Ctrl + Alt + H 查找函数调用
>
> Ctrl + Shift + I查看快速定义
>
> Ctrl + / 注释单行或选中的块



### 问题解决

- selenium.common.exceptions.WebDriverException: Message: 'chromedriver' executable needs to be in PATH. Please see https://sites.google.com/a/chromium.org/chromedriver/home

> [下载chromedriver](https://chromedriver.chromium.org/downloads) 放在C:\Program Files\Python36下面

