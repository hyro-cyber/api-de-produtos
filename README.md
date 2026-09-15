# API de Produtos

API REST desenvolvida em Java com Spring Boot para gerenciamento de produtos, permitindo operações de cadastro, consulta, atualização e remoção (CRUD).

## 📋 Sobre o projeto

Esta API foi construída com o objetivo de oferecer um serviço simples e eficiente para o gerenciamento de produtos, servindo como base para sistemas de e-commerce, controle de estoque ou catálogos digitais.

## 🚀 Tecnologias utilizadas

- **Java** — linguagem principal do projeto
- **Spring Boot** — framework para criação da API REST
- **Maven** — gerenciador de dependências e build
- **Banco de dados** — *(especifique aqui: MySQL, PostgreSQL, H2, etc.)*
- **Spring Data JPA** — *(se utilizado, para persistência de dados)*

## 📁 Estrutura do projeto

```
produto-api/
├── src/
│   ├── main/
│   │   ├── java/          # Código-fonte principal (controllers, services, models)
│   │   └── resources/     # Arquivos de configuração (application.properties/yml)
│   └── test/               # Testes automatizados
├── .mvn/                   # Wrapper do Maven
├── mvnw / mvnw.cmd         # Scripts para rodar o Maven sem instalação local
├── pom.xml                 # Configurações e dependências do projeto
└── README.md
```

## ⚙️ Como executar o projeto

### Pré-requisitos

- Java JDK instalado (versão *(especifique: 17, 21, etc.)* ou superior)
- Maven (ou use o `mvnw` incluso no projeto, que não exige instalação)

### Passo a passo

1. Clone o repositório:
```bash
git clone https://github.com/hyro-cyber/api-de-produtos.git
```

2. Acesse a pasta do projeto:
```bash
cd api-de-produtos
```

3. Execute a aplicação:
```bash
./mvnw spring-boot:run
```
No Windows, use:
```bash
mvnw.cmd spring-boot:run
```

4. A API estará disponível em:
```
http://localhost:8080
```

## 📌 Endpoints principais

| Método | Endpoint | Descrição |
|--------|----------|-----------|
| GET | `/produtos` | Lista todos os produtos |
| GET | `/produtos/{id}` | Busca um produto pelo ID |
| POST | `/produtos` | Cadastra um novo produto |
| PUT | `/produtos/{id}` | Atualiza um produto existente |
| DELETE | `/produtos/{id}` | Remove um produto |

*(Ajuste esta tabela conforme os endpoints reais implementados no seu projeto.)*

## 🧪 Testes

Para rodar os testes automatizados do projeto:
```bash
./mvnw test
```

## 🤝 Contribuindo

Contribuições são bem-vindas! Sinta-se à vontade para abrir uma *issue* ou enviar um *pull request*.

## 📄 Licença

Este projeto está sob a licença *(especifique: MIT, Apache 2.0, etc.)*. Veja o arquivo `LICENSE` para mais detalhes.

## 👤 Autor

Desenvolvido por **hyro-cyber**.