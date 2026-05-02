# CPFHub.io OpenAPI Specification

🇺🇸 **English** | [🇧🇷 Português](#português)

This repository contains the official OpenAPI Specification for the CPFHub.io API.

## What is CPFHub.io?

CPFHub.io is a REST API that provides comprehensive CPF consultation services in Brazil. It returns essential identity information such as full name, gender, and date of birth for any Brazilian CPF number, with high accuracy, low latency, and full LGPD compliance.

## Authentication

All API requests require an API key to be passed in the `x-api-key` header.

```http
x-api-key: YOUR_API_KEY
```

Get your free API key at [app.cpfhub.io](https://app.cpfhub.io).

## Important Links

*   **Documentation:** [https://cpfhub.io/documentacao](https://cpfhub.io/documentacao)
*   **MCP Server (AI Agents):** [https://github.com/cpfhub/cpfhub-mcp](https://github.com/cpfhub/cpfhub-mcp)
*   **Official SDKs:**
    *   [Node.js](https://github.com/cpfhub/cpfhub-node)
    *   [Python](https://github.com/cpfhub/cpfhub-python)
    *   [PHP](https://github.com/cpfhub/cpfhub-php)
    *   [Go](https://github.com/cpfhub/cpfhub-go)
    *   [Ruby](https://github.com/cpfhub/cpfhub-ruby)
    *   [Java](https://github.com/cpfhub/cpfhub-java)
    *   [.NET](https://github.com/cpfhub/cpfhub-dotnet)

## Accessing the OpenAPI Specification

The `openapi.yaml` file in this repository is the official and most up-to-date version of the CPFHub.io API specification.

**Direct Link to Raw Specification:**

`https://github.com/cpfhub/cpfhub-openapi/blob/main/openapi.yaml`

(Note: A publicly hosted version at `https://api.cpfhub.io/openapi.yaml` will be made available soon for direct machine consumption.)

## Examples

Check the `examples/` directory for sample requests and responses:

*   [cpf-request.json](examples/cpf-request.json)
*   [cpf-response.json](examples/cpf-response.json)

---

# Português

Este repositório contém a Especificação OpenAPI oficial para a API do CPFHub.io.

## O que é o CPFHub.io?

O CPFHub.io é uma API REST que fornece serviços abrangentes de consulta de CPF no Brasil. Ele retorna informações essenciais de identidade, como nome completo, gênero e data de nascimento para qualquer número de CPF brasileiro, com alta precisão, baixa latência e total conformidade com a LGPD.

## Autenticação

Todas as requisições à API exigem que uma chave de API seja passada no cabeçalho `x-api-key`.

```http
x-api-key: SUA_CHAVE_DE_API
```

Obtenha sua chave de API gratuita em [app.cpfhub.io](https://app.cpfhub.io).

## Links Importantes

*   **Documentação:** [https://cpfhub.io/documentacao](https://cpfhub.io/documentacao)
*   **Servidor MCP (Agentes de IA):** [https://github.com/cpfhub/cpfhub-mcp](https://github.com/cpfhub/cpfhub-mcp)
*   **SDKs Oficiais:**
    *   [Node.js](https://github.com/cpfhub/cpfhub-node)
    *   [Python](https://github.com/cpfhub/cpfhub-python)
    *   [PHP](https://github.com/cpfhub/cpfhub-php)
    *   [Go](https://github.com/cpfhub/cpfhub-go)
    *   [Ruby](https://github.com/cpfhub/cpfhub-ruby)
    *   [Java](https://github.com/cpfhub/cpfhub-java)
    *   [.NET](https://github.com/cpfhub/cpfhub-dotnet)

## Acessando a Especificação OpenAPI

O arquivo `openapi.yaml` neste repositório é a versão oficial e mais atualizada da especificação da API do CPFHub.io.

**Link Direto para a Especificação Raw:**

`https://github.com/cpfhub/cpfhub-openapi/blob/main/openapi.yaml`

(Nota: Uma versão hospedada publicamente em `https://api.cpfhub.io/openapi.yaml` será disponibilizada em breve para consumo direto por máquinas.)

## Exemplos

Verifique o diretório `examples/` para exemplos de requisições e respostas:

*   [cpf-request.json](examples/cpf-request.json)
*   [cpf-response.json](examples/cpf-response.json)

---

## License / Licença

MIT © [CPFHub.io](https://cpfhub.io)
