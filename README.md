# HNUSTGraduationDesignTemplate
湖南科技大学毕业设计模板及相关文件，欢迎指正！

## latex模板
[很久没维护了](https://github.com/Anudorannador/LaTex-Template-of-HNUST-Thesis)

## word模板

自己根据要求制作的模板，工作如下：

1. 把多级列表、文字、题注和三线表等样式设定了一下（大部分都有样式，直接套用就行），一级标题对标`标题 1`，二级标题对标`标题 2`。
2. 对一级标题设置了孤行控制、与下段同页、段前分页，其中段前分页优雅地替代了大部分分页符的工作；其它级别的标题设置了孤行控制、与下段同页。
   > [“孤行控制”“与下段同页”“段中不分页”“段前分页”是什么意思？ - 知乎 (zhihu.com)](https://zhuanlan.zhihu.com/p/613209475)
5. 表格设置了三线表格式，直接套用就行。
   ![image](https://github.com/3210448723/HNUSTGraduationDesignTemplate/assets/61307277/2b5a07a1-ac1d-47bd-b278-ab640a7b1ff9)
7. 如果要使用公式建议结合`MathType`使用（实现了自动编号和公式居中[1](https://zhuanlan.zhihu.com/p/421681741)、[2](https://zhuanlan.zhihu.com/p/473078485)），在确定好章节后将`MTEquationSection`格式设置为隐藏（[2](https://zhuanlan.zhihu.com/p/473078485)），注意设置隐藏后按退格也会删除隐藏的文字；
8. 如果不用`MathType`的话，需要删除每个章节后的用于公式自动编号的`公式章 (下一章) 节 1`隐藏字符![image](https://github.com/3210448723/HNUSTGraduationDesignTemplate/assets/61307277/14a503af-d1f7-49c3-8d25-7b42486efabc)
9. 关于`含章节号的题注编号以阿拉伯数字显示`的问题，看来看去还是觉得[该方法](https://gitcode.csdn.net/65e7d4151a836825ed789985.html)比较简单。注意这一步要**最后**执行，如果更新了域代码或者新插入了题注，会导致如`一.1`的格式问题。同时如果要**导出PDF**的话也会导致更新域代码，此时可以用'ctrl+a'选择所有内容，再按`ctrl+F11`来锁定域，避免更新；按`ctrl+shift+F11`来取消锁定域。
10. [Word中中英文目录对齐设置问题_目录中中文和英文没对齐-CSDN博客](https://blog.csdn.net/perfect12345/article/details/8658174)，但不算特别好的解决方案

## 建议
1. 使用zotero管理参考文献
2. 在word选项->显示->勾选`显示所有格式标记`，这样可以看到许多隐藏符号
3. 在表格中选择`查看网格线`![](https://github.com/3210448723/HNUSTGraduationDesignTemplate/assets/61307277/e02d5117-7e86-4fa5-a542-85bdd982d69c)
4. 多用格式刷
5. 打印使用导出的PDF版本，避免格式错乱
6. 多用![image](https://github.com/3210448723/HNUSTGraduationDesignTemplate/assets/61307277/06ea018f-e635-4628-8f8b-3dcce7b223a9)改错
7. 如果目录中条目首字符出现中英文没有对其的情况的话，![image](https://github.com/user-attachments/assets/7ec8f5d6-bbdc-4bbd-ac32-b744c2900c69)需要选中目录并勾选`允许西文字符换行`，不过这样会导致样式略微变化，暂时没发现更高的办法。


## 未实现
1. 目录格式设置与样式的绑定 
