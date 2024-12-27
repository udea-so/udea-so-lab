# Apuntadores

# Arreglos y matrices

## Lista de ejemplos

|#|Ejemplo|
|---|---|
|1|[pointers01.c](pointers01.c)|
|2|[pointers02.c](pointers02.c)|
|3|[pointers03.c](pointers03.c)|
|4|[pointers04.c](pointers04.c)|
|5|[pointers05.c](pointers05.c)|
|6|[null.c](null.c)|
|7|[arrays_and_pointers01.c](arrays_and_pointers01.c)|
|8|[arrays_and_pointers02.c](arrays_and_pointers02.c)|
|9|[arrays_and_pointers03.c](arrays_and_pointers03.c)|
|10|[arrays_and_pointers04.c](arrays_and_pointers04.c|
|11|[arrays_and_pointers05.c](arrays_and_pointers05.c)|
|12|[structs_and_pointers01.c](structs_and_pointers01.c)|
|13|[structs_and_pointers02.c](structs_and_pointers02.c)|
|14|[structs_and_pointers03.c](structs_and_pointers03.c)|

## Ejemplos

### Ejemplo 1

```c
#include <stdio.h>

int main()
{
    int a = 1000;
    int b = 2000;

    int *pa = &a;
    int *pb;

    pb = &b;

    // Print values of a and b.
    printf("a = %d\t *pa = %d\n", a, *pa);
    printf("b = %d\t *pb = %d\n", b, *pb);

    // Print addresses of a and b.
    printf("&a = %p\t pa = %p\n", &a, pa);
    printf("&b = %p\t pb = %p\n", &b, pb);
}
```

## Referencias teoricas

A continuación se muestran algunos apuntes de clase que ilustran algunos conceptos teoricos necesarios para comprender la lista de ejemplos adjuntos:

* **Apuntadores y arreglos** [[link]](https://udea-so.github.io/intro-c/content/CH_02-S02.html)
* **Apuntadores y arreglos multidimensionales** [[link]](https://udea-so.github.io/intro-c/content/CH_02-S03.html)
* **Estructuras en C**[[link]](https://udea-so.github.io/intro-c/content/CH_02-S04.html)
* **Structs** [[link]](https://diveintosystems.org/book/C2-C_depth/structs.html)

## Corriendo los ejemplos

Para compilar los ejemplos:

```bash
make
```

Para ejecutar los ejemplos use el nombre del archivo resultante al compilar sin tener en cuenta la extención (`.c`). Por ejemplo, si el archivo se llama `ejemplo.c`, para ejecutar el archivo generado por el makefile use el siguiente comando comando:

```bash
./ejemplo
```

## Referencias

* https://skills.microchip.com/page/c-programming
* https://skills.microchip.com/fundamentals-of-the-c-programming-language-part-i
* https://skills.microchip.com/fundamentals-of-the-c-programming-language-part-ii
* https://skills.microchip.com/fundamentals-of-the-c-programming-language-part-iii

