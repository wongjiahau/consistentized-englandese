# Consistentized Englandese — Specification

Status: draft v0.1

## 1. Purpose

Consistentized Englandese (CE) is a regularized form of English. Each grammatical or derivational meaning has one affix. CE replaces irregular and competing forms with the regular form, including in existing English words.

CE changes word forms. It also replaces some auxiliary verbs with verb suffixes (§3.1.1). It does not limit sentence length, voice, tense or style. Any text in English can be written in CE.

## 2. Core principles

- **P1. One word, one meaning.** Each word in the CE dictionary has one meaning and one part of speech.
- **P2. One meaning, one affix.** Each affix meaning has one affix. Different meanings use different affixes.
- **P3. Conditioned allomorphy only.** An affix may have more than one written form (allomorph). An allomorph exists only to prevent awkward spelling or pronunciation: a forced consonant cluster, a vowel clash, a triple letter, or a change in the sound of the base. A fixed rule always chooses the form; the writer never chooses freely. All allowed allomorphs are listed in §4.
- **P4. Plain base.** Derivations attach to the plain English base word. They do not attach to a Latin or Greek root. Example: *see* + *-able* → *seeable*, not *visible*. The test is that a reader can guess the meaning from the parts. A loan word that a reader cannot guess is rebuilt in this order:
  1. **Part swap.** Swap each Latin or Greek part for the plain English word with the same meaning: *legislative* (*legis*, "of law") → *lawizive*; *domestic* (*domus*, "home") → *homeal*. Stop at the first level that has a plain English word with the same meaning: *inhabit* (*habitare*, "dwell") → *dwell*, not a form of *have* (*habere*).
  2. **Synonym swap.** If no part swap works, derive from a plain word with the same meaning: *posterity* → *descendorage*; *liberty* → *freeness*.
  3. **Keep.** Otherwise, the loan stays as one base word: *Congress*, *Senate*, *torture*.

  Never coin a new root. A loan that is common and easy to guess stays as it is: *machine*, *tranquil*. When more than one form is possible, the dictionary (§6) chooses one.
- **P5. Overwrite.** If a regular CE form exists, it replaces the traditional English form. Example: *impossible* → *unpossible*. This includes technical vocabulary: *cardiology* → *heartology*, *flammable* → *burnable*.
- **P6. Codified names are exempt.** If an outside standard defines a name, CE keeps it. Otherwise, CE builds it. The exempt names are:
  - chemical names from IUPAC nomenclature (*carbon dioxide*, *sulfate*, *ferric oxide*)
  - SI units and SI prefixes (*kilometer*, *milligram*, *microsecond*)
  - scientific names of species (*Homo sapiens*)
  - registered and trade names (*Ltd*, product names)
  - part numbers, standard numbers and codes

  Reason: these names are already consistent systems with outside owners. A CE text must match the drawings, parts lists and data sheets it refers to.

  Terms with a legal or regulatory definition are not exempt. They follow the affix rules like any other word: *flammable* → *burnable*, also on a safety label.

## 3. Affix rules

### 3.1 Inflection

| Meaning | Affix | Term | Replaces | Examples |
|---|---|---|---|---|
| Plural noun | `-s` | plural | -en, -i, -a, vowel change, zero plural | *mouses*, *childs*, *mans*, *sheeps*, *datums*, *criterions* |
| Third person singular present | `-s` | 3rd person singular agreement | — | *gos*, *haves* (*has*) |
| Past tense | `-ed` | past tense | strong/irregular verbs | *goed*, *runned*, *taked*, *thinked* |
| Past participle | `-ed` | past participle (adjective) | -en, vowel change | *taked*, *writed*, *goed*, *the choosed members* |
| Progressive, gerund, present participle | `-ing` | progressive, gerund, present participle | — | *runing*, *connecting the wires is easy* |
| Comparative | `-er` | comparative | *more* + adjective or adverb, irregular forms | *taller*, *gooder* (*better*), *bader* (*worse*), *beautifuler* (*more beautiful*), *larger*, *carefullyer* (*more carefully*), *goodlyer* (*better*, adverb) |
| Superlative | `-est` | superlative | *most* + adjective or adverb, irregular forms | *tallest*, *goodest* (*best*), *badest* (*worst*), *beautifulest* (*most beautiful*), *largest* |

Notes:
- Plural `-s` and third person `-s` have the same form. This is a known exception to P2. It is kept because the part of speech is always clear from context and from P1.
- `-er` is only the comparative. The agent noun uses `-or` (§3.2). By P1 a base is an adjective or a verb, never both, so the two suffixes never attach to the same base.
- Every adjective and every adverb takes `-er` / `-est`, also long ones (*beautifuler*, *carefullyest*). Do not use *more* / *most* for degree. Use *more* / *most* only for amount (*more water*, *most bolts*).
- *be* is the only irregular verb. Its forms are kept: *am, is, are, was, were, been*. (Open question Q1.)
- The passive and the perfect do not use *be* or *have* + the past participle. They use verb slots (§3.1.1). The `-ed` participle stays as an adjective: *the choosed members*.

#### 3.1.1 Verb slots

Eight suffixes replace auxiliary verbs. Each slot is used once at most. `-end`, `-can` and `-may` share slot 2, so a verb takes only one of them.

| Slot | Affix | Term | Replaces | Anchor word | Example |
|---|---|---|---|---|---|
| 1 | `-en` | passive voice | *be* + past participle | *chosen*, *taken* | *choosen* (is chosen) |
| 2 | `-end` | deontic mood | *shall*, *must* | *reverend* | *choosend* (shall choose) |
| 2 | `-can` | ability or permission | *can*, *be able to*, *may* (permission) | *cannot* | *choosecan* (can choose) |
| 2 | `-may` | possibility | *may*, *might* | — | *choosemay* (may choose) |
| 3 | `-'ve` | perfect aspect | *have* + past participle | *I've* | *choose've* (has chosen) |
| 4 | `-'ll` | future tense | *will* | *he'll* | *choose'll* (will choose) |
| 5 | `-ed` | past or hypothetical; stacks on slots 1–4 | *had*, *would*, *could*, *might* | *walked* | *choose'ved* (had chosen), *choose'lled* (would choose), *choosecaned* (could choose), *choosemayed* (might choose) |
| 6 | `-not` | negation | *do not*, *not* | *cannot* | *choosenot* (does not choose) |

| Form | Parts | Meaning |
|---|---|---|
| *choosened* | choose + en + ed | was chosen |
| *choosen've* | choose + en + 've | has been chosen |
| *choosen'll* | choose + en + 'll | will be chosen |
| *choose've'll* | choose + 've + 'll | will have chosen |
| *choose've'lled* | choose + 've + 'll + ed | would have chosen |
| *choosednot* | choose + ed + not | did not choose |
| *choosenend'llnot* | choose + en + end + 'll + not | will not have to be chosen |
| *choosecannot* | choose + can + not | cannot choose |
| *choosencaned* | choose + en + can + ed | could be chosen |
| *choosecan'll* | choose + can + 'll | will be able to choose |
| *choosecan'ved* | choose + can + 've + ed | could have chosen |
| *choosenmay* | choose + en + may | may be chosen |
| *choosemay'ved* | choose + may + 've + ed | might have chosen |

Notes:
- Stack in slot order: voice, then mood, aspect, tense, polarity.
- `-en` and `-end` drop their *e* after a base that ends in *e*: *choosen*, *choosend* (§4.2).
- `-'ve` and `-'ll` keep the apostrophe, so that letters do not run together: *call'll*, not *callll*. They are the only affixes with an apostrophe. `-ed` after `-'ve` drops its *e* (§4.2): *choose'ved*.
- `-not` is used, not `-n't`, because *choosen't* (does not choose) and *choosend* (shall choose) are almost the same in speech.
- A verb with a slot suffix takes no third person `-s`: *she choosenot* (she does not choose).
- The slot suffixes are inflectional. They do not count for U2 (§3.6).
- *shall* as a plain future (*I shall go*) uses `-'ll`, not `-end`.
- `-en` replaces every *be* + past participle, also when the participle names a state: *the fuse breakened* (the fuse was broken). English has the same ambiguity. The `-ed` participle stays only next to a noun, with no *be*: *the choosed members*, *Members choosed every Year*.
- *be* keeps its irregular forms (§3.1). They take `-not`: *isnot*, *arenot*. *be* also takes `-'ve` and `-'ll`: *be've* (has been), *be'll* (will be). For `-end` on *be*, see Q11.
- In an ellipsis, *do* carries the slots: *than the inspector do'ved* (than the inspector had), *but the inspector do'vednot* (but the inspector had not).
- An imperative takes `-not` too: *overtightizenot the bolts* (do not tighten the bolts too much).
- `-can` means ability or permission: *the operateor opencan the valve* (is able to, or is allowed to). `-can` + `-not` gives the English spelling *cannot*.
- `-may` means possibility only: *it rainmay tomorrow*. It does not mean permission (*you may go* → *you gocan*).
- `-ed` on `-'ll`, `-can` and `-may` is often hypothetical, not past: *choosemayed* (might choose) is a weaker possibility, not a past one.
- `-can` and `-may` start with a consonant, so §4.2 never changes them: *makecan*, *seemay*.
- `-can` can take `-'ll` and `-'ve`, which English *can* cannot: *choosecan'll* (will be able to choose). English uses *be able to* there.
- *choosecan'ved* is ambiguous: "could have chosen" (counterfactual) or "had been able to choose" (past fact). Context decides.
- `-able` and `-can` are different. `-able` makes an adjective: *seeable*. `-can` makes a verb: *these problems seencannot easyly*.
- `-end` and `-and` are different. `-end` makes a verb: *the operateor testend the valve* (shall test). `-and` makes a noun: *the testand* (the thing that is to be tested).

### 3.2 Derivation

| Meaning | Affix | Term | Replaces | Examples |
|---|---|---|---|---|
| Not X (adjective, noun) | `un-` | negation | in-, im-, il-, ir-, non-, dis-, a- | *unpossible*, *unlegal*, *unregular*, *unhonest*, *unmoral* |
| Reverse the action X (verb) | `de-` | reversative | un-, dis- (on verbs) | *detie*, *delock*, *deconnect* |
| Against X | `anti-` | oppositive | counter-, contra- | *antiact*, *antisay* |
| Again | `re-` | repetitive | — | *redo* |
| Person or thing that does X (the subject of X) | `-or` | agent noun (*nomen agentis*), A or S | -er, -ar, -ist, -ian, -ant, -ent, -ee (on verbs with no object) | *actor*, *teachor* (*teacher*), *begor* (*beggar*), *scienceor* (*scientist*), *assistor* (*assistant*), *makeor* (*maker*), *escapeor* (*escapee*), *attendor* (*attendee*) |
| Person or thing that is X-ed (the direct object of X; the action is done or in progress) | `-ee` | object noun, O | — | *employee*, *trainee*, *usee*, *givee* (the gift), *sendee* (the thing that is sent) |
| Person or thing that gets something from X, or that X is done for (the indirect object of X) | `-ary` | recipient noun | -ee (in this meaning) | *giveary*, *sendary* (*addressee*), *payary* (the person who is payed), *teachary* (*student*), *grantary* (*grantee*), *leaseary* (*lessee*), *beneficiary* |
| Person or thing that is to be X-ed (gerundive) | `-and` | gerundive (future passive participle) | -end, -andum, -endum, -anda, -enda | *operand*, *summand*, *divideand* (*dividend*), *addand* (*addendum*), *rememberand* (*memorandum*), *doands* (*agenda*), *beaffixand* |
| Person or thing that is about to X (active, prospective) | `-ure` | future active participle (prospective) | *would-be* X-or, X-or *to be* | *electure* (a person about to vote), *departure* (*departing*: *the departure passengers*), *launchure* (a rocket about to launch), *graduateure* |
| Can be X-ed | `-able` | passive potential adjective | -ible, -uble | *seeable*, *readable*, *solveable*, *flyable* (can be flown) |
| The act of X | `-ment` | action noun (*nomen actionis*) | -tion, -sion, -ation (as an act), -ance, -ence, -al, -age, -ice (act), -ery (practice), -ism (practice), -ing (as a noun) | *connectment* (*connection*), *payment*, *arrivement* (*arrival*), *createment* (*creation*), *observeableizement* |
| The thing that X makes | `-ion` | result noun | -tion, -sion, -ation, -ing, -ure (in this meaning) | *connection* (a connection that has been made), *collection*, *confession*, *paintion* (*painting*), *buildion* (*building*), *describeion* (*description*), *mixion* (*mixture*) |
| State or quality of being X | `-ness` | quality noun (*nomen qualitatis*) | -ity, -th, -ance, -ence, -cy, -hood, -ship, -tude, -ice (quality), -ery (state), -ism (quality or condition) | *unpossibleness*, *trueness*, *longness*, *safeness* |
| Relating to X | `-al` | relational adjective | -ic, -ical, -ar, -ary (in this meaning); demonym adjectives (-ese, -ish, -ian, -an, -i) | *scienceal*, *historyal*, *personal*, *Englandal* (*English*: *Englandal food*), *Chinal* (*Chinese*) |
| Full of / having X | `-ful` | possessive (proprietive) adjective | -ous, -y (on nouns) | *dangerful*, *fameful*, *rainful* |
| Without X | `-less` | privative | — | *powerless* |
| In an X way (adverb) | `-ly` | manner adverb | irregular adverbs | *goodly* (*well*), *fastly* (*fast*) |
| Bring into the state X, or come into it (verb) | `-ize` | factitive, inchoative; causative on verbs | -ify, -en, -ate | *widize*, *simpleize*, *activeize* |

