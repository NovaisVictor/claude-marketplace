# claude-marketplace

Marketplace de plugins para Claude Code com stacks fullstack: Bun, Elysia, Drizzle, React, TanStack, BetterAuth.

## Adicionar o marketplace

```bash
claude plugin marketplace add NovaisVictor/claude-marketplace
```

## Plugins disponíveis

| Plugin                                                                           | Instalação                                                    | Descrição                                                                   |
| -------------------------------------------------------------------------------- | ------------------------------------------------------------- | --------------------------------------------------------------------------- |
| [claude-backend-plugin](https://github.com/NovaisVictor/claude-backend-plugin)   | `claude plugin install claude-backend-plugin@novais-plugins`  | Backend com Bun + Elysia + Drizzle + Clean Architecture + SOLID             |
| [claude-auth-plugin](https://github.com/NovaisVictor/claude-auth-plugin)         | `claude plugin install claude-auth-plugin@novais-plugins`     | Autenticação com BetterAuth + roles (user/manager/admin)                    |
| [claude-frontend-plugin](https://github.com/NovaisVictor/claude-frontend-plugin) | `claude plugin install claude-frontend-plugin@novais-plugins` | Frontend com React 19 + TanStack Router + TanStack Query + Kubb + shadcn/ui |

## Combinações

| Cenário                         | Plugins                                        |
| ------------------------------- | ---------------------------------------------- |
| API sem auth                    | `claude-backend-plugin`                        |
| API com auth                    | `claude-backend-plugin` + `claude-auth-plugin` |
| Frontend + backend com auth     | todos os 3                                     |
| Frontend consumindo API externa | `claude-frontend-plugin`                       |

## Atualizar plugins

```bash
claude plugin marketplace update novais-plugins
```
