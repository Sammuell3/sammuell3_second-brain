## Exercício 2: Conversão de Decimal para Binário

**03:19**

- O professor apresenta o segundo exemplo, que consiste em converter o número decimal `167` para binário. O processo envolve a soma ponderada de potências de dois, decompondo o número em partes.
    
- Primeiro, identificamos a maior potência de dois que não excede `167`. No caso, é 27=1282^7 = 12827=128. A diferença entre `167` e `128` é calculada:
    
    167−128=39167 - 128 = 39167−128=39

**04:27**

- Em seguida, repetimos o processo para decompor o número restante (`39`). A maior potência de dois que não excede `39` é 25=322^5 = 3225=32. Subtraímos `32` de `39`:
    
    39−32=739 - 32 = 739−32=7
- Agora, para decompor o `7`, a maior potência de dois é 22=42^2 = 422=4. Subtraímos `4` de `7`:
    
    7−4=37 - 4 = 37−4=3
- A próxima potência de dois que se encaixa no `3` é 21=22^1 = 221=2, resultando em:
    
    3−2=13 - 2 = 13−2=1
- Finalmente, a última potência que se encaixa no `1` é 20=12^0 = 120=1, concluindo o processo.
    

**05:46**

- Com a soma das potências identificadas (272^727, 252^525, 222^222, 212^121, e 202^020), podemos montar o número binário correspondente. Marcamos `1` nas posições desses expoentes e `0` nas demais, resultando em:
    
    101001111010011110100111
- Portanto, o número decimal `167` é equivalente a `10100111` em binário.