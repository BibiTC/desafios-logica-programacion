### Resolución de los desafíos del curso de lógica de programación

**Practicar la lógica de programación**, que incluye conceptos como variables, condicionales (if-else), bucles (while) e interacciones con el usuario (alert, prompt), es esencial para tu carrera en el desarrollo de software. Estos fundamentos proporcionan la base para resolver problemas de manera estructurada, tomar decisiones en el código, crear iteraciones controladas e interactuar eficazmente con los usuarios.

Comprender estos conceptos no solo facilita el aprendizaje de nuevos lenguajes y tecnologías, sino que también te capacita para crear soluciones innovadoras, depurar eficientemente y mantener la calidad a lo largo del ciclo de vida del software. Por lo tanto, invertir tiempo en estos principios desde el principio es fundamental para construir una base sólida y exitosa en el campo de la programación.

#### Calentamiento en programación - Respuestas

//Lógica de programación 
//04. Buenas prácticas en programación
//DESAFIO: Hora de Practicar


//ACTIVIDAD 1: Crea un programa que utilice console.log para mostrar un mensaje de bienvenida.

```javascript
console.log('¡Bienvenida y bienvenido a nuestro sitio web!');
```

//ACTIVIDAD 2: Crea una variable llamada "nombre" y asígnale tu nombre. 
//             Luego, utiliza console.log para mostrar el mensaje "¡Hola, [tu nombre]!" en la consola del navegador.

```javascript
let nombre = 'Bibiana Trujillo';

console.log(`¡Hola, ${nombre}!`);
````
//ACTIVIDAD 3: Crea una variable llamada "nombre" y asígnale tu nombre. 
//             Luego, utiliza alert para mostrar el mensaje "¡Hola, [tu nombre]!".

```javascript
let nombre = 'Bibiana Trujillo';

alert(`¡Hola, ${nombre}!`);
```

//ACTIVIDAD 4: Utiliza prompt y haz la siguiente pregunta: ¿Cuál es el lenguaje de programación que más te gusta?. 
//             Luego, almacena la respuesta en una variable y muestra la respuesta en la consola del navegador.

```javascript
let lenguajePrograma = prompt('¿Cuál es el lenguaje de programación que más te gusta?');

console.log(`¡Mi Lenguaje de Programación Preferido es: , ${lenguajePrograma}!`);
```

//ACTIVIDAD 5: Crea una variable llamada "valor1" y otra llamada "valor2", asignándoles valores numéricos de tu elección. 
//             Luego, realiza la suma de estos dos valores y almacena el resultado en una tercera variable llamada "resultado". 
//             Utiliza console.log para mostrar el mensaje "La suma de [valor1] y [valor2] es igual a [resultado]." en la consola.

```javascript
//Variables
let valor1 = 100;
let valor2 = 250;

//Resultado operacion suma
let resulado = valor1 + valor2;

//Mostrar en consola resultado
console.log(`Valor1 : ${typeof(resulado)}, Valor2 : ${typeof(resulado)} , Resultado : ${typeof(resulado)}`);

console.log(`La suma de ${valor1} y ${valor2} es igual a ${resulado}.`);
```

//ACTIVIDAD 6: Crea una variable llamada "valor1" y otra llamada "valor2", asignándoles valores numéricos de tu elección. 
//             Luego, realiza la resta de estos dos valores y almacena el resultado en una tercera variable llamada "resultado". 
//             Utiliza console.log para mostrar el mensaje "La diferencia entre [valor1] y [valor2] es igual a [resultado]." en la consola.

```javascript
//Variables
let valor1 = 500;
let valor2 = 1200;

//Resultado operacion resta
let resulado = valor1 - valor2;

//Mostrar en consola resultado
console.log(`Valor1 : ${typeof(resulado)}, Valor2 : ${typeof(resulado)} , Resultado : ${typeof(resulado)}`);

console.log(`La diferencia entre ${valor1} y ${valor2} es igual a ${resulado}.`);
```

//ACTIVIDAD 7: Pide al usuario que ingrese su edad con prompt. Con base en la edad ingresada, utiliza un if 
//             para verificar si la persona es mayor o menor de edad y muestra un mensaje apropiado en la consola.


```javascript
//Variables
let edad =  prompt('Por favor, ingrese su Edad');

//Valida edad ingresada
if(edad >= 18){
    console.log('Usted es mayor de edad');     
} else {
    console.log('Usted es menor de edad');     

}
```

//ACTIVIDAD 8: Crea una variable "numero" y solicita un valor con prompt. Luego, verifica si es positivo, 
//             negativo o cero utilizando un if-else y muestra el mensaje correspondiente.

```javascript
//Variables
let numero = prompt('Por favor, ingrese un número pósitivo, negativo o cero');

//Validación si el número es positivo, negativo o cero
if( numero > 0 ){
alert(`EL número ${numero} es positivo`);
} else if( numero < 0 ){
    alert(`EL número ${numero} es negativo`);
 } else if( numero == 0 ){
    alert(`EL número ${numero} es cero`);
}
```

//ACTIVIDAD 9: Utiliza un bucle while para mostrar los números del 1 al 10 en la consola.

```javascript
let contador = 1;

console.log('Números de 1 a 10 bucle');

while ( contador <= 10 ){
    console.log(contador);
    contador++;
}
```

//ACTIVIDAD 10: Crea una variable "nota" y asígnale un valor numérico. Utiliza un if-else para determinar 
//              si la nota es mayor o igual a 7 y muestra "Aprobado" o "Reprobado" en la consola.

```javascript
//Variables
let nota = 10;
let notaMinima = 7;

//Valida nota Aprobo (>=7) o Reprobo (<7)
if ( nota >=notaMinima ){
    alert(`Nota [ ${nota} ] , mayor o igual a [ ${notaMinima} ], ustes a sido ¡Aprobado!'`);
}
else {
    alert(`Nota [ ${nota} ]  ,menor a [ ${notaMinima} ], ustes a sido ¡Reaprobado!'`);
}
```

//ACTIVIDAD 11: Utiliza Math.random para generar cualquier número aleatorio y muestra ese número en la consola.

```javascript
//Numero aleatorio
console.log(Math.random());
```

//ACTIVIDAD 12: Utiliza Math.random para generar un número entero entre 1 y 10 y muestra ese número en la consola.

```javascript
//Numero entero random entre 1 y 10
console.log(parseInt(Math.random()*10)+1);
```

//ACTIVIDAD 13: Utiliza Math.random para generar un número entero entre 1 y 1000 y muestra ese número en la consola.

```javascript
console.log(parseInt(Math.random()*1000)+1);
```
