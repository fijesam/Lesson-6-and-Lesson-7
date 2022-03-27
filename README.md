# Lesson-6
//Lesson 6 exercise 1
using System;

namespace Lesson_6_Exercise_1
{
    class Program
    {
        static void Main(string[] args)
        {
            //Lesson 6 exercise 1
            Console.Write("Enter the number of columns: ");
            int N = int.Parse(Console.ReadLine());

            int[] matrixF = new int[N];

            for (int i = 0; i < N; i++)
            {
                Console.Write("matrixF[{0}] = ", i);
                matrixF[i] = int.Parse(Console.ReadLine());
                Console.WriteLine(matrixF);
                if (matrixF[i] % 7 == 0 && matrixF[i] % 3 == 0)
                {
                    
                        
                        
                    break;
                   

                }

                    
                    Console.WriteLine(matrixF);


            }
            Console.WriteLine("Hello World!");
        }
    }
}



//lesson 6 exercise 2
using System;

namespace Lesson_6_Exercise_2
{
    class Program
    {
        static void Main(string[] args)
        {
            //lesson 6 exercise 2
            //Enter the value of 300 for n
            Console.Write("Enter the value n: ");
            int n = int.Parse(Console.ReadLine());
            for (int i = 0; i < n; i++)
            {
                if (i % 7 == 0 && i % 5 != 0) 
                {
                    Console.WriteLine(+i);
                    continue;
                }
            }
            Console.WriteLine("Hello World!");
        }
    }
}
