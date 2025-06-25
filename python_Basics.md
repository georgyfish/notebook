# Basics
types - 类型 types and casting  转换
control flow -  if else , loop , logical operators 控制流 
exception  异常处理
fn 1  - function , lambda
fn 2  - map , filter
class & naming
inheritance 继承


## logical operators
and / or / not 

## lambda function 
简单说，就是把函数写成一行

## mapping function
```
def square(x):
    return x**2 
numbers = [1, 2, 3]
result = map(square, numbers)
result_list = list(result) # convert to a list - [1, 4, 9]
```

## filter function 
# 筛选
def myFn(x) -> bool:
    return x > 2

numbers = [1, 2, 3, 4, 5]
result = filter(myFn, numbers)
result_list = list(filter)  # [3, 4, 5]

## Naming
命名格式要求：
文件名： 下划线、字符串；
类名： 单词的首字母大写，单词连写；
public static  : static_filed
protected static :  _static_filed
private static : __static_filed

public_method 
_protected_method
__private_method

@staticmethod



