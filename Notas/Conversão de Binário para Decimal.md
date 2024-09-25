## Exercício 1: Conversão de Binário para Decimal

**00:00**

- O professor inicia a explicação sobre conversão entre sistemas numéricos, começando pela conversão do número binário `10 101` para o sistema decimal.

**00:25**

- É feita a atribuição dos pesos aos bits. O bit menos significativo (o primeiro à direita) recebe o peso de 202^020, e o mais significativo (à esquerda) recebe o maior peso correspondente à sua posição, 262^626. Neste exemplo, para o número `10 101`, os bits estão nas seguintes posições:
    - 202^020
    - 212^121
    - 222^222
    - 232^323
    - 242^424

**01:04**

- Cada bit do número binário é multiplicado por seu respectivo peso:
    - 1×24=161 \times 2^4 = 161×24=16
    - 0×23=00 \times 2^3 = 00×23=0
    - 1×22=41 \times 2^2 = 41×22=4
    - 0×21=00 \times 2^1 = 00×21=0
    - 1×20=11 \times 2^0 = 11×20=1

**01:47**

- Somando os resultados das multiplicações: 16+0+4+0+1=2116 + 0 + 4 + 0 + 1 = 2116+0+4+0+1=21. Portanto, o número binário `10 101` é equivalente a `21` no sistema decimal.

---