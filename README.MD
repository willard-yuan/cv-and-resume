### Mac版本

 1.Mac下搭建latex环境。MacTex+Sublime+Skim，具体安装步骤可以参阅[在Mac上通过Sublime、Skim编辑LaTeX](http://painterlin.com/2014/08/10/Using-LaTeX-with-Sublime-and-Skim-for-Mac.html),这篇文章讲得很详细了，另外需要补充的是编译出现：

```sh
LaTeXTools: you need to migrate your preferences. See the README file for instructions.
```

 打开Pallte（Command + Shift + P）输入如下命令即可:

```sh
LaTeXTools: Reconfigure and migrate setting
```

具体参考见这里：[Mac上配置LaTex+Sublime Text 2+Skim环境](http://xjzhou4u.lofter.com/post/2fe98e_44b83ec)。

配置完后默认的是latex(or pdflatex)引擎模版，所以如果要用xelatex编译引擎的话，需要在tex文件里显示的指出，即在tex的首行添加`%!TEX program = xelatex`即可，

2.添加中文字体支持。中文字体使用`xeCJK`宏包，具体怎么配置中文字体可以参阅[为 MacTeX 配置中文支持](http://liam0205.me/2014/11/02/latex-mactex-chinese-support/)，这篇文章讲得很详细，一路跟着毫无障碍。

### 优化方案

1. [modify size of blank spaces](http://tex.stackexchange.com/questions/82861/moderncv-modify-size-of-blank-spaces).
2. [How to change title font size in moderncv?](http://tex.stackexchange.com/questions/128052/how-to-change-title-font-size-in-moderncv)
3. [Changing margins in moderncv](http://tex.stackexchange.com/questions/12996/changing-margins-in-moderncv)

~~~text
As written in the template, you can use the following command in the preamble;
\setlength{\hintscolumnwidth}{3cm}

Change "3cm" by whatever length you wish.
~~~

