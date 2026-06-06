<p align="center"> <img src="https://github.com/user-attachments/assets/e31fc7f7-2b96-4b31-a44c-2be1b9b6ead9" width=400px> </p>

# Imports

Importa cosas de otros archivos o librerías.

> import React, { useEffect, useState, useCallback } from 'react';

# useState

Permite guardar datos que cambian.

# useEffect

Permite ejecutar código cuando ocurre algo.

# useCallBack

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



### IMPORTANTE

> const [cart, setCart] = useState([]);

En los estados no se puede hacer:
> cart.push(product);
o
> cart = nuevoArray;

Siempre setCart(nuevoArray);



