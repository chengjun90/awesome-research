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

## pdf
- pdfrw：读写pdf

- [PyPDF2](https://github.com/mstamy2/PyPDF2)
> PyPDF2 is a pure-python PDF library capable of splitting, merging together, cropping, and transforming the pages of PDF files. It can also add custom data, viewing options, and passwords to PDF files. It can retrieve text and metadata from PDFs as well as merge entire files together.

- pdfminer3k：抽取pdf信息

## word
[python-docx](https://python-docx.readthedocs.io/en/latest/)：docx文档读写

## 处理excel
- openpyxl

- xlsxwriter

## csv
- [csvkit](https://github.com/wireservice/csvkit)
> A suite of utilities for converting to and working with CSV, the king of tabular file formats.

## 其他
- [tablib](https://github.com/kennethreitz/tablib)
> A suite of utilities for converting to and working with CSV, the king of tabular file formats.

- [mistune](https://github.com/lepture/mistune)
> The fastest markdown parser in pure Python with renderer feature.
# 可视化

- 静态

- [Matplotlib](https://github.com/matplotlib/matplotlib)
> Matplotlib is a Python 2D plotting library which produces publication-quality figures in a variety of hardcopy formats and interactive environments across platforms. Matplotlib can be used in Python scripts, the Python and IPython shell (à la MATLAB or Mathematica), web application servers, and various graphical user interface toolkits.

- [Seaborn](http://seaborn.pydata.org)
> Seaborn is a Python visualization library based on matplotlib. It provides a high-level interface for drawing attractive statistical graphics.

- 动态

- [Bokeh](https://bokeh.pydata.org/en/latest/)
> Bokeh is a Python interactive visualization library that targets modern web browsers for presentation. Its goal is to provide elegant, concise construction of novel graphics in the style of D3.js, and to extend this capability with high-performance interactivity over very large or streaming datasets. Bokeh can help anyone who would like to quickly and easily create interactive plots, dashboards, and data applications.

# 图像处理
- [PILLOW](https://github.com/python-pillow/Pillow)

# 科学计算

- [NumPy](http://www.numpy.org)

- [SciPy](https://www.scipy.org/scipylib/index.html)

- [numexpr](https://github.com/pydata/numexpr)

# 数据分析框架

- [pandas](http://pandas.pydata.org)

数据整理与基础分析

- [xarray](https://github.com/pydata/xarray)

多维度数据结构

[Blaze](http://blaze.readthedocs.io/en/latest/index.html)

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

- Keras

- Theano 

- PyTorch

- Caffe2

- [luminoth](https://github.com/tryolabs/luminoth)
> Deep Learning toolkit for Computer Vision

# 交互式分析/展示
- [IPython](http://ipython.org)

- Jupyter NoteBook

- [jupyterlab](https://github.com/jupyterlab/jupyterlab)
> An extensible environment for interactive and reproducible computing, based on the Jupyter Notebook and Architecture.
> JupyterLab is the next-generation user interface for Project Jupyter. It offers all the familiar building blocks of the classic Jupyter Notebook (notebook, terminal, text editor, file browser, rich outputs, etc.) in a flexible and powerful user inteface that can be extended through third party extensions. Eventually, JupyterLab will replace the classic Jupyter Notebook after JupyterLab reaches 1.0.

- [dash](https://plot.ly/dash/)
> Dash is a productive Python framework for building web applications.  
> Written on top of Flask, Plotly.js, and React.js, Dash is ideal for building data visualization apps with highly custom user interfaces in pure Python. It's particularly suited for anyone who works with data in Python.

# 性能提升

- [Cython](https://github.com/cython/cython)
> Cython is an optimising static compiler for both the Python programming language and the extended Cython programming language (based on Pyrex). It makes writing C extensions for Python as easy as Python itself.

- Numba

# 其他
- APScheduler  
Python下的任务调度框架，全程为Advanced Python Scheduler。可以设置定时的任务，如定时下载文件等。
