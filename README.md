# bucleSs_Reto-07
Este repositorio es para usar bucles (while)

## Primer punto:

- Imprimir un listado con los números del 1 al 100 cada uno con su respectivo cuadrado.

```
#<bloque_prev>
i=1
while i<= 100:
    print ("El cuadrado de", i , "es:" , str(i**2))
    i +=1
```

Explicación: Aca inicializamos la variable i con el valor de 1 para luego decirle al programa que mientras la variable i sea menor o igual a 100 imprimir el cuadrado de este numero, en la ultima parte le decimos al programa que para cada ciclo que se realice se le sume 1 a i.

## Segundo punto:

- Imprimir un listado con los números impares desde 1 hasta 999 y seguidamente otro listado con los números pares desde 2 hasta 1000.


```
 #Impresion numeros pares de 1-1000
i=2
while i<=1000:
    print("Los pares son:", i)
    i += 2

```


```
#Impresion numeros impares de 1-1000
i=1
while i<=999:
    print("Numero impar:", i)
    i+=2

```    
Explicación:  En la primera se incializa en 2 ya que es la lista de los pares y asi contrariamente incializamos el segundo en 1 ya que es el primer impar luego le decimos al programa que mientras i sea menor que 1000 o 900 en cada codigo imprima el par es decir que sumando 2 en cada lista va a dar tanto el impar como el par.

## Tercer punto:

- Imprimir los números pares en forma descendente hasta 2 que son menores o iguales a un número natural n ≥ 2 dado

``` 
n=int(input("Ingrese un número:"))

#Garantizamos que n sea mayo o igual a 2
while n<2:
    n = int(input("El número ingresado no es válido, ingrese uno mayor a 2!!"))
i=n
while i>=2:
    if i%2 ==0:
        print(i)
    i -=2

```
Explicación: Ponemos primero el input para que usuario ingrese la varibale damos la condición de que mientras "n" sea menor a 2 el programa no va a funcionar porque ingreso un numero menor, luego inicalizamos la variable "i" con el valor de n damos la condición que mientras que "i" sea mayot a 2 y si "i" con modulo 2 es igual a 0 imprimos i pero como queremos la lista descendente le decimos al ciclo que reste dos en cada ciclo valga la rebundancia.

## Cuarto punto:

- En 2022 el país A tendrá una población de 25 millones de habitantes y el país B de 18:9 millones. Las tasas de crecimiento anual de la población serán de 2% y 3% respectivamente. Desarrollar un algoritmo para informar en que año la población del país B superará a la de A.

```
#definimos la variable
poblacion_a= 25000000
poblacion_b= 18900000
tasa_crecimiento_A= 0.02
tasa_crecimiento_B= 0.03
anio =2022

while poblacion_b < poblacion_a :
    anio += 1 #incrementar el año
    #calcular el nuevo tamaño de la población
    poblacion_a += poblacion_a*tasa_crecimiento_A
    poblacion_b += poblacion_b*tasa_crecimiento_B
    #Imprimir el resultado de la población
print("La población del pais b supero a la población del pais a en año", anio)

```
Explicación: Aca definimos las variables luego las inicializamos con los valores ya determinados luego damos la condicion de que mientras la población b se menor que la poblacion a, se tiene que calcular el crecimiento de cada poblacion sumandolo con el resultado obtenido en cada ciclo se sabe que se tiene que incrementar el año mientra se incremente la población le decimos al programa que imprima en que año la población b supera la población a.

## Quinto punto:

- Imprimir el factorial de un número natural n dado.

```
n=int(input("Ingrese un numero para realizar el factorial:"))
factorial=1

while n> 0:
    factorial *= n
    n -= 1
print("El factorial es:", factorial)

```
Explicación: Primero colocamos la variable la cual será insertada por el usuario luego inicializamos la variable factorial en 1 para saber que inciamos siempre ahi, luego ponemos la condición de que mientras n se mayor a 0 hacer que el programa multiplique el factoria por n sabiendo que en cada ciclo se va a resta un 1 para que de el factorial hasta que n sea menor que 0.


## Sexto punto:

- Implementar un algoritmo que permita adivinar un número dado de 1 a 100, preguntando en cada caso si el número es mayor, menor o igual.

```
print("Ten en cuenta un numero, este programa lo adivinara")

Numminimo =int=1
Nummaximo =int=100
numero = bool = False

while not numero:
    #Vamos a adivinar el numero basandonos en la mitad del rango
    intento = ( Nummaximo + Numminimo)// 2
    respuesta = input("Es el numero que elegiste" + str(intento)+"? (si/no)")
    
    if respuesta.lower() == "si": #El lower busca el datos escritos asi sea en mayusculas o minisculas
        #Es el fin de el bucle
        numero= True
    elif respuesta.lower() == "no":
        #decidimos preguntar si el  numero es mayor
        respuesta = input("Es el numero mayor que" + str(intento)+"? (si/no)")
        if respuesta.lower() == "si":
            Numminimo = intento + 1
        elif respuesta.lower()=="no":
            #si el numero es menor se ajusta el rango al maximo
            Nummaximo = intento - 1
        else:
           print("Lo que ingresaste no es valido")

print("He adivinado!!")

```
## Septimo punto:

- Implementar un programa que ingrese un número de 2 a 50 y muestre sus divisores.
```

ingresado= int(input("Ingrese un numero desde el 2 al al 50:"))

if ingresado < 2 or ingresado > 50: #Colocamos un condicional que le permite identificar al programa si el numero esta en el rango
    print("El numero no es valido ")
else:
   print("los divisores de", ingresado, "es:")

   divisor= 1 #se inicia con uno ya que el bloque while va a verficar de ahi todos los numeros

   while divisor<= ingresado:# La sangria es primordial para que se ejecute el bloque del codigo
       if ingresado% divisor == 0:
        print(divisor)

       divisor +=1 # se tiene que ir sumando un 1 para que se compruebe el siguiente
```
Explicación: Pedimos que al usuario que ingrese una variable llamada ingresado, se le solicitara que ingrese un numero entre 2 y 53 para hallar los divisores, ponemos un condicional en el progrma el cual permitira figar el rango en el cual debe estar el número ingresado y claramente si esta se emprimen los divisores sino se le dice que no sirve el número ingresado, luego declaramos otra variable y la inicializamos en 1 ya que a partir de ahí se tiene que verficar si cumple a ser divisor luego ponemos la condición while es decir mientras el divisor sea menor o igual a numero ingresado seguir con el proceso luego decimos que si el ingresado con modulo de el divisor es igual a 0 quiere decir que es divisor, en cada ciclo se le sumara 1 al divisor para comprobar si es divisor y se le pide al programa imprimir los que cumpla las condiciones.

## Octavo punto:

- Implementar el algoritmo que muestre los números primos del 1 al 100. nota: use funciones
```
def Es_primo(numero):
    if numero <= 1:
        return False
    
    contador = 2

    while contador <= numero**0.5:
        if numero % contador == 0:
            return False

        contador +=1
    
    return True

numero = 1

while numero <= 100:
    if Es_primo(numero):
     print(numero)
    
    numero +=1

```
