### Recurso externo (856)  

Use este campo para informar um link para recurso externo que possua uma ligação direta com a fonte descrita.

**URL do Recurso externo (856 $u)**

  

Insira o URL do recurso externo. Use sempre links permanentes (permalinks).   
  

**Nota sobre o recurso externo (856 $z) **

Este campo é obrigatório quando se insere um link para um recurso externo.   
Insira uma breve descrição que explique porque o URL é relevante para a fonte descrita, usando o seu idioma de catalogação. 

_Exemplos_:   
Cópia digital   
Marca d'água na p. 4   
Homepage ou página do projeto   
Detalhe da encadernação    
Registro bibliográfico   
Link para o registro em Bach Digital    
Link para a obra no Frescobaldi Thematic Catalogue Online   
Entrada nos registros da igreja   
Link para RISM ID no. 806155758, GB-Lbl Add. 14209 f.23r-27v, um acompanhamento [setting] por N. Porpora deste texto     
Fonte concordante em GB-Ob 

**Tipo de link (856 $x)**

Este campo é obrigatório quando se insere um link para um recurso externo. Selecione entre os seguintes: 

- 

**Fonte digitalizada**: O link é dirigido para um website externo que é uma cópia digitalizada do recurso a ser descrito. Links para repositórios institucionais são preferenciais, mas, caso nenhum esteja disponível, então links para repositórios externos, como o Internet Archive ou o IMSLP, são permitidos. 

_Exemplo_:   
[https://mirador.acdh.oeaw.ac.at/musikarchivspitz/A-SPD\_A15/](https://mirador.acdh.oeaw.ac.at/musikarchivspitz/A-SPD_A15/) 

- 

**Manifesto IIIF**: O objeto ligado é um objeto JSON legível por máquina, processado por um visualizador de documentos interno como o diva.js. O documento está embutido diretamente na página web. Muitas das vezes, “manifest”, “iiif” ou algo semelhante aparece no link. 

_Example_:*[  
https://iiif.lib.harvard.edu/manifests/drs:2820650](https://iiif.lib.harvard.edu/manifests/drs:2820650)*

Nos casos em que ambos os links para um visualizador externo e um manifesto IIIF estejam disponíveis, repita o campo e liste ambos os links separadamente.

_Exemplo_: 

  - Recurso externo: [http://nrs.harvard.edu/urn-3:FHCL.Loeb:537966](http://nrs.harvard.edu/urn-3:FHCL.Loeb:537966)   
Nota: versão digitalizada   
Tipo de link: fonte digitalizada 

  - Recurso externo: [https://iiif.lib.harvard.edu/manifests/drs:2820650](https://iiif.lib.harvard.edu/manifests/drs:2820650)   
Nota: manifesto IIIF    
Tipo de link: manifesto IIIF 

- **Outro**: Link para outros recursos que não correspondem ao recurso que está a ser descrito. 

 

**Tipos de recursos externos **

**Tipo de link 856 $x: Fonte digitalizada**  
Link somente para a fonte descrita no registro RISM. Use apenas links permanentes (permalinks). Se links permanentes não estiverem indisponíveis, pode-se criar um link para uma página onde o link para a fonte digitalizada possa ser facilmente encontrado (como um registro bibliográfico em um catálogo de biblioteca). Podem-se incluir partes da fonte digitalizada (como algumas páginas) caso uma versão integralmente digitalizada não esteja disponível. 

Links inseridos como música digitalizada aparecem no filtro "Fontes digitalizadas" no OPAC público (opac.rism.info). 

**Tipo de link 856 $x: Outro **

Outros tipos de recursos externos podem incluir os tipos listados abaixo. Certifique-se de sempre deixar claro para o usuário por quê um determinado link foi incluído, tal como em uma **Nota geral (500)**. 

- **Detalhes de fontes**  
Detalhes de fontes que apresentem apenas alguns aspectos, como marcas de água, encadernações, título de página, ou capa. 

- **Registros catalográficos/Bases de dados**  
Inclui entradas bibliográficas em catálogos externos ou entradas em bases de dados externas. Bases de dados acadêmicas externas que forneçam informação útil podem ser incluídas, mas considere se poderão estar melhor inseridas como um link para literatura secundária.  

- **Catálogos eletrônicos de obras,  enciclopédias online, fontes de referência digitalizadas**  
De um modo geral, use os campos **Literatura Secundária (691)** ou **Catálogo de obras (690)** para se referir a obras de referência online, como catálogos de obras ou enciclopédias. No entanto, como um serviço para os usuários, pode ser útil incluir adicionalmente um link direto para um determinado local dentro do recurso, através do campo 856. 

- **Fontes arquivísticas, fontes históricas**  
Inclui registros ou documentos municipais digitalizados, correspondência digitalizada, jornais históricos. Assegure-se de que a relevância da fonte arquivística esteja clara em uma **Nota geral (500)**, então inclua o link direto aqui. Para jornais históricos, deve-se inserir o nome do jornal como literatura secundária, mas pode-se inserir aqui um link para uma página específica onde se encontra o artigo; certifique-se de que informação sobre o artigo, como o título e a data, esteja incluída em uma nota. 

- **Websites**  
 Inclui websites de projetos, websites de agências de financiamento externas, ou outros websites relevantes.  

- **Outros registros RISM**  
Somente crie um link para outro registro RISM se o registro tiver uma relação direta com a fonte que está sendo descrita. Use apenas links permanentes (permalinks) do RISM OPAC ([https://opac.rism.info/)](https://opac.rism.info/)). Deve estar claro para o utilizador porque o registro é relevante para a fonte. No mínimo, nomeie a instituição detentora, cota ou código de referência, e número de ID RISM em uma nota. Às vezes a ligação para uma fonte diferente pode ser melhor explicada em uma **Nota geral (500)**. Se fizer referência a outros registros RISM em outro local do seu registro, não é necessário criar um link para eles neste campo. Não é necessário criar um link aqui para todas as fontes concordantes no RISM; na verdade, essa é uma busca infrutífera porque o número de fontes no Muscat cresce diariamente.  

- **Referências a fontes relevantes noutras instituições, mas não no RISM**  
 Se quiser criar um link para uma fonte que não esteja ainda no RISM, considere se é possível que seu grupo de trabalho insira primeiro o libreto, manuscrito ou tratado digitalizado, ou adicione materiais a um impresso específico. A Redação Central terá prazer em ajudar a verificar se uma fonte está no RISM, caso isto seja esperado. No entanto, é compreensível caso não seja possível criar um novo registro para uma fonte antes. 

- **Outras fontes relevantes**  
 Inclui fontes concordantes, obras concordantes, árias ou seções de obras concordantes, fontes que serviram de base para a fonte que está a ser descrita. Esses links podem ser dirigidos para os objetos digitalizados ou links para catálogos externos.