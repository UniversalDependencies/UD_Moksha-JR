# Summary

Erme Universal Dependencies annotated texts Moksha are the origin of UD_Moksha-JR with annotation (CoNLL-U) for texts in the Moksha language,
it originally consists of a sample from a number of fiction authors writing originals in Moksha.


# Introduction

This is a collection of sentences from almost entirely original Moksha-language literary sources dating back to the 1880s with
 Universal Dependencies (UD) annotations. It has been constructed in alignment with parallel work on Erzya language Universal Dependencies.

There are also about 20 parallel sentences translated by Marina Levina from the Erzya and Russian
texts: [http://ilazki.thinkgeek.co.uk/brat/#/uralic/myv](http://ilazki.thinkgeek.co.uk/brat/#/uralic/myv) and
[http://ilazki.thinkgeek.co.uk/brat/#/uralic/rus](http://ilazki.thinkgeek.co.uk/brat/#/uralic/rus)

The sent_id attribute value is not randomized in works published earlier than 1938. Developing UD documentation can be found at https://github.com/UniversalDependencies/docs for Erzya.

[https://github.com/rueter/erme-ud-moksha](https://github.com/rueter/erme-ud-moksha)


# Acknowledgments

The original annotation has been performed by Jack Rueter at the University of Helsinki with the help of Marina Levina
at the Mordovian State University im. P.N. Ogariova, Mordvin Languages Department using morphological tools 
that were originally built with funding from a Kone Foundation «Language Programme» funded project: 
«Creation of Morphological Parsers for Minority Finno-Ugrian Languages» (2013–2014) with the linguistic work of
Merja Salo, and facilitated at the Norwegian Arctic University in Tromsø. Work with the Moksha treebank
builds upon previous experience with the UD_Erzya-JR treebank and continued consultations and discussions
with Francis Tyers, Tommi Pirinen, Jonathan Washington. Without the Moksha writers themselves, however, we would be no where…

Annotation work is simultaneous to finite-state transducer development by Nadjezhda Kabaeva, Marina Levina and Jack Rueter in the [GiellaLT](https://giellalt.uit.no/lang-mdf) infrastucture, which also works with Constraint Grammar disambiguation of the morphological analysis.

## References

If you use this data set in an academic publication, I would be ever so grateful if you cited it as follows:

Jack Rueter. (2018, January 20). Erme UD Moksha (Version v1.0) http://doi.org/10.5281/zenodo.1156112

[![DOI](https://zenodo.org/badge/118232421.svg)](https://zenodo.org/badge/latestdoi/118232421)


## About the authors

* Кузнецов, Юрий 1975: Сембось ушеткшни киста. Саранск.
* Mishanina, V. I. (Мишанина, В. И.) 1972: Лиендень очконяса. Мокша №3, 38–39. Саранск. (MishaninaValentina_LiendenyOchkonyasa_Moksha-1972-No2-pp38-39) (Мордовиянь Кадошкина аймаконь Адаж веле)
* Мокшень кяль. Синтаксис : учебник / аноклаф-тиф Н. С. Алямкинонь и О. Е. Поляковонь профессорхнень вятемаснон ала. -- Саранск : Изд-во Мордов. ун-та, 2008. -- 200 с. -- На морд.-мокша яз.

 In release 2.7 additional example sentences used in the Moksha-language grammar *Мокшень кяль, синтаксис: учебник* (2008) were included. These sentences are marked with sent_id-s that contain the components `MKS:2008:page:n-th sentence:original author`. It is hoped that the inclusion of these sentences will help cover various grammatical phenomena in Moksha syntax. When refering to these sentences, we advise you also cite the original source:

- Алямкин, Н. С. (гл. ред.); Гришунина, В. П.; Иванова, Г. С.; Кабаева, Н. Ф.; Кулакова, Н. А.; Левина, М. З.; Поляков, О. Е. (гл. ред.); Рогожина, В. Ф.; Седова, П. Е. 2008: * Мокшень кяль. Синтаксис : учебник [Moksha language. Syntax: reader]. -- Саранск : Изд-во Мордов. ун-та.
- Alâmkin, N. S. (chief ed.); Grushinina, V. P.; Ivanova, G. S.; Kabaeva, N. F.; Kulakova, N. A.; Levina, M. Z.; Polâkov, O. E. (chief ed.); Rogozhina, V. F.; Sedova, P. E. 2008: * Mokshen' kâl'. Sintaksis: uchebnik [Moksha language. Syntax: reader]. -- Saransk : Izd-vo Mordov. un-ta.

# Changelog

* 2020-11-15 v2.7
  * Adding more example sentences quoted in Moksha syntaxis (2008).
* 2020-05-15 v2.6
  * Adding example sentences quoted in Moksha syntaxis (2008).
  * Expanding advmod:mmod, :lmod, :tmod and adding NameTypes.
* 2019-11-15 v2.5
  * Initial release in Universal Dependencies.


<pre>
=== Machine-readable metadata (DO NOT REMOVE!) ================================
Data available since: UD v2.5
License: CC BY-SA 4.0
Includes text: yes
Genre: nonfiction news
Lemmas: converted from manual
UPOS: converted from manual
XPOS: manual native
Features: converted from manual
Relations: converted from manual
Contributors: Rueter, Jack; Levina, Maria; Kabaeva, Nadezhda; Molnár, Judit
Contributing: here
Contact: rueter.jack@gmail.com
===============================================================================
</pre>
