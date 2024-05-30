
### Descrição:
<p>
O projeto consiste no desafio de construir nosso próprio catálogo de livros, utilizando para isso uma API gratuita chamada Gutendex, que possui dados de mais de 70 mil livros, ela é utilizada para o consumo dos dados, onde através de um menu de interação o usuário informa o nome do livro que deseja buscar na web, se o livro for encontrado os dados são retornados no formato Json, caso contrário uma mensagem informa que o livro não foi encontrado. 
</p>

<p>
No caso do livro encontrado será feita a desserealizaçao dos dados vindos no formato Json para o formato texto, através da biblioteca Jakcson. Após isso através de um CRUD é feita a persistência dos dados no Gerenciador de Banco de Dados Relacional Postgre, para serem manipulados posterirormente, nesta etapa são utilizadas apenas duas operações: Create e Read.
</p>
<p>
A interação com o usuário é feita através de um menu de opções, onde o usuário faz a escolha da operação desejada digitando o número correspondente a ela, assim o App faz o processamento do dados inseridos e retorna uma informação ao usuário.
</p> 
<p>
Atualmente busca pelos livros na API pode ser feita em quatro idimoas: Português, Inglês, Francês e Espanhol. Os Dados armazenados no Banco de Dados podem ser buscados de diversas maneiras, como por exemplo: Lista de autores, lista de livros, livros mais baixados.
</p> 

### Tecnologias Utilizadas:
<div> 
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white">   
</div>


