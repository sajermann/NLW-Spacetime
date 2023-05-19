# 🚀 Spacetime

Projeto da Semana Next Level Week (NLW) que foi transmitida pelo grupo Rocketseat do dia 15/05/2023 à 19/05/2023, ministrado pelo Diego Fernandes (CTO Rocketseat).

O projeto consiste em criar uma plataforma de mídia, onde o usuário pode fazer upload de imagens com descrições para visualizar posteriormente como se fosse uma cápsula do tempo, essa plataforma é completa, contendo Back-end, Front-end e o Mobile.

O Back-end gerencia as APIs resultantes do banco de dados, o Front-end fornece a interface gráfica na Web, e o Mobile fornece a interface gráfica no Mobile.

## Tecnologias

📁 Back-end: NodeJs - Utilizando [fastify](https://www.fastify.io/)

🗄️ Banco de Dados: SQLite - Utilizando [prisma](https://www.prisma.io/)

🖥️ Front-end: ReactJs - Utilizando [tailwind](https://tailwindcss.com/) e [@next](https://nextjs.org/)

📱 Mobile: React Native - Utilizando [expo](https://expo.dev/)

### Para executar a aplicação

Execute `npm install` no server, web e mobile, para instalar as dependências.

Execute `npm start` na pasta server (Porta 3333), `npm start` nas pastas web (Porta 3000) e mobile (Porta 19000) lembrando que para o mobile precisa executar o Expo no seu celular ou utilizar um emulador android.

É necessário atualizar os endereços de IP dentro dos projetos de acordo com cada computador.

É necessário também cadastrar duas aplicações de OAuth no Github e incluir os secrets em arquivos .env para que a aplicação consiga gerenciar as autenticações.

No Mobile, caso ocorra algum erro relacionado a fonts ou dependências, execute `npx expo install`