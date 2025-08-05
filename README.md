Chronos Pomodoro:

Este é um projeto de um timer Pomodoro moderno e personalizável, desenvolvido como parte de um curso de React com TypeScript. O objetivo foi criar uma aplicação robusta e bem estruturada para ajudar a gerenciar o tempo de trabalho e pausas.

Tecnologias Principais
O projeto foi construído com as seguintes tecnologias e ferramentas:

Linguagem Principal: TypeScript, para adicionar tipagem estática e melhorar a manutenibilidade do código.

Framework: React, para a construção da interface de usuário de forma declarativa e baseada em componentes.

Bundler: Vite, utilizado para um ambiente de desenvolvimento rápido e um build otimizado para produção.

Estilização: CSS modularizado, aplicando estilos específicos a cada componente.

Gerenciamento de Estado: Context API do React, combinada com o hook useReducer, para um gerenciamento de estado global e previsível.

Notificações: react-toastify, para exibir mensagens e alertas de forma elegante e não intrusiva.

Roteamento: react-router, para gerenciar as rotas e navegação entre as diferentes páginas da aplicação.

Timer: Web Worker, para executar a lógica do timer em um thread separado, evitando que a interface de usuário trave.

Funcionalidades:

Início e Pausa do Timer: Inicie, pause e reinicie a contagem do tempo de forma simples.

Ciclos Pomodoro Personalizáveis: Configure a duração do tempo de trabalho, pausa curta e pausa longa.

Histórico de Tarefas: Salve o histórico das tarefas concluídas com o timer.

Notificações Visuais: Receba notificações visuais no browser ao final de cada ciclo.

Instalação como Aplicativo (PWA)

O projeto inclui um Web Manifest, o que o torna um PWA (Progressive Web App). Isso significa que você pode instalá-lo diretamente do seu navegador, em dispositivos móveis ou desktop, para ter uma experiência de uso offline e mais fluida, como se fosse um aplicativo nativo.
