# Curso ONE LP Function and Lists
## Interagindo com HTML
### Desafio 3

1. Crie uma função que calcule o índice de massa corporal (IMC) de uma pessoa, a partir de sua altura, em metros, e peso, em quilogramas, que serão recebidos como parâmetro.
```ruby
function calcularIMC(altura, peso) {
    let imc = peso / (altura * altura);
    return imc;
  }
```
2. Crie uma função que calcule o valor do fatorial de um número passado como parâmetro.
```ruby
function fatorial(n){
   
    if (n == 0 || n == 1){
        return 1;
    } 

    for(let i = n - 1; i >= 1; i--){
        n *= i;
    }
    return n;
}
let n = 5;
let resultado = fatorial(n);
console.log(`O fatorial de ${n} é ${resultado}`);
```
3. Crie uma função que converte um valor em dólar, passado como parâmetro, e retorna o valor equivalente em reais. Para isso, considere a cotação do dólar igual a R$4,80.
```ruby
function conversaoDolar(valorDolar) {
    let valorReal = valorDolar * 4.80;
    return valorReal;
}
```
4. Crie uma função que mostre na tela a área e o perímetro de uma sala retangular, utilizando altura e largura que serão dadas como parâmetro.
```ruby
function areaPerimetro(largura, altura) {
    let area = largura * altura;
    let perimetro = largura * 2 + altura * 2;
   console.log(`A area da sala é ${area} e o perimetro é ${perimetro}`);
}
```
5. Crie uma função que mostre na tela a área e o perímetro de uma sala circular, utilizando seu raio que será fornecido como parâmetro. Considere Pi = 3,14.
```ruby
function areaPerimetro(raio) {
    let area = Math.PI * raio ** 2;
    let perimetro = 2 * Math.PI * raio;
    console.log(`A área da circunferência é ${area.toFixed(2)} e o perímetro é ${perimetro.toFixed(2)}`);
}
```
6. Crie uma função que mostre na tela a tabuada de um número dado como parâmetro.
```ruby
function tabuada(numero) {
    for (let i = 1; i <= 10; i++) {
        let resultado = numero * i;
        console.log(`${numero} x ${i} = ${resultado}`);
    
    }
}
let numero = 5;
tabuada(numero);
```
