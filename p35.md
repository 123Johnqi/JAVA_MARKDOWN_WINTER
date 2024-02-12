# Scanner接受用户键盘输入

1. 导包
```java
import java.util.Scanner;
```

(IDEA会自动导包)

2. 实例化Scanner
```java   
Scanner sc = new Scanner(System.in);
```
3. 令一个变量接受键盘的输入，区分nextInt()和next()
```java
int age = sc.nextInt();
string name = sc.next();
```
>nextInt()的返回值为整数，next()的返回值为字符串
