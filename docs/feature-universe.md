# Clean Life — Feature Universe

## 1. Purpose

Este documento reúne o universo de funcionalidades consideradas para o Clean Life.

O objetivo não é definir o MVP neste momento.

Todas as funcionalidades são inicialmente consideradas hipóteses de produto e deverão ser avaliadas posteriormente com base em:

- problema que resolvem;
- necessidade do usuário;
- alinhamento com a visão do produto;
- evidências de pesquisa;
- impacto esperado;
- complexidade de implementação;
- riscos de segurança e privacidade;
- dependências técnicas.

A presença de uma funcionalidade neste documento não significa que ela será implementada.

---

# 2. Feature Classification

As funcionalidades serão posteriormente classificadas em:

- Core MVP
- MVP Expansion
- Future
- Experimental
- Rejected

## Core MVP

Funcionalidades essenciais para testar a hipótese central do Clean Life.

## MVP Expansion

Funcionalidades importantes, mas que podem ser implementadas após a validação inicial do produto.

## Future

Funcionalidades compatíveis com a visão do produto, mas que não são prioritárias.

## Experimental

Funcionalidades que dependem de experimentação ou validação adicional.

## Rejected

Funcionalidades que não demonstraram valor suficiente, apresentam riscos excessivos ou não estão alinhadas à visão do produto.

---

# 3. Daily Overview

## Description

Uma visão inicial do dia que permita ao usuário compreender rapidamente sua situação atual.

## Possible Features

- Visualizar tarefas do dia.
- Visualizar compromissos.
- Visualizar prioridades.
- Visualizar metas relacionadas ao dia.
- Visualizar refeições planejadas.
- Visualizar períodos de descanso.
- Visualizar tempo livre estimado.
- Visualizar progresso das metas.
- Visualizar carga planejada.
- Visualizar possíveis conflitos.
- Visualizar recomendações da IA.
- Visualizar informações importantes em uma interface calma e não sobrecarregada.

## User Questions

A experiência deve ajudar o usuário a responder:

> Como será meu dia?

> O que preciso fazer?

> Tenho algum compromisso?

> O que é realmente importante hoje?

> Meu dia parece realista?

---

# 4. Tasks

## Description

Gerenciamento de atividades que o usuário deseja ou precisa realizar.

## Possible Features

- Criar tarefa.
- Editar tarefa.
- Excluir tarefa.
- Concluir tarefa.
- Adiar tarefa.
- Reagendar tarefa.
- Definir prioridade.
- Definir duração estimada.
- Registrar duração real.
- Definir data.
- Definir horário.
- Definir categoria.
- Definir recorrência.
- Associar tarefa a uma meta.
- Associar tarefa a um hábito.
- Adicionar observações.
- Definir dependências entre tarefas.
- Registrar motivo de não conclusão.

## Possible Task States

- Planned
- In Progress
- Completed
- Postponed
- Rescheduled
- Cancelled
- Skipped

---

# 5. Calendar and Commitments

## Description

Gerenciamento de compromissos e eventos que ocupam períodos específicos da rotina.

## Possible Features

- Criar compromisso.
- Editar compromisso.
- Excluir compromisso.
- Definir horário.
- Definir duração.
- Definir local.
- Adicionar descrição.
- Detectar conflitos.
- Visualizar compromissos do dia.
- Visualizar compromissos da semana.
- Visualizar compromissos do mês.
- Integrar com calendários externos no futuro.

## Future Integrations

Possíveis integrações futuras:

- Google Calendar
- Apple Calendar
- Microsoft Outlook Calendar

---

# 6. Goals

## Description

Permitir que o usuário acompanhe objetivos importantes em diferentes horizontes de tempo.

## Possible Features

- Criar meta.
- Definir prazo.
- Definir prioridade.
- Definir progresso.
- Definir métrica.
- Definir frequência.
- Associar tarefas à meta.
- Associar hábitos à meta.
- Registrar o motivo da meta.
- Visualizar progresso.
- Revisar meta.
- Ajustar meta.
- Pausar meta.
- Abandonar meta.
- Substituir meta.

## Goal Horizons

- Diário
- Semanal
- Mensal
- Trimestral
- Anual
- Longo prazo

---

# 7. Personal Meaning and Motivation

## Description

Permitir que o usuário registre os motivos e valores associados às suas metas e atividades importantes.

