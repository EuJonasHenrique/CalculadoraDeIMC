# CalculadoraDeIMC
/*
  IMC adultos condições:
  
  - Abaixo de 18.5 Abaixo do Peso;
  - Entre 18.5 e 25 Peso Normal;
  - Entre 25 e 30 Acima do Peso;
  - Entre 30 e 40 Obeso;
  - Acima de 40 Obesidade Grave;
*/
const peso = 25;
const altura = 1.75;
const imc = peso / (Math.pow (altura,2));

console.log(imc);

if (imc < 18.5) {
    console.log('abaixo do peso');
} 
else if (imc >= 18.5 && imc <= 25) {
    console.log('Peso Normal');
} else if (imc >= 25 && imc <= 30) {
    console.log('Acima do Peso');
} else if (imc >= 30 && imc <= 40) {
    console.log('Obeso');
} else {
    console.log('Obesidade Grave');
}
