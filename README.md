# Literalura

Literalura é uma aplicação Java/Spring Boot desenvolvida para amantes de livros. Com ela, você pode buscar livros, listar livros e autores registrados, e explorar diversas funcionalidades relacionadas à leitura e organização de sua biblioteca pessoal.

## Funcionalidades

1. **Buscar livros pelo título**: Utilize a API Gutendex para encontrar livros pelo título.
2. **Listar livros registrados**: Veja todos os livros cadastrados no banco de dados.
3. **Listar autores registrados**: Confira todos os autores dos livros registrados.
4. **Listar autores vivos em um determinado ano**: Descubra quais autores estavam vivos em um ano específico.
5. **Listar autores nascidos em determinado ano**: Veja os autores nascidos em um ano específico.
6. **Listar autores por ano de sua morte**: Conheça os autores que faleceram em um ano específico.
7. **Listar livros em um determinado idioma**: Encontre livros registrados em um idioma específico.
8. **Encerrar a aplicação**: Finalize a execução do programa.

## Tecnologias Utilizadas

- **Java 17**
- **Spring Boot 2.7**
- **Hibernate**
- **PostgreSQL**
- **Gutendex API**
- **Maven**

## Configuração do Projeto

### Pré-requisitos

- Java 17 ou superior
- Maven
- PostgreSQL

### Instalação

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/literalura.git
   cd literalura

Configure o banco de dados no arquivo application.properties:
spring.datasource.url=jdbc:postgresql://localhost:5432/literalura
spring.datasource.username=seu-usuario
spring.datasource.password=sua-senha
spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true

Execute o projeto:
mvn spring-boot:run

Estrutura do Projeto
br.com.alura.literalura: Pacote principal do projeto.
principal: Contém a classe Principal, que gerencia a execução da aplicação.
model: Contém as classes de modelo (Livro, Autor, LivroDTO, AutorDTO).
repository: Contém as interfaces de repositório Spring Data JPA.
service: Contém as classes de serviço (ConsumoAPI, ConverteDados).
Uso
Ao iniciar a aplicação, o menu principal será exibido com as opções disponíveis. Basta seguir as instruções na tela para navegar pelas funcionalidades.

Exemplo de Uso
Buscar livros pelo título:

Digite 1 e pressione Enter.
Insira o título do livro que deseja buscar.
A aplicação fará uma consulta à API Gutendex e exibirá os resultados encontrados.
Listar livros registrados:

Digite 2 e pressione Enter.
A aplicação listará todos os livros registrados no banco de dados.
Listar autores registrados:

Digite 3 e pressione Enter.
A aplicação listará todos os autores dos livros registrados.
Listar autores vivos em um determinado ano:

Digite 4 e pressione Enter.
Insira o ano desejado.
A aplicação listará os autores que estavam vivos naquele ano.
Listar autores nascidos em determinado ano:

Digite 5 e pressione Enter.
Insira o ano desejado.
A aplicação listará os autores que nasceram naquele ano.
Listar autores por ano de sua morte:

Digite 6 e pressione Enter.
Insira o ano desejado.
A aplicação listará os autores que morreram naquele ano.
Listar livros em um determinado idioma:

Digite 7 e pressione Enter.
Insira o código do idioma desejado (por exemplo, en para Inglês, pt para Português).
A aplicação listará todos os livros registrados no banco de dados naquele idioma.
Encerrar a aplicação:

Digite 0 e pressione Enter.
A aplicação será encerrada.
Contribuição
Se você deseja contribuir para o projeto, siga os passos abaixo:

Faça um fork do repositório.
Crie uma nova branch: git checkout -b minha-feature.
Faça suas alterações e commit: git commit -m 'Minha nova feature'.
Envie para o repositório original: git push origin minha-feature.
Abra um Pull Request.
Licença
Este projeto está licenciado sob a MIT License. Veja o arquivo LICENSE para mais detalhes.

Contato
Se você tiver alguma dúvida ou sugestão, sinta-se à vontade para entrar em contato.

