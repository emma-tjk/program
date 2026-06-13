using System;

class Program
{
    static void Main()
    {
        double n1, n2, n3, average;

        Console.Write("نمره درس اول: ");
        n1 = Convert.ToDouble(Console.ReadLine());

        Console.Write("نمره درس دوم: ");
        n2 = Convert.ToDouble(Console.ReadLine());

        Console.Write("نمره درس سوم: ");
        n3 = Convert.ToDouble(Console.ReadLine());

        average = (n1 + n2 + n3) / 3;

        Console.WriteLine("\nمعدل شما: " + average);

        if (average >= 17)
            Console.WriteLine("وضعیت: عالی");
        else if (average >= 12)
            Console.WriteLine("وضعیت: خوب");
        else
            Console.WriteLine("وضعیت: نیاز به تلاش بیشتر");
    }
}