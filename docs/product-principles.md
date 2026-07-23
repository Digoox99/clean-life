# Clean Life — Product Principles

## 1. Purpose

Este documento define os princípios que orientam as decisões de produto e design do Clean Life.

Os princípios funcionam como critérios para avaliar novas funcionalidades, comportamentos do sistema e decisões de interface.

Uma funcionalidade pode ser tecnicamente possível e ainda assim não pertencer ao Clean Life.

O produto deve priorizar qualidade, utilidade e coerência com sua visão central.

---

# 2. Core Principles

## PRINCIPLE-001 — User Autonomy

### Principle

O Clean Life deve aumentar a capacidade do usuário de compreender sua rotina e tomar decisões, e não assumir o controle de sua vida.

### Application

A IA pode:

- analisar informações;
- identificar padrões;
- sugerir ações;
- sugerir horários;
- apresentar cenários;
- explicar recomendações.

A IA não deve tomar decisões importantes unilateralmente.

Sempre que uma sugestão tiver impacto relevante na rotina do usuário, o usuário deve poder:

- aceitar;
- rejeitar;
- modificar;
- ignorar.

### Rationale

O Clean Life é concebido como um sistema de apoio à decisão. A autonomia do usuário é uma característica central do produto.

### Related Research

- Human-AI Interaction
- Human Autonomy
- Calm Technology

---

## PRINCIPLE-002 — Life Is More Than Tasks

### Principle

O sucesso do usuário não deve ser medido apenas pela quantidade de tarefas concluídas.

### Application

O sistema deve considerar, quando relevante:

- objetivos;
- compromissos;
- trabalho;
- estudo;
- descanso;
- tempo livre;
- hábitos;
- atividades pessoais;
- recursos financeiros;
- outros aspectos definidos pelo usuário.

### Rationale

Uma rotina produtiva não é necessariamente uma rotina saudável ou sustentável.

O Clean Life deve ajudar o usuário a compreender sua vida como um sistema integrado, e não apenas como uma lista de tarefas.

### Related Research

- Slow Technology
- Personal Informatics
- Recovery Research

---

## PRINCIPLE-003 — Attention Is a Limited Resource

### Principle

A atenção do usuário deve ser tratada como um recurso limitado.

### Application

O Clean Life não deve competir constantemente pela atenção do usuário.

Notificações e interrupções devem ser:

- relevantes;
- contextuais;
- controláveis;
- proporcionais à importância da informação.

O sistema deve evitar notificações desnecessárias.

### Rationale

O Clean Life deve ajudar a organizar a vida sem se tornar mais uma fonte de distração ou sobrecarga.

### Related Research

- Calm Technology
- Notification and Interruptibility Research

---

## PRINCIPLE-004 — Data Should Create Understanding

### Principle

O objetivo principal da coleta de dados pessoais deve ser ajudar o usuário a compreender sua própria rotina.

### Application

O sistema deve buscar transformar dados em:

- contexto;
- reflexão;
- padrões;
- aprendizado;
- decisões.

O Clean Life não deve coletar dados apenas para aumentar a quantidade de informações armazenadas.

### Example

Em vez de mostrar apenas:

> Você trabalhou 40 horas esta semana.

O sistema pode ajudar o usuário a refletir:

> Você trabalhou 40 horas esta semana, 8 horas acima da sua média recente.

### Rationale

Dados pessoais possuem maior valor quando ajudam o usuário a compreender sua situação e tomar decisões melhores.

### Related Research

- Personal Informatics
- Slow Technology

---

## PRINCIPLE-005 — Rest Is Part of the Plan

### Principle

Descanso deve ser considerado parte legítima do planejamento da vida.

### Application

O sistema não deve tratar o descanso simplesmente como "tempo não utilizado".

Quando apropriado, o Clean Life deve considerar:

- períodos de descanso;
- recuperação;
- tempo livre;
- atividades prazerosas;
- atividades percebidas pelo usuário como restauradoras.

### Rationale

Uma rotina sustentável precisa considerar recuperação e bem-estar, e não apenas produção.

### Related Research

- Recovery Research
- Slow Technology

---

## PRINCIPLE-006 — Goals Are Adaptable

### Principle

