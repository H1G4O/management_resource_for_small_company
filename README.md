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

Luís Gasparetto, 43 anos, nasceu em São Paulo e desde cedo demonstrou interesse por tecnologia e soluções digitais. Ainda jovem, começou a explorar programação por conta própria e, após concluir a faculdade, decidiu investir na criação de uma pequena empresa de desenvolvimento de software. Ao longo dos anos, formou um time enxuto de dez pessoas, com projetos variados para clientes de diferentes segmentos, e hoje atua como líder estratégico e operacional da equipe. Sua rotina é repleta de desafios: gerenciar múltiplos projetos simultaneamente, alinhar demandas com clientes, supervisionar tarefas do time e garantir que os prazos sejam cumpridos. Embora seja dedicado e detalhista, Luís percebe que, à medida que a empresa cresce, manter uma visão clara do andamento de cada projeto se torna cada vez mais difícil. Inserido no ecossistema de startups e tecnologia, mantém networking ativo, participa de eventos do setor e valoriza práticas ágeis e comunicação direta. Em termos econômicos, busca soluções que tragam produtividade e bom custo-benefício, evitando ferramentas complexas que só aumentem a burocracia. Culturalmente adaptado a um ambiente colaborativo e inovador, ele procura uma aplicação capaz de fornecer dashboards objetivos, linha do tempo de projetos e checklists de atividades para acompanhar as entregas do time de forma prática e eficiente.

### Persona Secundária

Mariana Reisz tem 29 anos, nasceu e cresceu em Campinas e, desde a adolescência, sempre gostou de criar e resolver problemas visuais. Formada em Design Gráfico, decidiu migrar para o digital ao perceber a demanda crescente por produtos e interfaces intuitivas, e hoje trabalha como designer em tempo integral em uma pequena empresa de desenvolvimento de software. Seu dia a dia é marcado por tarefas criativas e prazos curtos: criar layouts, revisar materiais e alinhar detalhes com o time de desenvolvimento. Mariana valoriza clareza e organização; para ela, entender exatamente o que precisa ser feito e quando entregar é essencial para manter a produtividade e a tranquilidade no trabalho. Culturalmente conectada ao universo digital, acompanha tendências de design, participa de comunidades online e troca experiências com outros profissionais da área. Em termos econômicos, busca estabilidade e boas oportunidades de aprendizado dentro da empresa, evitando complicações que atrasem seu fluxo criativo. Ela procura, em uma aplicação, checklists simples, prazos bem definidos, notificações objetivas e um painel claro do andamento dos projetos, que a ajudem a manter foco, priorizar tarefas e colaborar com a equipe sem sobrecarga.

### Outras Personas

Espíndola Ferreira tem 35 anos, vive em Belo Horizonte e construiu sua carreira como desenvolvedor freelancer, atendendo projetos de curta duração para diferentes clientes. Ao longo dos últimos anos, especializou-se em implementar funcionalidades pontuais e resolver problemas técnicos com agilidade, mantendo uma carteira variada de trabalhos. Por atuar de forma independente, valoriza ferramentas simples e processos claros, pois muitas vezes lida com mais de um cliente ao mesmo tempo e precisa evitar retrabalho. Quando é contratado por uma empresa de desenvolvimento, como apoio temporário, recebe um escopo fechado e um prazo curto, concentrando-se totalmente na execução. Espíndola prefere comunicação objetiva, centralizada e com mínimo de burocracia, já que seu tempo é fracionado entre vários projetos. Culturalmente inserido no ecossistema tech, acompanha tendências e participa de fóruns online, mas mantém foco em produtividade e entrega de resultados. Para ele, uma aplicação ideal deve permitir acesso limitado ao que realmente importa: tarefas atribuídas, datas de entrega, comentários do gestor e um espaço centralizado para atualizar status, garantindo que possa colaborar de forma eficiente sem se perder em informações desnecessárias.

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

### Persona Primária – Luís

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

### Outras Personas – Espíndola (Freelancer)

- **O que vê:** Tarefas pontuais atribuídas, prazos curtos, comunicação fragmentada entre diferentes clientes e projetos.
- **O que ouve:** Instruções objetivas do gestor, pedidos de atualização sobre entregas, feedbacks rápidos sobre o trabalho realizado.
- **O que diz e faz:** Executa as tarefas designadas, atualiza status no sistema, solicita esclarecimentos quando necessário, foca em entregar no prazo.
- **O que pensa e sente:** Deseja clareza e simplicidade, busca evitar retrabalho e perder tempo com informações irrelevantes; sente pressão pelo prazo e pela qualidade do trabalho.
- **Dores:** Falta de acesso limitado às informações relevantes, comunicação dispersa, dificuldade em organizar tarefas de múltiplos clientes.
- **Ganhos:** Acesso direto e limitado às tarefas, prazos claros, comunicação centralizada, foco na entrega sem sobrecarga.

