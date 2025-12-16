# 📚 Resolução - Lista de Exercícios de Férias - JavaScript

## Prof. Rodrigo Medeiros - Curso Programação Full-Stack | Digital College

---

## Questões Nível 1 (⭐)

---

### **Questão 1 ⭐**

```javascript
// Declarando variáveis
let nome = "Maria";
let idade = 25;
let estudante = true;

// Exibindo os valores
console.log("Nome:", nome);
console.log("Idade:", idade);
console.log("Estudante:", estudante);

// Verificando os tipos
console.log("Tipo de nome:", typeof nome);       // string
console.log("Tipo de idade:", typeof idade);     // number
console.log("Tipo de estudante:", typeof estudante); // boolean
```

---

### **Questão 2 ⭐**

```javascript
const PI = 3.14159;

// Tentar reatribuir gera erro: TypeError: Assignment to constant variable
// PI = 3.14; // Isso causaria erro!

// Explicação: const cria uma constante que não pode ter seu valor reatribuído
// após a declaração inicial.

// Calculando a área do círculo (A = π * r²)
let raio = 5;
let area = PI * raio * raio;
console.log("Área do círculo:", area); // 78.53975
```

---

### **Questão 3 ⭐**

```javascript
let a = 15;
let b = 4;

let soma = a + b;
let subtracao = a - b;
let multiplicacao = a * b;
let divisao = a / b;
let resto = a % b;

console.log("Soma:", soma);             // 19
console.log("Subtração:", subtracao);   // 11
console.log("Multiplicação:", multiplicacao); // 60
console.log("Divisão:", divisao);       // 3.75
console.log("Resto:", resto);           // 3
```

---

### **Questão 4 ⭐**

```javascript
function saudacao(nome) {
    return `Olá, ${nome}! Bem-vindo ao curso de JavaScript!`;
}

console.log(saudacao("Rodrigo")); 
// "Olá, Rodrigo! Bem-vindo ao curso de JavaScript!"
```

---

### **Questão 5 ⭐**

```javascript
function ehPar(numero) {
    return numero % 2 === 0;
}

console.log(ehPar(4));  // true
console.log(ehPar(7));  // false
console.log(ehPar(10)); // true
console.log(ehPar(15)); // false
```

---

### **Questão 6 ⭐**

```javascript
let frutas = ["Maçã", "Banana", "Laranja", "Uva", "Manga"];

// Primeira fruta (índice 0)
console.log("Primeira fruta:", frutas[0]); // Maçã

// Última fruta (índice length - 1)
console.log("Última fruta:", frutas[frutas.length - 1]); // Manga

// Tamanho do array
console.log("Tamanho do array:", frutas.length); // 5
```

---

### **Questão 7 ⭐**

```javascript
let numeros = [10, 20, 30, 40, 50];
console.log("Array inicial:", numeros);

// push() - adiciona 60 ao final
numeros.push(60);
console.log("Após push(60):", numeros); // [10, 20, 30, 40, 50, 60]

// pop() - remove o último elemento
numeros.pop();
console.log("Após pop():", numeros); // [10, 20, 30, 40, 50]

// unshift() - adiciona 5 no início
numeros.unshift(5);
console.log("Após unshift(5):", numeros); // [5, 10, 20, 30, 40, 50]

// shift() - remove o primeiro elemento
numeros.shift();
console.log("Após shift():", numeros); // [10, 20, 30, 40, 50]
```

---

### **Questão 8 ⭐**

```javascript
let pessoa = {
    nome: "Carlos",
    idade: 30,
    cidade: "Fortaleza",
    profissao: "Desenvolvedor"
};

console.log("Nome:", pessoa.nome);         // Carlos
console.log("Idade:", pessoa.idade);       // 30
console.log("Cidade:", pessoa.cidade);     // Fortaleza
console.log("Profissão:", pessoa.profissao); // Desenvolvedor
```

---

### **Questão 9 ⭐**

```javascript
let idade = 17;

if (idade >= 18) {
    console.log("Você é maior de idade. Pode entrar!");
} else {
    console.log("Você é menor de idade. Entrada não permitida.");
}
// Saída: "Você é menor de idade. Entrada não permitida."
```

---

### **Questão 10 ⭐**

```javascript
for (let i = 1; i <= 10; i++) {
    console.log(i);
}
// Saída: 1, 2, 3, 4, 5, 6, 7, 8, 9, 10
```

---

### **Questão 11 ⭐**

```javascript
const dobrar = (numero) => numero * 2;

console.log(dobrar(5));  // 10
console.log(dobrar(10)); // 20
console.log(dobrar(25)); // 50
```

---

### **Questão 12 ⭐**

```javascript
let cores = ["vermelho", "azul", "verde", "amarelo"];

cores.forEach(cor => {
    console.log(cor);
});
// Saída: vermelho, azul, verde, amarelo
```

---

### **Questão 13 ⭐**

```javascript
function calcularAreaRetangulo(base, altura) {
    return base * altura;
}

console.log(calcularAreaRetangulo(5, 3));  // 15
console.log(calcularAreaRetangulo(10, 4)); // 40
console.log(calcularAreaRetangulo(7, 7));  // 49
```

---

### **Questão 14 ⭐**

```javascript
let numero = -5;

let resultado = numero >= 0 ? "Positivo" : "Negativo";

console.log(resultado); // "Negativo"

// Testando com número positivo
numero = 10;
resultado = numero >= 0 ? "Positivo" : "Negativo";
console.log(resultado); // "Positivo"
```

---

### **Questão 15 ⭐**

