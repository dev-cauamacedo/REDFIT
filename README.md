# RedFit — Modelagem de Banco de Dados

## Metadados

- **Aluno 1:** CAUÃ MACEDO SANTANA CABRAL — RGM: 48124338
- **Aluno 2:** GUSTAVO RIBEIRO TOTINO — RGM: 48263745
- **Aluno 3:** MARCO AURÉLIO DA SILVA LIRA — RGM: 47572701
- **Aluno 4:** PEDRO HENRIQUE DA SILVA — RGM: 48165191
- **Aluno 5:** SUELLEN DE ARAUJO SANTOS PIMENTA — RGM: 48122360
- **Curso:** Analise e Desenvolvimento de Sistema / Ciencia da Computação
- **Disciplina:** Modelagem de Banco de Dados
- **Projeto:** Modelagem de Banco de Dados — RedFit

---

# 1. Caracterização da Organização

## 1.1 Organização

A organização escolhida para o desenvolvimento do projeto é a **RedFit**, uma rede de academias.

A empresa possui diversas unidades e oferece serviços relacionados à prática de exercícios físicos, acompanhamento de alunos, elaboração de treinos, avaliação física e controle de acesso às unidades.

De acordo com as informações levantadas durante a pesquisa, a rede possui **26 unidades** e trabalha com diferentes modalidades de planos, permitindo diferentes níveis de acesso aos serviços oferecidos.

## 1.2 Contexto e necessidades da organização

A RedFit necessita controlar diversas informações relacionadas aos seus alunos, profissionais, unidades, planos, pagamentos, treinos, exercícios, equipamentos e acessos.

Entre as principais informações identificadas estão:

- Cadastro dos alunos;
- Dados pessoais e de contato;
- Endereço dos alunos;
- Informações de saúde;
- Planos contratados;
- Pagamentos;
- Controle de acesso às unidades;
- Instrutores;
- Recepcionistas;
- Treinos;
- Exercícios;
- Equipamentos;
- Avaliações físicas;
- Unidades da rede.

O cadastro do aluno possui informações como CPF, nome completo, data de nascimento, endereço e telefone. A data de nascimento também pode ser utilizada para determinar se o aluno é menor ou maior de idade.

Também foram identificadas informações relacionadas à saúde dos alunos, incluindo problemas cardíacos, problemas ósseos, problemas pulmonares ou respiratórios, doenças hereditárias e utilização de medicamentos.

## 1.3 Justificativa

A utilização de um banco de dados estruturado permite centralizar as informações da organização, reduzir inconsistências, facilitar consultas e possibilitar um melhor controle dos processos realizados pela academia.

A modelagem proposta busca representar os principais processos e informações envolvidos na operação da RedFit, permitindo que os dados sejam organizados de forma consistente e possibilitando futuras expansões do sistema.

---

# 2. Processos de Negócio

Os principais processos de negócio identificados para a organização são:

### Cadastro de aluno

O processo inicia-se com o cadastro do aluno no sistema, registrando informações pessoais, documentos, endereço e telefone.

### Gestão de planos

O sistema deve permitir registrar o plano contratado pelo aluno e suas respectivas características.

A pesquisa identificou planos com diferentes possibilidades de acesso às unidades e benefícios. A nomenclatura e algumas regras comerciais dos planos ainda precisam ser validadas com a organização. 

### Pagamentos

O sistema deve registrar os pagamentos realizados pelos alunos, incluindo valor, data, forma de pagamento e situação do pagamento.

### Controle de acesso

O acesso às unidades pode ocorrer por meio de identificação biométrica, como impressão digital ou reconhecimento facial, além de acessos realizados por meio de parceiros como TotalPass, mediante autorização. 

### Gestão de treinos

O sistema deve armazenar os treinos dos alunos, seus exercícios, séries, repetições, cargas, tempos e intervalos.

As alterações realizadas nos treinos podem ser mantidas para permitir o histórico de evolução do aluno.

### Avaliação física

O sistema deve permitir registrar informações relacionadas às avaliações físicas dos alunos, incluindo peso, gordura corporal, gordura visceral, quantidade de água e massa muscular.

### Gestão de profissionais

A organização possui instrutores e recepcionistas, sendo necessário armazenar informações cadastrais e profissionais desses colaboradores.

### Gestão de exercícios e equipamentos

Os exercícios são relacionados aos grupos musculares e aos equipamentos disponíveis na academia.

Entre os equipamentos identificados estão:

- Cabo/polia;
- Remada articulada;
- Banco inclinado;
- Banco reto;
- Leg press;
- Cadeira extensora.

