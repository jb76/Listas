string delet = null; 

Console.WriteLine("Ingrese el nombre del listado que desea eliminar;");
                if (indice > 0 && indice < nombres.Length)
                {

indice = Convert.ToInt32(Console.ReadLine());
                    nombres[indice] = delet;
                    Console.ReadLine();
                }
                  else
                {
                    Console.WriteLine("el nombre " + indice + "no existe en el vector ");
                }