```javascript
let carro = {
    marca: "Toyota",
    modelo: "Corolla",
    ano: 2022
};

let chaves = Object.keys(carro);
console.log(chaves); // ["marca", "modelo", "ano"]
```

---

### **Questão 16 ⭐**

```javascript
let contador = 10;

while (contador >= 1) {
    console.log(contador);
    contador--;
}
// Saída: 10, 9, 8, 7, 6, 5, 4, 3, 2, 1
```

---

### **Questão 17 ⭐**

```javascript
let notas = [7.5, 8.0, 6.5, 9.0, 7.0];

let soma = notas.reduce((total, nota) => total + nota, 0);

console.log("Soma das notas:", soma); // 38
```

---

### **Questão 18 ⭐**

```javascript
const multiplicar = function(a, b) {
    return a * b;
};

console.log(multiplicar(4, 5));  // 20
console.log(multiplicar(3, 7));  // 21
console.log(multiplicar(10, 10)); // 100
```

---

### **Questão 19 ⭐**

```javascript
let aluno = { nome: "Maria", curso: "JavaScript", nota: 9.5 };

// Desestruturação
let { nome, curso, nota } = aluno;

console.log(nome);  // "Maria"
console.log(curso); // "JavaScript"
console.log(nota);  // 9.5
```

---

### **Questão 20 ⭐**

```javascript
let numeros = [1, 2, 3, 4, 5];

let triplicados = numeros.map(num => num * 3);

console.log(triplicados); // [3, 6, 9, 12, 15]
```

---

## Questões Nível 2 (⭐⭐)

---

### **Questão 21 ⭐⭐**

```javascript
function calcularMedia(notas) {
    let soma = notas.reduce((total, nota) => total + nota, 0);
    return soma / notas.length;
}

console.log(calcularMedia([7, 8, 9, 6]));     // 7.5
console.log(calcularMedia([10, 10, 10]));    // 10
console.log(calcularMedia([5.5, 6.5, 7.0])); // 6.333...
```

---

### **Questão 22 ⭐⭐**

```javascript
function avaliarAluno(nota) {
    if (nota >= 7) {
        return "Aprovado";
    } else if (nota >= 5) {
        return "Recuperação";
    } else {
        return "Reprovado";
    }
}

console.log(avaliarAluno(8.5)); // "Aprovado"
console.log(avaliarAluno(6.0)); // "Recuperação"
console.log(avaliarAluno(4.5)); // "Reprovado"
```

---

### **Questão 23 ⭐⭐**

```javascript
function filtrarPares(numeros) {
    return numeros.filter(num => num % 2 === 0);
}

console.log(filtrarPares([1, 2, 3, 4, 5, 6, 7, 8, 9, 10])); 
// [2, 4, 6, 8, 10]
```

---

### **Questão 24 ⭐⭐**

```javascript
let produtos = [
    { nome: "Notebook", preco: 3500 },
    { nome: "Mouse", preco: 150 },
    { nome: "Teclado", preco: 250 }
];

let nomesProdutos = produtos.map(produto => produto.nome);

console.log(nomesProdutos); // ["Notebook", "Mouse", "Teclado"]
```

---

### **Questão 25 ⭐⭐**

```javascript
function contarVogais(texto) {
    let vogais = "aeiouAEIOU";
    let contador = 0;
    
    for (let i = 0; i < texto.length; i++) {
        if (vogais.includes(texto[i])) {
            contador++;
        }
    }
    
    return contador;
}

console.log(contarVogais("JavaScript")); // 3
console.log(contarVogais("Programacao")); // 5
```

---

### **Questão 26 ⭐⭐**

```javascript
function diaDaSemana(numero) {
    switch (numero) {
        case 1: return "Domingo";
        case 2: return "Segunda-feira";
        case 3: return "Terça-feira";
        case 4: return "Quarta-feira";
        case 5: return "Quinta-feira";
        case 6: return "Sexta-feira";
        case 7: return "Sábado";
        default: return "Número inválido! Digite um número de 1 a 7.";
    }
}

console.log(diaDaSemana(1)); // "Domingo"
console.log(diaDaSemana(4)); // "Quarta-feira"
console.log(diaDaSemana(9)); // "Número inválido!"
```

---

### **Questão 27 ⭐⭐**

```javascript
class Retangulo {
    constructor(base, altura) {
        this.base = base;
        this.altura = altura;
    }
    
    calcularArea() {
        return this.base * this.altura;
    }
    
    calcularPerimetro() {
        return 2 * (this.base + this.altura);
    }
}

let retangulo1 = new Retangulo(5, 3);
console.log("Área:", retangulo1.calcularArea());       // 15
console.log("Perímetro:", retangulo1.calcularPerimetro()); // 16
```

---

### **Questão 28 ⭐⭐**

```javascript
let numeros = [10, 25, 35, 48, 52, 60, 75];

let encontrado = numeros.find(num => num > 50);

console.log(encontrado); // 52
```

---

### **Questão 29 ⭐⭐**

```javascript
function inverterString(texto) {
    return texto.split("").reverse().join("");
}

console.log(inverterString("JavaScript")); // "tpircSavaJ"
console.log(inverterString("Hello"));      // "olleH"
```

---

### **Questão 30 ⭐⭐**

```javascript
// 1. Criar uma cópia do array
let original = [1, 2, 3];
let copia = [...original];
console.log("Cópia:", copia); // [1, 2, 3]

// 2. Combinar dois arrays
let array1 = [1, 2, 3];
let array2 = [4, 5, 6];
let combinado = [...array1, ...array2];
console.log("Combinados:", combinado); // [1, 2, 3, 4, 5, 6]

// 3. Criar cópia de objeto adicionando propriedade
let pessoa = { nome: "João", idade: 25 };
let pessoaComCidade = { ...pessoa, cidade: "Fortaleza" };
console.log(pessoaComCidade); 
// { nome: "João", idade: 25, cidade: "Fortaleza" }
```

