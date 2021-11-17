### Incipit (031)
Incipits ajudam a identificar obras e facilitam a comparação de fontes. A melhor prática para música instrumental é incluir incipits de uma parte aguda e de uma parte grave, como vl 1 e baixo. Para música vocal, inclua incipits da parte vocal mais aguda e do primeiro violino ou da parte instrumental mais aguda. Escreva os instrumentos transpositores na altura real.  

Se a notação necessária não estiver disponível através do _Plaine & Easie code_ (ver abaixo), transcreva a música da melhor forma possível e inclua uma nota explicativa. Pode-se anexar uma imagem do incipit a partir da fonte para maior clareza.

#### Número de obra, número de movimento, número de incipit (031 $a, b, c)

**Campo obrigatório se qualquer campo nesta seção for utilizado.**

O número de incipit consiste de três dígitos, os quais representam obra, movimento e incipit. O primeiro dígito é sempre um 1. Movimentos se referem a seções significativas de uma obra, sejam elas tecnicamente movimentos (como em uma sinfonia) ou diferentes seções (como em uma ária). Para indicar que dois ou mais incipits soam simultaneamente (por exemplo, um vl 1 e um baixo), o primeiro e o segundo números de incipit devem ser iguais.

Numere os incipits consecutivamente, mesmo se movimentos estiverem faltando na fonte. Por exemplo, se a fonte é uma sinfonia de três movimentos, mas o movimento intermediário está faltando, os incipits deverão ser numerados 1.1.1 e 1.2.1 (e não 1.3.1). (Nota: Os pontos entre os números são automaticamente adicionados pelo Muscat.)

_Exemplos:_  
1.1.1 = 1ª obra, 1º movimento, 1º incipit  
1.1.2 = 1ª obra, 1º movimento, 2º incipit (soa ao mesmo tempo que 1.1.1)  
1.1.2 = 1ª obra, 1º movimento, entrada da parte vocal  
1.2.1 = 1ª obra, 2º movimento, 1º incipit

 
#### **Título do movimento, tempo (031 $d)**

Insira o título do movimento e o tempo ou indicações similares, se especificadas, tal como aparecem na fonte. Use | (a barra vertical) com um espaço simples antes e depois para indicar quebras de linha. Use colchetes para indicar suplementos ao original; todos estes acréscimos devem ser grafados consistentemente. Múltiplos títulos ou indicações adicionais de tempo podem ser adicionados em campos separados. No caso de inserir múltiplos incipits para os quais o título ou a indicação de tempo é o(a) mesmo(a), insira o título ou indicação de tempo somente no primeiro incipit musical.

 
#### **Voz/instrumento (031 $m)**

Insira a parte vocal ou instrumental usando a lista de **abreviaturas de instrumentos do RISM**. Insira **V** para uma parte vocal não especificada. Insira **i** para uma parte instrumental não especificada. Escreva os instrumentos transpositores na altura real. Indique a afinação de um instrumento no campo **Nota geral**.

_Exemplos_:  
pf  
T coro  
org with text

#### Papel (031 $e)

Insira aqui o nome normalizado do papel dramático. Se preencher este campo, certifique-se de preencher também o campo **Papéis dramáticos identificados (595)**. Indique quaisquer acréscimos editoriais entre colchetes. Indique toda informação questionável com uma interrogação.

 

#### Incipit literário (031 $t)

Um incipit literário consiste de algumas poucas das primeiras palavras da peça ou seção e pode ser a primeira linha, a primeira frase ou outro grupo de palavras que faça sentido linguístico. Incipits literários servem para identificar o texto usado e não precisam necessariamente corresponder ao tamanho da música apresentada no incipit musical. Incipits literários podem se incluídos independentemente se um incipit musical for inserido ou não. Por favor observe que regras separadas se aplicam a textos em Latim (ver abaixo).

Incipits literários são dados de forma padronizada. Insira o incipits literário usando a grafia moderna. Consulte o índice **Título/Incipits literários** para ajuda na padronização de seu texto. Insira novos incipits literários se eles não estiverem no índice.

