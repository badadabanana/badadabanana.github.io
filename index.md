layout: default
title: badada's Blog Title
---

# Blog Blog Blog!

Welcome to my little corner of the internet!

## Header 2

> The first one blog!
>
> LET'S DO IT.
> 
建设ing......

## 二级


### 三级标题  
#### 文本格式  

- ​**加粗试试看**​：`**加粗方法一**` 或 `__加粗方法二__`  
- *斜体试试看*：`*斜体方法一*` 或 `_斜体方法二_`  
- ~~删除线看效果~~：`~~删除线方法~~`  
- `行内代码是啥`：`` `代码嵌在语句中吗` ``  
- ==高亮试试看==（部分支持）：`==字体颜色怎么设置？==`
- 
#### 一些idea儿，哈哈哈  
[//]: # "这是注释：###与标题之间需要空格"

- 想要赛博朋克像素风类的，可以用Excel自制像素风图画
- 想要创建目录超链接，最好是冻结在左侧或最上方
- 想要评论留言功能
- 想要做笔记功能，不需要打开代码编写的内容
- 需要学习html+css+JS
  - 子项目（缩进2空格）

<!-- 向b站up：Box_盒马，学习，网站链接：https://async-area.com -->

#### 有序列表 

标准 Markdown 本身并不直接支持分栏

1. 第一种方法
 <div style="display: flex; justify-content: space-between; gap: 20px;">
  <div style="flex: 1; background-color: #f0f0f0; padding: 15px;">
    **左侧栏目**
    - 支持完整的 Markdown 语法
    - 这里是左侧的内容
  </div>
  <div style="flex: 1; background-color: #e0e0e0; padding: 15px;">
    **右侧栏目**
    - 右侧的内容区域
    - 同样可以自由编辑
  </div>
</div>

2. 第二种方法
<div style="width: 48%; float: left; background-color: #f0f0f0; padding: 10px;">
    **左侧浮动栏目**
    - 左侧内容
</div>
<div style="width: 48%; float: right; background-color: #e0e0e0; padding: 10px;">
    **右侧浮动栏目**
    - 右侧内容
</div>
<div style="clear: both;"></div> <!-- 清除浮动，重要！ -->

3. 第三种方法
<div style="display: grid; grid-template-columns: 1fr 1fr; gap: 20px;">
  <div style="padding: 15px;">
    **Grid 左栏**
    - 网格布局中的第一列
  </div>
  <div style="padding: 15px;">
    **Grid 右栏**
    - 网格布局中的第二列
  </div>
</div>


#### 链接与图片

[Blog](https://badadabanana.github.io)  
![来个表情包看看效果](https://wx3.sinaimg.cn/mw690/00822bhDly1htmy4iw7tmj30u00s1786.jpg)  
![Octocat](https://github.githubassets.com/images/icons/emoji/octocat.png)
#### 表格

| 左对齐 | 居中对齐 | 右对齐 |
|:-------|:-------:|-------:|
| 单元格 | 单元格  | 100    |


#### 多行引用  

> 引用内容  
> 多行引用  
多行？
---
或 ​**​*（分割线）

#### 任务列表 

- [x] 完成   <!-- 为什么×和√不能单击切换 -->
- [ ] 待办  


#### 多行代码

```python
def hello():
    print("Hello, Markdown!")
```
```python
  <!DOCTYPE html>
    <html>
    <head>
        <title>badada的网页Title</title>
          <!-- 
            这里是 head 部分，用于定义元数据和引入 CSS/JS这是一个段落。
            在 HTML 中，<title> 标签的内容 ​不会直接显示在网页的可见内容区域，而是有特定的显示位置和作用。
          -->
    </head>
    <body>
        <!-- 这里是 body 部分，所有可见内容都写在这里 -->
        <h1>欢迎访问我的网站</h1>
        <!-- 这个 h1 标签是页面的主标题 -->
        <p>hihi,badada.</p>
        <!-- 
        这是一个段落。
        这里是多行注释，
        可以写更详细的说明。
        /* 基础样式重置 */

        -->
    </body>
    </html>
```

* * *
<!-- 这是一个注释，不会在渲染后的内容中显示 -->
[//]: # "这是注释"
[^_^]: # "这也是注释"

不会搞侧边栏













