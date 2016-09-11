string respuesta, nuevoNombre;
Console.WriteLine("Ingrese el nombre del listado que desea modificar;");
                indice = Convert.ToInt32(Console.ReadLine());
                
                if (indice > 0 && indice < nombres.Length)
                {
                    Console.Write("ingres el nuevo nombre de " + nombres[indice] + ": ");
                    nuevoNombre = Console.ReadLine();
                    nombres[indice] = nuevoNombre;
                }
                  else
                {
                    Console.WriteLine("el nombre " + indice + "no existe en la base de datos ");



