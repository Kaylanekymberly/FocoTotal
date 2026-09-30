# FocoTotal

> Plataforma de foco, autocontrole e proteção digital.

O FocoTotal é uma aplicação web criada para transformar a proposta
inicial do projeto BetNet em uma plataforma mais ampla de
acompanhamento pessoal, foco e proteção digital.

---

## Origem do projeto

O FocoTotal surgiu a partir do BetNet, um projeto inicialmente
desenvolvido como uma extensão de navegador.

O BetNet utilizava JavaScript, Manifest V3, detecção de palavras-chave,
monitoramento de conteúdo dinâmico e mecanismos de bloqueio para
reduzir a exposição a conteúdos relacionados a apostas.

Com a evolução da ideia, o projeto passou de uma extensão focada
principalmente no bloqueio de conteúdo para uma aplicação web com
persistência de dados, autenticação e recursos de acompanhamento
pessoal.

### Evolução

BetNet → Extensão de navegador → FocoTotal → Aplicação Web

---

## Objetivo

O FocoTotal busca reunir recursos relacionados a:

- foco e concentração;
- sessões de foco;
- metas pessoais;
- acompanhamento financeiro;
- proteção contra comportamentos de risco;
- registro pessoal;
- acompanhamento de tentativas de bloqueio.

---

## Arquitetura

```text
Usuário
   │
   ▼
Aplicação Web
   │
   ▼
Autenticação
   │
   ▼
Supabase
   ├── Auth
   ├── PostgreSQL
   └── Row Level Security