Não coloque partes do texto entre parênteses para adicionar palavras que faltem. Omita marcações de pontuação e repetições no texto. Acentos só devem ser usados tal como aparecem em dicionário ou se eles são gramaticalmente corretos. Escreva os números em começos de textos por extenso, como palavras. Letras maiúsculas e minúsculas seguem as regras da língua respectiva, exceto no caso de designações para Deus (God, Herr, Dio, Dieu, Signore, Lord, etc.) que sempre iniciam com maiúscula. Se o incipit literário é utilizado como o título uniforme (240), certifique-se de que o tamanho e a grafia sejam exatamente iguais.

Omita o texto inteiramente caso não seja possível lê-lo e adicione uma nota dizendo “Texto ilegível” ou similar.

Em línguas de Romance [Romance languages], continue o texto diretamente depois de um apóstrofo e sem um espaço. Uma exceção a essa regra é quando a primeira letra de uma palavra está substituída por um apóstrofo (por exemplo: Fra l'amante e 'l genitor).

Textos confirmados ou derivados que não aparecem na fontes podem ser informados aqui. Nestes casos, insira o texto inteiro entre colchetes. Entre estes estão:

·        Textos de uma parte vocal perdida  
·        Texto dos incipits literários na língua original de uma obra quando a fonte contém uma versão traduzida  
·        Textos de composições vocais que se tornaram o tema de uma variação ou a base de um arranjo instrumental

**Caracteres não-latinos**: Se a sua fonte tem um incipit literário que usa letras ou caracteres não-latinos (alfabeto cirílico/grego/hebraico/coreano etc., caracteres chineses, etc.) insira o **Incipit literário** utilizando a letra original. Traduções ou transliterações são opcionais e podem ser acrescidas em campos adicionais de incipit literário. Adicione tradução que não esteja na fonte entre parênteses. Pode-se traduzir para qualquer um dos idiomas RISM.

**Regras Especiais para textos em Latim**: Insira texto em latim, tanto sacros como seculares. O campo é ligado ao arquivo **Título/Incipits literários**. Dentro do arquivo **Título/Incipits literários**, um termo precedido pelo indicador **t** significa que pode-se obter informação sobre o exato contexto litúrgico, versões variantes e outros assuntos. Se o incipit literário é usado como título uniforme, certifique-se de que a grafia é idêntica, mas lembre-se de que o texto latino em títulos uniformes só é inserido até a vírgula. Use colchetes para inserir textos latinos que não estão nomeados na fonte, mas foram determinados através de pesquisa.

Textos em latim padronizados geralmente correspondem aos textos do _Liber usualis_. No RISM, estes textos usualmente contém uma vírgula. Por exemplo, quando se procura pelo texto “Et in terra pax”, encontram-se cerca de uma dúzia de opções, mas apenas uma tem uma vírgula e esta fonte é utilizada 4.800 vezes na base de dados. Portanto é esta que queremos – presumindo que ela esteja de acordo com a sua fonte. Se o seu incipit literário é somente “Et in terra pax” então isto significa que sua fonte (1) contém somente estas palavras ou (2) continua de uma maneira diferente do _Liber usualis_. É claro que isso é possível, mas na maioria dos casos precisa-se da versão com a vírgula.

**O seguinte se aplica a dados importados:** Informação do campo **Texto (740 $a)**, se usado, deve ser repetida aqui.

#### **Tonalidade ou modo (031 $r)** 

Selecione a tonalidade ou modo na lista.

#### **Armadura de clave (031 $n)**

Insira **x** para tonalidades em sustenido ou **b** para tonalidades em bemóis, seguidas de letras maiúsculas das notas a serem alteradas para cima ou para baixo. Se uma peça está claramente em uma certa tonalidade mas um sustenido ou bemol não está na armadura de clave, os sustenidos ou bemóis omitidos podem ser adicionados entre colchetes. Se não há armadura de clave, deixe o campo em branco.

_Exemplos:_  
xF = Fá sustenido = Sol maior ou Mi menor  
bBE = Si e Mi bemóis = Si bemol maior ou Sol menor  
xFC[G] = Fá e Dó são sustenidos na fonte, mas a peça é claramente em Lá maior, então o último sustenido é adicionado entre colchetes

####   
**Compasso (031 $o)**  

Insira os compassos como frações. As seguintes expressões também são permitidas:

