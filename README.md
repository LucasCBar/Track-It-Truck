# Projeto Track It Truck 🚚

# Ideia do Projeto 

A ideia deste projeto surgiu da necessidade de criar um mapa em uma aplicação para trabalhos acadêmicos. Encontrei a framework "Leaflet" e despertou minha curiosidade em utilizá-la. Então, pensei em um projeto que exibisse a localização de diferentes caminhões e seus respectivos estados de operação.

# Objetivo

O objetivo deste projeto foi aplicar meus conhecimentos em JavaScript, aprofundar meu conhecimento na framework "Leaflet" e desenvolver o frontend desta aplicação.

Para elaborar esta aplicação, foi necessário utilizar conhecimentos em JavaScript, HTML, CSS e JSON Server.

# Como foi feito o Desafio?

Com a ideia em mente, criei um arquivo JSON para simular o backend da aplicação e gerar uma API para construir o frontend.

Para criar a API, simulei um banco de dados com as seguintes tabelas: ```equipment```, ```equipmentModel```, ```equipmentPositionHistory```, ```equipmentState```, ```equipmentStateHistory```, para armazenar todas as informações provenientes do backend.

Após gerar a API, o próximo passo foi compreender a biblioteca "Leaflet" para criar o mapa e aplicar meus conhecimentos na construção do frontend.

# Como utilizar a aplicação?

Os passos para rodar o projeto são:

1. Ter o Node.js instalado na máquina;
2. Também é necessário ter a biblioteca JSON Server instalada. Se esse não for o caso, é possível baixá-la dando o seguinte comando no prompt de comando: ```npm install -g json-server```;
3. Rode o seguinte comando para criar a API fake: ```json-server --watch ./data/db.json```;

# Tecnologias escolhidas

- [HTML] -  Linguagem de marcação de HiperTexto, define o significado e a estrutura do conteúdo da web.;
- [CSS] - linguagem de estilo, amplamente utilizada com HTML e representa diversas possibilidades para a formatação;
- [JavaScript] -  Linguagem de programação usada por desenvolvedores para fazer páginas interativas da Internet;
- [Node] - Plataforma de software de código aberto construída sobre o motor JavaScript do Google Chrome que permite a execução de código JavaScript no servidor;
- [JSON Server] - Biblioteca JavaScript que permite criar rapidamente uma API RESTful simulada usando um arquivo JSON como fonte de dados;