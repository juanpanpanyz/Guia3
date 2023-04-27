# Guia  3  NO SE COPIEN VAGOS

### **Alumno:** Juan Baader

### **Año:** 2023

### **Curso:** 3B TIC

### **Profesor/a** Luu Parrondo

[Link a Github](https://github.com/juanpanpanyz/Guia3)

<br>

## **Primer Ejercicio**

```c#
using System;

class Program {
  public static void Main (string[] args) {
    for (int i = 34; i >= 10; i --) {
      if (i % 2 == 0) {
      Console.WriteLine(i); 
      }
    }
  }
}
```

## **Segundo Ejercicio**

```c#
using System;
class Program {
    public static void Main(string[] args) {
      int suma = 0;
          Console.WriteLine("Ingrese un Numero");
          int num = int.Parse(Console.ReadLine());
      for (int i = 1; i <= num; i ++) {
        suma = suma + i;
        }
      Console.WriteLine(suma);
        }}
```

## **Tercer Ejercicio**

```c#

```

## **Cuarto Ejercicio**

```c#

```

## **Quinto Ejercicio**

```c#

```

## **Sexto Ejercicio**

```c#
using System;

class Program {
  public static void Main (string[] args) {
    Console.WriteLine ("Ingrese un numero para ver su tabla de multiplicar del 1 al 10");
    int amulti = Convert.ToInt32(Console.ReadLine());
    Console.WriteLine ($"{amulti} x 1 = {amulti * 1}");
    Console.WriteLine ($"{amulti} x 2 = {amulti * 2}");
    Console.WriteLine ($"{amulti} x 3 = {amulti * 3}");
    Console.WriteLine ($"{amulti} x 4 = {amulti * 4}");
    Console.WriteLine ($"{amulti} x 5 = {amulti * 5}");
    Console.WriteLine ($"{amulti} x 6 = {amulti * 6}");
    Console.WriteLine ($"{amulti} x 7 = {amulti * 7}");
    Console.WriteLine ($"{amulti} x 8 = {amulti * 8}");
    Console.WriteLine ($"{amulti} x 9 = {amulti * 9}");
    Console.WriteLine ($"{amulti} x 10 = {amulti * 10}");
  }
}
```
