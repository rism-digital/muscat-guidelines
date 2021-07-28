### Usando o Muscat

1. **Onde posso encontrar tutoriais sobre o Muscat?**  
Todos os tutoriais estão ligados à página do Muscat no sítio web da Redação Central do RISM: [http://www.rism.info/en/community/muscat.html](http://www.rism.info/en/community/muscat.html.)[  
](http://www.rism.info/en/community/muscat.html.)
  
2. **Como posso contatar outros usuários do Muscat?**  
Para contatar os desenvolvedores do Muscat: reporte quaisquer erros, questões, comentários ou sugestões para muscat@rism.info a qualquer momento.  
   
O **[RISM Muscat](https://groups.google.com/forum/#!forum/rism-muscat)**, um Grupo Google, é a lista de discussão oficial do Muscat, à qual cada usuário deve se associar. Anúncios oficiais da Redação Central e dos desenvolvedores do Muscat serão divulgados somente através deste grupo. Adicionalmente, todos os usuários do Muscat são estimulados a fazer perguntas ou lançar tópicos para discussão.   
  
Não é necessário ter uma conta Google. Um convite para se associar ao grupo será enviado juntamente com as informações sobre a sua conta Muscat.  
  
Também existe um canal de discussão no Slack, em:   
[https://rismcommunity.slack.com/](https://rismcommunity.slack.com/)  
  
3. **Toda a literatura citada no Muscat está na Redação Central?**  
Não, somente a literatura rotulada "HB" ou "Handbibliothek" ou "RISM-ZR" está de fato na biblioteca da Redação Central. Estes materiais são fontes de apoio para todos os contribuidores do RISM, de maneira que, caso tenhamos uma publicação que algum colaborador precise consultar, basta informar por email e tentaremos obter nela as informações necessárias. Mesmo no caso de uma publicação que não tenhamos na Redação Central, existe uma boa chance de que conheçamos alguém ou alguma instituição que a tenha.   
  
4. **O que devo fazer se esqueci a minha senha ou se quero modificá-la?**  
As senhas são administradas pela Redação Central. Entre em contato conosco caso tenha perdido a senha. Não é permitido modificar a senha fornecida.  
  
5. **Posso mostrar o Muscat para meus colegas? Posso fazer demonstrações do Muscat em conferências ou em workshops?**  
Sim, por favor! Uma versão de treinamento do Muscat está disponível exatamente para este propósito em [https://muscat-training.rism.info](https://muscat-training.rism.info/).   
  
Todos os usuários Muscat podem fazer login nela com suas credenciais pessoais. Existem também 99 contas de treinamento ("training01@rism.info" até "training99@rism.info") disponíveis para usuários individuais. Qualquer uma destas contas de treinamento podem ser usadas. Por favor contacte a Redação Central do RISM (Jennifer Ward, jennifer.ward@rism.info) para obter a senha atualizada.  
  
Qualquer coisa que estiver na versão de treinamento pode ser acrescentada, editada ou apagada. Ela é sincronizada uma vez por semana, (aos domingos) com os dados atuais do Muscat. Isto significa que novos registros estarão então disponíveis mas também que os registros criados na versão de treinamento serão apagados.   
  
6. **No histórico de modificação, o que significa se “[system]” está listado como o autor?**  
Pode-se ver uma edição do sistema se um dos campos indexados ligados ao seu registro foi modificado. A modificação no registro de autoridade também fica registrada como uma modificação no seu registro.  
  
7. **Posso criar registros baseados em descrição de catálogos impressos?**  
Sim! Às vezes, por várias razões, não é possível acessar a fonte e somente a descrição em um catálogo impresso ou em um catálogo de obras está disponível. Pode-se usar tal descrição como uma base para criar um registro. Ao fazê-lo, inclua uma **Nota geral (500)** tal como “Registro baseado na descrição encontrada em YouV” e vincule o catálogo com uma ligação no campo **Referência bibliográfica (691)**.
  
8. **Quando os registros aparecem no catálogo público em opac.rism.info?**  
Os registros Muscat são mandados para publicação no catálogo público em  opac.rism.info uma vez por mês, por volta do dia 19. Os registros estarão visíveis poucos dias depois.
  
9. **E se uma fonte no RISM não pertence mais à instituição indicada no registro RISM?**  
Use a sigla **N. N.** para situações em que a localização atual da fonte seja desconhecida, como nos casos em que ela esteve epositada em uma instituição mas foi retomada e agora se encontra em mãos privadas. Isso acontece muito raramente. Contate a Redação Central se uma fonte precisa desta sigla.

### Aspectos técnicos do Muscat
**1. Quais são os requisitos técnicos para o Muscat?**  

- O Muscat é independente de plataforma e trabalha tanto em Macs como em PCs.
- O acesso é feito através de uma URL e requer uma conexão à internet.
- O Muscat trabalha melhor com telas que tenham pelo menos 1366 x 768 pixels de resolução.
- O Muscat está otimizado para Firefox e Chrome. Não use o Internet Explorer!   

**2. Alguns aspectos técnicos sobre o Muscat.**

- O Muscat é “open source”, código aberto. O código fonte está disponível no repositório [GitHub](https://github.com/rism-ch/muscat).
- O Muscat é uma aplicação Ruby on Rails.
- O [Verovio](http://www.verovio.org/pae-examples.xhtml) é usado para representar incipits musicais através de MEI. 
- O Solr é usado como um motor de busca.
- O Muscat tem [um serviço SRU](https://github.com/rism-ch/muscat/wiki/SRU) e um [serviço de download SRU](https://github.com/rism-international/sru-downloader) para recuperar registros MARCXML.
- O Muscat é compatível com Unicode (UTF-8).  
Mais informação sobre o desenvolvimento do Muscat pode ser encontrada no [website do RISM Suíça](http://rism-ch.org/infrastructure/muscat.html?locale=en).   

**3. Alguns aspectos técnicos sobre a busca por incipit no Muscat.**

- Ela é baseada no motor [Themefinder](http://www.themefinder.org/) desenvolvido pela Universidade de Stanford. 
- Ela aproveita o sistema de indexação subjacente (Solr), usado para todas as consultas de busca no Muscat, que foi personalizado para permitir a análise da notação PAE usada no editor. O processo de indexação é completamente transparente para os usuários e catalogadores, e a inserção normal da notação codificada é necessária somente no campo 031.  

**4. Algumas características do Muscat**

- **Versões** : Catalogadores podem ver as modificações feitas nos registros.
- **VIAF** : Nomes de pessoas podem ser importados através do [Virtual International Authority File (VIAF)](https://viaf.org/). 

**5. Quais são os planos para futuros aprimoramentos do Muscat?**

- Integrar imagens usando [IIIF](http://iiif.io/)   
- Coletar feedback do usuário.
- Acrescentar traduções adicionais da interface e das diretrizes.
- Importar/exportar registros em lote para o Muscat e do Muscat para outros sistemas.