Metas devem poder ser revisadas, ajustadas ou abandonadas.

### Application

O usuário deve poder:

- criar uma meta;
- acompanhar seu progresso;
- revisar sua meta;
- ajustar sua meta;
- pausar sua meta;
- abandonar sua meta;
- substituir sua meta.

O sistema não deve interpretar automaticamente o não cumprimento de uma meta como fracasso.

### Rationale

A realidade do usuário pode mudar.

O Clean Life deve ajudar o usuário a avaliar se uma meta continua relevante e viável.

### Related Research

- Goal Setting
- Self-Regulation
- Personal Informatics

---

## PRINCIPLE-007 — Personalization Must Be Gradual

### Principle

O Clean Life deve aprender sobre o usuário progressivamente.

O sistema não deve presumir que conhece o usuário desde o primeiro uso.

### Application

O sistema pode aprender gradualmente:

- duração real das atividades;
- padrões de trabalho;
- horários preferenciais;
- hábitos;
- preferências de descanso;
- padrões de planejamento;
- preferências de notificações.

As sugestões devem melhorar conforme mais informações são observadas.

### Rationale

Personalização precisa ser construída a partir de dados e feedback do próprio usuário.

### Related Research

- Personal Informatics
- Human-AI Interaction

---

## PRINCIPLE-008 — AI Should Be Explainable

### Principle

Sugestões relevantes da IA devem ser compreensíveis para o usuário.

### Application

Quando apropriado, o sistema deve explicar:

- por que uma sugestão foi feita;
- quais informações foram consideradas;
- quais premissas foram utilizadas;
- qual o grau de incerteza da sugestão.

### Example

Em vez de:

> Faça essa tarefa amanhã às 14h.

O sistema pode apresentar:

> Sugestão: amanhã às 14h.
>
> Motivos:
>
> - Você costuma ter disponibilidade nesse horário.
> - A tarefa requer aproximadamente 2 horas.
> - Não há compromissos registrados nesse período.
> - Você normalmente realiza atividades semelhantes nesse horário.

### Rationale

O usuário deve compreender a lógica das recomendações para poder avaliá-las e corrigi-las.

### Related Research

- Human-AI Interaction
- Explainable AI

---

## PRINCIPLE-009 — Correlation Is Not Causation

### Principle

O Clean Life deve distinguir observações e associações de relações causais.

### Application

O sistema pode informar:

> Nos últimos meses, seus períodos de maior produtividade ocorreram frequentemente após noites de maior duração de sono.

O sistema não deve afirmar automaticamente:

> Dormir mais causou seu aumento de produtividade.

### Rationale

Dados pessoais observacionais não são suficientes, por si só, para estabelecer causalidade.

### Related Research

- Personal Informatics
- Personal Data Analysis

---

## PRINCIPLE-010 — Capacity Is Not the Same as Available Time

### Principle

O sistema deve reconhecer que possuir tempo disponível não significa necessariamente possuir capacidade suficiente para executar uma atividade.

### Application

O Clean Life pode considerar, de maneira experimental:

- quantidade de tarefas;
- duração estimada;
- carga planejada;
- intensidade das atividades;
- histórico de execução;
- períodos de trabalho;
- períodos de descanso.

O sistema pode identificar possíveis situações de sobrecarga.

### Important Limitation

Estimativas de capacidade são aproximações e não representam avaliações médicas ou psicológicas.

### Rationale

O objetivo é ajudar o usuário a construir planejamentos mais realistas.

### Related Research

- Cognitive Load
- Mental Workload
- Personal Planning

---

## PRINCIPLE-011 — Learn From Reality

### Principle

O Clean Life deve aprender com a diferença entre o planejamento e o comportamento observado.

### Application

O sistema pode comparar:

> Tempo estimado

com:

> Tempo realizado

Ao longo do tempo, pode utilizar essas informações para melhorar futuras sugestões.

### Example

O usuário estima:

> Estudar TCC — 2 horas.

Após várias execuções, o sistema observa:

> Duração média: 2h45.

O sistema pode sugerir:

> Esta atividade costuma levar aproximadamente 2h45 para você. Deseja reservar esse período?

### Rationale

Planejamentos baseados no histórico pessoal podem ser mais realistas do que estimativas genéricas.