---

### **Questão 31 ⭐⭐**

```javascript
function encontrarMaiorMenor(numeros) {
    return {
        maior: Math.max(...numeros),
        menor: Math.min(...numeros)
    };
}

console.log(encontrarMaiorMenor([5, 2, 9, 1, 7])); 
// { maior: 9, menor: 1 }
```

---

### **Questão 32 ⭐⭐**

```javascript
let numeros = [3, 8, 12, 14, 21, 25, 30];

for (let i = 0; i < numeros.length; i++) {
    if (numeros[i] % 7 === 0) {
        console.log("Primeiro múltiplo de 7:", numeros[i]);
        break;
    }
}
// Saída: "Primeiro múltiplo de 7 encontrado: 14"
```

---

### **Questão 33 ⭐⭐**

```javascript
function removerDuplicados(array) {
    return [...new Set(array)];
}

console.log(removerDuplicados([1, 2, 2, 3, 4, 4, 5])); 
// [1, 2, 3, 4, 5]
```

---

### **Questão 34 ⭐⭐**

```javascript
let estudantes = [
    { nome: "Ana", nota: 8.5 },
    { nome: "Bruno", nota: 6.0 },
    { nome: "Carla", nota: 9.0 },
    { nome: "Diego", nota: 5.5 },
    { nome: "Elena", nota: 7.5 }
];

let aprovados = estudantes
    .filter(estudante => estudante.nota >= 7)
    .map(estudante => estudante.nome);

console.log(aprovados); // ["Ana", "Carla", "Elena"]
```

---

### **Questão 35 ⭐⭐**

```javascript
function calcularFatorial(numero) {
    if (numero === 0 || numero === 1) return 1;
    
    let fatorial = 1;
    for (let i = 2; i <= numero; i++) {
        fatorial *= i;
    }
    
    return fatorial;
}

console.log(calcularFatorial(5));  // 120
console.log(calcularFatorial(0));  // 1
console.log(calcularFatorial(7));  // 5040
```

---

### **Questão 36 ⭐⭐**

```javascript
let pessoa = {
    nome: "Maria",
    idade: 28,
    profissao: "Desenvolvedora",
    cidade: "Fortaleza"
};

let entradas = Object.entries(pessoa);

entradas.forEach(([chave, valor]) => {
    console.log(`${chave}: ${valor}`);
});
// nome: Maria, idade: 28, profissao: Desenvolvedora, cidade: Fortaleza
```

---

### **Questão 37 ⭐⭐**

```javascript
function classificarIdade(idade) {
    if (idade <= 12) return "Criança";
    if (idade <= 17) return "Adolescente";
    if (idade <= 59) return "Adulto";
    return "Idoso";
}

console.log(classificarIdade(8));  // "Criança"
console.log(classificarIdade(15)); // "Adolescente"
console.log(classificarIdade(25)); // "Adulto"
console.log(classificarIdade(65)); // "Idoso"
```

---

### **Questão 38 ⭐⭐**

```javascript
function somarPares(numeros) {
    return numeros
        .filter(num => num % 2 === 0)
        .reduce((soma, num) => soma + num, 0);
}

console.log(somarPares([1, 2, 3, 4, 5, 6, 7, 8, 9, 10])); // 30
```

---

### **Questão 39 ⭐⭐**

```javascript
function sistemaLogin() {
    const senhaCorreta = "1234";
    let tentativas = ["0000", "1111", "1234"];
    let indice = 0;
    let tentativa;
    
    do {
        tentativa = tentativas[indice];
        console.log(`Tentativa ${indice + 1}: ${tentativa}`);
        
        if (tentativa !== senhaCorreta) {
            console.log("Senha incorreta!");
        }
        indice++;
    } while (tentativa !== senhaCorreta && indice < tentativas.length);
    
    if (tentativa === senhaCorreta) {
        console.log("Acesso permitido!");
    }
}

sistemaLogin();
```

---

### **Questão 40 ⭐⭐**

```javascript
let frutas = ["Banana", "Maçã", "Laranja", "Abacaxi", "Uva"];

// Ordenar em ordem alfabética
frutas.sort();
console.log("Alfabética:", frutas);
// ["Abacaxi", "Banana", "Laranja", "Maçã", "Uva"]

// Ordenar em ordem reversa
frutas.sort().reverse();
console.log("Reversa:", frutas);
// ["Uva", "Maçã", "Laranja", "Banana", "Abacaxi"]
```

---

## Questões Nível 3 (⭐⭐⭐)

---

### **Questão 41 ⭐⭐⭐**

```javascript
class ContaBancaria {
    constructor(titular) {
        this.titular = titular;
        this.saldo = 0;
    }
    
    depositar(valor) {
        if (valor > 0) {
            this.saldo += valor;
            console.log(`Depósito de R$${valor.toFixed(2)} realizado.`);
            console.log(`Novo saldo: R$${this.saldo.toFixed(2)}`);
        } else {
            console.log("Valor inválido.");
        }
    }
    
    sacar(valor) {
        if (valor > 0 && valor <= this.saldo) {
            this.saldo -= valor;
            console.log(`Saque de R$${valor.toFixed(2)} realizado.`);
            console.log(`Novo saldo: R$${this.saldo.toFixed(2)}`);
        } else if (valor > this.saldo) {
            console.log(`Saldo insuficiente. Saldo: R$${this.saldo.toFixed(2)}`);
        }
    }
    
    verSaldo() {
        console.log(`Titular: ${this.titular}`);
        console.log(`Saldo: R$${this.saldo.toFixed(2)}`);
        return this.saldo;
    }
}

let conta = new ContaBancaria("João Silva");
conta.depositar(1000);
conta.sacar(300);
conta.verSaldo();
conta.sacar(800); // Saldo insuficiente
```

