
# Rotten Potatoes
Implementação da aplicação RottenPotatoes desenvolvida em Ruby utilizando o framework Rails. Este trabalho foi desenvolvido para disciplina de Engenharia de Software, durante o segundo semestre de 2025.

## Funcionalidades Implementadas
A aplicação atualmente possui as seguintes funcionalidades:

* Listagem de todos os filmes cadastrados no banco de dados.
* Visualização de detalhes de um filme específico.
* Criação e cadastro de novos filmes através de um formulário web.
* **Ordenação dinâmica da lista de filmes**: É possível reordenar a lista clicando nos cabeçalhos das colunas **Título** (Movie Title) e **Data de Lançamento** (Release Date).
* **Destaque visual (highlight)**: A coluna que está sendo usada para a ordenação é destacada visualmente para melhor feedback ao usuário.

## Tecnologias Utilizadas
* **Ruby on Rails**: Framework principal da aplicação.
* **Ruby**: Linguagem de programação base.
* **SQLite3**: Banco de dados padrão de desenvolvimento.
* **HTML/ERB**: Para a estruturação e renderização das páginas.
* **CSS**: Para a estilização básica.
* **Git e GitHub**: Para versionamento de código.

## Como instalar o Projeto
* Instale o Ruby on Rails a partir deste link: 'https://guides.rubyonrails.org/getting_started.html'
* Clone este repositório do Github (utilizando o comando 'git clone' e a URL do repositório) em sua IDE de preferência (esse projeto foi desenvolvido no VS Code);
* Vá para o diretório do projeto (comando 'cd nome_do_diretório');
* Execute os comandos 'rails db:create', 'rails db:migrate' para criar e configurar o banco de dados;
* Execute o comando 'rails db:seed' para incluir no banco de dados os filmes do arquivo seeds.rb;
* EXTRA: você pode verificar as routes do projeto com 'rails routes';
* Inicie o servidor Rails com 'rails server' para rodar o projeto;
* Por fim, acesse 'http://localhost:3000/movies' no seu navegador para visualizar o projeto;

## Autor
* Este projeto foi desenvolvido por Maria Carolina Burgum Abreu Jorge.
* **Referência Bibliográfica**: Software Engineering as a Service: An Agile Approach Using Cloud Computing, de Armando Fox e David Patterson (ed. 2.0b7).

