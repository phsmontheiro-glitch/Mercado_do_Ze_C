# 🛒 Mercado do Zé — Sistema de Gerenciamento em C

O **Mercado do Zé** é uma aplicação desenvolvida em C ANSI como parte dos estudos da disciplina de Técnicas de Programação, no curso de Engenharia de Software.

Este foi meu primeiro projeto em C, desenvolvido em colaboração com Igor Jesus. O sistema simula operações básicas de um estabelecimento comercial, incluindo cadastro de produtos, cálculo de vendas, aplicação de descontos e fechamento de caixa.

## 🎯 Objetivo do Projeto

Aplicar conceitos fundamentais de programação em C, desenvolvendo uma aplicação de gerenciamento comercial por meio de estruturas de dados, funções e lógica condicional.

## ⚙️ Funcionalidades

* **Cadastro de produtos:** registro de nome, preço e quantidade dos produtos.
* **Cálculo de vendas:** cálculo automático do valor total dos itens cadastrados.
* **Sistema de descontos:** aplicação de regras condicionais para categorias como doces, temperos e verduras.
* **Fechamento de caixa:** consolidação dos valores da venda.
* **Emissão de nota fiscal:** apresentação de um relatório detalhado da compra diretamente no console.

## 🧠 Conceitos Aplicados

* Modularização e organização do código em funções.
* Estruturas (`struct`) para representar produtos.
* Vetores para armazenamento dos itens.
* Estruturas condicionais para implementação das regras de negócio.
* Laços de repetição para processamento dos produtos.
* Manipulação de strings e entrada de dados pelo console.

## 🛠️ Tecnologias

* **Linguagem:** C (ANSI)
* **Bibliotecas:** `stdio.h` e `string.h`
* **Ambiente:** Aplicação executada via console
* **Capacidade:** Até 100 produtos por sessão, conforme definido pela constante `MAX`.

## ▶️ Como Executar

O código pode ser compilado localmente ou executado em um compilador online.

### Opção 1 — Compilador online

1. Acesse o arquivo [`Mercado_do_Ze_C.c`](./Mercado_do_Ze_C.c).
2. Copie o código-fonte.
3. Abra um dos compiladores online:

   * [Programiz — C Online Compiler](https://www.programiz.com/c-programming/online-compiler/)
   * [OnlineGDB — C Compiler](https://www.onlinegdb.com/online_c_compiler)
4. Cole o código no editor.
5. Execute o programa clicando em **Run**.

### Opção 2 — Compilação local

Caso tenha o GCC instalado, compile o arquivo pelo terminal:

```bash
gcc Mercado_do_Ze_C.c -o mercado
```

Em seguida, execute o programa:

**Windows:**

```bash
.\mercado.exe
```

**Linux:**

```bash
./mercado
```

## 📚 Contexto Acadêmico

Projeto desenvolvido durante a disciplina de Técnicas de Programação, no curso de Engenharia de Software.

Representa uma etapa inicial de aprendizado em programação, com foco na construção de algoritmos, organização do código e resolução de problemas por meio da linguagem C.

## 👨‍💻 Desenvolvedores

- **[Pedro Monteiro](https://github.com/phsmontheiro-glitch)**
- **[Igor Jesus](https://github.com/igorjesusdasilvatoletntino)**

Projeto desenvolvido em colaboração para fins acadêmicos.
