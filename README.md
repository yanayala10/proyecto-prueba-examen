def comprar_entradas()
 print('precio entradas del 1 a 20 es: $100.000')
 print('precio entradas del 21 a 30 es: $50.000')
 print('precio entradas del 31 a 50 es: $10.000')

 cant_entradas = int(input('ingrese las cantidad de entradas entre 1 y 2 '))
  if cant_entradas < 0 and cant_entradas > 3
  cant_entradas = int(input('la cantidad ingresada no esta en los parametros provavor ingresa nuevamente la cant de entradas'))
 # Crear matriz de 8 filas y 20 columnas
  sala = []
  for i in range(8):
      fila = []
      for j in range(20):
          fila.append("O")
      sala.append(fila)
    # Marcar asientos vendidos
  sala[0][4] = "X"
  sala[2][4] = "X"
  sala[3][2] = "X"
  sala[4][7] = "X"
  # Mostrar matriz en pantalla
  for fila in sala:
      for asiento in fila:
          print(asiento, end=" ")
      print()
  ubicacion = int(input('ingresa una ubicacion y te dire si esta ocupada o no '))
  while ubicacion == sala
   print('la ubicacion ingresada ya esta ocupada')
   ubicacion = int(input('ingrese nuevamente la ubicacion porque la recien ingresada ya estaba ocupada'))
  print('ubicacion libre')

  print('se a guardado correctamente')

  def ubicaciones_disponibles()
  # Seleccionar ubicaciones
  while entradas > 0:
      # Pedir ubicación del asiento
      ubicacion = input("Ingrese la ubicación del asiento (ejemplo: A1): ")

      # Obtener fila y columna del asiento
      fila = ord(ubicacion[0]) - 65
      columna = int(ubicacion[1:]) - 1

      # Verificar si el asiento está disponible
      if sala[fila][columna] == "X":
          print("La ubicación seleccionada no está disponible.")
      else:
          # Marcar asiento como vendido
          sala[fila][columna] = "X"
          entradas -= 1

  # Mostrar matriz actualizada en pantalla
  for fila in sala:
      for asiento in fila:
          print(asiento, end=" ")
      print()
fila = 0
columna = 0
ubicacion = 0
entradas = 0
fila = []
sala = []
cant_entradas = 0
comprar_entradas = 0
opc = 0
elegir = 1
while elegir == 1
print('opcion 1 comprar entradas')
print('opcion 2 mostrar ubicaciones ')
print('opcion 3 ver lisrado de asistentes')
print('opcion 4 mostrar ganancias totales')
print('opcion 5 salir del programa')
try:
  opc = int(input('ingresa una opcion'))
   if opc == 1
    print('has elegido la opcion de comprar entradas')
    comprar_entradas()
   elif opc == 2
    print('has elegido la opcion de mostrar ubicaciones disponibles')
   elif opc == 3
    print('has elegido la opcion de ver listado de asistentes')
   elif occ == 4
    print('has elegido la opcion de mostrar ganancias totales')
   elif opc == 5
    print('has elegido la opcion de salir del sistema')
    print('Adios ')
    print(' Yan Ayala')
    print('11-17-2023')
    elegir = 0
