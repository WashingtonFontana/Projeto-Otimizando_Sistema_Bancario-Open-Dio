Aqui está o conteúdo do **README.md** reformulado em Markdown puro, otimizado para que você possa apenas copiar e colar no seu arquivo. Ele mantém toda a estrutura profissional e os requisitos obrigatórios que você solicitou:

---

# 🏦 Sistema Bancário em Python: Desafio DIO

[![Python](https://img.shields.io/badge/Python-3.x-blue.svg)](https://www.python.org/)
[![Status](https://img.shields.io/badge/Status-Conclu%C3%ADdo-brightgreen.svg)]()
[![Challenge](https://img.shields.io/badge/Desafio-DIO-orange.svg)](https://www.dio.me/)

Este repositório contém uma solução robusta para o sistema bancário em Python, desenvolvida como resposta ao desafio técnico proposto pela **Digital Innovation One (DIO)**. O foco do projeto foi aplicar conceitos avançados de modularização e lógica de programação para criar uma interface funcional de terminal.

---

## 🛠️ Análise Técnica e Arquitetura

O software foi desenvolvido seguindo princípios de **Clean Code** e organização modular. Ao invés de uma execução linear, o sistema utiliza funções independentes, o que eleva a escalabilidade e a legibilidade do código.

### Conceitos e Tecnologias Aplicadas:
* **Modularização:** Separação clara de responsabilidades entre funções de negócio (`sacar`, `depositar`) e funções de interface (`menu`).
* **Estruturas de Dados:** Uso estratégico de `listas` para coleções e `dicionários` para mapeamento de usuários e contas.
* **Controle de Fluxo:** Implementação rigorosa de estruturas de repetição e condicionais para validação de regras de saque.
* **Boas Práticas:** Uso de argumentos *positional-only* (`/`) e *keyword-only* (`*`) para garantir chamadas de função seguras e explícitas.

---

## 🚀 Funcionalidades do Ecossistema

O sistema simula o funcionamento real de um banco digital através das seguintes features:

* **Sistema de Depósito:** Processamento de valores positivos com atualização instantânea de saldo.
* **Controle de Saques:** Validação tripla (limite por operação, limite de saldo e limite diário de transações).
* **Extrato Detalhado:** Histórico dinâmico de todas as operações realizadas na sessão.
* **Gestão de Clientes:** Cadastro de usuários vinculados a CPF (único) e endereço.
* **Criação de Contas:** Motor de abertura de contas correntes vinculadas a usuários existentes.
* **Listagem de Contas:** Visualização formatada de todas as agências e contas ativas.

---

## 💻 Instruções de Uso

Para testar o sistema localmente, siga os passos abaixo:

1.  Certifique-se de ter o **Python 3.x** instalado.
2.  Faça o download do script `main.py` (ou nome equivalente).
3.  Execute o comando no seu terminal:
    ```bash
    python main.py
    ```
4.  Interaja com o menu utilizando as siglas indicadas entre colchetes (ex: `d` para depósito).

---

## 👤 Autor e Créditos

### **Washington Fontana Netto**

> **Finalidade Acadêmica:** Este projeto foi desenvolvido integralmente com propósitos de estudo e aprimoramento técnico, servindo como portfólio para demonstração de lógica de programação em ambiente acadêmico.