# 一及标题
## 二及标题
### 三及标题
\#为标题修饰符

## 正文内容

直接编辑正文内容即可，但是如果需要换行使用\<br\>,为换行符<br><br>
第一行数据
第二行数据<br>
第三行数据<br>

## 字体修饰符

**粗体** ，两队\*包含为粗体

*斜体* ， 一对\*包含为斜体

***粗斜体*** ， 三对\*包含为粗斜体

一段文本，其中`关键字`要凸显

~删除线效果~ ，一对\~展现删除线效果

##引用

需要引用可以使用\>,多级引用可以相互包含

>一及引用
>>二及引用
>>>三级引用
>>>>四级引用

###分割线

使用五个\*即可实现分割线特效

第一段数据

*****

第二段数据

##列表

如果使用\*表示无序列表，如果是1.2.3.4 均为有序列表

* 物理学
   * 粒子物理
   * 原子核物理
   * 凝聚态物理

* 计算机科学
   * 套接字
   * DNS
   * 内网搭建
      * 网络通信

1. 物理学
   1. 粒子物理
   2. 流体物理

* FPS第一人称
   1. pubg
   2. apex

##代码插入
插入不同的代码 要声明代码块
```c
	#include<stdio.h>
	int main()
	{
		printf("hello c"\n");
		return 0;
	}

```

```cpp
	#include<iostream>
	using namespace std;

        int main()
        {
                cout<<hello<<endl;
                return 0;
        }

```

```python

```

```bash
	git add files.c
	git rm files.c

```
## 超链接

[BiliBili弹幕网](https://www.bilibili.com "点击进入Bzhan")

## 插入图片
如果需要在github上显示图片数据，需要网络图片地址，将图片上传到某个网站生成图片的URL，而后github才可以访问加载这张图片

![截屏](C://Users//小赵的戴尔//Desktop//wonwoo.jpg "悬停标题")

## 表格数据

姓名|排行|技能
--|:--|:--|
wonwoo|6|rap
dk|10|vocal
hoshi|5|dance
