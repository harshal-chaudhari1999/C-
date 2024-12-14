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

// **C# Program for Properties**

using System;

namespace program   //Constructor
{
     public class Car
    {
        private string names;
        public string Name 
        {
            get { return names; }
            set { names = value; }
        }
    }

    class main_
    {
        public static void Main(string[] args)
        {
            Car car = new Car();
            Console.WriteLine(car.Name = "lalit");
            
        }
    }
}
// **2**
using System;

namespace program   //Constructor
{
     public class Car
    {
        private string names;
        public string Name 
        {
            get { return names; }
            set {
                if (value != "harshal")
                {
                    Console.WriteLine("success");
                    names = value;
                   
                }
            }
        }
    }

    class main_
    {
        public static void Main(string[] args)
        {
            Car car = new Car();
            car.Name = "harshal";
            Console.WriteLine(car.Name);

        }
    }
}
