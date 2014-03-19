using System;



    class PrimeNumberCheck
    {
        static void Main()
        {
            Console.WriteLine("Enter your number: ");
            int number = int.Parse(Console.ReadLine());
            int p = 1;
            for (int i = 1; i <+ number ; i++)
            {
                p = p * i;
            }
            p = p + 1;
            if (number % p == 0)
            {
                Console.WriteLine(true);
            }
            else
            {
                Console.WriteLine(false);
            }
        }
    }