Notes:
- `-ing` is only a verb form (§3.1). It is never a derived noun. Use `-ment` for the noun: *the connectment of the wires*, not *the connecting of the wires*. A gerund keeps its object without *of*: *connecting the wires is easy*.
- `-ment` starts with a consonant, so it never makes a vowel clash with a base that ends in *e*: *makement*, *replacement*.
- *able* + *ize* + *ment* makes "the process of making X-able": *observeableizement* (*observe* + *able* + *ize* + *ment*; 3 derivational affixes, the limit in U2).
- `-ize` has one meaning: a change into the state X. With an object, it means "make" (*widize the road*). With no object, it means "become" (*the road widizes*). This is like *open* in *open the door* and *the door opens*.
- `-ize` on a verb is causative: "make (the object) do X". The object is the one that does X: *deboardize the crew* (make the crew deboard), *fallize the tree* (*fell*), *riseize the flag* (*raise*), *lieize the cable on the floor* (*lay*). Use it only on verbs that have no object. If the verb has its own object, write a phrase: *tell the operator to examine the valve*. Do not put `-ize` on a word that already ends in `-ize`.
- A noun that ends in *-ics* uses the form without *-s* as the base for a suffix, like a plural place name (§3.4.2): *politics* → *political*, *economics* → *economical*. The noun alone keeps its *-s*. (A field of study uses `-ology`, §3.4.2.)
- `-ment` and `-ion` are different. *the connectment took one hour* (the act). *the connection is loose* (the thing that the act maked).
- `-ion` has no variant. The base never changes, so after *e* it stays *-ion*: *describeion*, *quoteion*, like *makeor* and *createive*. After *t* and *s* it gives the standard form: *connection*, *confession*.
- `-ion` and `-ee` are different. `-ion` is a thing that the action makes (*buildion*). `-ee` is a thing that the action is done to, and that existed before (*employee*).
- `-or`, `-ee` and `-ary` are chosen by grammatical relation, not by thematic role:
  - `-or` is the subject: A, or S on a verb with no object.
  - `-ee` is the direct object (O).
  - `-ary` is the indirect object: the one that gets something, or that the action is done for.
- If a verb has a thing and a person, `-ee` is always the thing and `-ary` is always the person. This is true also when standard English lets the person be the direct object (*pay the worker*, *teach the child*): *payee* is the money and *payary* is the worker; *teachee* is the subject that is taught and *teachary* is the student.
- A verb with no object has no `-ee` or `-ary` form. Traditional `-ee` words on these verbs use `-or`: *escapeor* (*escapee*), *attendor* (*attendee*), *retireor* (*retiree*).
- Traditional legal `-ee` words that name a recipient use `-ary`: *grantary* (*grantee*), *leaseary* (*lessee*), *mortgageary* (*mortgagee*), *licenseary* (*licensee*), *sendary* (*addressee*).
- The roles and their affixes:

  | Role | Any time | Not yet |
  |---|---|---|
  | Subject | `-or` (*testor*) | `-ure` (*testure*: about to test) |
  | Direct object | `-ee` (*testee*: is or was tested) | `-and` (*testand*: is to be tested) |
  | Indirect object | `-ary` (*giveary*) | — |

- `-and` and `-ure` are a pair. `-and` is passive and means "to be X-ed" (*an addand* is a number that is to be added). It does not say "must"; for that, use `-end` (§3.1.1). `-ure` is active and means "will soon X" (*an addure* is a person who will soon add). Neither one says that the action happens now. For that, use `-ing` (*the adding machine*).
- Traditional words in *-ure* that name a process use `-ment`: *failment* (*failure*), *closement* (*closure*). Words that name a result use `-ion`: *mixion* (*mixture*). *pressure*, *nature*, *culture* and *measure* are base words.

### 3.3 Affix order

When more than one affix attaches to a word, use this order:

```
prefix(es) + base + derivational suffix(es) + inflectional suffix(es)
```

Examples: *un* + *read* + *able* + *ness* → *unreadableness*; *re* + *connect* + *ed* → *reconnected*. On a verb, the inflectional suffixes follow the slot order in §3.1.1: *re* + *connect* + *en* + *'ll* → *reconnecten'll* (will be connected again).

### 3.4 Extended affixes

In standard English, many affixes work only with some words. For example, *-hood* goes on *child* but not on *teacher*, and *mis-* goes on *read* but not on *open*. In CE, every affix in §3.2 and §3.4 is **fully productive**. It attaches to every base of its input part of speech when the result makes sense. Each affix has one meaning. All the forms it replaces are removed.

#### 3.4.1 Prefixes

| Meaning | Affix | Term | Attaches to | Replaces | Examples |
|---|---|---|---|---|---|
| Wrongly, by mistake | `mis-` | — | verb | mal- (in this meaning) | *misfunction* (*malfunction*), *misread*, *miscount*, *misopen*, *misset* |
| On purpose, in bad faith | `mal-` | — | verb | mis- (in this meaning), *ab-* | *maltreat*, *malread* (read in a twisted way on purpose), *malbehave* (*misbehave*), *malgovern* (govern corruptly), *maluse* (*abuse*) |
| Too much | `over-` | excessive | verb, adj | hyper-, ultra-, super- (in this meaning) | *overheat*, *overtight*, *overactive* (*hyperactive*) |
| Too little | `under-` | deficient | verb, adj | hypo- | *undercook*, *underfill* |
| Below | `sub-` | subessive | noun | under- (in this meaning), infra- | *subground* (*underground*), *subline* (*underline*), *subgroup* |
| Above | `super-` | superessive | noun | over- (in this meaning), supra- | *superhead* (*overhead*), *superpass* (*overpass*) |
| Before (time) | `pre-` | anterior | noun, verb | fore-, ante- | *prewarn* (*forewarn*), *preroom* (*anteroom*), *prewash* |
| After (time) | `post-` | posterior | noun, verb | after- | *postshock* (*aftershock*), *postwash* |
| Between; each other (reciprocal) | `inter-` | interessive; reciprocal | noun, verb | *each other*, *one another* | *intercity*, *interconnect* (connect to each other), *interhelp* (help each other) |
| Inside one X | `intra-` | inessive | noun | endo-, *within* | *intracompany*, *intranet*, *intravein* (*intravenous*) |
| Done in reply to X, to stop or balance it | `counter-` | — | noun, verb | contra- | *counterattack*, *countermeasure*, *counterweight*, *counterspeak* (*contradict*) |
| Across (noun); through (verb) | `trans-` | perlative | noun, verb | dia-, per-, verb + *through* | *transsea*, *transcountry*; *transchew* (*chew through*), *transdrill*, *transpierce* |
| Together, jointly | `co-` | comitative | noun, verb | con-, com-, syn-, sym- (in new forms) | *cowork*, *cowriteor* |
| Former | `ex-` | — | noun | *former* | *exteachor*, *exhome* |
| Done to itself (the doer is also the receiver) | `self-` | reflexive | verb, noun | auto- (in this meaning) | *selfclean*, *selfteach*, *selfdefend*, *selfbiography* (*autobiography*) |
| Done without outside control, automatic | `auto-` | — | verb, noun | — | *autofocus*, *autolock*, *autopilot*, *automoveor* (*automobile*) |
| Do better than (verb); outside (noun) | `out-` | surpassive; exessive | verb, noun | ecto-, exo-, extra-, *outside* + noun | *outrun*, *outsee*, *outbuild*; *outhouse*, *outdoor*, *outbody*, *outLondon* |
| On, at the surface of | `a-` | superessive | noun | epi-, *on* + noun | *aboard*, *ashore*, *aground*, *atop*, *afloor* (*on the floor*), *awall*, *anoven* (*on the oven*) |
| Fake, false | `mock-` | — | noun | pseudo-, *fake* / *false* + noun | *mockgold*, *mockdoctor*, *mockscience* (*pseudoscience*) |
| Put in X | `en-` | illative | noun | em-, im- (in this meaning) | *encage*, *enbox*, *entomb*, *endanger*, *enprison* (*imprison*) |
| Give X, provide with X | `be-` | ornative | noun | en-, em- (in this meaning), *endow with* | *bepower* (*empower*), *betitle* (*entitle*), *bereason*, *bejewel*, *befriend* |
| Half, partly | `semi-` | — | noun, adj | hemi-, demi-, half- | *semisphere* (*hemisphere*), *semicircle* |
| One | `uni-` | numeral prefix | noun, verb (§3.8.3) | mono-, single- | *uniwheel*, *unirail* (*monorail*) |
| Two | `bi-` | numeral prefix | noun, verb (§3.8.3) | di-, twi-, double- | *biwheel*, *bilight* (*twilight*); not in chemical names (P6) |
| Three | `tri-` | numeral prefix | noun, verb (§3.8.3) | — | *triwheel* (*tricycle*), *triangle* |
| Many | `multi-` | — | noun, adj, verb (§3.8.3) | poly-, many- | *multicolor*, *multisided* (*polygonal*) |

Notes:
- `mis-` and `mal-` are different. *misread* means to read wrongly without knowing it; the reader acts in good faith. *malread* means to read in a twisted way on purpose. For poor skill, use the adverb: *reads badly*.
  - *"You are just malreading the scriptures!"* says that the other person twists the text on purpose. *"No, you are misreading it!"* says that the other person is honest but wrong.
  - More pairs: *misquote* / *malquote*, *misrepresent* / *malrepresent*, *misinform* / *malinform* (*disinform*).
  - *That's a malquoteion!* names the twisted quote (the result, `-ion`). *That's malquotement!* names the act (`-ment`).
- *under-* and *over-* now have one meaning each (amount). Place and rank use *sub-* and *super-*.
- *sub-* and *super-* have one meaning each: below and above. A rank is a place on a scale, so *subgroup* and *superpass* use the same meaning.
- *self-* and *auto-* are different. A *selfclean* oven cleans its own inside. An *autoclean* print head starts its cleaning cycle with no operator.
- *inter-* and *intra-* are different. *intercompany* is between companies. *intracompany* is inside one company.
- *inter-* on a verb makes it reciprocal: *the parts interconnect* means "the parts connect to each other". The verb has no object.
- *inter-*, *trans-* and *out-* have one meaning on a noun and a related meaning on a verb. The part of speech of the base (P1) always shows which meaning it is.
- *a-* makes an adverb or an adjective that comes after a verb: *lieize the cables afloor*, *the crew is aboard*. Do not put it before a noun: write *the cables afloor*, not *the afloor cables*. Before a vowel it is *an-* (§4.1).
- *a-* and *super-* are different. *awall* is on the wall and touches it. *superwall* is above the wall.
- *mock-* and *ex-* are different. *a mockdoctor* is not a real doctor. *an exdoctor* was a real doctor before.
- *anti-* and *counter-* are different. *anti-* means "opposed to X" (*antitheft*). *counter-* means "done in reply to X, to stop or balance it" (*counterattack*, *counterweight*).
- *en-* has no *em-* variant. *enprison* is easy to say (§4).
- *en-* and *be-* are different. *enbox the cake* puts the cake in a box. *bebox the cake* gives the cake a box.

#### 3.4.2 Suffixes