---

# 3. Requisitos do Sistema

## 3.1 Requisitos Funcionais

### RF01 — Cadastro de aluno

O sistema deve permitir cadastrar alunos com nome completo, CPF, data de nascimento, endereço e telefone.

### RF02 — Consulta de aluno

O sistema deve permitir consultar os dados cadastrados dos alunos.

### RF03 — Atualização de aluno

O sistema deve permitir atualizar os dados cadastrais dos alunos.

### RF04 — Cadastro de plano

O sistema deve permitir cadastrar os planos disponibilizados pela organização.

### RF05 — Associação de plano

O sistema deve permitir associar um aluno a um plano.

### RF06 — Controle de pagamentos

O sistema deve permitir registrar os pagamentos realizados pelos alunos.

### RF07 — Consulta de pagamentos

O sistema deve permitir consultar o histórico de pagamentos dos alunos.

### RF08 — Controle de acesso

O sistema deve registrar os acessos dos alunos às unidades.

### RF09 — Cadastro de instrutores

O sistema deve permitir cadastrar instrutores com seus respectivos dados profissionais.

### RF10 — Cadastro de recepcionistas

O sistema deve permitir cadastrar recepcionistas.

### RF11 — Cadastro de treinos

O sistema deve permitir criar e armazenar treinos para os alunos.

### RF12 — Cadastro de exercícios

O sistema deve permitir cadastrar exercícios.

### RF13 — Associação de exercícios

O sistema deve permitir associar exercícios aos treinos.

### RF14 — Registro de séries

O sistema deve permitir registrar a quantidade de séries de cada exercício.

### RF15 — Registro de repetições

O sistema deve permitir registrar a quantidade de repetições de cada exercício.

### RF16 — Registro de carga

O sistema deve permitir registrar a carga utilizada em cada exercício.

### RF17 — Registro de intervalo

O sistema deve permitir registrar o intervalo entre as séries.

### RF18 — Cadastro de equipamentos

O sistema deve permitir cadastrar os equipamentos disponíveis nas unidades.

### RF19 — Cadastro de unidades

O sistema deve permitir cadastrar as unidades pertencentes à rede.

### RF20 — Avaliação física

O sistema deve permitir registrar informações referentes às avaliações físicas dos alunos.

### RF21 — Prontuário de saúde

O sistema deve permitir armazenar informações relacionadas à saúde dos alunos.

### RF22 — Histórico

O sistema deve permitir manter o histórico de informações que sofreram alterações, principalmente relacionadas aos treinos.

---

## 3.2 Requisitos Não Funcionais

### RNF01 — Segurança

O sistema deve proteger os dados pessoais e de saúde armazenados.

### RNF02 — Integridade

Os dados armazenados devem manter consistência entre as entidades relacionadas.

### RNF03 — Disponibilidade

O sistema deve estar disponível para utilização pelos funcionários autorizados durante o funcionamento da organização.

### RNF04 — Desempenho

As consultas e operações mais frequentes devem apresentar tempo de resposta adequado.

### RNF05 — Controle de acesso

O sistema deve restringir determinadas operações de acordo com o perfil do usuário.

### RNF06 — Escalabilidade

A estrutura do banco deve permitir a inclusão de novas unidades, alunos, profissionais, equipamentos e demais informações sem necessidade de alterações estruturais frequentes.

### RNF07 — Manutenibilidade

O banco de dados deve possuir estrutura organizada e padronizada, facilitando futuras alterações e manutenções.

### RNF08 — Confiabilidade

O sistema deve garantir o armazenamento correto das informações registradas.

---

# 4. Regras de Negócio

### RN01

Cada aluno deve possuir um CPF cadastrado.

### RN02

O cadastro do aluno deve conter nome completo, data de nascimento, endereço e telefone.

### RN03

A data de nascimento deve ser utilizada para determinar a idade do aluno.

### RN04

Um aluno pode possuir um plano contratado.

### RN05

Os pagamentos devem estar associados ao aluno correspondente.

### RN06

O acesso à unidade deve ser registrado no sistema.

### RN07

O acesso pode ocorrer por meio de identificação biométrica ou por parceiros autorizados.

### RN08

As alterações relacionadas aos treinos podem ser mantidas para histórico.

### RN09

Os exercícios devem estar associados aos respectivos treinos.

### RN10

Os equipamentos devem estar relacionados aos exercícios e grupos musculares correspondentes.

### RN11

Os instrutores devem possuir registro profissional CREF.

### RN12

As informações de saúde devem ser armazenadas no prontuário do aluno.

