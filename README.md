# sklearn_tutorial 中文教程

sklearn_tutorial 中文教程，翻译自 Jake VanderPlas 的 [Scikit-learn Tutorial](https://github.com/jakevdp/sklearn_tutorial.git)。


# Scikit-learn 教程

*Jake VanderPlas*

- email: <jakevdp@uw.edu>
- twitter: [@jakevdp](https://twitter.com/jakevdp)
- github: [jakevdp](http://github.com/jakevdp)

这个代码库包含了[Scikit-learn](http://scikit-learn.org)教程的 notebooks 和其他相关的文件。


## 安装
这个教程需要以下的包:

- Python 版本 2.6-2.7 或者 3.3+
- `numpy` 版本 1.5 或者更新: http://www.numpy.org/
- `scipy` 版本 0.10 或更新: http://www.scipy.org/
- `matplotlib` 版本 1.3 或更高: http://matplotlib.org/
- `scikit-learn` 版本 0.14 或更高r: http://scikit-learn.org
- `ipython` 版本 2.0 或更高, 支持 Jupyter notebook: http://ipython.org
- `seaborn` 版本 0.5 或更高

The easiest way to get these is to use the [conda](https://store.continuum.io/) environment manager.
I suggest downloading and installing [miniconda](http://conda.pydata.org/miniconda.html).

Once this is installed, the following command will install all required packages in your Python environment:
```
$ conda install numpy scipy matplotlib scikit-learn ipython-notebook seaborn
```

Alternatively, you can download and install the (very large) Anaconda software distribution, found at https://store.continuum.io/.

## Downloading the Tutorial Materials
I would highly recommend using git, not only for this tutorial, but for the
general betterment of your life.  Once git is installed, you can clone the
material in this tutorial by using the git address shown above:

    git clone git://github.com/jakevdp/sklearn_tutorial.git

If you can't or don't want to install git, there is a link above to download
the contents of this repository as a zip file.  I may make minor changes to
the repository in the days before the tutorial, however, so cloning the
repository is a much better option.


## Notebook Listing
You can [view the tutorial materials](http://nbviewer.ipython.org/github/jakevdp/sklearn_tutorial/blob/master/notebooks/Index.ipynb) using the excellent nbviewer service.

Note, however, that you cannot modify or run the contents within nbviewer.
To modify them, first download the tutorial repository, change to the notebooks directory, and run ``ipython notebook``.
You should see the list in the ipython notebook launch page in your web browser.
For more information on the IPython notebook, see http://ipython.org/notebook.html

Note also that some of the code in these notebooks will not work outside the
directory structure of this tutorial, so it is important to clone the full
repository if possible.
