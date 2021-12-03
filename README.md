using System;

namespace coins
{
    class Program
    {
        static void Main(string[] args)
        {

            string username = Console.ReadLine();
            string password = Console.ReadLine();

            string user = username;
            string pass = password;
            bool isFalse = username != user && password != pass;
            while (!isFalse)
            {
                username = Console.ReadLine();
                password = Console.ReadLine();
                if (!isFalse)
                {
                    Console.WriteLine("Welcome");
                    break;
                }
                else
                {
                    Console.WriteLine("Invalid password");
                    Console.WriteLine("Try again");
                }
                


                
            }

            double cocaCola = 1.20;
            double fanta = 1.20;
            double sprite = 1.20;
            double chocolate = 1.15;
            double milk = 1.40;
            double waffle = 0.50;

            double totalPrice = 0;

            double client = 0;
            string command = Console.ReadLine();
            while (command!="Total")
            {

                if (client == cocaCola)
                {
                    totalPrice +=cocaCola;
                }
                if (client == fanta)
                {
                    totalPrice += fanta;
                }
                if (client == sprite)
                {
                    totalPrice += sprite;
                }
                if (client == chocolate)
                {
                    totalPrice += chocolate;
                }

            }

        }
    }
}
