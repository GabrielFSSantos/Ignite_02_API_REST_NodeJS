## Ignite_02_API_REST_NodeJS

# Anotações
Runtime Type Checking => JavaScript
Static TYpe Checking => TypeScript

npx => vem junto ao npm e serve para executar codigos das bibliotecas que baixamos.
exemplos: 'npx tsc --init' (comando do typescript), 'npx knex migrate:make' (comando do knex)

Migrations (knex) => controle de versão, historico de todas as mudanças realizadas na estrutura do banco de dados (semelhante ao git, mas para banco de dados).

Arquivos terminados em d.ts normalmente na pasta @types, são arquivos definição de tipos, são codigos com apenas type script e usado para sobrescrever um tipo de uma biblioteca.

Cookies são formas de manter contexto entre requisições.

# Testes
Unitários: testa uma unidade da sua apliação, ou seja, uma unidade isolada (função)
Integração: testa comunicação entre duas ou mais unidades
E2E - ponta a ponta: testes que simulam um usuário operando na nossa aplicação

Pirãmide de testes: E2E (não dependem de nenhuma tecnologia, não dependem de arquitetura)

## Engenharia de Software

# RF
- [x] O usuário deve porder criar uma nova transação;
- [x] O usiário deve poder obter um resumo da sua conta;
- [x] O usuário deve poder listar todas transações que já ocorreram;
- [x] O usuário deve poder visualizar uma transação única;

# RN
- [x] A transação pode ser do tipo crédito que somara no valor total, ou débito que subtrairá;
- [x] Deve ser possível identificarmos o usuário entre as requisições;
- [x] O usuário só pode visualizar transações o qual ele criou;

# RNF
- [ ] 