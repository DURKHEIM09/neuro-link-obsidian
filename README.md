# Neuro-Link + Obsidian

Um método de documentação e trabalho com IA: arquivos na origem, conhecimento curado e conexões explícitas entre projetos.

Uso o Obsidian como interface para consultar e editar os documentos com que os agentes trabalham. O Neuro-Link organiza o conhecimento curado e sua recuperação. O objetivo é manter contexto útil entre sessões, com fontes localizáveis, decisões registradas e uma estrutura que acompanhe o trabalho.

Este repositório publica **a estrutura e a metodologia**, com uma base fictícia pronta para explorar. O conteúdo interno do meu ambiente permanece fora do pacote.

[Padrão de documentação](docs/Metodologia-Documentacao.md) · [Trabalho com IA](docs/Fluxo-Trabalho-com-IA.md) · [Integração](docs/Neuro-Link-e-Obsidian.md) · [Como adaptar](docs/Como-Adaptar-o-Metodo.md)

## As partes

| Parte | Papel |
| --- | --- |
| Markdown na origem | Fonte oficial dos projetos, sistemas e infraestrutura. |
| Obsidian | Interface humana das notas, links, backlinks e grafo. |
| Neuro-Link | Conhecimento promovido por curadoria, com origem e critérios de recuperação. |
| Índice derivado | Representação regenerável usada para localizar fontes. |
| Agentes de IA | Consultam o contexto permitido, executam a demanda e atualizam a documentação pertinente. |

## Experimentar

```bash
git clone https://github.com/DURKHEIM09/neuro-link-obsidian.git
cd neuro-link-obsidian
```

Abra a pasta `exemplo/` como um cofre no Obsidian e comece por [Início do exemplo](exemplo/Inicio-do-Exemplo.md). Também é possível navegar pelos arquivos aqui no GitHub. Nenhum plugin comunitário é necessário para explorar os documentos e links do exemplo.

```text
docs/       método, fluxo de IA e integração
modelos/    documentos e instruções adaptáveis
exemplo/    projetos, sistemas, infraestrutura e Neuro-Link fictícios
```

Os JSON de índice, manifesto e avaliação são exemplos documentais. O pacote não instala um servidor MCP, um motor de busca ou o plugin específico do meu ambiente.

## Como escolho o que manter

Considero custo, usabilidade, manutenção e uso real. Projetos complexos podem servir ao aprendizado; a documentação deve ajudar a executar e retomar o trabalho. Começo com o necessário e acrescento organização conforme ela resolve uma necessidade concreta.

## Projetos relacionados

- [Hermes e Durkh 509](https://github.com/DURKHEIM09/hermes-durkh-509): experiência com o agente e suas integrações.
- [Factorio — Durkh Coop](https://github.com/DURKHEIM09/factorio-durkh-coop): um exemplo de projeto documentado e desenvolvido com apoio de IA.

O método é a organização adotada no meu ambiente, adaptada para compartilhamento. [Obsidian](https://obsidian.md/) e as ferramentas de terceiros mantêm seus próprios projetos e documentação.