## Possible Features

- Registrar "Por que isso importa?"
- Registrar valores pessoais.
- Registrar objetivos de longo prazo.
- Registrar visão de futuro.
- Associar uma razão a uma meta.
- Associar uma razão a uma atividade.
- Revisitar motivos periodicamente.
- Exibir motivos em momentos relevantes.

## Example

Goal:

> Terminar a faculdade.

Why:

> Quero construir uma carreira que me permita trabalhar com tecnologia e ter mais liberdade.

Possible Future Interaction:

> Você disse que deseja concluir a faculdade porque busca construir uma carreira com mais liberdade.

---

# 8. Habits

## Description

Acompanhamento de comportamentos recorrentes sem transformar o sistema em uma ferramenta de pressão ou culpa.

## Possible Features

- Criar hábito.
- Definir frequência.
- Definir horário preferencial.
- Definir flexibilidade.
- Registrar execução.
- Registrar não execução.
- Visualizar histórico.
- Identificar padrões.
- Reorganizar hábito.
- Pausar hábito.
- Ajustar frequência.
- Retomar hábito.

## Design Consideration

O sistema deve evitar tratar a interrupção de uma sequência como fracasso.

O objetivo deve ser apoiar a retomada e adaptação da rotina.

---

# 9. Adaptive Planning

## Description

Planejamento que considera a rotina real do usuário e não apenas os horários teoricamente disponíveis.

## Possible Features

- Sugerir horários para tarefas.
- Detectar conflitos.
- Identificar períodos disponíveis.
- Considerar duração estimada.
- Considerar duração histórica.
- Considerar prioridade.
- Considerar compromissos.
- Considerar períodos de descanso.
- Considerar metas.
- Reorganizar tarefas.
- Sugerir adiamento de tarefas de baixa prioridade.
- Sugerir migração de tarefas para outro dia.
- Solicitar confirmação antes de alterar o planejamento.

## Example

> Seu dia está acima da sua carga habitual.

> Você deseja mover uma tarefa de baixa prioridade para amanhã?

Options:

- Mover para amanhã.
- Escolher outro dia.
- Manter hoje.
- Ignorar sugestão.

---

# 10. Capacity Estimation

## Description

Estimar a carga planejada do usuário considerando seu histórico e contexto.

## Possible Inputs

- Quantidade de tarefas.
- Duração estimada.
- Duração histórica.
- Quantidade de compromissos.
- Tempo de trabalho.
- Tempo de estudo.
- Tempo de descanso.
- Intensidade estimada da atividade.
- Padrões históricos.

## Possible Outputs

- Carga baixa.
- Carga moderada.
- Carga elevada.
- Possível sobrecarga.

## Example

> Seu planejamento de hoje está acima do seu padrão recente de carga.

> Deseja revisar suas prioridades?

## Important Limitation

A capacidade estimada é uma aproximação baseada nos dados disponíveis e não representa uma avaliação médica ou psicológica.

---

# 11. Time Estimation

## Description

Aprender a diferença entre o tempo estimado pelo usuário e o tempo realmente utilizado.

## Possible Features

- Registrar duração estimada.
- Registrar duração real.
- Calcular diferença.
- Calcular média histórica.
- Identificar atividades subestimadas.
- Ajustar sugestões futuras.
- Informar o usuário sobre diferenças recorrentes.

## Example

> Você estimou 2 horas para essa atividade.

> Nas últimas cinco vezes, ela levou em média 2h45.

> Deseja reservar aproximadamente 3 horas?

---

# 12. Contextual Reminders

## Description

Lembretes baseados não apenas em horário, mas também no contexto da intenção.

## Possible Trigger Types

- Horário.
- Data.
- Evento.
- Conclusão de atividade.
- Início de atividade.
- Localização, caso autorizado.
- Mudança de contexto.

## Example

> Você está saindo do trabalho.

> Você pediu para ser lembrado de comprar leite quando estivesse a caminho de casa.

---

# 13. Notifications

## Description

Sistema de notificações adaptável e controlável.

## Possible Features

- Lembretes de tarefas.
- Lembretes de compromissos.
- Lembretes de refeições.
- Lembretes de hábitos.
- Lembretes de metas.
- Alertas de conflitos.
- Alertas de possível sobrecarga.
- Sugestões da IA.
- Resumos diários.
- Resumos semanais.

