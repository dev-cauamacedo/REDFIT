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
- **Item_Exercício**
- **Exercício**
- **Recepcionista**

O modelo contempla informações como identificação e dados cadastrais dos alunos, planos contratados, informações relacionadas à saúde, avaliações físicas, agendamentos, instrutores e estruturação dos treinos e exercícios.

## 🔐 Regras e Restrições

Durante o levantamento, foram consideradas regras e restrições necessárias para manter a consistência das informações representadas pelo modelo.

Entre elas estão:

- Cada aluno deve possuir uma identificação única;
- Cada plano deve possuir uma identificação própria;
- Informações de alunos e funcionários devem ser armazenadas de forma organizada;
- Os relacionamentos entre alunos, planos, avaliações, instrutores e treinos devem respeitar as cardinalidades definidas no DER;
- Um treino pode ser composto por diferentes itens de exercício;
- Cada item de exercício deve estar relacionado a um exercício cadastrado;
- Informações de saúde devem estar vinculadas ao aluno correspondente;
- Os exemplos utilizados na documentação não devem conter dados reais de pessoas.

## 🔄 Processos de Negócio

O levantamento dos processos busca representar como as principais atividades da academia ocorrem e quais informações são utilizadas em cada etapa.

Entre os processos considerados estão:

- Matrícula do aluno;
- Contratação de plano;
- Atendimento e registro pela recepção;
- Agendamento de atividades;
- Avaliação física;
- Orientação pelo instrutor;
- Criação e organização de treinos;
- Associação de exercícios aos treinos.

Os processos são representados por meio de fluxogramas na documentação da Entrega 1.

## ⚙️ Requisitos do Sistema

### Requisitos Funcionais

O sistema deverá permitir, entre outras funcionalidades:

- Cadastrar alunos;
- Consultar e atualizar dados cadastrais;
- Cadastrar planos;
- Associar alunos aos seus respectivos planos;
- Registrar informações do prontuário de saúde;
- Registrar avaliações físicas;
- Realizar e consultar agendamentos;
- Cadastrar instrutores;
- Cadastrar exercícios;
- Criar e organizar aulas/treinos;
- Associar exercícios aos treinos;
- Registrar informações relacionadas ao atendimento da recepção.

### Requisitos Não Funcionais

O sistema deverá considerar:

- **Segurança:** proteção das informações armazenadas;
- **Integridade:** manutenção da consistência dos relacionamentos entre os dados;
- **Escalabilidade:** estrutura preparada para inclusão de novos alunos, planos, exercícios e unidades;
- **Usabilidade:** organização das informações de maneira clara para os usuários;
- **Privacidade:** proteção de informações pessoais e de saúde dos alunos.

## 🤖 Uso de Inteligência Artificial

A Inteligência Artificial foi utilizada como ferramenta de apoio durante o desenvolvimento do projeto.

Os usos de IA incluem:

- Pesquisa e levantamento de informações;
- Organização de ideias;
- Apoio na elaboração da documentação;
- Revisão e melhoria textual;
- Apoio na identificação e análise de entidades, atributos e relacionamentos;
- Auxílio na estruturação do README e demais documentos do projeto.

Todas as utilizações de IA devem ser registradas conforme solicitado na documentação da **Entrega 1**, contendo:

- Ferramenta utilizada;
- Motivação para utilização;
- Prompt utilizado;
- Resposta obtida;
- Fontes verificadas, quando aplicável;
- Trechos corrigidos ou modificados;
- Reflexão crítica sobre a utilização da IA.

A IA foi utilizada como ferramenta de apoio, sendo necessária a análise e validação das informações pelo grupo.

## 📁 Estrutura do Repositório

```text
📦 projeto-academia
├── 📄 README.md
├── 📁 docs
│   ├── levantamento.md
│   ├── processos.md
│   ├── requisitos.md
│   ├── regras-de-negocio.md
│   ├── dicionario-de-dados.md
│   ├── justificativa-tecnica.md
│   └── uso-de-ia.md
│
└── 📁 DER
    └── diagrama-entidade-relacionamento.png
