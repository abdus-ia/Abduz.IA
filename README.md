# 👽 Abduz.IA — Sistema de Gestão de Abduções (SGA)

> Sistema proposto para organizar e controlar as operações de abdução da empresa interplanetária Abduz.IA.

![Status](https://img.shields.io/badge/Status-Em%20Discovery-blue)
![Projeto](https://img.shields.io/badge/Projeto-Acad%C3%AAmico-purple)
![Documentação](https://img.shields.io/badge/Documenta%C3%A7%C3%A3o-Em%20desenvolvimento-orange)

---

## 📑 Sumário

- [1. Sobre o Projeto](#-1-sobre-o-projeto)
- [2. Objetivos](#-2-objetivos)
- [3. Contexto e Problemas](#-3-contexto-e-problemas)
- [4. Stakeholders e Atores](#-4-stakeholders-e-atores)
- [5. Requisitos Funcionais](#-5-requisitos-funcionais)
- [6. Requisitos Não Funcionais](#-6-requisitos-não-funcionais)
- [7. Regras de Negócio](#-7-regras-de-negócio)
- [8. Restrições](#-8-restrições)
- [9. Questões em Aberto](#-9-questões-em-aberto)
- [10. Decisões Registradas](#-10-decisões-registradas)
- [11. Backlog e Planejamento](#-11-backlog-e-planejamento)
- [12. Estratégia de Branches](#-12-estratégia-de-branches)
- [13. Organização do Projeto](#-13-organização-do-projeto)
- [14. Integrantes](#-14-integrantes)
- [15. Histórico de Atualizações](#-15-histórico-de-atualizações)

---

## 📌 1. Sobre o Projeto

O **SGA — Sistema de Gestão de Abduções** é um projeto acadêmico que tem como objetivo organizar as operações da empresa interplanetária Abduz.IA.

A proposta surgiu da necessidade de substituir o gerenciamento atual, realizado por meio do AlienZap, por um sistema que permita controlar as abduções, os recursos envolvidos, as autorizações e o histórico das missões.

O projeto encontra-se na fase de **Discovery**, dedicada ao levantamento, à análise e à consolidação dos requisitos antes do início das etapas posteriores do desenvolvimento.

### Identificação

| Informação | Descrição |
|---|---|
| Projeto | Abduz.IA |
| Sistema | Sistema de Gestão de Abduções (SGA) |
| Categoria | Projeto acadêmico de desenvolvimento de software |
| Local | Sorocaba — SP |
| Fase atual | Discovery |
| Repositório | Abduz.IA |

---

## 🎯 2. Objetivos

### Objetivo geral

Organizar e controlar as operações de abdução da Abduz.IA, permitindo o gerenciamento das missões, dos aliens, dos humanos, das naves, das escalas de trabalho e das autorizações necessárias.

### Objetivos específicos

- Centralizar as informações relacionadas às operações.
- Permitir o cadastro e a consulta dos recursos envolvidos nas missões.
- Organizar o agendamento das abduções.
- Evitar conflitos entre missões e a utilização inadequada de naves.
- Registrar e consultar o histórico das missões.
- Controlar as autorizações necessárias para as operações.
- Gerenciar a disponibilidade dos aliens e das naves.
- Organizar as escalas de trabalho.
- Melhorar a rastreabilidade das operações e das decisões tomadas.

---

## 🌌 3. Contexto e Problemas

A Abduz.IA realiza abduções temporárias de humanos para pesquisas científicas.

Atualmente, a organização dessas operações ocorre por meio do AlienZap, situação que apresenta problemas operacionais.

### Problemas identificados

- Duas naves podem tentar abduzir o mesmo humano.
- Humanos podem ser devolvidos em locais incorretos.
- Naves em manutenção podem ser utilizadas indevidamente.
- Podem ocorrer conflitos de horários entre missões.
- Existe dificuldade para consultar o histórico das abduções.
- Existe dificuldade para identificar os participantes e os responsáveis pelas autorizações das missões.

O SGA pretende oferecer suporte à organização dessas atividades, considerando as regras de negócio e os requisitos levantados durante o Discovery.

---

## 👥 4. Stakeholders e Atores

### Stakeholders

Os stakeholders são as partes interessadas no projeto e em seus resultados.

| Identificador | Stakeholder | Interesse |
|---|---|---|
| STK-001 | Empresa Abduz.IA | Organização e controle das operações. |
| STK-002 | Gerência da empresa | Administração, controle e autorização das operações. |
| STK-003 | Equipes operacionais | Execução e acompanhamento das missões. |
| STK-004 | Equipe de desenvolvimento | Levantamento, documentação e desenvolvimento do sistema. |
| STK-005 | Professor responsável | Acompanhamento e avaliação acadêmica do projeto. |

### Atores

| Identificador | Ator | Responsabilidade geral |
|---|---|---|
| ACT-001 | Gerente | Gerenciamento da empresa e participação nas autorizações previstas nas regras de negócio. |
| ACT-002 | Comandante | Coordenação das missões e participação nas autorizações pertinentes. |
| ACT-003 | Piloto | Operação da nave e participação nas atividades operacionais. |
| ACT-004 | Restante da equipe | Participação nas atividades das missões, conforme suas permissões. |

As permissões detalhadas de cada ator deverão ser documentadas e validadas durante o Discovery.

---

## ⚙️ 5. Requisitos Funcionais

Os requisitos funcionais descrevem os serviços e comportamentos que o sistema deverá oferecer.

| ID | Requisito | Descrição |
|---|---|---|
| RF01 | Cadastro de entidades | O sistema deverá permitir cadastrar aliens, humanos e naves. |
| RF02 | Agendamento de missões | O sistema deverá permitir agendar missões. |
| RF03 | Agendamento de manutenções | O sistema deverá permitir agendar manutenções nas naves. |
| RF04 | Histórico de missões | O sistema deverá armazenar e permitir consultar o histórico de missões passadas. |
| RF05 | Consulta de naves em reparo | O sistema deverá permitir consultar as naves em reparo. |
| RF06 | Consulta da escala | O sistema deverá permitir consultar a escala de trabalho. |
| RF07 | Autorizações | O sistema deverá consultar e comparar as autorizações necessárias para agendar ou realizar missões. |
| RF08 | Missões em andamento | O sistema deverá permitir consultar as missões em andamento. |
| RF09 | Alteração da escala | O sistema deverá permitir alterar a escala de trabalho. |
| RF10 | Consulta de naves disponíveis | O sistema deverá permitir consultar as naves disponíveis. |

**Observação:** os requisitos acima correspondem ao levantamento funcional inicial. Sua especificação detalhada, incluindo permissões, exceções e critérios de aceitação, deverá ser consolidada durante o Discovery.

---

## 🛡️ 6. Requisitos Não Funcionais

Os requisitos não funcionais descrevem características, condições e restrições relacionadas ao funcionamento do sistema.

| ID | Requisito | Descrição registrada |
|---|---|---|
| RNF01 | Usabilidade | O sistema deverá ser intuitivo, com aprendizado rápido. |
| RNF02 | Disponibilidade | O sistema deverá apresentar alta disponibilidade. |
| RNF03 | Compatibilidade operacional | O sistema deverá funcionar em diferentes naves, independentemente do modelo ou computador. |
| RNF04 | Desempenho e capacidade | O documento estabelece tempo de resposta de até 1 segundo, tempo médio de digitação de 15 segundos e capacidade de armazenamento de registros por 10 anos. |
| RNF05 | Confiabilidade | O sistema deverá funcionar sem falhas durante 99% do tempo de utilização. |
| RNF06 | Sistema operacional | O sistema deverá funcionar em Linux. |
| RNF07 | Distribuição e atualização | O sistema será obtido por compartilhamento de um arquivo executável, e sua atualização será disponibilizada dentro do próprio executável. |
| RNF08 | Identidade visual | As cores deverão ser baseadas nos códigos `#4BC19A`, `#03F594` e `#FBFBFB`. |
| RNF09 | Integrações | O sistema não deverá se comunicar com outros sistemas. |
| RNF10 | Persistência e acesso | O sistema deverá armazenar os dados em um banco de dados e possuir quatro tipos de acesso: comandante, gerente, piloto e restante da equipe. |

**Pontos de atenção:** alguns requisitos precisam de esclarecimento para que possam ser validados objetivamente. Entre eles estão a definição de alta disponibilidade, a medição do tempo de resposta, o significado de tempo médio de digitação e a interpretação da meta de 99% de funcionamento sem falhas.

Os requisitos serão refinados antes das etapas posteriores do projeto.

---

## 📜 7. Regras de Negócio

As regras de negócio estabelecem condições que deverão ser respeitadas durante as operações.

| ID | Regra | Descrição |
|---|---|---|
| BR-001 | Vínculo de nave e humano | Uma nave por pessoa, conforme a regra registrada no levantamento inicial. |
| BR-002 | Autorização de missões | As missões deverão possuir as autorizações necessárias. |
| BR-003 | Local da abdução | O local da abdução deverá ser registrado. |
| BR-004 | Condição de trabalho do alien | Um alien doente não poderá trabalhar. |

### Regras complementares registradas durante o Discovery

As seguintes regras foram discutidas durante o refinamento dos requisitos:

- Cada alien poderá estar vinculado a apenas um turno por dia.
- A substituição de participantes deverá ser registrada.
- Quando houver substituição do comandante, será necessária a autorização dele e do gerente.
- A regra de autorização conjunta deverá ser aplicada às situações de substituição abrangidas pela decisão registrada.
- Um alien deverá estar disponível para participar de uma missão.
- Quando não houver alien disponível para a substituição necessária, a missão deverá permanecer em espera até que exista um alien disponível.
- Quando uma nave apresentar uma falha que exija manutenção, ela deverá ser encaminhada imediatamente para manutenção.
- A ocorrência de falha na nave poderá levar ao cancelamento da missão, conforme o fluxo operacional definido durante o Discovery.
- A falha na abdução deverá ser registrada como uma ocorrência da missão.
- A situação final do humano deverá considerar o que aconteceu durante a missão, incluindo a possibilidade de falecimento.

Os fluxos completos, as condições específicas e as permissões associadas a essas regras deverão ser consolidados na documentação detalhada do Discovery.

---

## 🚧 8. Restrições

As restrições identificadas até o momento incluem:

| ID | Restrição | Origem |
|---|---|---|
| RES-001 | O sistema deverá funcionar em Linux. | RNF06 |
| RES-002 | O sistema não deverá se comunicar com outros sistemas. | RNF09 |
| RES-003 | O sistema deverá possuir quatro tipos de acesso. | RNF10 |
| RES-004 | A distribuição deverá ocorrer por meio de um arquivo executável compartilhado. | RNF07 |
| RES-005 | As cores da interface deverão seguir a identidade visual especificada. | RNF08 |

Essas restrições representam o conteúdo registrado nos requisitos e poderão ser refinadas conforme os esclarecimentos obtidos durante o Discovery.

---

## ❓ 9. Questões em Aberto

As questões abaixo foram registradas no levantamento inicial e precisam ser esclarecidas ou relacionadas às decisões tomadas posteriormente.

| ID | Questão | Status |
|---|---|---|
| OPEN-001 | Uma nave poderá transportar apenas um humano por missão? | A esclarecer. |
| OPEN-002 | Uma nave poderá realizar apenas uma missão por vez? | A esclarecer. |
| OPEN-003 | Qual será o processo completo entre a solicitação e a partida da nave? | A esclarecer. |
| OPEN-004 | Qual será o procedimento quando uma missão falhar? | Refinar os fluxos e as consequências. |
| OPEN-005 | Um humano poderá ser abduzido mais de uma vez? | A esclarecer. |
| OPEN-006 | Quais serão as permissões específicas de cada tipo de usuário? | A esclarecer. |
| OPEN-007 | Quais condições deverão ser verificadas para considerar uma nave disponível? | A esclarecer. |
| OPEN-008 | Quais validações serão necessárias para liberar uma nave após manutenção? | A esclarecer. |
| OPEN-009 | Quais serão os critérios para considerar um alien disponível para uma missão? | Refinar as condições já discutidas. |
| OPEN-010 | Quais serão os critérios objetivos para validar disponibilidade, desempenho e confiabilidade? | A esclarecer. |

As questões deverão ser atualizadas conforme o grupo confirmar decisões. Uma questão resolvida deverá deixar de ser tratada como pendência, mantendo-se o registro da decisão correspondente.

---

## 🧭 10. Decisões Registradas

Esta seção deve reunir decisões confirmadas pelo grupo durante o Discovery.

| ID | Decisão | Situação |
|---|---|---|
| DEC-001 | Cada alien poderá estar vinculado a apenas um turno por dia. | Registrada durante o Discovery. |
| DEC-002 | As substituições deverão ser registradas. | Registrada durante o Discovery. |
| DEC-003 | A substituição do comandante exigirá autorização dele e do gerente. | Registrada durante o Discovery. |
| DEC-004 | Um alien deverá estar disponível para participar da missão. | Registrada durante o Discovery. |
| DEC-005 | Uma missão deverá aguardar quando não houver alien disponível para a substituição necessária. | Registrada durante o Discovery. |
| DEC-006 | Uma nave que apresentar falha que exija manutenção deverá ser encaminhada imediatamente para manutenção. | Registrada durante o Discovery. |

As decisões deverão ser mantidas alinhadas às regras de negócio e aos requisitos relacionados.

Novas decisões deverão receber novos identificadores, sem reutilizar os IDs existentes.

---

## 📋 11. Backlog e Planejamento

O backlog reúne o trabalho necessário para a evolução do projeto.

### Organização inicial do backlog

| ID | Item | Categoria |
|---|---|---|
| GIT-001 | Criar e configurar o repositório. | Gestão |
| GIT-002 | Criar as branches `main` e `develop`. | Gestão |
| GIT-003 | Criar e configurar o board. | Gestão |
| GIT-004 | Cadastrar e organizar os itens do backlog. | Gestão |
| DOC-001 | Consolidar os requisitos funcionais. | Discovery |
| DOC-002 | Consolidar os requisitos não funcionais. | Discovery |
| DOC-003 | Consolidar as regras de negócio e restrições. | Discovery |
| DOC-004 | Consolidar stakeholders e atores. | Discovery |
| DOC-005 | Registrar decisões e questões em aberto. | Discovery |
| DOC-006 | Consolidar os fluxos e estados das missões. | Discovery |
| DOC-007 | Definir critérios de aceitação. | Discovery |
| DOC-008 | Consolidar a documentação no README.md. | Documentação |
| PLAN-001 | Planejar a primeira Sprint. | Planejamento |
| PLAN-002 | Definir critérios de conclusão das tarefas. | Planejamento |

Esta lista é uma proposta inicial de organização. Os itens deverão ser cadastrados no board, receber responsáveis e ter seus critérios de aceitação definidos.

### Sprint 01 — Organização e consolidação do Discovery

**Objetivo:** organizar o ambiente de trabalho do projeto e consolidar a documentação de requisitos.

**Duração:** a definir pelo grupo.

**Entregas previstas:**

- Repositório organizado.
- Branches `main` e `develop` disponíveis.
- Board configurado.
- Backlog inicial registrado.
- Requisitos funcionais e não funcionais consolidados.
- Regras de negócio e restrições documentadas.
- Questões em aberto registradas.
- README.md atualizado.
- Planejamento e critérios de conclusão documentados.

A Sprint deverá ser acompanhada pelo board. Somente os itens efetivamente concluídos e validados deverão ser considerados finalizados.

---

## 🌿 12. Estratégia de Branches

O projeto utiliza duas branches principais para organizar o fluxo de trabalho.

| Branch | Finalidade |
|---|---|
| `main` | Manter a versão principal e estável do projeto. |
| `develop` | Integrar as alterações em desenvolvimento antes de sua incorporação à versão principal. |

### Fluxo de trabalho

1. As alterações deverão ser realizadas de maneira organizada.
2. Quando necessário, poderão ser criadas branches específicas para tarefas.
3. As alterações deverão ser revisadas antes da integração.
4. A branch `develop` deverá reunir as alterações aprovadas para desenvolvimento.
5. A integração à `main` deverá ocorrer após a validação correspondente.

O grupo deverá manter o repositório e a documentação alinhados ao estado real do projeto.

---

## 🗂️ 13. Organização do Projeto

A documentação oficial do projeto deverá estar acessível a partir deste README.

Conforme o projeto evoluir, poderão ser adicionados documentos complementares para organizar os artefatos produzidos.

Os principais artefatos previstos incluem:

- Documento de requisitos.
- Catálogo de requisitos funcionais.
- Catálogo de requisitos não funcionais.
- Regras de negócio.
- Registro de decisões.
- Registro de questões em aberto.
- Backlog do produto.
- Planejamento das Sprints.
- Critérios de aceitação.

O conteúdo deverá representar o estado consolidado do projeto, evitando contradições entre os documentos, as issues e o board.

---

## 👨‍🚀 14. Integrantes

Equipe responsável pelo projeto:

- Guilherme Felicidade
- Gustavo Ferreira
- João Vitor Mangili
- Lucas Couto
- Renan Muniz
- Willen Favarin

---

## 📝 15. Histórico de Atualizações

| Versão | Descrição |
|---|---|
| 1.0 | Organização inicial da documentação do projeto e consolidação dos requisitos levantados. |

O histórico deverá ser atualizado conforme mudanças relevantes forem aprovadas e incorporadas à documentação.

---

<p align="center">
  <strong>Abduz.IA — Organizando as operações além da Terra. 👽</strong>
</p>