| Meaning | Affix | Term | Attaches to | Replaces | Examples |
|---|---|---|---|---|---|
| Small X | `-let` | diminutive | noun | -ette, -kin, -ie, -y, mini- | *booklet*, *kitchenlet* (*kitchenette*), *doglet* (*doggy*), *carlet* |
| Child of X | `-ling` | — | noun | *X's child*, *son* / *daughter of X*, irregular young-animal nouns | *duckling*, *catling* (*kitten*), *dogling* (*puppy*), *kingling* (*prince*), *bakeorling* (a baker's child) |
| Like X, in the manner of X | `-like` | similative | noun | -ish (on nouns), -ly (on nouns), -esque, -oid | *childlike* (*childish*), *friendlike* (*friendly*), *humanlike* (*humanoid*) |
| Somewhat X, almost X | `-ish` | approximative (attenuative) | adj, number | -y (on colors) | *reddish*, *coldish*, *tenish* |
| Place where X is done or made | `-ery` | place noun (*nomen loci*) | verb, noun | -ory, -arium, -ary (in this meaning), -age, room words | *bakery*, *washery* (*laundry*), *readery* (*library*), *cookery* (*kitchen*), *fishery* |
| Area ruled by X | `-dom` | realm | noun | -ric, -ate (in this meaning) | *kingdom*, *dukedom*, *sultandom* (*sultanate*), *companydom* |
| All X as a group | `-age` | collective | noun | -ry, -ery (in this meaning), -dom (in this meaning), -ware | *bagage* (*baggage*), *leafage* (*foliage*), *machineage* (*machinery*), *kitchenage* (*kitchenware*), *voteorage* (*electorate*) |
| Toward X | `-ward` | directional (allative) | noun | -wards | *homeward*, *skyward*, *doorward* |
| With respect to X | `-wise` | limitative | noun | — | *costwise*, *timewise* |
| Belief in X, or a movement for X | `-ism` | doctrine noun | noun, adj | — | *realism*, *peaceism* (*pacifism*), *peopleism* (the belief that the people should rule) |
| A system in which X rules | `-cracy` | — | noun | -archy, -ism (in this meaning) | *peoplecracy* (*democracy*), *kingcracy* (*monarchy*), *moneycracy* (*plutocracy*), *techniquecracy* (*technocracy*) |
| Study or science of X | `-ology` | — | noun | -ics, -logy, -nomy, -graphy | *earthology* (*geology*), *animalology* (*zoology*), *starology* (*astronomy*), *lifeology* (*biology*) |
| Person from place X | `-an` | demonym | proper noun | -ian, -ish, -ese, -i, -er, -ite, -man | *Englandan* (*Englishman*), *Chinaan* → *Chinan* (*Chinese*), *Japanan* → *Japanian* (*Japanese*), *Spainan* (*Spaniard*), *Iraqan* (*Iraqi*), *Londonan* (*Londoner*) |
| Language of place X | `-ese` | glottonym | proper noun | -ish, -ian, -an, -i, -ic | *Italyese* (*Italian*), *Englandese* (*English*), *Franceese* → *Francese* (*French*) |
| Number X in order (ordinal) | `-th` | ordinal | number | irregular ordinals | *oneth* (*first*), *twoth* (*second*), *threeth* (*third*), *fiveth*, *eighth*, *twentyth* |
| X times as many | `-fold` | multiplicative | number | -ple, -ble | *twofold* (*double*), *threefold* (*triple*) |
| Not damaged or affected by X | `-proof` | — | noun | -tight, -resistant | *waterproof*, *heatproof*, *shockproof*, *tamperproof*, *airproof* (*airtight*) |
| Good enough or safe enough for X | `-worthy` | — | noun | — | *airworthy*, *roadworthy*, *trustworthy*, *newsworthy* |
| Tool that measures X | `-meter` | instrument noun (*nomen instrumenti*) | noun | -ometer, gauge | *speedmeter* (*speedometer*), *heatmeter* (*thermometer*), *pressuremeter* (*pressure gauge*) |
| Causes X (a feeling or state) in others | `-some` | — | noun | -ing (in this meaning), -y (on nouns) | *fearsome*, *painsome*, *worrysome* (*worrying*), *scaresome* (*scary*), *troublesome* |
| Female X | `-ess` | feminine | noun | -ette, -trix, -ine, -woman, *female* + noun | *actoress* (*actress*), *heroess* (*heroine*), *Walesaness* (*Welshwoman*), *lioness*, *dogess* (*bitch*) |
| In the lasting state of X-ing | `-ent` | stative adjective | verb | -ant, -ent (adjective), -ing (in this meaning) | *dependent*, *undependent* (*independent*), *different*, *existent*, *pleasent* (*pleasant*), *ignorent* (*ignorant*) |
| Can X | `-ive` | active potential | verb | -ive and -ile on Latin roots | *flyive* (can fly), *explodeive* (*explosive*), *createive* (*creative*), *destroyive* (*destructive*), *moveive* (*mobile*), *attractive*, *protective* |
| Often X-s, tends to X | `-y` | habitual adjective | verb | -ative, -ful and -some (on verbs) | *talky* (*talkative*), *forgety* (*forgetful*), *quarrely* (*quarrelsome*), *leaky*, *clingy*, *pushy*, *jumpy* |

Notes:
- By P1, a place gives three different words: the person (`-an`), the adjective (`-al`) and the language (`-ese`). Example: *a Chinan* speaks *Chinaese* and eats *Chinal food*. The people as a group is the plural: *the Chinans* (*the Chinese*).
- `-an` and `-ese` overwrite names of peoples and languages too (P5). The name of this language is *Consistentized Englandese*. More examples: *Thailandan*, *Thailandese* (*Thai*); *Walesan*, *Walesese* (*Welsh*); *Netherlandan* (*Dutchman*), *Netherlandese* (*Dutch*); *Canadan* (*Canadian*); *Francean* (*Frenchman*).
- `-an` is also used for cities and regions: *Londonan*, *Texasan*.
- A people or language whose name is itself the base word does not take `-an` or `-ese`. Examples: *a Tamil*, *the Yorubas*, *Basque*, *Latin*, *Esperanto*.
- Place names themselves do not change (*England*, *Malaysia*). Only the derived forms change.
- A plural place name uses its singular form as the base for a suffix: *Netherlands* → *Netherlandan*, *Netherlandal*, *Netherlandese*; *Philippines* → *Philippinean*, *Philippinese*. The name alone keeps its *-s* (*the Netherlands*). *Wales* is not a plural, so it keeps its *s*: *Walesan*, *Walesese*.
- *-like* and *-ly* are different. *-like* makes an adjective from a noun. *-ly* makes an adverb from an adjective. So *friendly* (adjective, "like a friend") becomes *friendlike*.
- Five suffixes say what can happen, or is to happen, to a thing. They are different:
  - *flyive*: it can fly.
  - *flyable*: it can be flown.
  - *flyand*: it is to be flown.
  - *airworthy*: it is safe enough to fly.
  - *airproof*: air does not go through it.
- *-ful* and *-some* are different. *-ful* means the thing has X (*a fearful child* feels fear). *-some* means the thing causes X (*a fearsome dog* causes fear).
- *-meter* is only for tools that measure. Other tools use *-or* (see Q5).
- `-let` and `-ling` are different. *a doglet* is a small dog of any age. *a dogling* is the child of a dog, of any size.
- `-ling` means a child of any age. *a bakeorling* can be an adult. *catling* (*kitten*) is a cat's child. `-ling` does not say that the child is young; for that, write *a young dog*.
- `-ling` never means "lesser person". Traditional words with that meaning are not CE forms. Write a phrase: *weakling* → *weak person*, *underling* → *junior worker*.
- *-ish* and *-like* are different. *childish* (like a child) becomes *childlike*. *reddish* (somewhat red) does not change.
- `-ess` is the only gender affix. There is no male affix: a noun without `-ess` means a male, or a person or animal whose sex is unknown or mixed (as in Esperanto). *an actor* is a male actor or an actor of unknown sex. *the actors* can be a mixed group. Use `-ess` for each known female: *the engineoress*, not *the engineor*, when the engineer is a woman.
- `-ing`, `-ent` and `-able` are different. *the depending country* is depending now (an action in progress). *the dependent country* is in that state, and the state lasts. *the dependable country* can be depended on.
- `-able` and `-ive` are a pair. `-able` is passive: *a flyable plane* can be flown. `-ive` is active: *a flyive bird* can fly. A verb with no object has no passive, so it takes only `-ive`: *an arriveive train*.
- `-ing`, `-ive`, `-y` and `-ent` are different:
  - *a talking child* is talking now (`-ing`);
  - *a talkive child* can talk (`-ive`);
  - *a talky child* often talks (`-y`);
  - *a dependent country* is in that state, and the state lasts (`-ent`).
- `-y` goes only on verbs. On a noun, traditional `-y` uses `-ful` (*rainful*) or `-let` (*doglet*). A base that ends in *y* keeps both letters: *playy*, *cryy* (§4).
- `-ent` and `-ive` are different. `-ent` is a state that is true now: *a dependent country*. `-ive` is a power that may not be used: *an explodeive gas* can explode, but it has not exploded.
- `-dom` and `-age` are different. *kingdom* is the area that a king rules. *kingage* is all kings as a group.
- `-ism` is only a belief. Other traditional *-ism* words use other affixes:
  - a system of rule uses `-cracy`: *kingcracy* (*monarchy*);
  - a practice uses `-ment`: *vandalizement* (*vandalism*), *terrorizement* (*terrorism*);
  - a quality or condition uses `-ness`: *heroness* (*heroism*), *dwarfness* (*dwarfism*).
- `-ism` and `-cracy` are different. *peopleism* is the belief that the people should rule. *peoplecracy* is a system in which they rule.
- `-dom` and `-cracy` are different. *kingdom* is the land that a king rules. *kingcracy* is the system in which a king rules.
- One who holds a belief uses `-or` (§3.2): *realismor* (*realist*), *peaceismor* (*pacifist*).
- `-ent` is only an adjective. Nouns in *-ant* and *-ent* use `-or` (§3.2): *student* → *studyor*, *assistant* → *assistor*.
- `-ess` goes after the other derivational suffixes: *teach* + *or* + *ess* → *teachoress*; *king* + *ling* + *ess* → *kinglingess* (*princess*).

### 3.5 Removed affixes

These affixes have no CE form. Use a separate word.

| Affix | Meaning | CE form | Examples |
|---|---|---|---|
| -ly (on time nouns) | every X | *each* + noun | *daily* → *each day*, *weekly* → *each week* |

For female forms, use `-ess` (§3.4.2).

Reason for *-ly* on time nouns: *-ly* already means "in an X way" (§3.2). *daily* would break P2.

### 3.6 When to use affixes

CE is agglutinative: each affix has one meaning, the base never changes, and affixes stack in a fixed order (§3.3). Use this to make text shorter, but keep each word easy to take apart.

- **U1. Prefer the affixed form.** If an affixed word replaces a phrase of two or more words, use the affixed word.
- **U2. Limit the stack.** Use no more than three derivational affixes in one word. Inflectional affixes (§3.1) are not counted.
- **U3. Use a phrase when U2 is broken.** If the affixed form needs more than three derivational affixes, write a phrase.
- **U4. Prefer the verb for an action.** To name an action, prefer the verb to the `-ment` noun: *connect the wires*, not *do the connectment of the wires*. For a result, use `-ion` (*the connection*) or a concrete base word (*the joint*).

| Phrase | Affixed form | Derivational affixes | Use |
|---|---|---|---|
| *cannot be seen* | *unseeable* | 2 | affixed form (U1) |
| *the word that is to be given an affix* | *beaffixand* | 2 | affixed form (U1) |
| *cleans itself* | *selfcleans* | 1 (*-s* not counted) | affixed form (U1) |
| *the state of being unable to be connected again* | *unreconnectableness* | 4 | phrase (U3) |
| *cannot be connected again* | *unreconnectable* | 3 | affixed form (U1) |

### 3.7 Compounds

A compound is two or more words that name one thing. Join the words with hyphens: *blood-sugar*, *finance-minister*, *low-blood-sugar*.

- **C1. One base.** A hyphenated compound is one base. It takes affixes like any other base.
- **C2. Affixes go on the ends.** Attach prefixes to the first word and suffixes to the last word, with no hyphen. The affix applies to the whole compound.
- **C3. No inner affix at an end.** Because of C2, a word inside a compound cannot have its own affix at the start or end of the compound. If it needs one, do not make a compound. Write a phrase.
- **C4. Counting.** For U2, count only the affixes on the ends of the compound.

| Form | Parts | Meaning |
|---|---|---|
| *low-blood-sugarize* | [low-blood-sugar] + ize | make or become low in blood sugar |
| *low-blood-sugarizement* | [low-blood-sugar] + ize + ment | the process of becoming low in blood sugar |
| *exfinance-minister* | ex + [finance-minister] | former finance minister |
| *unconfidence-vote* | un + [confidence-vote] | something that is not a confidence vote (C2) |
| *unconfidence vote* | [unconfidence] + *vote* (two words) | a vote that expresses no confidence (C3) |

### 3.8 Biological affixes

