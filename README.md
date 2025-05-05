# 🚀 Desafio Controle de Fluxo

Este é um projeto em Java que simula um contador entre dois valores inteiros fornecidos pelo usuário via terminal. O desafio consiste em aplicar o conhecimento de **controle de fluxo**, como estruturas de repetição e exceções personalizadas.

## 📝 Descrição

O programa solicita dois números inteiros:

- Se o **segundo número** for **maior** que o primeiro, ele executa um loop que imprime mensagens numeradas a partir de 1 até a diferença entre os dois.
- Se o **primeiro número** for **maior** que o segundo, é lançada uma exceção personalizada (`ParametrosInvalidosException`), com a mensagem:

```
O segundo parâmetro deve ser maior que o primeiro
```

## 📂 Estrutura do Projeto

```
DesafioControleFluxo/
├── Contador.java
├── ParametrosInvalidosException.java
└── README.md
```

## 📌 Exemplo de Uso

### ✅ Entrada válida:
```
Digite o primeiro parâmetro
10
Digite o segundo parâmetro
15
```

### 🖨️ Saída:
```
Imprimindo o número 1
Imprimindo o número 2
Imprimindo o número 3
Imprimindo o número 4
Imprimindo o número 5
```

### ❌ Entrada inválida:
```
Digite o primeiro parâmetro
20
Digite o segundo parâmetro
5
```

### ⚠️ Saída:
```
O segundo parâmetro deve ser maior que o primeiro
```

## 📚 Conceitos aplicados

- Leitura de dados com `Scanner`
- Controle de fluxo com `for` e `if`
- Criação e uso de exceção personalizada (`Exception`)
- Boas práticas de organização de código em Java

## 🛠️ Como executar

1. Clone o repositório:
```bash
git clone https://github.com/seu-usuario/DesafioControleFluxo.git
```

2. Compile e execute com:
```bash
javac Contador.java ParametrosInvalidosException.java
java Contador
```

---

Desenvolvido como parte de estudos de Java e lógica de programação. 💡