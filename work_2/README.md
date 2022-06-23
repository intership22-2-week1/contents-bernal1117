#   DIA 2 - 21/06/2022

## CONOCIENDO REPLIT y CODESPACES
Pudimos conocer replit y sus funcionamientos asi como codespaces, en el mismo vimos las ventajas de usar estar plataformas
asi como un ejercicio 
    ![img](/assets/DIA2.PNG)

## INTRODUCCION A LA TERMINAL 
Aprendimos varios comandos de la terminal para navegar entre carpetas, manipular archivos, conectarse a servidores remotos.
Por ejemplo: cat, mkdir, touch, nano, ls, clear, rm -rf, ls -lh, muchos mas.

Asi como un script como ejercicio
 ![img](/assets/DIA2A.PNG)
 ![img](/assets/DIA2B.PNG)

 
## PENSAMIENTO LOGICO
Consejos sobre el pensamiento asi como su funcionamiento detallado

## FUNDAMENTOS Y ALGORTINMO 
Vimos muchisimos temas relacionados al tema asi como 
-   Algoritmos
-   Tipos de datos
-   Diagramas de flujo
-   Estructuras de control
-   Excepciones
-   Ciclos
-   Funciones
-   Modularizacion de codigo 

## ACTIVIDAD 
RESPUESTAS:
1. ¿Qué haría usted para que cuando un cliente compre algún producto se utilicen la menor cantidad de botellas, y se desperdicie la menor cantidad de espacio en las mismas.?
   - Lo que yo haria para evitar desperdicios de botellas es realizar un algoritmo el cual determine que botellas son las adecuadas a elegir segun la cantidad exigida       por el cliente segun el stock registrado con la cantidad de botellas y su medida.
2. Plasme la descripción de su algoritmo
- INICIO
- Variable x = 0
- Variable cantidad = 0
- Variable B500 = 0, B350 = 0, B250 = 0, B100 = 0
- Variable BT500 = 500, BT350 = 350, BT250 = 250, BT100 = 100
- Pedir cantidad en ml
- Asignar ese valor a la variable cantidad 
- DO  
- IF cantidad es mayor o igual a BT500 tome MAX en STOCK | MIN en STOCK 
-    x = 500 
-   cantidad = cantidad - x
-    STOCK -1 
-    B500 ++
-  IFELSE cantidad es mayor o igual a BT350 | MIN en STOCK
-    x = 350 
-    cantidad = cantidad - x
-    STOCK -1
-    B350 ++
-  IFELSE cantidad es mayor o igual a BT250 | MIN en STOCK
-    x = 250 
-    cantidad = cantidad - x
-    STOCK -1
-    B250 ++ 
-  IFELSE cantidad es mayor o igual a BT100 | MIN en STOCK 
-    x = 100 
-    cantidad = cantidad - x
-    STOCK -1
-    B100 ++
- WHILE cantidad diferente de 0
- IMPRIMIR "Cantidad de botellas optimas a utilizar"
- IMPRIMIR "Botella 500" + B500 + "Botella 350" + B350 "Botella 250" + B250 "Botella 100" + B100 
- FIN
3. Ejemplifique cómo distribuiría el liquido en los contenedores de la tabla de arriba 
con las siguientes compras ficticias, siguiendo su propuesta.

![img](../assets/ac1.png)

2. Taller de santa claus



