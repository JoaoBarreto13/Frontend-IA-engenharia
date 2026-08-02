# Engenharia IA Frontend

Projeto final desenvolvido durante o curso de Engenharia de IA, com foco em construção de interfaces web modernas, organizadas e escaláveis.

[![Angular](https://img.shields.io/badge/Angular-19+-DD0031?logo=angular&logoColor=white)](https://angular.dev)
[![TypeScript](https://img.shields.io/badge/TypeScript-5+-3178C6?logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

## Sobre o projeto

Este repositório reúne a aplicação frontend desenvolvida como entrega final do curso. O objetivo é demonstrar boas práticas de desenvolvimento com **Angular** e **TypeScript**, incluindo organização de componentes, tipagem estática e versionamento com **Git**.

## Tecnologias

| Tecnologia   | Uso                          |
| ------------ | ---------------------------- |
| Angular      | Framework frontend           |
| TypeScript   | Linguagem principal          |
| CSS          | Estilização                  |
| Git          | Controle de versão           |

## Pré-requisitos

Antes de executar o projeto localmente, certifique-se de ter instalado:

- [Node.js](https://nodejs.org/) (LTS recomendado)
- [npm](https://www.npmjs.com/) ou [pnpm](https://pnpm.io/)
- [Angular CLI](https://angular.dev/tools/cli) (`npm install -g @angular/cli`)

## Instalação

Clone o repositório e instale as dependências:

```bash
git clone https://github.com/<seu-usuario>/engenharia-ia-frontend.git
cd engenharia-ia-frontend
npm install
```

## Desenvolvimento

Inicie o servidor de desenvolvimento:

```bash
ng serve
```

A aplicação ficará disponível em `http://localhost:4200/`. O projeto recarrega automaticamente ao alterar os arquivos fonte.

### Outros comandos úteis

```bash
# Build de produção
ng build

# Executar testes unitários
ng test

# Executar testes end-to-end
ng e2e
```

## Estrutura do projeto

```
src/
├── app/              # Componentes, serviços e módulos
├── assets/           # Imagens, fontes e arquivos estáticos
├── environments/     # Configurações por ambiente
└── styles.css        # Estilos globais
```

> A estrutura pode evoluir conforme novos módulos forem adicionados ao projeto.

## Convenções

Este projeto segue as regras definidas em [`claude.md`](claude.md):

- Nomes de variáveis em **inglês**
- Princípios de **Clean Code**
- Componentes **pequenos** e com responsabilidade única
- Commits no padrão **Conventional Commits**

Exemplos de mensagens de commit:

```
feat: adiciona formulário de cadastro
fix: corrige validação do campo e-mail
docs: atualiza instruções de instalação
refactor: extrai lógica de autenticação para serviço
```

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

## Autor

Desenvolvido como projeto final do curso de Engenharia de IA.
