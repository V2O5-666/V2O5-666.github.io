# My first Markdown

## text

纯文本测试123123。后面接两个空格表示换行  
*斜体* _斜体_  
**加粗** __加粗__  
~~删除线~~  
转义字符：\* \_  
用一个空行表示段落的结束

## 块引用

> dasdas  
> dasdsa
>> 12341234

## 链接

### 带标题的链接

这是一个[惊喜](https://www.baidu.com "快点开看看")  
惊喜[2](https://www.bilibili.com/video/BV1GJ411x7h7?from=search&seid=16871294989244760006 "谨防上当")
html_test[Click here](test.html "我的html测试")

### 其他链接格式

<http://www.douyu.com/>  
这是一个带有参考的[链接][1]  
注：参考ID可以是数字，也可以是字母、空格、标点符号  
ID区分大小写  
带有参考ID的链接或图片的定义可以出现在任何位置

## 图片

![picture](img/校训.jpg)  
![picture2][2]  

## 代码

### 代码块

可以使用4个空格或一个tab，之后写入代码  
或是使用前后各3个反引号包裹的形式  
但是在一个md文件中只能出现一种格式，不能混用

```R
a <- c(1,2,3)
sum(a)
```

### 代码片段

直接两个反引号包裹起来即可 `mean(a)`

## 列表

### 无序列表

在每一行前面加上+*-即可，如：

+ 123
+ 456
+ 789

### 有序列表

直接使用"数字."的格式，如：

1. aaa
2. bbb
3. ccc

注意，列表标识符与每行列表内容之间有空格

### 任务列表

+ [x] 已完成
+ [ ] 待办

与代码块的标识格式一样，一个md文件只能出现一种列表标识符，如：在该文件中前面的无序列表使用的是"+"，因此在任务列表中要使用"+ [ ]"的格式，使用"- [ ]"会报错

## 其他

### 表格

| Name   | Age    | No.    |
| :---   | :---:  | :---   |
| Adam   | 20     | 123456 |
| Bill   | 22     | 666666 |
| ...    | ...    | ...    |

### 带ID的标题

#### <a id="3">Title</a>

### 定义

DNA
: 脱氧核糖核酸

### Emoji

🐂🍺

[1]: https://www.zhihu.com/
[2]: img/屋檐一角.jpg
[点此回到Title](#3)