# conversiones

- Metros a kilómetros: dividir entre 1000
- Metros a centímetros: multiplicar por 100
- Gramos a kilogramos: dividir por 1000
- Gramos a miligramos: multiplicar por 1000
- Minutos a horas: dividir por 60
- Minutos a segundos: multiplicar por 60
- Litros a kilolitros: dividir por 1000
- Litros a mililitros: multiplicar por 1000

Ver si un valor es un número válido (hay que usar el punto como separador de decimales)

const valor = document.getElementById("metros").value
if(parseFloat(valor) == valor) {
    console.log("si");
} else {
    console.log("no");
}
