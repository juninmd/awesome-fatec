# AGENTS.md

Repositório de curadoria em Markdown: lista de projetos da Fatec Franca. Não há código, `package.json` nem testes.

## Stack

- Markdown (`README.md`, `CONTRIBUTING.md`, `AGENTS.md`)
- Lint: `markdownlint-cli2` com `.markdownlint.json` (MD013, MD033, MD034 e MD041 desligadas; MD024 só entre irmãos)
- Links: `lychee` (apenas no CI)

## Comandos

```bash
npx markdownlint-cli2 "**/*.md"   # lint, mesmo comando do CI (Node 20)
```

Não existem comandos de build ou teste.

## Gates de CI

- `validate.yml` (Validate): `juninmd/base-actions` `reusable-validate.yml`, em PR e push no `master`.
- `security.yml` (Security Scan): `juninmd/base-actions` `reusable-security-scan.yml`, push no `master`, semanal e manual.
- `ci.yml` (CI/CD Pipeline): markdownlint + lychee (`fail: true`); escuta `main`/`develop`, mas a branch padrão é `master`.

## Convenções

- Cada item é `- <https://github.com/usuario/repositorio>`, HTTPS, sem negrito/itálico, dentro da seção por linguagem/tecnologia (ver `CONTRIBUTING.md`).
- Documentação em pt-BR; commits em inglês com prefixo convencional.

## Não fazer

- Não adicionar link quebrado (o lychee reprova).
- Não colocar segredos, tokens ou dados pessoais em nenhum arquivo.
- Não criar seções fora da estrutura listada em `CONTRIBUTING.md` sem atualizá-lo.
