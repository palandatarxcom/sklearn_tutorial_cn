# sklearn_tutorial 中文教程

sklearn_tutorial 中文教程，翻译自 Jake VanderPlas 的 [Scikit-learn Tutorial](https://github.com/jakevdp/sklearn_tutorial.git)。


# Scikit-learn 教程

*Jake VanderPlas*

- email: <jakevdp@uw.edu>
- twitter: [@jakevdp](https://twitter.com/jakevdp)
- github: [jakevdp](http://github.com/jakevdp)

*派兰数据*

- email: <public@datarx.cn>
- 微博: [@派兰数据](http://weibo.com/datarx)
- github: [palandatarxcom](http://github.com/palandatarxcom)


这个代码库包含了[Scikit-learn](http://scikit-learn.org)教程 notebook 和其他相关的文件。


## 安装
这个教程需要以下的包:

- Python 版本 2.6-2.7 或者 3.3+
- `numpy` 版本 1.5 或者更新: http://www.numpy.org/
- `scipy` 版本 0.10 或更新: http://www.scipy.org/
- `matplotlib` 版本 1.3 或更高: http://matplotlib.org/
- `scikit-learn` 版本 0.14 或更高: http://scikit-learn.org
- `ipython` 版本 2.0 或更高， 支持 Jupyter notebook: http://ipython.org
- `seaborn` 版本 0.5 或更高

最方便的办法是使用 [conda](https://store.continuum.io/) 管理工具。 我建议下载和安装 [miniconda](http://conda.pydata.org/miniconda.html)。

安装好以后，执行下面的命令将在你的 Python 环境下安装所有需要的包

```
$ conda install numpy scipy matplotlib scikit-learn ipython-notebook seaborn
```

另外一个方法，你可以下载和安装完整的 Anaconda 分发包(但是非常大)， https://store.continuum.io/.


## 下载教程的课件

我强烈建议使用 git，不仅仅只是为这个教程，也是为改善你的生活。 一旦 git 安装好，你可以将这个教程的所有资料克隆下来：

    git clone git://github.com/jakevdp/sklearn_tutorial.git

如果你无法或者不愿安装 git，上面有一个代码库的 zip 文件供你下载。 我可能会对这个教程做一些微小的改动，所以克隆整个代码库是较好的一个选择。


## Notebook 清单
你可以通过 nbviewer 这个不错的服务[浏览教程的课件](http://nbviewer.ipython.org/github/palandatarxcom/sklearn_tutorial_cn/blob/master/notebooks/Index.ipynb)

请注意，你无法在 nbviewer 中修改或者运行教程的内容。 如果要修改，第一步是下载教程的代码库，切换到 notebooks 目录下面，然后执行 ``jupyter notebook``。 你应该会在 Jupyter notebook 唤起的浏览器里面看到这个清单。 需要更多了解 Jupyter notebook，请参考 http://ipython.org/notebook.html

另外也请注意，部分的代码在这个教程的目录结构之外是无法运行的，因此如果可能把整个代码库克隆下来是很重要的。

【译者注】这个教程的全部内容已经安装在派兰数据分析平台上了，注册并登陆 http://palandata.com ，不需要安装相关环境，也不需要克隆整个代码库，即可可以交互式地学习 sklearn 了。