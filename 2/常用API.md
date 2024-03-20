# 常用API

## Objects

![](images/2024-03-18-21-58-58.png)

### 使用Objects.equals的好处

![](images/2024-03-18-22-00-08.png)

可见使用s1.equals(s2)时，当其中一个对象为null时，将会报错

## 包装类

![](images/2024-03-18-22-09-45.png)

![](images/2024-03-18-22-14-19.png)

### 其它常见操作

![](images/2024-03-18-22-20-46.png)

![](images/2024-03-18-22-24-37.png)

也可以直接使用valueOf

![](images/2024-03-18-22-25-15.png)

## StringBulider和StringBuffer

### StringBulider

![](images/2024-03-20-10-46-14.png)

![](images/2024-03-20-10-46-44.png)

### StringBuffer

![](images/2024-03-20-10-55-09.png)

## StringJoiner

![](images/2024-03-20-10-56-38.png)

## Math

![](images/2024-03-20-15-20-56.png)

## System

![](images/2024-03-20-15-21-30.png)

## Runtime

![](images/2024-03-20-15-22-55.png)

## BigDecimal

![](images/2024-03-20-15-23-43.png)

![](images/2024-03-20-15-23-58.png)

推荐使用

```java
Double a = 0.01;
BigDecimal a = BigDecimal.valueOf(a);
```
将a转换为BigDecimal型数据

### 注意事项

![](images/2024-03-20-15-27-17.png)



