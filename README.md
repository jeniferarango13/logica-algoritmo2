# logica-algoritmo2
segundo ejercicio clase 30/01
let contador;
const number =[];

function getNumber() {
    for (contador = 0; contador <3; contador++) {
        NUMBER.push(prompt("Ingresa un numero"));
    }
    console.log(NUMBER)
}

function compareNumber() {
    if (NUMBER[0]) === NUMBER[1] && NUMBER[0] === NUMBER[2] && NUMBER[1] === NUMBER[2]) {
        document.write(`sus numeros ${NUMBER} : son iguales`)

    } else {
        document.write(`orden ascendente de sus numeros:  ${(NUMBER.sort((a, b) => a - b))}`);
        document.write(`orden desendente de sus numeros:  ${(NUMBER.sort((a, b) => b - a))}`);
    }
}

getNumber();
compareNumber();