**c** = tempo comum ou  tempus imperfectum cum prolatione imperfecta  
**c/** = alla breve  
**3** = proportio tripla; também **1**, **2**, etc.  
**c3** = proportio tripla  
**c3/2  
c.** = tempus imperfectum cum prolatione perfecta  
**o** = tempus perfectum cum prolatione imperfecta  
**o/** = tempus perfectum cum prolatione minore diminutum  
**o.**  = tempo perfeito, tempus perfectum cum prolatione perfecta

Se o metro muda constantemente, pode-se escrever a primeira fórmula de compasso seguida pela segunda, separada por um espaço. Se o incipit está sem indicação de compasso, deixe este campo em branco.

_Exemplos:_  
4/4  
6/8  
3/4 4/4

Se a indicação de compasso na fonte é obviamente errada, por favor corrija-a para que corresponda ao incipit fornecido. Inclua uma nota explicativa no campo **Nota geral**.

 

#### **Clave (031 $g)**

Selecione uma clave na lista. A letra indica o tipo de clave. Um hífen significa notação moderna. Um sinal de mais significa notação mensural. O número se refere à posição no pentagrama. 

#### **Validade (031 $s)**
Não insira nada neste campo! (Ele é usado somente para dados antigos)    

  

#### **Incipit musical  (031 $p)** 

Insira o incipit musical em forma codificada usando o _Plaine & Easie code_ (ver também [https://www.iaml.info/plaine-easie-code](https://www.iaml.info/plaine-easie-code)). O incipit deve ter pelo menos dois compassos ou seis notas de comprimento.

**1. Oitavas**  
' = na primeira oitava acima do Dó central  
'' = na segunda oitava acima do Dó central  
''' = na terceira oitava acima do Dó central  
, = na primeira oitava abaixo do Dó central  
,, = na segunda oitava abaixo do Dó central  
,,, = na terceira oitava abaixo do Dó central

**2. Valores rítmicos**  
0 = longa  
9 = breve  
1 = whole note / semibreve  
2 = half note / mínima  
4 = quarter note / crotchet / semínima  
8 = eighth note / quaver / colcheia  
6 = 16th note / semiquaver / semicolcheia   
3 = 32nd note / demisemiquaver / fusa  
5 = 64th note / hemidemisemiquaver / semifusa  
7 = 128th note / semihemidemisemiquaver / quartifusa  
7. = notação neumática

Pontos são usados para indicar notas pontuadas. Múltiplos pontos podem ser acrescidos a uma nota.  
4. = dotted quarter note / dotted crotchet / semínima pontuada  
8.. = double dotted eighth note / double dotted quaver / colcheia com dois pontos

**3. Acidentes**  
x = sustenido  
xx = duplo sustenido  
b = bemol  
bb = duplo bemol  
n = natural

**4. Nomes das notas**  
C, D, E, F, G, A, B

**5. Ornamentos**   
g = acciaccatura (sem valor rítmico, precede o nome da nota)  
q = appoggiatura (com valor rítmico, precede o nome da nota)  
qq...r = várias  appoggiaturas ou ornamentos que formam uma unidade (com valor rítmico)

**6. Pausas**

O '-' (sinal de menos) é para uma pausa equivalente a uma única nota. Use '=' (sinal de igual) para uma pausa de compasso inteiro. Para pausa de múltiplos compassos, adicione em seguida ao = o número de compassos. Uma barra de compasso deve ser adicionada para que a pausa múltipla seja exibida.

_Exemplo para uma pausa de colcheia:_  
8-   
  
_Exemplos para uma pausa de um compasso:_  
=  
=1

_Exemplos para pausa de múltiplos compassos:_  
=35

**7. Barras de compasso**  
/ = barra de compasso  
// = barra dupla   
//: = barra dupla com repetição  
:// = barra dupla com repetição  
://: = barra dupla com repetição

**8. Outros símbolos**  
t = trinado (imediatamente em seguida à nota)  
+ = ligadura de prolongamento (imediatamente em seguida à nota; não se deve confundir com uma ligadura de expressão)   
() = fermata/suspensão/pausa (somente uma nota ou pausa individual pode ser colocada entre parênteses; acidentes, indicações de altura, etc. devem estar fora dos parênteses; ver também **10. Ritmos especiais**, abaixo)

Não insira ligaduras de expressão.

**9. União de bandeirolas**  
{ = início da união de bandeirolas  
} = fim da união de bandeirolas  
  
_Exemplo:_  
{qq6'CDEDr}

**10. Ritmos especiais:**  
( = início do ritmo especial  
) = fim do ritmo especial  
   
O valor da duração total do grupo deve ser escrito antes do parêntese de abertura **(**. O valor rítmico da primeira nota deve ser colocado depois do parêntese de abertura **(**, mesmo se é idêntico ao da nota imediatamente anterior à seção do ritmo especial. O número de notas no interior do grupo deve ser indicado antes do parêntese de fechamento **)**. Ele é separado da última nota por um ponto e vírgula **;**.

_Exemplos:_  
8(3ABCDE;5)   = quiáltera de cinco, com cinco fusas, no espaço de uma colcheia  
8({3ABCDE};5) = quiáltera de cinco, com cinco fusas, no espaço de uma colcheia, bandeirolas unidas  

A trêsquiáltera é um caso especial. Estritamente falando, deve ser codificada assim:  
8(6ABC;3) ou 8({6ABC};3).  
Embora também seja permitida a seguinte indicação abreviada:  
(6ABC)  
({6ABC})

Por favor, não se esqueça do valor rítmico no interior dos parênteses!

**11. Atalhos**  
**Nota:** Atualmente, a busca pelo OPAC ignora os elementos repetidos descritos em 11.1 e 11.2. Isto significa que quando se utilizam estes atalhos os incipits não serão totalmente recuperáveis pelo OPAC. Até que isto seja corrigido, por favor escreva o incipit integralmente (o atalho 11.3 pode ser utilizado tal como descrito abaixo)  
  
11.1. Figuras repetidas  
! = Início e final de uma passagem a ser repetida  
f = indicação de repetição  
A figura será repetida tantas vezes quantas o f estiver repetido após o segundo “!”. Isso só é possível no interior de um compasso.

_Exemplo:_  
!{'8ABAG}!ff = esta figura será repetida duas vezes

11.2. Compassos repetidos  
i = repetir o último compasso  
'i' sempre vai entre duas barras de compasso.

_Exemplo:_  
'4ABAG/i/i/ = o compasso será repetido duas vezes

  

11.3. Padrões rítmicos

Quando uma dada sequência rítmica é repetida várias vezes, o padrão rítmico pode ser colocado antes das respectivas notas.

_Exemplo:_  
Ao invés de **8.A6B8C8.D6E8F** a codificação pode ser **8.68ABCDEF**  
A sequência rítmica termina assim que um valor rítmico diferente apareça.

   
**12. Mudança de clave, tonalidade ou compasso:** 

Use **%** para mudar de clave, **$** para mudar a tonalidade ou modo, e **@** para mudar a indicação de compasso. Estes sinais devem ser seguidos da nova indicação (tempo, tonalidade ou clave), seguida por um espaço.

_Exemplos:_  
%C-1 '2A  
%C-1 $xFC '8B  
@3/2 '1C  
$nBE $xFC

 

**13. Abreviaturas**   
Formas abreviadas de notação encontradas no interior da música, tais como tremolos ou signos similares para repetições, devem ser escritas integralmente usando a notação moderna.   
_Exemplo:_  
{'8DDDD} = mínima, tremolo em Ré

 

**14. Acordes**

Insira os acordes da nota mais aguda para a mais grave, separadas por um acento circunflexo ^.  
   
_Exemplo:_  
4’’C^’G^E^C

####  

#### **Nota geral (031 $q)** 

Adicione quaisquer comentários, tais como a afinação de instrumentos transpositores, erros no incipit, o texto literário com a grafia e/ou pontuação original, ou quaisquer ajustes que tenha a fazer. Insira utilizando seu idioma de catalogação.

 

#### **Formação instrumental no movimento (031 $z)**

Neste campo, pode-se indicar a formação instrumental específica para o movimento particular em questão (tal como um movimento dentro de uma peça vocal complexa). Liste a formação instrumental em uma linha usando as abreviaturas de instrumentos do RISM e na ordem padronizada (descrita em **Síntese da formação instrumental [240 $m]**). Use um ponto e vírgula para separar famílias de instrumentos..

_Exemplos:_   
S (Enrico), T (Vanoldo); vl 1, 2, b; [winds]  
S 2 solo; Coro; ob obl; strings, bc