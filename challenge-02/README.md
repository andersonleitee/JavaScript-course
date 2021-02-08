# Desafio da semana #2

Nesse exercício, você está livre para escolher os nomes para suas variáveis e funções! :smile:

```js
// Crie uma função que receba dois argumentos e retorne a soma dos mesmos.
> function soma(a,b){
    var t2 = a + b;
    return t2;
    }

// Declare uma variável que receba a invocação da função criada acima, passando dois números quaisquer por argumento, e somando `5` ao resultado retornado da função.
var sum = soma(5+10) + 5;

// Qual o valor atualizado dessa variável?
20

// Declare uma nova variável, sem valor.
var teste = 0;

/*
Crie uma função que adicione um valor à variável criada acima, e retorne a string:
    O valor da variável agora é VALOR.
Onde VALOR é o novo valor da variável.
*/
function funcao(){
    teste = 10;
    return 'O valor da variável agora é ' + teste;
} 

// Invoque a função criada acima.
funcao(2);

// Qual o retorno da função? (Use comentários de bloco).
2

/*
Crie uma função com as seguintes características:
1. A função deve receber 3 argumentos;
2. Se qualquer um dos três argumentos não estiverem preenchidos, a função deve retornar a string:
    Preencha todos os valores corretamente!
3. O retorno da função deve ser a multiplicação dos 3 argumentos, somando `2` ao resultado da multiplicação.
*/

function teste(a,b,c){
    if ( a === undefined || b === undefined || c === undefined){
        console.log("Preencha todos os dados corretamente!");
        } else {
        var t1 = (a*b*c) + 2;
        } 
        return t1;
     }



// Invoque a função criada acima, passando só dois números como argumento.

teste(1,2);

// Qual o resultado da invocação acima? (Use comentários para mostrar o valor retornado).

//Preencha todos os dados corretamente!

// Agora invoque novamente a função criada acima, mas passando todos os três argumentos necessários.
teste(1,2,3);

// Qual o resultado da invocação acima? (Use comentários para mostrar o valor retornado).

// 8

/*
Crie uma função com as seguintes características:
1. A função deve receber 3 argumentos.
2. Se somente um argumento for passado, retorne o valor do argumento.
3. Se dois argumentos forem passados, retorne a soma dos dois argumentos.
4. Se todos os argumentos forem passados, retorne a soma do primeiro com o segundo, e o resultado, dividido pelo terceiro.
5. Se nenhum argumento for passado, retorne o valor booleano `false`.
6. E ainda, se nenhuma das condições acima forem atendidas, retorne `null`.
*/

 function funcao(a,b,c){
        if(a !== undefined && b === undefined && c === undefined){
        return a;
        } else if (a !== undefined && b !== undefined && c === undefined){
        var soma = (a+b);
        return soma;
        } else if (a !== undefined && b !== undefined && c !== undefined){
        var soma = (a+b);
        return soma/c;
        } else if (a === undefined && b === undefined && c === undefined){
        return 'false';
        } else {
        return 'null';
        }
    }

// Invoque a função acima utilizando todas as possibilidades (com nenhum argumento, com um, com dois e com três.) Coloque um comentário de linha ao lado da função com o resultado de cada invocação.

// funcao()
// 'false'
// 
// funcao(1,2)
// 3
// 
// funcao(1,2,3)
// 1
// 
// funcao(1)
// 1








