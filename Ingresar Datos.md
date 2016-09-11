class Array
    {
        static void Main()
        {
            string[] nombres;
            int indice;
            ushort num = 10;
            nombres = new string[10];
            for (int i = 0; i < num; i++)
            {
                Console.Write("Escribe el nombre {0} ", i);
                nombres[i] = Console.ReadLine();
            }
            Console.WriteLine("Se han Ingresado los {0} nombres con exito !!! \n", num);
	     Console.WriteLine ();
   }

}
