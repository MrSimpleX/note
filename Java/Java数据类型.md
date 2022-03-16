# Java 基础知识-数据类型

Java中的数据类型分为两种 

- 基本类型

- 引用类型

## 基本类型总结

Java中基本数据类型一共有8种

### 布尔型
- boolean 占用 1 bite

### 数值型

- 整数：表示没有小数部分的数值，可以为负数 
  - int 占用 4 bite （-2147483648 ~ 2147483647）  long 占用 8 bite
  - short 占用 2 bite byte 占用 8 bite 
- 浮点数
  - float 占用 4 bite  double 占用 8 bite
- char 类型：用于表述单个字符（Unicode编码），字面值常量需要用单引号包裹
  - char 占用 2 bite

#### Unitcode编码
Unitcode 出现主要是为了统一字符编码机制，在 Unitcode 中，码点是与一个编码表中某个字符对应的编码值

## 引用类型

可以通过类型参数对引用类型进行参数化

- 类类型
- 接口类型
- 数组类型

