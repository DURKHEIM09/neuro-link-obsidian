# Padrão de documentação

[Voltar à apresentação](../README.md) · [Ver a base fictícia](../exemplo/Inicio-do-Exemplo.md)

## Uma fonte por informação

Documente o trabalho onde ele é mantido. Pessoas e agentes consultam e atualizam os mesmos arquivos. O Obsidian apresenta esses documentos; portais e índices ajudam a encontrá-los.

Cada nota deve ter um papel. Uma decisão pode ter registro próprio porque acrescenta contexto distinto; repetir o mesmo manual em vários lugares aumenta o custo de mantê-lo correto.

## Três áreas de responsabilidade

| Área | O que documenta |
| --- | --- |
| Projetos | Objetivo, escopo, implementação, decisões, entregas e continuidade. |
| Sistemas | Funcionamento, instalação, configuração e operação de um software. |
| Infraestrutura | Ambiente, rede, acessos e recursos que sustentam os sistemas. |

Um projeto explica como usa um sistema e aponta para a nota desse sistema. A instalação do sistema permanece em sua própria fonte. A [Biblioteca Demo](../exemplo/projetos/biblioteca-demo/Projeto-Biblioteca-Demo.md) mostra essa divisão com dados fictícios.

## Navegação e relações

Cada área possui uma nota-mãe. Ela liga os portais das unidades. Um portal explica a finalidade do projeto/sistema e oferece entradas para as notas por assunto. A nota comum possui um vínculo contextual de retorno.

Um link de navegação significa pertencimento ou localização. Um link técnico deve explicar o motivo: usa, integra, depende, complementa ou registra uma referência. Identifique a fonte dessa relação.

Distinga **uso documentado, integração parcial, planejado, histórico e referência**. Uma tecnologia mencionada no texto não demonstra uma dependência. Um estado registrado em determinada data não comprova disponibilidade atual.

## Nomes e links

Use nomes que continuem claros fora da pasta, como `Arquitetura-Biblioteca-Demo.md` ou `Decisao-Armazenamento-Biblioteca-Demo.md`. Preserve nomes exigidos por ferramentas, como `AGENTS.md`, `SKILL.md`, `README.md` de repositório e licenças.

Prefira links Markdown com caminhos relativos explícitos. Ao renomear uma nota, confira seus consumidores e os links de entrada. O aplicativo pode atualizar referências; uma renomeação direta pelo sistema de arquivos exige conferência própria. Veja a [documentação de links do Obsidian](https://obsidian.md/help/links).

## Conteúdo e evidência

Registre o objetivo, o estado, a data relevante, o que foi feito, como foi verificado, os limites e o próximo passo. Separe observação, explicação do responsável, inferência e intenção futura. Preserve evidências históricas com sua data.

Use os [modelos de projeto](../modelos/Documento-de-Projeto.md) e [decisão](../modelos/Registro-de-Decisao.md) como apoio. A quantidade de notas deve acompanhar o tamanho do trabalho.

## Ler o grafo

O grafo mostra links escritos entre notas. Ele ajuda a navegar, mas não verifica arquitetura, funcionamento ou entendimento. Registre o significado das relações no texto. Pastas e o explorador de arquivos continuam sendo caminhos de acesso úteis.

## Conhecimento curado

Um artefato de trabalho pode ser proposto para conhecimento durável. Revise fonte, responsabilidade, validade, duplicidade e sensibilidade antes de promovê-lo. A promoção pode produzir uma nova síntese com responsabilidade distinta ou consolidar uma nota existente; mantenha a origem explícita.

Índices são derivados. Corrija o conteúdo na fonte oficial e gere novamente a representação de busca. Backups, arquivos temporários, índices e material em quarentena não entram automaticamente no corpus consultado.