## Design Considerations

Notificações devem considerar:

- relevância;
- urgência;
- contexto;
- preferência do usuário;
- frequência;
- horário.

O sistema deve permitir ao usuário controlar os tipos de notificações recebidas.

---

# 14. Meals

## Description

Organização de refeições e lembretes relacionados à alimentação.

## Possible Features

- Registrar refeições.
- Criar refeições recorrentes.
- Definir horários.
- Criar lembretes.
- Registrar refeições realizadas.
- Registrar refeições não realizadas.
- Integrar refeições ao planejamento diário.

## Future Possibilities

- Integração com metas alimentares.
- Planejamento alimentar.
- Integração com aplicativos externos.

---

# 15. Rest and Recovery

## Description

Apoiar o usuário na organização de períodos de descanso e recuperação.

## Possible Features

- Registrar períodos de descanso.
- Registrar atividades de descanso.
- Registrar percepção após descanso.
- Identificar atividades associadas à recuperação percebida.
- Sugerir períodos de descanso.
- Sugerir atividades de recuperação.
- Registrar preferências de descanso.

## Possible Recovery Activities

- Dormir.
- Ler.
- Meditar.
- Caminhar.
- Assistir a filmes.
- Jogar.
- Socializar.
- Hobbies.
- Atividades definidas pelo usuário.

## Design Consideration

O sistema deve evitar assumir que uma atividade é restauradora para todos os usuários.

A personalização deve ocorrer com base nas preferências e feedback do próprio usuário.

---

# 16. Free Time

## Description

Ajudar o usuário a utilizar períodos livres de maneira intencional.

## Possible Features

- Detectar períodos livres.
- Mostrar tempo livre disponível.
- Criar lista de atividades desejadas.
- Cadastrar filmes.
- Cadastrar livros.
- Cadastrar jogos.
- Cadastrar hobbies.
- Cadastrar atividades sociais.
- Sugerir atividades.

## Example

> Você tem aproximadamente 1h30 livre.

> Algumas opções que você salvou:

- Assistir ao filme X.
- Ler o livro Y.
- Jogar Z.
- Caminhar.
- Fazer nada e descansar.

## Design Principle

Sugestões devem preservar a autonomia do usuário.

---

# 17. Personal Metrics

## Description

Permitir que o usuário escolha quais aspectos da própria vida deseja acompanhar.

## Possible Metrics

- Horas de trabalho.
- Horas de estudo.
- Horas de sono.
- Tempo livre.
- Treinos.
- Leitura.
- Meditação.
- Hábitos.
- Humor percebido.
- Energia percebida.
- Descanso.
- Gastos.
- Receitas.

## Possible Features

- Criar métrica personalizada.
- Definir unidade.
- Registrar valor.
- Definir frequência.
- Visualizar histórico.
- Visualizar tendências.
- Comparar períodos.

---

# 18. Finances

## Description

Apoiar o acompanhamento financeiro pessoal.

## Possible Features

- Registrar ganhos.
- Registrar gastos.
- Categorizar gastos.
- Criar categorias personalizadas.
- Registrar gastos recorrentes.
- Visualizar gastos mensais.
- Visualizar receitas mensais.
- Criar metas financeiras.
- Comparar períodos.
- Refletir sobre gastos.

## Future Possibilities

- Importação automática de transações.
- Integração bancária.
- Open Finance.
- Análise financeira assistida por IA.

## Security Consideration

Informações financeiras exigem nível elevado de proteção e devem ser avaliadas separadamente antes da implementação.

---

# 19. Daily Reflection

## Description

Permitir que o usuário encerre o dia compreendendo o que aconteceu.

## Possible Questions

> O que consegui realizar?

> O que ficou pendente?

> Por que ficou pendente?

> Algo inesperado aconteceu?

> Como me senti com minha rotina?

> Preciso reorganizar alguma atividade?

## Possible Features

- Resumo automático.
- Tarefas concluídas.
- Tarefas pendentes.
- Compromissos realizados.
- Metas relacionadas.
- Tempo de trabalho.
- Tempo de descanso.
- Reflexão livre.

---

# 20. Weekly Review

## Description

Permitir uma visão consolidada da semana.

## Possible Insights

