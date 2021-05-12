# 一级标题

## 二级标题

### 用#来标识标题，最多六级

----



斜体字体 用左右各一个\*包括来写*斜体字*

用\\可以实现转义字符的功能

用左右各两个\* 来写**粗体字**

用左右三个\*来写***粗斜体***



用至少三个连续的\+或\-或\*来标识一个分割线

*****

* * A 
  * * b
    * c  how to end
  * by enter key
* twice to the upper layer

+ 用\+\-\*后跟空格标识一个列表的一行



1. 用数字加 .  后跟空格标识一个有序号的列表
2. 关于嵌套：
       1. 添加四个空格即可
          2. 第二层的第二个嵌套

_____________



左右各两个\-标识~~删除线~~

采用HTML中的标记左边\<u>，和右边\</u> 来写<u>带下划线的文本</u>

脚注这样用，用方括号\[\]加\^来写脚注[^1]

[^1]: 之后用方括号\[\]加^再冒号跟空格注释



----

> \> 加在段落每一句开头，标识对这个段落的区块引用
>
> 就像这样，回车一次自动标识仍在区块中

两次退出引用区块

> 而引用是可以嵌套使用的
>
> > 只要在下一行的开头额外输入一个\>即可
> >
> > * 同样可以和列表项目进行相互嵌套
> > * 就像这样区块中嵌套列表

* 或是像这样

* > 在列表中嵌套区块
  >
  > 很灵活

-----

如果是段落上的一个函数或者片段代码可以用反引号把它包起来，比如此句中的 `printf()`函数

对于代码区块，则可以用头尾三个反引号包裹，并指定一种语言

```javascript
$(document).ready(function(){
    alert('RUNOOB');
});
​```
这是啥，注释吗
​```
```

也可以不指定语言

-----

可以用\[\] 中链接名称后跟\()中地址来标识，比如

[菜鸟教程](https://www.runoob.com)

或者可以直接由\<>中加地址来标识，如

<https://www.runoob.com>

又或者可以用网址变量\[][]的方式给出，,并在文档的结尾给变量赋值，比如

[cainiao][1]

[1]: https://www.runoob.com

-------

图片的格式如下：

* 开头一个感叹号！
* 紧接着方括号，里面放上如片的替代文字
* 最后一个普通括号，里面放上图片的网址，最后可以假设可选的title

![RUNOOB 图标](https://static.runoob.com/images/runoob-logo.png "RUNOOB")



当然也可以使用变量[RUNOOB][a]，然后在结尾赋值

[a]: https://static.runoob.com/images/runoob-logo.png

但无法指定图片的高度和宽度，如若需要可以使用普通的\<img>标签

<img src="https://static.runoob.com/images/runoob-logo.png" width="50%">



------

使用\|来分割不同的列，使用-来分割表头和其他行

比如

| 表头   |  表头  |
| :----- | :----: |
| 单元格 | 单元格 |

| 左对齐  | 右对齐 | 居中对齐 |
| ------- | ------ | -------- |
| :------ | -----: | :-----:  |

----

markdown支持HTML很多元素

如\<kbd> \<b> \<i> \<em> \<sup> \<br>等，如：

使用<kbd>Ctrl</kbd>+<kbd>Alt</kbd>+<kbd>Del</kbd>重启电脑，使用了\<kbd>和\</kbd> 的组合

当需要在编辑器中插入数学公式时可以使用两个美元符号$$包LaTeX的数学公式实现
$$
\mathbf{V}_1 \times \mathbf{V}_2 =  \begin{vmatrix} 
\mathbf{i} & \mathbf{j} & \mathbf{k} \\
\frac{\partial X}{\partial u} &  \frac{\partial Y}{\partial u} & 0 \\
\frac{\partial X}{\partial v} &  \frac{\partial Y}{\partial v} & 0 \\
\end{vmatrix}
${$tep1}{\style{visibility:hidden}{(x+1)(x+1)}}
$$


 

