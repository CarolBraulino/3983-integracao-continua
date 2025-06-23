
# Integração Contínua com GitHub Actions

Repositório criado como parte do curso de Integração Contínua da [Alura](https://www.alura.com.br/), com foco na implementação de pipelines de testes automatizados utilizando **GitHub Actions**.

## Objetivo

Demonstrar na prática como configurar uma pipeline de **Integração Contínua (CI)** utilizando o GitHub Actions para automatizar testes em uma aplicação Go (`Golang`). 

---

## Tecnologias Utilizadas

- **Linguagem:** Go (Golang)
- **Ferramenta de CI:** GitHub Actions
- **Gerenciador de dependências:** `go mod`
- **Docker (opcional)**: Ambiente de execução isolado

---

## Funcionalidades Implementadas

- Pipeline de CI acionada a cada `push` ou `pull request`
- Execução automática de testes unitários com `go test`
- Feedback de sucesso ou falha diretamente nos commits/PRs
- Estrutura básica para testes automatizados com Go

---

## Estrutura do Projeto

```
3983-integracao-continua/
├── .github/
│   └── workflows/
│       └── ci.yml          # Definição do workflow do GitHub Actions
├── main.go                 # Arquivo principal da aplicação
├── main_teste.go           # Testes automatizados (Go)
├── go.mod                  # Módulo do Go
├── go.sum                  # Hashes das dependências
└── README.md               # Documentação do projeto
```

---

## Executando os Testes Localmente

1. Instale o Go: https://go.dev/doc/install
2. Clone este repositório:
   ```bash
   git clone https://github.com/CarolBraulino/3983-integracao-continua.git
   cd 3983-integracao-continua
   ```
3. Execute os testes:
   ```bash
   go test -v ./...
   ```
---

## Curso Alura

Este projeto foi desenvolvido durante o curso:

> **Integração Contínua: automatize testes e entregas com GitHub Actions**  
> Plataforma: [Alura](https://www.alura.com.br/)

---

## Autoria

Desenvolvido por [Carol Braulino](https://github.com/CarolBraulino) como parte dos estudos em DevOps e Qualidade de Software.

---

## Licença

Este projeto é apenas para fins educacionais e segue os termos da licença MIT.
