using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace players_guide1
{
    class Program
    {

        static void Main(string[] args)
        {
            //CountToTen();
            // DoSomething();
            int number = Convert.ToInt32(Console.ReadLine());
            int[] tablica = new int[number];

            Console.WriteLine("Generowanie elementow");
            GenerateNumbers(number,tablica);

            Console.WriteLine("Wypisywanie:");
            Wypisz(tablica);

            Console.WriteLine("Podmiana elementow");
            PodmienElementy(tablica);

            Console.WriteLine("Wypisywanie elementow");
            Wypisz(tablica);

            //strona: 126

            ///<summary>
            ///Takes two numbers and multiplies them together, returning the result.
            /// </summary>
            /// <param name="a">First to multiplay</param>
            /// <param name="b">Second to multiplay</param>
            /// <returns>Product of 2 params</returns>
            
            Console.ReadLine();
        }

        //static void CountToTen()
        //{
        //    for (int i = 0; i < 10; i++)
        //    {
        //        Console.WriteLine(i);
        //    }
        //}
        //static void DoSomething()
        //{
        //    int aNumber = 1;
        //    if (aNumber == 2) return;
        //    Console.WriteLine("This only gets printed if the 'return' statement wasn't executed.");
        //}
        static void GenerateNumbers(int number,int[] tablica)
        {    
            for (int i = 0; i < number; i++) tablica[i] = i;
        }

        static void Wypisz(int[] tablica)
        {
            foreach(int item in tablica) {
                Console.WriteLine(item);
            }
        }

        static void PodmienElementy(int[] tablica)
        {
            int temp=0;
            for(int i=0;i<tablica.Length/2;i++)
            {
                temp = tablica[i];
                tablica[i] = tablica[tablica.Length - i - 1];
                tablica[tablica.Length - i - 1] = temp;
            }
        }
        
        static int Multiplay(int a,int b)
        {
            return a * b;
        }

        static double Multiplay(double a,double b)
        {
            return a * b;
        }

    }
}
