namespace pradeep;
class system
{
    public static void Main(string[] args)
    {
        int t, s; int r = 123, age;
        Console.WriteLine("         ****Election Commision of India****");
        Console.Write("Are you a new registrant? :");
        Console.Write("if yes press 1 & if no press 2:");
        int k = Convert.ToInt32(Console.ReadLine());
        if (k is 1)
        {
            Console.WriteLine("       ****registration portal*****");
            Console.Write("Name : ");
            String n = Console.ReadLine();
            Console.Write("Age :");
            age = Convert.ToInt32(Console.ReadLine());
            if (age < 18)
            {
                Console.WriteLine("Sorry bro you are not eligible");
            }
            Console.Write("Father Name :");
            String l = Console.ReadLine();
            Console.Write("Mother Name :");
            String p = Console.ReadLine();
            Console.Write(" preferred voter id :");
            s = Convert.ToInt32(Console.ReadLine());
            Console.Write("Mob No : ");
            int m = Convert.ToInt32(Console.ReadLine());
            Console.WriteLine("     ****Your Profile****");
            Console.Write("Name :" + n);
            Console.WriteLine("Age :" + age);
            Console.WriteLine("Father name :" + l);
            Console.WriteLine("Mother name" + p);
            Console.WriteLine("Voter id :" + s);
            Console.WriteLine("         ");
            Console.WriteLine("       *****Login portal*****");
            Console.Write(" voter id : ");
            int i = Convert.ToInt32(Console.ReadLine());
            if (s == i)
            {
                Console.WriteLine("           ");
                Console.WriteLine("     **** parties *****");
                Console.Write("1.Telugudesam 2.YCP 3.JSP :");
                int h = Convert.ToInt32(Console.ReadLine());
                if (h == 1)
                {
                    Console.WriteLine(" Thank you Thammudu: Vote 1");
                }
                else
                {
                    Console.WriteLine("okka chance");

                }
                if (h == 2)
                {
                    Console.WriteLine("Nenu vunnanu nenu vinnanu: Vote 1");
                }
                if (h == 3)
                {
                    Console.WriteLine("Hello Ap bye bye Ycp: Vote 1");
                }
            }
        }
        else
        {
            Console.WriteLine("           ");
            Console.WriteLine("       *****Login portal*****");
            Console.WriteLine(" voter id : ");
            int e = Convert.ToInt32(Console.ReadLine());
            if (e == r)
            {
                Console.WriteLine("Name : Pradeep");
                Console.WriteLine("Age  : 19");
                Console.WriteLine("Father Name : Prabhakar");
                Console.WriteLine("Mother Name : Samatha");
                Console.WriteLine("           ");
                Console.WriteLine("     **** parties *****");
                Console.Write("1.Telugudesam 2.YCP 3.JSP :");
                int h = Convert.ToInt32(Console.ReadLine());
                if (h == 1)
                {
                    Console.WriteLine(" Thank you Thammudu: Vote 1");
                }
                else
                {
                    Console.WriteLine("okka chance");

                }
                if (h == 2)
                {
                    Console.WriteLine("Nenu vunnanu nenu vinnanu: Vote 1");
                }
                if (h == 3)
                {
                    Console.WriteLine("Hello Ap bye bye Ycp: Vote 1");
                }
            }
        }


    }



    
}