---

### **Questão 42 ⭐⭐⭐**

```javascript
function agruparPorPropriedade(array, chave) {
    return array.reduce((grupos, item) => {
        let valorChave = item[chave];
        
        if (!grupos[valorChave]) {
            grupos[valorChave] = [];
        }
        
        grupos[valorChave].push(item);
        return grupos;
    }, {});
}

let pessoas = [
    { nome: "Ana", cidade: "SP" },
    { nome: "João", cidade: "RJ" },
    { nome: "Maria", cidade: "SP" },
    { nome: "Pedro", cidade: "MG" }
];

console.log(agruparPorPropriedade(pessoas, "cidade"));
// { SP: [...], RJ: [...], MG: [...] }
```

---

### **Questão 43 ⭐⭐⭐**

```javascript
function validarCPF(cpf) {
    cpf = cpf.replace(/\D/g, '');
    
    if (cpf.length !== 11) return false;
    if (/^(\d)\1+$/.test(cpf)) return false;
    
    // Validação primeiro dígito
    let soma = 0;
    for (let i = 0; i < 9; i++) {
        soma += parseInt(cpf[i]) * (10 - i);
    }
    let resto = (soma * 10) % 11;
    if (resto === 10 || resto === 11) resto = 0;
    if (resto !== parseInt(cpf[9])) return false;
    
    // Validação segundo dígito
    soma = 0;
    for (let i = 0; i < 10; i++) {
        soma += parseInt(cpf[i]) * (11 - i);
    }
    resto = (soma * 10) % 11;
    if (resto === 10 || resto === 11) resto = 0;
    if (resto !== parseInt(cpf[10])) return false;
    
    return true;
}

console.log(validarCPF("123.456.789-09")); // true ou false
console.log(validarCPF("111.111.111-11")); // false
```

---

### **Questão 44 ⭐⭐⭐**

```javascript
function ordenarPorPropriedade(array, propriedade) {
    return [...array].sort((a, b) => {
        let valorA = a[propriedade];
        let valorB = b[propriedade];
        
        if (typeof valorA === 'string') {
            return valorA.localeCompare(valorB);
        }
        return valorA - valorB;
    });
}

let pessoas = [
    { nome: "Zélia", idade: 30 },
    { nome: "Ana", idade: 25 },
    { nome: "Carlos", idade: 35 }
];

console.log(ordenarPorPropriedade(pessoas, "nome"));
console.log(ordenarPorPropriedade(pessoas, "idade"));
```

---

### **Questão 45 ⭐⭐⭐**

```javascript
class Produto {
    constructor(nome, preco, quantidade) {
        this.nome = nome;
        this.preco = preco;
        this.quantidade = quantidade;
    }
    
    getSubtotal() {
        return this.preco * this.quantidade;
    }
}

class Carrinho {
    constructor() {
        this.produtos = [];
    }
    
    adicionarProduto(produto) {
        let existente = this.produtos.find(p => p.nome === produto.nome);
        if (existente) {
            existente.quantidade += produto.quantidade;
        } else {
            this.produtos.push(produto);
        }
        console.log(`${produto.nome} adicionado ao carrinho.`);
    }
    
    removerProduto(nomeProduto) {
        let indice = this.produtos.findIndex(p => p.nome === nomeProduto);
        if (indice !== -1) {
            this.produtos.splice(indice, 1);
            console.log(`${nomeProduto} removido.`);
        }
    }
    
    calcularTotal() {
        return this.produtos.reduce((soma, p) => soma + p.getSubtotal(), 0);
    }
    
    listarProdutos() {
        console.log("=== Carrinho ===");
        this.produtos.forEach(p => {
            console.log(`${p.nome}: R$${p.preco} x ${p.quantidade} = R$${p.getSubtotal()}`);
        });
        console.log(`Total: R$${this.calcularTotal().toFixed(2)}`);
    }
}

let carrinho = new Carrinho();
carrinho.adicionarProduto(new Produto("Notebook", 3500, 1));
carrinho.adicionarProduto(new Produto("Mouse", 150, 2));
carrinho.listarProdutos();
```

---

### **Questão 46 ⭐⭐⭐**

```javascript
function deepClone(obj) {
    if (obj === null || typeof obj !== 'object') return obj;
    
    if (Array.isArray(obj)) {
        return obj.map(item => deepClone(item));
    }
    
    let cloneObj = {};
    for (let chave in obj) {
        if (obj.hasOwnProperty(chave)) {
            cloneObj[chave] = deepClone(obj[chave]);
        }
    }
    return cloneObj;
}

let original = {
    nome: "João",
    endereco: { cidade: "Fortaleza", estado: "CE" },
    hobbies: ["leitura", ["violão", "guitarra"]]
};

let clone = deepClone(original);
clone.endereco.cidade = "São Paulo";
console.log(original.endereco.cidade); // "Fortaleza" (não alterado)
console.log(clone.endereco.cidade);    // "São Paulo"
```

---

### **Questão 47 ⭐⭐⭐**