### Related Research

- Personal Informatics
- Time Estimation
- Adaptive Systems

---

## PRINCIPLE-012 — Contextual Reminders

### Principle

Lembretes devem considerar o contexto da intenção sempre que possível.

### Application

O sistema pode utilizar diferentes tipos de gatilho:

- horário;
- data;
- evento;
- localização, quando autorizado;
- conclusão de outra atividade;
- mudança de contexto.

### Example

Em vez de:

> 18:00 — Comprar leite.

O sistema pode lembrar:

> Você está saindo do trabalho. Você pediu para ser lembrado de comprar leite quando estivesse a caminho de casa.

### Rationale

Lembretes contextuais podem estar mais alinhados com a intenção original do usuário do que lembretes exclusivamente baseados em horário.

### Related Research

- Prospective Memory
- Contextual Reminders

---

## PRINCIPLE-013 — Predictions Must Be Conditional

### Principle

Previsões sobre o futuro devem ser apresentadas como cenários condicionais, não como certezas.

### Application

O sistema pode apresentar:

> Se sua rotina continuar semelhante às últimas seis semanas, sua meta provavelmente será concluída em aproximadamente quatro meses.

O sistema deve evitar:

> Você terminará sua meta em quatro meses.

### Rationale

O futuro depende de variáveis que podem mudar.

### Related Research

- Personal Informatics
- Decision Support
- What-if Analysis

---

## PRINCIPLE-014 — Show Trade-offs

### Principle

O Clean Life deve ajudar o usuário a compreender os possíveis custos e benefícios de suas escolhas.

### Application

Quando possível, o sistema pode apresentar impactos estimados.

### Example

O usuário decide adicionar cinco horas de trabalho por semana.

O sistema pode apresentar:

> Possíveis impactos:
>
> + 5h de trabalho
>
> + Maior renda potencial
>
> - 5h de tempo livre
>
> - Menor disponibilidade para descanso

### Rationale

Decisões pessoais frequentemente envolvem trade-offs.

O objetivo do Clean Life não é decidir pelo usuário, mas tornar os custos de uma escolha mais visíveis.

### Related Research

- Decision Support
- What-if Analysis
- Human-AI Interaction

---

## PRINCIPLE-015 — Quality Over Quantity

### Principle

O Clean Life deve priorizar qualidade e utilidade sobre quantidade de funcionalidades.

### Application

Uma funcionalidade só deve ser adicionada quando:

1. Resolve um problema real;
2. Está alinhada à visão do produto;
3. Possui justificativa;
4. Pode ser implementada com qualidade;
5. Não adiciona complexidade desnecessária.

### Rationale

O objetivo do projeto é construir uma experiência coerente e útil, e não acumular funcionalidades.

### Related Research

- Product Vision
- Research Foundations

---

# 3. Decision Rule

Toda decisão importante do Clean Life deve possuir uma justificativa.

A justificativa pode ser baseada em:

- literatura científica;
- princípios de IHC;
- necessidade observada do usuário;
- restrições técnicas;
- segurança;
- privacidade;
- experimento realizado no produto.

Quando uma decisão não possuir evidência suficiente, ela deve ser registrada como hipótese ou decisão experimental.

---

# 4. Decision Hierarchy

Quando houver conflito entre objetivos, o Clean Life deve priorizar:

1. Segurança e privacidade;
2. Autonomia do usuário;
3. Utilidade real;
4. Clareza e compreensão;
5. Bem-estar e sustentabilidade da rotina;
6. Personalização;
7. Eficiência;
8. Conveniência.

---

# 5. Product Philosophy

O Clean Life não deve ajudar o usuário simplesmente a fazer mais.

Ele deve ajudá-lo a:

- compreender melhor sua rotina;
- decidir melhor onde colocar sua energia;
- proteger seu tempo e atenção;
- manter seus objetivos visíveis;
- reconhecer seus limites;
- descansar sem culpa;
- refletir sobre suas escolhas;
- adaptar seus planos à realidade.

A pergunta central do produto não é:

> "Como fazer o usuário produzir mais?"

É:

> "Como ajudar o usuário a viver de maneira mais consciente e intencional?"
