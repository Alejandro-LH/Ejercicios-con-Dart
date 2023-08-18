# Ejercicios 1

### Código #1:

#### main:

```dart
void main () {     //void=vacio (no retorna a nada);

var nombre = "Jahir"; // punto y coma para finalizar una instruccion (;).

print("Hola " + nombre); 
print("Hola $nombre"); //esto es una interporacion en el string (inyectar un valor dentro).

}

//salida: Hola Jahir
```

### Código #2:

#### main:
```dart
 // Programa que muestra el producto de dos números enteros.

void main(List<String>args) {
  Operaciones op = new Operaciones ();
  print (op.suma(2,3));
}

///Clase que permite realizar operaciones aritmeticas
class Operaciones {
///[a] es el primer argumento a sumar
int? a;
///[b] es el primer argumento a sumar 
int? b;
///Metodo que obtiene la suma de a + b
///
///[a] y[b] deben ser tipo int 
///
///uso: 
///```
///Operaciones op = new Operaciones ();
///print (op.suma(2,3));
///```
///Resultado:
///```bash
///5

  int suma (int a, int b){
  return a + b;
 }
}

// salida: 5
```

### Código #3:

#### main:

```dart
// Definir un numero con el tipo de dato "int" e imprimirlo.

void main () {
 int numero = 1; // Scope: es el lugar donde esta variable solo va a sobrevivir dentro de estos corchetes.
 print(numero);
}

// salida: 1
```


### Código #4:

#### main:

```dart
// Asignar dos variables con diferente tipo de dato y multiplicarlos.

void main () {
  var n1,n2; //dynamic es cunado no sabemos que tipo de dato es.
  n1=2; 
  n2="-";
  print(n2*n1); //no puedo poner primero el n1 por que si no no se puede ejecutar.
}

//salida: -
```


### Código #5:

#### main:

```dart
// Esto es una interporacion de cadenas.

void main () {
  int edad = 19;
  String nombre = "Jahir";
  print("Hola $nombre, tienes $edad años"); // El simbolo de "$" se utiliza para inyectar o insertar variables.
}

// salida: Hola Jahir, tienes 19 años
```

### Código #6:

#### main:

```dart
// Obtenga el producto de dos numero enteros.

void main () {
  int n1 = 15;
  int n2 = 30;
  print(n1 * n2);
}

// salida: 450
```

### Código #7:

#### main:

```dart
// Programa que muestra el producto de dos números enteros.
void main () {
  int n1 = 10;
  int n2 = 7;
  print("$n1 * $n2 = ${n1 * n2}"); // Los corchetes sirven para obtener el producto de las variables.
}

// salida: 10 * 7 = 70
```

### Código #8:

#### main:

```dart
// crear un programa que reciba un correo y que verifique que el correo termine con @ucol.
void main(List<String>args) {
  String correo = args[0]; // Recibimos el correo como argumento.
  
  if (correo.endsWith("@ucol.mx")) { // Verificamos que el correo termine con @ucol para eso usamos el método endsWith.
    print("tu correo '$correo' ha sido registrado con éxito");
  } else { // Si no cumple con la condición anterior, entonces se imprime el mensaje.
    print("El correo '$correo' que ingresaste no cumple con nuestras normas, intenta nuevamente");
  }
}

// salida: tu correo 'jlopez139@ucol' ha sido registrado con éxito
```

### Código #9:

#### main:

```dart
// Programa que muestra el producto de dos números enteros.
void main () {
  int? variable;
  variable = 8;
  print(variable*2);
  print(variable.runtimeType); // runtimeType nos dice el tipo de dato de la variable.
}

// salida: 16
```

### Código #10:

#### main:

```dart
// hacer un programa que reciba un número y que imprima el número al cuadrado.

 import 'dart:math';

void main() {
  int n = 5; 
  print("5 al cubo = ${pow(n, 3)}"); // pow es una función que recibe dos parámetros, el primero es la base y el segundo es el exponente.
  print(max(5, 10)); // max es una función que recibe dos parámetros y regresa el mayor de ellos.
  print(max(5.5, 4.5)); 
}

num maximo (num a, num b) { // num es un tipo de dato que puede ser int o double.
  if (a > b) { // Si a es mayor que b, entonces regresamos a.
    return a;
  } else {
    return b; // Si no, regresamos b.
  }
}

// salida: 5 al cubo = 125.0
```
