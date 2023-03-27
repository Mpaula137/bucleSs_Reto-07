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

## Diagrama de flujo:
[![](https://mermaid.ink/img/pako:eNodT01Pg0AQ_SuTPbW1JMUjERMtVD140ht4mOwOduJ-kGHRGOC_u-vt5X3Nm0XpYEhVarDhR19RIrw3vQd42L141hz2RXH_2HFdfiRwXl6ZfBScgO_q8nTaErl-kxg0JGFtiq61oGc0giaAIWCg5D0cbnO87diNwo4FfKbynURfOr6pS2g9aDQImrUN_9o5tw9op7A-FZ1NUvAmj_LgA0yULrnRUq5-3g3s9zl0yTsTUEflSByySd8tWelVvJKjXlUJGpSvXvV-Sz6cY3j79VpVUWY6qnk0GKlh_BR0qsoLaPsDsLZgaQ?type=png)](https://mermaid.live/edit#pako:eNodT01Pg0AQ_SuTPbW1JMUjERMtVD140ht4mOwOduJ-kGHRGOC_u-vt5X3Nm0XpYEhVarDhR19RIrw3vQd42L141hz2RXH_2HFdfiRwXl6ZfBScgO_q8nTaErl-kxg0JGFtiq61oGc0giaAIWCg5D0cbnO87diNwo4FfKbynURfOr6pS2g9aDQImrUN_9o5tw9op7A-FZ1NUvAmj_LgA0yULrnRUq5-3g3s9zl0yTsTUEflSByySd8tWelVvJKjXlUJGpSvXvV-Sz6cY3j79VpVUWY6qnk0GKlh_BR0qsoLaPsDsLZgaQ)

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

## Diagrama de flujo:
[![](https://mermaid.ink/img/pako:eNp1kM1OwzAQhF_F8qkVjZT2loggAWlKKZzgFvewsjftqvG6chwQavruOAIJ8XcbjXZmPu1JamdQ5rJp3avegw_iuVR8PVmzJjdNkqubmor5NoqytoQcPHSCLot5mqbRTRQPL-gNGPRuWCY12aMnS17QmFnVSxYaDAhNunWCLorFVvFqrFNcxvxQQdu54S6pOxQGQ5xAge3H_VixnjTE04gU9W1kWYxm9Y0ly7JfKPc_UTZ_o2zGNsXVF8rDvyiPnyhyJi16C2Ti406KhVAy7NGiknmUBvxBScXneAd9cE9vrGUefI8z2R8NBCwJdh6szJu4iOd3-FqATw?type=png)](https://mermaid.live/edit#pako:eNp1kM1OwzAQhF_F8qkVjZT2loggAWlKKZzgFvewsjftqvG6chwQavruOAIJ8XcbjXZmPu1JamdQ5rJp3avegw_iuVR8PVmzJjdNkqubmor5NoqytoQcPHSCLot5mqbRTRQPL-gNGPRuWCY12aMnS17QmFnVSxYaDAhNunWCLorFVvFqrFNcxvxQQdu54S6pOxQGQ5xAge3H_VixnjTE04gU9W1kWYxm9Y0ly7JfKPc_UTZ_o2zGNsXVF8rDvyiPnyhyJi16C2Ti406KhVAy7NGiknmUBvxBScXneAd9cE9vrGUefI8z2R8NBCwJdh6szJu4iOd3-FqATw)

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

## Diagrama de flujo:
[![](https://mermaid.ink/img/pako:eNpVkMFKAzEQhl9lyKmFBqTHRQVtt7qKJ71tehiSaRtMJiWbVWR3391ZFdRbyHz_908yKJscqUodQnq3J8wFXraGbxYNe-vTUuvr25b7SDmBQ5f2huVqMzx54pKxA75cT1rr8Y2yzAUbt7rtCBwVQQgogPU2pL3E6sXO89LwZg4cMHRpbIY6QEyuDwnWEgIG6sAfewyAcDHNdX_ld19yH8_ZR4Fn631bM1h0-F0EMs_UFRSfqBxZn4H11XpmN4ab3_KH2VUoR8_4b9HHn0UNq5WSt0f0Tv5oMAxgVDlRJKMqOTrMr0YZnoTDvqTnD7aqKrmnlerPDgttPR4zRlXNlTR9AtLkfEU?type=png)](https://mermaid.live/edit#pako:eNpVkMFKAzEQhl9lyKmFBqTHRQVtt7qKJ71tehiSaRtMJiWbVWR3391ZFdRbyHz_908yKJscqUodQnq3J8wFXraGbxYNe-vTUuvr25b7SDmBQ5f2huVqMzx54pKxA75cT1rr8Y2yzAUbt7rtCBwVQQgogPU2pL3E6sXO89LwZg4cMHRpbIY6QEyuDwnWEgIG6sAfewyAcDHNdX_ld19yH8_ZR4Fn631bM1h0-F0EMs_UFRSfqBxZn4H11XpmN4ab3_KH2VUoR8_4b9HHn0UNq5WSt0f0Tv5oMAxgVDlRJKMqOTrMr0YZnoTDvqTnD7aqKrmnlerPDgttPR4zRlXNlTR9AtLkfEU)

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

Explicación= Este es otro punto el cual se me dificulto mucho investigando aclare muchas dudas y entendi qu para que el programa adivinara un número primero que todo habia que manejar todo con booleanos luego se tenia que acortar en rangos lo que es nuevo que use fue "respuesta.lower" lo cual se utiliza para buscar algo que se escriba esto sirvio para preguntar al usuario si el numero era mayor al numero que daba la condición de rango luego la condición while ayudaba ya que hacia que se le sumara 1 a las variables a las que lleaba el programa y se pudiera adivinar el número.

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
Explicación: Pedimos que al usuario que ingrese una variable llamada ingresado, se le solicitara que ingrese un número entre 2 y 53 para hallar los divisores, ponemos un condicional en el programa el cual permitira fijar el rango en el cual debe estar el número ingresado y claramente si esta se emprimen los divisores sino se le dice que no sirve el número ingresado, luego declaramos otra variable y la inicializamos en 1 ya que a partir de ahí se tiene que verficar si cumple a ser divisor luego ponemos la condición while es decir mientras el divisor sea menor o igual a número ingresado seguir con el proceso luego decimos que si el ingresado con modulo de el divisor es igual a 0 quiere decir que es divisor, en cada ciclo se le sumara 1 al divisor para comprobar si es divisor y se le pide al programa imprimir los que cumpla las condiciones.

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
Explicación: Este me confundio mcuho tuve que pensarlo mucho lo intente y no me daba asi que tuve que buscar guias, luego de buscar guias pude hacerlo usando banderas aunque habian diferentes maneras, como se ve en el código llamo la función y doy una condición la cual dice que si el número es menor o igual a 1, es falso, luego inicalizo la variable "contador" en 2 ya que es el primer numero primo, luego decimos que mientras la variable "contador" sea menor o igual a la raiz del número se da la condición de que el modulo entre el número y el contador sea igual a 0, es falso, ya que se sabe que tiene mas divisores, luego le decimos que el "contador" en cada ciclo tiene que sumar 1 para retonar true si no se cumple la condición, luego damos la condición para que esto se que en un rango menor o igual a 100 claramente llamando a que la funcion se cumpla.

## trate de explicar lo mejor que pude todo lo que realice en este reto, graciass!!! nos vemos en el proximo