```javascript
function fibonacci(n) {
    if (n <= 0) return [];
    if (n === 1) return [0];
    if (n === 2) return [0, 1];
    
    let sequencia = [0, 1];
    for (let i = 2; i < n; i++) {
        sequencia.push(sequencia[i - 1] + sequencia[i - 2]);
    }
    return sequencia;
}

console.log(fibonacci(10)); // [0, 1, 1, 2, 3, 5, 8, 13, 21, 34]
```

---

### **Questão 48 ⭐⭐⭐**

```javascript
function buscarProfundo(obj, chaveBuscada) {
    if (obj.hasOwnProperty(chaveBuscada)) {
        return obj[chaveBuscada];
    }
    
    for (let chave in obj) {
        if (typeof obj[chave] === 'object' && obj[chave] !== null) {
            let resultado = buscarProfundo(obj[chave], chaveBuscada);
            if (resultado !== undefined) return resultado;
        }
    }
    return undefined;
}

let obj = { a: { b: { c: { d: "encontrado" } } } };
console.log(buscarProfundo(obj, "d")); // "encontrado"
```

---

### **Questão 49 ⭐⭐⭐**

```javascript
function compararObjetos(obj1, obj2) {
    if (obj1 === obj2) return true;
    if (typeof obj1 !== 'object' || typeof obj2 !== 'object') return false;
    if (obj1 === null || obj2 === null) return false;
    
    let chaves1 = Object.keys(obj1);
    let chaves2 = Object.keys(obj2);
    
    if (chaves1.length !== chaves2.length) return false;
    
    for (let chave of chaves1) {
        if (!obj2.hasOwnProperty(chave)) return false;
        if (!compararObjetos(obj1[chave], obj2[chave])) return false;
    }
    return true;
}

let objA = { nome: "João", idade: 30 };
let objB = { nome: "João", idade: 30 };
console.log(compararObjetos(objA, objB)); // true
```

---

### **Questão 50 ⭐⭐⭐**

```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <title>Lista de Tarefas</title>
    <style>
        body { font-family: Arial; max-width: 500px; margin: 50px auto; }
        .tarefa { display: flex; justify-content: space-between; padding: 10px; border: 1px solid #ddd; margin: 5px 0; }
        .concluida span { text-decoration: line-through; color: #888; }
        button { cursor: pointer; margin-left: 5px; }
    </style>
</head>
<body>
    <h1>Lista de Tarefas</h1>
    <input type="text" id="inputTarefa" placeholder="Nova tarefa...">
    <button id="btnAdicionar">Adicionar</button>
    <ul id="listaTarefas"></ul>

    <script>
        const input = document.getElementById('inputTarefa');
        const btnAdicionar = document.getElementById('btnAdicionar');
        const lista = document.getElementById('listaTarefas');

        function criarTarefa(texto) {
            const li = document.createElement('li');
            li.className = 'tarefa';
            
            const span = document.createElement('span');
            span.textContent = texto;
            
            const btnConcluir = document.createElement('button');
            btnConcluir.textContent = '✓';
            btnConcluir.onclick = () => li.classList.toggle('concluida');
            
            const btnRemover = document.createElement('button');
            btnRemover.textContent = '✕';
            btnRemover.onclick = () => li.remove();
            
            li.appendChild(span);
            li.appendChild(btnConcluir);
            li.appendChild(btnRemover);
            return li;
        }

        function adicionarTarefa() {
            const texto = input.value.trim();
            if (texto) {
                lista.appendChild(criarTarefa(texto));
                input.value = '';
            }
        }

        btnAdicionar.onclick = adicionarTarefa;
        input.onkeypress = (e) => { if (e.key === 'Enter') adicionarTarefa(); };
    </script>
</body>
</html>
```

---

### **Questão 51 ⭐⭐⭐**

```javascript
function flattenArray(array) {
    return array.reduce((acc, item) => {
        if (Array.isArray(item)) {
            return acc.concat(flattenArray(item));
        }
        return acc.concat(item);
    }, []);
}

console.log(flattenArray([[1, 2], [3, [4, 5]]])); // [1, 2, 3, 4, 5]
console.log(flattenArray([1, [2, [3, [4, [5]]]]])); // [1, 2, 3, 4, 5]
```

---

### **Questão 52 ⭐⭐⭐**

```javascript
function memoize(fn) {
    const cache = {};
    
    return function(...args) {
        const chave = JSON.stringify(args);
        
        if (cache.hasOwnProperty(chave)) {
            console.log(`Cache hit: ${chave}`);
            return cache[chave];
        }
        
        console.log(`Calculando: ${chave}`);
        const resultado = fn.apply(this, args);
        cache[chave] = resultado;
        return resultado;
    };
}

const fibMemo = memoize(function(n) {
    if (n <= 1) return n;
    return fibMemo(n - 1) + fibMemo(n - 2);
});

console.log(fibMemo(10)); // 55
console.log(fibMemo(10)); // Cache hit
```

---

### **Questão 53 ⭐⭐⭐**

```javascript
function validarFormulario(dados) {
    const erros = {};
    
    if (!dados.nome || dados.nome.trim().length < 3) {
        erros.nome = "Nome deve ter no mínimo 3 caracteres";
    }
    
    const regexEmail = /^[^\s@]+@[^\s@]+\.[^\s@]+$/;
    if (!dados.email || !regexEmail.test(dados.email)) {
        erros.email = "Email inválido";
    }
    
    const idade = Number(dados.idade);
    if (isNaN(idade) || idade < 18 || idade > 100) {
        erros.idade = "Idade deve ser entre 18 e 100";
    }
    
    if (!dados.senha || dados.senha.length < 8 || 
        !/[A-Z]/.test(dados.senha) || !/[0-9]/.test(dados.senha)) {
        erros.senha = "Senha: mínimo 8 caracteres, 1 maiúscula, 1 número";
    }
    
    return erros;
}

console.log(validarFormulario({
    nome: "Jo", email: "invalido", idade: 15, senha: "123"
}));
```

