[![](http://ehci.googlecode.com/svn/wiki/images/logo_ita.gif)](http://www.ita.br/)

Este projeto visa difundir o uso de latex em teses do Instituto Tecnológico de Aeronáutica, tanto para alunos da graduação como para alunos do mestrado e doutorado. O trabalho hospedado neste site é composto por templates para geração das teses nos formatos requisitados pela instituição.
Conta-se com o apoio de todos os usuários, tanto na requisição de novas funcionalidades, como para atender a uma nova especificação do ITA, ou mesmo para "codificar" estas alterações.

# Downloads #

[Exemplo de Tese (.tar.gz)](http://italus.googlecode.com/files/ExemploTeseITA.tar.gz)

[Exemplo de Tese (.zip)](http://italus.googlecode.com/files/ExemploTeseITA.zip)

[Classe Latex (.tar.gz)](http://italus.googlecode.com/files/classeITA.tar.gz)

[Classe Latex (.zip)](http://italus.googlecode.com/files/classeITA.zip)


# Introdução #

A iniciativa de criar uma classe LaTeX para as teses desenvolvidas no ITA partiu de alunos de Pós-Graduação da Instituição, que sentiram a necessidade de resolver os problemas de formatação dos documentos científicos referentes às suas pesquisas.

O grupo ITALUS foi criado em Maio de 2004, com o propósito de divulgar e incentivar o uso do LaTeX no ITA, assegurar a continuidade e aprimoramento da classe desenvolvida, bem como motivar o desenvolvimento de novas classes e/ou estilos para os demais documentos científicos produzidos no Instituto, como TGs, Relatórios Técnicos entre outros.

Todo o material foi desenvolvido de acordo com a licença GPL. Desta forma, qualquer alteração nos seus componentes deverá ser disponibilizada.


# Dependências #

  * Macros para LaTeX [abnTeX](http://abntex.codigolivre.org.br/node6.html#download) (utilizado para a formatação das referências bibliográficas - NBR 6023)

  * Estilo makeglo.sty (by Klaus Steding-Jessen, utilizado para a criação/formatação do glossário - acompanha a classe)

# Documentação sobre LaTeX e BibTeX #

  * [Breve Introdução ao LaTeX2e](http://www.ctan.org/tex-archive/info/lshort/portuguese-BR/lshortBR.pdf)
  * [The Not So Short Introduction to LaTeX2e](http://www.ctan.org/tex-archive/info/lshort/english/lshort.pdf)
  * [BibTeXing](http://www.ctan.org/tex-archive/biblio/bibtex/distribs/doc/btxdoc.tex)
  * [Help on LaTeX Math Symbols](http://www.astro.ku.dk/help/LaTeX/ltx-117.html)
  * [LaTeX Math Symbols](http://www.fi.uib.no/Fysisk/Teori/KURS/WRK/TeX/symALL.html)


# FAQ #

**1. O que é LaTeX? Onde eu aprendo a utilizar esse "negócio" ?**

Utilizando o conceito de reusabilidade, clique aqui. :o)

**2. Qual a vantagem de utilizar LaTeX e a classe ITA.cls?**

Em primeiro lugar, não ter que usar o Word e passar por várias de suas frustrações na composição de um documento científico e conseqüentemente longo, como uma tese. Além disso, a filosofia do LaTeX prega que os usuários devem preocupar-se somente com conteúdo e **nunca** com formatação. Quem nunca passou por aqueles "pequenos probleminhas", tais como: perder a numeração de capítulos/seções, ter que renumerar equações, entrar em pânico com mensagens de arquivos corrompidos, figuras que insistem em ir para onde não devem, entre outros, emitidos pelo Word e assemelhados...??? :-)

**3. Utilizando a classe eu não preciso me preocupar com mais nada?**

Quem nos dera ... Suas contas para pagar, problemas pessoais, relacionamentos com vizinhos, processos burocráticos, exigências do orientador e, principalmente o conteúdo da sua tese, definitivamente não serão resolvidos pela classe ... :-) Talvez numa versão futura ... :o) O objetivo é "livrar" o pós-graduando do árduo trabalho de formatação da tese, nada além disto.

LEMBRE-SE: a utilização da classe não exime o aluno da leitura do "Manual para Confecção de Tese: Mestrado - Doutorado.", bem como do cumprimento de todas as exigências da Instituição.

**4. A classe ITA.cls e os demais componentes resolvem todos os meus problemas de formatação?**

Praticamente. A classe ITA foi criada baseada nas especificações contidas no "Manual para Confecção de Tese: Mestrado - Doutorado." disponível no site da Biblioteca Central do Instituto. Como existem certas especificações indefinidas no próprio Manual, recorreu-se sempre à ABNT e a funcionários da biblioteca para saná-las. Entretanto, ressalta-se que é um tanto quanto complicado simular todas as especificidades que uma tese pode requerer. Desta forma, torna-se muito importante um feedback por parte dos usuários, relatando possíveis problemas com a classe, de forma que os autores possam corrigir bugs e adicionar novas funcionalidades.

**5. A classe ITA.cls gera a tese eletrônica com os links? E gera a tal Folha de Registro do Documento??**

Mas é claro que sim!!!!! O objetivo não é livrar o pós-graduando do trabalho de formatação? ;-)

**6. O que são estas dependências que o pacote possui?**

Novamente, o conceito de reusabilidade está presente. Assim, utilizamos certos pacotes/classes desenvolvidos para fins específicos, como por exemplo, a parte de formatação das referências bibliográficas, desenvolvido/mantido pelo projeto abnTeX.

**7. As referências bibliográficas atendem a NBR 6023?**

Sim. A equipe do projeto abnTeX criou um estilo bst que atende à "norma" 6023. Entretanto, como a norma está sempre inventando coisas novas :-D, obviamente é preciso estar atento em utilizar sempre a versão mais nova das classes disponíveis no site do respectivo projeto.

**8. O que é o BibTeX?**

Olha a reusabilidade aí de novo ... clique aqui.

**9. Como eu gerencio meu arquivo de referências bibliográficas?**

Existem vários programas disponíveis na internet que tornam fácil o gerenciamento de arquivos contendo suas referências. Que tal o JabRef?

**10. Existe uma lista de discussão sobre TeX / LaTeX?**

Sim. Acreditamos que a TeX-BR seja uma das melhores.

**11. Como eu faço para criar um glossário na minha tese?**

No arquivo makeglo.sty, que acompanha a classe, tem isso explicadinho explicadinho ... :-)

**12. Estou escrevendo meu Exame de Qualificação para o Doutorado. Posso utilizar a classe ITA?**

Claro que sim!!! A classe prevê também esse tipo de documento.

**13. Estou escrevendo meu TG. Posso utilizar a classe ITA?**

Errr ... ainda não :o) A formatação para TGs deverá ser desenvolvida em breve. Estamos enfrentando sérios problemas de "tempo". Como a necessidade é a mãe da invenção, algum voluntário desenvolvendo TG está disposto a nos ajudar?

**14. Já comecei a escrever minha Tese no Word. E agora? Posso convertê-la para LaTeX e começar a utilizar a classe ITA?**

Mas é claro tchê! Uma das melhores alternativas de solução :-) seria converter teu arquivo doc para o formato rtf e utilizar o rtf2latex2e. Alguns ajustes no "braço" serão necessários, mas com certeza ganharás tempo no futuro utilizando LaTeX.

**15. Existe alguma lista de discussão do ITALUS?**

Lóóóóóóógico ... :-) Dê uma olhada aqui.

**16. Não achei uma pergunta/resposta aqui ... E agora? Volto para o Word? :-)**

Pelamordedeus, NÃO faça isso!! :o) Inscreva-se na lista de discussão do ITALUS e mande sua dúvida. Os membros da lista estarão sempre prontos para ajudá-lo, dentro de suas disponibilidades e conhecimentos, além de estarem sempre no processo de "angariar" mais integrantes ao "movimento use LaTeX"! ... :-)