- Progresso das metas.
- Tarefas concluídas.
- Tarefas adiadas.
- Tarefas canceladas.
- Horas de trabalho.
- Horas de estudo.
- Tempo livre.
- Descanso.
- Hábitos.
- Gastos.
- Receitas.

## Possible Questions

> O que funcionou?

> O que não funcionou?

> O que causou sobrecarga?

> O que deveria mudar?

> Quais metas estão avançando?

> Alguma meta precisa ser revisada?

---

# 21. Monthly Review

## Description

Permitir reflexão de maior escala sobre a vida do usuário.

## Possible Insights

- Metas concluídas.
- Metas não concluídas.
- Evolução das metas.
- Distribuição de tempo.
- Trabalho.
- Estudo.
- Descanso.
- Tempo livre.
- Finanças.
- Hábitos.
- Padrões identificados.

## Possible Questions

> O que eu conquistei este mês?

> O que não consegui realizar?

> O que aprendi sobre minha rotina?

> Minhas metas continuam fazendo sentido?

> Minhas metas são viáveis?

> O que devo mudar no próximo mês?

---

# 22. Personal Pattern Learning

## Description

Permitir que o sistema aprenda padrões individuais ao longo do tempo.

## Possible Patterns

- Horários de maior produtividade.
- Duração média de atividades.
- Horários de descanso.
- Preferências de descanso.
- Frequência de adiamento.
- Padrões de sobrecarga.
- Preferências de planejamento.
- Padrões de trabalho.
- Padrões de estudo.
- Padrões de lazer.

## Design Principle

O sistema deve diferenciar:

- comportamento observado;
- associação;
- hipótese;
- conclusão.

Não deve apresentar automaticamente correlação como causalidade.

---

# 23. AI Assistant

## Description

Uma camada de inteligência artificial para auxiliar o usuário na compreensão e organização da rotina.

## Possible Capabilities

- Responder perguntas sobre a rotina.
- Sugerir horários.
- Sugerir reorganização.
- Explicar conflitos.
- Identificar padrões.
- Sugerir descanso.
- Sugerir atividades.
- Ajudar na definição de metas.
- Ajudar na revisão de metas.
- Gerar resumos.
- Ajudar em reflexões.
- Explorar cenários futuros.

## AI Interaction Principle

A IA deve:

- explicar;
- sugerir;
- permitir correção;
- permitir rejeição;
- reconhecer incerteza;
- preservar autonomia.

---

# 24. What-if Scenarios

## Description

Permitir que o usuário explore possíveis consequências de mudanças em sua rotina.

## Example Questions

> E se eu trabalhar 5 horas a mais por semana?

> E se eu estudar mais?

> E se eu reduzir meus treinos?

> E se eu dormir mais?

> E se eu mudar minha meta?

## Possible Outputs

- Mudança estimada no tempo disponível.
- Impacto estimado em outras atividades.
- Impacto nas metas.
- Mudança no tempo livre.
- Possível alteração na carga planejada.

## Design Principle

Resultados devem ser apresentados como cenários condicionais.

Exemplo:

> Se sua rotina continuar semelhante ao padrão observado recentemente...

---

# 25. Life Trade-offs

## Description

Ajudar o usuário a visualizar os custos e benefícios de suas decisões.

## Example

Decisão:

> Trabalhar 5 horas adicionais.

Possible Impact:

- +5h trabalho.
- Possível aumento de renda.
- -5h tempo livre.
- Menor disponibilidade para descanso.
- Possível conflito com estudo.

## Design Principle

O sistema deve informar o usuário, não decidir por ele.

---

# 26. Future Projection

## Description

Permitir visualizar possíveis tendências futuras baseadas no comportamento observado.

## Example

> Se você continuar mantendo seu ritmo atual de estudo, sua meta poderá ser concluída aproximadamente em quatro meses.

## Important Limitation

Projeções não devem ser apresentadas como certezas.

---

# 27. Purpose and Identity

## Description

Conectar atividades e metas às razões pessoais do usuário.

## Possible Features

- Registrar valores.
- Registrar propósito.
- Registrar identidade desejada.
- Registrar visão de futuro.
- Associar metas a valores.
- Relembrar propósito em momentos relevantes.

## Example

> Por que você está fazendo isso?

> Porque quero me tornar um profissional capaz de construir minha própria carreira.

---

# 28. Privacy and Data Control

## Description

Permitir que o usuário tenha controle sobre seus próprios dados.

## Possible Features