---

### **Questão 54 ⭐⭐⭐**

```javascript
class Musica {
    constructor(titulo, artista, duracao) {
        this.titulo = titulo;
        this.artista = artista;
        this.duracao = duracao;
    }
}

class Playlist {
    constructor(nome) {
        this.nome = nome;
        this.musicas = [];
    }
    
    adicionarMusica(musica) {
        this.musicas.push(musica);
    }
    
    removerMusica(titulo) {
        this.musicas = this.musicas.filter(m => m.titulo !== titulo);
    }
    
    embaralhar() {
        for (let i = this.musicas.length - 1; i > 0; i--) {
            const j = Math.floor(Math.random() * (i + 1));
            [this.musicas[i], this.musicas[j]] = [this.musicas[j], this.musicas[i]];
        }
    }
    
    calcularDuracaoTotal() {
        const total = this.musicas.reduce((t, m) => t + m.duracao, 0);
        const min = Math.floor(total / 60);
        const seg = total % 60;
        return `${min}min ${seg}s`;
    }
    
    buscarPorArtista(artista) {
        return this.musicas.filter(m => 
            m.artista.toLowerCase().includes(artista.toLowerCase())
        );
    }
}

const playlist = new Playlist("Rock");
playlist.adicionarMusica(new Musica("Bohemian Rhapsody", "Queen", 354));
playlist.adicionarMusica(new Musica("Imagine", "John Lennon", 183));
console.log(playlist.calcularDuracaoTotal());
```

---

### **Questão 55 ⭐⭐⭐**

```javascript
function pipe(...funcoes) {
    return function(valorInicial) {
        return funcoes.reduce((valor, funcao) => funcao(valor), valorInicial);
    };
}

const adicionar2 = x => x + 2;
const multiplicar3 = x => x * 3;
const dividir2 = x => x / 2;

const pipeline = pipe(adicionar2, multiplicar3, dividir2);
console.log(pipeline(5)); // ((5 + 2) * 3) / 2 = 10.5
```

---

### **Questão 56 ⭐⭐⭐**

```javascript
function valorPorExtenso(valor) {
    const unidades = ['', 'um', 'dois', 'três', 'quatro', 'cinco', 'seis', 'sete', 'oito', 'nove'];
    const dezADezenove = ['dez', 'onze', 'doze', 'treze', 'quatorze', 'quinze', 'dezesseis', 'dezessete', 'dezoito', 'dezenove'];
    const dezenas = ['', '', 'vinte', 'trinta', 'quarenta', 'cinquenta', 'sessenta', 'setenta', 'oitenta', 'noventa'];
    const centenas = ['', 'cento', 'duzentos', 'trezentos', 'quatrocentos', 'quinhentos', 'seiscentos', 'setecentos', 'oitocentos', 'novecentos'];
    
    function converterGrupo(n) {
        if (n === 0) return '';
        if (n === 100) return 'cem';
        
        let resultado = '';
        const c = Math.floor(n / 100);
        if (c > 0) resultado += centenas[c];
        
        const du = n % 100;
        if (du > 0) {
            if (resultado) resultado += ' e ';
            if (du >= 10 && du <= 19) {
                resultado += dezADezenove[du - 10];
            } else {
                const d = Math.floor(du / 10);
                const u = du % 10;
                if (d > 0) resultado += dezenas[d];
                if (u > 0) resultado += (d > 0 ? ' e ' : '') + unidades[u];
            }
        }
        return resultado;
    }
    
    const [reais, centavos] = valor.toFixed(2).split('.').map(Number);
    let resultado = '';
    
    if (reais > 0) {
        if (reais >= 1000) {
            const milhares = Math.floor(reais / 1000);
            resultado += (milhares === 1 ? 'mil' : converterGrupo(milhares) + ' mil');
            const resto = reais % 1000;
            if (resto > 0) resultado += (resto < 100 ? ' e ' : ' ') + converterGrupo(resto);
        } else {
            resultado += converterGrupo(reais);
        }
        resultado += reais === 1 ? ' real' : ' reais';
    }
    
    if (centavos > 0) {
        if (reais > 0) resultado += ' e ';
        resultado += converterGrupo(centavos) + (centavos === 1 ? ' centavo' : ' centavos');
    }
    
    return resultado || 'zero reais';
}

console.log(valorPorExtenso(1523.45));
// "mil quinhentos e vinte e três reais e quarenta e cinco centavos"
```

---

### **Questão 57 ⭐⭐⭐**

```javascript
class Produto {
    constructor(codigo, nome, quantidade, precoUnitario) {
        this.codigo = codigo;
        this.nome = nome;
        this.quantidade = quantidade;
        this.precoUnitario = precoUnitario;
    }
}

class Estoque {
    constructor() {
        this.produtos = [];
    }
    
    adicionarProduto(produto) {
        if (this.buscarPorCodigo(produto.codigo)) {
            console.log("Produto já existe!");
            return false;
        }
        this.produtos.push(produto);
        return true;
    }
    
    removerProduto(codigo) {
        this.produtos = this.produtos.filter(p => p.codigo !== codigo);
    }
    
    atualizarQuantidade(codigo, quantidade) {
        const produto = this.buscarPorCodigo(codigo);
        if (produto) produto.quantidade = quantidade;
    }
    
    buscarPorCodigo(codigo) {
        return this.produtos.find(p => p.codigo === codigo);
    }
    
    buscarPorNome(nome) {
        return this.produtos.filter(p => 
            p.nome.toLowerCase().includes(nome.toLowerCase())
        );
    }
    
    calcularValorTotal() {
        return this.produtos.reduce((t, p) => t + (p.quantidade * p.precoUnitario), 0);
    }
    
    listarAbaixoDoLimite(limite) {
        return this.produtos.filter(p => p.quantidade < limite);
    }
}

const estoque = new Estoque();
estoque.adicionarProduto(new Produto(1, "Notebook", 10, 3500));
estoque.adicionarProduto(new Produto(2, "Mouse", 50, 80));
console.log("Valor total:", estoque.calcularValorTotal());
```

