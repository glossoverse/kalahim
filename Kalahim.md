---
title: Kalahim grammar sketch
author: Stefano Coretta
output:
  pdf_document:
    keep_tex: yes
    latex_engine: xelatex
    number_sections: yes
    includes:
      in_header: preamble.tex
mainfont: FreeSerif
papersize: a4
indent: true
---

# Phonology

## Consonants

Kalahim has stops, fricatives, nasals, approximants, and a trill. Stops contrast by voicing, while the fricatives are all voiceless.

|             | labial | dental | palatal | velar | glottal |
|-------------|--------|--------|---------|-------|---------|
| stop        | p b    | t d    | tʃ dʒ   | k g   |         |
| fricative   | f      | s      | ʃ       |       | h       |
| nasal       | m      | n      |         |       |         |
| approximant | w      | l      | j       |       |         |
| trill       |        | r      |         |       |         |

1. The approximant /w/ is always preceded by a consonant. For example: *amua* /amwa/, *fuanen* /fwanen/. Cf. \*\*/wana/. Historical note: Single onset /w/ was lost everywhere, and the eventual resulting vowel combination became a diphthong or simplified to a simple vowel. Examples: *reik-* 'to turn' /reik/ < *\*rewik-*, *iel*- 'to sing' /jel/ < /jail/ < *\*yawal-*.

## Vowels

Kalahim has a five-vowel system, with high, mid, and low heights, front, central, and back backness. Note that the mid vowels are both mid-high.

|      | front | central | back |
|------|-------|---------|------|
| high | i     |         | u    |
| mid  | e     |         | o    |
| low  |       | a       |      |

There are also the following diphthongs: /ei/, /eu/.

## Phonotactics

The basic syllabic structure of Kalahim is C(C)V(C). Onsetless syllables are only permitted in word-initial position. Independent of syllabic affiliation, no more than two consecutive consonants are allowed in any position in the word.
Any consonant, except /tʃ/ and /dʒ/, can be word-final.

Allowed onset clusters:

* pr, pl, pw, pj
* tr, tl, tw, tj
* kr, kl, kw, kj, ks, kʃ
* br, bl, bw, bj
* dr, dl, dw, dj
* gr, gl, gw, gj
* sp, st, sk, sw, sj
* ʃp, ʃt, ʃk, ʃl, ʃw, ʃj
* fl, fr, fw, fj
* hw, hj
* mw, mj
* nw, nj
* rw, rj
* lw, lj

## Stress

Stress is intensive and it falls always on the penultimate syllable of the word in plurisyllabic words, and in the only syllable of monosyllabic words.

# Writing system

Consonants:

|             | labial | dental | palatal | velar | glottal |
|-------------|--------|--------|---------|-------|---------|
| stop        | p b    | t d    | c j     | k g   |         |
| fricative   | f      | s      | sh      |       | h       |
| nasal       | m      | n      |         |       |         |
| approximant | u      | l      | i       |       |         |
| trill       |        | r      |         |       |         |

Vowels:

|      | front | central | back |
|------|-------|---------|------|
| high | i/y   |         | u    |
| mid  | e     |         | o    |
| low  |       | a       |      |

* [i] is written as ⟨i⟩ and ⟨y⟩ for historical reasons.
* ⟨ai, æ⟩ /e/, ⟨au, å⟩, /o/, ⟨oe, öe⟩ /we/.

# Morphosyntax

## Word order

The general word order is SVO. Complements follow the noun they refer to, but adjectives precede it.

\ex \begingl \glpreamble Blin manai acaroni.//
\gla blin mainai acaro-ni//
\glb strong warrior east-GEN:SG//
\glft `The strong warrior of the East.'//
\endgl \xe

## Verbs

*Revision*: Verbs end in vowel (are there C-final verbs? what about nouns?). In the Present, the vowel coalesces with the Present Tense suffix *-u*: a-u > o, e-u > ie, i-u > y, o-u > o, u-u > u. Past and Future are analytic? Past uses *lusho* 'to go' as auxiliary (new 'to go' is different). Future is just the verb stem plus the Subj suffixes.

Infinitive: -sh (< -tʲ). Hypothetical from -bʷi, a form of future?

Passive: it was -s, now it has Non-Past form (Present and Future) which is original Gnomic (that takes on future meaning in Active). Passive Past is with auxiliary *dlanti* 'to come'.

*reika* 'to turn'

| Active | present    | past           | future    | hypothetical      |
|--------|------------|----------------|-----------|-------------------|
| 1s     | reiko-go  | lurgo  reika-s | reika-go  | lurby-go  reika-s |
| 2s     | reiko-ni  | lurni  reika-s | reika-ni  | lurby-ni  reika-s |
| 3sm    | reiko-lo  | luelo  reika-s | reika-lo  | lurby-lo  reika-s |
| 3sf    | reiko-re  | luere  reika-s | reika-re  | lurby-re  reika-s |
| 3sn    | reiko-lah | luelah reika-s | reika-lah | lurby-lah reika-s |
| 1pl    | reiko-min | lurmin reika-s | reika-min | lurby-min reika-s |
| 2pl    | reiko-ty  | lusty  reika-s | reika-ty  | lurby-ty  reika-s |
| 3plm   | reiko-su  | luesu  reika-s | reika-su  | lurby-su  reika-s |
| 3plf   | reiko-shi | lueshi reika-s | reika-shi | lurby-shi reika-s |
| 3pln   | reiko-sah | luesah reika-s | reika-sah | lurby-sah reika-s |

| Passive | non-past   | past          |
|---------|------------|---------------|
| 1s      | reika-gos  | lango reika-s |
| 2s      | reika-nis  | leni  reika-s |
| 3sm     | reika-los  | lelo  reika-s |
| 3sf     | reika-res  | lere  reika-s |
| 3sn     | reika-les  | lelah reika-s |
| 1pl     | reika-meis | lemin reika-s |
| 2pl     | reika-tys  | lanty reika-s |
| 3plm    | reika-sus  | lesu  reika-s |
| 3plf    | reika-shis | leshi reika-s |
| 3pln    | reika-ses  | lesah reika-s |

\ex \begingl \glpreamble Lango (done)ganis nide.//
\gla lan-go       (done)gani-s     ni-de//
\glb PST:PASS-1sg save-PASS.PRT  2s-ABL:SG//
\glft `I was saved by you.'//
\endgl \xe

