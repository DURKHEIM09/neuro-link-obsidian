---
title: Arquitetura da Biblioteca Demo
tipo: arquitetura
estado: ficticio-planejado
---

# Arquitetura da Biblioteca Demo

Contexto: [Projeto Biblioteca Demo](Projeto-Biblioteca-Demo.md). A solução abaixo é uma proposta fictícia; não existe aplicação executável neste exemplo.

## Fluxo proposto

1. A pessoa consulta o catálogo de livros.
2. O sistema consulta a disponibilidade de um exemplar.
3. Uma solicitação válida registra o empréstimo.
4. A devolução encerra o empréstimo e atualiza a disponibilidade.

## Regra demonstrativa

O prazo proposto para um empréstimo é de **14 dias**. Essa regra foi inventada para este exemplo e ainda precisaria ser validada com usuários numa implementação real. Ela pode servir de fonte para uma pergunta de avaliação da recuperação de conhecimento.

## Responsabilidades

- A futura aplicação aplicaria as regras de empréstimo e apresentaria o catálogo.
- O [Sistema Armazenamento Demo](../../sistemas/armazenamento-demo/Sistema-Armazenamento-Demo.md) seria a dependência de persistência. Sua nota explica seu papel e cuidados operacionais conceituais; os procedimentos de instalação pertencem àquele sistema quando existirem.
- A [Infraestrutura Ambiente Demo](../../infraestrutura/ambiente-demo/Infraestrutura-Ambiente-Demo.md) definiria onde executar os componentes e como separar áreas de trabalho e dados.

## Decisões abertas

Interface, linguagem, banco e forma de implantação continuam indefinidos. A ligação entre documentos não comprova uma integração. O [estado do projeto](Estado-Biblioteca-Demo.md) mantém a distinção entre proposta e entrega.
