# Random随机数
## 生成随机数步骤
1. 导包
```java
import java.util.Random;
```
2. 实例化Random
```java
Random r = new Random();
```

3. 生成随机数
```java
int number = r.nextInt(10);
```
>nextInt(n)只能生成0至n-1之间的随机数，不包含n

## 生成65~91之间的随机数
65to91可变换为（0to26）+65，故代码可改为：
```java
int number = r.nextInt(27) + 65;
```