Present participles are formed with the suffix -*m* which is attached to the verb root and they can be declined according the to consonant declination.

\ex \begingl \glpreamble Catieni shonamen//
\gla catie-ni      shona-m-en//
\glb person-GEN:SG think-PTCP-GEN:SG//
\glft `Of the thinking person.'//
\endgl \xe

### Copula

There are two copulas in Kalahim, *aum-* and *ash-*. The first is used with the predicative case and refers to a permanent or substantial feature of the subject. For example, *om-a-go ned-es* 'I am (a) man'. *ash-* is used with temporary states and feelings, like in *ash-a-lah cul* 'it is sweet'.

| aum-     | past     | present  | future   | hypothetical |
|---------|----------|----------|----------|-----------|
| 1s      | aum-i-go   | om-a-go    | aum-u-go   | aum-yl-go   |
| 2s      | aum-i-ni   | om-a-ni    | aum-u-ni   | aum-yl-ni   |
| 3sm     | aum-ie-lo  | om-a-lo    | aum-uo-lo  | aum-yl-lo   |
| 3sf     | aum-ie-re  | om-a-re    | aum-uo-re  | aum-yl-re   |
| 3sn     | aum-ie-lah | om-a-lah   | aum-uo-lah | aum-yl-lah  |
| 1pl     | aum-e-min  | om-a-min   | aum-o-min  | aum-yl-min  |
| 2pl     | aum-e-ty   | om-a-ty    | aum-o-ty   | aum-yl-ty   |
| 3plm    | aum-ei-su  | om-a-su    | aum-ou-su  | aum-yl-su   |
| 3plf    | aum-ei-shi | om-a-shi   | aum-ou-shi | aum-yl-shi  |
| 3pln    | aum-ei-sah | om-a-sah   | aum-ou-sah | aum-yl-sah  |

| ash-     | past     | present  | future   | hypothetical |
|---------|----------|----------|----------|-----------|
| 1s      | ash-e-go  | ash-a-go    | ash-o-go  | ash-ily-go   |
| 2s      | ash-e-ni  | ash-a-ni    | ash-o-ni  | ash-ily-ni   |
| 3sm     | ash-e-lo  | ash-a-lo    | ash-o-lo  | ash-ily-lo   |
| 3sf     | ash-e-re  | ash-a-re    | ash-o-re  | ash-ily-re   |
| 3sn     | ash-e-lah | ash-a-lah   | ash-o-lah | ash-ily-lah  |
| 1pl     | ash-e-min | ash-a-min   | ash-o-min | ash-ily-min  |
| 2pl     | ash-e-ty  | ash-a-ty    | ash-o-ty  | ash-ily-ty   |
| 3plm    | ash-e-su  | ash-a-su    | ash-o-su  | ash-ily-su   |
| 3plf    | ash-e-shi | ash-a-shi   | ash-o-shi | ash-ily-shi  |
| 3pln    | ash-e-sah | ash-a-sah   | ash-o-sah | ash-ily-sah  |

The verb *om*- which means 'to be (locative)' derives from *aum-* although it does not have allomorphy. It is also used at the neuter to mean 'There is/are' (expletive), in which case it is used with the predicative case. *om*- follows the standard verbal conjugation.

\ex \begingl \glpreamble Omago Limlin'ija.//
\gla om-a-go         Limlin'-ija//
\glb be.PRED-PRS-1s  Limlin-LOC:SG//
\glft `I am in Limlin.'//
\endgl \xe

