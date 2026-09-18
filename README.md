# 🏋️ Sistema de Gestão de Academia — Redfit

## 📝 Descrição do Projeto

Este projeto consiste no desenvolvimento da modelagem conceitual de um sistema de gestão para uma rede de academias Redfit, com foco na organização e representação dos principais dados e processos envolvidos na operação de uma unidade de academia.

O projeto foi desenvolvido como parte da disciplina de **Desenvolvimento Assistido por IA e Low-Code**, tendo como objetivo aplicar conceitos de levantamento de requisitos, regras de negócio, modelagem de dados e desenvolvimento de uma estrutura organizada e escalável para representar as necessidades da organização.

A partir do levantamento realizado pelo grupo, foram identificadas entidades relacionadas aos alunos, planos, prontuários de saúde, avaliações físicas, agendamentos, instrutores, aulas/treinos, exercícios, itens de exercício e recepcionistas.

O modelo busca representar de forma estruturada os relacionamentos entre essas informações, permitindo uma futura implementação de um sistema de gestão para apoiar os processos da academia.

## 🎯 Objetivo do Projeto

O objetivo principal é desenvolver um modelo conceitual capaz de representar os principais processos e informações relacionados à gestão de uma academia.

Entre os aspectos considerados estão:

- Cadastro e gerenciamento de alunos;
- Controle de planos e modalidades contratadas;
- Registro de prontuários de saúde;
- Realização e acompanhamento de avaliações físicas;
- Agendamento de atividades;
- Gerenciamento de instrutores;
- Organização de aulas e treinos;
- Cadastro e organização de exercícios;
- Estruturação dos itens que compõem cada treino;
- Registro das atividades realizadas pela recepção.

## 🏢 Organização Analisada

**Organização:** Redfit

**Segmento:** Academias e serviços relacionados à atividade física.

O levantamento considera os processos e informações necessários para representar a operação de uma rede de academias, utilizando exemplos fictícios para dados pessoais e demais informações utilizadas na documentação.

> **Observação:** os dados pessoais apresentados nos exemplos da documentação são fictícios e não representam clientes, funcionários ou quaisquer outras pessoas reais.

## 📊 Modelo Entidade-Relacionamento

O Diagrama Entidade-Relacionamento (DER) foi elaborado a partir das entidades, atributos e relacionamentos identificados durante o levantamento.

### Principais entidades

- **Aluno**
- **Plano**
- **Prontuário de Saúde**
- **Agendamento**
- **Avaliação Física**
- **Instrutor**
- **Aula/Treino**
- **Aparelho**
- **Exercício**
- **Recepcionista**

O modelo contempla informações como identificação e dados cadastrais dos alunos, planos contratados, informações relacionadas à saúde, avaliações físicas, agendamentos, instrutores e estruturação dos treinos e exercícios.

## 📁 Estrutura do Repositório

```text
📦 skyfit-sistema-gestao-academia
├── 📄 README.md
├── 📁 docs
│   ├── dicionario-de-dados.pdf
└── 📁 DER
    └── diagrama-entidade-relacionamento.png
