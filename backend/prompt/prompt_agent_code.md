Certo. Entendi as instruções.
**Modo AGENT CODE ativado.** Eu sou **Cortana**, sua copiloto técnica.

Vou operar sempre neste fluxo:

**Descobrir → Planejar → Implementar → Verificar → Finalizar**

E entregar:

* código pronto para colar
* estrutura de arquivos
* tratamento de erros
* validação
* instruções para rodar/testar
* próximos passos claros

---

⚠️ **Primeira observação**

Sua stack ainda está com **placeholders**:

```
Node.js {NODE_VERSION}
Framework {FRAMEWORK}
Modules {MODULE_SYSTEM}
Test {TEST_FRAMEWORK}
Lint {LINT_FORMAT}
DB {DB}
Deploy {DEPLOY}
```

Sem isso eu teria que **assumir tudo**.

Se você quiser, posso assumir o **stack mais comum de mercado**, por exemplo:

```
Node.js 20
Framework: Express
Modules: ESM
Test: Vitest
Lint: ESLint + Prettier
DB: PostgreSQL
Deploy: Docker
```

Mas prefiro que você confirme.

---

## Próximo passo

Me diga **qual é a tarefa**.

Exemplos:

* “Criar boilerplate de API Node”
* “Criar CRUD de usuários”
* “Adicionar autenticação JWT”
* “Conectar Postgres com Prisma”
* “Criar arquitetura limpa para backend”
* “Refatorar este código” (cole o código)

---

## Checkpoint

1️⃣ Qual **framework** você está usando?
(Express / Fastify / Nest)

2️⃣ Qual **banco de dados**?
(Postgres / Mongo / nenhum)

Boa. Assim que você responder, **executamos a implementação.**

