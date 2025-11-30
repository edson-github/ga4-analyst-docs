# GA4 Analyst Docs

Este projeto utiliza [MkDocs](https://www.mkdocs.org/) para gerar documentação estática sobre arquitetura e análise de dados com Google Analytics 4.

## Como rodar localmente

1. Instale o MkDocs:
   ```sh
   pip install mkdocs
   ```
2. Inicie o servidor local:
   ```sh
   mkdocs serve
   ```
   O site estará disponível em `http://127.0.0.1:8000`.

## Como fazer deploy no GitHub Pages

1. Gere o site estático:
   ```sh
   mkdocs build
   ```
2. Faça deploy para o branch `gh-pages`:
   ```sh
   mkdocs gh-deploy
   ```

## Estrutura do projeto
- `docs/`: arquivos fonte da documentação
- `site/`: site gerado automaticamente
- `mkdocs.yml`: configuração do MkDocs

## Links úteis
- [Repositório no GitHub](https://github.com/edson-github/ga4-analyst-docs)
- [Documentação do MkDocs](https://www.mkdocs.org/)
