# Atividade-While-Par-Impar
Solicite ao usuário que insira um número inteiro. Verifique se o número é par ou ímpar. Continue pedindo números até que o usuário insira o número 0, momento em que o programa deve parar.

using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace Ativ.While_Par_Impar
{
    public class Program
    {
        static void Main(string[] args)
        {
            int op, cont, numero, i = 1;
            {
                Console.WriteLine("Digite o numero: ");
                numero = Convert.ToInt32(Console.ReadLine());
                {
                    while (i <= 1)
                    {
                        Console.WriteLine($"É PAR");
                        Console.WriteLine($"É IMPAR");
                        i++
                    }

                    Console.ReadKey();
                }

            }
        }
    }
}

