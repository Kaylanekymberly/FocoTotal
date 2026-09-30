# História do Projeto

## 1. Origem - BetNet

O FocoTotal surgiu a partir do BetNet, um projeto inicialmente
desenvolvido como uma extensão de navegador.

O BetNet foi criado como uma primeira abordagem técnica para
reduzir a exposição do usuário a conteúdos relacionados a apostas.

A extensão utilizava JavaScript, Manifest V3, detecção de palavras-chave,
monitoramento de conteúdo dinâmico e mecanismos de bloqueio.

## 2. Primeira arquitetura

O BetNet foi desenvolvido utilizando recursos da arquitetura de
extensões do navegador, incluindo:

- Content Scripts;
- Background Service Workers;
- Declarative Net Request;
- regras de bloqueio;
- monitoramento de DOM;
- detecção de palavras-chave;
- interfaces de bloqueio.

O projeto também utilizava mecanismos como `MutationObserver`,
Event Delegation e técnicas de controle de execução.

## 3. Evolução do conceito

Com o desenvolvimento do projeto, surgiu a necessidade de ampliar
a proposta para além do bloqueio de conteúdo.

A ideia passou a envolver uma aplicação capaz de trabalhar com
autenticação, persistência de dados e acompanhamento de diferentes
informações relacionadas ao usuário.

Dessa evolução nasceu o FocoTotal.

## 4. FocoTotal

O FocoTotal representa uma nova etapa arquitetural do projeto.

Enquanto o BetNet foi desenvolvido como uma extensão de navegador,
o FocoTotal passou a utilizar uma aplicação web conectada a uma
estrutura de backend e banco de dados.

A nova arquitetura permite trabalhar com:

- autenticação;
- persistência de dados;
- sessões de foco;
- metas;
- registros financeiros;
- bloqueios;
- registros pessoais;
- contatos de proteção;
- controle de acesso por usuário.

## 5. Evolução arquitetural

```text
BETNET
Extensão de navegador
        │
        │
        ▼
Detecção e bloqueio
        │
        │
        ▼
FOCOTOTAL
Aplicação Web
        │
        ├── Autenticação
        ├── Banco de Dados
        ├── Segurança
        ├── Foco
        ├── Metas
        ├── Finanças
        └── Proteção
