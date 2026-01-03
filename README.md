# SivaLabs Marketplace

A collection of plugins that helps building Spring Boot applications using Claude Code.

## Installation

```
/plugin marketplace add sivaprasadreddy/sivalabs-marketplace
/plugin enable sivaprasadreddy/sivalabs-marketplace
/plugin install spring-boot-dev@sivalabs-marketplace
```

## Available Plugins

### spring-boot-dev

A plugin for Spring Boot application development using Java, Spring Boot, Spring Data JPA technology stack.

#### Skills

| Skill                                     | Description                                                    |
|-------------------------------------------|----------------------------------------------------------------|
| **spring-boot-package-structure-creator** | Creates recommended package structure for Spring Boot projects |
| **jpa-entity-creator**                    | Creates JPA Entitiies                                          |
| **spring-data-jpa-repo-creator**          | Creates Spring Data JPA Repositories                           |
| **spring-service-creator**                | Creates Spring Service layer classes                           |
| **spring-rest-api-creator**               | Creates Spring MVC REST API Controllers                        |

#### MCP Servers

| Server            | Description                            |
|-------------------|----------------------------------------|
| **context7**      | General library documentation lookup   |
| **Playwright**    | Browser automation for testing         |

## How to use?

- Clone this repository
  `git clone https://github.com/sivaprasadreddy/sivalabs-marketplace.git`
- Install the marketplace and plugins
  ```shell
  $ claude
  /plugin marketplace add sivaprasadreddy/sivalabs-marketplace
  /plugin enable sivaprasadreddy/sivalabs-marketplace
  /plugin install spring-boot-dev@sivalabs-marketplace
  ```

- Verify the plugins are installed successfully using `/plugins` command in Claude CLI
- Create a Spring Boot project with Web, Validation, Spring Data JPA, H2 starters
- In the Claude CLI, prompt "Implement CRUD REST API for Person with id, name, email and phone fields"
