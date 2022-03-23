# 动手学差分隐私（Programming Differential Privacy）

This is the source repository for the book "Programming Differential Privacy." You can find the book online [here](https://uvm-plaid.github.io/programming-dp).

这是教材《动手学深度学习（Programming Differential Privacy）》的源代码仓库。你可以[在此](https://uvm-plaid.github.io/programming-dp/zh_cn)在线阅读本教材。

## 声明（Declaration）

The translation work is authorized by original authors Joseph P. Near and Chiké Abuah, and is supported by the editor Lei Yao from China Machine Press. The Chinese version of the book will be freely available online, and there will be a printed version edited by China Machine Press.

本教材的翻译工作得到了原作者Joseph P. Near和Chiké Abuah的授权，并得到了机械工业出版社（China Machine Press）编辑姚蕾老师的支持。本教材的中文版本将免费在线发布，并推出机械工业出版社编辑的纸质版本。

## 中文版本配置（Configuration for Chinese version）

为使编译得到的PDF版本正确显示中文，需在`_config.yml`下增加下述配置：

```text
sphinx:
    config:
        language: zh_CN
```

如果使用新版本的`jupyter-book`完成编译，需先在源代码目录下执行：

```text
jupyter-book toc migrate /Users/liuweiran/DsProjects/programming-dp/zh_cn/_toc.yml -o /Users/liuweiran/DsProjects/programming-dp/zh_cn/_toc.yml
```