## Linguagem de programação

Maneira de dar instrução ao computador.
Como um lego, você irá utilizar peças para criar algoritmos, ou seja, para resolver problemas.

**Algoritmo**: Sequência de passos lógicos e finita para resolução de um problema.


## Peças de uma linguagem

- Comentários
- Declaração de váriaveis (const,, let)
- Operadores (atribuição, concatenação, matemática, lógicos )
- Tipos de dados (string, number, boolean)
- Estruturas de dados (fucnctions, object, array)
- Controle de fluxo (if/else)
- Estrutura de repetição (for, while)

# Fases da resolução de um problema

Coletar os dados
Processar os dados (manipular, alterar ...)
Apresentar os dados

## Escopo e variáveis:
Variáveis globais e locais
Constantes

## Tipos de dados

Strings (textos): ""   ''  ``
- [x] number 2  1.4
- [x] Boolean: true, false



## Operadores
- [x] Operadores de atribuição de valor
- [x] Operador de contatenação: +
- [x] Operadores de comparação: ==  !=   <=  >=  < > 
- [x] Spread operator: ...

## Estruturas de dados

### Arrays:

- [x] Uma lista que contem qualquer tipo de dados
- [x] Métodos de array: push, [find, forEach, filter] : HOF (Higher Oder Functions)


### Objetos

- [x] Atributos e métodos
- [x] Criação e manipulação de objetos
- [x] Acesso a propriedades de objetos


### Functions

- [x] criar, passar argumento
- [x] execultar
- [x] arrow function / named function


# Estrutura de repetição

- [x] while

# Condicionais 

- [x] switch
- [x] if/else


## Módulos em Node.js:

- [x] Importação de módulos (require, CommonJS)
- [x] Biblioteca 'inquirer' para criar prompts interativos
- [x] FS (file system)


## JSON

- [x] Javascript Object Notation (.json)
- [x] JSON.parse() transforma de JSON para JS
- [x] JSON.stringify() transforma de JS para JSON


## Programação assíncrona e Promises:

- [x] Uso de funções assícronas (async/await)







### Já desenvolvido no curso

let meta = {
    value: 'Ler um livro por mês.',
    checked: true,
}

let metas = [
    meta,
    {
        value: "Caminhar 20 minutos todos os dias.",
        checked: false
    }
]
console.log(meta.value)
console.log(metas[1].value)




/* Assunto: hello word
let mensagem = "hello world"
console.log(mensagem) */

/* Assunto: Array

let metas = ["Marcelo", "Alô"]
console.log(metas[1] + ", " + metas[0])
*/

/* Assunto: Objetos

let meta = {
    value: "Ler um livro por mês",
    checked: false
}
console.log(meta.value)
*/

/* Assunto: function 
//function
funcion criarMeta() {}


// arrow funcion
const criarMeta = () => {}
*/


/*Observação: Método é o mesmo que função, porém ele tem os nomes diferentes 
a diferença é que o método está dentro de um objeto e a função está fora de um objeto */

/* function start(){     Aqui função normal e abaixo é uma arrow function

const start = () =>{ 
    console.log("Começou")
}
start()
 */

 /* Abaixo é um contador de 1 a 10

const start = () =>{ 
    let count = 1
    while(count <= 10) {
        console.log(count)
        count = count + 1
    }
}
start()
*/