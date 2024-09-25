Um exemplo de uma metadiretiva pode ser:
`#pragma omp metadirective when (context1: variant1) \`
                            `when (context2: variant2) \`
                            `default(variant3)`

Neste exemplo, `variant1` será usada se `context1` estiver ativo, `variant2` se `context2` estiver ativo, e `variant3` será a padrão se nenhum dos contextos for atendido

#ciência-da-computacao 