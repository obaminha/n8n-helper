# 🤖 n8n Automation Consultant

> Seu consultor de IA para criar, entender, corrigir e otimizar workflows e automações no n8n.

O **n8n Automation Consultant** é um assistente especializado em **n8n, workflows, integrações e automações**. Ele ajuda você a transformar ideias em automações funcionais, entender o papel de cada Node, solucionar problemas e construir workflows completos passo a passo.

A proposta é simples: **não apenas entregar uma solução, mas explicar a lógica por trás dela**, permitindo que você compreenda, modifique e mantenha suas próprias automações.

---

## ✨ O que este consultor faz

O consultor atua principalmente em quatro frentes:

| Você precisa de...   | O consultor...                                  |
| -------------------- | ----------------------------------------------- |
| Criar uma automação  | Estrutura o workflow e explica como construí-lo |
| Entender um workflow | Explica cada Node e o fluxo dos dados           |
| Corrigir um problema | Identifica a causa e orienta a correção         |
| Aprender n8n         | Ensina os conceitos de forma prática e objetiva |

Além disso, ele pode ajudar a **otimizar workflows existentes**, melhorar sua organização e propor abordagens alternativas quando fizer sentido.

---

## 🧠 Como ele explica um Workflow

Um dos principais diferenciais é explicar o workflow tanto **individualmente quanto como um sistema completo**.

### 🔹 1. Objetivo

Primeiro, explica:

* Qual problema o workflow resolve.
* Qual é o resultado esperado.
* Qual é a lógica geral da automação.

### 🔹 2. Visão geral

Antes de entrar nos detalhes, apresenta o caminho percorrido pelos dados:

```text
Entrada
   ↓
Processamento
   ↓
Decisão
   ↓
Ação
   ↓
Resultado
```

A ideia é permitir que você entenda o workflow antes de analisar seus detalhes técnicos.

### 🔹 3. Node por Node

Para cada Node, explica:

* O que ele faz.
* Por que está sendo utilizado.
* O que recebe.
* O que processa.
* O que entrega.
* Como se conecta ao próximo Node.

### 🔹 4. Funcionamento coletivo

Depois de analisar os Nodes individualmente, explica como eles trabalham juntos.

> O dado chega → é processado → uma condição é avaliada → o fluxo segue por determinado caminho → uma ação é executada → o resultado é entregue.

Esse modelo ajuda a transformar um workflow visual em uma **história lógica que pode ser compreendida de ponta a ponta**.

---

## 🚀 Construindo um Workflow

Quando o objetivo for criar uma automação do zero, o consultor conduz o processo passo a passo.

### Exemplo de sequência:

```text
1. Definir o objetivo
        ↓
2. Identificar as entradas
        ↓
3. Adicionar o Trigger
        ↓
4. Configurar os Nodes
        ↓
5. Conectar o fluxo
        ↓
6. Criar regras e condições
        ↓
7. Processar os dados
        ↓
8. Executar a ação final
        ↓
9. Testar o workflow
        ↓
10. Validar o resultado
```

Durante a construção, ele explica **onde clicar, o que configurar, quais valores utilizar e como testar cada etapa**.

---

## 🛠️ Quando houver um erro

Ao apresentar um workflow que não está funcionando, o consultor segue uma abordagem objetiva:

1. 🔎 Identifica a causa provável.
2. 🧠 Explica por que o problema acontece.
3. 🔧 Mostra como corrigir.
4. ✅ Explica como validar a correção.
5. 🛡️ Mostra como evitar o mesmo problema no futuro.

Quando as informações disponíveis não forem suficientes, ele deve indicar **exatamente o que precisa ser analisado**, evitando assumir informações que não foram fornecidas.

---

## 📖 Storytelling Técnico

O consultor utiliza **storytelling técnico** para explicar automações.

Em vez de simplesmente dizer:

> "O Node A envia os dados para o Node B."

A explicação deve permitir visualizar o processo:

> "O workflow recebe o pedido. Primeiro, verifica se os dados estão completos. Depois, envia essas informações para o próximo serviço. Se a resposta for válida, o fluxo continua; caso contrário, segue para o tratamento de erro."

O objetivo é fazer com que você consiga **visualizar mentalmente o caminho dos dados dentro do workflow**.

---

## 💬 Como conversar com o consultor

Não é necessário utilizar comandos específicos.

Você pode escrever naturalmente, por exemplo:

### 🏗️ Criar um Workflow

```text
Quero criar um workflow que receba dados de um formulário,
consulte uma API, processe os dados e salve o resultado no banco.

Me explique como construir isso no n8n passo a passo.
```

### 🔍 Entender um Workflow

```text
Explique esse workflow para mim.

Quero entender:
- O objetivo geral;
- O que cada Node faz;
- Como os dados passam entre os Nodes;
- Como tudo funciona em conjunto.
```

### 🐛 Corrigir um problema

```text
Meu workflow está apresentando um erro neste Node.

Explique:
- O que provavelmente está causando o problema;
- Como corrigir;
- Como testar a correção;
- Como evitar esse problema novamente.
```

### 🧠 Aprender um conceito

```text
Explique como funcionam Expressions no n8n.

Quero uma explicação simples, exemplos práticos
e situações em que eu realmente utilizaria isso.
```

---

## 📐 Princípios de resposta

O consultor deve seguir alguns princípios:

| Princípio             | Comportamento                                     |
| --------------------- | ------------------------------------------------- |
| 🎯 Objetividade       | Ir direto ao ponto                                |
| 🗣️ Linguagem natural | Evitar complexidade desnecessária                 |
| 🧩 Praticidade        | Priorizar exemplos reais                          |
| 🧠 Didática           | Explicar o motivo das decisões                    |
| 🔗 Contexto           | Relacionar Nodes individuais ao workflow completo |
| 🛠️ Implementação     | Ensinar como realmente construir                  |
| ✅ Confiabilidade      | Evitar inventar funcionalidades ou configurações  |
| 🔄 Manutenção         | Priorizar soluções simples e sustentáveis         |

---

## 📂 Estrutura sugerida

```text
n8n-automation-consultant/
│
├── README.md
│
├── prompt/
│   └── system-prompt.md
│
├── workflows/
│   ├── examples/
│   └── templates/
│
└── docs/
    ├── concepts/
    └── guides/
```

### Arquivos

| Arquivo/Pasta | Função                                   |
| ------------- | ---------------------------------------- |
| `README.md`   | Documentação principal do projeto        |
| `prompt/`     | Instruções de comportamento do consultor |
| `workflows/`  | Workflows e exemplos práticos            |
| `templates/`  | Modelos reutilizáveis                    |
| `docs/`       | Documentação complementar                |

---

## 🎯 Objetivo do projeto

O objetivo não é apenas criar workflows que **funcionem**.

É criar workflows que também sejam:

* Compreensíveis;
* Explicáveis;
* Fáceis de modificar;
* Fáceis de manter;
* Reutilizáveis;
* Bem estruturados.

> **Automatizar é apenas uma parte. Entender a automação é o que permite evoluí-la.**

---

## 🚀 Resultado esperado

Ao utilizar este consultor, você deve conseguir sair de uma ideia como:

```text
"Quero automatizar esse processo."
```

Para algo concreto:

```text
Ideia
 ↓
Arquitetura
 ↓
Workflow
 ↓
Nodes
 ↓
Configurações
 ↓
Testes
 ↓
Automação funcionando
```

E, principalmente, **entender por que cada etapa existe e como todo o workflow funciona em conjunto**.
