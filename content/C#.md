Title:C#
Date: 2010-03-03 10:20
Modified: 2010-12-06 19:30
Category: Programing languages
Tags:Programing languages
Authors:Muhammad Zeeshan
#### Q: Write a code to print rt.angle triangle ?
```
*
**
***
****
*****
******
*******
********
*********
**********
***********
************
*************
**************
***************
****************
*****************
******************
*******************
********************
```
# Code:-
```
namespace ConsoleApplication1
{
    class Program
    {
        static void Main(string[] args)
        {
            int a = 20;
            int i, j, k;
            for (i = 1; i <=a; i++)
            {
                for (j = 1; j <= i; j++)
                {
                    Console.Write("");
                }
                for (k = 1; k <= i; k++)
                {
                    Console.Write("*");
                }
                Console.WriteLine("");
            }
            Console.ReadLine();
        }
    }
}
```
# Output:-
 ![triangle image](images\z.png)



