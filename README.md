# Family
using System;
namespace Uteshitel
{
    class onli
    {
        static void Main(string[] args)
        {
            AA1 f= new AA1();
            AA1.family();
            AA2 g= new AA2();
            AA2.son();
            AA3 h = new AA3();
            AA3.daughter();
        }
    }
    class Parents
    {
        public static void family()
        {
            Console.Write("Введите своё имя:");
            string a = Console.ReadLine();
            Console.WriteLine($"Имя :{a}");
            Console.ReadKey();

        }
        public static void son()
        {
            Console.WriteLine("Имя: Александр ");
            Console.WriteLine("возраст: 18");
            Console.WriteLine("класс: 11");
            
        }
        public static void daughter()
        {
            Console.WriteLine("Имя: Аня ");
            Console.WriteLine("возраст: 16");
            Console.WriteLine("класс: 9");
        }
    }
    class AA1 : Parents
    {

    }
    class AA2 : Parents
    {

    }
    class AA3 : Parents
    {

    }
}
