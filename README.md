# Projeto Track It Truck 🚚

# Descrição

O problema proposto foi desenvolver o frontend de uma aplicação web que trate e exiba essas informações para os gestores da operação.

Para elaborar esse teste, foi necessário usar meus conhecimentos em Javascript, HTML, CSS e análise de banco de dados.

# Como foi feito o Desafio?

Após ler e compreender o que foi pedido na elaboração do teste, elaborei um projeto no Figma para ter uma referência do estilo e da usabilidade da aplicação.

Com isso em mãos, ficou claro quais eram os meus próximos passos. Logo em seguida, analisei os dados disponibilizados para fazer a execução do teste. Os arquivos JSON simulam um banco de dados. Com isso, criei outro arquivo JSON (```db.json```) e passei todos os dados para ele para criar uma API falsa, utilizando a biblioteca JSON Server.

Com a API em mãos, os dois últimos passos foram compreender o banco de dados que os dados disponíveis estavam simulando e escolher uma biblioteca para fazer o mapa. A biblioteca utilizada foi a Leaflet.

# Como utilizar a aplicação?

Os passos para rodar o projeto são:

1. Ter o Node.js instalado na máquina;
2. Também é necessário ter a biblioteca JSON Server instalada. Se esse não for o caso, é possível baixá-la dando o seguinte comando no prompt de comando: ```npm install -g json-server```;
3. Rode o seguinte comando para criar a API falsa: ```json-server --watch ./data/db.json```;

# Tecnologias escolhidas

- [HTML] -  Linguagem de marcação de HiperTexto, define o significado e a estrutura do conteúdo da web.;
- [CSS] - linguagem de estilo, amplamente utilizada com HTML e representa diversas possibilidades para a formatação;
- [JavaScript] -  Linguagem de programação usada por desenvolvedores para fazer páginas interativas da Internet;
- [Node] - Plataforma de software de código aberto construída sobre o motor JavaScript do Google Chrome que permite a execução de código JavaScript no servidor;
- [JSON Server] - Biblioteca JavaScript que permite criar rapidamente uma API RESTful simulada usando um arquivo JSON como fonte de dados;