\ex \begingl \glpreamble Omielah jekines.//
\gla om-ie-lah       jeki-nes//
\glb be.STA-PST-3sn  monkey-PRED:PL//
\glft `There were (some) monkeys.'//
\endgl \xe

### Negation

A verb is negated by placing the negative adverb *an* after the verb.

\ex \begingl \glpreamble Dluntuogo an fladriba.//
\gla dlunt-uo-go an  fladri-ba//
\glb come-FUT-1s NEG forest-ALL:SG//
\glft `I will not come to the forest.'//
\endgl \xe

## Nouns

Nouns end either in a vowel or a consonant and follow their respective class declension. Archaic forms of suffixes are given in square brackets. The predicative plural ending has two forms, -*nes* and -*nesse* which tend to be respectively the standard in the spoken and written language.

The predicative is used with the verb *aum-* 'to be', which has an existential meaning (while *ash*- is more generally stative).

| vowel         | singular       |   plural       |
|---------------|----------------|----------------|
| nominative    | [varies]       | -m             |
| accusative    | -l [arc. -lu]  | -le [arc.-leo] |
| predicative   | -sse           | -nes(se)       |
| dative        | -vo            | -vi            |
| instrumental  | -ru [arc.-kru] | -du [arc.-dru] |
| genitive      | -ni [arc.-nig] | -nek           |
| locative      | -ja [arc.-jai] | -ce            |
| allative      | -ba            | -pe            |
| ablative      | -da [arc.-de]  | -te            |
| vocative      | -ku            | -ho            |

| consonant     | singular        | plural           |
|---------------|-----------------|------------------|
| nominative    | [varies]        | -am              |
| accusative    | -olu            | -elo             |
| predicative   | -es [arc.-esse] | -enes            |
| dative        | -ol             | -ive             |
| instrumental  | -ur [arc.-ruk]  | -udu [arc.-udru] |
| genitive      | -en             | -ek              |
| locative      | -ija            | -ice             |
| allative      | -iba            | -ipe             |
| ablative      | -ida [arc.-eda] | -ete             |
| vocative      | -uk             | -oho             |

## Subordination

**Complement clauses** are introduced by the particle *nai*. All complement clauses are finite (they always have a finite verb).

*Kabasiesu nai korashiego.*

    kabas-ie-su   nai korash-ie-go
    know-PST-3plm SUB be.happy-PST-1s
    'They knew I was/have been happy.'

*Tokago nai noirgah-a-go nil.*

    tok-a-go    nai sibu-a-go   ni-l
    want-PRS-1s SUB meet-PRS-1s 2s-ACC:SG
    'I want to meet you.'

Subject complement clauses are preceded by an independent clause of the form 'be.PRED + ADJ/PTCP'.

*Omalah pushaitam nai sibuemin.*

    om-a-lah        pushait-am  nai sibu-o-min
    be.PRED-PRS-3sn scare-PTCP  SUB meet-PST-1pl
    'It scares me that we will meet.'

**Adverbial clauses** are introduced by a variety of adverbial subordinating conjunctions.

**Relative clauses** are introduced by *ki* and a resumptive pronoun is used. The resumptive pronoun in the relative clause is in the case and position it would be if the clause were independent. A nominative resumptive pronoun is generally omitted. If the antecedent is the object of the main clause and the subject of the relative close, *ki* and the subject pronoun are omitted and the antecedent is in the nominative case.

*Lonum ki voinalo korashalo.*

    lonu-m  ki  voin-a-lo     korash-a-lo
    boy-PL  REL play-PRS-3sm  be.happy-PRS-3sm
    'The boy who plays is happy.'

*Nem korashielo mol noirgahielo lonu voinielo.*

    nem       korash-ie-lo    mol   noirgah-ie-lo lonu    voin-ie-lo
    yesterday be.hapy-PST-3sm GRND  see-PST-3sm   boy.NOM play-PST-3sm
    'Yesterday he rejoiced in seeing the boy who was playing.'

Cf. with the object complement clause *Nem korashielo mol noirgahielo nai lonu voinielo* 'Yesterday he rejoiced in seeing that the boy was playing.'

*Firkiniego catieru ki noirgahieni laholu.*

    firkin-ie-go  catie-ru        ki  noirgah-ie-ni lah-olu
    speak-PST-1s  person-INST:SG  REL see-PST-2s    3sn-ACC:SG
    'I spoke with the person you saw.'

*Noirgahiego catiel ki firkinieni lahur.*

    noirgah-ie-go catie-l       ki  firkin-ie-ni  lah-ur
    see-PST-1s    person-ACC:SG REL speak-PST-2s  3sn-INST:SG
    'I saw the person you spoke to.'

# Glossed examples

\ex \begingl \glpreamble Ashani lof namshal gonji shimalah ki mallabalah vinedolu, e Firniluk goniguk!//
\gla ash-a-ni   lof   namsha-l     gonji   shim-a-lah ki    mallab-a-lah    vined-olu e   Firnil-uk      gonig-uk//
\glb be-PRS-2s  like  star-ACC:SG  so.much shine-PRS-3sn CONJ  obscure-PRS-3sn other-ACC:PL oh  Firnil-VOC:SG  my-VOC:SG//
\glft `You are like a star that is so bright to obscure the others, oh my Firnil!'//
\endgl \xe
