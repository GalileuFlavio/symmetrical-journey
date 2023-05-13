# symmetrical-journey
Exemplo simples de um Programa em C# que interage com o usuário usando o .NET Framework:
using System;

namespace MeuPrograma
{
    class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("Bem-vindo ao meu programa!");
            Console.Write("Por favor, digite o seu nome: ");
            string nome = Console.ReadLine();
            Console.WriteLine("Olá, " + nome + "!");
            Console.WriteLine("Pressione qualquer tecla para sair.");
            Console.ReadKey();
        }
    }
}
