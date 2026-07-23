# Clean Life — Decision Log

## Purpose

Este documento registra decisões importantes tomadas durante o desenvolvimento do Clean Life.

Cada decisão relevante deve possuir uma justificativa.

As justificativas podem ser fundamentadas em:

- literatura científica;
- princípios de IHC;
- necessidades observadas no usuário;
- requisitos de segurança e privacidade;
- restrições técnicas;
- experimentos realizados no produto;
- hipóteses que precisam ser validadas.

O objetivo deste documento é manter a rastreabilidade das decisões e evitar que escolhas importantes sejam feitas apenas com base em preferências pessoais ou tendências tecnológicas.

---

# Decision 001 — Evidence-Based Product Decisions

## Date

2026-07-23

## Decision

Toda decisão importante do Clean Life deve possuir uma justificativa explícita.

A justificativa pode ser baseada em:

- literatura científica;
- princípios de Interação Humano-Computador (IHC);
- necessidades observadas no usuário;
- experimentos realizados no produto;
- requisitos de segurança;
- requisitos de privacidade;
- restrições técnicas;
- hipóteses de produto.

## Rationale

O Clean Life pretende ser um projeto de software pessoal, mas também um projeto de aprendizado e experimentação em engenharia de software, inteligência artificial, segurança de dados, automação e IHC.

Para manter a qualidade e a coerência do projeto, decisões importantes não devem ser tomadas apenas por preferência pessoal ou por tendências tecnológicas.

A adoção de uma regra de justificativa permite que o projeto seja analisado de maneira crítica e que decisões futuras possam ser revisadas quando novas evidências surgirem.

## Consequences

Decisões importantes deverão ser registradas neste documento.

Quando uma decisão for baseada em uma hipótese ainda não validada, isso deverá ser explicitamente indicado.

O projeto poderá revisar decisões anteriores caso novas evidências demonstrem que uma abordagem diferente é mais adequada.

## Status

Accepted

---

# Decision 002 — Clean Life as a Decision-Support System

## Date

2026-07-23

## Decision

O Clean Life deve ser projetado como um sistema de apoio à decisão pessoal, e não como um sistema que assume o controle da vida do usuário.

O objetivo principal é aumentar a capacidade do usuário de:

- compreender sua rotina;
- identificar prioridades;
- perceber padrões;
- avaliar alternativas;
- refletir sobre suas escolhas;
- tomar decisões mais conscientes.

## Rationale

O Clean Life terá acesso potencial a informações pessoais e poderá utilizar inteligência artificial para analisar padrões e fazer recomendações.

Existe o risco de que um sistema altamente automatizado passe de uma ferramenta de apoio para uma ferramenta que determina o comportamento do usuário.

A proposta do Clean Life é diferente.

O sistema deve ajudar o usuário a responder perguntas como:

> Como será meu dia?

> O que preciso fazer?

> O que é mais importante agora?

> Estou avançando em direção às minhas metas?

> O que pode acontecer se eu continuar seguindo minha rotina atual?

A decisão final deve permanecer com o usuário.

## Consequences

A IA será utilizada prioritariamente para:

- analisar;
- sugerir;
- explicar;
- apresentar alternativas;
- identificar padrões;
- simular cenários.

A IA não deve realizar automaticamente mudanças relevantes na rotina do usuário sem autorização apropriada.

Sugestões importantes devem ser apresentadas de maneira compreensível e, quando possível, explicar os motivos que levaram à recomendação.

## Related Principles

- User Autonomy
- AI Should Be Explainable
- Predictions Must Be Conditional
- Show Trade-offs

## Status

Accepted

---

# Decision 003 — Personalization Through Gradual Learning

## Date

2026-07-23

## Decision

A personalização do Clean Life deve ocorrer progressivamente, com base na combinação de:

1. informações fornecidas explicitamente pelo usuário;
2. padrões observados ao longo do uso;
3. feedback do usuário sobre sugestões;
4. histórico de planejamento e execução.

O sistema não deve presumir que conhece o usuário desde o primeiro uso.

## Rationale

O objetivo do Clean Life é adaptar-se a diferentes tipos de usuários e rotinas.

