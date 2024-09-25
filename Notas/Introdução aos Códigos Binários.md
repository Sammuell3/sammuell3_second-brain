Highlight

00:00

# Introdução aos Códigos Binários

Copy

Highlight

## Definição de Código

Copy

Highlight

00:00

- O professor Pedro Sousa introduz o conceito de código como uma representação de números, letras e palavras através de símbolos. Um exemplo clássico é o código Morse.

Copy

Highlight

## Manipulação de Dados em Sistemas Digitais

Copy

Highlight

00:26

- Os sistemas digitais não se limitam a informações numéricas; eles podem manipular qualquer tipo de informação. Contudo, a maioria opera com dados binários, exigindo representações em sequências de bits.

Copy

Highlight

00:49

# Exemplo Prático: Controle de Temperatura do Motor

Copy

Highlight

## Situações do Motor

Copy

Highlight

00:49

- O motor pode estar em três estados: frio (abaixo de 80°C), normal (entre 80°C e 100°C) ou quente (acima de 100°C). A partir dessas informações, um sistema digital pode ser projetado para segurança.

Copy

Highlight

## Representação Binária das Temperaturas

Copy

Highlight

01:41

- Cada estado do motor é representado por uma sequência binária:

Copy

Highlight

- Frio: `00`

Copy

Highlight

- Normal: `01`

Copy

Highlight

- Quente: `10`

Copy

Highlight

02:07

# Códigos Binários e Mapeamento

Copy

Highlight

## Processamento da Informação

Copy

Highlight

02:07

- O sistema digital processa informações já convertidas para binário. Cada elemento discreto é mapeado por uma sequência específica de bits.

Copy

Highlight

## Exemplificação com Temperaturas

Copy

Highlight

02:35

- As temperaturas são mapeadas como:

Copy

Highlight

- Quente: `10`

Copy

Highlight

- Normal: `01`

Copy

Highlight

- Frio: `00`

Copy

Highlight

03:27

# Código de Largura Mínima

Copy

Highlight

## Conceito e Aplicação

Copy

Highlight

03:27

- A atribuição da sequência binária a cada elemento é chamada "código". Existem várias formas para realizar essa qualificação, sendo a mais simples usar a quantidade mínima necessária de bits.

Copy

Highlight

## Cálculo da Quantidade Necessária

Copy

Highlight

03:55

- Para determinar quantos bits são necessários para representar n elementos discretos, utiliza-se a fórmula:

Copy

Highlight

[ L = \lceil \log_2(n) \rceil ]

Copy

Highlight

04:50

# Exemplo Prático com Elementos Discretos

Copy

Highlight

## Codificação dos Elementos

Copy

Highlight

04:50

- No exemplo dado, há seis conceitos (A, B, C, D, E, F). Para codificá-los usando código largura mínima:

Copy

Highlight

[ L = \lceil \log_2(6) \rceil = 3 ]

Copy

Highlight

## Verificação da Necessidade dos Bits

Copy

Highlight

05:16

- Com três bits disponíveis (`2^3 = 8`), é possível codificar os seis elementos. Se fossem usados apenas dois bits (`2^2 = 4`), não seria suficiente.

Copy

Highlight

06:17

# Conclusão sobre Códigos Binários

Copy

Highlight

## Importância da Codificação Adequada

Copy

Highlight

07:10

# Qualificação e Códigos na Eletrônica Digital

Copy

Highlight

## Introdução à Qualificação

Copy

Highlight

07:10

- A qualificação de dados requer três bits, mas é possível utilizar mais bits para essa tarefa. Um exemplo de codificação é o conceito b-001.

Copy

Highlight

07:38

- Na prática, não há restrições para usar mais bits do que o mínimo necessário; por exemplo, a temperatura do motor pode ser qualificada com dois ou três bits.

Copy

Highlight

## Códigos Digitais

Copy

Highlight

08:02

- Existem diversos códigos padronizados na eletrônica digital, como BCD, Grey, Reflexivo, Excess-3 e ASCII.