CE imports common affixes from biology and medicine and makes them fully productive (§3.4). An affix is imported only when English has no native affix with the same meaning. Native affixes for "on", "outside", "through" and "fake" are in §3.4.1. Each one attaches to plain English bases (P4), not only to Greek and Latin roots. The affix keeps its scientific meaning, made general: *-vore* means "eats X" for any X, not only for animals.

#### 3.8.1 Prefixes

| Meaning | Affix | Source | Attaches to | Replaces | Examples |
|---|---|---|---|---|---|
| New | `neo-` | *neocortex* | noun | *new* + noun | *neooven*, *neoversion* |
| Old | `paleo-` | *paleontology* | noun | *old* + noun | *paleooven*, *paleoroad* |
| Large | `macro-` | *macrophage* | noun | *large* / *big* + noun | *macromakeery* (*large factory*), *macrodog*; not *mega-*, which is an SI prefix (P6) |
| Around | `peri-` | *pericardium* | noun | *around* + noun | *perihouse*, *perilake* |

#### 3.8.2 Suffixes

| Meaning | Affix | Source | Attaches to | Replaces | Examples |
|---|---|---|---|---|---|
| Shaped like X | `-form` | *cruciform* | noun | *X-shaped* | *heartform*, *starform*, *bellform* |
| Eats X | `-vore` | *herbivore* | noun | *-eater*, *-vorous* | *grassvore* (*herbivore*), *meatvore* (*carnivore*), *antvore* (*anteater*) |
| Loves X | `-phile` | *hydrophile* | noun | *X-lover*, *-philic* | *bookphile*, *catphile* |
| Fears X, avoids X | `-phobe` | *hydrophobe* | noun | *-phobic* | *waterphobe*, *crowdphobe* |
| Kills X | `-cide` | *herbicide* | noun | *X-killer*, *-icide* | *weedcide* (*herbicide*), *bugcide* (*insecticide*) |
| Produces X | `-gen` | *pathogen* | noun | *-genic*, *-ogen* | *diseasegen* (*pathogen*), *cancergen* (*carcinogen*) |
| Swelling, inflammation of X | `-itis` | *arthritis* | noun | *-itis* on Greek roots | *jointitis* (*arthritis*), *skinitis* (*dermatitis*) |
| Removal of X by cutting | `-ectomy` | *appendectomy* | noun | *-ectomy* on Greek roots | *tonsilectomy*, *wombectomy* (*hysterectomy*) |
| Tool to look at X | `-scope` | *microscope* | noun | *-oscope* | *starscope* (*telescope*), *insidescope* (*endoscope*) |

#### 3.8.3 Numeral prefixes on verbs

On a verb, a numeral prefix (§3.4.1) means "X times": *bimisfunction* (*malfunction twice*), *triknock* (*knock three times*), *multicheck* (*check many times*). *uni-* on a verb means "once".

Notes:
- A prefix keeps the capital letter of a proper noun: *periParis*, *outLondon*.
- `-form` and `-like` are different. `-form` is about shape (*a heartform cake*). `-like` is about manner (*childlike*).
- `-gen`, `-ful` and `-some` are different. *a diseasegen* produces disease. *a diseaseful town* has disease. *a fearsome dog* causes fear.
- `-phobe` and `anti-` are different. *a waterphobe* avoids water. *antiwater* is opposed to water.
- `-scope` and `-meter` are different. `-scope` shows X. `-meter` measures X.

## 4. Allowed allomorphs

**Rule: the base word never changes.** An affix never adds, removes or changes a letter of the base. All variation is in the affix.

An affix may have a variant only to prevent awkward spelling or pronunciation (P3). It is not enough that the traditional form is more familiar. So *un-* has no *im-*, *il-* or *ir-* variant: *unpossible* and *unlegal* are easy to say.

These are the only allowed variants. A rule always chooses the form.

### 4.1 Add a letter to the affix (break a consonant cluster, a vowel clash or a repeat)

| Affix | Variant | Condition | Examples |
|---|---|---|---|
| `-s` | `-es` | Base ends in *s, x, z, ch, sh* | *box* → *boxes*, *wish* → *wishes* |
| `a-` | `an-` | Base starts with a vowel, as with the article *a* / *an* | *anoven* (*on the oven*), *anice* (*on the ice*) |
| `-an` | `-ian` | Base ends in *an* (prevents *anan*) | *Japan* → *Japanian*, *Iran* → *Iranian*, *Pakistan* → *Pakistanian*, *Taiwan* → *Taiwanian* |

### 4.2 Remove the first letter of the affix (prevent an overlap)

When the base ends in the letter that the affix starts with, and keeping both would be awkward, the affix loses its first letter. Awkward means one of these:

- a doubled *e* or a doubled *a*
- a triple letter
- *tth*

| Affix | Variant | Condition | Examples |
|---|---|---|---|
| Any suffix that starts with *e* (`-ed`, `-en`, `-end`, `-er`, `-est`, `-ee`, `-ent`, `-ery`, `-ese`, `-ess`, `-ectomy`) | drop the *e* | Base ends in *e* | *bake* → *baked*; *choose* → *choosen*, *choosend*; *choose've* → *choose'ved*; *large* → *larger*, *largest*; *use* → *usee*; *bake* → *bakery*; *France* → *Francese*; *graduateure* → *graduateuress*; *please* → *pleasent* |
| Any suffix that starts with *a* (`-al`, `-an`, `-able`, `-and`, `-age`, `-ary`) | drop the *a* | Base ends in *a* | *China* → *Chinal*, *Chinan*; *Canada* → *Canadal*, *Canadan*; *Korea* → *Korean*; *formula* → *formulal*, *formulage* |
| `-or` | no variant | Base ends in *e* | *make* → *makeor*, *operate* → *operateor* (the base never changes; *e* + *o* is not a doubled *e*) |
| `-ure` | no variant | Base ends in *e* | *close* → *closeure*, *graduate* → *graduateure* |
| `-ize` | `-iz` | The next suffix starts with a vowel (*a, e, i, o, u*) | *lawize* → *lawizive*, *lawized*, *lawizing*, *lawizion*; *slaveize* → *slaveizor*; *looseize* → *unlooseizable*; but *slaveizement*, *lawizes* |
| Any affix | drop its first letter | The result would have three of the same letter | *full* + `-ly` → *fully*; *skill* + `-less` → *skilless* |
| `-th` | `-h` | Base ends in *t* | *eight* → *eighth* |

The `-ize` row is the only case where an affix changes because of the affix that follows it. `-ize` is an affix, not a base, so the base before it never changes. Before `-ed`, `-er` and `-est`, the result is the same as the rule for suffixes that start with *e*: *Consistentized*.

### 4.3 Results of the rule

Because the base never changes, these traditional spelling changes are not used:

| Traditional | CE | Rule removed |
|---|---|---|
| *tried*, *happiness* | *tryed*, *happyness* | *y* → *i* |
| *stopped*, *running* | *stoped*, *runing* | double the final consonant |
| *making*, *usable* | *makeing*, *useable* | drop the final *e* |
| *simply* | *simplely* | *-le* → *-ly* |
| *panicked* | *paniced* | *c* → *ck* |

Note: without doubling and *c* → *ck*, some spellings no longer show the sound of the base (*stoped* looks like it has a long *o*; *paniced* looks like it has an *s* sound). See Q3.

## 5. Collisions with existing words

Some regular CE forms have the same spelling as an existing English word with a different meaning. CE gives the word its CE meaning. List of known collisions:

| CE form | CE meaning | Existing English meaning |
|---|---|---|
| *seed* | past tense of *see* | part of a plant |
| *goodly* | in a good way | large in amount (archaic) |
| *departure* | a person or thing that is about to depart | the act of leaving (CE: *department*) |
| *department* | the act of departing | a part of an organization (CE: *partdom* or a dictionary base word, to be decided) |
| *pressure* | a person or thing that is about to press | force on a surface (if *pressure* is kept as a base word, the two meanings collide) |
| *ahead* | on the head | in front |
| *away* | on the way | at a distance |
| *haven*, *liken*, *waken*, *leaven* | is had, is liked, is woken, is left (`-en`, §3.1.1) | a safe place; compare; wake; yeast |
| *reverend*, *dividend*, *addend* | shall revere, shall divide, shall add (`-end`, §3.1.1) | a title of clergy; a share of profit (CE: *divideand*); a number to be added (CE: *addand*) |

(Open question Q2.)

### 5.1 False affixes

Some loan words start or end with letters that look like a CE affix, but the letters do not have the CE meaning. A reader must not take these words apart. If the word fails the test in P4, it is rebuilt. Otherwise it stays as one base word.

| Word | Looks like | CE meaning of the affix | Real meaning | CE |
|---|---|---|---|---|
| *ensure*, *insure* | `en-` + *sure* | put in X | make sure | *sureize* |
| *enslave* | `en-` + *slave* | put in X | make into a slave | *slaveize* (*slaveizor*: *enslaver*) |
| *legislative* | *legislate* + `-ive` | can X | relating to lawmaking | *lawizive* |
| *represent* | `re-` + *present* | again | act or speak for | one base word (*representor*) |
| *receive* | `re-` + *ceive* | again | get | one base word |
| *deliver* | `de-` + *liver* | reverse the action | bring | one base word |
| *devote* | `de-` + *vote* | reverse the action | give to a purpose | one base word |
| *detail* | `de-` + *tail* | reverse the action | small part | one base word |
| *defend* | `de-` + *fend* | reverse the action | guard | one base word (*defendment*) |
| *descend* | `de-` + *scend* | reverse the action | go down | one base word (*descendorage*) |
| *inhabit* | `in-` + *habit* | — (old "not"; *habit* is "custom") | dwell | *dwell* (*dwellor*: *inhabitant*) |
| *respective*, *respecting* | `re-` + *spect* (+ `-ive`) | again; can X | each one's own; on the subject of | *own*, *about* |
| *determine* | `de-` + *termine* | reverse the action | find out, fix | one base word, or a plain verb (*count*) |
| *exclude*, *exceed* | `ex-` + *clude*, `ex-` + *ceed* | former | shut out, go beyond | *leave out*, *outgo* |
| *subsequent* | `sub-` + *sequent* | below | following | *following* |
| *abridge* | `a-` + *bridge* | on the surface of | make short | *shortize* |
| *redress* | `re-` + *dress* | again | set right | *rightize* (*rightizement*) |
| *peaceable* | *peace* + `-able` | can be X-ed | in a peaceful way | *peaceful* |
| *legislature* | *legislate* + `-ure` | about to X | the body that makes law | *lawizorage* |

## 6. Dictionary

The CE dictionary lists base words, so that each base has one part of speech (P1) and the affix rules can choose the right suffix. CE does not limit text to dictionary words. A word that is not in the dictionary follows the same affix rules. Each entry has:

- the base word
- its one part of speech
- its one meaning
- one example sentence
- the traditional words it replaces (optional)

A base noun names one thing, not a group. A group of things uses `-age` (§3.4.2): *kin* (one relative) → *kinage*; *machine* → *machineage*; *voteor* → *voteorage*; *governor* → *governorage* (*government*).

The dictionary is to be done. Only base words go in the dictionary. Affixed forms are made by the rules in §3 and are not listed.

## 7. Open questions

- **Q1.** Do we regularize *be* (*I be, he bes, he beed*)?
- **Q2.** How do we handle collisions such as *seed* (see §5)? Options: accept the collision, add a hyphen (*see-ed*), or change the allomorph rule.
- **Q3.** Do we need a variant that keeps the sound of the base without changing its spelling? Example: a hyphen or a written mark between base and affix (*stop-ed*, *panic-ed*).
- **Q4.** (Closed.) `-ment` covered the act and its result. It now names only the act, and the result uses `-ion` (§3.2).
- **Q5.** (Closed.) `-or` covers persons (*teachor*) and tools (*computeor*). Both mean "the one that does X", which is one meaning. `-ee`, `-and` and `-ure` also cover persons and things. When the context does not show which one it is, use a compound: *wash-machine*.
- **Q6.** (Closed.) Plural place names made awkward language names (*Netherlandsese*). A plural place name now uses its singular form as the base (§3.4.2): *Netherlandese*, *Philippinese*.
- **Q7.** (Partly closed.) *will*, *shall*, *must*, *would*, *had*, *can*, *could*, *may* and *might* are now verb slots (§3.1.1). Still open: *should* (weak obligation).
- **Q8.** (Closed.) `-ee` covered three thematic roles: patient (*employee*), recipient (*payee*) and agent (*escapee*). `-ee` now means only the direct object. The recipient uses `-ary`, and the agent uses `-or` (§3.2).
- **Q9.** How does the progressive (*be* + `-ing`) fit the verb slots?
- **Q10.** Is a stack of four slot suffixes acceptable? Example: *passen've'lled* (would have been passed).
- **Q11.** *be* + `-end` gives *bend* by §4.2, and *bend* is an existing verb. Until this is decided, *shall be* stays before a noun or an adjective: *No Person shall be a Representor* (G.4).
- **Q12.** When two verbs share one set of auxiliaries, does each verb take the slots? Example: *shall not have attained … and been …* (G.4). Until this is decided, the text keeps the auxiliaries.