- Visualizar dados armazenados.
- Editar dados.
- Exportar dados.
- Excluir dados.
- Excluir conta.
- Controlar permissões.
- Controlar dados utilizados pela IA.
- Visualizar integrações.
- Revogar integrações.

---

# 29. Security

## Possible Features

- Autenticação segura.
- Autorização.
- Criptografia em trânsito.
- Criptografia em repouso.
- Gerenciamento seguro de sessões.
- Controle de acesso.
- Auditoria.
- Backup seguro.
- Recuperação de conta.
- Proteção contra abuso.

## Important Principle

Segurança deve ser considerada desde a arquitetura inicial e não adicionada apenas posteriormente.

---

# 30. Community

## Description

Possível camada social para usuários compartilharem experiências e objetivos.

## Possible Features

- Comunidades temáticas.
- Grupos de interesse.
- Compartilhamento de metas.
- Discussões.
- Apoio entre usuários.
- Desafios.
- Experiências compartilhadas.

## Current Position

A comunidade não faz parte do núcleo inicial do Clean Life.

Sua inclusão deverá ser avaliada futuramente.

---

# 31. Automation

## Description

Automatizar tarefas repetitivas quando houver benefício claro para o usuário.

## Possible Features

- Criar tarefas recorrentes.
- Criar lembretes automaticamente.
- Gerar resumos.
- Atualizar métricas.
- Reorganizar sugestões.
- Detectar conflitos.
- Sincronizar calendários.
- Processar eventos externos.

## Design Principle

Automação deve ser:

- transparente;
- reversível;
- controlável;
- explicável.

---

# 32. Integrations

## Possible Future Integrations

- Google Calendar.
- Apple Calendar.
- Microsoft Outlook.
- Serviços de música.
- Serviços de filmes.
- Aplicativos de leitura.
- Aplicativos de exercícios.
- Serviços financeiros.
- Serviços de saúde.

## Important Consideration

Integrações aumentam o valor do produto, mas também aumentam:

- complexidade;
- dependência de terceiros;
- superfície de ataque;
- riscos de privacidade;
- custos de manutenção.

---

# 33. Experimental Ideas

Funcionalidades que podem ser exploradas futuramente:

- Life State.
- Índice de sobrecarga pessoal.
- Índice de equilíbrio de rotina.
- Simulação de cenários.
- Recomendações adaptativas.
- Detecção de mudanças de rotina.
- Previsão de conflitos.
- Planejamento automático.
- Agentes de IA.
- Automação contextual.

Essas funcionalidades não devem ser consideradas requisitos do MVP sem validação adicional.

---

# 34. Out of Scope for Initial MVP

Inicialmente, as seguintes funcionalidades não são consideradas essenciais para validar a hipótese central do produto:

- Comunidade.
- Rede social.
- Integrações bancárias.
- Open Finance.
- Marketplace.
- Gamificação avançada.
- Agentes autônomos.
- Automação irreversível.
- Integrações externas extensivas.
- Recursos sociais complexos.

Essas funcionalidades podem ser reconsideradas após a validação do produto.

---

# 35. Open Questions

As seguintes questões ainda precisam ser investigadas:

1. Qual é a quantidade mínima de dados necessária para gerar sugestões úteis?

2. Quanto tempo o sistema precisa observar o usuário antes de começar a personalizar sugestões?

3. Como medir a "capacidade" diária de maneira útil sem criar uma falsa precisão?

4. Como evitar que o acompanhamento de metas gere ansiedade ou pressão?

5. Como determinar quando uma notificação realmente merece interromper o usuário?

6. Como apresentar previsões sem gerar falsa confiança?

7. Como permitir que o usuário compreenda e controle o modelo de personalização?

8. Quais dados devem ser processados localmente?

9. Quais dados podem ser enviados para modelos de IA externos?

10. Como proteger informações altamente sensíveis?

11. Quais funcionalidades realmente diferenciam o Clean Life de ferramentas existentes?

12. A comunidade adicionaria valor real ou desviaria o produto de sua proposta central?

---

# 36. Next Step

O próximo documento deverá avaliar este universo de funcionalidades e classificá-las com base em:

- problema;
- valor;
- alinhamento com a visão;
- evidência;
- complexidade;
- risco;
- dependências.

O objetivo será definir o escopo inicial do Clean Life e construir o MVP.
