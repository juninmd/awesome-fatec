# awesome-fatec

[![CI](https://github.com/juninmd/awesome-fatec/actions/workflows/ci.yml/badge.svg)](https://github.com/juninmd/awesome-fatec/actions/workflows/ci.yml)

> Lista de projetos feitos na Fatec Franca

Repositório de curadoria: apenas Markdown, sem código executável. O `README.md` é um índice de links para os repositórios de trabalhos acadêmicos, agrupados por disciplina ou tecnologia.

## Requisitos

- Git
- Node.js 20 ou superior (somente para rodar o lint de Markdown localmente; é a versão usada no CI)

Não há instalação de dependências nem configuração: o projeto não tem `package.json` e não usa variáveis de ambiente.

## Como contribuir

Adicione o link na seção correta, no formato `- <https://github.com/usuario/repositorio>`, e abra um Pull Request. Regras completas em [CONTRIBUTING.md](CONTRIBUTING.md).

## Lint

Mesmo comando do CI (regras em `.markdownlint.json`):

```bash
npx markdownlint-cli2 "**/*.md"
```

## Gates de CI

| Workflow | Arquivo | O que checa |
| --- | --- | --- |
| Validate | `.github/workflows/validate.yml` | Gate de PR/push no `master`, via workflow reutilizável `juninmd/base-actions` (`reusable-validate.yml`) |
| Security Scan | `.github/workflows/security.yml` | Varredura de segurança via `juninmd/base-actions` (`reusable-security-scan.yml`); push no `master`, semanal e manual |
| CI/CD Pipeline | `.github/workflows/ci.yml` | Lint de Markdown (`markdownlint-cli2`) e verificação de links (`lychee`); dispara em push para `main`/`develop` e PR para `main` |

Observação: a branch padrão é `master`, então o `ci.yml` (que escuta `main`/`develop`) não é disparado pelos eventos normais do repositório. O lint local acima é a forma de validar antes do PR.

## Projetos

## C

- <https://github.com/juninmd/fatec-compare-c>
- <https://github.com/juninmd/fatec-c-lista-encadeada>
- <https://github.com/juninmd/fatec-c-lista-duplamente-encadeada>
- <https://github.com/juninmd/fatec-c-lista-circular-encadeada>

## Java

- <https://github.com/juninmd/fatec-java-lista-1>
- <https://github.com/juninmd/fatec-java-lista-2>
- <https://github.com/juninmd/fatec-java-lista-3>
- <https://github.com/juninmd/fatec-java-lista-4>
- <https://github.com/juninmd/fatec-java-lista-5>
- <https://github.com/juninmd/fatec-java-lista-6>
- <https://github.com/juninmd/fatec-java-lista-7>
- <https://github.com/juninmd/fatec-java-lista-8>
- <https://github.com/juninmd/fatec-java-projeto-final>

## A.G.I

- <https://github.com/juninmd/fatec-apresentacao-agi>
- <https://github.com/juninmd/fatec-gerador-arquivo>

## Scripts

- <https://github.com/juninmd/fatec-projeto-scripts-neto>

## Estatística

- <https://github.com/juninmd/fatec-estatistica>

## Programação WEB

- <https://github.com/juninmd/lost-fatec>
- <https://github.com/juninmd/lost-fatec-api>
- <https://github.com/juninmd/inicial-node-fatec>
- <https://github.com/juninmd/fatec-node-lojinha>

## Ionic

- <https://github.com/juninmd/fatec-ionic-lojinha>

## L.E.S

- <https://github.com/juninmd/fatec-trabalholes/tree/master/LES_17_I_N>
- <https://github.com/juninmd/fatec-gerador-tabela-trabalho-les>

## Dados

- <https://github.com/juninmd/fatec-sync-database>

## Utilitários

- <https://github.com/juninmd/wifi-fatec>

## Interfatecs

- <https://github.com/juninmd/treinamento-interfatecs>

## REACT + Node

- <https://github.com/juninmd/fatec-my-mind-api>
- <https://github.com/juninmd/fatec-my-mind-web>

## Angular

- <https://github.com/juninmd/Calculadora>
