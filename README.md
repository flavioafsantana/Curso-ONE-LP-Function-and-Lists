# Curso ONE LP Function and Lists
## Interagindo com HTML
### Desafio 1

Altere o conteúdo da tag h1 com document.querySelector e atribua o seguinte texto: Hora do Desafio.
```ruby
let titulo = document.querySelector('h1');
titulo.innerHTML = 'Hora do Desafio';
```
Crie uma função que exiba no console a mensagem O botão foi clicado sempre que o botão Console for pressionado.
#### Adicionamos essa linha no codigo HTML
```ruby
<button onclick="consoleClick()" class="button">Console</button>
```
#### E criamos a função no js
```ruby
function consoleClick() {
    console.log('O botão foi clicado');
}
```
Crie uma função que exiba um alerta com a mensagem: Eu amo JS, sempre que o botão Alerta for pressionado.
#### Adicionamos essa linha no codigo HTML
```ruby
<button onclick="alertClick()" class="button">Alert</button>
```
#### E criamos a função no js
```ruby
function alertClick() {
    alert('Eu amo JS');
}
```
Crie uma função que é executada quando o botão prompt é clicado, perguntando o nome de uma cidade do Brasil. Em seguida, exiba um alerta com a mensagem concatenando a resposta com o texto: Estive em {cidade} e lembrei de você.
#### Adicionamos essa linha no codigo HTML
```ruby
<button onclick="promptClick()" class="button">Prompt</button>
```
#### E criamos a função no js
```ruby
function promptClick() {
    let cidade = prompt('Qual a sua cidade?');
    alert('Estive em ' + cidade + ' e lembrei de você.');
}
```
Ao clicar no botão soma, peça 2 números inteiros e exiba o resultado da soma em um alerta.
#### Adicionamos essa linha no codigo HTML
```ruby
<button onclick="somaClick()" class="button">Soma</button>
```
#### E criamos a função no js
```ruby
function somaClick() {
    let n1 = prompt('Digite um número');
    let n2 = prompt('Digite outro número');
    let resultado = Number(n1) + Number(n2);
    alert(`${n1} + ${n2} = ${resultado}`);
}
```
