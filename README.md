so中执行js, 可以参考此仓库
[autojsNativeJs](https://github.com/snailuncle/autojsNativeJs)

webpack打包多个autojs的js文件为一个js文件, 可以参考此仓库
[webpack-autojs](https://github.com/snailuncle/webpack-autojs)


# 该仓库目的是将autojs编写的js文件转为dex文件


## 环境要求
1. java  要用java
2. android studio  要用dx

## 步骤
1. 当前仓库根目录执行  node index.js

## 备注
1. 步骤:js -> Class -> Dex
2. config.js中配置dx的绝对路径
3. jsList文件夹放js文件
4. 生成的class以及dex就在jsList文件夹里

## 备注2
如果没有安装as, 可以使用dx文件夹中的bat命令, 将class转为dex

## 注意
如果js中有let, 请使用var代替, 否则报错.
