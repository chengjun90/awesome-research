[Python 资源大全中文版](https://github.com/jobbole/awesome-python-cn)


# 版本与包管理

- pip  
官方的包管理器

- Conda

- [pipenv](https://github.com/pypa/pipenv)  
Python官方机构推荐的Python虚拟环境工具

# 网络/爬虫
- requests  
http请求库

- [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/)  
提取网页信息

- [requests-html](http://html.python-requests.org)，解析html，提取相应的元素

- lxml  
快速定位网页信息

- chardet  
测试网页编码，和文件编码

- [requestium](https://github.com/tryolabs/requestium)  

- [Scrapy](https://scrapy.org)，爬虫框架

- Pyspider，国产爬虫框架

# 自然语言处理
- FlashText  
在处理大规模文本时性能优于re库

- [Jieaba](https://github.com/fxsjy/jieba)  
最好用的中文分词库。

- NLTK  
提供了文本标记、分词、构建语料树等功能，用以揭示句中或句间的依赖关系。

- [Gensim](https://radimrehurek.com/gensim/index.html)  
进行主题建模、文档索引和文本相似度分析。[官网教程](https://radimrehurek.com/gensim/tutorial.html)。

- [Synonyms](https://github.com/huyingxi/Synonyms)，开源的中文近义词工具包

# 文件读写

## pdf
- pdfrw：读写pdf

- [PyPDF2](https://github.com/mstamy2/PyPDF2),能够分割、合并、裁剪和转换PDF 文件页面。它还可以添加自定义数据、查看选项和密码到 PDF 文件。

PyPDF2 可以从 PDF 中检索文本和元数据

- pdfminer3k：抽取pdf信息

## word
[python-docx](https://python-docx.readthedocs.io/en/latest/)：docx文档读写

## 处理excel
- openpyxl,读写和处理xlsx

- xlsxwriter,写xlsx

## csv
- [csvkit](https://github.com/wireservice/csvkit)
> A suite of utilities for converting to and working with CSV, the king of tabular file formats.

## 其他
- [tablib](https://github.com/kennethreitz/tablib)
> A suite of utilities for converting to and working with CSV, the king of tabular file formats.

- [mistune](https://github.com/lepture/mistune)
> The fastest markdown parser in pure Python with renderer feature.
# 可视化

## 静态

- [Matplotlib](https://github.com/matplotlib/matplotlib)


- [Seaborn](http://seaborn.pydata.org)


## 动态

- [Bokeh](https://bokeh.pydata.org/en/latest/)


# 图像处理
- [PILLOW](https://github.com/python-pillow/Pillow)

# 科学计算

- [NumPy](http://www.numpy.org)

- [SciPy](https://www.scipy.org/scipylib/index.html)

- [numexpr](https://github.com/pydata/numexpr)

# 数据分析框架

- [pandas](http://pandas.pydata.org)

数据整理与基础分析

- [dask](https://dask.pydata.org/en/latest/)

- [The Blaze Ecosystem](http://blaze.pydata.org/)

- [xarray](https://github.com/pydata/xarray)：N-D labeled arrays and datasets in Python，把pandas引入物理学

- [Python for Data, Github](https://github.com/pydata)，如xarray和numexpr等。

# 时间处理

datetime库是Python自带的库，是通用库，所以有点复杂。第三方提供了更简洁的包，如Pendulum和Arrow等。

- [Arrow](https://github.com/crsmithdev/arrow/)

- [Pendulum](https://github.com/sdispater/pendulum)

更好用的时间处理库。吐槽了[Arrow](https://github.com/crsmithdev/arrow/)。

# 统计分析

- [Statsmodels](http://www.statsmodels.org/stable/index.html)

Python 中一个强大的统计分析包，包含了回归分析、时间序列分析、假设检验等等的功能。Statsmodels 在计量的简便性上是远远不及 Stata 等软件的，但它的优点在于可以与 Python 的其他的任务（如 NumPy、Pandas）有效结合，提高工作效率。

- [PyFlux](https://github.com/RJT1990/pyflux)

时间序列分析包，提供了ARIMA、GARCH和VAR等模型。

# 机器学习/深度学习

## 机器学习
- [SciKit-Learn](http://scikit-learn.org)
提供了准确、统一的接口，可以方便地使用各种机器学习算法

## 深度学习
- Tensorflow

- PyTorch

- mxnet

- Keras

- Theano 

# 交互式分析/展示
- [spyder](https://github.com/spyder-ide/spyder)，IDE，适合数据科学从业者使用

- [IPython](http://ipython.org)，可以使用

- [qtconsole](https://github.com/jupyter/qtconsole),jupyter-qtconsole

- [jupyterlab](https://github.com/jupyterlab/jupyterlab)

- [dash](https://plot.ly/dash/)

# 性能提升

- [Cython](https://github.com/cython/cython)

- Numba

# 其他
- APScheduler  
任务调度框架，可以设置定时的任务，如定时下载文件等。

