
# Instru��es

Antes de come�ar o exerc�cio, baixe o arquivo *zip* acima. Ele tem toda a configura��o que passamos em aula para relacionar os arquivos `index.html` e `index.js`. 

Para os exerc�cios de hoje, voc� precisa mexer **apenas no arquivo** `index.js`

Os exerc�cios de hoje s�o divididos em interpreta��o e escrita de c�digo. Para os de interpreta��o, coloque as respostas em coment�rios de c�digo. J�, nos de escrita, lembre-se de imprimir no console os resultados.

> **ATEN��O**
> 
> N�o � permitido utilizar estruturas e sintaxes de c�digo ainda n�o ensinadas no curso. Para um melhor aproveitamento para si mesmo, force-se a utilizar s� o que foi passado a voc�s.

---

### Exerc�cios de escrita de c�digo

#### 1. Construa um programa, seguindo os seguintes passos:

a) Declare uma vari�vel para armazenar um nome, sem atribuir um valor.

b) Declare uma vari�vel para armazenar uma idade, sem atribuir um valor.

c) Imprima na tela o tipo dessas vari�veis que acabou de criar, usando o comando `typeof`.

d) Reflita: por que esse tipo foi impresso? Escreva a resposta em um coment�rio de c�digo.

e) Pergunte ao usu�rio seu nome e sua idade, atribuindo esses dois valores �s vari�veis que acabou de criar.

Dica: Se voc� receber um erro de c�digo nessa etapa, reflita sobre o tipo de declara��o que utilizou.

f) Novamente, imprima na tela o tipo dessas vari�veis. O que voc� notou? Escreva em um coment�rio de c�digo.

g) Para finalizar, imprima na tela a mensagem: "Ol� `nome`,  voc� tem `idade` anos". Onde `nome` e `idade` s�o os valores que o usu�rio inseriu.

Dica: Para imprimir mais de um valor na mesma linha, voc� pode usar essa sintaxe: `console.log(valor1, valor2)`.

---

#### 2. Escreva um programa que fa�a 3 perguntas de Sim ou N�o, armazenado em uma vari�vel.

Por exemplo: "Voc� est� usando uma roupa azul hoje?". Depois, siga os passos:
    
a) Crie tr�s novas vari�veis, contendo as respostas.

b) Imprima na tela todas as perguntas seguidas por suas respectivas respostas. Por exemplo:
`Voc� est� usando uma roupa azul hoje? - SIM`

---

#### 3. Suponha que temos duas vari�veis `a` e `b`, cada uma com um valor inicial
    
```
let a = 10
let b = 25
```

Agora, queremos trocar os valores delas, de forma que `a` passe a ter o valor de `b` e `b` passe a ter o valor de `a`.
Ou seja, no caso desse exemplo acima, `a` passaria a ser 25 e `b` passaria a ser 10.
    
```
let a = 10
let b = 25

// Aqui faremos uma l�gica para trocar os valores

// Depois de trocados, teremos o seguinte resultado:
console.log("O novo valor de a �", a) // O novo valor de a � 25
console.log("O novo valor de b �", b) // O novo valor de b � 10
```
    
Crie a l�gica que deve ser inserida no c�digo para que os valores de `a` e `b` sejam trocados, independente de qual valor essas vari�veis assumam inicialmente (ou seja: n�o basta dizer que `a = 25` e `b = 10` porque se os valores iniciais mudarem, a l�gica do seu programa teria que mudar tamb�m).

**Dicas:**

1. Podemos come�ar fazendo com que o valor de `a` seja igual ao que est� no `b`, ent�o ficaria assim: `a = b`. Nesse ponto, se d�ssemos um `console.log` no `a` e no `b`, ter�amos que `a = 25` e `b = 25`. Mas desse jeito, a gente perdeu o valor anterior que estava no `a`! E agora, como voc� poderia guardar esse valor para atribuir � vari�vel `b`?

2. Vamos supor que voc� tem dois copos: um copo A que tem suco de laranja e um copo B que tem coca-cola. Como voc� faria para trocar o conte�do dos dois?

3. Para trocar os l�quidos de copo sem mistur�-los, voc� pode pegar um copo vazio para te auxiliar!

---

### Documenta��o

[JavaScript - Vari�veis](https://www.w3schools.com/js/js_variables.asp)
