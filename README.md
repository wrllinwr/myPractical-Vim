# myPractical-Vim

# myPractical-Vim

* 向下查找光标所在的单词

cw 1.删除光标位置到当前词结尾处的文本。 2.并且还会进入插入模式

dw 删除光标位置到当前词尾

vit v是可是模式，在可是模式下选中标签内的文本

     例如，选中Practical Vim <a href="www.some.com/other/">Practical Vim</a>

$vim -u NONE -N  -u NONE不加载你的vimrc，自己的定制和插件会被禁用。Vim会进入到vi兼容模式； -N (nocompatible)防止进入vi兼容模式。

.（微型宏）  重复上次修改

# 修改：一个命令的执行是一次修改。进入到插入模式（包含何种进入插入模式的操作）一直到到esc，这期间的所有输入操作都被记录下来。算作一次整体的修改。
## 在插入模式移动光标会重置修改状态

>G  增加从当前行到文档末尾的缩进层级
