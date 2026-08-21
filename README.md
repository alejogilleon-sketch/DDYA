# DDYA

#Semana 1 
# Prueba Técnica - Semana 1

## Introducción

Durante la primera semana del curso se realizó la presentación de los objetivos, la metodología de trabajo y las herramientas que se utilizarán durante el semestre. Se explicó el uso de Git y GitHub para el control de versiones y la entrega de actividades. Además, se desarrolló una prueba técnica en Python con el propósito de evaluar los conocimientos iniciales en programación y fortalecer las buenas prácticas de desarrollo.

## Actividades realizadas

- Creación del repositorio en GitHub.
- Configuración del entorno de trabajo.
- Desarrollo de la prueba técnica en Python.
- Implementación de funciones para resolver los ejercicios propuestos.
- Verificación y corrección de errores durante las pruebas.
- Organización del código y documentación del proyecto mediante un archivo `README.md`.

## Tecnologías utilizadas

- Python 3
- Git
- GitHub

## Resultado

Se completó satisfactoriamente la prueba técnica, implementando cada uno de los ejercicios solicitados y almacenando el proyecto en un repositorio de GitHub, aplicando buenas prácticas de organización y control de versiones.

# Laboratorio Semana 2

## Introducción

Durante la segunda semana del curso se trabajó el algoritmo de ordenamiento **Insertion Sort**, aplicándolo a un problema relacionado con la organización de precios de productos de una tienda.

## Ejercicio: Organización de precios en una tienda

Se desarrolló un programa que permite al usuario ingresar la cantidad de productos y registrar el precio de cada uno. Posteriormente, el programa permite seleccionar el tipo de ordenamiento que se desea realizar.

## Punto 1. Orden ascendente

Se implementó el ordenamiento de los precios de menor a mayor, con el objetivo de mostrar primero los productos más económicos.

## Punto 2. Orden descendente

Se implementó el ordenamiento de los precios de mayor a menor, con el objetivo de mostrar primero los productos más costosos.

## Algoritmo utilizado

Para organizar los precios se utilizó el algoritmo **Insertion Sort**, implementando tanto el ordenamiento ascendente como el descendente.

## Tecnologías utilizadas

- Python
- Git
- GitHub

## Resultado

Se desarrolló un programa capaz de recibir una cantidad variable de precios y organizarlos mediante el algoritmo **Insertion Sort**, permitiendo mostrar los resultados en orden ascendente o descendente.

## Entrega

El ejercicio se encuentra en la carpeta correspondiente a la **Semana 2** del repositorio de GitHub.

La entrega se realizó mediante un **Pull Request (PR)** con dos revisores.

# Laboratorio Semana 2

## Introducción

Durante la segunda semana del curso se trabajó el algoritmo de ordenamiento **Insertion Sort**, aplicándolo a un problema relacionado con la organización de precios de productos de una tienda.

## Ejercicio: Organización de precios en una tienda

Se desarrolló un programa que permite al usuario ingresar la cantidad de productos y registrar el precio de cada uno. Posteriormente, el programa permite seleccionar el tipo de ordenamiento que se desea realizar.

## Punto 1. Orden ascendente

Se implementó el ordenamiento de los precios de menor a mayor, con el objetivo de mostrar primero los productos más económicos.

## Punto 2. Orden descendente

Se implementó el ordenamiento de los precios de mayor a menor, con el objetivo de mostrar primero los productos más costosos.

## Algoritmo utilizado

Para organizar los precios se utilizó el algoritmo **Insertion Sort**, implementando tanto el ordenamiento ascendente como el descendente.

## Tecnologías utilizadas

- Python
- Git
- GitHub

## Resultado

Se desarrolló un programa capaz de recibir una cantidad variable de precios y organizarlos mediante el algoritmo **Insertion Sort**, permitiendo mostrar los resultados en orden ascendente o descendente.

## Entrega

El ejercicio se encuentra en la carpeta correspondiente a la **Semana 2** del repositorio de GitHub.

La entrega se realizó mediante un **Pull Request (PR)** con dos revisores.

# Semana 3 – Merge Sort y Búsqueda Binaria

## Descripción

Durante la Semana 3 se desarrolló un ejercicio relacionado con la **organización y búsqueda de productos en una tienda**.

El programa permite registrar una cantidad `n` de productos mediante sus códigos numéricos, ordenar dichos códigos utilizando **Merge Sort** y posteriormente buscar un código específico mediante **Búsqueda Binaria**.

## Objetivos

* Registrar una cantidad `n` de productos.
* Almacenar los códigos numéricos de los productos.
* Ordenar los códigos de menor a mayor utilizando **Merge Sort**.
* Buscar un código específico utilizando **Búsqueda Binaria**.
* Mostrar si el producto fue encontrado o no.

## Merge Sort

**Merge Sort** es un algoritmo de ordenamiento que utiliza la estrategia de **Divide y Conquista**.

Su funcionamiento consiste en:

1. **Dividir:** separar la lista en dos partes.
2. **Conquistar:** ordenar cada mitad de forma recursiva.
3. **Combinar:** unir las mitades ordenadas.

Su complejidad temporal es:

**O(n log n)**

## Búsqueda Binaria

La **Búsqueda Binaria** permite encontrar un elemento dentro de una lista que previamente debe estar ordenada.

El algoritmo compara el elemento buscado con el elemento central:

* Si son iguales, el elemento fue encontrado.
* Si el elemento buscado es menor, se busca en la mitad izquierda.
* Si el elemento buscado es mayor, se busca en la mitad derecha.

Su complejidad temporal es:

**O(log n)**

## Ejemplo

El usuario registra 6 productos:

```text
Ingrese la cantidad de productos: 6
Ingrese el código del producto 1: 105
Ingrese el código del producto 2: 32
Ingrese el código del producto 3: 78
Ingrese el código del producto 4: 15
Ingrese el código del producto 5: 120
Ingrese el código del producto 6: 50
```

Lista original:

```text
[105, 32, 78, 15, 120, 50]
```

Después de aplicar Merge Sort:

```text
[15, 32, 50, 78, 105, 120]
```

Luego se realiza la búsqueda:

```text
Ingrese el código que desea buscar: 78
```

Resultado:

```text
El producto con código 78 fue encontrado.
```

Si se busca un código que no existe:

```text
Ingrese el código que desea buscar: 90
```

Resultado:

```text
El producto con código 90 no se encuentra registrado.
```

## Complejidad

| Algoritmo        | Complejidad |
| ---------------- | ----------- |
| Merge Sort       | O(n log n)  |
| Búsqueda Binaria | O(log n)    |

## Conclusión

En este ejercicio se aplicaron los algoritmos **Merge Sort** y **Búsqueda Binaria** para solucionar un problema de organización y búsqueda de productos.

Se aplicó la estrategia de **Divide y Conquista** para ordenar los datos y posteriormente aprovechar el orden obtenido para realizar búsquedas de manera eficiente.


## Autor

**Emmanuel Alejandro Gil León**

**Ingeniería de Sistemas**  
**Escuela Colombiana de Ingeniería Julio Garavito**
