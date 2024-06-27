# Curso ONE LP Function and Lists
## Interagindo com HTML
### Desafio 1

```ruby
let titulo = document.querySelector('h1');
titulo.innerHTML = 'Hora do Desafio';

function consoleClick() {
    console.log('O botão foi clicado');
}

function alertClick() {
    alert('Eu amo JS');
}

function promptClick() {
    let cidade = prompt('Qual a sua cidade?');
    alert('Estive em ' + cidade + ' e lembrei de você.');
}

function somaClick() {
    let n1 = prompt('Digite um número');
    let n2 = prompt('Digite outro número');
    let resultado = Number(n1) + Number(n2);
    alert('A soma dos números é ' + resultado);
}
```
