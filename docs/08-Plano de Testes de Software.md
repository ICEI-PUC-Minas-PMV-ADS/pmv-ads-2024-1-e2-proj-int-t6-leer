# Plano de Testes de Software

Os requisitos para a realização dos testes de software são:

- Site publicado na Internet

- Navegador da Internet: Chrome, Firefox ou Edge

- Conectividade de Internet

## Tipos de Testes

Os testes funcionais a serem realizados na aplicação são descritos a seguir.

|Caso de Teste    | CT-01 - Cadastro de credenciais |
|:---|:---|
| Requisitos Associados | RF-05 O usuário deve cadastrar o e-mail e senha para criar uma conta através da pagina crie sua conta |
| Objetivo do Teste | Verificar se a função de cadastro do usuário está operando corretamente.|
| Passos | 1. Acessar o site <br/>2. Clicar no botão "Se cadastrar" <br/> 3. Inserir todos os dados requisitados para cadastro <br/> 4. Clicar no botão "Salvar" |
| Critérios de êxito | O usuário tem uma conta criada no site Leer |
| Responsável pela elaborar do caso de Teste | Vitoria Pilon e André Florio|

|Caso de Teste    | CT-02 - Login usando credenciais |
|:---|:---|
| Requisitos Associados | RF-01	Cada usuário deve fazer o login na página através de um e-mail e uma senha |
| Objetivo do Teste | Verificar se o usuário consegue fazer o login |
| Passos | 1. Acessar o site <br/>2. Clicar no campo e-mail adress e inserir o e-mail cadastrado <br/>3. Clicar no campo "password" e inserir a senha cadastrada <br/>4. Clicar no botão "Entrar no meu LEER"|
| Critérios de êxito | O ususário é direcionado a página inicial |
| Responsável pela elaborar do caso de Teste | Vitoria Pilon e André Florio|

|Caso de Teste    | CT-03 - Criar, editar e salvar um novo tema |
|:---|:---|
| Requisitos Associados | RF-03 - Incluir, editar, excluir tema |
| Objetivo do Teste | Verificar se o usuário consegue adicionar um novo tema |
| Passos | 1. Acessar o site <br/> 2. Na pagina inicial ao lado esquerdo na coluna Temas clicar no botão "Adicionar tema" <br/> 3. Clicar no campo "Digite o novo tema" <br/> 4. Digitar o nome escolhido <br/> 5. Clicar no botão "ok" para salvar|
| Critérios de êxito | Um novo tema é criado na coluna Tema e o tema é armazenado no localstorage  |
| Responsável pela elaborar do caso de Teste | Vitoria Pilon e André Florio|

|Caso de Teste    | CT-04 - Adicionar, salvar, editar e excluir o conteúdo "O que aprendi hoje..." no tema escolhido|
|:---|:---|
| Requisitos Associados | RF-02 O usuário deve ser capaz de adicionar, salvar, editar e excluir o conteúdo que aprendeu no tema escolhido |
| Objetivo do Teste | Verificar se o usuário consegue adicionar, salvar, editar e excluir o conteúdo aprendido do dia no tema escolhido |
| Passos | 1. Acessar o site <br/> 2. Na coluna Temas clicar no tema escolhido <br/> 3. Na coluna "O que aprendi hoje" no botão "O que aprendi hoje" <br/> 5. Inserir o conteúdo na caixa de texto <br/>6. Clicar no botão "ok" para salvar <br/> 7. Clicar no icone editar, inserir o conteúdo e clicar em "ok" para salvar <br/> 8. Para excluir clicar no icone "X" e clicar em "ok"|
| Critérios de êxito | O conteúdo é salvo na coluna "O que aprendi hoje" e no localstorage  |
| Responsável pela elaborar do caso de Teste | Vitoria Pilon e André Florio|

|Caso de Teste    | CT-05 - Adicionar, salvar, editar e excluir  o conteúdo "O que preciso revisar..." no tema escolhido|
|:---|:---|
| Requisitos Associados | RF-02 O usuário deve ser capaz de adicionar, salvar, editar e excluir o conteúdo que precisa revisar no tema escolhido |
| Objetivo do Teste | Verificar se o usuário consegue adicionar, salvar, editar e excluir o conteúdo que precisa revisar do tema escolhido |
| Passos | 1. Acessar o site <br/> 2. Na coluna "Temas", clicar no tema escolhido <br/> 3. Na coluna "O que preciso revisar" clicar  no botão "O que preciso revisar"<br/> 4. Inserir o conteúdo na caixa de texto  <br/>5. Clicar no botão "ok" para salvar  <br/> 6. Clicar no icone "editar", inserir o conteúdo e clicar em "ok" para salvar <br/> 7. Para excluir clicar no icone "X" e clicar em "ok"|
| Critérios de êxito | O conteúdo é salvo na coluna "O que preciso revisar" e no localstorage  |
| Responsável pela elaborar do caso de Teste | Vitoria Pilon e André Florio|

|Caso de Teste    | CT-06 - Adicionar, salvar, editar e excluir  "Datas importantes..." no tema escolhido|
|:---|:---|
| Requisitos Associados | RF-02 O usuário deve ser capaz de adicionar, salvar, editar e excluir as datas importantes no tema escolhido |
| Objetivo do Teste | Verificar se o usuário consegue adicionar, salvar, editar e excluir as datas importantes no tema escolhido |
| Passos | 1. Acessar o site <br/> 2. Na coluna "Temas", clicar no tema desejado<br/> 3. Na coluna "Datas importantes", clicar no botão "calendario" <br/> 4. Inserir a data desejada <br/> 5. Clicar no botão "Datas Importantes" <br/> 6. Inserir a descrição da data importante no caixa de texto <br/>7. Clicar no botão "Ok" para salvar  <br/> 8. Clicar no icone "editar", inserir o conteúdo e clicar em "Ok" para salvar <br/> 9. Para excluir clicar no icone "X" e clicar em "ok"|
| Critérios de êxito | A data importante e a descrição são salvas na coluna "Datas importantes" e no localstorage   |
| Responsável pela elaborar do caso de Teste | Vitoria Pilon e Andre Florio|

|Caso de Teste    | CT-07 - Funcionamento do botão "Focus Time"|
|:---|:---|
| Requisitos Associados | RF-04 O site deve permitir que o usuário seja capaz de cronometrar seu tempo de estudo, parar e zerar o cronômetro|
| Objetivo do Teste | Verificar se o usuário consegue iniciar, parar e zerar o cronômetro  |
| Passos | 1. Acessar o site <br/> 2. Na pagina inicial ao lado direito superior <br/> 3. Clicar no botão "Focus Time" para iniciar o cronômetro <br/> 4. Clicar no botão mesmo botão para parar <br/> 5. Clicar no botão "Zerar" para zerar <br/> |
| Critérios de êxito | O usuário é capaz de medir o seu tempo de estudo e zerar o cronometro quando acabar |
| Responsável pela elaborar do caso de Teste | Vitoria Pilon e André Florio|
