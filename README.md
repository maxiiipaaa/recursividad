# recursividad

La recursividad en programación es una técnica donde una función se llama a sí misma para resolver un problema. Tiene dos partes clave:

    Caso base: Condición que detiene la recursión.
    Llamada recursiva: Parte donde la función se llama con un argumento modificado.

Un ejemplo común es el cálculo del factorial de un número. Es útil para descomponer problemas complejos, aunque puede ser menos eficiente que métodos iterativos.
Un ejemplo clásico de recursividad es el cálculo del factorial de un número. Aquí tienes un ejemplo en pseudocódigo:

```plaintext
función factorial(n):
    si n == 0:
        devolver 1  // Caso base
    sino:
        devolver n * factorial(n - 1)  // Llamada recursiva

def mostrar_descendente(n):
    if n < 1:  # Caso base
        return
    print(n)  # Mostrar el número
    mostrar_descendente(n - 1)  # Llamada recursiva

mostrar_descendente(5)
