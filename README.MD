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

### Job职位

1. 图像处理工程师，[口袋购物](http://hr.koudai.com/join/joinus.html#fb6)
2. 算法工程师，[阿里巴巴](https://campus.alibaba.com/position.htm?refno=11545)
3. 视觉计算研发工程师，[视觉计算研发工程师](http://www.sensetime.com/cn/jobs)
4. 图像搜索高级算法工程师，[360](http://www.lagou.com/jobs/650994.html)
5. 视觉工程师，[格林深瞳](http://www.deepglint.com/assets/vision.html)