Um fisiculturista, por exemplo, pode considerar treino e alimentação como prioridades fundamentais.

Um estudante pode considerar estudos e provas como prioridades principais.

Um profissional pode priorizar trabalho e compromissos.

Portanto, o sistema não deve impor uma definição universal de uma "vida ideal".

Ele deve aprender quais aspectos são importantes para cada usuário.

## Example

O sistema pode observar que uma determinada atividade costuma levar mais tempo do que o usuário inicialmente estima.

Depois de observar esse padrão repetidamente, pode sugerir:

> Essa atividade costuma levar aproximadamente 2h45 para você.

> Deseja reservar esse período?

Da mesma forma, o sistema pode aprender preferências relacionadas a:

- horários de trabalho;
- horários de estudo;
- duração de descanso;
- atividades restauradoras;
- padrões de adiamento;
- períodos de maior produtividade;
- preferências de planejamento.

## Consequences

O sistema deverá diferenciar:

- informação fornecida pelo usuário;
- comportamento observado;
- padrão identificado;
- hipótese;
- recomendação.

A personalização deverá ser gradual.

O usuário deverá poder corrigir ou rejeitar interpretações feitas pelo sistema.

## Related Principles

- Personalization Must Be Gradual
- Learn From Reality
- Correlation Is Not Causation
- User Autonomy

## Status

Accepted

---

# Decision 004 — Clean Life Must Prioritize Sustainable Personal Organization

## Date

2026-07-23

## Decision

O Clean Life não deve ter como objetivo principal maximizar produtividade ou quantidade de tarefas concluídas.

Seu objetivo deve ser ajudar o usuário a construir uma rotina mais consciente, realista e sustentável.

O sistema deve considerar que uma vida organizada envolve diferentes dimensões, incluindo:

- trabalho;
- estudo;
- metas;
- compromissos;
- descanso;
- tempo livre;
- hábitos;
- interesses pessoais;
- finanças;
- outras dimensões definidas pelo usuário.

## Rationale

A dificuldade central identificada durante o processo de definição do Clean Life não é simplesmente "ter muitas tarefas".

O problema envolve a dificuldade de equilibrar:

- o que precisa ser feito;
- o que é importante;
- o que pode esperar;
- quanto tempo realmente existe;
- quanto o usuário consegue realizar;
- quando é necessário descansar.

O usuário deve conseguir terminar um dia sabendo não apenas quantas tarefas realizou, mas também compreendendo se sua rotina está contribuindo para seus objetivos.

## Consequences

O Clean Life deverá considerar descanso e tempo livre como componentes legítimos do planejamento.

O sistema não deverá interpretar automaticamente tarefas não concluídas como fracasso.

Quando o usuário estiver sobrecarregado, o sistema poderá:

- identificar a sobrecarga;
- sugerir priorização;
- sugerir adiamento de tarefas de menor prioridade;
- lembrar o usuário de seus objetivos e motivos;
- apresentar alternativas.

O sistema deve evitar criar uma cultura de produtividade constante.

## Related Principles

- Life Is More Than Tasks
- Rest Is Part of the Plan
- Attention Is a Limited Resource
- Quality Over Quantity

## Status

Accepted

---

# Decision 005 — Initial MVP Scope

## Date

2026-07-23

## Decision

O MVP inicial do Clean Life será concentrado em seis capacidades principais:

1. Daily Overview
2. Tasks and Commitments
3. Goals
4. Adaptive Planning
5. Daily Reflection
6. Weekly Review

A inteligência artificial será integrada a essas capacidades como uma camada de apoio à decisão, em vez de ser implementada inicialmente como um chatbot independente.

## Rationale

O MVP deve possuir um escopo limitado para permitir que a hipótese central do produto seja validada antes da expansão para outros domínios.

A hipótese central é:

> Um sistema que combina planejamento diário, metas pessoais, planejamento adaptativo e reflexão pode ajudar usuários a construir rotinas mais realistas e compreender melhor seu progresso.

As seis capacidades selecionadas estão diretamente relacionadas às três perguntas centrais que o Clean Life deve ajudar o usuário a responder:

