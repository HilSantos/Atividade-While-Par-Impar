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
            int numero;

  Console.Write("Digite um número (0 para sair): ");
            numero = int.Parse(Console.ReadLine());

  while (numero != 0)
            {
                if (numero % 2 == 0)
                    Console.WriteLine("O número é par.");
                else
                    Console.WriteLine("O número é ímpar.");

  Console.Write("Digite um número (0 para sair): ");
                numero = int.Parse(Console.ReadLine());
            }

  Console.WriteLine("Programa encerrado.");
            Console.ReadKey();
        }
    }
}

