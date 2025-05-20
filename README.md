## 🧠 Perguntas para medir aprendizado (responder neste README)

1. **Explique com suas palavras o papel de cada camada da arquitetura MVC usada neste projeto.**  
   Model: O Model é responsável por criar os bancos de dados com as tabelas e criar as relações para que sejam usadas dentro de um contexto, a partir de métodos como JOJN e CRUD. <br>

   Controller: O controller é uma intermediação entre a view e o model. Ele pega as requisições e seleciona as ifnromações necessárias que estão no model. <br>

   View: É a camada responsável pela interface com o usuário. Através da página inicial e seus formulários, ela coleta os dados inseridos pelos usuários, como informações de alunos e cursos.

2. **Como ocorre o envio e o recebimento de dados no formato JSON neste projeto?**  
   O envio e recebimento de dados em JSON é feito por meio do Controller, que lida com as requisições e responde no formato JSON.
   Um exemplo de rota é: http://localhost:3000/alunos.
   Ao acessar essa rota, o servidor retorna uma lista de alunos em formato JSON, permitindo que outras aplicações ou o próprio front-end consumam esses dados de forma estruturada

3. **Qual a importância de usar HTML básico com formulários e tabelas para organizar e manipular dados no navegador?**  
  Utilizar HTML simples com formulários e tabelas é essencial para facilitar a entrada, visualização e organização dos dados diretamente no navegador. Isso torna a interface mais acessível e intuitiva para o usuário final.