---

### **Questão 58 ⭐⭐⭐**

```javascript
function throttle(funcao, limite) {
    let aguardando = false;
    
    return function(...args) {
        if (!aguardando) {
            funcao.apply(this, args);
            aguardando = true;
            setTimeout(() => { aguardando = false; }, limite);
        }
    };
}

const funcaoThrottled = throttle(() => {
    console.log("Executado:", new Date().toISOString());
}, 2000);

// Teste: chamar várias vezes rapidamente
funcaoThrottled();
funcaoThrottled();
funcaoThrottled();
// Apenas a primeira executa, as outras são ignoradas por 2 segundos
```

---

### **Questão 59 ⭐⭐⭐**

```javascript
function calcularExpressao(expressao) {
    expressao = expressao.replace(/\s+/g, '');
    
    // Tokenizar
    const tokens = [];
    let numero = '';
    for (let char of expressao) {
        if (/[\d.]/.test(char)) {
            numero += char;
        } else if (['+', '-', '*', '/'].includes(char)) {
            if (numero) { tokens.push(parseFloat(numero)); numero = ''; }
            tokens.push(char);
        }
    }
    if (numero) tokens.push(parseFloat(numero));
    
    // Multiplicação e divisão primeiro
    let i = 0;
    while (i < tokens.length) {
        if (tokens[i] === '*' || tokens[i] === '/') {
            const resultado = tokens[i] === '*' 
                ? tokens[i-1] * tokens[i+1] 
                : tokens[i-1] / tokens[i+1];
            tokens.splice(i-1, 3, resultado);
        } else {
            i++;
        }
    }
    
    // Soma e subtração
    let resultado = tokens[0];
    for (let j = 1; j < tokens.length; j += 2) {
        resultado = tokens[j] === '+' ? resultado + tokens[j+1] : resultado - tokens[j+1];
    }
    
    return resultado;
}

console.log(calcularExpressao("2 + 3 * 4"));    // 14
console.log(calcularExpressao("10 - 2 * 3"));  // 4
console.log(calcularExpressao("8 / 2 + 3"));   // 7
```

---

### **Questão 60 ⭐⭐⭐**

