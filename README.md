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
using System;
class Program {
    public static void Main(string[] args) {
      int factos = 1;
          Console.WriteLine("Ingrese un Numero");
          int num = int.Parse(Console.ReadLine());
      for (int i = 1; i <= num; i ++) {
        factos = factos * i;
        }
      Console.WriteLine(factos);
        }}
```

## **Cuarto Ejercicio**

```c#
using System;

class Program {
  public static void Main (string[] args) {
    Console.WriteLine("Ingrese un Numero");
    int num = int.Parse(Console.ReadLine());
    while (num >1 && num % 2 == 0) {
      num /= 2;
      }
    if (num == 1) {
      Console.WriteLine("Es Potencia de 2");
    }  else {
      Console.WriteLine("No es Potencia de 2");
    }
    }
  }
```

## **Quinto Ejercicio**

```c#
using System;
class Program {
    public static void Main(string[] args) {
          Console.WriteLine("Ingrese un Numero");
          int num = int.Parse(Console.ReadLine());
          Console.WriteLine("Ingrese otro Numero");
          int num2 = int.Parse(Console.ReadLine());
         Console.WriteLine(Math.Pow(num, num2));
        }}
```

## **Sexto Ejercicio**

```c#
using System;

class Program {
  public static void Main (string[] args) {
          int multi = 1;
          Console.WriteLine("Ingrese un Numero");
          int num = int.Parse(Console.ReadLine());
    for (int x = 1; x < 11; x ++) {
      Console.WriteLine (multi + " x " + multi + " = " +(num * multi));
      multi +=1;
    }
  }
}
```
