using System;

namespace ConsoleApp1
{

    class Calculator
    {
        // numbers and opperator
        public float number
        {
            get; set;
        }
        public float result
        {
            get; set;
        }
        // add method
        public void Add(float num)
        {
            number = result;
            result = number + num;
            Console.WriteLine("{0} + {1} = {2}", number, num, result);
        }
        // sub method
        public void Substract(int num)
        {
            number = result;
            result = number - num;
            Console.WriteLine("{0} - {1} = {2}", number, num, result);
        }
        // multiply method
        public void Multiply(int num)
        {
            number = result;
            result = number * num;
            Console.WriteLine("{0} * {1} = {2}", number, num, result);
        }
        // devide method
        public void Devide(int num)
        {
            if (num == 0)
            {
                Console.WriteLine("Can't devide by zero");
            }
            else
            {
                number = result;
                result = number / num;
                Console.WriteLine("{0} / {1} = {2}", number, num, result);
            }
        }
        // clear method
        public void Clear()
        {
            number = 0;
            result = 0;
            Console.WriteLine("Calculator reseted to zero");
        }
    }
    internal class Program
    {
        static void Main()
        {
            Calculator calculator = new Calculator();
            calculator.number = 10;
            calculator.Add(10);
            calculator.Multiply(30);
            calculator.Devide(4);
            calculator.Devide(0);
            calculator.Clear();
            calculator.Substract(20);
        }
    }
}
