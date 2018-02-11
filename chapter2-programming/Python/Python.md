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

- lxml  
快速定位网页信息

- chardet  
测试网页编码，和文件编码

- [Scrapy](https://scrapy.org)

- [requestium](https://github.com/tryolabs/requestium)  
> Integration layer between Requests and Selenium for automation of web actions.  
可以一试

# 自然语言处理
- FlashText  
在处理大规模文本时性能优于re库

- [Jieaba](https://github.com/fxsjy/jieba)  
最好用的中文分词库。

- NLTK  
提供了文本标记、分词、构建语料树等功能，用以揭示句中或句间的依赖关系。

- [Gensim](https://radimrehurek.com/gensim/index.html)  
进行主题建模、文档索引和文本相似度分析。官网教程[点击这里](https://radimrehurek.com/gensim/tutorial.html)。

- [Synonyms](https://github.com/huyingxi/Synonyms)，开源的中文近义词工具包

# 文件读写


dash：采用纯Python创建交互式，响应式Web应用的库

## pdf
pdfrw：读写pdf

pdfminer3k：抽取pdf信息

## word
[python-docx](https://python-docx.readthedocs.io/en/latest/)：docx文档读写

## 处理excel
- openpyxl

- xlsxwriter

# 可视化

- 静态

Matplotlib

Seaborn

- 动态

Bokeh

# 图像处理
- PILLOW

- Luminoth

# 科学计算

- NumPy

- SciPy

- numexpr

# 数据分析框架

- pandas

数据整理与基础分析

- xarray

多维度数据结构

[Blaze](http://blaze.readthedocs.io/en/latest/index.html)

# 时间处理

datetime库是Python自带的库，是通用库，所以有点复杂。第三方提供了更简洁的包，如Pendulum和Arrow等。

- [Arrow](https://github.com/crsmithdev/arrow/)

- [Pendulum](https://github.com/sdispater/pendulum)

更好用的时间处理库。吐槽了[Arrow](https://github.com/crsmithdev/arrow/)。

# 统计分析

- Statsmodels

Python 中一个强大的统计分析包，包含了回归分析、时间序列分析、假设检验等等的功能。Statsmodels 在计量的简便性上是远远不及 Stata 等软件的，但它的优点在于可以与 Python 的其他的任务（如 NumPy、Pandas）有效结合，提高工作效率。

- [PyFlux](https://github.com/RJT1990/pyflux)

时间序列分析包，提供了ARIMA、GARCH和VAR等模型。

#机器学习/深度学习

- SciKit-Learn  
提供了准确、统一的接口，可以方便地使用各种机器学习算法

- Theano 

- Tensorflow 

- Keras

- PyTorch

- Caffe2

# 交互式分析/展示
- IPython

- Jupyter NoteBook

- jupyterlab

- [Dash](https://plot.ly/products/dash/)

网页展示。

# 性能提升

- Cython

- Numba

# 其他
- APScheduler  
Python下的任务调度框架，全程为Advanced Python Scheduler。可以设置定时的任务，如定时下载文件等。