# Links #

  * [Grupo de usuários brasileiros de (La)TeX](http://biquinho.furg.br/tex-br)
  * [Projeto ABNTeX](http://abntex.codigolivre.org.br/)
  * [Página de Donald Knuth](http://www-cs-faculty.stanford.edu/~knuth/)
  * [Comprehensive TeX Archive Network - CTAN](http://www.ctan.org/)

# Ferramentas #

  * [tex2latin](http://www.inf.ufrgs.br/utug/download/tex2latin), script para converter comandos de acentos (ex. \'a) para o caracter acentuado correspondente (no caso, á)
  * [latin2tex](http://www.inf.ufrgs.br/utug/download/latin2tex), que faz o processo inverso (ex. á para {\'a})

# Lista de Discussão #

O ITALUS possui uma lista de discussão, cujo objetivo é o mesmo de qualquer lista: dirimir dúvidas, reportar bugs, sugerir modificações, etc, etc, etc. Abaixo estão os endereços.
| Enviar mensagem: | italus {at} yahoogroups.com |
|:-----------------|:----------------------------|
| Inscrever-se: | italus-subscribe {at} yahoogroups.com |
| "Desinscrever-se" :o)  | italus-unsubscribe {at} yahoogroups.com |
| Mail para o "manda-chuva" da lista | italus-owner {at} yahoogroups.com |
|Página da lista de discussão 	| http://groups.yahoo.com/group/italus/ |

Sugerimos que as dúvidas sejam sempre enviadas para a lista de discussão.

# Autores #

  * [Fábio Fagundes Silveira](http://fabiosilveira.net/) - EX-MANTENEDOR
  * Benedito Carlos de Oliveira Maciel
  * [Giovani Volnei Meinerz](http://www.comp.ita.br/~giovani)
  * [Alan Wilter Sousa da Silva- INPE (Colaborador)](http://www.lac.inpe.br/~alan)