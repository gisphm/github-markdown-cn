# Markdown基础
[Markdown][1]允许你用易读、易写的纯文本格式来书写，然后会被转换成可供查看有效的HTML以便在Github上查看。

## 基础写作

### 段落
Markdown里的段落就是一行或者多行的连续文本紧接着一行或多行的空行。

```
在7月2日，一艘外星母舰进入了地球近地轨道并投放了几打的碟形“破坏者”飞船，每一艘都有15英里（24公里）宽。

7月3日，海军陆战队的F/A-18大黄峰“黑骑士”中队在洛杉矶附近参与了对破坏者的袭击行动。
```

### 标题
在标题文本前面，你可以通过添加一个或多个`#`符号来创建标题。
`#`的数量决定标题的大小

```
# 最大的标题（<h1>标签）
## 第二级的标题（<h2>标签）
...
###### 第六级标题（<h6>标签）
```

### 区块引用
你可以用`>`来引用[文字说明][2]。

```
In the words of Abraham Lincoln:

> Pardon my french
```

### 文本样式
你可以让文本变成[**粗体**][3]或者变成[*斜体*][4]。

```
*这个文本将变成斜体*
**这个文本将变成粗体**
```

**粗体**和_斜体_都可以用`*`或者`_`来包围文本以样式化。
如果需要，你可以把粗体和斜体结合起来用。

```
**Everyone _must_ attend the meeting at 5 o'clock today.**
```


## 列表
### 无序列表
你可以在列表项前面加上`*`或者`-`来创建一个[无序列表][5]。

```
* Item
* Item
* Item

- Item
- Item
- Item
```

### 有序列表
你可以在列表项前面加上一个数字来创建[有序列表][6]

```
1. Item 1
2. Item 2
3. Item 3
```

### 嵌套列表
你可以通过缩进两个空格来创建嵌套列表

```
1. 项目 1
  1. 上述项目的一个推论
  2. 另一个需要考虑的点
2. 项目 2
  * 不需要序号的推论
    * 这个缩进了四个空格，因为它比上面的项多了两个空格
    * 你可能考虑创建一个列表
3. 项目 3
```

## 代码格式化
### 内联格式
使用单个反引号（`` ` ``）来把文本格式化成特殊的等宽文本格式。
在反引号里的一切都会显示成原样，而没有其他特殊的格式化。

```
Here's an idea: why don't we take `SuperiorProject` and turn it into `**Reasonable**Project`.
```

### 多行
你可以用三个反引号（```` ``` ````）来格式化文本，以作为一个独特的区块。

```
Check out this neat program I wrote:

    ```
    x = 0
    x = 2 + 2
    what is x
    ```
```

## 链接
你可以用中括号（`[ ]`）来包含链接文字和用小括号（`( )`）来包含链接地址以创建链接。

比如，为创建到 [www.github.com][7] 的链接，并加上一个链接文本 Visit Github!，
你就这么在Markdown里写：`[Visit Github!](www.github.com)`。


[1]: http://daringfireball.net/projects/markdown/
[2]: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/blockquote
[3]: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/strong
[4]: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/em
[5]: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ul
[6]: https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ol
[7]: https://www.github.com
