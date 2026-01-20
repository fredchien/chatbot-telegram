<h1 align="center">Desafio Fase 2 - Bot de Clima no Telegram com N8N</h1>

<!-- Status -->

<h4 align="center">
	🚧  Desafio Fase 2 - Bot de Clima no Telegram com N8N 🚀 🚧
</h4>

<hr>

<p align="center">
  <a href="#dart-sobre">Sobre</a> &#xa0; | &#xa0; 
  <a href="#sparkles-funcionalidades">Funcionalidades</a> &#xa0; | &#xa0;
  <a href="#rocket-tecnologias">Tecnologias</a> &#xa0; | &#xa0;
  <a href="#checkered_flag-começando">Importando Workflow</a> &#xa0; | &#xa0;
  <a href="https://github.com/EstudioVnW/" target="_blank">Autor</a>
</p>

<br>

## :dart: Sobre

Foi criado um chatbot no Telegram utilizando N8N que informa a temperatura atual de qualquer cidade do Brasil. O chatbot recebe o nome da cidade e estado via mensagem, consulta com a API gratuita do OpenWeather, processa a resposta e devolve ao usuário uma mensagem curta, clara e amigável com a temperatura.

## :sparkles: Funcionalidades

:heavy_check_mark: Receber o nome da cidade e estado via mensagem;</br>
:heavy_check_mark: Consultar com a API gratuita do OpenWeather;</br>
:heavy_check_mark: Processar a resposta;</br>
:heavy_check_mark: Devolver ao usuário uma mensagem curta, clara e amigável com a temperatura;

## :rocket: Tecnologias

As seguintes ferramentas foram usadas na construção do projeto:

- [N8N](https://n8n.io)


## :checkered_flag: Importando Workflow

```bash
1 - Baixar o arquivo workflow-chatbot-telegram.json
2 - Importar o workflow no N8N (Import from file...)
3 - Criar uma credential do Telegram Account
4 - Incluir seu token do Telegram no input Access Token
5 - Criar uma credential do OpenWeather
6 - Incluir sua chave de API do OpenWeather na variavel OPENWEATHER_API_KEY que está no segundo Node
7 - Salvar as credentials
8 - Executar o workflow

```

Feito com :heart: por <a href="https://github.com/fredchien" target="_blank">Frederic Chien</a>

&#xa0;

<a href="#top">Voltar para o topo</a>
