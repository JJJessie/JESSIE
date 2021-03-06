# Java基本运算符
 Java针对操控变量提供了一组丰富的操作符。我们可以将所有的Java操作符分为如下几组：  
- 算数运算符
- 关系运算符
- 位运算符
- 逻辑运算符
- 赋值运算符
- 其他运算符  

##算数运算符
算术运算符在数学表达中的使用和它们在代数中的使用是相同的。下面的表格列举了算数运算符：  
假设整体变量A有10个，变量B有20个，那么：  

## 示例：  

|运算符   | 描述         | 例子|  
|---------|:------------:|--------:|
|+|    加法 – 在运算符的另一端增加 |A+B为30 |
|-|    减法 – 将右侧的操作数从左侧的操作数中减去|A - B 为-10 |
|* |	   乘法 – 将运算符两端的值相乘	|A * B 为200 |
|/ |	   除法 – 用右侧操作数除左侧操作数|B / A 为2 |
|% |	   系数 - 用右侧操作数除左侧操作数并返回馀数|B % A 为0 |
|++|   增量 – 给操作数的值增加1|B++ 为21 |
|--|   减量 – 给操作数的值减去1|B—为19 |  

##关系运算符：
以下是java语言可支持的关系运算符。  
假设变量A有10，变量B有20，那么：  

##示例:  
|运算符    | 描述         | 例子|  
|---------:|------------:|--------:|
|==      	|检查双方操作数的值是否相等，如果相等那么条件为真 |	(A == B) 不为真。|
|!=      	|检查双方操作数的值是否相等，如果不相等那么条件为真|	(A != B) 为真。|
|>		      |检查左侧的操作数是否大于右侧的操作数，如果大于那么条件为真	|(A > B) 不为真。|
|<		      |检查左侧的操作数是否小于右侧的操作数，如果小于那么条件为真	|(A < B) 为真。|
|>=	      |检查左侧的操作数是够大于等于右侧的操作数，如果是那么条件为真|	(A >= B) 不为真。|
|<=       |检查左侧的操作数是否小于等于右侧的操作数，如果是那么条件为真|	(A <= B) 为真。|

##位运算符：
Java定义了几种运算符，这类运算符可被运用于整数型式，long, int，short，字符型和字节型。  
位运算符作用于二进制系统间传输标准，并执行按位操作。假设如果a等于60；b等于13；现在在二进制型式下它们就如下所示：  
a = 0011 1100

b = 0000 1101

-----------------

a&b = 0000 1100

a|b = 0011 1101

a^b = 0011 0001

~a  = 1100 0011  

以下表格列举了位运算符：  
假设整数变量A有60个，B有13个那么：  
##示例：
|运算符   | 描述         | 例子|  
|---------|:------------:|--------:|
|&	       |二进制AND运算符在结果上复制一位如果在双方操作数同时存在|	(A & B) 为12，即 0000 1100|
|\|	      |二进制OR运算符在结果上复制一位如果在任何一个操作数上存在|	(A \| B) 为61，即0011 1101|
|^	       |二进制XOR 运算符复制位，如果它是设置在一个操作数上而不是两个。|	(A ^ B) 为49， 即0011 0001|
|~	       |二进制补充运算符是一元的，b并有“翻转”位的影响|	(~A ) 为 -61，由于是带符号的二进制数，那2的补位形式为1100 0011|
|<<       |二进制左移运算符。左侧操作数的值根据右侧操作数指定的位的数量移至左侧。|	A << 2 为240 ，即1111 0000|
|>>       |二进制右移运算符。左侧操作数的值根据右侧操作数指定的位的数量移至右侧。	|A >> 2 为 15即1111|
|>>>      |右移补零运算符。左侧操作数的值根据右侧操作数指定的位的数量移至右，并且转移的值用零补满。|	A >>>2 为15 ，即0000 1111|

##逻辑运算符：  
以下表格列举了逻辑运算符：  
假设布尔数学体系变量A为真，B为假，那么：  
##示例：
|运算符   | 描述         | 例子|  
|---------|:------------:|--------:|
|&&	      |称为逻辑与运算符。如果双方操作数都不为零，那么条件为真。|	(A && B) 为真.|
|\|\|     |称为逻辑或运算符. 如果双方操作数其中的任何一个都不为零，那么条件为真。	|(A \|\| B) 为真.|
|!	       |称为逻辑非运算符. 用作翻转操作数的逻辑状态。如果一个条件为真，那么逻辑非运算符为假。|	!(A && B) 为真.|

