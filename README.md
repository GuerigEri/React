<p align="center"> <img src="https://github.com/user-attachments/assets/e31fc7f7-2b96-4b31-a44c-2be1b9b6ead9" width=400px> </p>

# Link documentación

https://www.reactjs.wiki/

# SUBIR PROYECTO A LA RED

Para crear una versión optimizada para producción de tu aplicación:

``npm run build``

Esto nos devuelve una carpeta dist, eso es lo que hay que subir al hostinger que usemos.
Si tenemos una bbdd también habría que subir la carpeta api.

También hay que cambiar las rutas de las imagenes y quitar el /public a las que lo tengan.


# Imports

Importa cosas de otros archivos o librerías.

> import React, { useEffect, useState, useCallback } from 'react';

#Hooks

## useState

Permite guardar datos que cambian. De forma que el usuario puede ver como sus acciones en la web tienen cambios en tiempo real.

### batching
Buena practica: suponiendo que estoy ejecutando una lógica que hace un cambio de estado, si se ejecutan varios cambios de estado al mismo tiempo, se agrupan y se ejecutan al final. Es decir, el cambio del render se hace cuando se ejecuta todo.

## useEffect

Permite ejecutar código cuando ocurre algo.

### Ejemplos

> useEffect(() => {
> }, [algo]);
Es como decir: cuando cambie "algo" -> "Ejecuta este código"

## useCallBack

Sirve para memorizar funciones

# Link 

Sirve para navegar

# useNavigate

Permite navegar desde JavaScript

# Modal

Es un componente propio.

> import Modal from './Modal';

Se usa:
> <Modal />

# const

Una constante es una variable cuyo valor no puede ser reasignado después de crearse.

>  const [cart, setCart] = useState([]);

Cuando se llama a setCart() no se esta cambiando la constante, sino que se le esta dichiendo a react:
"Guarda este nuevo valor como estado y vuelve a ejecutar el componente."

# some()

Se usa para comprobar si al menos un elemento de un array cumple una condición.

# AbortController()

El AbortController es una api de js que sirve para cancelar operaciones asincronas, especialmente peticiones con fetch.

# localStorage
Solo guarda strings.

# Map()

Un Map es una estructura de datos que almacena pares clave -> valor, parecida a un objeto({}), pero con algunas ventajas.

```
map.set(clave, valor);   // Añadir o actualizar
map.get(clave);          // Obtener valor
map.has(clave);          // Comprobar si existe
map.delete(clave);       // Eliminar
map.clear();             // Vaciar todo

```

### IMPORTANTE

> const [cart, setCart] = useState([]);

En los estados no se puede hacer:
> cart.push(product);

o

> cart = nuevoArray;

Siempre setCart(nuevoArray);

---

Se puede interrumpir un endpoint.






















































