# CPFHub.io OpenAPI Specification

🇺🇸 **English** | [🇧🇷 Português](#portugu%C3%AAs)

This repository contains the official OpenAPI Specification for the CPFHub.io API.

## What is CPFHub.io?

CPFHub.io is a REST API that provides real-time CPF lookup services in Brazil. It returns essential identity information — full name, gender, and date of birth — for any Brazilian CPF number, with high accuracy, low latency, and full LGPD compliance.

**10M+ CPFs queried · 1,300+ active companies · 99.9% uptime**

## Authentication

All API requests require an API key passed in the `x-api-key` header.

```
GET https://api.cpfhub.io/cpf/12345678909
x-api-key: YOUR_API_KEY
```

Get your free API key at [app.cpfhub.io](https://app.cpfhub.io) — no credit card required.

## Quick Example

```bash
curl -X GET "https://api.cpfhub.io/cpf/12345678909" \
  -H "x-api-key: YOUR_API_KEY"
```

**Response:**

```json
{
  "success": true,
  "data": {
    "cpf": "12345678909",
    "name": "Fulano de Tal",
    "nameUpper": "FULANO DE TAL",
    "gender": "M",
    "birthDate": "15/06/1990",
    "day": 15,
    "month": 6,
    "year": 1990
  }
}
```

## OpenAPI Specification

The `openapi.yaml` file in this repository is the official and most up-to-date version of the CPFHub.io API specification.

**Direct link to the raw specification:**

```
https://raw.githubusercontent.com/cpfhub/cpfhub-openapi/main/openapi.yaml
```

> **Note:** A publicly hosted version at `https://api.cpfhub.io/openapi.yaml` will be available soon for direct machine consumption by AI agents.

## Tool Definition

The `tool-definition.json` file contains the canonical AI tool definition for the `get_person_by_cpf` function, ready to be used in MCP servers, LangChain tools, OpenAI function calling, and other agent frameworks.

## Examples

See the `examples/` directory for sample requests and responses:

- [`examples/cpf-request.json`](https://github.com/cpfhub/cpfhub-openapi/blob/main/examples/cpf-request.json) — example HTTP request
- [`examples/cpf-response.json`](https://github.com/cpfhub/cpfhub-openapi/blob/main/examples/cpf-response.json) — example HTTP response

## Important Links

| Resource | URL |
|---|---|
| Documentation | https://cpfhub.io/documentacao |
| Dashboard | https://app.cpfhub.io |
| MCP Server (AI Agents) | https://github.com/cpfhub/cpfhub-mcp |
| Node.js SDK | https://github.com/cpfhub/cpfhub-node |
| Python SDK | https://github.com/cpfhub/cpfhub-python |
| PHP SDK | https://github.com/cpfhub/cpfhub-php |
| Go SDK | https://github.com/cpfhub/cpfhub-go |
| Ruby SDK | https://github.com/cpfhub/cpfhub-ruby |
| Java SDK | https://github.com/cpfhub/cpfhub-java |
| .NET SDK | https://github.com/cpfhub/cpfhub-dotnet |
| Rust SDK | https://github.com/cpfhub/cpfhub-rust |
| Elixir SDK | https://github.com/cpfhub/cpfhub-elixir |
| Dart/Flutter SDK | https://github.com/cpfhub/cpfhub-dart |
| Lua SDK | https://github.com/cpfhub/cpfhub-lua |
| Nim SDK | https://github.com/cpfhub/cpfhub-nim |
| Swift SDK | https://github.com/cpfhub/cpfhub-swift |
| R SDK | https://github.com/cpfhub/cpfhub-r |
| n8n Node | https://github.com/cpfhub/n8n-nodes-cpfhub |

## License

MIT © [CPFHub.io](https://cpfhub.io)

---

# Português

[🇺🇸 English](#cpfhubio-openapi-specification) | 🇧🇷 **Português**

Este repositório contém a Especificação OpenAPI oficial para a API do CPFHub.io.

## O que é o CPFHub.io?

O CPFHub.io é uma API REST que fornece serviços de consulta de CPF em tempo real no Brasil. Retorna informações essenciais de identidade — nome completo, gênero e data de nascimento — para qualquer CPF brasileiro, com alta precisão, baixa latência e total conformidade com a LGPD.

**10M+ CPFs consultados · 1.300+ empresas ativas · 99,9% uptime**

## Autenticação

Todas as requisições à API exigem uma chave de API passada no cabeçalho `x-api-key`.

```
GET https://api.cpfhub.io/cpf/12345678909
x-api-key: SUA_CHAVE_DE_API
```

Obtenha sua chave de API gratuita em [app.cpfhub.io](https://app.cpfhub.io) — sem cartão de crédito.

## Exemplo Rápido

```bash
curl -X GET "https://api.cpfhub.io/cpf/12345678909" \
  -H "x-api-key: SUA_CHAVE_DE_API"
```

**Resposta:**

```json
{
  "success": true,
  "data": {
    "cpf": "12345678909",
    "name": "Fulano de Tal",
    "nameUpper": "FULANO DE TAL",
    "gender": "M",
    "birthDate": "15/06/1990",
    "day": 15,
    "month": 6,
    "year": 1990
  }
}
```

## Especificação OpenAPI

O arquivo `openapi.yaml` neste repositório é a versão oficial e mais atualizada da especificação da API do CPFHub.io.

**Link direto para a especificação raw:**

```
https://raw.githubusercontent.com/cpfhub/cpfhub-openapi/main/openapi.yaml
```

> **Nota:** Uma versão hospedada publicamente em `https://api.cpfhub.io/openapi.yaml` estará disponível em breve para consumo direto por agentes de IA.

## Definição de Tool (Ferramenta de IA)

O arquivo `tool-definition.json` contém a definição canônica de ferramenta de IA para a função `get_person_by_cpf`, pronta para uso em servidores MCP, ferramentas LangChain, function calling do OpenAI e outros frameworks de agentes.

## Exemplos

Veja o diretório `examples/` para exemplos de requisições e respostas:

- [`examples/cpf-request.json`](https://github.com/cpfhub/cpfhub-openapi/blob/main/examples/cpf-request.json) — exemplo de requisição HTTP
- [`examples/cpf-response.json`](https://github.com/cpfhub/cpfhub-openapi/blob/main/examples/cpf-response.json) — exemplo de resposta HTTP

## Links Importantes

| Recurso | URL |
|---|---|
| Documentação | https://cpfhub.io/documentacao |
| Dashboard | https://app.cpfhub.io |
| Servidor MCP (Agentes de IA) | https://github.com/cpfhub/cpfhub-mcp |
| SDK Node.js | https://github.com/cpfhub/cpfhub-node |
| SDK Python | https://github.com/cpfhub/cpfhub-python |
| SDK PHP | https://github.com/cpfhub/cpfhub-php |
| SDK Go | https://github.com/cpfhub/cpfhub-go |
| SDK Ruby | https://github.com/cpfhub/cpfhub-ruby |
| SDK Java | https://github.com/cpfhub/cpfhub-java |
| SDK .NET | https://github.com/cpfhub/cpfhub-dotnet |
| SDK Rust | https://github.com/cpfhub/cpfhub-rust |
| SDK Elixir | https://github.com/cpfhub/cpfhub-elixir |
| SDK Dart/Flutter | https://github.com/cpfhub/cpfhub-dart |
| SDK Lua | https://github.com/cpfhub/cpfhub-lua |
| SDK Nim | https://github.com/cpfhub/cpfhub-nim |
| SDK Swift | https://github.com/cpfhub/cpfhub-swift |
| SDK R | https://github.com/cpfhub/cpfhub-r |
| n8n Node | https://github.com/cpfhub/n8n-nodes-cpfhub |

## Licença

MIT © [CPFHub.io](https://cpfhub.io)
