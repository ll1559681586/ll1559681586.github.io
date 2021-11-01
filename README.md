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

Console.Writeline("Hello World!");

Console.Readline();                    //Writeline与Readline配合使用，实现打印效果。

```

## Variables 变量
```makedown

关于变量，我的想法是将某个值存在一个变量中，变量有自己的名字并且拥有自己的类型，会在多出地方出现一个值时会使用变量

在Writeline中的一些写法：

string characterName="Jack";

Console.Writeline("There once was a man named "+characterName);  //引号外 +变量名 ，直接将变量打印在句子最后面

characterName="Mike";    //从这一行开始，往下的characterName变量的值变成Mike

Console.Writeline("There once was a man named "+characterName+"");  //引号内 "+变量名+"

Console.Read();

```

## DATA TYPE 数据类型
```makedown

1.  string--->string characterName="John";     //string字符串 characterName变量名 （引号内必须为英文字母）（必须有双引号）

2.  int------>int characterAge=25;            //无需双引号，值是整数，可正可负

3.  char---->char name1='A';                 //单引号，值必须是单个字母，可大写可小写

4.  double-->double name2=3.3;            //值为小数类型，最常用的小数的数据类型

5.  float和decimal     //float数字后面加F

```

