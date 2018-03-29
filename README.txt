# Summary

The Cantonese-HK UD treebank was manually annotated by Tak-sum Wong and Herman H. M. Leung at City University of Hong Kong, by finely transcribing three films shooted by students from the School of Creative Media. The data are in Tradiaitonal Chinese.  These trees form a parallel treebank with those in Chinese-HK.

# Introduction

ORIGIN

#send_id = 1 to 410
Title: Missing days / 小時光
Source: https://www.youtube.com/watch?v=1qSMiw0vhzU
Duration: 30 minutes
Fluency: The dialogues are mostly prepared.

#send_id = 411 to 547
Title: Tempo in Temple / 廟眾樂樂
Source: https://www.youtube.com/watch?v=8e8Lqd6grTE	
Duration: 16 minutes
Fluency: This is an interview.  Most sentences are not prepared and thus contain a lot of disfluencies.  A lot of reparandums are tagged. 

#send_id = 548 to 650
Title: What day is today / 今日星期幾
Source: https://www.youtube.com/watch?v=bBGwxIDiZ_o
Duration: 31 minutes
Fluency: The dialogues are mostly prepared.  This film contains a lot of dead air.

DATA

Since there are only 6264 tokens, only the test set is provided.

BASIC STATISTICS

Tree count:  650
Word count:  6264
Token count: 6264
Dep. relations: 46 of which 15 language specific
POS tags: 15
Category=value feature pairs: 1

FORM and LEMMA

Since Cantonese is not an official language, there is no standard written form.  In this treebank, the FORM field adopts the popular written form while we have tried our best to find different characters attested in dictioanries or other studies for the LEMMA field to discern the homophones, in order to faciliate computer processing.

POS TAGGING

When determining the POS, one usually considers both the "morphological evidence", i.e., the linguistic form of the word, as well as the "distributional evidence", i.e., its syntactic use in the sentence. Usually, these two kinds of evidence should agree; in some cases, however, the POS of some word is tentatively alterned to fullfil the special purpose of the author.

Take an example in English, consider the word "pen" in the sentence "I pen a letter".  Morphological evidence suggests the word "pen" should be tagged as an noun (NN), reflecting its normal usage. Distributional evidence suggests it should be tagged as a verb, since this word is in a typical syntactic position of verb in a SVO language.

When these two kinds of evidence contradict one another, the morphological evidence prevails.

# Acknowledgments

This work was partially supported by a grant from the PROCORE-France/Hong Kong Joint Research Scheme sponsored by the Research Grants Council and the Consulate General of France in Hong Kong (Reference No.: F-CityU107/15 and N 35322RG); and by two Strategic Research Grants (Project No. 7004494 and No. 7004736) from City University of Hong Kong.

# References

When using this treebank, please cite at least one paper from the following references:
Tak-sum WONG, Kim GERDES, Herman LEUNG, and John LEE. "Quantitative Comparative Syntax on the Cantonese-Mandarin Parallel Dependency Treebank" Proceedings of the Fourth International Conference on Dependency Linguistics, pp. 266−275, Pisa, Italy, September 2017.

=== Machine-readable metadata =================================================
Documentation status: partial
Data source: manual
Data available since: UD v2.1
License: CC BY-SA 4.0
Includes text: yes
Genre: spoken
Lemmas: manual native
UPOS: manual native
XPOS: not available
Features: manual native
Relations: manual native
Contributors: Gerdes, Kim; Lee, John; Leung, Herman; Wong, Tak-sum
contributing: elsewhere
Contact: tswong-c@my.cityu.edu.hk; jsylee@cityu.edu.hk
===============================================================================
