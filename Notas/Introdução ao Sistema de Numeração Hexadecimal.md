## O que é o sistema hexadecimal?


00:00

- O professor Pedro Souza introduz o tema do vídeo, que é o sistema de numeração hexadecimal.

00:25

- O sistema hexadecimal possui base 16, utilizando 16 símbolos: 0-9 e A-F (onde A representa 10 e F representa 15).

## Relação entre sistemas de numeração

01:08

- É apresentada uma tabela que relaciona números decimais, binários e hexadecimais.

01:36

- Os dígitos hexadecimais são representados por exatamente 4 bits no sistema binário.

02:54

# Contagem no Sistema Hexadecimal

## Princípios da contagem

02:54

- A contagem no sistema hexadecimal segue a mesma lógica dos sistemas decimal e binário.

03:18

- Após o número 9, os dígitos continuam com A, B, C, D, E e F.

## Exemplo de contagem
03:59

- Quando se atinge F (15), adiciona-se uma unidade ao próximo dígito à esquerda.

04:58

- Essa lógica continua até atingir valores como FF (255), onde ambos os dígitos atingem seu valor máximo.

06:21
# Conversão entre Sistemas

## Conversão de hexadecimal para decimal

06:50

- Para converter um número hexadecimal para decimal, aplica-se a regra geral de formação considerando os pesos dos dígitos.


07:18

- Por exemplo, para o número 356 na base hexadecimal: (3 \times 16^2 + 5 \times 16^1 + 6 \times 16^0), resultando em 854 na base decimal.

## Outro exemplo prático

08:25

# Conversão de Sistemas Numéricos: Hexadecimal e Binário

## Multiplicação e Substituição em Hexadecimal

08:25

- A regra geral para formação de números hexadecimais envolve multiplicar cada dígito pelo seu respectivo peso. No entanto, não se pode multiplicar `F` elevado a zero ou `A` elevado a um.

08:55

- O valor hexadecimal `F` é substituído por 15 e o valor `A` por 10, resultando na equação: (2 \times 16^2 + 10 \times 16^1 + 15 \times 16^0).

## Conversão de Hexadecimal para Decimal

09:21

- Após realizar as operações, o número hexadecimal (2AF) é convertido para decimal como sendo igual a 687.
## Conversão de Hexadecimal para Binário

09:49

- Cada dígito hexadecimal é representado por quatro dígitos binários. O processo consiste em substituir cada dígito pelo seu equivalente binário.

10:13

- Por exemplo, ao converter o número hexadecimal `CF8`, os valores são substituídos conforme uma tabela que relaciona os dígitos hexadecimais aos seus equivalentes binários.

## Exemplos Práticos de Conversão

11:10

- Para o número hexadecimal `CF8`, a conversão resulta em um número binário extenso, demonstrando que a representação hexadecimal é mais compacta e menos propensa a erros.

11:38

- A conversão do número `9742` da base 16 para binário segue o mesmo princípio, utilizando uma tabela de equivalência.

## Processo Inverso: Binário para Hexadecimal


13:06

- Para converter do sistema binário para o sistema hexadecimal, agrupa-se os bits em conjuntos de quatro, começando pela direita.

13:33

- Cada grupo de quatro bits é então substituído pelo seu equivalente hexadecimal usando uma tabela específica.
## Exemplificação da Conversão Binária

13:59

- Ao agrupar os bits do número binário e convertê-los usando a tabela correspondente, obtemos os valores hexadecimais equivalentes.


15:29

- Um exemplo prático mostra que agrupamentos podem incluir zeros à esquerda sem alterar o valor numérico final.

## Métodos Adicionais de Conversão


16:36

# Conversão de Decimal para Hexadecimal


## Método das Sucessivas Divisões por 16


16:36

- O método recomendado para conversão de decimal para hexadecimal é o das sucessivas divisões por 16, que é mais fácil de aplicar do que outros métodos.

16:54

- A diferença em relação ao método de divisão por dois é que aqui utilizamos divisões por 16. O critério de parada permanece o mesmo: quando o quociente se torna zero.

17:19

- Durante a conversão, os restos da divisão devem ser substituídos pelos seus equivalentes hexadecimais. Por exemplo, um resto de 10 deve ser substituído pela letra 'A', e assim sucessivamente até o resto 15, que corresponde à letra 'F'.


## Exemplo Prático de Conversão


17:44

- Para converter o número decimal 423 para hexadecimal, inicia-se dividindo 423 por 16. O resultado é um quociente de 26 e um resto de 7.


18:13

- Continuando a divisão, pegamos o quociente (26), dividimos novamente por 16, resultando em um quociente de 1 e um resto de 10. Repetimos esse processo até que o quociente seja zero.

18:40

- Após todas as divisões, lemos os restos na ordem inversa: começando pelo último resto obtido. Assim, a conversão resulta em '1A7' no sistema hexadecimal para o número decimal original (423).