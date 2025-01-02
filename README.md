# Introdução

Este repositorio será usado para eu aplicar conceitos novos, aprimorar minhas habilidades e lapidar minhas tecnicas. Não espere nada desse espaço, fique a vontade para usar o que eu deixar aqui também.

## Meu roadmap

Estou trabalhando em um projeto, e para conseguir concretiza-lo pedi que o chatGPT gerasse um roadmap que me ensine o que preciso. Ao menos assim tenho um norte de onde andar.

- ### JavaScript (Base do Desenvolvimento)

  - Sintaxe básica e conceitos fundamentais
    - ~~Variáveis (let, const, var)~~
    - ~~Tipos de dados (strings, arrays, objetos)~~
    - ~~Operadores (aritméticos, lógicos, comparação)~~
    - ~~Estruturas de controle (if, for, while, switch)~~
  - Funções
    - ~~Declaração e expressão de função~~
    - ~~Funções anônimas e arrow functions~~
    - ~~Callbacks e Promises~~
  - Manipulação de objetos e arrays
    - Métodos úteis (map, filter, reduce, etc.)
  - Conceitos de programação assíncrona:
    - Event Loop
    - Promises e async/await
  - Módulos e Importação
    - CommonJS (require) e ESModules (import)

- ### Node.js (Servidor e Backend)

  - Fundamentos do Node.js:
    - Como funciona o runtime do Node.js
    - Sistema de módulos do Node.js
  - Trabalhando com o File System (fs)
    - Ler e escrever arquivos
    - Manipular diretórios
  - Eventos e Streams
    - Manipulação de eventos (EventEmitter)
    - Fluxos de dados (streams)
  - Gerenciamento de Pacotes com NPM/Yarn
    - Instalação e uso de bibliotecas
    - Criação de scripts no package.json

- ### Fundamentos do Electron

  - Arquitetura do Electron:
    - Processos principais e de renderização
    - Comunicação entre processos (IPC)
  - Criando sua primeira aplicação
    - Configuração inicial
    - Uso do main.js e index.html
  - Janelas e interfaces
    - Criação e gerenciamento de janelas (BrowserWindow)
    - Integração com HTML/CSS/JavaScript
  - Módulos do Electron
    - Menu: criar menus personalizados
    - Tray: adicionar ícones na bandeja do sistema
    - Dialog: janelas modais (abrir/guardar arquivos)
    - NativeImage: manipular imagens no sistema
  - Distribuição
    - Empacotar sua aplicação com electron-packager ou electron-builder
    - Criar instaladores para Windows, macOS e Linux

- ### Avançado no Electron

  - Integrar APIs do sistema operacional
    - Sistema de notificações
    - Manipular a bandeja e atalhos globais
  - Persistência de Dados
    - Usar bancos de dados locais (SQLite, NeDB, ou IndexedDB)
    - Armazenar configurações com electron-store
  - Segurança
    - Práticas de segurança em aplicações Electron
    - Isolar processos de renderização

- ### Construção do Backend com Node.js

  - Frameworks e Ferramentas
    - Express.js: criar APIs e servidores HTTP
    - Socket.IO: comunicação em tempo real (se necessário)
  - Autenticação e Segurança
    - JWT (JSON Web Tokens) para autenticação de usuários
    - Criptografia de senhas com bcrypt
    - Proteção contra ataques comuns (XSS, CSRF, etc.)
  - Gerenciamento de Arquivos e Uploads
    - Upload de arquivos com multer
    - Manipulação de arquivos no servidor
  - Integração com Banco de Dados
    - PostgreSQL (ou outro de sua escolha)
    - ORM/Query Builder: Sequelize ou Knex.js

- ### Integração Frontend + Backend

  - Use APIs REST para que o backend se comunique com o Electron.
  - Caso precise de atualizações em tempo real, use WebSockets (com Socket.IO).

- ### PostgreSQL

  - Instalação e Configuração
    - Criar tabelas e esquemas
    - Configurar usuários e permissões
  - Consultas Básicas
    - SELECT, INSERT, UPDATE, DELETE
    - Joins e subconsultas
  - Avançado
    - Índices e otimização de consultas
    - Transações e bloqueios
  - Integração com Node.js
    - Usar bibliotecas como pg ou Sequelize

- ### Testes e Qualidade

  - Testes Unitários
    - Usar ferramentas como Jest ou Mocha para testar funções e APIs
  - Testes de Integração
    - Testar o sistema completo, incluindo banco de dados e API
  - Linting e Formatação
    - ESLint para encontrar erros no código
    - Prettier para formatação automática
  - CI/CD
    - Configurar pipelines para automação de testes e deploy

- ### Distribuição e Publicação

  - Empacotar o Sistema
    - Electron-builder para criar instaladores multiplataforma.
  - Licenciamento
    - Implementar um sistema de verificação de licença (se aplicável).
  - Marketplace (opcional)
    - Criar uma API para gerenciar vendas e registros de módulos.
