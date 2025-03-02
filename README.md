# SuffixalDerivation

**Authors:** 

Ivelina Stoyanova, Svetlozara Leseva (Institute for Bulgarian Language, Bulgarian Academy of Sciences)

Verginica Barbu Mititelu (Romanian Academy Research Institute for Artificial Intelligence)

Gianina Iordăchioaia (University og Graz, Austria)

**Contributors**

We thank our student assistants Anna-Lena Feichter and Mariya Kavaldzhieva for a first round of manual annotation of the data.

**1. MSD DATASET.**
This dataset is distributed by the PWN project as a standoff file consisting of 17,739 derivationally related noun-verb pairs,
which are labeled with a morphosemantic relation (such as Agent, Instrument, Event, etc.) 

License: Wordnet 3.0 License (https://wordnet.princeton.edu/license-and-commercial-use) granting 'permission to use, copy, modify and distribute' for both commercial and non-commercial use. 

Source: https://wordnetcode.princeton.edu/standoff-files/morphosemantic-links.xls

Reference: Fellbaum, C., Osherson, A., and Clark, P.E. (2007). Putting Semantics into WordNet's "Morphosemantic" Links. 
In: Proceedings of the Third Language and Technology Conference, Poznan, Poland. Reprinted in: Responding to Information 
Society Challenges: New Advances in Human Language Technologies, eds. Z. Vetulani and H. Uszkoreit. Springer Lecture 
Notes in Informatics vol. 5603:350-358 (2009)

**2. DERIV DATASET.**
This dataset covers 18,344 synset pairs in total, between whose members a derivational relation exists in PWN. Additionally, 
we identify automatically 23,418 pairs of literals within each pair of synsets which share a common base and use 
verbalising and nominalising suffixes.
In the DERIV DATASET there are 4,520 noun-verb pairs of literals that are not in the MSD DATASET and are linked 
by a derivational relation alone (i.e., with no morphosemantic relation assigned), e.g. carbon and carbonate.

**3. SUFFIX DATASET.**
This dataset comprises 7 verbalising and 26 nominalising suffixes in total, which are reduced to 5 and 11 invariant
verbalising and nominalising suffixes, respectively. These represent direct noun-to-verb or verb-to-noun derivations, 
including also zeroN and zeroV suffixes. There are further 36 suffixes which take part in more complex derivational 
patterns, such that both the noun and the verb are derived from a third word (e.g., rigidify – rigidness both 
derived from the adjective rigid; criminalise – criminal both derived from the adjective criminal) or they are 
derived in several steps (e.g., argue – argumentation with an intermediary step argument; attract – attractiveness 
with an intermediary attractive).

**4. RESULTING DATASET 1.0.** 
The dataset presents a comprehensive description of derivationally related pairs of verb–noun literals including
the suffixes, the direction of derivation (whenever available), as well as semantic information in the
form of an assigned morphosemantic relation between the noun and the verb. While based on the derivational 
relation, in essence, the morphosemantic relation is semantic and thus extends beyond the particular pair of 
literals, and holds between the corresponding verb and noun synsets.
The datases covers 21,251 verb-noun pairs with identified suffixal derivational model and assigned morphosemantic 
relation. 

The resource is distributed under the Creative Commons Attribution 4.0 International license.

**References**

Stoyanova, Ivelina, Svetlozara Leseva, Gianina Iordăchioaia, Verginica Barbu Mititelu. _Expanding and 
Enhancing Derivational and Morphosemantic Relations in Princeton WordNet_. In: Proceedings of the 
13th International Global Wordnet Conference (GWC2025), Pavia, Italy, January 2025.

Barbu Mititelu, Verginica, Iordăchioaia, Gianina, Leseva, Svetlozara and Stoyanova, Ivelina. 
_The meaning of zero nouns and zero verbs_. In: The Semantics of Derivational Morphology: 
Theory, Methods, Evidence, edited by Sven Kotowski and Ingo Plag, Berlin, Boston: De Gruyter, 
2023, pp. 63-102. https://doi.org/10.1515/9783111074917-004



