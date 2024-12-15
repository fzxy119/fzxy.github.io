---
title: Markdown基本语法
date: 2021-11-09 14:13:31
tags:
- Markdown
categories:
- 工具
---

# 一、标题

一个#是一级标题，二个#是二级标题，以此类推。支持六级标题。

```markdown
# 这是一级标题
## 这是二级标题
### 这是三级标题
#### 这是四级标题
##### 这是五级标题
###### 这是六级标题
```

# 二、字体

- ##### 加粗

要加粗的文字左右分别用两个*号包起来

- ##### 斜体

要倾斜的文字左右分别用一个*号包起来

- ##### 斜体加粗

要倾斜和加粗的文字左右分别用三个*号包起来

- ##### 删除线

要加删除线的文字左右分别用两个~~号包起来

```markdown
**这是加粗的文字**
*这是倾斜的文字*`
***这是斜体加粗的文字***
~~这是加删除线的文字~~
```

# 三、引用

在引用的文字前加>即可。引用也可以嵌套，如加两个>>三个>>>

```markdown
> 这是引用的内容
>> 这是引用的内容
>>>>>>>>>> 这是引用的内容
```

# 四、分割线

三个或者三个以上的 - 或者 * 都可以。

```markdown
---
----
***
*****
```

# 五、图片

```markdown
![图片alt](图片地址 ''图片title'')
```

# 六、超链接

```markdown
[超链接名](超链接地址 "超链接title")

[简书](http://jianshu.com)
[百度](http://baidu.com)
```

# 七、列表

##### 无序列表

无序列表用 - + * 任何一种都可以

```markdown
- 列表内容
+ 列表内容
* 列表内容

注意：- + * 跟内容之间都要有一个空格
```

##### 有序列表

```markdown
1. 列表内容
2. 列表内容
3. 列表内容

注意：序号跟内容之间要有空格
```

##### 列表嵌套

**上一级和下一级之间敲三个空格即可**


