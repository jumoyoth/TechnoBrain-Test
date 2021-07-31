 static void Main(string[] args)
    {
        Console.WriteLine("This program will convert numbers that you enter into their spoken English counterpart.\nExample: 100 = One Hundred.\n\nPlease enter your desired number to convert: ");
        string getinput = (Console.ReadLine());
        char[] getarray = getinput.ToCharArray();

        for (int getindex = 0; getindex < getarray.Length; getindex++)
        {
            char getchar = getarray[getindex];
            Console.WriteLine("getchar: " + getchar);
            //Console.WriteLine("getarray: " + getarray);
            Console.WriteLine("getindex: " + getindex);
            //int convertinput = Convert.ToInt32(getinput);
        }
    }
    class ToText
    {
        //attributes
        private string[] ones = { "zero", "one", "two", "three", "four", "five", "six", "seven", "eight", "nine" }; //each value is part of the array
        private string[] teens = { "eleven", "twelve", "thirteen", "fourteen", "fifteen", "sixteen", "seventeen", "eighteen", "nineteen" }; //array 0 in this set = "eleven" or tens[0] = "eleven"
        private string[] tens = { "ten", "twenty", "thirty", "fourty", "fifty", "sixty", "seventy", "eighty", "ninety" };
        private string[] moreThan99 = { "hundred", "thousand", "million", "billion", "trillion" };

        //methods
        public string ConvertToText()
        {

        }

        //constructors
        public ToText()
        {

        }
