[[ Introdução ao Sistema de Numeração Hexadecimal]]
[[Conversão de Sistemas Numéricos]]
[[Introdução aos Códigos Binários]]
[[Introdução às Operações Aritméticas em Binário]]
[[Como Representar Números Negativos no Sistema Binário?]]
[[Aritmética de Números BCD]]
[[Ferramentas de Descrição de Circuitos Digitais]]
[[Funções e Portas Lógicas]]
## Sistemas de Numeração
# [00:00](https://youtu.be/RuXmtYdmQKY?t=0) Introdução aos Sistemas de Numeração

**Visão Geral da Seção:** Nesta seção introdutória, o palestrante aborda os conceitos fundamentais relacionados aos sistemas de numeração utilizados na eletrônica digital.

## Definição de Números e Representação

- [00:26](https://youtu.be/RuXmtYdmQKY?t=26) Um número é uma forma de representação de quantidades, desde a antiguidade com pastores contando ovelhas até os sistemas mais avançados atualmente.
- [00:54](https://youtu.be/RuXmtYdmQKY?t=54) O sistema de numeração é um conjunto de símbolos que permite representar números, sendo a base do sistema um dos principais parâmetros a serem estudados.

## Sistemas de Numeração e Regra Geral

- [01:18](https://youtu.be/RuXmtYdmQKY?t=78) A base do sistema indica quantos dígitos o sistema terá e qual será o peso exponencial de cada dígito na composição do número.
- [01:55](https://youtu.be/RuXmtYdmQKY?t=115) Existem três sistemas importantes na eletrônica digital: decimal, binário e hexadecimal, todos seguindo uma regra geral matemática para formação dos números.

# [02:25](https://youtu.be/RuXmtYdmQKY?t=145) Regra Geral de Formação e Sistema Decimal

**Visão Geral da Seção:** Aqui são explorados exemplos práticos da aplicação da regra geral de formação em um sistema decimal.

## Aplicação da Regra Geral no Sistema Decimal

- [03:19](https://youtu.be/RuXmtYdmQKY?t=199) Cada dígito em um número é multiplicado pela base do sistema elevado à sua posição relativa para obter seu equivalente decimal.
- [04:39](https://youtu.be/RuXmtYdmQKY?t=279) No sistema decimal (base 10), há 10 dígitos para compor números, onde cada dígito tem um peso ponderado conforme sua posição relativa no número.

## Exemplo Prático: Aplicando a Regra Geral

- [05:07](https://youtu.be/RuXmtYdmQKY?t=307) Ao analisar o número 47.1932, podemos observar como cada dígito é ponderado com base na posição relativa e na potência correspondente à base 10.
- [06:32](https://youtu.be/RuXmtYdmQKY?t=392) A soma das multiplicações resulta no equivalente decimal do número original, demonstrando a aplicabilidade da regra geral na conversão entre bases numéricas.

# [07:00](https://youtu.be/RuXmtYdmQKY?t=420) Aspectos Importantes nos Sistemas de Numeração

**Visão Geral da Seção:** Esta parte destaca aspectos cruciais nos sistemas de numeração além da aplicação prática das regras gerais.

## Mudança entre Bases Numéricas

- [07:31](https://youtu.be/RuXmtYdmQKY?t=451) A mudança entre diferentes sistemas de numeração envolve principalmente a alteração da base utilizada mantendo-se a mesma regra geral para formar os números.

## Contagem nos Sistemas Numéricos

# [07:55](https://youtu.be/RuXmtYdmQKY?t=475) Contagem Decimal e Binária

**Visão Geral da Seção:** Nesta seção, são abordados conceitos de contagem decimal e binária, destacando a transição entre unidades, dezenas e centenas nos sistemas numéricos.

## Sistema Decimal

- [07:55](https://youtu.be/RuXmtYdmQKY?t=475) Introdução à contagem decimal, onde após o 9, adiciona-se uma unidade às dezenas.
- [08:24](https://youtu.be/RuXmtYdmQKY?t=504) Explicação da transição para as dezenas ao atingir o número 19 e subsequente avanço para os 20.
- [09:03](https://youtu.be/RuXmtYdmQKY?t=543) Destaque sobre a adição das centenas ao atingir o número 99 no sistema decimal.

## Regras Gerais

- [09:29](https://youtu.be/RuXmtYdmQKY?t=569) Observação de que a adição de uma unidade determina a posição máxima permitida no sistema decimal.
- [10:00](https://youtu.be/RuXmtYdmQKY?t=600) Aplicação das regras gerais na contagem: unidades variam em cada fase; dezenas mudam a cada dez contagens; centenas variam a cada cem contagens.

# [10:27](https://youtu.be/RuXmtYdmQKY?t=627) Sistema Binário e Ponderação dos Dígitos

**Visão Geral da Seção:** Aqui são explorados os princípios do sistema binário, incluindo a representação dos números com base dois e a ponderação dos dígitos conforme sua posição.

## Sistema Binário

- [10:27](https://youtu.be/RuXmtYdmQKY?t=627) Introdução ao sistema binário como base dois com dígitos 0 e 1 para representar informações.
- [10:52](https://youtu.be/RuXmtYdmQKY?t=652) Explicação da ponderação dos dígitos no sistema binário através do expoente da base dois.
- [11:33](https://youtu.be/RuXmtYdmQKY?t=693) Associação dos pesos aos dígitos resultando na representação do número binário.

## Exemplo Prático

- [12:03](https://youtu.be/RuXmtYdmQKY?t=723) Demonstração da conversão do número binário "110" para decimal aplicando os pesos correspondentes.
- [12:31](https://youtu.be/RuXmtYdmQKY?t=751) Conclusão: A regra geral permite converter qualquer número em diferentes bases, indicando-as por subscrito.

# [13:04](https://youtu.be/RuXmtYdmQKY?t=784) Características do Sistema Binário

**Visão Geral da Seção:** Detalhes sobre o sistema binário, incluindo nomenclaturas específicas para os dígitos e conceitos fundamentais como MSB (Bit Mais Significativo).

## Nomenclaturas

- [13:04](https://youtu.be/RuXmtYdmQKY?t=784) Definição dos termos: bit (dígito binário), byte (conjunto de oito bits).
- [13:39](https://youtu.be/RuXmtYdmQKY?t=819) Explicação sobre MSB (Bit Mais Significativo) e LSB (Bit Menos Significativo).

## Peso dos Dígitos

- [14:16](https://youtu.be/RuXmtYdmQKY?t=856) Associação dos pesos aos bits no exemplo "1101", destacando o LSB e MSB conforme suas posições relativas.

# [14:44](https://youtu.be/RuXmtYdmQKY?t=884) Aplicabilidade do Sistema Binário

**Visão Geral da Seção:** Abordagem sobre a utilização prática do sistema binário em circuitos digitais e sua simplicidade em relação ao sistema decimal.

## Utilização Prática

- [14:44](https://youtu.be/RuXmtYdmQKY?t=884) Comparativo entre sistemas numéricos: dificuldade de implementar o decimal versus simplicidade do binário em circuitos digitais.

# Conversão de Números Binários para Decimal

**Visão Geral da Seção:** Nesta seção, são abordados os conceitos de conversão de números binários para decimal, destacando a associação de bits com seus pesos correspondentes na base dois e a aplicação prática desse conhecimento.

## Associação de Bits com Pesos Correspondentes

- [16:51](https://youtu.be/RuXmtYdmQKY?t=1011) A conversão de binário para decimal envolve associar cada bit com seu peso correspondente na base dois.
- [17:44](https://youtu.be/RuXmtYdmQKY?t=1064) Cada bit em um número binário é multiplicado pelo seu peso (2 elevado à posição do bit) e somado para obter o valor decimal.

## Exemplo Prático: Conversão Binário para Decimal

- [18:41](https://youtu.be/RuXmtYdmQKY?t=1121) Após associar os bits com seus pesos, realiza-se a multiplicação e soma dos produtos para converter o número binário em decimal.
- [19:13](https://youtu.be/RuXmtYdmQKY?t=1153) A aplicação da regra geral simplifica a conversão, tornando-a um processo matemático direto e eficaz.

# Conversão de Números Decimais para Binários

**Visão Geral da Seção:** Aqui são exploradas as formas de converter números decimais em binários, apresentando métodos como soma ponderada de pesos e divisão sucessiva por dois.

## Soma Ponderada de Pesos na Base Dois

- [19:46](https://youtu.be/RuXmtYdmQKY?t=1186) O método da soma ponderada consiste em escrever o número decimal como uma soma dos pesos na base dois.
- [20:36](https://youtu.be/RuXmtYdmQKY?t=1236) Na divisão sucessiva por dois, divide-se o número decimal até que o quociente seja zero, obtendo assim os restos que formam o número binário equivalente.

## Exemplo Prático: Conversão Decimal para Binário

- [21:03](https://youtu.be/RuXmtYdmQKY?t=1263) Ao converter 76 em decimal para binário, aplica-se a soma ponderada dos pesos na base dois conforme a tabela exponencial do dois.

# Conversão de Decimal para Binário

**Visão Geral da Seção:** Nesta seção, é abordado o processo de conversão de números decimais para binários, destacando a importância desse método e sua aplicação prática.

## Processo de Conversão

- [24:20](https://youtu.be/RuXmtYdmQKY?t=1460) Ao converter um número decimal para binário, utiliza-se o método das formas moderadas, que consiste em dividir o número decimal por dois repetidamente.
- [25:10](https://youtu.be/RuXmtYdmQKY?t=1510) O processo simétrico envolve dividir o número por dois até que o quociente seja zero, obtendo assim a representação binária do número.

## Importância da Ordem na Conversão

- [26:35](https://youtu.be/RuXmtYdmQKY?t=1595) Na conversão, os restos das divisões são lidos do último para o primeiro, onde o último resto representa o bit mais significativo e o primeiro resto corresponde ao bit menos significativo.

## Padrões na Contagem Binária

- [29:21](https://youtu.be/RuXmtYdmQKY?t=1761) Cada bit em um número binário varia conforme a contagem: b0 muda a cada contagem; b1 a cada duas contagens; b2 a cada quatro contagens; e assim sucessivamente.
- [29:59](https://youtu.be/RuXmtYdmQKY?t=1799) A variação dos bits segue uma progressão exponencial: b0 varia a cada 2^0 contagens; b1 a cada 2^1 contagens; b2 a cada 2^2 contagens; e assim por diante.

# Compreensão dos Pesos nos Números Binários

**Visão Geral da Seção:** Esta parte explora como os pesos dos bits influenciam na composição dos números binários e como isso impacta as representações numéricas.

## Relação entre Bits e Pesos

- [30:24](https://youtu.be/RuXmtYdmQKY?t=1824) Cada bit em um número binário tem um peso específico: b0 equivale a 2^0; b1 equivale a 2^1; b2 equivale a 2^2; e assim sucessivamente.

# [32:08](https://youtu.be/RuXmtYdmQKY?t=1928) Aula de Sistemas de Numeração - [32:08](https://youtu.be/RuXmtYdmQKY?t=1928) Conceitos Básicos

**Visão Geral da Seção:** Nesta seção, são abordados os conceitos fundamentais sobre sistemas de numeração decimal e binário, incluindo a formação geral, a diferença entre bits significativos e menos significativos, e como realizar contagens nos sistemas binários.

## Conceitos Fundamentais

- [32:08](https://youtu.be/RuXmtYdmQKY?t=1928) Exploração dos conceitos básicos sobre sistemas de numeração decimal e binário.
- [32:08](https://youtu.be/RuXmtYdmQKY?t=1928) Compreensão da regra geral de formação dos sistemas de numeração.
- [32:08](https://youtu.be/RuXmtYdmQKY?t=1928) Diferenciação entre o bit mais significativo e o menos significativo.
- [32:08](https://youtu.be/RuXmtYdmQKY?t=1928) Métodos para realizar contagens no sistema de numeração binário.