## Appendix A. Example translation

### A.1 Text

**Standard English**

> Before you begin, make sure the machine is completely disconnected from the power supply. It is impossible to safely inspect the electrical components while the unit is running. The technician who carried out the last inspection found that several bolts had been loosened and two of the seals were broken. These problems are not easily visible, so you should check each joint carefully. If a seal is unusable, replace it immediately. The replacement must be done by a qualified operator.

**Consistentized Englandese**

> Before you begin, sureize the machine deconnecten completely from the power supply. It is unpossible to safely inspect the electric components while the unit is runing. The techniqueor who carryed out the last inspectment finded that several bolts looseizen'ved and two of the seals breakened. These problems arenot easyly seeable, so you should check each joint carefully. If a seal is unuseable, replace it immediately. The replacement doenend by a qualifyed operateor.

### A.2 Changes

| Standard | CE | Rule |
|---|---|---|
| *disconnected* | *deconnected* | `de-` is the only "reverse the action" prefix (§3.2) |
| *impossible*, *unusable* | *unpossible*, *unuseable* | `un-` is the only "not" prefix (§3.2) |
| *technician*, *operator* | *techniqueor*, *operateor* | one agent suffix, `-or`; base unchanged (§3.2, §4.2) |
| *inspection*, *replacement* | *inspectment*, *replacement* | one process-noun suffix, `-ment` (§3.2) |
| *found* | *finded* | every past form uses `-ed` (§3.1) |
| *make sure* | *sureize* | one "make X" suffix, `-ize` (§3.2); as in G.1 |
| *had been loosened* | *looseizen'ved* | one "make X" suffix, `-ize` (§3.2), as `-iz` before a vowel (§4.2); then passive `-en`, perfect `-'ve`, past `-ed` (§3.1.1) |
| *is completely disconnected*, *were broken* | *deconnecten completely*, *breakened* | passive `-en` (§3.1.1) |
| *must be done* | *doenend* | passive `-en`, deontic `-end` (§3.1.1) |
| *are not* | *arenot* | `-not` on a form of *be* (§3.1.1) |
| *visible* | *seeable* | affix goes on the plain base (P4) |
| *easily*, *carried*, *qualified* | *easyly*, *carryed*, *qualifyed* | the base never changes: no *y* → *i* (§4) |
| *running* | *runing* | the base never changes: no doubled consonant (§4) |
| *electrical* | *electric* | *electric* is already the adjective; *-ical* is not a CE affix (§3.2) |

The auxiliary verbs become verb slots (§3.1.1): *must be done* becomes one word, *doenend*, and it stays passive. The rest of the sentence structure does not change: *carried out* stays a phrasal verb. Two forms stay open: the progressive *is runing* (Q9) and the modal *should* (Q7).

### A.3 One base, all forms

A learner who knows one base word and the affix rules can make every related form. Standard English uses roots from three sources (*see*, *view*, *vis-*) and two irregular forms. CE uses one base.

| Meaning | Standard English | CE |
|---|---|---|
| past | *saw* | *seed* (see Q2) |
| past participle (next to a noun) | *seen* | *seed* (see Q2) |
| is seen | *is seen* | *seen* |
| has seen | *has seen* | *see've* |
| will see | *will see* | *see'll* |
| shall see | *shall see* | *seend* |
| does not see | *does not see* | *seenot* |
| one who sees | *viewer* | *seeor* |
| can be seen | *visible* | *seeable* |
| cannot be seen | *invisible* | *unseeable* |
| state of being seeable | *visibility* | *seeableness* |
| see again | *review* | *resee* |

### A.4 Cost

To an ordinary English reader, CE forms such as *finded*, *easyly* and *techniqueor* look like mistakes, although they are easy to understand. CE accepts this cost in exchange for predictable word forms.

## Appendix B. Agglutination example

This example shows how CE uses stacked affixes (§3.6) to make text shorter.

### B.1 Text

**Standard English** (118 words)

> Each door that locks automatically in the testing room can only be opened again by a trained operator. Before each test, write the items that are to be tested on the board. If an item that is to be tested malfunctions, work together with a robotics specialist. Do not tighten the bolts too much. Bolts that are too tight cannot be removed. Mark cables that cannot be connected again with red tape. The newer small robots are faster, but they are also the most easily overheated. Move hot small robots toward the door. On the third day, examine each joint for cracks that cannot be seen. The machinery in the testing room is the responsibility of every operator.

**Consistentized Englandese** (77 words)

> Each autolock door in the testery is reopenable only by a trained operateor. Before each test, write the testands on the board. If a testand misfunctions, cowork with a robotologyor. Overtightizenot the bolts. Overtight bolts are unremoveable. Mark unreconnectable cables with red tape. The newer robotlets are faster, but they are also the overheatablest. Move hot robotlets doorward. On the threeth day, examine each joint for unseeable cracks. The testery's machineage is the responsibleness of each operateor.

The CE text has 35% fewer words and 22% fewer characters.

### B.2 Word breakdown

| CE word | Parts | Replaces |
|---|---|---|
| *reopenable* | re + open + able | *can be opened again* |
| *unreconnectable* | un + re + connect + able (3, the limit in U2) | *cannot be connected again* |
| *testand* | test + and | *item that is to be tested* |
| *robotologyor* | robot + ology + or | *robotics specialist* |
| *overtightizenot* | over + tight + ize + not | *do not tighten too much* |
| *unremoveable* | un + remove + able | *cannot be removed* |
| *overheatablest* | over + heat + able + est | *most easily overheated* |
| *robotlet* | robot + let | *small robot* |
| *doorward* | door + ward | *toward the door* |
| *testery* | test + ery | *testing room* |
| *machineage* | machine + age | *machinery* |
| *autolock* | auto + lock | *that locks automatically* |
| *cowork* | co + work | *work together* |
| *misfunctions* | mis + function + s | *malfunctions* |
| *unseeable* | un + see + able | *that cannot be seen* |
| *operateor* | operate + or | *operator* |
| *threeth* | three + th | *third* |

### B.3 Where the savings come from

Most of the savings come from relative clauses (*that cannot be …*, *that is to be …*). In CE, each of these becomes one affixed adjective or noun. *testand* replaces five words. *overheatablest* stacks two derivational affixes and one inflection in one word.

## Appendix C. News example

The country and the people in this text are not real.

### C.1 Text

**Standard English** (90 words)

> Velmora's Prime Minister Ana Reyes narrowly survived a no-confidence vote on Tuesday, two weeks before the general election. The opposition, led by former finance minister Tomas Bell, accused the government of corruption and of underfunding public hospitals. Reyes's popularity is now at its lowest level since 2022. Reyes promised an anti-corruption law and said that the coalition would not raise taxes. Thousands of protesters gathered outside parliament. Analysts said that the result is unforeseeable. Most of the electorate is still undecided, and both candidates are less trusted than their parties.

**Consistentized Englandese** (84 words)

> Velmora's Prime Minister Ana Reyes narrowly survived an unconfidence vote on Tuesday, two weeks before the general electment. The opposeors, under exfinance-minister Tomas Bell, accused the governorage of corruptment and of underfunding public hospitals. Reyes's popularness is now at its lowest since 2022. Reyes promised an anticorruptment law and sayed that the cogovernorage increase'llednot taxes. Thousands of protestors meeted outside the parliament. Analyzeors sayed that the result is unpreseeable. Most of the voteorage is still undecided, and both electands are untrustabler than their partys.

### C.2 Word breakdown

| CE | Parts | Standard | Note |
|---|---|---|---|
| *electand* | elect + and | *candidate* | one who is to be elected |
| *voteorage* | vote + or + age | *electorate* | all voters as a group |
| *electment*, *corruptment* | elect + ment, corrupt + ment | *election*, *corruption* | process noun |
| *underfunding* | under + fund + ing | *underfunding* | gerund with an object (*public hospitals*), so `-ing` stays |
| *cogovernorage* | co + govern + or + age | *coalition* | all who govern together, as a group (§6); 3 derivational affixes, the limit in U2 |
| *opposeors* | oppose + or + s | *the opposition* | |
| *unpreseeable* | un + pre + see + able | *unforeseeable* | 3 derivational affixes, the limit in U2 |
| *untrustabler* | un + trust + able + er | *less trusted* | |
| *exfinance-minister* | ex + [finance-minister] | *former finance minister* | compound (§3.7) |
| *governorage* | govern + or + age | *government* | all who govern, as a group (§6) |
| *partys*, *protestors* | party + s, protest + or + s | *parties*, *protesters* | |
| *sayed*, *meeted* | say + ed, meet + ed | *said*, *gathered* | regular past (§3.1) |
| *increase'llednot* | increase + 'll + ed + not | *would not raise* | `-'ll` + `-ed` is *would* (§3.1.1) |
| *Prime Minister*, *parliament* | — | no change | base words |

### C.3 Comment

