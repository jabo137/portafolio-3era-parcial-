**EJERCICIO 1**


#H1 *USANDO 2 VECTORES CAPTURE EDAD Y SEMESTRE DE N ESTUDIANTES*


[![1.jpg](https://i.postimg.cc/Y2PfCgYw/1.jpg)](https://postimg.cc/4nzh8YW8)
[![1-2.jpg](https://i.postimg.cc/y6Dpj7Ts/1-2.jpg)](https://postimg.cc/DmKcykDM)


##H2 prueba de escritorio


corrida|valor i|V E|V S|i=n?|
|-|-|-|-|-|
|1|0|VE[0]=16|VS[0]=3|no|
|2|1|VE[1]=17|VS[1]=5|no|
|3|2|VE[2]=18|VS[2]=7|no|
|4|3|VE[3]=17|VS[3]=5|Si, impr VE y VS|

**Ejemplo**

|Edad|Semestre|
|-|-|
|16|3|
|17|5|
|18|7|
|17|5|


**ENTRADA**

sem| n| edad| 


**SALIDA**


"dame semestre entre [1,12]" | "¿cuantos estudiantes?" | "dame tu edad" | "fuer de rango" | "E,S"





**EJERCICIO 2**


#H1 *USANDO MATRICES CAPTURE EDAD Y SEMESTRE DE N ESTUDUANTES*


[![2.jpg](https://i.postimg.cc/D0PLPCBW/2.jpg)](https://postimg.cc/hQhXS0Fg)


##H2 PRUEBA DE ESCRITORIO 


|corrida|valor i|valor j|matriz|i=n?|
|-|-|-|-|-|
|1|0|0|M[0,0]=16|no|
|2|1|0|M[1,0]=17|no|
|3|2|0|M[2,0]=17|no|
|4|3|0|M[3,0]=16|Si, entonces sig contador|

|corrida|valor i|valor j|matriz|i=n?|
|-|-|-|-|-|
|1|0|0|M[0,1]=3|no|
|2|1|0|M[1,1]=5|no|
|3|2|0|M[2,1]=5|no|
|4|3|0|M[3,1]=3|Si, entonces impr [M]|


**Ejemplo**

|Edad|Semestre|
|-|-|
|16|3|
|17|5|
|17|5|
|16|3|



**ENTRADAS**


N| E| S| 


**SALIDAS**


"¿cuantos estudiantes?"| "fuera de rango"| "edad"| "semestre"| "no. de estudiante".: i+1, "edad": M[i,0], "semestre": m[i,1]|


**EJERCICIO 3**


#H1 *RELLENAR UNA MATRIZ CUADRADA (NxN) CON UN NUMERO LEIDO DEL TECLADO*


[![3.jpg](https://i.postimg.cc/Y0BYBchD/3.jpg)](https://postimg.cc/xJgcL4GL)


##H2 PRUBA DE ESCRITORIO


|i|j|Matriz|num|i=M?|
|-|-|-|-|-|
|0|0|M[0,0|5|no|
|0|1|M[0,1]|7|no|
|0|2|M[0,2]|8|si, entonces J+1 y vuelve a empezar|

**Ejemplo**

|5|7|8|
|-|-|-|
|5|7|8|
|5|7|8|



**ENTRADAS**


N| NUM|


**SALIDAS**


"¿TAMAÑO DE LA MATRIZ?"| "DAME NUM"| "DEBE SER MAYOR A 0"|



**EJERCICIO 4**


#H1 *RELLENAR UNA MATRIZ NxN CON NUMEROS CONSECUTIVOS*


##H2 *ANALISIS*

|1|2|3|
|-|-|-|
|4|5|6|
|7|8|9|


[![4.jpg](https://i.postimg.cc/XJbdTSZH/4.jpg)](https://postimg.cc/2q01Zt7h)


###H3 *PRUEBA DE ESCRITORIO*


|i|j|Matriz|C|i=M?|
|-|-|-|-|-|
|0|0|M[0,0|0|no|
|0|1|M[0,1]|0|no|
|0|2|M[0,2]|0|si, entonces vuelve a empezar|

**Ejemplo**

|1|2|3|
|-|-|-|
|4|5|6|
|7|8|9|


**ENTRADAS**


|N|


**SALIDAS**


|"TAMAÑO DE MATRIZ"| "DEBE SER MAYOR A 2 O MENOR-IGUAL A 100"



**EJERCICIO 5**


#H1 *RELLENE UNA MATRIZ DE NxN PER QUE REPITA TODO EL RENGLON EL MISMO NUMERO


##H2 *ANALISIS*

|1|1|1|
|-|-|-|
|2|2|2|
|3|3|3|

[![5.jpg](https://i.postimg.cc/tJm50vGs/5.jpg)](https://postimg.cc/T5gmg9wx)


###H3 *PRUEBA DE ESCRITORIO*


|i|j|Matriz|C|i=M?|
|-|-|-|-|-|
|0|0|M[0,0|1|no|
|0|1|M[0,1]|1|no|
|0|2|M[0,2]|1|si, entonces C+1 y vuelve a empezar|

**Ejemplo**

|1|1|1|
|-|-|-|
|2|2|2|
|3|3|3|


**ENTRADAS**


|N|


**SALIDAS**


|"TAMAÑO DE LA MATRIZ"| "FUERA DEL RANGO [100,100]"



**EJERCICIO 6**


#H1 *GENERE UNA MARIZ QUE QUEDE*
|1|0|0|0|
|-|-|-|-|
|0|2|0|0|
|0|0|3|0|
|0|0|0|4|

[![6.jpg](https://i.postimg.cc/7LyNyTdn/6.jpg)](https://postimg.cc/3knGXWKk)


##H2 *PRUEBA DE ESCRITORIO*


Primero rellenamos 


|corridas|i|j|M|j=m?|
|-|-|-|-|-|
|1|0|1|M[0,0]=0|no|
|2|0|2|M[0,0]=0|no|
|3|0|3|M[0,0]=0|no|
|4|0|4|0|0|M[0,0]=0|si, entonces i+1 y j=0|

Ejemplo

|0|0|0|0|
|-|-|-|-|
|0|0|0|0|
|0|0|0|0|
|0|0|0|0|

Ahora hacemos la secuencia y en cada ciclo acabado le sumamos 1 a j

|Corridas|i|M|
|-|-|-|
|1|0|M[i,i=i+1|
|2|1|M[i,i=i+1|
|3|2|M[i,i=i+1|
|4|3|M[i,i=i+1|


Ejemplo

|1|0|0|0|
|-|-|-|-|
|0|2|0|0|
|0|0|3|0|
|0|0|0|4|


**ENTRADAS**


|N|


**SALIDAS**


|"TAMAÑO DE LA MATRIZ"| "FUERA DEL RANGO [100,100]"



**EJERCICIO 7**


#H1 *CONVERTIR*
|1|4|9|                      
|-|-|-|                     
|16|25|36|               
|49|64|81|  

    |
    V
 |1|
 |-|
 |4|
 |9|
 |16|
 |25|
 |36|
 |49|
 |64|
 |81|
 
 
 [![7.jpg](https://i.postimg.cc/8ktDJRbs/7.jpg)](https://postimg.cc/XXGttym0)
 
 
 ##H2 *PRUEBA DE ESCRITORIO*
 
 
 
|corridas|Matriz|Vector|j+1|
|-|-|-|-|
|1|M 0,0|M 0,0=V 0|j+1|
|2|M 0,1|M 0,1=V 1|j+1|
|3|M 0,2|M 0,2=V 2|j+1|

If j=M, i+1 and j=0 y regresa el ciclo hasta que i=M

Ejemplo 

|1|2|3|
|-|-|-|
|4|5|6|
|7|8|9|

Para

|1|
|-|
|2|
|3|
|4|
|5|
|6|
|7|
|8|
|9|
 
 
 **ENTRADAS**
 
 
 |N| 
 
 
 **SALIDAS**
 
 
|"TAMAÑO DE LA MATRIZ"| "FUERA DEL RANGO [100,100]"| V[i]|



**EJERCICO 8**


#H1 *EL 1B QUIERE CONOCER EL PROMEDIO POR PERSONA Y POR MATERIA, ADEMAS DE LA MATERIA CON MEJOR PROMEDIO GRUPAL Y AL ALUMNO CON MEJOR PROMEDIO, SON 7 MATERIAS 
Y 32 ALUMNOS, MENCIONE LOS ALUMNOS EN RIESGO (CON ALMENOS 1 MATERIA REPROBADA)


##H2 *ANALISIS*



             a l u m n o s 
             
             
            |1|2|3|4|5|6|7| 
            |-|-|-|-|-|-|-|
            | | | | | | | |
          
    
  [![8.jpg](https://i.postimg.cc/ZKv7tNVC/8.jpg)](https://postimg.cc/crZMfvqS)
  
  
  ###H3 *PRUEBA DE ESCRITORIO*
  
  
|corridas|i|j|M|j+1|
|-|-|-|-|-|
|1|0|0|M 0,0=Materia|j+1|
|2|0|1|M 0,1=Materia|j+1|
|3|0|2|M 0,2=Materia|j+1|
|4|0|3|M 0,3=Materia|j+1|

If J=M, i+1 and j=0, y vuelve a iniciar ahora con calificaciones

Ejemplo 

|Español|Matematicas|Historia|Geografia|
|-|-|-|-|
|5|4|3|9|
|8|6|4|7|
|9|7|7|6|
|7|9|8|7|
  
  
  
  **ENTRADAS**
  
  
  (ASIGNACION)
  M[33,7]
  VA[33]
  VM[7]
  
  
  **SALIDAS**
  
  
  |VA[i]| VM[i]| MM,MA| "ALUMNO EN RIESGO"|
  
  
  
  **EJERCICIO 9**
  
  
  #H1 *PREGUNTE LAS DIMENSIONES DE UNA MATRIZ EL RANGO ES [5,5], VALIDA QUE SEA CUADRADA Y OBTENGA LA SUMA DE LA DIAGONAL PREINCIPAL Y LA INVERSA.
  DETERMINE CUAL ES MAYOR, PREGUNTE LOS VALORES PARA LLENAR LA MATRIZ
  
  
  [![9.jpg](https://i.postimg.cc/XvthygHS/9.jpg)](https://postimg.cc/KKrQ6thJ)
  
  
  ##H2 *PREBA DE ECRITORIO*
  
  
  |corridas|j|M|j+1|
|-|-|-|-|
|1|0|M j,j+sig|j+1|
|2|1|M j,j+sig|j+1|
|3|2|M j,j+sig|j+1|

If j=M, impr Suma 

J=M

|corridas|j|M|j-1|
|-|-|-|-|
|1|0|M j,j+sig|j-1|
|2|1|M j,j+sig|j-1|
|3|2|M j,j+sig|j-1|
  
  
  
  **ENTRADAS**
  
  
 | r| c| 
 
 
 **SALIDAS**
 
 
 |"DAME EL NUMERO DE RENGLONES DE LA MARIZ"| "DAE EL NUMERO DE COLUMNAS"| "EL NUMERO DE COLUMNAS DEBE SER IGUAL AL DE LOS RENGLONES"
 |"FUERA DEL RANGO"| "DP ES MAYOR"| "DI ES MAYOR"| 
 


**EJERCICIO 10**


#H1 *ALMACENAR EN UN ARRAY LA SUMATORIA DE LOS NUMEROS DEL 1 HASTA N EN CADA POSICION DEL ARRAY, EJEMPLO SI N:3 (2,1) EL ARRAY DEBERA SER 1,3,6


##H2 *ANALISIS*


|1|
|-|
|3|
|6|

[![10.jpg](https://i.postimg.cc/ncRCfsS9/10.jpg)](https://postimg.cc/TpbRrP6T)


###H3 *PRUEBA DE ESCRITORIO*


|i|vector|i=V?|
|-|-|-|
|1|0|V[i]=V[i-1]+i+1|
|2|1|V[i]=V[i-1]+i+1|
|3|2|V[i]=V[i-1]+i+1|

Ejemplo

|1|
|-|
|3|
|6|



**ENTRADAS**


|N|


**SALIDAS**


|"TAMAÑO DE ARRAY MENOR  100"| "N DEBE SER >0 Y <100"| "A"|




**EJERCICIO 11**


#H1 *DADA UNA MATRIZ DE NxM ALMACENAR EN UN VECTOR LAS MAYORES*


[![11.jpg](https://i.postimg.cc/sgWyH1kr/11.jpg)](https://postimg.cc/v4Gpc88q)


##H2 *PRUEBA DE ESRITORIO*


|i|j|M|Suma|
|-|-|-|-|
|0|0|M [i,j]>mayor?-->si, M[i,j]=V [c] and C=c+1|j+1|
|0|1|M [i,j]>mayor?-->si, M[i,j]=V [c] and C=c+1|j+1|
|0|2|M [i,j]>mayor?-->si, M[i,j]=V [c] and C=c+1|j+1|
|0|3|M [i,j]>mayor?-->si, M[i,j]=V [c] and C=c+1|j+1|

If J=M, J=0 and I+1 y vuelve a iniciar



**ENTRADAS**


|N| M| NUM|


**SALIDAS**


|"TU NUMERO DE RENGLONES"| "NUMERO DE COLUMNAS"| "FUERA DEL RANGO"| 
    
    
          
