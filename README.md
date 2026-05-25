# Projeto CTT AP2 — Documentação Go com Zensical

## Integrantes

- ADS 3A NOITE
- Gabrielly Campos Bugança - 2500214
- Giovanna Rodrigues Pereira - 2500628
- Luanne Teles de Oliveira - 2301320

---

## Objetivo do Projeto

Este projeto tem como objetivo criar uma documentação técnica sobre a linguagem Go utilizando o gerador de sites Zensical.

A documentação aborda os principais conceitos da linguagem, incluindo:
- Sintaxe básica
- Estruturas de controle
- Arrays, Slices e Maps
- Structs
- Tratamento de erros
- Concorrência
- Go Modules
- Testes automatizados

---

## Fluxo de Trabalho

O grupo utilizou o fluxo baseado em Git Flow e Pull Requests.

### Processo utilizado

1. Atualizar a branch main
2. Criar branch individual
3. Desenvolver documentação
4. Realizar commit
5. Enviar branch para GitHub
6. Abrir Pull Request
7. Outra integrante revisar
8. Aprovar PR
9. Realizar merge na main

---

## Branches Utilizadas

| Integrante | Branch |
|---|---|
| Giovanna | feat/docs-basico |
| Gabrielly | feat/docs-intermediario |
| Luanne | feat/concorrencia-modulos |

---

## Pull Requests

Todos os conteúdos foram enviados através de Pull Requests com revisão obrigatória entre as integrantes.

As revisões foram realizadas utilizando:
- Approve Review
- Merge Pull Request

---

## GitHub Actions

O projeto utiliza GitHub Actions para:
- Build automático do site
- Deploy automático
- Integração contínua (CI/CD)

Workflow criado em:

```text
.github/workflows/ci.yml
```

---

## GitHub Pages

A documentação foi publicada utilizando GitHub Pages integrado ao GitHub Actions.

Link do site:

https://impacta-gb.github.io/projeto-ctt-ap2-ubgq/

---

## Tecnologias Utilizadas

- Go
- Zensical
- GitHub Actions
- GitHub Pages
- Markdown
- Git

---

## Estrutura do Projeto

```text
docs/
.github/workflows/
README.md
zensical.toml
```