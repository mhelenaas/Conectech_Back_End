# Projeto Backend Conectech

[![License](https://img.shields.io/github/license/seu-usuario/seu-repositorio)](https://github.com/seu-usuario/seu-repositorio/blob/main/LICENSE)

# Sobre o Projeto

O Projeto Backend Conectech é uma aplicação desenvolvida para fornecer uma API robusta e eficiente para suportar as funcionalidades do frontend Conectech. Utilizando tecnologias modernas e boas práticas de desenvolvimento, o projeto oferece um ambiente seguro e escalável para lidar com as operações de cadastro de usuários, gerenciamento de posts e comentários, entre outras funcionalidades.

## Funcionalidades

- **Cadastro de Usuário**: Permite que os usuários se cadastrem no aplicativo fornecendo informações básicas, como nome, e-mail, senha e habilidades.
- **Login**: Esta funcionalidade permite que usuários registrados acessem suas contas fornecendo suas credenciais de login.
- **Escolha de Interesses**: Permite que os usuários personalizem sua experiência na plataforma selecionando tópicos ou áreas de interesse.
- **Gerenciamento de Eventos**: Permite que os usuários visualizem, participem e criem eventos relacionados à tecnologia.
- **Grupos e Comunidades**: Esta funcionalidade permite que os usuários se juntem a grupos e comunidades de interesse e participem de discussões relacionadas à tecnologia.
- **Fórum**: Oferece um espaço para os usuários participarem de discussões sobre diversos tópicos relacionados à tecnologia.
- **Exploração de Temas**: Permite que os usuários descubram e explorem uma variedade de temas relacionados à tecnologia.
- **Chat**: Esta funcionalidade permite que os usuários se comuniquem por meio de mensagens de texto.
- **Feed de Atividades**: Fornece aos usuários uma lista de atividades e postagens.
- **Favoritos**: Permite que os usuários marquem e acessem rapidamente itens de interesse dentro do aplicativo.
- **Postagem de Conteúdo**: Permite que os usuários compartilhem conteúdo, ideias, perguntas e informações com outros usuários na plataforma.
- **Populares**: Os usuários podem visualizar postagens ou usuários que estão em alta.

## Tecnologias Utilizadas

- **Java**: Linguagem de programação amplamente utilizada para o desenvolvimento de aplicativos corporativos.
- **Spring Boot**: Framework que simplifica o desenvolvimento de aplicativos Java, fornecendo um conjunto de ferramentas e bibliotecas para facilitar a criação de APIs RESTful.
- **Spring Data JPA / Hibernate**: Facilita a integração com o banco de dados e simplifica as operações de persistência de dados.
- **MongoDB**: Banco de dados NoSQL utilizado para armazenar os dados da aplicação.
- **Maven**: Gerenciador de dependências e construção de projetos para Java.
  
# Como Executar o Projeto

## Pré-requisitos
  Docker
- Java
- Maven
- Spring Boot

## Executando o Projeto

1. Clone o repositório:
   ```bash
   git clone https://github.com/SIN-disciplina-PI3/Conectech_Back_End
   ```
Entre na pasta do projeto:
```bash
Copy code
cd repositorio que se encontra o dockerfile
```
Compile o projeto:
Nessa etapa é nescessario ter o Docker Instalado na sua maquina e copie esse codigo
```bash
Copy code
docker-compose up --build
```
Após essa etapa vai aparecer uma mensagem de build complete successfully e voce vai poder verificar o status da aplicaçao por meio do navegador colando
http://localhost:8080/users 
Com isso vai aparecer uma mensagem de [] indicando que o docker conseguiu subir a aplicação e conseguiu criar a imagem do MongoDb corretamente na sua maquina

# Autor
Este projeto foi desenvolvido por Felipe Ferreira,Lara Nunes,Cauã Sebastian,Thales Thiago,Maria Helena e Edgar Tavares.
