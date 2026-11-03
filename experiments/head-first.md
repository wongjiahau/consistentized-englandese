# Experiment: head-first noun phrases

Status: experiment, not part of the specification.

This file translates some example texts of SPEC.md again. It keeps every CE affix rule and the verb slots. It adds one change to word order: in a noun phrase, the head noun comes first and every modifier follows it. The goal is to remove *of the*, the possessive *'s* and the possessive pronouns.

Malay (*pintu rumah*, "door house" = the door of the house), Arabic and Hebrew (the construct state) work in this way.

## Rules used

- **H1. Head first.** In a noun phrase, the head noun comes first. Adjectives, participles, ordinals and possessors follow it: *a flight long* (*a long flight*), *the day oneth* (*the first day*). Degree adverbs follow the adjective: *noisefuler slightly* (*slightly noisier*). Manner adverbs follow the verb: *survived narrowly*.
- **H2. Determiners stay in front.** Articles, demonstratives, quantifiers and numbers come before the head: *the*, *a*, *this*, *each*, *every*, *all*, *no*, *several*, *most*, *40*. In the DP analysis the determiner is the head of the phrase, so this is head-first too.
- **H3. Possessor by position.** A noun phrase that comes straight after the head and its adjectives is the possessor. *of* and *'s* are not used: *the popularity of Reyes*, *Reyes's popularity* → *popularness Reyes*.
- **H3a. *of* in a chain.** A possessor can have its own possessor. In such a chain, only the last possessor is bare; each earlier link takes *of*: *Electors of Branch numberfulest of Lawizorage State* (Electors of the numberfulest Branch of the Lawizorage of the State). The *of* shows where each step starts, and H4 still drops the *the*. A phrase with one possessor has no *of*: *popularness Reyes*.
- **H4. Construct state.** A possessor drops its *the*. A head that has a possessor also drops its *the*, because the possessor makes it definite: *the door of the house* → *door house*. Other determiners stay: *a door house* (*a door of the house*), *price a house* (*the price of a house*), *day oneth each month*.
- **H5. Pronoun possessors.** A pronoun possessor uses the object form: *student her* (*her student*), *partys thons* (*their partys*), *Descendorage me'all* (*our Posterity*). *my*, *your*, *his*, *its*, *my'all*, *thons'* and possessive *her* are not used.
- **H6. Mirror order.** Several adjectives come in the mirror order of English: the adjective that is nearest to the head in English is nearest to it in CE: *a long transocean flight* → *a flight transocean long*.
- **H7. Order in the phrase.** Determiner + head + adjectives + possessor + prepositional phrase + relative clause. The possessor's own adjectives follow it: *door red house old* (*the red door of the old house*).
- **H8. Compounds.** A hyphenated compound (§3.7) is head-first too: *alarm-smoke* (*smoke alarm*), *minister-finance* (*finance minister*). Inflectional suffixes go on the head, as in English *mothers-in-law*: *alarms-smoke*. Prefixes go on the first word, which is now the head: *exminister-finance*.
- **Names stay.** A name with *of* in it keeps it (*the United States of America*). A name of more than one word is one unit (*Ana Reyes*, *New Hampshire*).
- ***of* after a verb or an adjective stays.** Only *of* between two nouns goes: *composenmust of Members*, *accused the governorage of corruptment*, *prewarnened of arrivement thons*.

Why the order is not ambiguous: by P1, each word has one part of speech, so a reader always knows whether the word after a head is an adjective (H1) or a noun (H3). H4 also gives a signal: a head with *the* has no possessor, so *the noise it maked* is a relative clause ("the noise that it made"), not "its noise".

Admission (P7): the change removes competing forms for one meaning. English marks a possessor with *of*, with *'s*, with a possessive pronoun or with a noun before the head (*the house roof*). H3 keeps one form.

## A. News example (Appendix C)

**CE** (82 words)

> Velmora's Archminister Ana Reyes narrowly survived an unconfidence vote on Tuesday, two weeks before the general electment. The opposeors, under exfinance-minister Tomas Bell, accused the governorage of corruptment and of underfunding public hospitals. Reyes's popularness be now at its lowest since 2022. Reyes promised an anticorruptment law and sayed that the cogovernorage increase'llednot taxes. Thousands of protestors meeted outside the parliament. Analyzeors sayed that the result be unpreseeable. Most of the voteorage be still undecided, and both electands be untrustabler than thons' partys.

