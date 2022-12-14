[![NPM](https://img.shields.io/npm/l/react)](https://github.com/lucarauj/spring-Boot3-API-Rest-Java/blob/main/LICENSE)

<h1 align="center"> Curso Spring Boot 3 API Rest em Java: </h1>
<h2 align="center"> Gerenciando uma clínica médica </h2>

<p align="center"><img width="150px" src="https://github.com/lucarauj/assets/blob/main/ApiJavaSpring.png" /></p>

### ❌ Abordagens:

- Criação de uma API Rest em Java com Spring Boot do zero
- Desenvolvimento de CRUDs utilizando o banco de dados MySQL
- Utilização do Flyway como ferramenta de Migrations da API
- Realização de validações utilizando o Bean Validation
- Realização de paginação dos dados da API

### ⛏ Criação do projeto base no [Spring Initializr](https://start.spring.io/) com as seguintes dependências:

- Spring boot DevTools
- Lombok
- Spring Web
- Validation
- MySQL Driver
- Spring Data JPA
- Flyway Migration

### ⚙ Configurando o arquivo application.properties

```
spring.datasource.url=jdbc:mysql://localhost:3306/vollmed_api
spring.datasource.username= root
spring.datasource.password=
```

### ❌ Utilizando o Xampp/MySQL:

<img width="600px" src="https://github.com/lucarauj/spring-Boot3-API-Rest-Java/blob/main/images/Xampp.png"/>

### ▶ Utilizando o Postman:

- POST
<img width="750px" src="https://github.com/lucarauj/spring-Boot3-API-Rest-Java/blob/main/images/POST.png"/>

- GET
<img width="750px" src="https://github.com/lucarauj/spring-Boot3-API-Rest-Java/blob/main/images/GET.png"/>

- GET PAGINAÇÃO
<img width="750px" src="https://github.com/lucarauj/spring-Boot3-API-Rest-Java/blob/main/images/GET_PAGINACAO.png"/>

- GET ORDENAÇÃO
<img width="750px" src="https://github.com/lucarauj/spring-Boot3-API-Rest-Java/blob/main/images/GET_ORDENACAO.png"/>

- PUT
<img width="750px" src="https://github.com/lucarauj/spring-Boot3-API-Rest-Java/blob/main/images/PUT.png"/>

- DELETE
<img width="750px" src="https://github.com/lucarauj/spring-Boot3-API-Rest-Java/blob/main/images/DELETE.png"/>

### ❌ Consultando banco de dados 👉 PhpMyAdmin/MySQL:

<img width="900px" src="https://github.com/lucarauj/spring-Boot3-API-Rest-Java/blob/main/images/Select_From_Medicos.png"/>

### 📝 Anotações utilizadas no projeto:

- @RestController
- @RequestMapping
- @GetMapping
- @PostMapping
- @RequestBody
- @Table
- @Entity
- @Id
- @GeneratedValue
- @Enumerated
- @Embedded
- @Embeddable
- @Getter
- @NoArgsConstructor
- @AllArgsConstructor
- @EqualsAndHashCode
- @Autowired
- @Transactional
- @NotBlank: um atributo do tipo String não pode ser nulo e nem vazio;
- @Email
- @Pattern
- @NotNull
- @Valid
- @GenerationType
- @PageableDefault
- @PutMapping
- @DeleteMapping
- @PathVariable

### 🛠 Configuração para comandos SQL disparados no banco de dados ```application.properties```:

```
spring.jpa.show-sql=true
spring.jpa.properties.hibernate.format_sql=true
```

### 🚀 Principais tecnologias utilizadas no projeto:

<div style="display: inline_block"><br>
<img align="center" alt="Lucarauj-Java" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg">
<img align="center" alt="Lucarauj-Postman" height="50" width="90" src="https://github.com/lucarauj/assets/blob/main/postman.png">
<img align="center" alt="Lucarauj-Spring" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/spring/spring-original.svg">
<img align="center" alt="Lucarauj-SpringBoot" height="40" width="110" src="https://github.com/lucarauj/assets/blob/main/SpringBoot.jpeg">
<img align="center" alt="Lucarauj-Maven" height="50" width="60" src="https://github.com/lucarauj/assets/blob/main/Maven-Apache.svg">
<img align="center" alt="Lucarauj-Mysql" height="50" width="70" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original-wordmark.svg">
</div>

## Aluno

#### Lucas Araujo

<a href="https://www.linkedin.com/in/lucarauj"><img alt="lucarauj | LinkdeIN" width="40px" src="https://user-images.githubusercontent.com/43545812/144035037-0f415fc7-9f96-4517-a370-ccc6e78a714b.png" /></a>
