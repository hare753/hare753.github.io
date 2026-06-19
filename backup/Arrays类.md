# `Arrays`类

- 数组的工具类
  - `java.util.Arrays`
- 由于数组对象本身并没有什么方法可以供我们调用
  - 但API中提供了一个工具类Arrays供我们使用，从而可以对数据对象进行一些基本的操作

- ==***查看JDK帮助文档***==



## 类中的方法

- Arrays类中的方法
  - 都是static修饰的静态方法
  - 在使用的时候**可直接使用类名进行调用**
  - 而”不用“使用对象来调用==**（注意：是“不用“而不是“不能”）**==
- 具有以下常用功能：
  - 给数组赋值：通过==**`fill`方法**==
  - 对数组排序：通过==**`sort`方法，按升序**==
  - 比较数组：通过==**`equals`方法比较数组中元素值是否相等**==
  - 查找数组元素：通过==**`binarySearch`方法能对排序好的数组进行二分查找法操作**==

<img width="774" height="716" alt="Image" src="https://github.com/user-attachments/assets/13230de4-d40e-41ad-998a-c610ae9efa3a" />



## 自己实现方法

- 可以自己实现方法：
  - 建议：**不要重复造轮子！！！**
  - 举例：

```java
public static void main(String[] args){
    int[] a = {1,2,3,4,9090,31231,543,21,3,23};
    printArray(a);
}

//打印数组
public static void printArray(int[] a){
    for (int i = 0; i < a.length; i++) {
        if (i==0){
            System.out.print("[");
        }
        if (i==a.length-1){
            System.out.print(a[i] + "]");
        }else {
            System.out.print(a[i] + ", ");
        }
    }
}
```

