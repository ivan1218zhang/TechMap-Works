#第二次任务
1.第一题答案
>报错原因：输入的a默认是**字符类型**，故无法和**整形**相加
>如何得到正确结果：
>>
```
>>>a=int(input())
2
>>>b=1
>>>print(a+b)
3
```
2.第二题答案
>abc

3.第三题答案
>在Python3以前的版本中，整数除以整数，结果一定是整数。但是在Python3及以上版本中，软件系统会智能化地将整数转化成为浮点数来进行运算
>7/3结果为浮点数，7//3表示整除，结果是整数2
>7.0//3与7//3结果在大小上相同，但其中一个为浮点数的时候结果为浮点数，即2.0


4.第四题答案
>变量并不直接存储值，而只是引用一个内存地址，故可以a,b=b,a来交换变量的值

5.第五题答案
>a所占用一块内存，del a 之后a的内存被释放，然后这块内存会被用来存储下一个数据，因此具有不确定性。

6.第六题答案
>在python中用+= 、-=来实现自增和自减
例如：a+=1表示变量a自增

7.第七题答案
>is是判断两个变量的内存地址是否相同而==是判断两个变量的值是否相等

8.第八题答案
```
>>>a="Let`s go"
>>>print(a)
Let`s go
```

9.第九题答案
```
a='techf5ve'
print(a[6:8])
print(a[-2: ])
print(a[6: ])
```