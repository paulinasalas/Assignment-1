using System;

namespace assignment1
{
    class MainClass
    {
        static void Main(string[] args)

        {
            //Welcome Message
            Console.WriteLine("Welcome to Tropical Bar! \n Please enter your name: ");
            string name = Console.ReadLine();

            //Menu
            Console.WriteLine("Menu: \n 1. Mango Daiquiri $10 \n 2. Jalapeno Watermelon Margarita $10 \n 3. Blackberry Mojito $10 ");
            Console.WriteLine("Which drink would you like to order? ");
            string drink = Console.ReadLine();
            Console.WriteLine("Great choice! You selected:" + drink);

            //Total
            int drinkTotal = 10;
            Console.WriteLine("Your total is: " + drinkTotal);

            //Tip
            Console.WriteLine("Leave a Tip? 1 = Yes 2 = No");
            int y = Convert.ToInt32(Console.ReadLine());
            int x = 10 + 1;
            if (y == 1)
            {
                Console.WriteLine("Thank you! Your total is $" + x);
            }
            else
            {
                Console.WriteLine("Your order is complete!");
            }
        }
    }
}
