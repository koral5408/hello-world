# 一个#是一级标题
## 两个#是二级标题
### 三个#是三级标题
#### 四个#是四级标题
##### 五个#是五级标题
###### 六个#是六级标题

或者是用==和--做标题，本行是用====的效果
===================
这是使用----的效果
----------------

@1 第一次修改


# 1、关于添加引用
引用其他文件的或者名言之类的，应该是吧？语法为在行（或者段）前面加一个 > 符号即可，大于号

> 真理惟一可靠的标准就是永远自相符合。 —— 欧文（一行的开始加一个>）

> 土地是以它的肥沃和收获而被估价的；才能也是土地，不过它生产的不是粮食，而是真理。如果只能滋生瞑想和幻想的话，即使再大的才能也只是砂地或盐池，那上面连小草也长不出来的。 —— 别林斯基 （在一段的开始加一个>）

> 父亲子女兄弟姊妹等称谓，并不是简单的荣誉称号，而是一种负有完全确定的异常郑重的相互义务的称呼，这些义务的总和便构成这些民族的社会制度的实质部分。 —— 恩> 格斯（统一段落的多行，每一行加一个>）

>一个人最怕不老实，青年人最可贵的是老实作风。"老实"就是不自欺欺人，做到不欺骗人家容易，不欺骗自己最难。"老实作风"就是脚踏实地，不占便宜。
>
>>诚才是人生最高的美德。 —— 乔叟（尝试二级引用，就是用两个>>）
>
>世界上没有便宜的事，谁想占便宜水就会吃亏。 —— 徐特立

# 2、关于列表
## 无序列表，使用星号、加号和减号作为列表标记（加减乘）

### 星号*
* 红
* 绿
* 蓝

### 加号+
+ 红
+ 绿
+ 蓝

### 减号-
- 红
- 绿
- 蓝

## 有序列表，使用数字和一个英文句点来表示 （1.  2.  ）
### 数字可以随意
1.  鸟
2.  兽
4.  虫
3.  <。)#)))≦

# 3、代码插入时使用制表符或者四个空格
### 使用代码行的时候首先在代码首尾各空一行，行首添加 ```
```
void main(){
  int i; //一个制表符
  int j; //一回车自动添加制表符
  
  if (flag == true){
    i++ //尝试两个制表符
```

# 4、分隔符
### 在一个空行中使用三个以上的 星号 减号 底线 来建立一个分隔符，行内不能有其他东西，星号或者减号中间可以插入空格
下面是三个星号 ***
***
下面是三个减号 ---
---
下面是三个底线 ___
___

# 5、连接 分两种，行内连接和参考连接
### 行内连接， 即使用在一行内直接使用，格式为 \[百度\]\(http://www.baidu.com "百度连接"\)
例如，[百度](http://www.baidu.com "百度连接")

### 参考连接就是使用标签的形式格式为 \[百度\]\[baidu\] ，其中\[baidu\] 在文件任意位置定义 \[baidu\]: http://www.baidu.com "百度连接"
[baidu]: http://www.baidu.com "百度连接"
参考连接 [百度][baidu]

# 6、图片
### markdown 中使用的图片使用和超链接类似的方式来插入，在前面家一个!(感叹号 “标题”)，即\!\[闯荡世界\]\(http://c1.mifile.cn/f/i/17/mi6/index/photos-group03_1.jpg\)
![闯荡世界](http://c1.mifile.cn/f/i/17/mi6/index/photos-group03_1.jpg "开始闯荡世界")

### 图片也可以使用参考索引

### 设置图片大小 \!\[名称\]\(链接地址 =宽x高\)  【没找到markdown的语法，可能不支持？】
![闯荡世界](http://c1.mifile.cn/f/i/17/mi6/index/photos-group03_1.jpg = 400*300 "开始闯荡世界")

# 7、强调，包括粗体和斜体，使用星号* 和 底线 _
### 
 *\*前后各有一个星号\**    
 **\*\*前后各有两个星号**\*\*    
 _\_前后各有一个底划线\__    
 __\_\_前后各有两个底划线\_\___    
 *__\*\_\_前后各有一个星号，两个底划线\_\_\*__*   
 _**\_\*\*前后各有一个底划线，两星号\*\*\_**_   
 
# 8、使用反斜杠 \\ 来注释
```
\   反斜线
`   反引号
*   星号
_   底线
{}  花括号
[]  方括号
()  括弧
#   井字号
+   加号
-   减号
.   英文句点
!   惊叹号
```

# 9、从ubuntu中进行修改
测试本地进行修改，然后上传到github上去
