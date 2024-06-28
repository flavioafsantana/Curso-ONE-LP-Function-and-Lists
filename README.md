# Curso ONE LP Function and Lists
## Interagindo com HTML
### Desafio 2

1. Criar uma função que exibe "Olá, mundo!" no console.
```ruby
function olaMundo() {
    console.log("Olá, mundo!");
}
olaMundo();
```
2. Criar uma função que recebe um nome como parâmetro e exibe "Olá, [nome]!" no console.
```ruby
function olaNome(nome) {
    console.log(`Olá, ${nome}!`);
}
olaNome('Flavio');
```
3. Criar uma função que recebe um número como parâmetro e retorna o dobro desse número.
```ruby
function dobreONumero(numero){
    return numero * 2;
}
let resultado = dobreONumero(3);
console.log(resultado)
```
4. Criar uma função que recebe três números como parâmetros e retorna a média deles.
```ruby
function calcularMedia(numero1,numero2,numero3){
    return (numero1 + numero2 + numero3) / 3;
}
let media = calcularMedia(4, 7, 10);
console.log(media);
```
5. Criar uma função que recebe dois números como parâmetros e retorna o maior deles.
```ruby
function numeroMaior(numero1,numero2){
   return a > b ? a : b;
}
let maiorNumero = numeroMaior(11,7);
console.log(maiorNumero);
```
6. Criar uma função que recebe um número como parâmetro e retorna o resultado da multiplicação desse número por ele mesmo
```ruby
function quadrado(numero1){
    return numero1 * numero1;
}
let resultado = quadrado(6)
console.log(resultado);
```

