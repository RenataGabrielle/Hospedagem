Documentação e Hospedagem

Este projeto é uma aplicação Spring Boot que implementa um sistema de CRUD (Create, Read, Update, Delete) para duas entidades relacionadas: Documento e Categoria . O objetivo principal é demonstrar a implementação de uma API RESTful completa, utilizando Spring Data JPA para persistência de dados (com H2 em memória para este exemplo) e a integração do Swagger/OpenAPI para a documentação automática da API.

O relacionamento entre as entidades é de um para muitos (One-to-Many) , onde uma Categoriapode ter múltiplos Documentos, e um Documentopertence a uma única Categoria.

Passos para Execução Local
Para executar a aplicação localmente, você precisa ter o Java Development Kit (JDK) 17 ou superior e o Apache Maven instalado.

Clone o repositório (assumindo que este código será versionado no GitHub):

git clone [LINK_DO_SEU_REPOSITORIO]
cd pratica09-hospedagem
Compile e empacote uma aplicação usando o Maven:

mvn clean package
Execute o arquivo JAR gerado:

java -jar target/pratica09-hospedagem-0.0.1-SNAPSHOT.jar
A aplicação estará acessível em http://localhost:8080.

Documentação da API (Swagger/OpenAPI)
A documentação interativa da API foi gerada automaticamente utilizando o Springdoc OpenAPI .

Link da Documentação Swagger (Local): http://localhost:8080/swagger-ui.html

Link da Documentação Swagger (Hospedada no Render): https://hospedagem-caun.onrender.com/swagger-ui/index.html (Este link deve ser substituído pelo link real após o deploy)

Como acessar e usar a documentação
Após iniciar o aplicativo (localmente ou acessando o link do Render), navegue para o endereço do Swagger UI.
Você verá uma lista de endpoints agrupados por tags (Documentos e Categorias).
Clique em qualquer endpoint para expandir e ver os detalhes, incluindo parâmetros de requisição, exemplos de corpo de requisição e respostas.
Para testar um endpoint , clique no botão "Try it out" , preencha os campos necessários e clique em "Execute" .
Sobre
hospedagem-caun.onrender.com/swagger-ui/index.html
Recursos
 Leia-me
 Atividade
Estrelas
 0 estrelas
Observadores
 0 pessoas assistindo
Garfos
 0 garfos
Repositório de
Lançamentos
Nenhuma versão publicada
sêmen
Nenhum pacote publicado
Línguas
Java
94,2%
 
Dockerfile
5,8%
