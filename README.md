# Amharic (amh)

## Contents

- `amh`: inflection tables for Amharic (ISO 639-3 `amh`)
- `amh.gloss`: English glosses for the lemmas in `amh`
- `README.md`: this file

## Data
All data were generated using the Amharic morphological generator in 
[HornMorpho](https://github.com/hltdi/HornMorpho), described in [Gasser (2013)](https://www.researchgate.net/publication/228910448_HornMorpho_a_system_for_morphological_processing_of_Amharic_Oromo_and_Tigrinya).

Decisions about lemma frequency and subcategorization were based on [Biniam Gebremichael's Amharic word list](https://www.cs.ru.nl/~biniam/geez/crawl.php).

Common orthographic variants of lemmas and common variant plural forms of nouns are included.
In these cases, the variants are distinguished with the features `LGSPEC1` and `LGSPEC2`.
Predictable orthographic variants are not included.
These include alternate representations of labialized consonants (ቆ/ቈ, ቁ/ቍ, ፏ/ፍዋ, etc.), the two ways of writing the vowel ɨ/i before y (e.g., ጅያ/ጂያ), and the common replacement of ው with ዉ.

The total number of lemmas is 2,465: `V` 670, `N` 1599, `ADJ` 196.

### Verbs

Although the formation of the passive-reflexive, causative, reciprocal, and frequentative from bare roots is relatively productive, many roots fail to appear in the basic, underived form, in which case the morphologically passive-reflexive or causative form is not semantically or syntactically passive-reflexive or causative (for example, "passive-reflexive" ተቀመጠ 'sit', "causative" አለቀሰ 'cry'). For this reason, each of these derived forms of a root is treated as a separate lemma, and only those appearing in the word list have been included. For example, based on the root <sbr> 'break', there are the following lemmas in the repository: ሰበረ 'break', ተሰበረ 'be broken', ሰባበረ 'break repeatedly'. Other possible forms derived from this root are not included.

Verb lemmas appear in all of the major tense-aspect categories and the infinitive:

* perfective (UM: `PFV`)
* finite (UM: `IPFV`) and non-finite imperfective (UM: `NFIN;IPFV`)
* gerundive (UM: `V.CVB`)
* present perfect (UM: `PRF`)
* jussive-imperative (UM: `IMP`)
* infinitive (UM: `V.MSDR`).

Features for the copula (ነው) and verb of existence (ለአ) include "present" (`PRS`).

Verb lemmas are divided into two subcategories based on their occurrence with different subjects or with only (or mainly) third person singular masculine subjects.
Lemmas in the first ("personal") category are further divided into reciprocal verbs, which only appear with plural subjects, and all other verbs, which appear with all eight subject agreement affixes.
Lemmas in the "impersonal" category only appear with third person singular masculine affixes.

Not included in the paradigms: object suffixes, negative prefixes/suffixes, relative prefixes, prepositional/conjunctive prefixes.

### Nouns and adjectives
Nouns and adjectives share most of their morphology and are often not clearly distinguished.

Noun and adjective lemmas are divided into five categories based on their occurrence with the masculine and feminine definite suffixes, with the plural form, and with possessive suffixes.
Those classified as adjectives admit both masculine and feminine definite suffixes and plural forms and have English adjective glosses.
Since most nouns do have inherent gender, gender is only specified for singular nouns with one of the gender-specific definite suffixes.
Gender is not distinguished for plural nouns and adjectives.

Not included in the paradigms: prepositional/case prefixes and the accusative suffix.

## Annotator
Michael Gasser

## Paradigm Samples
### Noun (including plural and possessive suffixes)
ቃል /k'al/ 'word'

	ቃል	ቃሉ	N;DEF;MASC
	ቃል	ቃሉ	N;PSS3SM
	ቃል	ቃላቱ	N;DEF;PL
	ቃል	ቃላቱ	N;PL;PSS3SM
	ቃል	ቃላታቸው	N;PL;PSS3P
	ቃል	ቃላታችሁ	N;PL;PSS2P
	ቃል	ቃላታችን	N;PL;PSS1P
	ቃል	ቃላቴ	N;PL;PSS1S
	ቃል	ቃላት	N;PL
	ቃል	ቃላትህ	N;PL;PSS2SM
	ቃል	ቃላትሽ	N;PL;PSS2SF
	ቃል	ቃላትዎ	N;PL;FORM;PSS2S
	ቃል	ቃላቷ	N;PL;PSS3SF
	ቃል	ቃላቸው	N;PSS3P
	ቃል	ቃላችሁ	N;PSS2P
	ቃል	ቃላችን	N;PSS1P
	ቃል	ቃሌ	N;PSS1S
	ቃል	ቃል	N
	ቃል	ቃልህ	N;PSS2SM
	ቃል	ቃልሽ	N;PSS2SF
	ቃል	ቃልዎ	N;FORM;PSS2S
	ቃል	ቃሎቹ	N;DEF;PL;LGSPEC1
	ቃል	ቃሎቹ	N;PL;PSS3SM;LGSPEC1
	ቃል	ቃሎቻቸው	N;PL;PSS3P;LGSPEC1
	ቃል	ቃሎቻችሁ	N;PL;PSS2P;LGSPEC1
	ቃል	ቃሎቻችን	N;PL;PSS1P;LGSPEC1
	ቃል	ቃሎቼ	N;PL;PSS1S;LGSPEC1
	ቃል	ቃሎች	N;PL;LGSPEC1
	ቃል	ቃሎችህ	N;PL;PSS2SM;LGSPEC1
	ቃል	ቃሎችሽ	N;PL;PSS2SF;LGSPEC1
	ቃል	ቃሎችዎ	N;PL;FORM;PSS2S;LGSPEC1
	ቃል	ቃሎቿ	N;PL;PSS3SF;LGSPEC1
	ቃል	ቃሏ	N;DEF;FEM
	ቃል	ቃሏ	N;PSS3SF

### Verb (all subjects)
ተቀመጠ /tǝk'ǝmmǝt'ǝ/ 'sit'
	
	ተቀመጠ	ተቀምጠን	V.CVB;1;PL
	ተቀመጠ	ተቀምጬ	V.CVB;1;SG
	ተቀመጠ	ተቀምጣችሁ	V.CVB;2;PL
	ተቀመጠ	ተቀምጠሽ	V.CVB;2;SG;FEM
	ተቀመጠ	ተቀምጠህ	V.CVB;2;SG;MASC
	ተቀመጠ	ተቀምጠው	V.CVB;3;PL
	ተቀመጠ	ተቀምጣ	V.CVB;3;SG;FEM
	ተቀመጠ	ተቀምጦ	V.CVB;3;SG;MASC
	ተቀመጠ	መቀመጥ	V.MSDR
	ተቀመጠ	እንቀመጥ	V;IMP;1;PL
	ተቀመጠ	ልቀመጥ	V;IMP;1;SG
	ተቀመጠ	ተቀመጡ	V;IMP;2;PL
	ተቀመጠ	ተቀመጪ	V;IMP;2;SG;FEM
	ተቀመጠ	ተቀመጥ	V;IMP;2;SG;MASC
	ተቀመጠ	ይቀመጡ	V;IMP;3;PL
	ተቀመጠ	ትቀመጥ	V;IMP;3;SG;FEM
	ተቀመጠ	ይቀመጥ	V;IMP;3;SG;MASC
	ተቀመጠ	እንቀመጣለን	V;IPFV;1;PL
	ተቀመጠ	እቀመጣለሁ	V;IPFV;1;SG
	ተቀመጠ	ትቀመጣላችሁ	V;IPFV;2;PL
	ተቀመጠ	ትቀመጫለሽ	V;IPFV;2;SG;FEM
	ተቀመጠ	ትቀመጣለህ	V;IPFV;2;SG;MASC
	ተቀመጠ	ይቀመጣሉ	V;IPFV;3;PL
	ተቀመጠ	ትቀመጣለች	V;IPFV;3;SG;FEM
	ተቀመጠ	ይቀመጣል	V;IPFV;3;SG;MASC
	ተቀመጠ	እንቀመጥ	V;IPFV;NFIN;1;PL
	ተቀመጠ	እቀመጥ	V;IPFV;NFIN;1;SG
	ተቀመጠ	ትቀመጡ	V;IPFV;NFIN;2;PL
	ተቀመጠ	ትቀመጪ	V;IPFV;NFIN;2;SG;FEM
	ተቀመጠ	ትቀመጥ	V;IPFV;NFIN;2;SG;MASC
	ተቀመጠ	ይቀመጡ	V;IPFV;NFIN;3;PL
	ተቀመጠ	ትቀመጥ	V;IPFV;NFIN;3;SG;FEM
	ተቀመጠ	ይቀመጥ	V;IPFV;NFIN;3;SG;MASC
	ተቀመጠ	ተቀመጥን	V;PFV;1;PL
	ተቀመጠ	ተቀመጥኩ	V;PFV;1;SG
	ተቀመጠ	ተቀመጣችሁ	V;PFV;2;PL
	ተቀመጠ	ተቀመጥሽ	V;PFV;2;SG;FEM
	ተቀመጠ	ተቀመጥክ	V;PFV;2;SG;MASC
	ተቀመጠ	ተቀመጡ	V;PFV;3;PL
	ተቀመጠ	ተቀመጠች	V;PFV;3;SG;FEM
	ተቀመጠ	ተቀመጠ	V;PFV;3;SG;MASC
	ተቀመጠ	ተቀምጠናል	V;PRF;1;PL
	ተቀመጠ	ተቀምጫለሁ	V;PRF;1;SG
	ተቀመጠ	ተቀምጣችኋል	V;PRF;2;PL
	ተቀመጠ	ተቀምጠሻል	V;PRF;2;SG;FEM
	ተቀመጠ	ተቀምጠሀል	V;PRF;2;SG;MASC
	ተቀመጠ	ተቀምጠዋል	V;PRF;3;PL
	ተቀመጠ	ተቀምጣለች	V;PRF;3;SG;FEM
	ተቀመጠ	ተቀምጧል	V;PRF;3;SG;MASC

## License
- [Creative Commons Attribution-ShareAlike 3.0 Unported (CC BY-SA 3.0)](https://creativecommons.org/licenses/by-sa/3.0/)


