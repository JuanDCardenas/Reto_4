### Reto_4
Este repositorio contiene el archivo .ipynb del reto#4 de la calse de programación.

Ir a Reto_4.ipynb

### Codigo_1
Dado un número entero, determinar si ese número corresponde al código ASCII de una vocal minúscula.
```python
#punto1
numero=int(input("Ingrese un número entero: "))
if str(chr(numero))=="a":
    print("El número corresponde a el codigo ASCII de una vocal en minuscula")
elif str(chr(numero))=="e":
    print("El número corresponde a el codigo ASCII de una vocal en minuscula")
elif str(chr(numero))=="i":
    print("El número corresponde a el codigo ASCII de una vocal en minuscula")
elif str(chr(numero))=="o":
    print("El número corresponde a el codigo ASCII de una vocal en minuscula")
elif str(chr(numero))=="u":
    print("El número corresponde a el codigo ASCII de una vocal en minuscula")
else :
    print("El número NO corresponde a el codigo ASCII de una vocal en minuscula")
````
### Codigo_2
Dada una cadena de longitud 1, determine si el código ASCII de primera letra de la cadena es par o no.
```python
#punto2
cadena=str(input("Escribe un str de longitud uno:" ))
resultado:int=ord(cadena)
if resultado%2==0:
    print("El ASCII de este caracter es par")
else:
    print("El ASCII de este caracter es impar")
```

### Codigo_3
Dado un carácter, construya un programa en Python para determinar si el carácter es un dígito o no.

```python
#punto3
caracter=(input("Escribe un caracter: "))
resultado=ord(caracter)
if resultado== 48:
    print("Este caracter corresponde a un digito")
elif resultado== 49:
    print("Este caracter corresponde a un digito")
elif resultado== 50:
    print("Este caracter corresponde a un digito")
elif resultado== 51:
    print("Este caracter corresponde a un digito")
elif resultado== 52:
    print("Este caracter corresponde a un digito")
elif resultado== 53:
    print("Este caracter corresponde a un digito")
elif resultado== 54:
    print("Este caracter corresponde a un digito")
elif resultado== 55:
    print("Este caracter corresponde a un digito")
elif resultado== 56:
    print("Este caracter corresponde a un digito")
elif resultado== 57:
    print("Este caracter corresponde a un digito")
else:
    print("Este caracter NO corresponde a un digito")
```

# Codigo_4
Dado un número real x, construya un programa que permita determinar si el número es positivo, negativo o cero. Para cada caso de debe imprimir el texto que se especifica a continuación:

Positivo: "El número x es positivo"
Negativo: "El número x es negativo"
Cero (0): "El número x es el neutro para la suma"

```python
numero=float(input("Escriba un número x =  "))
if numero == 0:
    print("El número x es el neutro para la suma")
elif numero > 0:
    print("El número x es positivo")
else :
    print("El número x es negativo")
```

# Codigo_5
Dado el centro y el radio de un círculo, determinar si un punto de R2 pertenece o no al interior del círculo.

```python
#punto5
radio=float(input("Escribe el radio de la circunferencia: "))
centro_x=float(input("Escribe la coordenada en x del centro de la circunferencia: "))
centro_y=float(input("Escribe la coordenada en y del centro de la circunferencia: "))
punto_x=float(input("Escribe la coordenada en x de un punto del plano: "))
punto_y=float(input("Escribe la coordenada en y de ese punto del plano: "))

if (((centro_x-punto_x)**2+(centro_y-punto_y)**2)**(1/2))>radio:
    print("El punto no esta dentro de la circunferencia")
else:
    print("El punto esta dentro de la circunferencia")
```

# Codigo_6
Dadas tres longitudes positivas, determinar si con esas longitudes se puede construir un triángulo.

```python
#punto6
primer_lado=float(input("Escribe la longitud de un lado: "))
segundo_lado=float(input("Escribe la longitud de otro lado: "))
tercer_lado=float(input("Escribe la longitud de un ultimo lado: "))

if primer_lado==segundo_lado==tercer_lado:
    print("Con estas longitudes si se puede construir un triangulo")
elif primer_lado>=segundo_lado and primer_lado>=tercer_lado:
    if (segundo_lado+tercer_lado)<=primer_lado:
        print("No se puede hacer un triangulo con estas medidas")
    else:
        print("Con estas longitudes si se puede construir un triangulo")
elif segundo_lado>=primer_lado and segundo_lado>=tercer_lado:
    if (primer_lado+tercer_lado)<=segundo_lado:
        print("No se puede hacer un triangulo con estas medidas")
    else:
        print("Con estas longitudes si se puede construir un triangulo")
elif tercer_lado>=primer_lado and tercer_lado>=segundo_lado:
    if (segundo_lado+primer_lado)<=tercer_lado:
        print("No se puede hacer un triangulo con estas medidas")
    else:
        print("Con estas longitudes si se puede construir un triangulo")
```


# By: Juan Diego Cárdenas Olarte
# ∞BT
