A **Busca** no Muscat está disponível através de uma **busca facetada** e através de **filtros**.

#### Busca facetada

####

A **Busca facetada** (menu superior ao meio) está disponível para buscar dados em um conjunto OPAC comum. O usuário que tem autorização para editar uma fonte em particular, visualizará um botão editar que leva diretamente para o modo de edição do Muscat.

Uma **busca por incipit** está disponível em Busca avançada, através do menu Busca facetada. Um teclado permite a inserção de notas de maneira fácil. Quatro modos de busca estão disponíveis em vários graus de imprecisão:  
1. Altura exata: O incipit corresponde às alturas exatas.  
2. Intervalo: Alturas exatas são ignoradas, mas os mesmos intervalos são procurados. Isto permite a inclusão de **transposições** de uma dada melodia.  
3. Contorno refinado de altura: Intervalos são ignorados, mas somente os movimentos ascendentes e descendentes da melodia são procurados.  
4. Contorno bruto de altura: Este é o mais impreciso de todos. O contorno aproximado da melodia é procurado.  

Na parte inferior da página, o campo **Incipit** permite ao usuário inserir o código _Plaine & Easie_ bruto (ele pode ser copiado e colado de uma fonte, por exemplo). O pentagrama musical é pré-visualizado e automaticamente atualizado no editor de fontes.  


Todos os outros campos presentes na Busca avançada podem ser combinados com a busca por incipit.  

O OPAC RISM tem uma busca simplificada por incipit na [Busca avançada](https://opac.rism.info/index.php?id=3&L=0). Veja a [página de ajuda](https://opac.rism.info/index.php?id=8&L=0#c38) para mais informações.

Não deixe de fazer sempre uma busca por incipit antes de inserir uma fonte como anônima! Faça uma [busca por incipit primeiro](https://youtu.be/kKc0zzc8cbo)!  

#### Filtros do Muscat  

Os **filtros** do Muscat oferecem buscas simples, mas poderosas.

É possível inserir em cada campo:

- Palavras únicas
- Palavras múltiplas:   
tanto sem aspas: **lass noch**  
 como entre aspas: **"lass noch"**  
- Truncamento com  ? ou \*  
**?**: A interrogação substitui exatamente uma letra. **B?cher** encontrará Bucher e Bacher.   
**\***: O asterisco pode ser usado para truncar ou substituir qualquer número de letras. **B\*cher** encontrará Bucher e Bacher, mas também Boucher e Bötticher.
- AND, OR, NOT, ( ): Tire proveito da busca booleana. Use parênteses para agrupar sua busca. Exemplos:  

  - Compositor contém: **(Bach AND Johann) NOT Sebastian**  
para encontrar Johann Michael Bach e Johann Christian Bach mas não Johann Sebastian Bach
  - Sigla contém: **D-B AND (I-\* OR F-P\*) **   
para encontrar todos os impressos na biblioteca D-B de que haja também exemplares em Itália ou Pari **s**   



Por favor, observe o seguinte para todas as seções:

- **Data**

  - **Buscando por data:** Insira datas no formato YYYY-MM-DD. O dia é definido para meia-noite por padrão.
  - **Data única ("de"):** Se somente o campo da esquerda (o "de") for preenchido, obtêm-se todos os registros modificados ou criados **desde aquela data** (inclusive registros criados durante o dia naquela data).   
Exemplo: Última modificação   
**2012-02-07** - [vazio]  
recuperará todos os registros editados a partir de 07 de Fevereiro de 2012 até hoje.
  - **Data única ("até")**: Se somente o campo da direita (o "até") for preenchido, obtêm-se todos os registros modificados ou criados até a meia-noite daquela data.  
Exemplo: Última modificação   
 [vazio] -  **2012-02-07**  
recuperará todos os registros editados a partir do começo até a meia-noite de 07 de Fevereiro de 2012 (significando que registros criados durante o dia 07 de fevereiro não serão incluídos).
  - **Faixa de datas**: Observe que uma vez que a hora do dia é definida para a meia-noite, para buscar por todos os registros criados em 07 de Fevereiro de 2012, por exemplo, deve-se inserir a data inicial 2012-02-07 (entendida como meia-noite de 07 de Fevereiro de 2012) e a data final de 2012-02-08 (entendida como meia-noite de 08 de Fevereiro de 2012). Isto incluirá todas as fontes criadas durante o dia. Uma busca de 2012-02-07 até 2012-02-07 resultará vazia!



Por favor, observe o seguinte para buscar **Fontes**:  

- **Sigla contém**: Busca pelas letras de uma sigla. Este campo diferencia maiúsculas e minúsculas. Por exemplo:  
**D-\*** = todas as fontes na Alemanha  
**D-B\*** = todas as fontes em cidades da Alemanha que começam com B  
**D-B** = todas as fontes na Staatsbibliothek zu Berlin



#### Nomes de pessoas  

Por favor, observe o seguinte para buscar **Nomes de pessoas**:

- **Nome:** Busca nos campos **Título**** – Nome de pessoa (100 $a) **e** Variante de nome (400 $a)**.
- **Datas:** Busca no campo **Anos de nascimento e morte (100 $d)**, tanto ao digitar um ano como ao usar as seguintes abreviaturas: sc  a  p  c \*  +  /
- **Profissão**: Busca o campo **Profissão ou função (550 $a)**, que são inseridas em inglês.
- **Código de país**: Busca a nacionalidade usando a norma ISO 3166 [http://www.iso.org/iso/home/standards/country\_codes.htm](http://www.iso.org/iso/home/standards/country_codes.htm)
- **Locais**: Busca o campo **Nome geográfico (551)**. Isto inclui locais de nascimento, morte, origem ou de atividade.
