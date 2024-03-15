
# Metodologia

<span style="color:red">Pré-requisitos: <a href="2-Especificação do Projeto.md"> Documentação de Especificação</a></span>

A metodologia ágil escolhida para o desenvolvimento deste projeto foi o SCRUM, pois como citam Amaral, Fleury e Isoni (2019, p. 68), seus benefícios são a “visão clara dos resultados a entregar; ritmo e disciplina necessários à execução; definição de papéis e responsabilidades dos integrantes do projeto (Scrum Owner, Scrum Master e Team); empoderamento dos membros da equipe de projetos para atingir o desafio; conhecimento distribuído e compartilhado de forma colaborativa; ambiência favorável para crítica às ideias e não às pessoas.”

## Controle de Versão

A ferramenta de controle de versão adotada no projeto foi o
[Git](https://git-scm.com/), sendo que o [Github](https://github.com)
foi utilizado para hospedagem do repositório.

O projeto segue a seguinte convenção para o nome de branches:

- `main`: versão estável já testada do software
- `unstable`: versão já testada do software, porém instável
- `testing`: versão em testes do software
- `dev`: versão de desenvolvimento do software

Quanto à gerência de issues, o projeto adota a seguinte convenção para
etiquetas:

- `documentation`: melhorias ou acréscimos à documentação
- `bug`: uma funcionalidade encontra-se com problemas
- `enhancement`: uma funcionalidade precisa ser melhorada
- `feature`: uma nova funcionalidade precisa ser introduzida

Discuta como a configuração do projeto foi feita na ferramenta de versionamento escolhida. Exponha como a gerência de tags, merges, commits e branchs é realizada. Discuta como a gerência de issues foi realizada.

> **Links Úteis**:
> - [Tutorial GitHub](https://guides.github.com/activities/hello-world/)
> - [Git e Github](https://www.youtube.com/playlist?list=PLHz_AreHm4dm7ZULPAmadvNhH6vk9oNZA)
>  - [Comparando fluxos de trabalho](https://www.atlassian.com/br/git/tutorials/comparing-workflows)
> - [Understanding the GitHub flow](https://guides.github.com/introduction/flow/)
> - [The gitflow workflow - in less than 5 mins](https://www.youtube.com/watch?v=1SXpE08hvGs)

## Gerenciamento de Projeto

### Divisão de Papéis

A equipe utiliza o Scrum como base para definição do processo de desenvolvimento.

- Scrum Master: Vitoria Veronezzi Pilon.
- Product Owner: 
- Equipe de Desenvolvimento: Andre Florio; Caio Lelis Penido; Mariana Sayuri Tomioka; Robert Alexandre Rodrigues; Simony Larissa Bueno; Vitoria Veronezzi Pilon.
- Equipe de Design: Mariana Sayuri. 
- Equipe de teste: Andre Florio; Vitoria Veronezzi Pilon. 

### Processo

- Backlog: recebe as tarefas a serem trabalhadas e representa o Product Backlog. Todas as atividades identificadas no decorrer do projeto também devem ser incorporadas a esta lista. 
- To Do: Esta lista representa o Sprint Backlog. Este é o Sprint atual que estamos trabalhando. 
- In Progress: Tarefas iniciadas e inicabadas são movidas para essa coluna.
- Test: São as tarefas que estão finalizadas e prontas para serem testadas, se elas passarem no teste podem ir para a última coluna (Done), se reporvar volta para primeira coluna (Todo)
- Done: São as tarefas que passaram pelos testes e controle de qualidade e estão prontos para serem entregues ao usuário.

  O quadro do Kanban do grupo no Github Projects está disponível através do link (https://github.com/orgs/ICEI-PUC-Minas-PMV-ADS/projects/905/views/1).
  
  <figure>
    <img src="https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2024-1-e2-proj-int-t6-leer/blob/2e9b8562ae528099906ccfcd998eba1431169b4f/docs/img/Kanban%20.png" <figcaption>Figura - Tela do Kaban utilizado pelo grupo </figcaption>
  </figure>
  


### Ferramentas

As ferramentas empregadas no projeto são:

| AMBIENTE                            | PLATAFORMA                         | LINK DE ACESSO |
|-------------------------------------|------------------------------------|----------------|
| Editor de código                    | Visual Studio Code                 | 
| Ferramenta de comunicação           | Whatsapp                           |https://www.whatsapp.com/|
| Repositório de código fonte         | GitHub                             |https://github.com/ICEI-PUC-Minas-PMV-ADS/pmv-ads-2024-1-e2-proj-int-t6-leer|
| Documentos do projeto               | GitHub                             |
| Gerenciamento do Projeto            | GitHub Projects                    |https://github.com/orgs/ICEI-PUC-Minas-PMV-ADS/projects/905|
| Hospedagem                          | GitHub Pages                       | 
| Ferramentas de desenho de tela      |                                    | 


O editor de código foi escolhido porque ele possui uma integração com o
sistema de versão. As ferramentas de comunicação utilizadas possuem
integração semelhante e por isso foram selecionadas. Por fim, para criar
diagramas utilizamos essa ferramenta por melhor captar as
necessidades da nossa solução.
