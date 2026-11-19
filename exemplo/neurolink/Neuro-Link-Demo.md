# Neuro-Link Demo

[Voltar ao exemplo BibliotecaDemo](../Inicio-do-Exemplo.md)

Este exemplo mostra como separar fonte, catálogo derivado, proveniência e avaliação usando conteúdo fictício. A política desta pasta foi escrita para a demonstração; ela não contém notas ou regras privadas de um ambiente real.

## Camadas do exemplo

| Pasta | Papel |
| --- | --- |
| `collections/` | Fonte canônica fictícia que pode ser consultada. |
| `index/` | Catálogo ilustrativo de metadados, termos e seções da fonte. |
| `manifests/` | Registro da origem e SHA-256 dos bytes da fonte usada. |
| `evaluation/` | Perguntas fictícias com fonte, seção e resposta esperadas. |

A fonte é a [Política de curadoria Demo](./collections/Politica-Curadoria-Demo.md). Ela contém duas seções de referência. Uma mudança no conteúdo exige conferir novamente seu hash e atualizar os derivados; editar o catálogo não altera a política.

## Como usar a demonstração

1. Leia a política e suas duas seções.
2. Consulte `index/catalogo-demonstrativo.json` para ver como cada seção pode ganhar URI, termos e caminho de origem.
3. Compare a fonte com `manifests/fontes-demonstrativas.json`: o SHA-256 foi calculado sobre o arquivo fictício incluído aqui.
4. Use as duas perguntas de `evaluation/perguntas-ficticias.json` para conferir a resposta e a seção que uma recuperação deveria citar.

Somente arquivos de `collections/` podem aparecer no catálogo deste exemplo. Perguntas de avaliação e o manifesto não são fontes de resposta.

## Formato e limites

Os JSONs usam formatos próprios desta demonstração, identificados como `biblioteca-demo-v1`. Eles não são um protocolo de importação do Knowledge MCP. A URI `demo://curadoria/politica` é um identificador ilustrativo.

O catálogo não implementa FTS5, embeddings, busca semântica, atualização automática ou um servidor MCP. Ele permite examinar a separação das camadas e conferir citações com dois casos pequenos. Aprovar esses casos não demonstra a qualidade de um sistema de recuperação real.