### RN13

Determinadas operações, como exclusões, devem ser realizadas por usuários autorizados.

### RN14

Alterações cadastrais devem ser realizadas por funcionários com permissão para essa operação.

As regras comerciais relacionadas aos planos, valores, benefícios, fidelidade, cancelamento e utilização de unidades ainda precisam ser confirmadas com a organização.

---

# 5. Dicionário de Dados Conceitual (Preliminar)

## 5.1 ALUNO

| Atributo | Descrição | Regra de Negócio |
|---|---|---|
| ID_ALUNO | Identificador único do aluno | Deve ser único |
| NM_ALUNO | Nome completo do aluno | Obrigatório |
| NR_CPF | CPF do aluno | Deve ser único |
| DT_NASCIMENTO | Data de nascimento | Obrigatório |
| DS_ENDERECO | Endereço do aluno | Obrigatório |
| NR_TELEFONE | Telefone do aluno | Deve ser informado |

## 5.2 PLANO

| Atributo | Descrição | Regra de Negócio |
|---|---|---|
| ID_PLANO | Identificador do plano | Deve ser único |
| NM_PLANO | Nome do plano | Obrigatório |
| VL_PLANO | Valor do plano | Deve possuir valor válido |
| DS_PLANO | Descrição do plano | Descreve as características do plano |
| IN_ATIVO | Situação do plano | Indica se está disponível |

## 5.3 PRONTUÁRIO_SAUDE

| Atributo | Descrição | Regra de Negócio |
|---|---|---|
| ID_PRONTUARIO | Identificador do prontuário | Deve ser único |
| ID_ALUNO | Aluno relacionado | Deve existir um aluno |
| IN_PROBLEMA_CARDIACO | Indicação de problema cardíaco | Informação de saúde |
| IN_PROBLEMA_OSSEO | Indicação de problema ósseo | Informação de saúde |
| IN_PROBLEMA_RESPIRATORIO | Indicação de problema respiratório | Informação de saúde |
| DS_DOENCA_HEREDITARIA | Doenças hereditárias | Informação de saúde |
| DS_MEDICAMENTO | Medicamentos utilizados | Informação de saúde |

## 5.4 INSTRUTOR

| Atributo | Descrição | Regra de Negócio |
|---|---|---|
| ID_INSTRUTOR | Identificador do instrutor | Deve ser único |
| NM_INSTRUTOR | Nome do instrutor | Obrigatório |
| NR_CPF | CPF do instrutor | Deve ser único |
| NR_TELEFONE | Telefone | Deve ser informado |
| DS_ESPECIALIDADE | Especialidade | Informação profissional |
| DS_CERTIFICACAO | Certificação/formação | Informação profissional |
| NR_CREF | Registro CREF | Deve ser informado |

## 5.5 RECEPCIONISTA

| Atributo | Descrição | Regra de Negócio |
|---|---|---|
| ID_RECEPCIONISTA | Identificador do recepcionista | Deve ser único |
| NM_RECEPCIONISTA | Nome do recepcionista | Obrigatório |
| NR_CPF | CPF | Deve ser único |
| NR_TELEFONE | Telefone | Deve ser informado |
| DS_ENDERECO | Endereço | Informação cadastral |

## 5.6 TREINO

| Atributo | Descrição | Regra de Negócio |
|---|---|---|
| ID_TREINO | Identificador do treino | Deve ser único |
| ID_ALUNO | Aluno relacionado | Deve existir um aluno |
| ID_INSTRUTOR | Instrutor responsável | Deve existir um instrutor |
| NM_TREINO | Nome do treino | Obrigatório |
| TP_TREINO | Tipo do treino | Deve representar o tipo definido pela organização |
| DS_TREINO | Descrição do treino | Descrição das atividades |
| DT_INICIO | Data de início | Obrigatória |
| DT_FIM | Data de término | Deve ser posterior à data de início |
| DS_OBJETIVO | Objetivo do treino | Descrição do objetivo |

## 5.7 ITEM_TREINO

| Atributo | Descrição | Regra de Negócio |
|---|---|---|
| ID_ITEM | Identificador do item | Deve ser único |
| ID_TREINO | Treino relacionado | Deve existir um treino |
| ID_EXERCICIO | Exercício relacionado | Deve existir um exercício |
| QT_SERIES | Quantidade de séries | Deve ser maior que zero |
| QT_REPETICOES | Quantidade de repetições | Deve ser maior que zero |
| VL_CARGA | Carga utilizada | Deve possuir valor válido |
| QT_TEMPO | Tempo do exercício | Unidade deve ser definida |
| QT_INTERVALO | Intervalo entre séries | Unidade deve ser definida |

