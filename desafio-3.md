Resolución de los desafíos del curso de lógica de programación
Practicar la lógica de programación, que incluye conceptos como variables, condicionales (if-else), bucles (while) e interacciones con el usuario (alert, prompt), es esencial para tu carrera en el desarrollo de software. Estos fundamentos proporcionan la base para resolver problemas de manera estructurada, tomar decisiones en el código, crear iteraciones controladas e interactuar eficazmente con los usuarios.

Comprender estos conceptos no solo facilita el aprendizaje de nuevos lenguajes y tecnologías, sino que también te capacita para crear soluciones innovadoras, depurar de manera eficiente y mantener la calidad a lo largo del ciclo de vida del software. Por lo tanto, invertir tiempo en estos principios desde el principio es fundamental para construir una base sólida y exitosa en el campo de la programación.

Desafíos - Respuestas


//Lógica de programación `
//03. Loops y tentativas
//DESAFIO: Hora de Practicar


//ACTIVIDAD 1: Crea un contador que comience en 1 y vaya hasta 10 usando un bucle 'while'. Muestra cada número.

```javascript
//Variables
let contador = 1;

while(contador <= 10){
    console.log(`Número: ${contador}`);
    contador += 1;  //contador = contador +1 // contador ++
}
```



//ACTIVIDAD 2: Crea un contador que comience en 10 y vaya hasta 0 usando un bucle 'while'. Muestra cada número.

```javascript
//Variables
let contador = 10;

while(contador >= 0){
    console.log(`Número: ${contador}`);
    contador --;  //contador = contador -1
}
```



//ACTIVIDAD 3: Crea un programa de cuenta regresiva. Pide un número y cuenta desde 0 hasta ese número utilizando un bucle 'while' en la consola del navegador.

```javascript
//Variables
let numeroMax = prompt('Por favor ingresa un numero para hacer cuenta regresiva');

while(numeroMax >= 0){
    console.log(`Número: ${numeroMax}`);
    numeroMax --;  //numeroMax = numeroMax +1
}
```





//ACTIVIDAD 4:Crea un programa de cuenta progresiva. Pide un número y cuenta desde 0 hasta ese número utilizando un bucle 'while' en la consola del navegador.

```javascript
//Variables
let numeroMax = prompt('Por favor ingresa un numero para hacer cuenta progresiva');
let contador = 0;

while(contador <= numeroMax){
    console.log(`Número: ${contador}`);
    contador += 1;  //contador = contador +1 // contador ++
}
```




//OPERADORES LOGICOS

//AND (&&)

```javascript
let edad = 25;
let tieneLicencia = true;

// si la edad es mayor de 18 y tiene una licencia...
if (edad > 18 && tieneLicencia) {
  console.log("Puede conducir!");
} else {
  console.log("No puede conducir!");
}
```

```javascript
//OR( | | )
// si tiene manzana o tiene banana…
if (tieneManzana|| tieneBanana) {
    console.log("Tienes frutas!");
  } else {
    console.log("No tienes frutas.");
  }
```

