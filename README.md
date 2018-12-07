# -

using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;

namespace ConsoleApplication1//名称
{
    class Program
    {
        static void Main(string[] args)//main函数程序起点
        {
            //Console.WriteLine("Hello  World!");//Ctrl+k+c快速注释，Ctrl+k+u取消注释
            //const double pi = 3.14;//const是定义常量
//            int _a33 = 6;//变量名称只有下划线字母数字@，首字且不为数字
//            Console.WriteLine("圆的面积是" + pi * _a33 * _a33);//这里是+
//            Console.WriteLine("shishi\n");//\n是自动换行而，在console.writeline(@"\n");这样@就是来忽略转义字符
//            Console.Write("有无line");//有line自动换行，没有则接着这一行
//            Console.Write("有无line");//@还可以用在一行过长，空格到下一行时候保证程序正常，如下
//            Console.WriteLine(@"aaaaaaaaaaaaaaaaaaaaaaaaa
//            aaaaaa");

//            Object z = "..55说得到的大大大大大大大大大大大大555555555555.........我..";
//            String num = ".15532爱事实上是事实是事实是事实是事实是事实上上";
//            Char number = '子';  //这个只能有一个字符（字，数字，符号）
//            Console.WriteLine(z);

//            Console.WriteLine(num);
//            Console.WriteLine(number);



            Console.WriteLine("请您的输入姓名");
            string name = Console.ReadLine();
            Console.WriteLine("请输入年龄");
            string age = Console.ReadLine();                                              
            Console.WriteLine("请您输入喜欢的女生类型");
            string la = Console.ReadLine();


            Console.WriteLine("接下来将会筛选出适合你的类型,请按任意键继续");
            Console.ReadLine();
            object nvhaizi = "母猪";
            

            Console.WriteLine("{0}先生，您好,适合您的女生是{1}", name, nvhaizi);
Console.ReadLine();
            Console.WriteLine("请输入语文成绩");
            double yuwen = Convert.ToDouble(Console.ReadLine());
            Console.WriteLine("请输入数学成绩");
            double shuxue = Convert.ToDouble(Console.ReadLine());//consolereadline只能是string类型，用其他的要转换成convert.to类型
            Console.WriteLine("两门合计{0}",shuxue+yuwen);





            Console.ReadKey();




        }
    }
}




using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;

namespace if语句
{
    class Program
    {
        static void Main(string[] args)
        {

            Console.WriteLine("请输入");
            int a=int.Parse(Console.ReadLine());//int.Parse是让用户输入的语句转变为整型
            if (a < 10)
            {
                Console.WriteLine("输入的值<10");//行数多就这样
            }
            if (a > 10) Console.WriteLine("输入的值>10");//行数少的时候可以这样
           


            else
            { Console.WriteLine("输入的值等于10"); }
            Console.ReadLine();


            Console.WriteLine("需要知道的月份");
            int month = int.Parse(Console.ReadLine());
            switch (month)
            {
                case 9: 
                case 4:
                case 6:
                case 11:Console.WriteLine("本月30天"); break;
                case 2: Console.WriteLine("本月28天"); break;
                case 1:
                case 3:
                case 5: Console.WriteLine("31tian"); break;
                default: Console.WriteLine("错误错误\a\a\a\a\a\a\a\a\a\a "); break;
                   
            }


            Console.ReadLine();
            Console.WriteLine("响铃\a\a\a\a\a");
                





            Console.ReadKey();












        }
    }
}




using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;

namespace 练习
{
    class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("Hello,请问，你喜欢吃什么水果？");
           object shuiguo= Console.ReadLine();

           Console.WriteLine("哇，好巧，我也喜欢{0}哎",shuiguo);
           Console.ReadLine();
           Console.WriteLine("那么好的，接下来，我们进行一项测试吧\n请按任意键继续");
           Console.ReadLine();
           Console.WriteLine("请输入你的姓名");
           object name=Console.ReadLine();
           Console.WriteLine("请输入您的出生年份");
           double a =Convert.ToInt32(Console.ReadLine());
          
            Console.ReadLine();
            
            Console.WriteLine("{0}先生您好", name); Console.Write("你的年龄是{0}",2018-a);





           Console.ReadKey();













        }
    }
}
