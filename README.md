# recursividad
La recursividad en programación es una técnica en la que una función se llama a sí misma para resolver un problema. Este enfoque se utiliza para descomponer un problema complejo en subproblemas más simples y manejables. 

Una función recursiva generalmente tiene dos componentes:

1. **Caso base**: Es una condición que detiene la recursión. Sin este caso, la función continuaría llamándose a sí misma indefinidamente, lo que resultaría en un error de desbordamiento de pila.

2. **Llamada recursiva**: Es la parte donde la función se llama a sí misma con un argumento modificado, acercándose al caso base.

Un ejemplo clásico de recursividad es el cálculo del factorial de un número. Aquí tienes un ejemplo en pseudocódigo:

```plaintext
función factorial(n):
    si n == 0:
        devolver 1  // Caso base
    sino:
        devolver n * factorial(n - 1)  // Llamada recursiva
```

La recursividad puede ser muy elegante y fácil de entender, pero es importante usarla adecuadamente, ya que puede consumir más memoria y tiempo de ejecución en comparación con enfoques iterativos.