##赋值运算符：  
以下是由Java语言所支持的赋值运算符：  
##示例： 
|运算符   | 描述         | 例子|  
|---------:|------------:|--------:|
|=	      |简单及运算符, 将右侧操作数的值赋给左侧操作数|	C = A + B 会将 A + B 的值赋给 C|
|+=	     |增加及赋值运算符, 它将右侧的操作数增加到左侧的操作数并且结果赋给左侧操作数|	C += A 同等于 C = C + A|
|-=	     |减去及赋值运算符，它将右侧操作数从左侧操作数中减去并将结果赋给左侧操作数|	C -= A 同等于C = C - A|
|*=     	|乘以及赋值运算符，它将右侧操作数与左侧相乘并将结果赋给左侧操作数|	C *= A 同等于 C = C * A|
|/=	     |除以及赋值运算符，它将右侧操作数除左侧操作数并将结果赋给左侧操作数|	C /= A 同等于 C = C / A|
|%=	     |系数及赋值运算符 需要系数运用两个操作数并且将结果赋给左侧操作数|	C %= A is 同等于 C = C % A|
|<<=     |左移和赋值运算符|	C <<= 2 同等于C = C << 2|
|>>=     |右移和赋值运算符|	C >>= 2 同等于 C = C >> 2|
|&=	     |按位和赋值运算符|C &= 2 同等于C = C & 2|
|^=	     |按位异或及赋值运算符|	C ^= 2 同等于 C = C ^ 2|
|\|=	    |按位可兼或及赋值运算符|	C \|= 2 同等于C = C | 2|

##其它运算符： 
以下是由Java语言所支持的一些其他的运算符：

##条件运算符（？：）：  
条件运算符同样也被称作为三元运算符。这种运算符由三个操作数组成，被用作评估布尔数学体系表达。这种运算符的目的是来决定哪些值应被赋予到变量上。这个运算符被写作如下：  
```
variable x = (expression) ? value if true : value if false 
```
以下是示例：  
```
public class Test {

   public static void main(String args[]){
      int a , b;
      a = 10;
      b = (a == 1) ? 20: 30;
      System.out.println( "Value of b is : " +  b );

      b = (a == 10) ? 20: 30;
      System.out.println( "Value of b is : " + b );
   }
}
```  
这样就会有如下结果：  
```
Value of b is : 30
Value of b is : 20
```
## Instanceof 符
这种操作符只用于对象引用变量。这种操作符检查对象是否是独特类型（类型或接口类型）。Instanceof 运算符写为：  
```
( Object reference variable ) instanceof  (class/interface type)
```
如果在运算符左侧的由变量所指代的对象为右侧的类型或接口类型通过IS-A检查，那么结果为真。以下是示例：  
```
public class Test {

   public static void main(String args[]){
      String name = "James";
      // following will return true since name is type of String
      boolean result = name instanceof String;  
      System.out.println( result );
   }
}
```
这就会产出如下结果：  
```
true
```
这种运算符仍会返回到真如果被比较的对象是与右边类型兼容的赋值。以下是另一个例子：  
```
class Vehicle {}

public class Car extends Vehicle {
   public static void main(String args[]){
      Vehicle a = new Car();
      boolean result =  a instanceof Car;
      System.out.println( result );
   }
}
```
这样将会产生以下的结果：  
```
true
```
##Java 运算符的优先级:
运算符优先级决定一个表达式里术语的分组。它影响着一个表达式如何求值。一定的运算符比其他运算符拥有更高的优先级；例如：乘法运算符比加法运算符有更高的优先级：
例如，x=7+3 * 2; 这里x 被赋值为13，不是20，是因为运算符 * 比运算符+由更高的优先级， 所以它首先运算乘法 3*2, 然后再加7。 

这里，有着最高优先级的运算符在这个表格的最高一层，最低优先权的则出现在最底部。在一个表达式中，越高等级的优先权的运算符会最先被求值。  

|类       |运算符     |关联性|
|---------:|---------:|-----:|
|后缀     |	() [] . (dot operator)|	从左到右|
|一元     | 	++ - - ! ~          |	从右到左|
|乘法的   |	* / % 	              |从左到右|
|加法的   | 	+ - 	              |从左到右|
|移位	    | >> >>> <<            	|从左到右|
|关系的   | 	> >= < <=           |从左到右| 
|相等	    |== !=                  |从左到右|
|位与	    |&                      |从左到右|
|位异或   |	^        	            |从左到右|
|位或	    | 	 \|                  |从左到右|
|逻辑与	  |&&                     |从左到右| 
|逻辑或	  |        \|\| 	           |从左到右|
|有条件的 |	?: 	                  |从右到左|
|赋值	    | = += -= *= /= %= >>= <<= &= ^== |从右到左|
|逗号     |	   , 	                 |从左到右|  
##接下来是？  
接下来的一章将会解释Java程序设计中的循环控制。该章节将会描述不同种类的循环以及这些循环如何运用到Java程序发展和以什么样的目的来使用它们。  











