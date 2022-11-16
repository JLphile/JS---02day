

# js基础第二天测试题

## 1. if...else语句的if和else两个句子里的代码能同时被执行吗?

A： 不可以，因为两个条件不同
B： 有时候可以，有时候不可以
C： 2个都不能执行
D： 可以，因为条件是并列的

## 2. 仔细阅读代码，请问下面的输出结果是？

```html
<script>
    switch (2) {
    case 1:
    console.log(1)
    break
    case 2:
    console.log(2)
    default:
    console.log(3)
    break
    }
</script>

```

A： 3
B： 2 3
C： 1 2 3
D： 2

## 3. 结束当前循环,继续进行下一次循环的关键词是()

A： break
B： continue
C： end
D： return

## 4. 以下哪些情况可能会出现死循环() 【多选题】

A： while(1){}
B： while(true){}
C： while(0){}
D： while("itcast"){}

## 5. 以下while循环的次数是()

```html
<script>     
  console.log(11 && 22)
  console.log(false && 'hello')
  console.log(33 || 44)
  console.log(0 || 55)
</script>
```

A:    22 hello 33 55
B： 11 hello 33 55
C： 22 false 33 0
D： 22 false 33 55

## 8. 请根据运算符的优先级给下面的运算符做个排序？

a逻辑运算符 ||
b比较运算符 >
c一元运算符 ++
d算数运算符 +
A： abcd
B： dcab
C： cdba
D： cbda

## 9. 运算结果正确的是？

- ```html
  <script>      
    console.log(1 > 2)
    console.log(2 >= 2)
    console.log(2 <= 2)
    console.log(2 == '2')
    console.log(2 !== '2')
  </script>
  ```

A： false true true true false
B： false true true false false
C： false true true true true
D： false false false true false

## 10. 用break语句可以使流程跳出switch语句体，也可以用break语句在循环结构终止本层循环体，从而提前结束本层循环

- 对
- 错

  

## 11. continue 不会打断当次循环执行。

- 对
- 错

  

# 作业

## 1.switch-case 语句练习

请用户输入1个星期数，就将对应的英文的星期打印出来

- 比如用户输入‘星期一’，则页面可以打印Monday

## 2. if-else  else-if 多分支语句练习

接收用户输入的分数，根据分数输出对应的等级字母 A B C D E ,其中：

- 90分以上 ，输出A
- 80-90 输出 B
- 70-80 输出C
- 60-70 输出 D
- 60以下 E

## 3. 循环大练习

1. 打印0-20 之间的整数，将每个数输出到控制台
2. 计算1-1000之间的和
3. 打印100-200之间，可以被6整除的数字
4. 用户输入一个数，计算1到这个数的和
   - 比如用户输入的是5，则计算1~5之间的累加和
   - 比如用户输入的是10，则计算1~10之间的累加和

## 4. 用户登录验证

题目描述：

- 接收用户输入的用户和密码，若用户名为 ‘admin’ ，且 密码为‘123456’ ，则提示用户登录成功，否则让用户一直输入。

## 5. 简答题：关键字汇总

能简单说出这些关键字的作用

- let
- const
- typeof
- if
- else
- switch
- case
- default
- while
- prompt
- alert
- console
- document.write

## 6. 拓展题

用户输入年份和月份，打印出这个月有多少天

- 1 3 5 7 8 10 12有31天
- 4 6 9 11有30天
- 2月平年28天，闰年29天（闰年条件：能被400整除 或者 被4整除但不被100 整除）





