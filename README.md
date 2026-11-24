# API de Chamados de Suporte

**Estudante:** Jefferson Rodrigues de Oliveira

## Objetivo
Criar a estrutura inicial da API de chamados de suporte usando Flask,
com uma rota inicial que confirma que a aplicação está funcionando.

## Instalação das dependências
```
uv sync --locked
```

## Como executar
```
uv run flask --app app run --host=0.0.0.0 --port=5000
```

## Rota inicial
Acesse `GET /` (por exemplo, `http://localhost:5000/`).

Resposta esperada (status 200, `application/json`):
```json
{
  "mensagem": "API de chamados em funcionamento"
}
```