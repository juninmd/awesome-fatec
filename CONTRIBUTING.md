# Contributing to awesome-fatec

Obrigado por contribuir com a lista de projetos da Fatec Franca!

## Como Adicionar um Projeto

1. Fork este repositorio
2. Adicione o link do seu projeto na secao correta do `README.md`
3. Siga o formato existente: `- <URL-do-repositorio>`
4. Crie um Pull Request

## Formato do Link

Use o formato de link direto para o repositorio:

```markdown
- <https://github.com/usuario/repositorio>
```

## Qualidade do Conteudo

### CI/CD Pipeline

Este repositorio utiliza GitHub Actions para validar o conteudo automaticamente:

- **Lint Markdown**: Verificacao de formatacao com markdownlint-cli2
- **Verificacao de Links**: Checagem de URLs com lychee

O Pull Request deve passar em todas as verificacoes antes de ser aceito.

### Regras de Formatacao

- Use apenas links HTTPS
- Nao use formatacao Markdown desnecessaria (negrito, italico, etc.)
- Mantenha a consistencia com a formatacao existente
- Cada secao deve conter apenas links para repositorios

### Verificacao de Links

- Todos os links devem ser URLs validas e acessiveis
- Links quebrados serao rejeitados pelo CI
- Use links diretos para o repositorio (nao para branches especificas, exceto quando necessario)

## Estrutura do README

Mantenha a estrutura organizada por linguagem/tecnologia:

1. **C** - Projetos em linguagem C
2. **Java** - Projetos em Java
3. **A.G.I** - Apresentacoes e geradores
4. **Scripts** - Scripts utilitarios
5. **Estatística** - Projetos de estatística
6. **Programação WEB** - Projetos web (Node.js, etc.)
7. **Ionic** - Aplicativos mobile com Ionic
8. **L.E.S** - Engenharia de Software
9. **Dados** - Projetos de dados
10. **Utilitários** - Ferramentas utilitárias
11. **Interfatecs** - Treinamento para Interfatecs
12. **REACT + Node** - Projetos com React e Node.js
13. **Angular** - Projetos com Angular

## Perguntas?

Abra uma issue no repositorio para tirar duvidas.
