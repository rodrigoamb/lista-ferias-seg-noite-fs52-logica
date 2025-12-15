# 📚 Lista de Exercícios de Férias - JavaScript

## Prof. Rodrigo Medeiros - Curso Programação Full-Stack | Digital College

---

## 📖 Tópicos para Estudo

Antes de resolver os exercícios, revise os seguintes conteúdos:

### Aula 11 - Introdução ao JavaScript

- O que é JavaScript e sua importância
- Formas de executar JavaScript (console, HTML, arquivo .js, Node.js)
- Variáveis: `var`, `let` e `const`
- Boas práticas na nomeação de variáveis (camelCase, nomes descritivos)
- Tipos de dados primitivos: `String`, `Number`, `Boolean`, `Undefined`, `Null`
- Tipos complexos: Arrays e Objetos
- Operador `typeof`
- Operadores aritméticos: `+`, `-`, `*`, `/`, `%`
- Operadores relacionais: `>`, `<`, `>=`, `<=`, `==`, `===`, `!=`, `!==`
- Operadores lógicos: `&&`, `||`, `!`

### Aula 12 - Funções em JavaScript

- O que são funções e por que utilizá-las
- Princípio DRY (Don't Repeat Yourself)
- Funções declaradas (nomeadas)
- Funções anônimas
- Arrow Functions
- Parâmetros e argumentos
- Retorno de valores (`return`)
- Escopo global e local de variáveis

### Aula 13 - Estruturas de Controle

- Estruturas condicionais: `if`, `else if`, `else`
- Estrutura `switch/case`
- Importância do `break` no switch
- Operador ternário (`? :`)

### Aula 14 - Estruturas de Repetição

- Loop `for`
- Loop `while`
- Loop `do...while`
- Controle de fluxo: `break` e `continue`
- Diferença entre `while` e `do...while`

### Aula 15 - Arrays e seus Métodos

- O que são Arrays
- Criação de arrays (colchetes e `new Array()`)
- Acesso a elementos por índice
- Métodos básicos: `push()`, `pop()`, `unshift()`, `shift()`, `splice()`, `slice()`
- Métodos avançados: `map()`, `filter()`, `reduce()`, `forEach()`, `find()`, `some()`, `every()`
- Manipulação: `sort()`, `indexOf()`, `includes()`
- Iteração com `for` e `for...of`

### Aula 16 - Objetos e Introdução à POO

- O que são objetos (pares chave: valor)
- Criação de objetos literais
- Acesso e modificação de propriedades
- Adição e remoção de propriedades
- Desestruturação de objetos e arrays
- Operador Spread (`...`)
- Métodos: `Object.keys()`, `Object.values()`, `Object.entries()`
- Iteração com `for...in`
- Conceitos de POO: Classe, Objeto, Instância, Método
- Criação de classes com `class` e `constructor`

### Aula 17 - Manipulação Avançada do DOM

- O que é o DOM (Document Object Model)
- Diferença entre HTML e DOM
- Seleção de elementos: `getElementById()`, `querySelector()`, `querySelectorAll()`
- Criação de elementos: `createElement()`
- Adição de elementos: `appendChild()`
- Remoção de elementos: `remove()`
- Manipulação de classes: `classList.add()`, `classList.remove()`
- Eventos: `addEventListener()`
- Navegação no DOM: `parentElement`, `parentNode`

---

## 🎯 Exercícios

### Legenda de Níveis:

- ⭐ **Nível 1** - Básico
- ⭐⭐ **Nível 2** - Intermediário
- ⭐⭐⭐ **Nível 3** - Avançado

---

## Questões Nível 1 (⭐)

**1. ⭐ Nível 1**
Declare três variáveis usando `let`: `nome` (string), `idade` (number) e `estudante` (boolean). Atribua valores a elas e exiba no console usando `console.log()`. Em seguida, use `typeof` para verificar o tipo de cada variável.

---

**2. ⭐ Nível 1**
Crie uma variável `const` chamada `PI` com o valor `3.14159`. Tente reatribuir um novo valor a ela e explique o que acontece. Depois, use essa constante para calcular a área de um círculo com raio 5.

---

**3. ⭐ Nível 1**
Dados dois números armazenados em variáveis `a = 15` e `b = 4`, calcule e exiba no console:

- A soma
- A subtração
- A multiplicação
- A divisão
- O resto da divisão (módulo)

---

**4. ⭐ Nível 1**
Crie uma função chamada `saudacao` que receba um nome como parâmetro e retorne a string `"Olá, [nome]! Bem-vindo ao curso de JavaScript!"`. Chame a função com seu próprio nome.

---

**5. ⭐ Nível 1**
Escreva uma função `ehPar` que receba um número e retorne `true` se o número for par ou `false` se for ímpar. Use o operador módulo (`%`).

---

**6. ⭐ Nível 1**
Crie um array chamado `frutas` com 5 frutas de sua escolha. Em seguida:

- Exiba a primeira fruta
- Exiba a última fruta
- Exiba o tamanho do array usando `.length`

---

**7. ⭐ Nível 1**
Dado o array `let numeros = [10, 20, 30, 40, 50]`, use os métodos:

- `push()` para adicionar o número 60 ao final
- `pop()` para remover o último elemento
- `unshift()` para adicionar o número 5 no início
- `shift()` para remover o primeiro elemento

Exiba o array após cada operação.

---

**8. ⭐ Nível 1**
Crie um objeto chamado `pessoa` com as propriedades: `nome`, `idade`, `cidade` e `profissao`. Depois, acesse e exiba cada propriedade usando notação de ponto (`objeto.propriedade`).

---

**9. ⭐ Nível 1**
Escreva uma estrutura condicional `if/else` que verifique se uma pessoa é maior de idade (18 anos ou mais). A idade deve estar em uma variável. Exiba uma mensagem apropriada para cada caso.

---

**10. ⭐ Nível 1**
Use um loop `for` para exibir os números de 1 a 10 no console. Cada número deve aparecer em uma linha separada.

---

**11. ⭐ Nível 1**
Crie uma Arrow Function chamada `dobrar` que receba um número e retorne o dobro dele. Teste com os valores 5, 10 e 25.

---

**12. ⭐ Nível 1**
Dado o array `let cores = ["vermelho", "azul", "verde", "amarelo"]`, use o método `forEach()` para exibir cada cor no console.

---

**13. ⭐ Nível 1**
Crie uma função `calcularAreaRetangulo` que receba a base e a altura como parâmetros e retorne a área do retângulo (base × altura).

---

**14. ⭐ Nível 1**
Use o operador ternário para verificar se um número armazenado em uma variável é positivo ou negativo. Armazene o resultado ("Positivo" ou "Negativo") em uma nova variável e exiba-a.

---

**15. ⭐ Nível 1**
Crie um objeto `carro` com as propriedades `marca`, `modelo` e `ano`. Use `Object.keys()` para exibir todas as chaves do objeto.

---

**16. ⭐ Nível 1**
Escreva um loop `while` que conte de 10 até 1 (contagem regressiva) e exiba cada número no console.

---

**17. ⭐ Nível 1**
Dado o array `let notas = [7.5, 8.0, 6.5, 9.0, 7.0]`, use o método `reduce()` para calcular a soma de todas as notas.

---

**18. ⭐ Nível 1**
Crie uma função anônima armazenada em uma variável `const multiplicar` que receba dois números e retorne o produto deles.

---

**19. ⭐ Nível 1**
Use a desestruturação para extrair os valores de um objeto `let aluno = { nome: "Maria", curso: "JavaScript", nota: 9.5 }` em variáveis separadas.

---

**20. ⭐ Nível 1**
Crie um array de números `[1, 2, 3, 4, 5]` e use o método `map()` para criar um novo array onde cada número está triplicado.

---

## Questões Nível 2 (⭐⭐)

**21. ⭐⭐ Nível 2**
Crie uma função `calcularMedia` que receba um array de notas como parâmetro e retorne a média aritmética. Use `reduce()` para somar os valores e divida pelo tamanho do array.

---

**22. ⭐⭐ Nível 2**
Escreva uma função `avaliarAluno` que receba uma nota e retorne:

- "Aprovado" se a nota for >= 7
- "Recuperação" se a nota for >= 5 e < 7
- "Reprovado" se a nota for < 5

Use estruturas condicionais `if/else if/else`.

---

**23. ⭐⭐ Nível 2**
Crie uma função `filtrarPares` que receba um array de números e retorne um novo array contendo apenas os números pares. Use o método `filter()`.

---

**24. ⭐⭐ Nível 2**
Dado um array de objetos representando produtos:

```javascript
let produtos = [
  { nome: "Notebook", preco: 3500 },
  { nome: "Mouse", preco: 150 },
  { nome: "Teclado", preco: 250 },
];
```

Use `map()` para criar um novo array contendo apenas os nomes dos produtos.

---

**25. ⭐⭐ Nível 2**
Crie uma função `contarVogais` que receba uma string e retorne a quantidade de vogais presentes nela. Use um loop `for` para percorrer a string.

---

**26. ⭐⭐ Nível 2**
Implemente uma estrutura `switch/case` que receba um número de 1 a 7 e retorne o dia da semana correspondente. Inclua um `default` para números inválidos.

---

**27. ⭐⭐ Nível 2**
Crie uma classe `Retangulo` com propriedades `base` e `altura`. Adicione métodos `calcularArea()` e `calcularPerimetro()`. Crie uma instância e teste os métodos.

---

**28. ⭐⭐ Nível 2**
Dado um array de números, use `find()` para encontrar o primeiro número maior que 50. Se não existir, o resultado deve ser `undefined`.

---

**29. ⭐⭐ Nível 2**
Crie uma função `inverterString` que receba uma string e retorne ela invertida. Por exemplo: "JavaScript" → "tpircSavaJ".

---

**30. ⭐⭐ Nível 2**
Use o operador spread (`...`) para:

1. Criar uma cópia do array `[1, 2, 3]`
2. Combinar dois arrays `[1, 2, 3]` e `[4, 5, 6]` em um único array
3. Criar uma cópia de um objeto `{ nome: "João", idade: 25 }` adicionando uma nova propriedade `cidade`

---

**31. ⭐⭐ Nível 2**
Crie uma função `encontrarMaiorMenor` que receba um array de números e retorne um objeto com as propriedades `maior` e `menor` contendo respectivamente o maior e o menor valor do array.

---

**32. ⭐⭐ Nível 2**
Use um loop `for` com a instrução `break` para encontrar o primeiro múltiplo de 7 em um array de números. Quando encontrar, interrompa o loop e exiba o valor.

---

**33. ⭐⭐ Nível 2**
Crie uma função `removerDuplicados` que receba um array e retorne um novo array sem elementos duplicados. Dica: use `filter()` e `indexOf()`.

---

**34. ⭐⭐ Nível 2**
Dado um array de objetos de estudantes com `nome` e `nota`, use `filter()` para retornar apenas os estudantes aprovados (nota >= 7) e `map()` para extrair apenas seus nomes.

---

**35. ⭐⭐ Nível 2**
Crie uma função `calcularFatorial` que receba um número e retorne seu fatorial usando um loop `for`. Por exemplo: fatorial de 5 = 5 × 4 × 3 × 2 × 1 = 120.

---

**36. ⭐⭐ Nível 2**
Use `Object.entries()` para iterar sobre um objeto e exibir cada par chave-valor no formato "chave: valor".

---

**37. ⭐⭐ Nível 2**
Crie uma função `classificarIdade` que receba uma idade e retorne:

- "Criança" para idade até 12
- "Adolescente" para idade de 13 a 17
- "Adulto" para idade de 18 a 59
- "Idoso" para idade 60 ou mais

---

**38. ⭐⭐ Nível 2**
Implemente uma função `somarPares` que use `filter()` e `reduce()` encadeados para somar apenas os números pares de um array.

---

**39. ⭐⭐ Nível 2**
Crie uma função usando `do...while` que simule um sistema de login. O loop deve continuar pedindo a senha até que a senha correta ("1234") seja inserida. Use `prompt()` se estiver no navegador ou simule com variáveis.

---

**40. ⭐⭐ Nível 2**
Dado um array de strings, use `sort()` para ordená-las em ordem alfabética. Depois, ordene em ordem alfabética reversa.

---

## Questões Nível 3 (⭐⭐⭐)

**41. ⭐⭐⭐ Nível 3**
Crie uma classe `ContaBancaria` com:

- Propriedades: `titular`, `saldo` (inicial 0)
- Métodos: `depositar(valor)`, `sacar(valor)`, `verSaldo()`
- O método `sacar` deve verificar se há saldo suficiente

Crie duas instâncias e simule operações bancárias.

---

**42. ⭐⭐⭐ Nível 3**
Implemente uma função `agruparPorPropriedade` que receba um array de objetos e uma chave, e retorne um objeto onde cada propriedade é um valor único da chave e o valor é um array com os objetos correspondentes.

Exemplo:

```javascript
let pessoas = [
  { nome: "Ana", cidade: "SP" },
  { nome: "João", cidade: "RJ" },
  { nome: "Maria", cidade: "SP" },
];
// agruparPorPropriedade(pessoas, "cidade") deve retornar:
// { SP: [{...}, {...}], RJ: [{...}] }
```

---

**43. ⭐⭐⭐ Nível 3**
Crie uma função `validarCPF` que receba uma string de CPF (apenas números) e verifique:

- Se tem exatamente 11 dígitos
- Se não são todos iguais (ex: "11111111111")
- Retorne `true` para válido ou `false` para inválido

---

**44. ⭐⭐⭐ Nível 3**
Implemente uma função `ordenarPorPropriedade` que receba um array de objetos e o nome de uma propriedade, e retorne o array ordenado por essa propriedade (crescente para números, alfabético para strings).

---

**45. ⭐⭐⭐ Nível 3**
Crie um sistema de carrinho de compras usando classes:

- Classe `Produto` com `nome`, `preco`, `quantidade`
- Classe `Carrinho` com métodos:
  - `adicionarProduto(produto)`
  - `removerProduto(nomeProduto)`
  - `calcularTotal()`
  - `listarProdutos()`

---

**46. ⭐⭐⭐ Nível 3**
Implemente uma função `deepClone` que faça uma cópia profunda de um objeto (incluindo objetos aninhados). Não use `JSON.parse(JSON.stringify())`.

---

**47. ⭐⭐⭐ Nível 3**
Crie uma função `fibonacci` que retorne um array com os primeiros `n` números da sequência de Fibonacci. Use um loop e não recursão.

---

**48. ⭐⭐⭐ Nível 3**
Implemente uma função `buscarProfundo` que receba um objeto aninhado e uma chave, e retorne o valor dessa chave em qualquer nível de profundidade do objeto.

Exemplo:

```javascript
let obj = { a: { b: { c: { d: "encontrado" } } } };
// buscarProfundo(obj, "d") deve retornar "encontrado"
```

---

**49. ⭐⭐⭐ Nível 3**
Crie uma função `compararObjetos` que receba dois objetos e retorne `true` se eles tiverem as mesmas propriedades com os mesmos valores, ou `false` caso contrário.

---

**50. ⭐⭐⭐ Nível 3**
Implemente um sistema de lista de tarefas (TODO) usando manipulação do DOM:

- Input para digitar a tarefa
- Botão para adicionar
- Cada tarefa deve ter um botão para marcar como concluída (riscar texto)
- Cada tarefa deve ter um botão para remover

Escreva o HTML e o JavaScript necessários.

---

**51. ⭐⭐⭐ Nível 3**
Crie uma função `flattenArray` que transforme um array multidimensional em um array de uma única dimensão. Exemplo: `[[1, 2], [3, [4, 5]]]` → `[1, 2, 3, 4, 5]`.

---

**52. ⭐⭐⭐ Nível 3**
Implemente uma função `memoize` que receba uma função como parâmetro e retorne uma versão "memorizada" dela, que armazena resultados anteriores para evitar recálculos.

---

**53. ⭐⭐⭐ Nível 3**
Crie um validador de formulário que verifique:

- Nome: mínimo 3 caracteres
- Email: deve conter "@" e "."
- Idade: número entre 18 e 100
- Senha: mínimo 8 caracteres, pelo menos uma letra maiúscula e um número

Retorne um objeto com os erros encontrados ou um objeto vazio se tudo estiver válido.

---

**54. ⭐⭐⭐ Nível 3**
Implemente uma classe `Playlist` que:

- Armazene músicas (objetos com `titulo`, `artista`, `duracao`)
- Tenha métodos para adicionar, remover, embaralhar e calcular duração total
- Tenha um método para buscar músicas por artista

---

**55. ⭐⭐⭐ Nível 3**
Crie uma função `pipe` que receba múltiplas funções como argumentos e retorne uma nova função que aplique todas elas em sequência ao valor de entrada.

Exemplo:

```javascript
const adicionar2 = (x) => x + 2;
const multiplicar3 = (x) => x * 3;
const pipeline = pipe(adicionar2, multiplicar3);
// pipeline(5) deve retornar 21 ((5 + 2) * 3)
```

---

**56. ⭐⭐⭐ Nível 3**
Implemente uma função que converta um valor em reais para extenso. Por exemplo: `1523.45` → "mil quinhentos e vinte e três reais e quarenta e cinco centavos".

---

**57. ⭐⭐⭐ Nível 3**
Crie um sistema de gerenciamento de estoque com classes:

- `Produto`: `codigo`, `nome`, `quantidade`, `precoUnitario`
- `Estoque`: array de produtos com métodos para:
  - Adicionar/remover produto
  - Atualizar quantidade
  - Buscar por código ou nome
  - Calcular valor total do estoque
  - Listar produtos com quantidade abaixo de um limite

---

**58. ⭐⭐⭐ Nível 3**
Implemente uma função `throttle` que limite a execução de uma função para no máximo uma vez a cada `n` milissegundos.

---

**59. ⭐⭐⭐ Nível 3**
Crie um mini interpretador de expressões matemáticas que receba uma string como "2 + 3 \* 4" e retorne o resultado correto (respeitando precedência de operadores).

---

**60. ⭐⭐⭐ Nível 3**
Implemente um sistema completo de cadastro de alunos com interface DOM:

- Formulário para cadastrar aluno (nome, email, curso, notas)
- Tabela para exibir todos os alunos cadastrados
- Cálculo automático da média e situação (Aprovado/Reprovado)
- Botões para editar e excluir cada aluno
- Filtro para buscar alunos por nome ou curso
- Ordenação por nome ou média

Utilize classes, manipulação do DOM, arrays e todos os conceitos aprendidos.

---

## 💡 Dicas para Resolver os Exercícios

1. **Leia o enunciado com atenção** antes de começar a codificar
2. **Divida problemas complexos** em partes menores
3. **Teste seu código** com diferentes valores de entrada
4. **Use `console.log()`** para debugar e entender o fluxo do código
5. **Consulte a documentação** do MDN Web Docs quando tiver dúvidas
6. **Pratique regularmente** - a programação se aprende praticando!

---

## 📝 Entrega

- Crie um arquivo `.js` para cada exercício ou agrupe por nível
- Comente seu código explicando a lógica utilizada
- Teste todas as funções antes de considerar o exercício concluído

---

**Bons estudos e boas férias! 🚀**

_Prof. Rodrigo Medeiros - Digital College_
