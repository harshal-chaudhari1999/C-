# C-
C# programs

// **C# program for Constructor**
using System;

namespace program   //Constructor
{
     class Car
    {
        int carPrice;
        Car() 
        {
            carPrice = 3000;
            Console.WriteLine("the price of a Car is :" + carPrice);

        }
    }
    public static void Main (string[] args)
    {
        Car obj1 = new Car();
    }
}
