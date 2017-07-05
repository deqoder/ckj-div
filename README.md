# ckj-div

## 总体目标

可方便地编辑汉字的拆分，只对不可拆字进行人工编码，自动递归生成所有汉字的码表

## [预览](https://deqoder.github.io/ckj-div/main.html)

## 已实现的功能
### 2017-07-05
* 读入json数据生成表格，表格两列，一列汉字，一列是拆分
* 双击表格第二列任意一格，可对其编辑
* 再次双击则保存，在其他行双击则之前的自动保存
* 保存在json变量中，并dump出来，未实现保存回文件
* 支持超过65536的unicode字符
