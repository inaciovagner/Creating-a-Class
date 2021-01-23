using System;
using System.Collections.Generic;
using System.Text;

namespace new_class_1
{
    class vehicle
    { 
        public void PressHorn()
        {
            Console.WriteLine("Peep peep");
        }
        static void Main(string[] args)
        {
            vehicle car = new vehicle();
            car.PressHorn(); // Outputs "Peep peep"

        }
    }
}
