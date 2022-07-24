- **1_Print special numbers exercise.**
  - En este ejercicio debes usar un control de flujo iterativo para poder imprimir todos los números pares en el rango  de números del 0 al 100. Recuerda que no debes imprimir cada número, debes usar una estructura de control de flujo  para realizar el ejercicio
   
  - ```js
    for(let i=0 ;i<= 100;i++){
    if(i % 2==0){
    console.log (i);}
    }

- **2_Bad Code exercise.**
- El código que se muestra a continuación no está funcionando de la manera correcta, como tarea debes encontrar el error que cometió el desarrollador que programó este código y corregirlo, para este ejercicio debes explicar cuál es el error y colocar el código correcto
```js
  var cond = false;

  if ((cond = true)) {
    console.log('The cond variable is true');
  } else {
   console.log('The cond variable is false');
  }
```
- el error está en que en la sentencia if  se le está asignando otro valor a la variable cond y no se lo está comparando,una solución podría ser esta:
```js
  var cond = false;

  if ((cond == true)) {
    console.log('The cond variable is true');
  } else {
   console.log('The cond variable is false');
  }
```

- **3_Bad Code 2 exercise.**
 - Debes crear el código que sigue la siguiente lógica, si el número dado es 100, toma este número como especial y muestra el siguiente mensaje: "¡Este es un número especial!", pero si el número es menor que 1000, múltiplo de 10 y diferente de 100, debe mostrar el siguiente mensaje: "Este número es casi especial". si no se cumple ninguna de las condiciones dadas mostrar el siguiente mensaje: "Sólo un número regular". Otro desarrollador estaba tratando de programar la lógica, pero aparentemente no pudo, necesita corregir el código para que funcione correctamente.
 ```js
  var n = 100;

if (n == 100) {
  console.log('This is a special number!');
}
if (n < 1000) {
  console.log('');
} else {
  console.log('Just a regular number');
}
if (n % 10 == 0) {
  console.log('This number is multiple of 10');
}
```
- solución:

```js
 var n = 100;

if (n == 100) {
  console.log('This is a special number!');
}else if (n < 1000 && n % 10 == 0 && n != 100) {
  console.log('This number is almost special');
} else {
  console.log('Just a regular number');
}
```
- **4_Follow Git Course**
