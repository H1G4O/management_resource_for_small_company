# Plataforma de Gestão de Tarefas para Times Pequenos

Trabalho de Experiência do Usuário (UX) apresentado ao Centro Universitário [FEI](https://portal.fei.edu.br/), como parte dos requisitos da disciplina de Experiência do Usuário e Front-End (CCP310) do curso de Ciência da Computação, orientado pelo Prof. Dr. [Fagner de Assis Moura Pimentel](https://github.com/fagnerpimentel).

---

## Componentes do Grupo

- Higor Augusto  
- Lucas Pimentel  

---

## Resumo

Uma aplicação focada em gestão de atividades para **times pequenos e freelancers**, com dashboards, linha do tempo para acompanhamento de projetos e checklists de atividades por usuários, além de fluxo de tarefas customizável.  

O objetivo é centralizar as informações importantes de cada projeto e permitir colaboração eficiente, com uma interface leve, intuitiva e colaborativa.

---

## Introdução

Times pequenos e freelancers enfrentam desafios como:

- Prazos apertados e múltiplas entregas simultâneas.  
- Cada pessoa organizando tarefas de forma diferente.  
- Ferramentas muito complexas ou pouco flexíveis.  

Nossa plataforma resolve isso oferecendo:

- Dashboards claros e intuitivos.  
- Linha do tempo para acompanhamento de projetos.  
- Checklists de atividades por usuário.  
- Fluxos de tarefas customizáveis.

---

## Público-Alvo

- Pequenos times (2 a 10 pessoas)  
- Freelancers que trabalham em colaboração  
- Pequenas empresas em crescimento  

---

## Personas

### Persona Primária

**Ricardo Alves**  
- **Idade:** 34 anos  
- **Cargo:** Dono de agência de marketing digital (8 pessoas)  
- **Características:** Líder e tomador de decisão, multitarefas, pragmático, conectado.  
- **Contexto Social:** Networking, busca reputação e credibilidade.  
- **Contexto Econômico:** Orçamento controlado, procura soluções custo-benefício.  
- **Contexto Cultural:** Cultura de startups/agências criativas, aberta à inovação.  
- **Hábitos de desenvolvimento pessoal:** Participa de sessões com coach e lê livros de autoajuda.  
- **Necessidades na aplicação:** Dashboards claros, linha do tempo para múltiplos projetos, checklists para garantir prazos.

### Persona Secundária

**Profissional fixo ou parceiro recorrente** (designer, dev, redator, analista)  
- Executor fixo, busca clareza de prazos, checklists simples e notificações.  
- Participa da execução diária das atividades e colabora constantemente com a equipe.  

### Outras Personas

**Freelancer contratado pontualmente**  
- Freelancer eventual, precisa de acesso limitado, tarefas bem definidas e comunicação centralizada.

---

## Informações fornecidas para o serviço

- **Usuário:** nome, e-mail, senha, função (gestor, membro, externo).  
- **Equipe/Projeto:** nome da equipe, projetos, prazos, responsáveis, fluxo de tarefas.  
- **Atividades:** tarefas atribuídas, status, prazos, anexos, observações.  
- **Colaboração:** comentários, histórico de alterações, checklists.  
- **Visão Geral:** dashboards, linha do tempo, métricas de produtividade.

---

## Mapa de Empatia

![Mapa de empatia](empatia.png)

### Persona Primária – Ricardo

- **O que vê:** Calendário lotado, e-mails, planilhas, KPIs fragmentados.  
- **O que ouve:** Clientes cobrando status, equipe pedindo prioridades, relatórios financeiros.  
- **O que diz e faz:** Define prioridades, delega tarefas, acompanha entregas vs. escopo.  
- **O que pensa e sente:** Pressão por prazos, busca previsibilidade e dados confiáveis.  
- **Dores:** Falta de centralização, retrabalho, status desatualizado.  
- **Ganhos:** Painel central com métricas, checklists claros, menos retrabalho.


### Persona Secundária – Mariana (profissional fixo)

- **O que vê:** Briefings, boards de tarefas, dependências entre áreas.  
- **O que ouve:** PM/gestor pedindo consistência e prazo, colegas sugerindo ajustes.  
- **O que diz e faz:** Comenta em cards, entrega etapas do trabalho, anexa arquivos.  
- **O que pensa e sente:** Quer foco e critérios claros de aprovação.  
- **Dores:** Retrabalho, revisões sem histórico, prioridades pouco visíveis.  
- **Ganhos:** Fluxo padronizado, checklists claros, entregas rastreáveis.

---

## Contexto de Uso

### Ambiente de Uso

- Aplicação digital, utilizada em **trabalho remoto, híbrido ou em pequenos escritórios**, acessível por computadores e dispositivos móveis durante a execução e acompanhamento de tarefas.

### Contexto Social

- Informações que o sistema deve armazenar antes da interação:  
  - Usuário: função, idioma, fuso horário, preferências de notificação.  
  - Equipe/Projeto: times ativos, projetos, marcos, workflow, permissões.  
  - Atividades: tarefas, prazos, anexos, observações.  
  - Colaboração: histórico de alterações, checklists, aprovações.  
  - Visão Geral: métricas, dashboards, linha do tempo.  

- Ambiente típico de uso:  
  - Início do dia: verificação de prazos e prioridades.  
  - Durante a execução: acompanhamento de tarefas e handoffs.  
  - Pré-deadline: conferência de checklists e aprovação.  
  - Pós-entrega: registro de lições aprendidas e ajustes de workflow.

---

## Jornada do Usuário

1. **Primeira interação / Onboarding:** Criação de conta, workspace, convites, integrações, configuração do workflow inicial.  
2. **Planejamento de projeto:** Criação do projeto, divisão de atividades, definição de responsáveis, checklists e dependências.  
3. **Execução e colaboração:** Membros assumem tarefas, adicionam anexos, comentários, atualizam status.  
4. **Revisão e aprovação:** Aprovadores analisam, pedem ajustes, marcam tarefas como concluídas.  
5. **Acompanhamento e gestão:** Gestor acompanha métricas, timeline, rebalanceia tarefas e monitora riscos.  
6. **Entrega e pós-projeto:** Pacote final entregue, relatórios de produtividade gerados, workflow ajustado.

---



## Análise de concorrência

- Pesquise serviços ou podutos existentes atualmente que possam realizar o objetivo deste projeto.
- Selecione pelo menos 3 serviços ou podutos diferentes.
- Em relação aos concorrentes, respondam as seguintes perguntas?
  - Existe plataforma similar que atende o mesmo mercado e funcionalidades? Se sim: Quais os pontos positivos? Quais os pontos negativos?
  - Existe plataforma diferente quanto ao serviço, mas que atenda esse mercado? Se sim: Quais os pontos positivos? Quais os pontos negativos?

## Coleta de dados

## Modelo de tarefas

## Design

- Pense nas características de Affordances do seu serviço ou poduto. 
    - Que tipo de acessibilidades devem ser consideradas dentro do seu projeto?
- Discuta o papel das expectativas do usuário no projeto deste serviço ou poduto. Qual a importância e pontos a serem considerados se você quiser vender esse serviço ou poduto?

### Prototipação em baixo nível (papel)
#### Avaliação heurística

### Prtotipação em médio nível (Figma)
#### Avaliação heurística

### Prtotipação em alto nível (React)
#### Avaliação heurística

[^1]: Fonte: Adaptado de <https://hazeshift.com.br/mapa-de-empatia/>

<!-- TODOs:
- Add exemplos
 -->






