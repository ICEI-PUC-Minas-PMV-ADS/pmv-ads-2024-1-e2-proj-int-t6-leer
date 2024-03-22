# Especificações do Projeto

A definição precisa do problema e os aspectos mais importantes a serem abordados neste projeto foram estabelecidos após a participação ativa dos usuários em um processo imersivo conduzido pela equipe. Isso incluiu a observação dos usuários em seu ambiente natural e a realização de pesquisas. Os insights obtidos durante esse processo foram organizados em personas e histórias de usuários.

## Personas

<table>
<tbody>
<tr align=center>
<th colspan="2">Gabriela - 21 anos</th>
</tr>
<tr>
<td width="150px"><b>Descrição</b></td>
<td width="600px">Gabriela tem 21 anos e é natural de São Paulo, mas mudou-se para Campinas para cursar Engenharia Civil. Ela está se adaptando à vida universitária, tentando equilibrar seus estudos com suas atividades extracurriculares e sua vida social. Gabriela é muito dedicada aos estudos e busca maneiras de melhorar sua organização para alcançar seus objetivos acadêmicos.</td>
</tr>
<tr>
<td><b>Necessidades</b></td>
<td>A maior dificuldade de Gabriela é gerenciar seu tempo de forma eficiente. Ela precisa acompanhar os horários das aulas, prazos de entregas de trabalhos e projetos, além de encontrar tempo para atividades como esportes, eventos universitários e trabalhos voluntários. Gabriela sente que uma ferramenta que a ajude a planejar e priorizar suas tarefas seria extremamente útil para melhorar sua produtividade e reduzir o estresse do dia a dia.</td>
</tr>
</tbody>
</table>


<table>
<tbody>
<tr align=center>
<th colspan="2">Marcos - 30 anos</th>
</tr>
<tr>
<td width="150px"><b>Descrição</b></td>
<td width="600px">Marcos tem 30 anos e é natural de Porto Alegre. Ele está cursando uma pós-graduação em Administração em São Paulo e mora sozinho em um apartamento. Marcos trabalha em período integral em uma empresa de consultoria e está sempre buscando formas de aprimorar seus conhecimentos e habilidades profissionais.</td>
</tr>
<tr>
<td><b>Necessidades</b></td>
<td> O maior desafio de Marcos é conciliar sua rotina intensa de trabalho com os estudos da pós-graduação. Ele precisa gerenciar seus horários de aula, prazos de entrega de trabalhos e projetos, além de encontrar tempo para se dedicar ao networking e participar de eventos relacionados à sua área de atuação. Marcos também precisa cuidar das tarefas domésticas em seu apartamento e encontrar momentos para relaxar e recarregar as energias. Ele acredita que uma ferramenta digital que o ajude a organizar sua agenda, lembrar de compromissos importantes e priorizar suas tarefas seria fundamental para aumentar sua produtividade e alcançar seus objetivos acadêmicos e profissionais.</td>
</tr>
</tbody>
</table>

## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Usuário do sistema  | Registrar minhas tarefas           | Não esquecer de fazê-las               |
|Administrador       | Alterar permissões                 | Permitir que possam administrar contas |

Apresente aqui as histórias de usuário que são relevantes para o projeto de sua solução. As Histórias de Usuário consistem em uma ferramenta poderosa para a compreensão e elicitação dos requisitos funcionais e não funcionais da sua aplicação. Se possível, agrupe as histórias de usuário por contexto, para facilitar consultas recorrentes à essa parte do documento.

> **Links Úteis**:
> - [Histórias de usuários com exemplos e template](https://www.atlassian.com/br/agile/project-management/user-stories)
> - [Como escrever boas histórias de usuário (User Stories)](https://medium.com/vertice/como-escrever-boas-users-stories-hist%C3%B3rias-de-usu%C3%A1rios-b29c75043fac)
> - [User Stories: requisitos que humanos entendem](https://www.luiztools.com.br/post/user-stories-descricao-de-requisitos-que-humanos-entendem/)
> - [Histórias de Usuários: mais exemplos](https://www.reqview.com/doc/user-stories-example.html)
> - [9 Common User Story Mistakes](https://airfocus.com/blog/user-story-mistakes/)

## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| A aplicação deve permitir que o usuário gerencie suas tarefas | ALTA | 
|RF-002| A aplicação deve emitir um relatório de tarefas realizadas no mês   | MÉDIA |

### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| A aplicação deve ser responsiva | MÉDIA | 
|RNF-002| A aplicação deve processar requisições do usuário em no máximo 3s |  BAIXA | 

Com base nas Histórias de Usuário, enumere os requisitos da sua solução. Classifique esses requisitos em dois grupos:

- [Requisitos Funcionais
 (RF)](https://pt.wikipedia.org/wiki/Requisito_funcional):
 correspondem a uma funcionalidade que deve estar presente na
  plataforma (ex: cadastro de usuário).
- [Requisitos Não Funcionais
  (RNF)](https://pt.wikipedia.org/wiki/Requisito_n%C3%A3o_funcional):
  correspondem a uma característica técnica, seja de usabilidade,
  desempenho, confiabilidade, segurança ou outro (ex: suporte a
  dispositivos iOS e Android).
Lembre-se que cada requisito deve corresponder à uma e somente uma
característica alvo da sua solução. Além disso, certifique-se de que
todos os aspectos capturados nas Histórias de Usuário foram cobertos.

## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue até o final do semestre |
|02| Não pode ser desenvolvido um módulo de backend        |


Enumere as restrições à sua solução. Lembre-se de que as restrições geralmente limitam a solução candidata.

> **Links Úteis**:
> - [O que são Requisitos Funcionais e Requisitos Não Funcionais?](https://codificar.com.br/requisitos-funcionais-nao-funcionais/)
> - [O que são requisitos funcionais e requisitos não funcionais?](https://analisederequisitos.com.br/requisitos-funcionais-e-requisitos-nao-funcionais-o-que-sao/)

## Diagrama de Casos de Uso

O diagrama de casos de uso é o próximo passo após a elicitação de requisitos, que utiliza um modelo gráfico e uma tabela com as descrições sucintas dos casos de uso e dos atores. Ele contempla a fronteira do sistema e o detalhamento dos requisitos funcionais com a indicação dos atores, casos de uso e seus relacionamentos. 

As referências abaixo irão auxiliá-lo na geração do artefato “Diagrama de Casos de Uso”.

> **Links Úteis**:
> - [Criando Casos de Uso](https://www.ibm.com/docs/pt-br/elm/6.0?topic=requirements-creating-use-cases)
> - [Como Criar Diagrama de Caso de Uso: Tutorial Passo a Passo](https://gitmind.com/pt/fazer-diagrama-de-caso-uso.html/)
> - [Lucidchart](https://www.lucidchart.com/)
> - [Astah](https://astah.net/)
> - [Diagrams](https://app.diagrams.net/)