---

## Contexto de Uso

### Ambiente de Uso

A aplicação será utilizada em ambientes de trabalho remoto, híbrido ou em pequenos escritórios, voltados à gestão de tarefas colaborativas. O acesso será feito tanto por computadores quanto por dispositivos móveis, permitindo o acompanhamento das atividades em tempo real durante todas as etapas do projeto.

 - O uso da plataforma se encaixa nos principais momentos do fluxo de trabalho das equipes:
  - Início do dia: verificação de tarefas pendentes, prazos e prioridades do dia.
  - Durante a execução: acompanhamento do progresso das atividades, comunicação entre membros e atualização de status.
  - Próximo ao deadline: revisão de checklists, conferência de entregas e aprovação final das tarefas.
  - Pós-entrega: registro de lições aprendidas, arquivamento de projetos concluídos e ajustes no fluxo de trabalho para futuras iterações.
---

### Contexto Social

- Informações que o sistema deve armazenar antes da interação:  
  - Usuário: função, idioma, fuso horário, preferências de notificação.  
  - Equipe/Projeto: times ativos, projetos, marcos, workflow, permissões.  
  - Atividades: tarefas, prazos, anexos, observações.  
  - Colaboração: histórico de alterações, checklists, aprovações.  
  - Visão Geral: métricas, dashboards, linha do tempo.  
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

- Pesquise serviços ou produtos existentes atualmente que possam realizar o objetivo deste projeto.
- Selecione pelo menos 3 serviços ou podutos diferentes.
- Em relação aos concorrentes, respondam as seguintes perguntas?
  - Existe plataforma similar que atende o mesmo mercado e funcionalidades? Se sim: Quais os pontos positivos? Quais os pontos negativos?
  - Existe plataforma diferente quanto ao serviço, mas que atenda esse mercado? Se sim: Quais os pontos positivos? Quais os pontos negativos?

## Coleta de dados
### Modelo de entrevista:
Objetivo: entender hábitos, dificuldades e expectativas de profissionais que trabalham em equipe ou como freelancers na gestão de tarefas.

Duração: cerca de 10 a 15 minutos.
Formato: presencial ou online (videoconferência).
Participantes ideais: pequenos gestores, designers, desenvolvedores ou freelancers.

Roteiro

  - Contexto do trabalho
    
-Pode me contar brevemente como é seu dia a dia profissional?

-Você trabalha sozinho(a) ou em equipe? De quantas pessoas?

  - Organização de tarefas
    
-Como você costuma organizar suas tarefas ou as do seu time?

-Quais ferramentas ou métodos usa atualmente (ex: Trello, planilhas, agenda)?

  - Dores e desafios
    
-O que mais te incomoda nas ferramentas que usa hoje?

-Já teve problemas com prazos, comunicação ou tarefas esquecidas?

  - Colaboração
    
-Como é a comunicação entre o time durante um projeto?

-Você sente falta de alguma funcionalidade que facilitaria essa colaboração?

  - Expectativas
    
-Se pudesse criar a ferramenta ideal de gestão de tarefas, o que ela teria?

-Qual seria o diferencial que te faria preferir uma nova plataforma?
    
(https://forms.cloud.microsoft/r/U1Lwzhftfm)

## Modelo de tarefas
(!!!!!)
## Design

- Pense nas características de Affordances do seu serviço ou produto. 
    - Que tipo de acessibilidades devem ser consideradas dentro do seu projeto?
- Discuta o papel das expectativas do usuário no projeto deste serviço ou poduto. Qual a importância e pontos a serem considerados se você quiser vender esse serviço ou poduto?

### Prototipação em baixo nível (papel)
(!!!!!!)

#### Avaliação heurística
(!!!!!!)
### Prtotipação em médio nível (Figma)
#### Avaliação heurística

### Prtotipação em alto nível (React)
#### Avaliação heurística

[^1]: Fonte: Adaptado de <https://hazeshift.com.br/mapa-de-empatia/>

<!-- TODOs:
- Add exemplos
 -->









