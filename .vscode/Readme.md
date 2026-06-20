Batalha Naval

Este projeto é uma aplicação web interativa baseada no clássico jogo de estratégia Batalha Naval, desenvolvida com foco em lógica de programação, manipulação de estado e componentização utilizando React.

A aplicação permite ao jogador posicionar estrategicamente seus navios em um tabuleiro e realizar ataques contra o adversário, simulando as regras tradicionais do jogo. Cada jogada é processada dinamicamente, atualizando o estado do jogo em tempo real e fornecendo feedback visual sobre acertos, erros e progresso da partida.

Além disso, o projeto explora conceitos importantes do desenvolvimento front-end moderno, como renderização dinâmica de componentes, gerenciamento de estado, reutilização de código e integração com APIs (quando aplicável).

O sistema foi projetado para ser intuitivo e responsivo, proporcionando uma experiência de usuário clara e envolvente, ao mesmo tempo em que demonstra boas práticas de organização de código e separação de responsabilidades.

🚀 Tecnologias

As principais tecnologias utilizadas no projeto:

React
JavaScript (JS)
HTML5
CSS3
(Opcional) React Query ou Fetch API para requisições

▶️ Como Rodar

Siga os passos abaixo para executar o projeto localmente:

# Clone o repositório
git clone https://github.com/seu-usuario/batalha-naval.git

# Entre na pasta do projeto
cd batalha-naval

# Instale as dependências
npm install

# Execute o projeto
npm start

Abra no navegador:

http://localhost:3000

✨ Funcionalidades
⚓ Criação e exibição do tabuleiro do jogo
🚢 Posicionamento de navios
🎯 Sistema de ataque (acerto e erro)
🔄 Atualização dinâmica do estado do jogo
🧠 Lógica para verificar vitória ou derrota
🧩 Componentes reutilizáveis em React
📡 (Opcional) Consumo de API para dados do jogo

📁 Estrutura do Projeto
src/
 ├── components/
 ├── pages/
 ├── services/
 ├── App.js
 └── index.js

🎯 Objetivos do Projeto
Praticar lógica de programação aplicada a jogos
Trabalhar com gerenciamento de estado no React
Criar componentes reutilizáveis e organizados
Simular regras reais de um jogo clássico
Desenvolver uma interface interativa e dinâmica

🧠 Como o Jogo Funciona
O jogador posiciona seus navios no tabuleiro
Cada célula do tabuleiro pode ser atacada
O sistema identifica automaticamente:
Acertos (quando atinge um navio)
Erros (quando atinge água)
O jogo acompanha o estado de cada navio
Quando todos os navios são destruídos, a partida termina.

👨‍💻 Autor

Desenvolvido por Marcos Vinícius
