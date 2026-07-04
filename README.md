# Repositorio de Práctica para JS

Colección de ejercicios de práctica en JavaScript, organizados por diapositiva/clase, enfocados en manipulación de arreglos, objetos y strings.

## Contenido

### Diapositiva 01

| Archivo | Descripción |
| --- | --- |
| [`Ejercicio1.js`](Diapositiva%2001/Ejercicio1.js) | Ordena un arreglo de números de menor a mayor con `sort`. |
| [`Ejercicio2.js`](Diapositiva%2001/Ejercicio2.js) | Invierte un arreglo manualmente, sin usar `.reverse()`. |
| [`Ejercicio3.js`](Diapositiva%2001/Ejercicio3.js) | Elimina duplicados de un arreglo sin usar `Set`. |
| [`Ejercicio4.js`](Diapositiva%2001/Ejercicio4.js) | Encuentra el número mayor y menor de un arreglo sin `Math.max`/`Math.min`. |
| [`Ejercicio5.js`](Diapositiva%2001/Ejercicio5.js) | Determina si una frase es palíndromo. |

### Diapositiva 02

| Archivo | Descripción |
| --- | --- |
| [`Ejercicio1.js`](Diapositiva%2002/Ejercicio1.js) | Encuentra el segundo número más grande de un arreglo sin usar `sort`. |
| [`Ejercicio2.js`](Diapositiva%2002/Ejercicio2.js) | Convierte un string con formato `clave: valor` en un objeto. |
| [`Ejercicio3.js`](Diapositiva%2002/Ejercicio3.js) | Filtra los valores "falsy" de un arreglo. |
| [`Ejercicio4.js`](Diapositiva%2002/Ejercicio4.js) | Filtra usuarios mayores o iguales a 18 años. |

## Requisitos

- [Node.js](https://nodejs.org/)

## Uso

Cada archivo es independiente y se ejecuta directamente, por ejemplo:

```bash
node "Diapositiva 01/Ejercicio1.js"
```

## Problema conocido

`Diapositiva 01/Ejercicio4.js` usa las variables `mayor` y `menor` dentro del bucle, pero solo declara `max` y `min` — esto lanza un `ReferenceError` al ejecutarlo. Hay que renombrar `max`/`min` a `mayor`/`menor` (o viceversa) para que el script corra correctamente.

## Autor

**Kaleb Torres**
