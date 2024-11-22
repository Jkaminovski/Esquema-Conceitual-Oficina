# 🛠️ Esquema Conceitual para Oficina Mecânica

Este repositório contém o esquema conceitual de banco de dados criado para gerenciar o **controle e execução de ordens de serviço (OS)** em uma oficina mecânica, conforme a narrativa proposta no desafio.

---

## 📚 Descrição do Projeto

O objetivo é projetar um **modelo conceitual** que abranja todas as entidades, atributos e relacionamentos necessários para gerenciar os processos de uma oficina mecânica. A modelagem foi desenvolvida a partir de uma narrativa e inclui adaptações baseadas na compreensão do contexto.

### 📝 Contexto (Narrativa)
- Clientes levam veículos para **conserto** ou **revisões periódicas**.  
- Cada veículo é designado a uma **equipe de mecânicos**, que avalia os serviços a serem executados e preenche uma **Ordem de Serviço (OS)** com:
  - Número da OS  
  - Data de emissão  
  - Valor total  
  - Status  
  - Data prevista para conclusão  
- A partir da OS:
  - Calcula-se o valor de cada serviço com base em uma **tabela de referência de mão de obra**.
  - Incluem-se os valores das peças necessárias para a execução.  
- A equipe executa os serviços autorizados pelo cliente.  
- **Mecânicos** possuem:  
  - Código  
  - Nome  
  - Endereço  
  - Especialidade  

---

## 🎯 Objetivo

Desenvolver um **esquema conceitual** para organizar e gerenciar os processos da oficina, representando:
- Entidades essenciais como **Clientes**, **Veículos**, **Ordens de Serviço**, **Serviços**, **Peças** e **Mecânicos**.
- Relacionamentos entre essas entidades para garantir um fluxo claro das informações.

---

## 🛠️ Ferramentas Utilizadas

- **MySQL Workbench** para a modelagem conceitual em formato de diagrama ER.  

---
## 🌟 Resultado

O modelo conceitual criado representa a estrutura necessária para gerenciar os processos de uma oficina mecânica de forma eficiente.
Ele está preparado para ser implementado em um banco de dados físico para uso prático.
