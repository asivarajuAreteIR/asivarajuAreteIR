- class pyramid
{
    public static void Main()
    {
        int num, space;

        while (true)
        {
            Console.Write("Enter a number between 1 to 9 : ");

            num = Convert.ToInt32(Console.ReadLine());

            space = num - 1;

            for (int i = 1; i <= num; i++)
            {
                for (space = 1; space <= (num - i); space++)
                {
                    Console.Write(" ");
                }

                for (int j = 1; j <= i; j++)
                {
                    Console.Write(j);
                }

                for (int k = (i - 1); k >= 1; k--)
                {
                    Console.Write(k);
                }

                Console.WriteLine();

            }
        }

    }
}  
