# Markdown
Learn how to use the markdown
# Markdown快速入门（typora）

## 1.代码块：

```c++
//代码块语法：
​```C++
    

    
    
```

**C++代码**

```c++
#include <iostream>
using namespace std;
int main() {
	double e{ 1 };
	int n = 100000;
	double i;
	int j;
	for (i = 1, j = 1; j <= n; j++, i = i / j) {
		e += i;
		if (j % 10000 == 0) {
			cout << e << endl;
		}
	}
	return 0;
}
```

## 2.标题：

```c++
//标题语法
# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题
```

# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题

## 3.字体

```c++
//加粗
**等不到天黑**
//代码高亮显示
==等不到天黑==
//删除线
~~等不到天黑~~
//斜体
*等不到天黑*
```

**等不到天黑**
==等不到天黑==
~~等不到天黑~~
*等不到天黑*

## 4.引用

```c++
//引用语法
>作者：高乐
>>作者：高乐
>>>作者：高乐
```

>作者：高乐
>>作者：高乐
>>
>>>作者：高乐
>>>
>>>

## 5.分割线

```c++
//分割线1
---
//分割线2
***
```


---
***

## 6.图片插入

```c++
//在线图片or本地图片
![我的照片](/image/me.png)--图片路径
```

![markdown的图片](https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1602426001885&di=8dc76d4d0351aaf174c7473678eb90c9&imgtype=0&src=http%3A%2F%2Fjackyshan.github.io%2Fimages%2Fmarkdown-syntax-language.png)

![我的照片](D:\桌面202006\找工作\高乐正装照 .jpg)

## 7.超链接

```c++
//超链接语法
[百度网址]（www.baidu.com）
```

//超链接语法
[百度网址]（www.baidu.com）

## 8.列表

```c++
//无序列表
- 目录1
- 目录2
- 目录3
//有序列表
1 .title
2 .name
```

//无序列表
- 目录1

- 目录2

- 目录3

  //有序列表

  1 .title
  2 .name

## 9.表格

| 成绩 | C++  | 数据结构 |
| ---- | ---- | -------- |
|      | 100  | 100      |

