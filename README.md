using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace Vowels_Sum
{
    class Program
    {
        static void Main(string[] args)
        {
            string word = Console.ReadLine();
            int simbolSum = 0;

            for (int i = 0; i < word.Length; i++)
            {
                char simbol = word[i];


                switch (simbol)
                {
                    case 'a': simbolSum += 1; break;
                    case 'e': simbolSum += 2; break;
                    case 'i': simbolSum += 3; break;
                    case 'o': simbolSum += 4; break;
                    case 'u': simbolSum += 5; break;
                   

                }
            }
            Console.WriteLine(simbolSum);
        }
    }
}
