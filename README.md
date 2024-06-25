using System;

namespace MoonlitWhispers
{
    class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("Exploring the mysteries of software development under the gentle guidance of moonlit whispers...\n");

            for (int i = 1; i <= 5; i++)
            {
                MoonlitWhisper(i);
                Pause();
            }

            Console.WriteLine("\nThe journey through the night has illuminated our path, whispering secrets only the moon can share.");
        }

        static void MoonlitWhisper(int step)
        {
            switch (step)
            {
                case 1:
                    Console.WriteLine("Step 1: In the stillness of the night, the code begins to breathe.");
                    break;
                case 2:
                    Console.WriteLine("Step 2: Variables and loops dance like shadows under the moon.");
                    break;
                case 3:
                    Console.WriteLine("Step 3: Conditionals whisper choices, guiding the flow of logic.");
                    break;
                case 4:
                    Console.WriteLine("Step 4: Methods become our spells, encapsulating the essence of tasks.");
                    break;
                case 5:
                    Console.WriteLine("Step 5: In the end, the program sleeps, dreaming of new beginnings.");
                    break;
                default:
                    Console.WriteLine("The moon hides its face, and mysteries remain unsolved.");
                    break;
            }
        }

        static void Pause()
        {
            Console.WriteLine("Press any key to continue...");
            Console.ReadKey();
            Console.WriteLine();
        }
    }
}
