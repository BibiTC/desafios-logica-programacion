# Resolución de los desafíos del curso de lógica de programación <h1>

Practicar la lógica de programación, incluyendo conceptos como variables, condiciones (if-else), bucles (while) e interacciones con el usuario (alert, prompt), es esencial para tu carrera en el desarrollo de software. Estos fundamentos son la base para abordar problemas de manera estructurada, tomar decisiones sin código, crear bucles controlados e interactuar de manera efectiva con los usuarios.

Comprender estos conceptos no solo facilita el aprendizaje de nuevos lenguajes y tecnologías, sino que también te capacita para crear soluciones innovadoras, depurar de manera eficiente y mantener la calidad a lo largo del ciclo de vida del software. Por lo tanto, invertir tiempo en estos principios desde temprano es fundamental para construir una base sólida y exitosa en el campo de la programación.

## Desafíos - Respuestas <h2>

/Ejercicio 1: Sala de Espera de MediaRecorder, juego de adivinar el numero
//Lógica de programmación
//02. Condiciones y concatenación
//DESAFIO : Sala de Espera de MediaRecorder, juego de adivinar el numero
```javascript  
alert('Bienvenido al juego del número secreto');
```
// Agrega un console.log para verificar el valor de "intento" después de la entrada del usuario
let intento = prompt('Elige un número entre 1 y 10');
console.log('Valor de intento:', intento);
```javascript 
let numeroSecreto = 8;
```
// Agrega un console.log para verificar la comparación entre "intento" y "numeroSecreto"
console.log('Resultado de la comparación:', intento == numeroSecreto);
//console.log( `Resultado de la comparación: ${intento == numeroSecreto} `); // Tambien funciona pero el true o false queda sin reslatar en el log
```javascript
if (intento == numeroSecreto) {
    alert('Adivinaste');
} else {
    // Agrega un console.log para verificar el valor de "numeroSecreto" cuando el jugador se equivoca
    console.log('Valor del número secreto:', numeroSecreto);
 }
```


/Ejercicio 2: Pregunta al usuario qué día de la semana es. Si la respuesta es "Sábado" o "Domingo", muestra "¡Buen fin de semana!". De lo contrario, muestra "¡Buena semana!".

//Lógica de programmación
//02. Condiciones y concatenación
//DESAFIO 1: Pregunta al usuario qué día de la semana es. Si la respuesta es "Sábado" o "Domingo", 
//          muestra "¡Buen fin de semana!". De lo contrario, muestra "¡Buena semana!".
```javascript
//Variables
let diaSemana = prompt('Bienvenido, Que dia de la semana es ?');
let diaSabado = 'Sábado'
let diaDomingo = 'Domingo'

// Agrega un console.log para verificar el dia de la semana que ingreso el usuario.
console.log('Dia de la Semana:', diaSemana);

if (diaSemana == diaSabado || diaSemana == diaDomingo) {
    alert('¡Buen fin de semana!');
} else {
    alert('¡Buena semana!');
 }
```


//Lógica de programmación
//02. Condiciones y concatenación
//DESAFIO 2: Verifica si un número ingresado por el usuario es positivo o negativo. Muestra una alerta informativa. 
```javascript
//Variables
let numero = prompt('Ingresa un número positivo o negativo');

// Agrega un console.log para verificar el dia de la semana que ingreso el usuario.
console.log('número:', numero);

if (numero > 0) {
    alert('El número es positivo');
    console.log('El número es positivo');
} else if(numero < 0) {
    alert ('El número es negativo');
    console.log('El número es negativo');
 }else alert ('El número es cero');
       console.log('El número es cero');
```

/Ejercicio 3: Crea un sistema de puntuación para un juego. Si la puntuación es mayor o igual a 100, muestra "¡Felicidades, has ganado!". En caso contrario, muestra "Intentalo nuevamente para ganar.".

//Lógica de programmación
//02. Condiciones y concatenación
//DESAFIO 3: Crea un sistema de puntuación para un juego. 
//           Si la puntuación es mayor o igual a 100, muestra "¡Felicidades, has ganado!". 
//           En caso contrario, muestra "Intentalo nuevamente para ganar.".
```javascript
//Variables
let puntuacion = prompt('Ingresa tu puntuación');

// Agrega un console.log para verificar el dia de la semana que ingreso el usuario.
console.log('puntuación:', puntuacion);

if (puntuacion >= 100) {
    alert('¡Felicidades, has ganado!');
    console.log('¡Felicidades, has ganado!');
} else { 
    alert('Intentalo nuevamente para ganar');
    console.log('Intentalo nuevamente para ganar');
}
```


/Ejercicio 4: Crea un mensaje que informe al usuario sobre el saldo de su cuenta, utilizando un template string para incluir el valor del saldo.

//Lógica de programmación `
//02. Condiciones y concatenación
//DESAFIO 4: Crea un mensaje que informe al usuario sobre el saldo de su cuenta, 
//           utilizando un template string para incluir el valor del saldo.

```javascript
//Variables
let saldoCuentaUsuario = 1000;

alert(`Estimado usuario el Saldo de su Cuenta XXXXX es: ${saldoCuentaUsuario}`);
```

/Ejercicio 5: Pide al usuario que ingrese su nombre mediante un prompt. Luego, muestra una alerta de bienvenida usando ese nombre.

//Lógica de programmación `
//02. Condiciones y concatenación
//DESAFIO 5: Pide al usuario que ingrese su nombre mediante un prompt. 
//           Luego, muestra una alerta de bienvenida usando ese nombre.

```javascript
//Variables
let nombreUsuario = prompt('Por favor, ingrese su nombre');

alert(`Bienvenido(a), ${nombreUsuario}!`);
```
