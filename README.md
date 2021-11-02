# C# Learning Notes
### Something useful.
[Click here](https://github.com/ll1559681586/ll1559681586.github.io/edit/main/README.md) to modify my notes.

[Jekyll](https://jekyllrb.com/) to rebuild the pages in your site.

Get help : [documentation](https://docs.github.com/categories/github-pages-basics/) 
 or [contact support](https://support.github.com/contact)
 
 [Makedown使用方法](https://www.jianshu.com/p/191d1e21f7ed)
 
 网页主题 [repository settings](https://github.com/ll1559681586/ll1559681586.github.io/settings/pages). 主题名保存在 Jekyll `_config.yml` configuration file.
## 初始的代码框架
```makedown
using System;

using System.Collections.Generic;

using System.Linq;

using System.Text;

using System.Threading.Tasks;

namespace FirstTry 

{

    class Program
    
    {
    
        static void Main(string[] args)
        
        {
        
          在此输入具体代码

        }
        
    }
    
}
```
## Hello World!
```makedown

Console.WriteLine("Hello World!");

Console.WriteLine();                    //Writeline与Readline配合使用，实现打印效果。

```

## Variables 变量
```makedown

关于变量，我的想法是将某个值存在一个变量中，变量有自己的名字并且拥有自己的类型，会在多出地方出现一个值时会使用变量

在Writeline中的一些写法：

string characterName="Jack";

Console.WriteLine("There once was a man named "+characterName);  //引号外 +变量名 ，直接将变量打印在句子最后面

characterName="Mike";    //从这一行开始，往下的characterName变量的值变成Mike

Console.WriteLine("There once was a man named "+characterName+"");  //引号内 "+变量名+"

Console.Read();

```

## DATA TYPE 数据类型
```makedown

1.  string--->string characterName="John";     //string字符串 characterName变量名 （引号内必须为英文字母）（必须有双引号）

2.  int------>int characterAge=25;            //无需双引号，值是整数，可正可负

3.  char---->char name1='A';                 //单引号，值必须是单个字母，可大写可小写

4.  double-->double name2=3.3;            //值为小数类型，最常用的小数的数据类型

5.  float和decimal     //float的小数后面加F,decimal的小数后面加M

6.  bool--->bool isMale=true;  //bool的值可以是ture和false (只有这两种)

```
## Working with string （string的细节知识点）[详细](https://docs.microsoft.com/en-us/dotnet/api/system.string?view=net-5.0#methods)
```makedown
string phrase="John"+"Mike";  //输出结果会直接在John后面加上Mike

一丶String Methods

变量名.method   [Console.Writeline(phrase.Toupper())]
1.    phrase.Toupper()和phrase.Tolower()  //phrase的值全变成大写或小写

2.    phrase.contains("")  //双引号内输入字母，如果输入的字母在phrase中有的话就会输出Ture，没有就是False

3.    phrase[0]  //输出phrase的值的第一个字母,1就是输出第二个字母

4.    phrase.Indexof("")  //双引号中输入phrase里有的字母(多位数字母)，会输出这个字母在第几位，双引号改成单引号，里面只能输单个字母  

5.    phrase.substring(2,3)  //输出phrase值从第二个字母起的三个字母

```
## Working with numbers
```makedown
Console.WriteLine(3+2) //输出5 其他算法也一样

Console.WriteLine(5/2.0)  //输出2.5  除2的话输出2

Console.WriteLine(Math.Pow(6,2)) //6的2次方

Console.WriteLine(Math.Abs(-6))  //绝对值6

Console.WriteLine(Math.sqrt(36))  //开根号等于6

Console.WriteLine(Math.max(9,90))  //90更大 输出90  只能对比两个数（Min是对立的）




```
## Getting user input
```makedown
 Console.Write("type your name:");   //打印
 
 string name = Console.ReadLine();  //把玩家输入的内容存到name里面，变量类型是string
 
 Console.WriteLine("Hello "+name);  //打印
 
 string age = Console.ReadLine();   //和name一样
 
 Console.WriteLine("Hi " + name +" you are "+age);  //打印
 
 Console.ReadLine();   //readline实际上是为了读取用户输入的数据，把那个黑色界面显示在那里，但这句放在最后的话，不管输入了什么再回车，也只是单纯的读取完了关掉，其他什么都不做。

```
