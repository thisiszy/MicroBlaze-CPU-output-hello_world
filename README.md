# MicroBlaze-CPU-output-hello_world
## 实验环境

`vivado 2019.1`

`xshell 6`

## 简介

其实这个实验网上资料已经很多了，不过由于大多数已有的资料使用的是较早版本的`vivado`所以有一些选项在2019.1版本中已经被移除，而2019.2以后的版本中将目前的SDK替换成了`Vitis`平台，所以资料相对较少。

本文档是关于`vivado 2019.1`版本中，使用SDK让MicroBlaze CPU从JTAG中输出文字的介绍。（基本都是IP核的设置）