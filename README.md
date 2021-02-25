<img src="https://logos-download.com/wp-content/uploads/2016/10/Python_logo_wordmark.png" width=256 height=64 align="left">


# 10分钟快速入门

## Python的版本

* Python的版本号表示为Python major.minor.bugfix。其中major版本基本不变，minor版本具有新的和增强功能，bugfix版本是错误修正和安全补丁。 

* Python 2.x.x已于2020年1月1日正式终止 (2.7.16)。目前官方仅支持3.5.x及后续版本，其中最新版为2019年12月18日发布的3.8.1。

* Python 3.x.x并不向下兼容Python 2.x.x。一些使用Python 2.x.x语法和库的程序，不经过修改无法在Python 3.x.x上运行。

## Python的安装

### 方法一：Anaconda

[Anaconda](https://www.anaconda.com/)是一个免费开源、用于科学计算的Python发行版。它提供了软件包管理工具Conda和用户图形界面Anaconda Navigator，大大简化了Python环境配置和软件包的管理和部署。用户可以通过Anaconda Navigator启动应用（比如JupyterLab），配置Python运行环境，安装和升级软件包等。可以利用Conda命令更新到最新版本：
~~~
conda update conda
~~~

建议初学者用此方法安装和使用Python。典型安装将占用3GB的硬盘空间。如需减少空间占用，可选择安装[Miniconda](https://docs.conda.io/en/latest/miniconda.html)（约400MB），再使用Conda命令安装需要的软件包，如
~~~
conda install numpy
conda install anaconda-navigator
~~~
必要的软件包包括：
* [NumPy](https://www.numpy.org)：高维数组与矩阵运算库
* [SciPy](https://www.scipy.org)：算法库和数学工具包
* [Matplotlib](https://matplotlib.org/)：图形绘制库

其他建议安装的软件包包括：
* [JupyterLab](https://jupyter.org/)或Jupyter Notebook：基于Web的交互式计算平台
* Anaconda Navigator：Anaconda的图形用户界面

---
```octave
a=4             #整数
b=3.1           #浮点数
c=a+b*(0+1.0j)  #复数
d=0xe           #十六进制整数
a,b,c,d
```
---

<pre><code>This is a code block.
</code></pre>

~~~markdown
This is some text
```js
console.log('Hello, World!');
```

```js
console.log('Hello, World!');
```
~~~

> fds