**Head-first CE** (79 words)

> Ana Reyes, Archminister Velmora, survived narrowly a vote unconfidence on Tuesday, two weeks before the electment general. The opposeors, under Tomas Bell, exminister-finance, accused the governorage of corruptment and of underfunding hospitals public. Popularness Reyes be now at lowest it since 2022. Reyes promised a law anticorruptment and sayed that the cogovernorage increase'llednot taxes. Thousands protestors meeted outside the parliament. Analyzeors sayed that the result be unpreseeable. Most voteorage be still undecided, and both electands be untrustabler than partys thons.

| CE | Head-first CE | Rule |
|---|---|---|
| *Velmora's Archminister Ana Reyes* | *Ana Reyes, Archminister Velmora,* | H3; the title becomes an apposition, so that the name does not read as a possessor |
| *Reyes's popularness* | *Popularness Reyes* | H3, H4 |
| *at its lowest* | *at lowest it* | H4, H5 |
| *Thousands of protestors*, *Most of the voteorage* | *Thousands protestors*, *Most voteorage* | H3, H4: *thousands* and *most* are the heads |
| *thons' partys* | *partys thons* | H5 |
| *exfinance-minister* | *exminister-finance* | H8 |
| *an unconfidence vote* | *a vote unconfidence* | H1; *unconfidence* is a noun, so this is H3 (a vote of no confidence) |

## B. Preamble (Appendix G.1)

**CE** (51 words)

> I'all the People of the United States, in Order to form a perfecter Uniteion, establish Justness, sureize homeal Tranquilness, provide for the common defendment, promote the general Welfare, and secure the Blessions of Freeness to myself'all and my'all Descendorage, do ordain and establish this Constituteion for the United States of America.

**Head-first CE** (46 words)

> I'all, People United States, in Order to form a Uniteion perfecter, establish Justness, sureize Tranquilness homeal, provide for the defendment common, promote the Welfare general, and secure Blessions Freeness to myself'all and Descendorage me'all, do ordain and establish this Constituteion for the United States of America.

| CE | Head-first CE | Rule |
|---|---|---|
| *the People of the United States* | *People United States* | H3, H4 |
| *the Blessions of Freeness* | *Blessions Freeness* | H3, H4 |
| *my'all Descendorage* | *Descendorage me'all* | H5 |
| *the United States of America* | no change | a name |

## C. House of Representatives (Appendix G.3)

**CE** (38 words)

> The House of Representors composenmust of Members choosed every twoth Year by the People of the several States, and the Electors in each State havemust the Qualifyions needed for Electors of the numberfulest Branch of the State Lawizorage.

**Head-first CE** (31 words)

> House Representors composenmust of Members choosed every Year twoth by People several States, and the Electors in each State havemust the Qualifyions needed for Electors of Branch numberfulest of Lawizorage State.

| CE | Head-first CE | Rule |
|---|---|---|
| *The House of Representors* | *House Representors* | H3, H4 |
| *every twoth Year* | *every Year twoth* | H1, H2 |
| *the People of the several States* | *People several States* | H4: *several* is not *the*, so it stays |
| *Electors of the numberfulest Branch of the State Lawizorage* | *Electors of Branch numberfulest of Lawizorage State* | a chain of three possessors, so H3a; *State Lawizorage* (the legislature of the State) is a possessor too, and as the last link it is bare |

## D. Lease (Appendix I)

**CE** (93 words)

> 1. The Leaseary paymust the rent to the Leaseor on the oneth day of each month.
>
> 2. The Leaseary subletoknot the premises without the writed consent of the Leaseor. The Leaseor refuseok consent only on fair grounds.
>
> 3. The Leaseary repaintmustnot the premises at the end of the term.
>
> 4. If the rent payennot within fourteen days, the Leaseor endok this lease by writed notice.
>
> 5. The Leaseary inspectbest the smoke-alarms each month.
>
> 6. Any repairs that carryen've out by the Leaseary reportenmust to the Leaseor.
>
> 7. The deposit returnen'll to the Leaseary within thirty days after the lease end've.

**Head-first CE** (85 words)

