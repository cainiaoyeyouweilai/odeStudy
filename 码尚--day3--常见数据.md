- [ ] 码尚--day3--常见数据类型详解：


- 一、Python基本语法

  - ```
    print(keyword.kwlist)   #	查看Python中的关键字  
    输出：['False', 'None', 'True', 'and', 'as', 'assert', 'async', 'await', 'break', 'class', 'continue', 'def', 'del', 'elif', 'else', 'except', 'finally', 'for', 'from', 'global', 'if', 'import', 'in', 'is', 'lambda', 'nonlocal', 'not', 'or', 'pass', 'raise', 'return', 'try', 'while', 'with', 'yield']
    ```

- 二、Python常见六种数据类型

​                Number（数字）---不可变

​		String（字符串）---不可变

​		List（列表）---可变

​		Tuple（元祖）---不可变

​		Set（集合）---可变

​      	  Dictionary（字典）---可变

- 三、Number数据类型---数值类型

  ​	1、Python3支持四种不同的数值类型int、float、bool、complex		（复数）。

  ​		bool类型：0==False    1==True

  ​	2、常用的数值函数

  ​            abs(x)取得数字的绝对值

  ​	    ceil(x)返回数字的上入整数

  ​            floor(x)返回数字的下舍整数

  ​            random.random()返回随机生成的一个实数，它在[0,1)范围内。

  ​	    random.randint(a,b)返回随机生成一个整数，在a~b之间的整数  	    	


```Python
import math
# 随机生成数值类型
import random
# 定义number类型
num1=1
num2=2.1
num3=False
print(num1)
# 打印数据类型
print(type(num1),type(num2),type(num3))
print(num1**2)
print(9/2)
# //获取得到与除数类型是一致，不会进行四舍五入，/返回值类型为float
print(9//2.0)
print(abs(num1))
print(" floor(x)返回数字的下舍整数:",math.floor(4.0))
print(" ceil(x)返回数字的上入整数",math.ceil(5.1))
print(" random.random()返回随机生成的一个实数，它在[0,1)范围内:", random.random())
# random.randint(a,b)返回随机生成一个整数，在a~b之间的整数")
print("random.randint(a,b)返回随机生成一个整数，在a~b之间的整数:", random.randint(100, 200))
# 进行四舍五入
print(round(4.7),round(4.78,1))
# 去掉整数部分 math.trunc
print(math.trunc(4.7))
```

​	四、运算符

​		\+  -  *  /  或者 //  ** a**b=  a的b次幂    %  取余四、String数据类型

 	      注意：//获取得到与除数类型是一致，不会进行四舍五入/返回值类型为float

- 五、Tuple数据类型