The CE text has only 7% fewer words, and 3 of the 6 words come from one verb (*would not raise* → *increase'llednot*). News text uses many nouns and names, and few relative clauses (*that cannot be …*), so agglutination saves less than in technical text (Appendix B). The benefit here is transparency: a reader can take apart each CE word to find its meaning.

## Appendix D. Feature tour

This passage is written to use as many CE rules as possible in ordinary prose. The people in it are not real. It uses only §3.1–§3.7. Appendix E translates it again with the biological affixes (§3.8).

### D.1 Text

**Standard English** (359 words)

> Last week, a retired engineer and her former student visited a small bakery in London. The engineer, a Japanese woman, speaks fluent English and Dutch. She had arrived after a long flight across the ocean, and her student came by bicycle. The baker, a cheerful Welshwoman, was forewarned of their arrival. She told them that her oven had malfunctioned twice that month, that its thermometer was unreliable, and that the noise it made was frightening.
>
> The engineer examined the machinery more carefully than the government inspector had. The wires under the floor were interconnected, and the overhead lamp was dangerous. "Disconnect everything and unlock the cover," she told the employees, "and do not tighten the screws too much." She found that the eighth fuse was broken and that mice had chewed through the insulation. A skilled electrician would have seen it at once, but the inspector had not.
>
> They worked together to raise the oven, lay new cables on the floor and rebuild the heater. The student, a biologist, contradicted the baker: the damage was worse than her description. His repair, however, was better than his teacher's. The new oven cleans itself, starts automatically and bakes double the bread. It is waterproof and airtight, and it is more beautiful than the old one, although slightly noisier.
>
> The baker's daughter, who is about to graduate in pharmacy, was impressed but doubtful. "It is impossible to trust a machine fully," she said. The engineer smiled. "It is the safest oven in the kingdom, and the most reliable machine that I have ever built." She refused payment. In return, the baker gave them a basket of warm loaves and a reddish, heart-shaped cake. The children in the shop behaved childishly and outran each other toward the door.
>
> Since then, the ingredients that must be ordered daily are written on a whiteboard in the kitchen: 25 kilograms of flour, sodium bicarbonate and Chinese tea. The engineer, now a co-owner, has never been happier, and the new oven has empowered the baker. "Money-wise, a small bakery is better than a large factory," she says. Her husband, a former firefighter, agrees and does the deliveries.

**Consistentized Englandese** (315 words)

> Last week, a retired engineoress and her exstudent visited a bakerylet in London. The engineoress, a Japanianess, speaks fluent Englandese and Netherlandese. She arrive'ved after a long transocean flight, and her student comed by biwheel. The bakeoress, a cheerful Walesaness, prewarnened of their arrivement. She telled them that her oven misfunction'ved twice that month, that its heatmeter was unrelyable, and that the noise it maked was frightsome.
>
> The engineoress examined the machineage carefullyer than the governorage's inspector do'ved. The subfloor wires interconnectened, and the superhead lamp was dangerful. "Deconnect everything and delock the cover," she telled the employees, "and overtightizenot the screws." She finded that the eighth fuse breakened and that mouses transchew'ved the insulatement. A skilled electricityor see've'lled it at once, but the inspector do'vednot.
>
> They coworked to riseize the oven, lieize new cables afloor and rebuild the heator. The student, a lifeologyor, counterspeaked the bakeoress: the damage was bader than her describeion. His repair, however, was gooder than his teachoress's. The new oven selfcleans, autostarts and bakes twofold the bread. It is waterproof and airproof, and it is beautifuler than the old one, although slightly noisefuler.
>
> The bakeorlingess, a pharmacy graduateuress, impressened but was doubtful. "It is unpossible to trust a machine fully," she sayed. The engineoress smiled. "It is the safest oven in the kingdom, and the relyablest machine that I ever build've." She refused payment. In return, the bakeoress gived them a basket of warm loafs and a reddish, heart-shaped cake. The childs in the shop behaved childlikely and outruned each other doorward.
>
> Since then, the orderands of each day writen on a whiteboard in the cookery: 25 kilograms of flour, sodium bicarbonate and Chinal tea. The engineoress, now a coownoress, never be've happyer, and the new oven bepower've the bakeoress. "Moneywise, a bakerylet is gooder than a large makeery," she says. Her husband, an exfire-fightor, agrees and dos the deliverments.

### D.2 Features shown

| Feature | Standard → CE | Rule |
|---|---|---|
| Regular plural | *mice*, *children*, *loaves* → *mouses*, *childs*, *loafs* | `-s` (§3.1) |
| Regular past | *came*, *told*, *made*, *found*, *gave* → *comed*, *telled*, *maked*, *finded*, *gived* | `-ed` (§3.1) |
| Regular *do*, *say* | *does*, *said* → *dos*, *sayed* | `-s`, `-ed`; only *be* stays irregular (§3.1) |
| Verb slots | *had arrived*, *had malfunctioned*, *had chewed through*, *have ever built*, *has empowered* → *arrive'ved*, *misfunction'ved*, *transchew'ved*, *ever build've*, *bepower've* | perfect `-'ve`, past `-ed` (§3.1.1) |
| Passive | *was forewarned*, *were interconnected*, *was broken*, *was impressed*, *are written* → *prewarnened*, *interconnectened*, *breakened*, *impressened*, *writen* | `-en` (§3.1.1) |
| Stacked slots | *would have seen* → *see've'lled* | `-'ve` + `-'ll` + `-ed` (§3.1.1) |
| Slots on *be* and *do* | *has never been*, *had* (ellipsis), *had not*, *do not tighten* → *never be've*, *do'ved*, *do'vednot*, *overtightizenot* | §3.1.1 |
| Regular comparison | *worse*, *better* → *bader*, *gooder* | `-er` (§3.1) |
| Comparison of long words | *more carefully*, *more beautiful*, *most reliable* → *carefullyer*, *beautifuler*, *relyablest* | no *more* / *most* for degree (§3.1) |
| Not X | *impossible*, *unreliable* → *unpossible*, *unrelyable* | `un-` (§3.2) |
| Reverse the action | *disconnect*, *unlock* → *deconnect*, *delock* | `de-` (§3.2) |
| Again | *rebuild* | `re-` (§3.2) |
| Agent noun | *engineer*, *baker*, *teacher*, *heater*, *biologist*, *electrician* → *engineor*, *bakeor*, *teachor*, *heator*, *lifeologyor*, *electricityor* | `-or` (§3.2) |
| Patient noun | *employees* | `-ee`, already regular (§3.2) |
| Gerundive | *ingredients that must be ordered* → *orderands* (things that are to be ordered; *must* is left to context) | `-and` (§3.2) |
| Prospective | *who is about to graduate* → *graduateure* | `-ure` (§3.2) |
| Can be X-ed | *reliable* → *relyable* | `-able`, base unchanged (§3.2, §4) |
| Action noun | *arrival*, *insulation*, *deliveries* → *arrivement*, *insulatement*, *deliverments* | `-ment` (§3.2) |
| Result noun | *description* → *describeion* | `-ion` (§3.2) |
| Having X | *dangerous*, *noisy* → *dangerful*, *noiseful* | `-ful` (§3.2) |
| Manner adverb | *childishly* → *childlikely* | `-like` + `-ly` (§3.2, §3.4.2) |
| Make X, causative | *tighten too much*, *raise*, *lay* → *overtightize*/*overtightizenot*, *riseize*, *lieize* | `-ize` (§3.2) |
| Prefixes | *malfunctioned*, *under the floor*, *overhead*, *forewarned*, *contradicted*, *across the ocean*, *worked together*, *former*, *cleans itself*, *starts automatically*, *outran*, *empowered*, *bicycle*, *co-owner* → *misfunctioned*, *subfloor*, *superhead*, *prewarned*, *counterspeaked*, *transocean*, *coworked*, *ex-*, *selfcleans*, *autostarts*, *outruned*, *bepowered*, *biwheel*, *coownor* | §3.4.1 |
| On, through | *on the floor*, *chewed through* → *afloor*, *transchewed* | `a-`; `trans-` on a verb (§3.4.1) |
| Suffixes | *small bakery*, *machinery*, *kitchen*, *factory*, *toward the door*, *money-wise*, *thermometer*, *airtight*, *double*, *frightening* → *bakerylet*, *machineage*, *cookery*, *makeery*, *doorward*, *moneywise*, *heatmeter*, *airproof*, *twofold*, *frightsome* | §3.4.2 |
| Child of X | *the baker's daughter* → *the bakeorlingess* | `-or` + `-ling` + `-ess`: 3 derivational affixes, the limit in U2 (§3.4.2) |
| Unchanged regular forms | *reddish*, *waterproof*, *interconnected*, *kingdom*, *doubtful* | already CE |
| Person, adjective, language | *Japanese woman*, *Welshwoman*, *English*, *Dutch*, *Chinese tea* → *Japanianess*, *Walesaness*, *Englandese*, *Netherlandese*, *Chinal tea* | `-an`, `-ese`, `-al` (§3.4.2) |
| Female | *engineer*, *baker*, *teacher*, *co-owner*, *graduate* (all women) → *engineoress*, *bakeoress*, *teachoress*, *coownoress*, *graduateuress* | `-ess`; the unmarked noun is male (§3.4.2) |
| Every X | *daily* → *of each day* | removed affix (§3.5) |
| Compound | *former firefighter* → *exfire-fightor* | affixes on the ends (§3.7) |
| Allomorphs | *Japanian* (`-ian` after *an*), *Chinal* (drop *a*), *retired*, *arrive'ved*, *writen* (drop *e*), *fully* (no triple *l*), *eighth* (`-h` after *t*) | §4 |
| Base never changes | *happier* → *happyer* (no *y* → *i*); *outran* → *outruned* (no doubled *n*) | §4.3 |
| Exempt names | *25 kilograms*, *sodium bicarbonate*, *London* | P6, place names |

### D.3 Comment

The CE text has 12% fewer words. Before the verb slots (§3.1.1) it had 8% fewer (330 words). The savings come from phrases that become one word (*orderands*, *graduateure*, *transocean*, *overtightizenot*, *doorward*, *see've'lled*). The cost is in narrative verbs: almost every sentence has a regularized past form or a slot suffix. *comed*, *dos* and the stacked slots (*see've'lled*, *do'vednot*) are the CE forms that look strangest to a native reader.

*impressened but was doubtful* splits one *was* into two: `-en` needs a participle, and *doubtful* is an adjective, so it keeps *was*.

Not shown: `-ness`, `anti-`, `intra-`, `semi-`, `uni-`, `tri-`, `multi-`, `post-`, `under-`, `-less`, `-ism`, `-ology` alone, `-worthy`, `-wise` on a non-money noun, `-th` on a regular number, and the `-es` plural.

## Appendix E. Feature tour with biological affixes

This is the passage from Appendix D, translated again with the biological affixes (§3.8). It also uses two existing affixes that Appendix D did not use.

### E.1 Text

**Consistentized Englandese with §3.8** (305 words)

> Last week, a retired engineoress and her exstudent visited a bakerylet in London. The engineoress, a Japanianess, speaks fluent Englandese and Netherlandese. She arrive'ved after a long transocean flight, and her student comed by biwheel. The bakeoress, a cheerful Walesaness, prewarnened of their arrivement. She telled them that her oven bimisfunction'ved that month, that its heatmeter was unrelyable, and that the noise it maked was frightsome.
>
> The engineoress examined the machineage carefullyer than the governorage's inspector do'ved. The subfloor wires interconnectened, and the superhead lamp was dangerful. "Deconnect everything and delock the cover," she telled the employees, "and overtightizenot the screws." She finded that the eighth fuse breakened and that mouses transchew'ved the insulatement. A skilled electricityor see've'lled it at once, but the inspector do'vednot.
>
> They coworked to riseize the oven, lieize new cables afloor and rebuild the heator. The student, a lifeologyor, counterspeaked the bakeoress: the damage was bader than her describeion. His repair, however, was gooder than his teachoress's. The neooven selfcleans, autostarts and bakes twofold the bread. It is waterproof and airproof, and it is beautifuler than the old one, although slightly noisefuler.
>
> The bakeorlingess, a pharmacy graduateuress, impressened but was doubtful. "It is unpossible to trust a machine fully," she sayed. The engineoress smiled. "It is the safest oven in the kingdom, and the relyablest machine that I ever build've." She refused payment. In return, the bakeoress gived them a basket of warm loafs and a reddish, heartform cake. The intrashop childs behaved childlikely and interoutruned doorward.
>
> Since then, the orderands of each day writen on an intracookery whiteboard: 25 kilograms of flour, sodium bicarbonate and Chinal tea. The engineoress, now a coownoress, never be've happyer, and the neooven bepower've the bakeoress. "Moneywise, a bakerylet is gooder than a macromakeery," she says. Her husband, an exfire-fightor, agrees and dos the deliverments.

### E.2 Changes from Appendix D

| Appendix D | Appendix E | Affix |
|---|---|---|
| *misfunction'ved twice* | *bimisfunction'ved* | numeral prefix on a verb (§3.8.3) |
| *The new oven*, *the new oven* | *The neooven*, *the neooven* | `neo-` (§3.8.1) |
| *heart-shaped* | *heartform* | `-form` (§3.8.2) |
| *a large makeery* | *a macromakeery* | `macro-` (§3.8.1) |
| *The childs in the shop*, *a whiteboard in the cookery* | *The intrashop childs*, *an intracookery whiteboard* | `intra-` (§3.4.1), existing, not used in Appendix D |
| *outruned each other* | *interoutruned* | reciprocal `inter-` (§3.4.1), existing, not used in Appendix D |

### E.3 Size

| Version | Words | Characters |
|---|---|---|
| Standard English (D.1) | 359 | 2158 |
| CE (D.1) | 315 | 2099 |
| CE with §3.8 (E.1) | 305 | 2080 |

### E.4 Comment

The §3.8 version has 3% fewer words and 1% fewer characters than Appendix D, and 15% fewer words than the standard English text.

The biological affixes save less than expected on this passage. Most of them name things that a story about an oven does not talk about: eating, killing, disease, fear and love. The savings come from `neo-`, `macro-` and numeral prefixes on verbs. Of the 10 words saved, 4 come from §3.8 and 6 come from the existing `intra-` and reciprocal `inter-`. The native prefixes that replaced imported ones (`a-`, `trans-` on verbs) are in §3.4.1, so Appendix D uses them too: *afloor*, *transchewed*.

Not used: `paleo-`, `peri-`, `-vore`, `-phile`, `-phobe`, `-cide`, `-gen`, `-itis`, `-ectomy`, `-scope`. `paleo-` makes the text longer here: *the paleooven* is longer than *the old one*.

## Appendix F. Baseline: Universal Declaration of Human Rights

These translations use only the rules above. They are a baseline: when a new affix is added, translate these texts again and compare. Each size table also shows the CE text before the verb slots (§3.1.1).

### F.1 Article 1

#### F.1.1 Text

**Standard English** (30 words)

> All human beings are born free and equal in dignity and rights. They are endowed with reason and conscience and should act towards one another in a spirit of brotherhood.

**Consistentized Englandese** (23 words)

> All human bements bearen free and equal in worthyness and rights. They bereasonen and beconsciencen and should interact in a spirit of brotherness.

#### F.1.2 Word breakdown

| CE | Parts | Standard | Note |
|---|---|---|---|
| *bements* | be + ment + s | *beings* | `-ing` is never a noun (§3.2), so the noun uses `-ment` |
| *bearen* | bear + en | *are born* | passive (§3.1.1); collides with the noun *bear* (P1) |
| *worthyness* | worthy + ness | *dignity* | `-ness` replaces `-ity` (§3.2); *dignity* has no plain English base (P4) |
| *bereasonen*, *beconsciencen* | be + reason + en, be + conscience + en | *are endowed with reason and conscience* | `be-` means "give X" (§3.4.1); passive (§3.1.1); `-en` drops its *e* after *conscience* (§4.2) |
| *interact* | inter + act | *act towards one another* | reciprocal `inter-` (§3.4.1) |
| *brotherness* | brother + ness | *brotherhood* | `-ness` replaces `-hood` (§3.2) |
| *should* | — | no change | modal (Q7) |

#### F.1.3 Size

| Version | Words | Characters |
|---|---|---|
| Standard English | 30 | 170 |
| CE before §3.1.1 | 25 | 155 |
| CE | 23 | 147 |

#### F.1.4 Gaps

- *bements* is a legal form, but it is strange. CE has no affix for "a thing that is X" or "a thing that exists".
- *bearen* breaks P1: *bear* is also an animal. This is a dictionary problem, not an affix problem.
- *dignity* has no plain base, so *worthyness* changes the meaning a little.
- *brother* has no `-ess`, so by §3.4.2 it means a male or a person of unknown sex. *brotherness* therefore includes sisters. *sister* becomes *brotheress*.
- The verb slots save 2 words: *are born* and *are endowed* each become one word. *should* stays (Q7).

### F.2 Article 2

#### F.2.1 Text

**Standard English** (78 words)

> Everyone is entitled to all the rights and freedoms set forth in this Declaration, without distinction of any kind, such as race, colour, sex, language, religion, political or other opinion, national or social origin, property, birth or other status. Furthermore, no distinction shall be made on the basis of the political, jurisdictional or international status of the country or territory to which a person belongs, whether it be independent, trust, non-self-governing or under any other limitation of sovereignty.

**Consistentized Englandese** (75 words)

> Everyone betitlen to all the rights and freenesses setted forth in this Declareion, without distinguishment of any kind, such as race, colour, sex, language, religion, political or other opinion, national or societyal origin, ownee, bearment or other status. Furthermore, no distinguishment makenend on the basis of the political, jurisdictional or international status of the country or territory to which a person belongs, whether it be undependent, trust, unselfgoverning or under any other limitment of sovereignness.

#### F.2.2 Word breakdown

| CE | Parts | Standard | Note |
|---|---|---|---|
| *betitlen* | be + title + en | *is entitled* | `be-` means "give X"; `en-` is only "put in X" (§3.4.1); passive (§3.1.1) |
| *freenesses* | free + ness + es | *freedoms* | a state, so `-ness`; `-dom` is only a realm (§3.4.2) |
| *setted* | set + ed | *set* | zero past participle replaced (§3.1); next to a noun, so `-ed` (§3.1.1) |
| *distinguishment* | distinguish + ment | *distinction* | `-ment` replaces `-tion` (§3.2) |
| *political* | politic + al | no change | *-ics* noun drops *-s* before a suffix (§3.2) |
| *Declareion* | declare + ion | *Declaration* | the document that declaring makes, so `-ion` (§3.2); legal terms are not exempt (P6) |
| *societyal* | society + al | *social* | affix goes on the plain base (P4) |
| *national*, *international* | nation + al, inter + nation + al | no change | already CE |
| *ownee* | own + ee | *property* | the thing that is owned (§3.2) |
| *bearment* | bear + ment | *birth* | action noun; matches *bearen* in Article 1 |
| *makenend* | make + en + end | *shall be made* | passive, deontic (§3.1.1); `-en` drops its *e* (§4.2) |
| *jurisdictional* | jurisdiction + al | no change | already CE; *jurisdiction* has no plain English base |
| *undependent* | un + depend + ent | *independent* | `un-` replaces `in-` (§3.2); stative `-ent` (§3.4.2) |
| *unselfgoverning* | un + self + govern + ing | *non-self-governing* | `un-` replaces `non-` (§3.2); 2 derivational affixes |
| *limitment* | limit + ment | *limitation* | §3.2 |
| *sovereignness* | sovereign + ness | *sovereignty* | `-ness` replaces `-ty` (§3.2) |
| *trust*, *territory* | — | no change | base words |

#### F.2.3 Size

| Version | Words | Characters |
|---|---|---|
| Standard English | 78 | 516 |
| CE before §3.1.1 | 78 | 531 |
| CE | 75 | 521 |

#### F.2.4 Gaps

- (Closed.) CE had no affix for "in the state of X" (*independent*), so this translation used *undepending*. Stative `-ent` (§3.4.2) now fills this gap: *undependent*.
- (Partly closed.) **Few savings.** Before the verb slots, the text had the same number of words and 3% more characters. The slots save 3 words (*is entitled*, *shall be made*), and the text now has 1% more characters. Legal text uses many abstract nouns, and `-ment` and `-ness` are often longer than `-tion` and `-ty`. It has few relative clauses that affixes can replace.
- *whether it be* is a subjunctive *be*, not an auxiliary, so it stays.
- (Closed.) Legal terms were exempt under P6, so *Declaration* and *property* were treated differently. P6 no longer exempts legal terms: *Declareion*, *ownee*.
- (Closed.) *politicsal* was awkward. A noun that ends in *-ics* now drops its *-s* before a suffix (§3.2): *political*.

### F.3 Article 3

#### F.3.1 Text

**Standard English** (11 words)

> Everyone has the right to life, liberty and security of person.

**Consistentized Englandese** (11 words)

> Everyone haves the right to life, freeness and secureness of person.

#### F.3.2 Word breakdown

| CE | Parts | Standard | Note |
|---|---|---|---|
| *haves* | have + s | *has* | regular third person (§3.1) |
| *freeness* | free + ness | *liberty* | affix goes on the plain base (P4); `-ness` replaces `-ty` (§3.2) |
| *secureness* | secure + ness | *security* | `-ness` replaces `-ity` (§3.2) |

#### F.3.3 Size

| Version | Words | Characters |
|---|---|---|
| Standard English | 11 | 63 |
| CE | 11 | 68 |

#### F.3.4 Gaps

- *liberty* and *freedom* (Article 2) both become *freeness*. By P4 they have the same plain base, so CE loses the difference between them. In this text the two words mean the same thing, so nothing is lost here.
- The text has no phrase that an affix can replace, so CE cannot make it shorter. `-ness` is longer than `-ty` and `-ity`.
- *haves* is the main verb, not an auxiliary, so the verb slots (§3.1.1) change nothing.

### F.4 Article 4

#### F.4.1 Text

**Standard English** (21 words)

> No one shall be held in slavery or servitude; slavery and the slave trade shall be prohibited in all their forms.

**Consistentized Englandese** (16 words)

> No one holdenend in slaveness or serveorness; slaveizement and the slave-trade prohibitenend in all their forms.

#### F.4.2 Word breakdown

| CE | Parts | Standard | Note |
|---|---|---|---|
| *holdenend* | hold + en + end | *shall be held* | passive, deontic (§3.1.1) |
| *slaveness* | slave + ness | *slavery* (the state) | *held in slavery* is a state, so `-ness` (§3.2); `-ery` is only a place (§3.4.2) |
| *slaveizement* | slave + ize + ment | *slavery* (the practice) | the act of making people slaves (§3.2); 2 derivational affixes |
| *serveorness* | serve + or + ness | *servitude* | the state of being one who serves; 2 derivational affixes |
| *slave-trade* | [slave-trade] | *slave trade* | compound (§3.7) |
| *prohibitenend* | prohibit + en + end | *shall be prohibited* | passive, deontic (§3.1.1) |

#### F.4.3 Size

| Version | Words | Characters |
|---|---|---|
| Standard English | 21 | 113 |
| CE before §3.1.1 | 20 | 124 |
| CE | 16 | 112 |

#### F.4.4 Gaps

- (Closed.) *slavery* has two meanings in this text: a state (*held in slavery*) and a practice (*slavery … shall be prohibited*). Standard `-ery` also names both, but CE `-ery` is only a place. The `-ness` row now replaces `-ery` (state) and `-tude`, and the `-ment` row replaces `-ery` (practice).
- *serveorness* needs two affixes, because the state belongs to the person (*serveor*), not to the verb (*serve*).
- The verb slots save 4 words, and the CE text is now shorter than the standard text in characters too. *shall be* + participle is the most common verb form in legal text, and each one becomes one word.

### F.5 Article 5

#### F.5.1 Text

**Standard English** (16 words)

> No one shall be subjected to torture or to cruel, inhuman or degrading treatment or punishment.

**Consistentized Englandese** (14 words)

> No one subjectenend to torture or to cruel, unhuman or degrading treatment or punishment.

#### F.5.2 Word breakdown

| CE | Parts | Standard | Note |
|---|---|---|---|
| *unhuman* | un + human | *inhuman* | `un-` replaces `in-` (§3.2) |
| *subjectenend* | subject + en + end | *shall be subjected* | passive, deontic (§3.1.1) |
| *treatment*, *punishment* | treat + ment, punish + ment | no change | already CE: the act (§3.2) |
| *degrading* | degrade + ing | no change | present participle (§3.1): the treatment degrades when it happens |
| *torture* | — | no change | base word, like *pressure* and *nature* (§3.2); it has no plain English base |

#### F.5.3 Size

| Version | Words | Characters |
|---|---|---|
| Standard English | 16 | 95 |
| CE before §3.1.1 | 16 | 95 |
| CE | 14 | 89 |

#### F.5.4 Gaps

- Only two words change. *treatment* and *punishment* already use the act suffix `-ment`.
- *degrading* could also take `-ive` (it can degrade) or `-some` (it causes shame). `-ing` is the closest: the treatment degrades the person each time it happens.

## Appendix G. Baseline: Constitution of the United States

These translations use only the rules above. The capital letters of the original are kept. As in Appendix F, each size table also shows the CE text before the verb slots (§3.1.1).

### G.1 Preamble

#### G.1.1 Text

**Standard English** (52 words)

> We the People of the United States, in Order to form a more perfect Union, establish Justice, insure domestic Tranquility, provide for the common defence, promote the general Welfare, and secure the Blessings of Liberty to ourselves and our Posterity, do ordain and establish this Constitution for the United States of America.

**Consistentized Englandese** (51 words)

> We the People of the United States, in Order to form a perfecter Uniteion, establish Justness, sureize homeal Tranquilness, provide for the common defendment, promote the general Welfare, and secure the Blessions of Freeness to ourselves and our Descendorage, do ordain and establish this Constituteion for the United States of America.

#### G.1.2 Word breakdown

| CE | Parts | Standard | Note |
|---|---|---|---|
| *perfecter* | perfect + er | *more perfect* | no *more* for degree (§3.1) |
| *Uniteion* | unite + ion | *Union* | the thing that uniting makes, so `-ion` (§3.2); plain base (P4) |
| *Justness* | just + ness | *Justice* | `-ness` replaces `-ice` |
| *sureize* | sure + ize | *insure* | bring into the state *sure* (§3.2); *insure* is a false affix (§5.1) |
| *homeal* | home + al | *domestic* | plain base (P4); `-al` replaces `-ic` (§3.2) |
| *Tranquilness* | tranquil + ness | *Tranquility* | `-ness` replaces `-ity` (§3.2) |
| *defendment* | defend + ment | *defence* | the act (§3.2) |
| *Blessions* | bless + ion + s | *Blessings* | `-ing` is never a noun; the things that blessing gives are a result, so `-ion` (§3.2) |
| *Freeness* | free + ness | *Liberty* | as in UDHR Article 3 (F.3) |
| *Descendorage* | descend + or + age | *Posterity* | all who descend, as a group (§3.2, §3.4.2); 2 derivational affixes |
| *Constituteion* | constitute + ion | *Constitution* | the document that constituting makes, as *Declareion* (F.2) |
| *United States*, *America* | — | no change | place names |
| *Welfare*, *People* | — | no change | base words |

#### G.1.3 Size

| Version | Words | Characters |
|---|---|---|
| Standard English | 52 | 327 |
| CE | 51 | 336 |

#### G.1.4 Gaps

- (Closed.) `-ice` was not in any Replaces column. It now goes to `-ness` for a quality (*justness*, *cowardness*) and to `-ment` for an act (*servement*). *Justness* keeps only the quality of *justice*, not the system of fair law.
- *Uniteion* and *Constituteion* show the cost of `-ion` after *e* (§3.2). Both are among the most familiar words of the text.
- *do ordain and establish* uses an emphatic *do*, not an auxiliary, so the verb slots (§3.1.1) change nothing in this text.
- *Descendorage* is clear but long. Standard English has many collective words for people (*posterity*, *ancestry*, *humanity*) that CE builds with `-or` + `-age`.

### G.2 Article I, Section 1

#### G.2.1 Text

**Standard English** (25 words)

> All legislative Powers herein granted shall be vested in a Congress of the United States, which shall consist of a Senate and House of Representatives.

**Consistentized Englandese** (22 words)

> All lawizive Powers herein granted vestenend in a Congress of the United States, which consistend of a Senate and House of Representors.

#### G.2.2 Word breakdown

| CE | Parts | Standard | Note |
|---|---|---|---|
| *lawizive* | law + ize + ive | *legislative* | powers that can make law: active potential (§3.4.2); *legis* means "of law", so part swap (P4); `-ize` is `-iz` before a vowel (§4.2) |
| *Representors* | represent + or + s | *Representatives* | the ones who represent: agent noun (§3.2) |
| *vestenend* | vest + en + end | *shall be vested* | passive, deontic (§3.1.1) |
| *consistend* | consist + end | *shall consist* | deontic (§3.1.1) |
| *granted* | grant + ed | no change | already CE; next to a noun, so `-ed` (§3.1.1) |
| *Congress*, *Senate* | — | no change | base words; no plain English base |

#### G.2.3 Size

| Version | Words | Characters |
|---|---|---|
| Standard English | 25 | 151 |
| CE before §3.1.1 | 25 | 145 |
| CE | 22 | 136 |

#### G.2.4 Gaps

- *Representatives* uses `-ive` as a noun for a person. In CE, `-ive` is only an adjective, so the person uses `-or`.
- *legislate* is a Latin compound (*legis* "of law" + *latus* "carried"), so P4 rebuilds it from *law*. Before the `-iz` variant (§4.2), the form was *lawizeive*.
- *shall consist* is not an order. It describes what Congress is. `-end` still replaces it, because `-end` replaces every *shall* that is not a plain future (§3.1.1).

### G.3 Article I, Section 2, Clause 1

#### G.3.1 Text

**Standard English** (42 words)

> The House of Representatives shall be composed of Members chosen every second Year by the People of the several States, and the Electors in each State shall have the Qualifications requisite for Electors of the most numerous Branch of the State Legislature.

**Consistentized Englandese** (38 words)

> The House of Representors composenend of Members choosed every twoth Year by the People of the several States, and the Electors in each State havend the Qualifyions needed for Electors of the numberfulest Branch of the State Lawizorage.

#### G.3.2 Word breakdown

| CE | Parts | Standard | Note |
|---|---|---|---|
| *choosed* | choose + ed | *chosen* | regular past participle (§3.1); next to a noun, so `-ed` (§3.1.1) |
| *twoth* | two + th | *second* | ordinal (§3.4.2) |
| *Qualifyions* | qualify + ion + s | *Qualifications* | the conditions that qualify a person: result noun (§3.2) |
| *needed* | need + ed | *requisite* | synonym swap (P4); *requisite* is not guessable and starts with a false `re-` (§5.1) |
| *numberfulest* | number + ful + est | *most numerous* | `-ful` replaces `-ous` (§3.2); no *most* for degree (§3.1) |
| *Lawizorage* | law + iz + or + age | *Legislature* | all who make law, as a group (§6); part swap as in *lawizive* (G.2); `-ize` is `-iz` before a vowel (§4.2) |
| *Electors* | elect + or + s | no change | already CE: the ones who elect |
| *composenend* | compose + en + end | *shall be composed* | passive, deontic (§3.1.1); *compose* is common and easy to guess (P4) |
| *havend* | have + end | *shall have* | deontic (§3.1.1); `-end` drops its *e* (§4.2) |
| *Members*, *Branch*, *Year* | — | no change | base words |

#### G.3.3 Size

| Version | Words | Characters |
|---|---|---|
| Standard English | 42 | 257 |
| CE before §3.1.1 | 41 | 246 |
| CE | 38 | 236 |

#### G.3.4 Gaps

- *Legislature* ends in letters that look like CE `-ure` (about to X), so a CE reader would take it as "a person who is about to legislate". It is a false affix (§5.1).
- *Qualifyions* is not a clear result. A qualification here is a condition that a person must meet before the act, not a thing that qualifying makes. CE has no affix for "a condition for X".
- *Lawizorage* and *Legislature* have the same length, but the CE word shows its parts.

### G.4 Article I, Section 2, Clause 2

#### G.4.1 Text

**Standard English** (46 words)

> No Person shall be a Representative who shall not have attained to the Age of twenty five Years, and been seven Years a Citizen of the United States, and who shall not, when elected, be an Inhabitant of that State in which he shall be chosen.

**Consistentized Englandese** (44 words)

> No Person shall be a Representor who shall not have attained to the Age of twenty five Years, and been seven Years a Citizen of the United States, and who shall not, when elected, be a Dwellor of that State in which he choosenend.

#### G.4.2 Word breakdown

| CE | Parts | Standard | Note |
|---|---|---|---|
| *Representor* | represent + or | *Representative* | as in G.2 |
| *Dwellor* | dwell + or | *Inhabitant* | *habitare* means "dwell", so part swap (P4); *inhabit* is a false affix (§5.1); `-or` replaces `-ant` (§3.2) |
| *choosenend* | choose + en + end | *shall be chosen* | passive, deontic (§3.1.1) |
| *attained*, *elected* | attain + ed, elect + ed | no change | already CE; *attain* is common and easy to guess (P4) |
| *Citizen*, *Person*, *Age* | — | no change | base words |

#### G.4.3 Size

| Version | Words | Characters |
|---|---|---|
| Standard English | 46 | 242 |
| CE before §3.1.1 | 46 | 236 |
| CE | 44 | 230 |

#### G.4.4 Gaps

- This clause is short on derived words, so CE changes only three of them.
- The part swap stops at *habitare* ("dwell"), not at its root *habere* ("have") (P4).
- The verb slots change only *shall be chosen*. *shall be a Representor* and *shall not … be a Dwellor* need `-end` on *be* (Q11). *shall not have attained … and been* shares one set of auxiliaries between two verbs (Q12).

### G.5 Article I, Section 2, Clause 3

The Fourteenth Amendment later changed this clause. The text is the original of 1787, with its spelling *chuse*.

#### G.5.1 Text

**Standard English** (164 words)

> Representatives and direct Taxes shall be apportioned among the several States which may be included within this Union, according to their respective Numbers, which shall be determined by adding to the whole Number of free Persons, including those bound to Service for a Term of Years, and excluding Indians not taxed, three fifths of all other Persons. The actual Enumeration shall be made within three Years after the first Meeting of the Congress of the United States, and within every subsequent Term of ten Years, in such Manner as they shall by Law direct. The Number of Representatives shall not exceed one for every thirty Thousand, but each State shall have at Least one Representative; and until such enumeration shall be made, the State of New Hampshire shall be entitled to chuse three, Massachusetts eight, Rhode-Island and Providence Plantations one, Connecticut five, New-York six, New Jersey four, Pennsylvania eight, Delaware one, Maryland six, Virginia ten, North Carolina five, South Carolina five, and Georgia three.

**Consistentized Englandese** (149 words)

> Representors and direct Taxes partenend among the several States which includenmay within this Uniteion, according to their own Numbers, which countenend by adding to the whole Number of free Persons, including those binded to Servement for a Term of Years, and leaving out Indians not taxed, three fiveths of all other Persons. The actual Numberment makenend within three Years after the oneth Meetment of the Congress of the United States, and within every following Term of ten Years, in such Manner as they by Law directend. The Number of Representors outgoendnot one for every thirty Thousand, but each State havend at Least one Representor; and until such numberment makenend, the State of New Hampshire betitlenend to choose three, Massachusetts eight, Rhode-Island and Providence Plantations one, Connecticut five, New-York six, New Jersey four, Pennsylvania eight, Delaware one, Maryland six, Virginia ten, North Carolina five, South Carolina five, and Georgia three.

#### G.5.2 Word breakdown

| CE | Parts | Standard | Note |
|---|---|---|---|
| *parted* | part + ed | *apportioned* | *portio* means "part", so part swap (P4) |
| *Uniteion* | unite + ion | *Union* | as in G.1 |
| *own* | — | *respective* | synonym swap (P4); *respective* is a false affix (§5.1) |
| *counted* | count + ed | *determined* | synonym swap (P4); *determine* is a false affix (§5.1) |
| *binded* | bind + ed | *bound* | regular past participle (§3.1); next to a noun, so `-ed` (§3.1.1) |
| *Servement* | serve + ment | *Service* | the act (§3.2); `-ment` replaces `-ice` (act) |
| *leaving out* | — | *excluding* | synonym swap (P4); *exclude* is a false affix (§5.1); *including* stays, because CE has no `in-` |
| *fiveths*, *oneth* | five + th + s, one + th | *fifths*, *first* | ordinal (§3.4.2) |
| *Numberment*, *numberment* | number + ment | *Enumeration* | *numerus* means "number", so part swap (P4); the act of counting (§3.2) |
| *partenend*, *countenend*, *makenend*, *betitlenend* | part + en + end, … | *shall be apportioned*, *shall be determined*, *shall be made*, *shall be entitled* | passive, deontic (§3.1.1) |
| *directend*, *havend* | direct + end, have + end | *shall direct*, *shall have* | deontic (§3.1.1); *by Law* moves before the verb |
| *outgoendnot* | out + go + end + not | *shall not exceed* | deontic, negation (§3.1.1) |
| *includenmay* | include + en + may | *may be included* | passive, possibility (§3.1.1) |
| *Meetment* | meet + ment | *Meeting* | `-ing` is never a noun; the act (§3.2) |
| *following* | follow + ing | *subsequent* | *sequi* means "follow", so part swap (P4); *subsequent* is a false affix (§5.1) |
| *outgo* | out + go | *exceed* | *ex-* "out" + *cedere* "go", so part swap (P4); `out-` on a verb means "do better than" (§3.4.1) |
| *choose* | — | *chuse* | modern spelling of the base |
| *actual*, *direct*, *included* | — | no change | common and easy to guess (P4) |
| place names, *Providence Plantations* | — | no change | names |

#### G.5.3 Size

| Version | Words | Characters |
|---|---|---|
| Standard English | 164 | 1036 |
| CE before §3.1.1 | 165 | 1021 |
| CE | 149 | 976 |

#### G.5.4 Gaps

- *Indians* collides with the CE demonym: *India* + `-an` is a person from India (§3.4.2), but here the word means the first peoples of America. The text keeps *Indians* as the name it was in 1787.
- *own* is a little wider than *respective* ("each one's own").
- *Servement* names the act of serving, but here *Service* is a duty to work for a master. CE has no word that shows that this duty is not free.
- The verb slots save 16 words. This clause has nine uses of *shall*, more than any other baseline text.
- *as they by Law directend* moves *by Law* before the verb, because the slots join *shall* to the verb.

### G.6 First Amendment

#### G.6.1 Text

**Standard English** (45 words)

> Congress shall make no law respecting an establishment of religion, or prohibiting the free exercise thereof; or abridging the freedom of speech, or of the press; or the right of the people peaceably to assemble, and to petition the Government for a redress of grievances.

**Consistentized Englandese** (44 words)

> Congress makend no law about an establishment of religion, or prohibiting the free exercise thereof; or shortizing the freeness of speakment, or of the press; or the right of the people peacefully to assemble, and to petition the Governorage for a rightizement of wrongs.

#### G.6.2 Word breakdown

| CE | Parts | Standard | Note |
|---|---|---|---|
| *makend* | make + end | *shall make* | deontic (§3.1.1); `-end` drops its *e* (§4.2) |
| *about* | — | *respecting* | synonym swap (P4); *respect* is a false affix (§5.1) |
| *shortizing* | short + iz + ing | *abridging* | *abridge* comes from Latin *abbreviare*, *brevis* "short", so part swap (P4); *abridge* is a false affix (§5.1); `-ize` is `-iz` before a vowel (§4.2) |
| *freeness* | free + ness | *freedom* | `-dom` is a realm only (§3.4.2), as in F.2 |
| *speakment* | speak + ment | *speech* | the act (§3.2) |
| *peacefully* | peace + ful + ly | *peaceably* | *peaceable* does not mean "can be peaced", so `-able` is false (§5.1); `-ful` is "having X" (§3.2) |
| *Governorage* | govern + or + age | *Government* | all who govern, as a group (§6), as *Lawizorage* (G.3) |
| *rightizement* | right + iz + ment | *redress* | the act of making right; *redress* comes from Old French *redresser*, "set straight again" (P4); *redress* is a false affix (§5.1) |
| *wrongs* | wrong + s | *grievances* | synonym swap (P4); `-ance` is not a CE affix, and *grievance* is neither an act nor a quality |
| *establishment* | establish + ment | no change | already CE: the act of establishing |
| *prohibiting*, *exercise*, *assemble*, *petition*, *religion* | — | no change | common and easy to guess (P4) |

#### G.6.3 Size

| Version | Words | Characters |
|---|---|---|
| Standard English | 45 | 272 |
| CE before §3.1.1 | 45 | 275 |
| CE | 44 | 271 |

#### G.6.4 Gaps

- *about* is wider than *respecting*. In this text both mean "on the subject of".
- *speakment* is the act of speaking. The right also covers what is said, which would be *speakion* (the result).
