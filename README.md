# Parking Control API - Spring Boot Project

Este projeto é uma implementação utilizando o framework **Spring Boot**, explorando conceitos como *Inversão de Controle*, *Injeção de Dependências*, *Beans*, *Spring MVC*, *Spring Data JPA* e *Spring Validation*. A API resultante conta com recursos como *Pageable*, métodos `getAll`, `getOne`, `post`, `delete`, `update` e *Global Custom Date*.

## Tecnologias Utilizadas

- **Spring Boot**
- *Inversão de Controle*
- *Injeção de Dependências*
- **Spring MVC**
- **Spring Data JPA**
- **Spring Validation**

## Funcionalidades Principais

### Pageable
A API suporta paginação, permitindo a recuperação de dados de maneira eficiente através do conceito de *Pageable*.

### Métodos Principais
- **getAll:** Recupera todos os registros disponíveis.
- **getOne:** Recupera um único registro com base em um identificador específico.
- **post:** Adiciona um novo registro à base de dados.
- **delete:** Remove um registro existente com base no identificador.
- **update:** Atualiza as informações de um registro existente.

### Global Custom Date
A API implementa um tratamento global personalizado para datas, garantindo consistência e formatos padronizados em toda a aplicação.

## Como Utilizar

1. **Pré-requisitos:** Certifique-se de ter o ambiente Spring Boot configurado.
2. **Clone o Repositório:** `git clone https://github.com/seu-usuario/parking-control-api.git`
3. **Build do Projeto:** Execute o comando `mvn clean install` para realizar o build do projeto.
4. **Execute a Aplicação:** Inicie a aplicação Spring Boot.
5. **Acesse a API:** Acesse os endpoints fornecidos pela API para interagir com as funcionalidades implementadas.

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir problemas (issues) ou enviar pull requests para melhorar este projeto.

## Licença

Este projeto está licenciado sob a [Licença MIT](LICENSE), o que significa que você pode utilizá-lo livremente em seus próprios projetos.