> 1. The Leaseary paymust the rent to the Leaseor on day oneth each month.
>
> 2. The Leaseary subletoknot the premises without consent writed Leaseor. The Leaseor refuseok consent only on grounds fair.
>
> 3. The Leaseary repaintmustnot the premises at end term.
>
> 4. If the rent payennot within fourteen days, the Leaseor endok this lease by notice writed.
>
> 5. The Leaseary inspectbest the alarms-smoke each month.
>
> 6. Any repairs that carryen've out by the Leaseary reportenmust to the Leaseor.
>
> 7. The deposit returnen'll to the Leaseary within thirty days after the lease end've.

| CE | Head-first CE | Rule |
|---|---|---|
| *on the oneth day of each month* | *on day oneth each month* | H1, H2, H4 |
| *the writed consent of the Leaseor* | *consent writed Leaseor* | H1, H3, H4, H7 |
| *at the end of the term* | *at end term* | H3, H4 |
| *the smoke-alarms* | *the alarms-smoke* | H8 |

## E. Pronoun possessors (Appendix D, paragraph 1)

**CE** (67 words)

> Last week, a retired engineoress and her exstudent visited a bakerylet in London. The engineoress, a Japanianess, speak fluent Englandese and Netherlandese. She arrive'ved after a long transocean flight, and her student comed by biwheel. The bakeoress, a cheerful Walesaness, prewarnened of thons' arrivement. She telled thons that her oven misfunction'ved twice that month, that its heatmeter beed unrelyable, and that the noise it maked beed frightsome.

**Head-first CE** (67 words)

> Week last, an engineoress retired and exstudent her visited a bakerylet in London. The engineoress, a Japanianess, speak Englandese fluent and Netherlandese. She arrive'ved after a flight transocean long, and student her comed by biwheel. The bakeoress, a Walesaness cheerful, prewarnened of arrivement thons. She telled thons that oven her misfunction'ved twice that month, that heatmeter it beed unrelyable, and that the noise it maked beed frightsome.

*speak fluent Englandese and Netherlandese* becomes *speak Englandese fluent and Netherlandese*, because *Englandese and Netherlandese fluent* can mean that only the second language is fluent. English has the same problem in the other direction.

## Size

| Text | CE | Head-first CE | Change |
|---|---|---|---|
| A. News | 82 | 79 | −4% |
| B. Preamble | 51 | 46 | −10% |
| C. House | 38 | 31 | −18% |
| D. Lease | 93 | 85 | −9% |
| E. Pronouns | 67 | 67 | 0% |

Every saved word is an *of*, a *the* or both. H3a gives back an *of* for each extra link in a chain, but not the *the*. A text saves in proportion to its count of *X of the Y*. Legal text has the most (C), and narrative text with pronoun possessors saves nothing (E): *her student* and *student her* have the same length.

## Gaps

- **It changes sentences, not only words.** §1 says that CE changes word forms and replaces auxiliaries, and leaves sentence style alone. Head-first order changes almost every noun phrase. It is the largest cost to an English reader that CE has tryed so far: *Week last*, *a vote unconfidence*.
- **Pronoun possessors before a verb.** *that heatmeter it beed unrelyable* reads first as "that the heatmeter, it was unreliable". A pronoun possessor at the end of a subject looks like a second subject.
- **Two indefinite objects.** *gived a child a book* can mean "gave a child a book" or "gave a child of a book". H4 saves the definite case: *gived the child the book* has two *the*s, so it has two phrases. With *a*, use *to*: *gived a book to a child*.
- **Bare plural possessors.** *rights persons* is "the rights of persons" and "the rights of the persons". H4 removes the difference.
- (Closed.) **Long chains.** Without *of*, *Electors Branch numberfulest Lawizorage State* made a reader hold four nouns before the meaning closed, and the adjective *numberfulest* sat between two nouns. H3a puts *of* back at each step but the last: *Electors of Branch numberfulest of Lawizorage State*.
- **Titles and names.** *Archminister Velmora Ana Reyes* reads as "the Archminister of Velmora-Ana-Reyes". Each title becomes an apposition with commas.
- **Compounds.** With H3, *minister finance* (the minister of the finance) and *minister-finance* (a finance minister) differ only by a hyphen. It is not clear that CE still needs head-first compounds. Derivational suffixes still go on the last word (C2), which is no longer the head: *sugar-blood-lowize*.
- **Adjective scope over *and*.** *Englandese and Netherlandese fluent* (see E).
