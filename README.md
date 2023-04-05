# SCUT 实验报告
## 基本功能
+ 更加清晰的logo和首页排版
+ 带有超链接的目录
+ 自动生成的日期，pdf属性，页尾编号
+ 代码高亮
+ 图表的超链接
+ 更多图表支持
+ svg 支持（但仍推荐插入pdf）
+ 优化了其他的排版细节

## 使用注意
由于使用了minted这个代码高亮包，编译前您需要先进行一下两个步骤
1. 在python中安装[Pygments](https://pygments.org/)
2. 为你的编译器加入`-shell-escape`(如果您使用VSCode，这里有一个[教程](https://github.com/James-Yu/LaTeX-Workshop/issues/455))
当然如果你不喜欢这个包，而更熟悉listing。选用它不会存在任何问题。