> Como será meu dia?

> O que preciso fazer?

> Estou caminhando na direção que desejo?

O escopo inicial não inclui como funcionalidades centrais:

- comunidade;
- gerenciamento financeiro;
- planejamento de refeições;
- integrações externas extensivas;
- gamificação avançada;
- agentes autônomos de IA.

Essas funcionalidades poderão ser avaliadas em versões futuras.

## MVP Capabilities

### 1. Daily Overview

Permitir que o usuário compreenda rapidamente:

- tarefas do dia;
- compromissos;
- prioridades;
- carga planejada;
- metas relacionadas.

### 2. Tasks and Commitments

Permitir o gerenciamento de:

- tarefas;
- compromissos;
- duração estimada;
- prioridade;
- data;
- status de execução.

### 3. Goals

Permitir que o usuário:

- crie metas;
- acompanhe progresso;
- defina prazos;
- registre os motivos das metas;
- associe atividades às metas.

### 4. Adaptive Planning

Permitir que o sistema sugira:

- horários para atividades;
- reorganização da agenda;
- adiamento de tarefas de menor prioridade;
- redistribuição de atividades.

As sugestões deverão considerar, quando possível:

- agenda;
- duração estimada;
- histórico;
- prioridade;
- metas;
- capacidade planejada.

O usuário deverá manter o controle sobre as decisões.

### 5. Daily Reflection

Permitir que o usuário compreenda:

- o que realizou;
- o que não realizou;
- o que foi adiado;
- possíveis motivos;
- diferenças entre planejamento e execução.

### 6. Weekly Review

Permitir uma visão consolidada da semana, incluindo:

- progresso de metas;
- execução de tarefas;
- tarefas adiadas;
- tempo planejado;
- tempo de trabalho;
- tempo livre;
- padrões observados.

## AI Role

A IA deverá ser integrada aos fluxos principais do produto.

Exemplos:

### Planejamento

> Onde devo colocar esta tarefa?

### Sobrecarga

> Meu dia está muito cheio?

### Priorização

> O que devo fazer primeiro?

### Reflexão

> O que aconteceu esta semana?

### Metas

> Estou avançando em direção ao meu objetivo?

### Cenários futuros

> Se eu continuar vivendo dessa forma, como pode ser meu próximo mês?

A IA deverá atuar como uma camada de inteligência e apoio à decisão.

## Consequences

O MVP terá um escopo menor e deverá ser mais fácil de:

- desenvolver;
- testar;
- avaliar;
- validar com usuários;
- estudar tecnicamente.

A arquitetura inicial deverá permitir expansão futura sem exigir a implementação imediata de todas as funcionalidades previstas no Feature Universe.

O sistema deverá armazenar dados estruturados suficientes para permitir futura personalização e análise assistida por IA.

O Adaptive Planning será uma das áreas tecnicamente mais complexas do MVP e deverá ser desenvolvido de maneira incremental.

## Related Principles

- User Autonomy
- Life Is More Than Tasks
- Data Should Create Understanding
- Personalization Must Be Gradual
- AI Should Be Explainable
- Quality Over Quantity

## Status

Proposed

---

# Decision Status Legend

## Proposed

Decisão sugerida, mas ainda não validada ou aprovada definitivamente.

## Accepted

Decisão aprovada e adotada pelo projeto.

## Rejected

Decisão analisada e descartada.

## Superseded

Decisão anteriormente aceita que foi substituída por uma nova decisão.

## Experimental

Decisão temporária que depende de experimentação ou validação.

---

# Decision Review Process

Uma decisão pode ser revisada quando:

- novas evidências científicas forem encontradas;
- testes com usuários apresentarem resultados diferentes;
- experimentos do produto contradizerem a hipótese;
- surgirem novas restrições técnicas;
- houver novos riscos de segurança ou privacidade;
- a visão do produto for alterada.

Quando uma decisão aceita for modificada, a decisão anterior não deve ser apagada.

Ela deve ser marcada como:

> Superseded

E uma nova decisão deve registrar a mudança.

Isso mantém o histórico e a rastreabilidade do projeto.
