## Use Chinese in Latax, There has two ways.
#### First:
tex文档设为utf-8编码，然后文档类型为ctexart， 比如文件的前两行为如下即可：

%-- coding: UTF-8 --

\documentclass[UTF8]{ctexart}

#### Second:
tex文档设为utf-8编码，加载ctex包， 比如源文件要包含如下两行：

%-- coding: UTF-8 --

\usepackage[UTF8]{ctex}
