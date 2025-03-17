# Curso de Java 🚀  

Este repositorio marca el inicio de mi aprendizaje en Java.  

## Primer programa: "Hola Mundo"  

El siguiente código imprime "Hola Mundo con Java" y un saludo adicional:  

```java
public class HolaMundo {
    public static void main(String[] args) {
        System.out.println("Hola Mundo con Java");
        System.out.println("Saludos");
    }
}

```
📌 **Objetivo**:
Aprender los fundamentos de Java y desarrollar aplicaciones prácticas.
✨ ¡Vamos por más! 🚀

# 📌 Variables en Java  
📌 Fuente: [GlobalMentoring.com.mx](https://www.GlobalMentoring.com.mx)

Una variable es un contenedor que almacena datos que pueden cambiar durante la ejecución de un programa.  

Una variable almacena un valor y dicho valor puede ser de un tipo de dato en particular. En Java tenemos los siguientes tipos de datos:  

## 🔹 Tipos Primitivos  
Son tipos de datos simples:  

- **Enteros:** `byte`, `short`, `int`, `long`  
  - Ejemplo: `-10`, `127`, etc.  
- **Punto Flotante:** `float` y `double`  
  - Ejemplo: `-12.6`, `3.1416`, etc.  
- **Carácter:** `char`  
  - Ejemplo: `'0'`, `'@'`, etc.  
- **Booleano:** `boolean`  
  - Ejemplo: `true`, `false`  

## 🔹 Tipos Object (Referencia)  
Almacenan referencias a objetos:  

- **Cadenas:** `String`  
  - Ejemplo: `"Karla"`  
- **Arreglos:** `int[]`, `String[]`  
- **Objetos de Clases:** Cualquier instancia de una clase definida por el usuario.  
---  
# 📌 Sintaxis para definir Variables en Java

Para definir una Variable se debe especificar el tipo de dato que va almacenar Variable, seguido del nombre de la variable. El valor se puede asignar al momento de la declaración o posteriormente.

## 🔹 Ejemplo de Sintaxis de Variables en Java:
```java
tipo nombreDeLaVariable = Valor

```
## 🔹 **Ejemplos variables en Java**:

```java
- int Edad = 15; //Declaración y Asignación
- double Salario; //Declaración de variable
- salario = 5000,50; //Asignación posterior
- String mensaje = "Hola Mundo"; //Variable tipo object
---
```
# 📌 Sintaxis para definir Variables
## Tipos de Datos en Java

```java

        //Enteros (Su valor por default es 0)
        byte tipoByte = 127;
        System.out.println("tipoByte = " + tipoByte); //Concatenación de cadenas
        short tipoShort = 32000;
        int tipoInt = 2147483647;
        long tipoLong = 987654321098765432L; // L o l para indicar que es tipo long
                
        //Punto (Su valor por default es 0.0)
        float tipoFloat = 3.14F; // F o f para indicar que es tipo flotante
        double tipoDouble = 3.1315; // D o d para indicar que es tipo double (opcional)
                
        //Caracter (Su valor por deafult es '\u0000') para indicar que el valor es 0 pero en el juego de caracteres UNICODE
        char tipoChar = 'A'; //Caracteres del juego UNICODE
        tipoChar = 65; //65 Representa la letra A en el juego de caraceres UNICODE
        tipoChar = '@';
                
        //Booleano (Su valor por deafult es false)
        boolean tipoBoolean = true;
        tipoBoolean = false;
                
        //Tipos Object (Referencia)
        String nombre = null; //si no se asigna un valor a la variable por default su valor es null - ausencia de referencia o ausencia de valor
        nombre = "Juan Pérez";       
---
```
# 📌 Reglas de Nombres de Variables en Java

Los nombre de variables en JAVA son esenciales para la legibilidad y mantenibilidad del código. Seguir buenas prácticas ayuda a que el código sea más comprensible y profesional.

## 1️⃣ Reglas
1. Debe comenzar con una letra, un símbolo de dolar ($) o guión bajo (_)
   Ej: nombre, _nombre, $nombre
2. No puede comenzar con espacio ni caracteres especiales.
   Ej: nombreCliente
3. No puede ser una palabra reservada de Java (keyword).
   Ej: No usar int, for, while, class, etc.
4. Distingue entre mayúsculas y minúsculas.
   Ej: nombre, Nombre y NOMBRE son 3 variables distintas
---
## 2️⃣ Buenas prácticas en nombres de las variables

1. **Usar Camel Case para nombres de variabñes:** Comienza con minúscula y cada nueva palabra su primer letra inicia con mayúscula.
   Ej: nombreCompleto, edadPersona.
2. **Ser descriptivo y claro:** Los nombres de las palabras deben describir claramente su propósito.
   Ej: precioProducto, numeroTelefono (sin uso de acentos, solo caracteres soportados en el idioma inglés).
4. **Prefijos y Sufijos claros (solo si es necesario):** prefijo 'is' y 'has' en tipos booleanos.
   Ej: isActivo, hasPrecio
5. **No abusar de abreviaturas:**
   Ej: Usar totalPiezas en lugar de totPzs.
---


