### 链接标签

```css
target 打开窗口的方式  

默认值是_self 当前窗口打开，**___**blank新窗口打开 

下载链接：如果href里面地址是一个文件或者压缩包，会下载这个文件
锚点链接：在链接文本的href属性中，设置属性值为#名字的形式，如<a href="#two">第二集</a>
		找到目标位置标签，里面添加一个id属性=刚才的名字，如<h3 id="two">第二集</h3>
```

### label标签

```shell
绑定表单元素，点击label标签内的文本，自动选择对应的表单元素上
for 和 id 对应
<label for="sex">男</label>
<input type="radio" name="sex" id="sex"/>
```

### text-align

```shell
 #只能设置水平对齐
 text-align:
 	center  left  right
```

### text-decoration

```shell
# 装饰文本
text-decoration
a {
	text-decoration: none
}
underline  下划线
overline   上划线
```

### text-indent

```shell
# 缩进
text-indent: 2em
```

### line-height

```shell
# 行间距
line-height:26px
文字高度 + 上间距 + 下边距
```

### 复合选择器

```shell
# 后代选择器
ol li
# 子元素选择器
ol>li
```

### 并集选择器

```shell
div,
p,
ul
并集选择器竖着写，最后一个不加逗号
```

### 伪类选择器

```shell
最大的特点就是用冒号表示
a:link      没有访问过的连接
a:visited   访问过的连接
a:hover     鼠标经过的时候
a:active    正在按下没有谈起的时候
注意事项：
顺序 l v  h a

:focus 把获得光标的表单元素选取出来
例 input:focus
```

```shell
#块元素
<h1>-<h6> div p ul ol li
```

###　显示模式的转换

```shell
# 转换为块元素
display：block
# 转换为行内元素
display:inline
```

### 单行文字垂直居中

```shell
height = line-height
```

### 背景图片

```shell
background-image:url()  # 绝对或相对位置

background-repeat: no-repeat/repeat-x
```

### 背景位置

```shell
# 后面可以跟方位名词和精确单位
background-position: x , y
background-position: center , right
# 省略一个参数，省略的位置为居中
background-position: right
# 如果是精确单位，第一个必须是x,第二个是y
```

### 背景固定

```shell
background-attachment: scroll | fixed
scroll  随对象内容滚动
fixed  背景图像固定
```

### 背景复合写法

```shell
background: 背景颜色 背景图片地址 背景平铺 背景图像滚动 背景图片位置
```

###　css三大特性

```shell
# 层叠性
样式冲突，就近原则
# 继承性
孩子继承父亲的样式
# 优先级
继承或者*  0，0，0，0
元素选择器 0，0，0，1
类，伪类   0，0，1，0
id选择器   0，1，0，0
行内样式   1，0，0，0
！import   无穷大
```

### 盒子模型

```shell
# 合并相邻的边框
border-collapse:collapse
# 如果没有指定宽度和宽度  padding撑不开盒子大小
# 快级盒子水平居中
	前提条件：盒子设置了宽度，左右外边距都设置auto
	margin: 0 auto
# 行内元素或者行内块元素水平居中
	给父元素添加 text-align:center
# 盒子阴影 
	box-shadow
```

### 浮动

**特性**

```shell
1.浮动元素会脱离标准流

2.浮动的元素会一行显示并且元素顶部对齐

3.浮动的元素会具有行内块元素的特性
```

**注意点**

```shell
1.浮动和标准流的父盒子搭配
2.一个元素浮动，其余兄弟元素都要浮动
	浮动的盒子只会影响后面的标准流，不会影响前面的标准流
```

**清除浮动**

```shell
1-额外标签法
2-父级添加overflow
	缺点：无法显示溢出的部分
3-父级添加after伪元素
4-父级添加双伪元素
```

### ps切图

**合并图层**

```shell
shift 选择两个图层
图层菜单->合并图层（ctrl+e） 然后导出+
```







