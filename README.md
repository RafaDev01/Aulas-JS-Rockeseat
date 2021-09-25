# Aulas JS Rockeseat
 Aulas JS Rockeseat

Conforme o ECMAScript standard temos 9 tipos de dados:

*Data types
  *Primitive / Primitive value
  *Structural
  *Structural Primitive

## Primitivos

*String
*Number
*Boolean
*undefined
*Symbol
*BigInt

## Estruturais

*Object
  *Array
  *Map
  *Set
  *Date
  *...
*Function

## Primitivo Estruturtal / Structural Root Primiteve

*null

## Variaveis

*Nomes simbolicos para receber algum valor
*Atalhos de código
*Identificadores
*3 palavras reservadas para criar uma variavel
  *var
  *let
  *const

-> O JS é uma linguagem francamente tipada e dinâmica

- Variáveis não precisam ter um tipo previamente definido
- Podemos mudar o conteúdo da variavel

# Scope

* Escopo determina a visibilidade de alguma variável no JS

# Block statement 
```js
// vamos iniciar um bloco
{
    // aqui dentro é um bloco e posso colocar qualquer código
    //aqui fechamos o bloco
}
```

-> O bloco também criará um novo escopo. Chamamos de `block-scoped`

## var
```js
// var é global e poderá funcionar fora de escopo de bloco
console.log('> exites x antes do bloco?', x)

{
  var x = 0
}

console.log('> existe x depois do bloco?', x)

``` 

## let e const
```js
// const e let são locais e só funcionam no escopo onde foi criada
console.log('> existe y antes do bloco?', y)

{
  let y = 0
}

console.log('> existe y depois do bloco?', y)
```

## Para criar nomes

*JS é case-sensitive (sensível ao caso)
*JS aceita a cadeia de caracteres Unicode

-Posso: 
  *Iniciar com esses caracteres especiais: $ _
  *Iniciar com letras
  *Colocar acentos
  *Letras maíusculas e minúsculas fazem diferença

-Não posso:
  *Iniciar com números
  *Colocar espaços vazios no nome

-Ideal 
  *Criar nomes que fazem sentido
  *Que explique o que a variável é ou faz
  *camelCase
  *Snake_case
  *Escrever em inglês