```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <title>Cadastro de Alunos</title>
    <style>
        body { font-family: Arial; max-width: 900px; margin: 20px auto; padding: 20px; }
        .card { background: #f5f5f5; padding: 20px; border-radius: 10px; margin-bottom: 20px; }
        input, select { padding: 8px; margin: 5px; border: 1px solid #ddd; border-radius: 4px; }
        button { padding: 10px 20px; background: #4CAF50; color: white; border: none; cursor: pointer; border-radius: 4px; }
        button:hover { background: #45a049; }
        .btn-danger { background: #e74c3c; }
        .btn-warning { background: #f39c12; }
        table { width: 100%; border-collapse: collapse; margin-top: 15px; }
        th, td { padding: 10px; border-bottom: 1px solid #ddd; text-align: left; }
        th { background: #4CAF50; color: white; cursor: pointer; }
        .aprovado { color: green; font-weight: bold; }
        .reprovado { color: red; font-weight: bold; }
    </style>
</head>
<body>
    <h1>Sistema de Cadastro de Alunos</h1>
    
    <div class="card">
        <h2 id="formTitulo">Cadastrar Aluno</h2>
        <input type="hidden" id="alunoId">
        <input type="text" id="nome" placeholder="Nome">
        <input type="email" id="email" placeholder="E-mail">
        <input type="text" id="curso" placeholder="Curso">
        <input type="number" id="nota1" placeholder="N1" min="0" max="10" step="0.1">
        <input type="number" id="nota2" placeholder="N2" min="0" max="10" step="0.1">
        <input type="number" id="nota3" placeholder="N3" min="0" max="10" step="0.1">
        <button id="btnSalvar">Salvar</button>
        <button id="btnCancelar" class="btn-warning" style="display:none;">Cancelar</button>
    </div>
    
    <div class="card">
        <h2>Lista de Alunos</h2>
        <input type="text" id="filtroNome" placeholder="Buscar nome...">
        <select id="filtroSituacao">
            <option value="">Todas situações</option>
            <option value="Aprovado">Aprovados</option>
            <option value="Reprovado">Reprovados</option>
        </select>
        <table>
            <thead>
                <tr>
                    <th data-sort="nome">Nome</th>
                    <th data-sort="email">E-mail</th>
                    <th data-sort="curso">Curso</th>
                    <th>Notas</th>
                    <th data-sort="media">Média</th>
                    <th>Situação</th>
                    <th>Ações</th>
                </tr>
            </thead>
            <tbody id="corpoTabela"></tbody>
        </table>
    </div>

    <script>
        class Aluno {
            constructor(id, nome, email, curso, notas) {
                this.id = id;
                this.nome = nome;
                this.email = email;
                this.curso = curso;
                this.notas = notas;
            }
            
            get media() { return (this.notas.reduce((a, b) => a + b, 0) / 3).toFixed(2); }
            get situacao() { return this.media >= 7 ? "Aprovado" : "Reprovado"; }
        }
        
        class Sistema {
            constructor() {
                this.alunos = [];
                this.proximoId = 1;
                this.editandoId = null;
                this.ordenacao = { campo: 'nome', dir: 'asc' };
                this.init();
            }
            
            init() {
                document.getElementById('btnSalvar').onclick = () => this.salvar();
                document.getElementById('btnCancelar').onclick = () => this.cancelar();
                document.getElementById('filtroNome').oninput = () => this.renderizar();
                document.getElementById('filtroSituacao').onchange = () => this.renderizar();
                document.querySelectorAll('th[data-sort]').forEach(th => {
                    th.onclick = () => this.ordenar(th.dataset.sort);
                });
                
                // Dados de exemplo
                this.adicionar(new Aluno(this.proximoId++, "Ana Silva", "ana@email.com", "JavaScript", [8.5, 9.0, 7.5]));
                this.adicionar(new Aluno(this.proximoId++, "Bruno Costa", "bruno@email.com", "Python", [5.0, 6.0, 5.5]));
                this.renderizar();
            }
            
            adicionar(aluno) { this.alunos.push(aluno); }
            
            salvar() {
                const nome = document.getElementById('nome').value;
                const email = document.getElementById('email').value;
                const curso = document.getElementById('curso').value;
                const notas = [
                    parseFloat(document.getElementById('nota1').value),
                    parseFloat(document.getElementById('nota2').value),
                    parseFloat(document.getElementById('nota3').value)
                ];
                
                if (this.editandoId) {
                    const aluno = this.alunos.find(a => a.id === this.editandoId);
                    Object.assign(aluno, { nome, email, curso, notas });
                    this.cancelar();
                } else {
                    this.adicionar(new Aluno(this.proximoId++, nome, email, curso, notas));
                }
                
                this.limparForm();
                this.renderizar();
            }
            
            editar(id) {
                const aluno = this.alunos.find(a => a.id === id);
                this.editandoId = id;
                document.getElementById('nome').value = aluno.nome;
                document.getElementById('email').value = aluno.email;
                document.getElementById('curso').value = aluno.curso;
                document.getElementById('nota1').value = aluno.notas[0];
                document.getElementById('nota2').value = aluno.notas[1];
                document.getElementById('nota3').value = aluno.notas[2];
                document.getElementById('formTitulo').textContent = 'Editar Aluno';
                document.getElementById('btnCancelar').style.display = 'inline';
            }
            
            cancelar() {
                this.editandoId = null;
                this.limparForm();
                document.getElementById('formTitulo').textContent = 'Cadastrar Aluno';
                document.getElementById('btnCancelar').style.display = 'none';
            }
            
            remover(id) {
                if (confirm('Remover aluno?')) {
                    this.alunos = this.alunos.filter(a => a.id !== id);
                    this.renderizar();
                }
            }
            
            limparForm() {
                ['nome', 'email', 'curso', 'nota1', 'nota2', 'nota3'].forEach(id => {
                    document.getElementById(id).value = '';
                });
            }
            
            ordenar(campo) {
                if (this.ordenacao.campo === campo) {
                    this.ordenacao.dir = this.ordenacao.dir === 'asc' ? 'desc' : 'asc';
                } else {
                    this.ordenacao = { campo, dir: 'asc' };
                }
                this.renderizar();
            }
            
            filtrar() {
                const filtroNome = document.getElementById('filtroNome').value.toLowerCase();
                const filtroSituacao = document.getElementById('filtroSituacao').value;
                
                return this.alunos
                    .filter(a => a.nome.toLowerCase().includes(filtroNome))
                    .filter(a => !filtroSituacao || a.situacao === filtroSituacao)
                    .sort((a, b) => {
                        let va = this.ordenacao.campo === 'media' ? parseFloat(a.media) : a[this.ordenacao.campo];
                        let vb = this.ordenacao.campo === 'media' ? parseFloat(b.media) : b[this.ordenacao.campo];
                        if (typeof va === 'string') { va = va.toLowerCase(); vb = vb.toLowerCase(); }
                        return this.ordenacao.dir === 'asc' ? (va > vb ? 1 : -1) : (va < vb ? 1 : -1);
                    });
            }
            
            renderizar() {
                const tbody = document.getElementById('corpoTabela');
                const alunos = this.filtrar();
                
                tbody.innerHTML = alunos.map(a => `
                    <tr>
                        <td>${a.nome}</td>
                        <td>${a.email}</td>
                        <td>${a.curso}</td>
                        <td>${a.notas.join(' | ')}</td>
                        <td>${a.media}</td>
                        <td class="${a.situacao.toLowerCase()}">${a.situacao}</td>
                        <td>
                            <button class="btn-warning" onclick="sistema.editar(${a.id})">Editar</button>
                            <button class="btn-danger" onclick="sistema.remover(${a.id})">Excluir</button>
                        </td>
                    </tr>
                `).join('');
            }
        }
        
        const sistema = new Sistema();
    </script>
</body>
</html>
```

---

## 📝 Critérios de Avaliação

| Nível | Questões | Pontos cada | Total |
|-------|----------|-------------|-------|
| ⭐ | 1-20 | 0.5 | 10 pontos |
| ⭐⭐ | 21-40 | 1.0 | 20 pontos |
| ⭐⭐⭐ | 41-60 | 1.5 | 30 pontos |
| **TOTAL** | **60** | - | **60 pontos** |

**Nota:** Aceite variações nas soluções dos alunos, desde que a lógica esteja correta!

---

*Prof. Rodrigo Medeiros - Digital College - 2025*
