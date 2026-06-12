# 🦸‍♂️ Desafio Multiverso Nerd - Higienização e Normalização de Dados

## 📋 Sobre o Projeto

Este repositório contém a solução do desafio **"O Multiverso Precisa de Organização!"**, cujo objetivo foi realizar a higienização e normalização de uma base de dados composta por personagens, criaturas e heróis de diferentes universos da cultura nerd.

O projeto foi desenvolvido utilizando **MongoDB**, aplicando técnicas de limpeza, padronização e modelagem de dados para transformar uma base inconsistente em uma estrutura organizada e relacional.

---

## 🎯 Objetivos

### Etapa 1 - Higienização de Dados

- Padronização de nomes de campos;
- Correção de capitalização e espaços extras;
- Conversão de tipos de dados;
- Tratamento de valores nulos, vazios e inconsistentes;
- Conversão de listas para arrays;
- Unificação de universos equivalentes;
- Remoção de registros duplicados;
- Geração da coleção `nerd_universe_clean`;
- Exportação dos dados higienizados para `nerd_universe_clean.json`.

### Etapa 2 - Normalização

Criação de coleções independentes e relacionadas por referências:

- `characters`
- `universes`
- `species`
- `equipment`
- `movies`

Também foram realizados testes de relacionamento utilizando o operador `$lookup`.

---

## 🛠️ Tecnologias Utilizadas

- MongoDB
- MongoDB Compass
- Aggregation Framework
- JSON

---

## 📁 Estrutura do Repositório

```text
├── datasets/
├── nerd_universe_clean.json
├── queries/
├── README.md