## 5.8 EXERCICIO

| Atributo | Descrição | Regra de Negócio |
|---|---|---|
| ID_EXERCICIO | Identificador do exercício | Deve ser único |
| NM_EXERCICIO | Nome do exercício | Obrigatório |
| DS_EXERCICIO | Descrição do exercício | Descrição da execução |
| DS_GRUPO_MUSCULAR | Grupo muscular trabalhado | Deve ser informado |
| ID_EQUIPAMENTO | Equipamento utilizado | Deve existir quando aplicável |

## 5.9 UNIDADE

| Atributo | Descrição | Regra de Negócio |
|---|---|---|
| ID_UNIDADE | Identificador da unidade | Deve ser único |
| NM_UNIDADE | Nome da unidade | Obrigatório |
| DS_ENDERECO | Endereço da unidade | Deve ser informado |

A pesquisa identificou a existência de 26 unidades, porém os endereços individuais das unidades não foram disponibilizados no material analisado.

## 5.10 CHECK_IN

| Atributo | Descrição | Regra de Negócio |
|---|---|---|
| ID_CHECK_IN | Identificador do acesso | Deve ser único |
| ID_ALUNO | Aluno que realizou o acesso | Deve existir um aluno |
| ID_UNIDADE | Unidade acessada | Deve existir uma unidade |
| DT_HORA | Data e hora do acesso | Obrigatório |
| TP_ACESSO | Tipo de acesso | Deve representar a forma utilizada |
| TP_STATUS | Situação do acesso | Deve representar o resultado da validação |

## 5.11 PAGAMENTO

| Atributo | Descrição | Regra de Negócio |
|---|---|---|
| ID_PAGAMENTO | Identificador do pagamento | Deve ser único |
| ID_ALUNO | Aluno relacionado | Deve existir um aluno |
| DT_PAGAMENTO | Data do pagamento | Obrigatória |
| VL_PAGAMENTO | Valor pago | Deve ser maior que zero |
| TP_FORMA_PAGAMENTO | Forma de pagamento | Deve ser informada |
| TP_STATUS | Situação do pagamento | Deve indicar a situação atual |
| IN_RECORRENTE | Indica pagamento recorrente | Deve representar a recorrência |

## 5.12 EQUIPAMENTO

| Atributo | Descrição | Regra de Negócio |
|---|---|---|
| ID_EQUIPAMENTO | Identificador do equipamento | Deve ser único |
| NM_EQUIPAMENTO | Nome do equipamento | Obrigatório |
| DS_EQUIPAMENTO | Descrição do equipamento | Descrição do equipamento |
| ID_UNIDADE | Unidade onde está localizado | Deve existir uma unidade |

---

# 6. Modelagem Conceitual

A modelagem conceitual foi desenvolvida considerando as principais entidades identificadas durante o levantamento das informações da RedFit.

As principais entidades são:

- ALUNO
- PLANO
- PRONTUÁRIO_SAUDE
- INSTRUTOR
- RECEPCIONISTA
- TREINO
- ITEM_TREINO
- EXERCICIO
- UNIDADE
- CHECK_IN
- PAGAMENTO
- EQUIPAMENTO

## 6.1 Relacionamentos principais

### ALUNO e PLANO

Um aluno pode possuir um plano contratado, enquanto um plano pode estar associado a diversos alunos.

### ALUNO e PRONTUÁRIO_SAUDE

O prontuário de saúde pertence ao aluno e armazena informações relacionadas à sua saúde.

### ALUNO e TREINO

Um aluno pode possuir diversos treinos ao longo do tempo.

### INSTRUTOR e TREINO

Um instrutor pode ser responsável por diversos treinos.

### TREINO e ITEM_TREINO

Um treino é composto por diversos itens de treino.

### ITEM_TREINO e EXERCICIO

Cada item de treino está associado a um exercício.

### EXERCICIO e EQUIPAMENTO

Um exercício pode utilizar determinado equipamento.

### UNIDADE e EQUIPAMENTO

Uma unidade pode possuir diversos equipamentos.

### ALUNO e CHECK_IN

Um aluno pode possuir diversos registros de acesso.

### UNIDADE e CHECK_IN

Uma unidade pode possuir diversos registros de acesso.

### ALUNO e PAGAMENTO

Um aluno pode possuir diversos pagamentos registrados.

---

# 7. Diagrama Entidade-Relacionamento (DER)

