
<h1 align="center">
  Despertador de Remédios
</h1>

<h4 align="center">Aplicação mobile desenvolvida para controle de remedios e acompanhamento dos mesmos</h4>

<p align="center">
  <a href="#como-executar">Como executar</a> •
  <a href="#funcionalidades">Funcionalidades</a> •
  <a href="#a-desenvolver">A desenvolver</a> •
</p>

![](https://github.com/0rakul0/remedios/blob/main/assets/preview.png)

**Link figma:** https://www.figma.com/file/NgcyocatrZu804fIgLTqdd/SeusRem%C3%A9dios?node-id=0%3A1

## 🚀 Como executar
<ul>
  <li> fazer um clone do projeto para o seu computador </li>
  <li> no diretório raiz, executar **expo start** para iniciar a aplicação </li>
  <li> ou **yarn android | ios** para rodar a aplicação usando emulador </li>
  <li> para startar o servidor local use json-server </li>
  <li> use o comando json-server ./src/services/server.json -H <-endereço da sua manquina-> -p 3333 </li>
</ul>

## 💬 Funcionalidades
<ul>
  <li>listagem dos remédios</li>
  <li>adição e remoção de remédios monitorados</li>
  <li>definição de alarmes para lembretes</li>
  <li>recebimento de alertas</li>
</ul>

## 🔧 A desenvolver
<ul>
  <li>criação de um banco de dados local</li>
  <li>adição de remédios na listagem pelo usuário</li>
  <li>criar um botão para cancelar as notificações</li>
</ul>

## Atividades realizadas por dia
dia 1
- instalação de dependências (nodejs, expo-cli, typescript)
- criação e estilização do primeiro componente button

dia 2
- criação da tela inicial (screen) para pré-carregamento
- componente button e utilização de SASS
- criação de páginas e navegação entre rotas

dia 3 
- criação ta tela para selecionar remédios e filtro
- consumindo dados de api
- uso de animações para melhorar a experiência do usuário

dia 4
- validação de campos e passagem de parâmetros
- armazenamento com Async Storage
- cadastro de remédios, refatoração de telas e interfaces

dia 5
- refatoração de código
- exclusão de reme´dios com efeito swipe, remoção do Storage
- agendamento de notificação, api e recebimento
