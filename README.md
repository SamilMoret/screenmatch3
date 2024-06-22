# Screenmatch API

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-F2F4F9?style=for-the-badge&logo=spring-boot)

## 📜 Descrição

Este projeto é resultado do curso "Java: criando sua primeira API e conectando ao front-end" da Alura. O objetivo foi criar uma API REST para fornecer dados a uma aplicação front-end, exercitando conceitos essenciais do desenvolvimento web com Java e Spring Boot.

## 🚀 Funcionalidades

- **API REST**: Transformação da aplicação Screenmatch em uma API REST.
- **Spring Boot**: Utilização do Spring Boot para configurar e executar a aplicação com um servidor embutido.
- **Controller**: Criação da classe responsável por receber as requisições.
- **Anotações Spring**: Utilização de @RestController, @RequestMapping, @GetMapping, entre outras.
- **Serviços**: Implementação de classes de serviço com @Service para fornecer dados ao controlador.
- **Rotas e Requisições**: Implementação completa das rotas esperadas pelo front-end.
- **Filtros e Detalhes**: Criação de filtros por categorias e páginas de detalhes com dados de todas as temporadas e episódios.

## 📚 Tecnologias Utilizadas

- Java
- Spring Boot
- Maven
- Spring Boot
- Front-end (HTML, CSS, JavaScript)

## 📂 Estrutura do Projeto
```
├── src
│ ├── main
│ │ ├── java
│ │ │ └── br
│ │ │ └── com
│ │ │ └── alura
│ │ │ └── screenmatch4
│ │ │ ├── controller
│ │ │ │ └── SerieController.java
│ │ │ ├── dto
│ │ │ ├── model
│ │ │ ├── repository
│ │ │ └── service
│ ├── resources
│ └── test
├── pom.xml
└── README.md
```

## 📋 Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/SamilMoret/screenmatch3.git
   ```
2. Navegue até o diretório do projeto:
```bash
cd screenmatch3
```
3. Execute o projeto com Maven:
```bash
mvn spring-boot:run
```
4. Acesse a aplicação em http://localhost:8082

## 📸 Imagens
Página Inicial

Detalhes da Série

## 🙌 Agradecimentos
Agradeço ao Programa ONE Oracle + Alura pelo excelente curso e às instrutoras Jacqueline Oliveira e Iasmin Araújo pelo conteúdo didático e enriquecedor.

<h3>🧑‍💻 Feito por:</h3>
<p>Samil Moret</p>
<a href="https://www.linkedin.com/in/samilmoret/"><img width="48" height="48" src="https://img.icons8.com/color/48/linkedin.png" alt="linkedin"/></a>
<a href="https://linkwhats.app/f27e11"><img width="48" height="48" src="https://img.icons8.com/color/48/whatsapp--v1.png" alt="whatsapp--v1"/></a>
