# Operators 运算符

#### 运算符分为：单目运算符，双目运算符

1. 算术运算符：+ - * / 等日常运算	

2. 运算顺序：由左向右

3. 运算符优先级：【+取正 -取负】> 【*乘法 /除法】>【Div整除 Mod求余】>【+加法 - 减法】

4. 布尔运算符

   1. True/False;  NOT：非  AND与  OR或  XOR异或

5. 位运算符

   1. | **运算符** | **操作举例** | **操作数类型** | **结果类型** | **功能说明**                                     |
      | ---------- | ------------ | -------------- | ------------ | ------------------------------------------------ |
      | NOT        | NOT x        | integer        | integer      | 即按二进制形式将每位求反                         |
      | AND        | a AND b      | integer        | integer      | 将两者相对应的位进行AND运算                      |
      | OR         | a OR b       | integer        | integer      | 将两者相对应的位进行OR运算                       |
      | XOR        | a XOR b      | integer        | integer      | 将两者相对应的位进行取XOR运算，两者不同时结果为1 |
      | SHL        | a SHL b      | integer        | integer      | 将a的二进制值向左移动b位，左移一位相当于乘2      |
      | SHR        | a SHR b      | integer        | integer      | 将a的二进制向右移动b位，右移一位相当于除2        |

6. 关系运算符

   1. | **关系符** | **操作** | **操作数类型**                                         | **结果类型** |
      | ---------- | -------- | ------------------------------------------------------ | ------------ |
      | =          | 等于     | 简单类型，字符串或可变类型，类，类引用，指针，集合类型 | Boolean      |
      | <>         | 不等于   | 简单类型，字符串或可变类型，类，类引用，指针，集合类型 | Boolean      |
      | <          | 小于     | 简单类型，字符串或可变类型                             | Boolean      |
      | >          | 大于     | 简单类型，字符串或可变类型                             | Boolean      |
      | <=         | 小于等于 | 简单类型，字符串或可变类型                             | Boolean      |
      | >=         | 大于等于 | 简单类型，字符串或可变类型                             | Boolean      |

7. 字符串运算符

   1. 常用字符串运算符 ：  +

8. 运算符的优先级

   1. | **优先顺序** | **运算符**              | **分类描述**                   |
      | ------------ | ----------------------- | ------------------------------ |
      | 1            | @（取地址）,NOT,-       | 一元运算符                     |
      | 2            | *,/,DIV,MOD,AND,SHL,SHR | 乘除及类型强制转换运算符       |
      | 3            | +,－,OR,XOR             | 加减运算符                     |
      | 4            | =,< >,<,>,< =,> =,in,is | 关系、集合成员及类型比较运算符 |