Copy

Highlight

### Código BCD

Copy

Highlight

08:28

- O código BCD (Binary-Coded Decimal) representa cada dígito decimal com seu equivalente binário. Para 10 dígitos decimais são necessários 4 bits.

Copy

Highlight

08:54

- Com 4 bits, é possível representar até 16 sequências diferentes; no entanto, apenas 10 são utilizadas no código BCD.

Copy

Highlight

## Conversão entre Sistemas

Copy

Highlight

09:30

- A conversão de um número decimal para BCD envolve converter cada dígito separadamente. Por exemplo, ao converter o número 35:

Copy

Highlight

- O dígito '3' se torna '0011'.

Copy

Highlight

- O dígito '5' se torna '0101'.

Copy

Highlight

### Exemplo Prático

Copy

Highlight

10:49

- Ao converter o número 35 em BCD resulta em: `0011 0101`. Essa conversão não deve ser confundida com a conversão direta do número inteiro para binário.

Copy

Highlight

## Conversão Inversa: De BCD para Decimal

Copy

Highlight

11:23

- Para converter de BCD para decimal, os grupos de quatro bits devem ser analisados da direita para a esquerda.

Copy

Highlight

- Exemplo: `1000` equivale a 8; `0110` equivale a 6; `0001` equivale a 1.

Copy

Highlight

## Código Grey

Copy

Highlight

12:22

- O código Grey é um tipo de código não posicional que não permite operações aritméticas. Sua principal característica é que apenas um bit muda entre palavras consecutivas.

Copy

Highlight

### Propriedades do Código Grey

Copy

Highlight

12:48

- Em uma sequência binária normal (ex.: `00`, `01`, `10`), podem ocorrer mudanças em múltiplos bits. No código Grey isso não acontece; sempre ocorre uma mudança única.

Copy

Highlight

### Construção do Código Grey

Copy

Highlight

13:48

- Para construir o código Grey:

Copy

Highlight

- Copia-se o primeiro bit e reflete-se os demais. Por exemplo: começando com `00`, obtemos `01`.

Copy

Highlight

15:42

# Códigos Binários e suas Aplicações

Copy

Highlight

## Introdução aos Códigos Binários

Copy

Highlight

15:42

- O apresentador discute a construção de códigos binários, começando com um exemplo de código de 2 bits, onde se adiciona um bit à frente e lê os outros bits na ordem inversa.

Copy

Highlight

## Código Grey

Copy

Highlight

16:16

- O código Grey é mencionado como uma aplicação importante em sistemas de instrumentação e aquisição de dados, especialmente para medição de deslocamento angular em motores.

Copy

Highlight

## Códigos One-Hot e Johnson

Copy

Highlight

16:48

- O código One-Hot é descrito como um código não aritmético, onde apenas um dos bits é igual a 1. Este tipo de código não permite operações aritméticas.

Copy

Highlight

17:40

- O código Johnson é introduzido com uma tabela que converte 10 elementos de informação em um formato específico. A contagem segue uma lógica onde se empurra os bits para a esquerda ao adicionar novos valores.

Copy

Highlight

## Código Excesso-3

Copy

Highlight

19:24

- O funcionamento do código Excesso-3 é explicado: soma-se três ao número decimal desejado antes da conversão para binário. Exemplos são dados para converter números como zero e quatro.

Copy

Highlight

## Código ASCII

Copy

Highlight

20:26

- O código ASCII (American Standard Code for Information Interchange) é apresentado como um sistema que mapeia números e letras, sendo fundamental na representação digital.

Copy

Highlight

21:03

- A versão original do ASCII utiliza 7 bits para representar até 128 caracteres, incluindo caracteres de controle.

Copy

Highlight

22:27

- É discutido o ASCII estendido, que usa 8 bits permitindo a inclusão de caracteres estrangeiros e símbolos adicionais, aumentando o total para 256 caracteres.
