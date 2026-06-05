# Scanner对象

## `Java5`新特性

- `java.util.Scanner`
  - ***通过`Scanner`类来获取用户的输入***

- 基本语法：

```java
Scanner s = new Scanner(System.in);
```

- ***获取***输入的字符串：
  - ***通过`Scanner`类的`next()`与`nextLine()`方法***

- 读取前***判断***是否还有输入的数据：
  - ***使用`hasNext()`与`hasNextLine()`方法***



## next()

1. 一定要读取到有效字符后才可以结束输入
2. 对输入有效字符之前遇到的**空白**，`next()`方法**会自动将其去掉**

```java
//输入：Hello World
//输出：Hello
```

3. 只有输入有效字符后才将其后面输入的空白作为分隔符或者结束符
4. `next()`不能得到带有空格的字符串



<img width="851" height="826" alt="Image" src="https://github.com/user-attachments/assets/654aae9b-889e-4602-a2d9-3e8d1a93fff4" />



## nextLine()

- 以`Enter`为结束符
  - 也就是说`nextLine()`方法返回的是**输入回车之前的所有字符**

```java
//输入：我是长颈鹭 狂野震撼亚洲！
//输出：我是长颈鹭 狂野震撼亚洲！
```

- 可以获得***空白***



### 举例

<img width="708" height="761" alt="Image" src="https://github.com/user-attachments/assets/47aa3263-2da6-46b2-8f28-9788ebf9b75b" />



### 格式化写法

<img width="676" height="690" alt="Image" src="https://github.com/user-attachments/assets/51c3fdd5-91e5-4374-ac66-567419ded34b" />



## 进阶使用

- 具体***数据类型***

<img width="698" height="869" alt="Image" src="https://github.com/user-attachments/assets/807d2f65-ddb4-4cad-b78d-03573f3887d7" />

<img width="692" height="397" alt="Image" src="https://github.com/user-attachments/assets/964e8446-da2f-4434-a15d-a21980844012" />



- 实例
  - 求多个数字的总和与平均数

<img width="1000" height="936" alt="Image" src="https://github.com/user-attachments/assets/5a0dff81-6387-41f4-8ca0-6e8ee1ef4bce" />







