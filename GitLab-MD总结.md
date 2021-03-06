# 目录

- [符号语法整理](#符号语法整理)
- [文本格式整理](#文本格式整理)
- [缩进换行整理](#缩进换行整理)
- [参考链接整理](#参考链接整理)

# 符号语法整理

# 等于号(\=)

1. 设置一级标题

    > 一级标题
    > =

# 减号(\-)

1. 设置二级标题

    > 二级标题
    > --

2. 设置表格对齐方式
    > |左对齐|右对齐|居中对齐|
    > |:-----|-----:|:------:|
    > |    左|右    |居    中|

3. 设置无序列表、任务列表

    > - 无序列表
    > - [x] 任务列表

4. 设置分割线

    > ---

# 星号(\*)

1. 设置无序列表、任务列表

    > * 无序列表
    > * [x] 任务列表

2. 设置分割线

    > ***

3. 设置文本格式

    > *斜体* ， **粗体** ， ***斜粗体***

# 加号(\+)

1. 无序列表、任务列表

    > + 无序列表
    > + [x] 任务列表

# 下划线(\_)

1. 设置分割线

    > ___

2. 设置文本格式

    > _斜体_ ， __粗体__ ， ___斜粗体___

# 井号(\#)

1. 设置标题

    > ###### 六级标题

# 反引号(\`)

1. 设置行内代码高亮，一对「 ` 」

    > `行内代码` `高亮`

2. 设置文本块，一对「 ``` 」

    > ```
    > echo "Hello"
    > ```

3. 设置代码块，一对「 ``` 」+语言

    > ```sh
    > echo "Hello"
    > ```

# 大于号(\>)

1. 设置引用

    > 引用

# 竖线(\|)

1. 表格

    > |表格|
    > |----|

# 波浪号(\~)

1. 设置文本格式

    > ~~删除线~~

# 尖括号(\<\>)

1. 自动链接

    > <https://www.baidu.com>

# 中括号(\[\])

1. \[\]\(\)

    > [有道云笔记官网](http://note.youdao.com/ "http://note.youdao.com/")

2. \!\[\]\(\)

    > ![图片无法显示](http://note.youdao.com/favicon.ico "有道云笔记Logo")

3. \[\]\(\#\)

    > [前往目录](#目录 "目录")


# 文本格式整理

| # | 用法 | 效果 |
| - | ---- | ---- |
| 1 | `*这是斜体*` `_这是斜体_` | *这是斜体* _这是斜体_ |
| 2 | `**这是粗体**` `__这是粗体__` | **这是粗体** __这是粗体__ |
| 3 | `~~这是删除线~~` | ~~这是删除线~~ |

> 注意：符号和文本之间没有空格


# 缩进换行整理

1. 缩进

    > 缩进参考文本  
　　行首2个全角空格(输入法 `shift + space` 切换半角/全角)  
&emsp;&emsp;行首2个 `&emsp;`  

2. 换行

    > 只需在行末加两个空格


# 参考链接整理

```
[![图片标记]][链接标记]
[图片标记]:图片地址 "鼠标悬停显示的内容"
[链接标记]:链接地址 "鼠标悬停显示的内容"
```

**示例**

| # | 用法 | 效果 |
| - | ---- | ---- |
| 1 | `[YDNote][]` | [YDNote][] |
| 2 | `[有道云笔记][YDNote]` | [有道云笔记][YDNote] |
| 3 | `![][YDNote-Logo]` | ![][YDNote-Logo] |
| 4 | `[![YDNote-Logo]](http://note.youdao.com/ "YDNote官网")` | [![YDNote-Logo]](http://note.youdao.com/ "YDNote官网") |
| 5 |`[![](http://note.youdao.com/favicon.ico "有道云笔记官网 http://note.youdao.com/")][YDNote]` | [![](http://note.youdao.com/favicon.ico "有道云笔记官网 http://note.youdao.com/")][YDNote] |
| 6 | `[![YDNote-Logo]] [YDNote]` | [![YDNote-Logo]][YDNote] |

[YDNote]:http://note.youdao.com/ "有道云笔记官网"
[YDNote-Logo]:http://note.youdao.com/favicon.ico "有道云笔记LOGO"

> 参考式链接的URL标识符
> 1. `[YDNote]:http://note.youdao.com/ "有道云笔记官网"`
> 2. `[YDNote-Logo]:http://note.youdao.com/favicon.ico "有道云笔记LOGO"`


|***[返回目录](#目录)***|
|-|

