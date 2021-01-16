 Console.WriteLine("Pick a number between 1 and 10. Keep it in your head.");
            Console.WriteLine("Multiply your number by two. Multiply the new number by 5. Divide the current number by the original number. Subtract 7 from the current number.");
            Console.WriteLine("The Number is 3? Yes(1) or no(2)?");
            double thinkingofanumber = Convert.ToInt32(Console.ReadLine());
            if (thinkingofanumber == 1)
            {
                Console.WriteLine("I guessed your number!");

            }
            else
            {
                Console.WriteLine("I am stupid.");
            }