O Diagrama Entidade-Relacionamento representa graficamente as entidades, atributos, relacionamentos e cardinalidades definidos durante a modelagem conceitual.

## 7.1 DER

A imagem do DER deve ser inserida neste ponto do README.

Exemplo:

![Diagrama Entidade-Relacionamento](./DER.png)

## 7.2 Entidades representadas

O DER deve representar as seguintes entidades:

- ALUNO
- PLANO
- PRONTUÁRIO_SAUDE
- INSTRUTOR
- RECEPCIONISTA
- TREINO
- ITEM_TREINO
- EXERCICIO
- UNIDADE
- CHECK_IN
- PAGAMENTO
- EQUIPAMENTO

## 7.3 Consistência e escalabilidade

O modelo foi estruturado buscando separar as principais informações da organização em entidades específicas.

Essa organização permite evitar a concentração de informações diferentes em uma única estrutura e facilita a manutenção e expansão do banco de dados.

A estrutura pode ser expandida posteriormente para contemplar novas unidades, alunos, profissionais, equipamentos, planos e outras funcionalidades.

---

# 8. Justificativa Técnica

A modelagem proposta foi construída a partir das informações levantadas sobre os processos da RedFit.

A separação das entidades permite organizar os dados de acordo com suas responsabilidades.

A entidade **ALUNO**, por exemplo, concentra os dados cadastrais do cliente, enquanto informações específicas de saúde são armazenadas no **PRONTUÁRIO_SAUDE**.

Da mesma forma, os dados referentes aos treinos foram separados em **TREINO**, **ITEM_TREINO** e **EXERCICIO**, permitindo representar a composição de um treino e os exercícios que fazem parte dele.

A utilização de entidades específicas para **UNIDADE**, **EQUIPAMENTO** e **CHECK_IN** também permite representar a operação de uma rede de academias com diversas unidades.

O modelo busca garantir:

- Organização dos dados;
- Integridade das informações;
- Redução de redundância;
- Facilidade de consulta;
- Facilidade de manutenção;
- Possibilidade de expansão futura;
- Separação adequada das responsabilidades de cada entidade.

---

# 9. Uso de Inteligência Artificial

A Inteligência Artificial foi utilizada como ferramenta de apoio durante o desenvolvimento do projeto, principalmente para auxiliar na organização das informações, identificação de entidades, definição de atributos e revisão da estrutura do modelo.

## 9.1 Ferramenta utilizada

**Ferramenta:** ChatGPT e Cloude.

## 9.2 Etapas em que a IA foi utilizada

A IA foi utilizada para:

- Organizar as informações obtidas durante a pesquisa;
- Identificar possíveis entidades;
- Sugerir atributos;
- Auxiliar na elaboração do dicionário de dados;
- Auxiliar na definição das regras de negócio;
- Revisar a estrutura do modelo;
- Identificar possíveis inconsistências.

## 9.3 Exemplos de prompts utilizados

> "Com base nas informações levantadas sobre uma rede de academias, identifique as principais entidades necessárias para um banco de dados."

> "Crie um dicionário de dados preliminar contendo entidade, atributo, descrição e regra de negócio."

> "Analise as entidades e relacionamentos de um modelo conceitual de banco de dados para uma academia."

> "Identifique possíveis inconsistências ou informações que precisam ser validadas antes da criação do DER."

## 9.4 Análise crítica das respostas

As respostas fornecidas pela Inteligência Artificial não foram utilizadas de maneira automática.

As informações foram comparadas com o material obtido durante a pesquisa e os pontos que não estavam confirmados foram identificados para validação.

Durante essa análise foram identificados alguns pontos que precisam ser confirmados, como:

- Nomenclatura atual dos planos;
- Valores atuais dos planos;
- Regras de cancelamento;
- Regras de fidelidade;
- Benefícios dos planos;
- Regras relacionadas ao acompanhante;
- Benefícios relacionados à bioimpedância;
- Necessidade da entidade de aula/agendamento;
- Unidade de medida para tempo e intervalo dos exercícios;
- Existência de determinados campos cadastrais.

## 9.5 Reflexão sobre o uso da IA

A utilização da Inteligência Artificial foi considerada uma ferramenta de apoio ao desenvolvimento do projeto, e não como substituição da análise dos integrantes.

A ferramenta auxiliou na organização e identificação de informações, porém foi necessário analisar criticamente as respostas e comparar as sugestões com os dados levantados durante a pesquisa.

Dessa forma, as decisões finais do modelo devem ser tomadas a partir das informações efetivamente confirmadas sobre a organização.
