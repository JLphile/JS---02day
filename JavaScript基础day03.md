

## JavaScript基础day03测试题



#### 1. 关于数组的常用方法，下列描述正确的是（A）

- A： 数组能在本长度内任意位置删除元素
- B： 数组只能在头部追加或删除元素
- C： 数组只能在头部或尾部追加或删除元素
- D： 上述描述都是错误的

#### 2. 关于javascript中数组的说法中,不正确的是（A）

- A： 数组的长度必须是创建时给定,之后便不能改变
- B： 数组里面可以存放多个数据
- C： 数组中元素的类型可以不同
- D： 数组可以在声明的同时进行初始化

#### 3. let arr = [] 声明数组未给值，请问里面的值是什么？ （D）

- A、true
- B、false
- C、null
- D、undefined

#### 4.下面关于for循环说法正确的是（D）

- A： for(;;) 这种写法会出现语法错误
- B： 在for循环中,不能用break语句跳出循环体
- C： for循环是先执行循环体语句,后判断表达式（终止条件）
- D： for循环的循环体语句中,可以包含多条语句,但必须用花括号括起来

#### 5.以下代码,依次输出的结果为 （D）

```html
<script>
  let i
  for (let i = 0; i < 5; i++) {
    console.log(i)
  }
  console.log(i)
</script>
```

- A： 0 1 2 3 4 4
- B： 5 5 5 5 5 5
- C： 0 1 2 3 4 5
- D： 0 1 2 3 4  undefined

#### 6. 下列语句中 helloworld打印的次数是 （D）

```html
<script>
	for (var i = 0; i <= 3; i++) {
        for (let j = 1; j <= 3; j++) {
          console.log('helloworld')
        }
	}
</script>
```



- A： 3次
- B： 4次
- C： 9次
- D： 12次

#### 7. 关于数组的说法错误的是（D）

- A： 可以按照索引号查找数组元素
- B： 能存储多个数据
- C： 按照索引遍历数组方便
- D： 数组只能存储一种类型的数据

#### 8. 关于数组的描述错误的是 （C）

- A： 数组的创建方式是 let arr = [1, 2, 3, 4, 5]
- B： 数组的长度可以使用 arr.length 来得到
- C： 数组的每一项值都有索引， 索引默认从1开始
- D： 数组里面的元素可以增加和删除等操作

#### 9. 请问以下代码执行的结果是什么？（C）

```html
<script>
    let sum = 0
      let arr = [10, 20, 30, 40]
      for (let i = 0; i < arr.length; i++) {
        if (i === 2) {
          continue
        }
        sum += arr[i]
      }
      console.log(sum)
</script>
```

- A： 0
- B： 60
- C： 70
- D： 100

#### 10. 下面代码输出的结果是（C）

```html
<script>
	let sum = 0
      let arr = [11, 22, 33]
      for (let i = 0; i < arr.length; i++) {
        sum += arr[i]
      }
      console.log(sum)
</script>
```

- A： 66
- B： 0112233
- C： NaN
- D： undefined

#### 11. 今日单词：请问下面那个方法可以删除数组第一个元素？（A）

- A: shift()
- B: unshift()
- C: pop()
- D: push()

#### 12. 今日单词：请问下面那个方法可以删除数组最后一个元素？（C）

- A: shift()
- B: unshift()
- C: pop()
- D: push()
- E: splice()

#### 13. 今日单词：请问下面那个方法可以给数组尾部追加元素？ （D）

- A: shift()
- B: unshift()
- C: pop()
- D: push()
- E: splice()

#### 14.今日单词：请问下面那个方法可以给数组头部追加元素？ （B）

- A: shift()
- B: unshift()
- C: pop()
- D: push()
- E: splice()

#### 15. 今日单词：请问下面那个方法可以删除数组任意元素？ （E）

- A: shift()
- B: unshift()
- C: pop()
- D: push()
- E: splice()

#### 16. 今日单词：请问下面那个方法可以给数组元素排序？ （D）

- A: join()
- B: unshift()
- C: pop()
- D: sort()
- E: splice()



## 代码题

#### 1.写一个程序，要求如下：

- 让用户输入5个有效的年龄（0-100之间），放入数组中
  - 必须输入5个有效年龄，如果无效，则不能放入数组中
- 打印出所有成年人的年龄（数组筛选）
- 打印所有人总年龄（累加）
- 打印平均年龄
- 打印最大年龄和最小年龄（最大值）

#### 2.找出数组中元素为10的下标，有则打印该下标，没有打印-1

- 例如：[88,20,10,100,50] 打印2
- 例如：[88,20,30,100,50] 打印-1

#### 3. 用for循环，求出数组元素的和[5,8,9,2,1,5]

#### 4.使用for循环-求出数组里大于5的数据和[4,9,5,20,3,11]

#### 5.for循环，求出班级同学们平均年龄[15,19,21,33,18,24]

#### 6.计算[2,6,18,15,40]中能被3整除的偶数的和

#### 7.计算[2,6,18,15,40]中能被3整除的偶数的个数

#### 8.给一个数字数组，该数组中有很多数字0，将不为0的数据存到一个新的数组中[2,6,0,18,0,0,15,40,0]
