# Consistentized Englandese — Specification

Status: draft v0.1

## 1. Purpose

Consistentized Englandese (CE) is a controlled form of English. It has two layers:

1. **Base layer.** Writing rules that follow the principles of Simplified Technical English (ASD-STE100). The rules are written here in our own words. CE does not copy the STE100 dictionary.
2. **Affix layer.** Each grammatical or derivational meaning has one affix. CE replaces irregular and competing forms with the regular form, including in existing English words.

## 2. Core principles

- **P1. One word, one meaning.** Each word in the CE dictionary has one meaning and one part of speech.
- **P2. One meaning, one affix.** Each affix meaning has one affix. Different meanings use different affixes.
- **P3. Conditioned allomorphy only.** An affix may have more than one written form (allomorph). An allomorph exists only to prevent awkward spelling or pronunciation: a forced consonant cluster, a vowel clash, a triple letter, or a change in the sound of the base. A fixed rule always chooses the form; the writer never chooses freely. All allowed allomorphs are listed in §5.
- **P4. Plain base.** Derivations attach to the plain English base word. They do not attach to a Latin or Greek root. Example: *see* + *-able* → *seeable*, not *visible*.
- **P5. Overwrite.** If a regular CE form exists, it replaces the traditional English form. Example: *impossible* → *unpossible*. This includes technical vocabulary: *cardiology* → *heartology*, *flammable* → *burnable*.
- **P6. Codified names are exempt.** If an outside standard defines a name, CE keeps it. Otherwise, CE builds it. The exempt names are:
  - chemical names from IUPAC nomenclature (*carbon dioxide*, *sulfate*, *ferric oxide*)
  - SI units and SI prefixes (*kilometer*, *milligram*, *microsecond*)
  - scientific names of species (*Homo sapiens*)
  - legal, registered and trade names (*Ltd*, product names)
  - part numbers, standard numbers and codes
  - terms with a legal or regulatory definition, when the text depends on that definition (*flammable* and *combustible* on a safety label)

  Reason: these names are already consistent systems with outside owners. A CE text must match the drawings, parts lists, data sheets and regulations it refers to.

## 3. Base layer: writing rules

### 3.1 Words
- Use only words in the CE dictionary (§7), or technical names and technical verbs from your field. Technical names follow the affix rules unless P6 exempts them.
- Use a word only with its dictionary meaning and part of speech.
- Do not use phrasal verbs (*set up*, *carry out*). Use a single verb.

### 3.2 Sentences
- Procedural sentences: no more than 20 words.
- Descriptive sentences: no more than 25 words.
- Write one instruction in each sentence. You can write two instructions in one sentence only when the reader must do them at the same time.
- Use the active voice in procedures.
- Use the imperative (command) form for instructions.
- Use only these verb forms: simple present, simple past, simple future, imperative, infinitive, and past participle as an adjective.
- Do not leave out articles (*a*, *the*) or other short words to make a sentence shorter.

### 3.3 Paragraphs
- Write one topic in each paragraph.
- A paragraph has no more than 6 sentences.
- Put a warning or caution before the instruction it applies to.

## 4. Affix layer

### 4.1 Inflection

| Meaning | Affix | Replaces | Examples |
|---|---|---|---|
| Plural noun | `-s` | -en, -i, -a, vowel change, zero plural | *mouses*, *childs*, *mans*, *sheeps*, *datums*, *criterions* |
| Third person singular present | `-s` | — | *gos*, *haves* (*has*) |
| Past tense | `-ed` | strong/irregular verbs | *goed*, *runned*, *taked*, *thinked* |
| Past participle | `-ed` | -en, vowel change | *taked*, *writed*, *goed* |
| Progressive / gerund | `-ing` | — | *runing* |
| Comparative | *more* + adjective | -er, irregular forms | *more good*, *more big* |
| Superlative | *most* + adjective | -est, irregular forms | *most good*, *most big* |

Notes:
- Plural `-s` and third person `-s` have the same form. This is a known exception to P2. It is kept because the part of speech is always clear from context and from P1.
- Comparison uses *more* / *most*, not `-er` / `-est`. This keeps `-er` for the agent noun only (§4.2).
- *be* is the only irregular verb. Its forms are kept: *am, is, are, was, were, been*. (Open question Q1.)

### 4.2 Derivation

| Meaning | Affix | Replaces | Examples |
|---|---|---|---|
| Not X (adjective, noun) | `un-` | in-, im-, il-, ir-, non-, dis-, a- | *unpossible*, *unlegal*, *unregular*, *unhonest*, *unmoral* |
| Reverse the action X (verb) | `de-` | un-, dis- (on verbs) | *detie*, *delock*, *deconnect* |
| Against X | `anti-` | counter-, contra- | *antiact*, *antisay* |
| Again | `re-` | — | *redo* |
| Person or thing that does X | `-er` | -or, -ar, -ist, -ian, -ant, -ent | *acter*, *beger* (*beggar*), *sciencer*, *assister* |
| Person or thing that receives X | `-ee` | — | *employee*, *payee*, *usee* |
| Can be X-ed | `-able` | -ible, -uble | *seeable*, *readable*, *solveable* |
| Process or act of X (noun) | `-ing` | -tion, -sion, -ment, -ance, -ence, -al, -age | *connecting*, *paying*, *arriving* |
| State or quality of being X | `-ness` | -ity, -th, -ance, -ence, -cy, -hood, -ship | *unpossibleness*, *trueness*, *longness*, *safeness* |
| Relating to X | `-al` | -ic, -ical, -ar, -ary | *scienceal*, *historyal*, *personal* |
| Full of / having X | `-ful` | -ous, -y, -ive | *dangerful*, *fameful*, *rainful* |
| Without X | `-less` | — | *powerless* |
| In an X way (adverb) | `-ly` | irregular adverbs | *goodly* (*well*), *fastly* (*fast*) |
| Make X / become X (verb) | `-ize` | -ify, -en, -ate | *widize*, *simpleize*, *activeize* |

### 4.3 Affix order

When more than one affix attaches to a word, use this order:

```
prefix(es) + base + derivational suffix(es) + inflectional suffix
```

Examples: *un* + *read* + *able* + *ness* → *unreadableness*; *re* + *connect* + *ed* → *reconnected*.

### 4.4 Extended affixes

In standard English, many affixes work only with some words. For example, *-hood* goes on *child* but not on *teacher*, and *mis-* goes on *read* but not on *open*. In CE, every affix in §4.2 and §4.4 is **fully productive**. It attaches to every base of its input part of speech when the result makes sense. Each affix has one meaning. All the forms it replaces are removed.

#### 4.4.1 Prefixes

| Meaning | Affix | Attaches to | Replaces | Examples |
|---|---|---|---|---|
| Wrongly, badly | `mis-` | verb | mal-, mis- | *misfunction* (*malfunction*), *misopen*, *misset* |
| Too much | `over-` | verb, adj | hyper-, ultra-, super- (in this meaning) | *overheat*, *overtight*, *overactive* (*hyperactive*) |
| Too little | `under-` | verb, adj | hypo- | *undercook*, *underfill* |
| Below (place or rank) | `sub-` | noun | under- (in this meaning), infra- | *subground* (*underground*), *subline* (*underline*), *subgroup* |
| Above (place or rank) | `super-` | noun | over- (in this meaning), supra- | *superhead* (*overhead*), *superpass* (*overpass*) |
| Before (time) | `pre-` | noun, verb | fore-, ante- | *prewarn* (*forewarn*), *preroom* (*anteroom*), *prewash* |
| After (time) | `post-` | noun, verb | after- | *postshock* (*aftershock*), *postwash* |
| Between | `inter-` | noun, verb | — | *intercity*, *interconnect* |
| Across | `trans-` | noun | — | *transsea*, *transcountry* |
| Together, jointly | `co-` | noun, verb | con-, com-, syn-, sym- (in new forms) | *cowork*, *cowriter* |
| Former | `ex-` | noun | *former* | *exteacher*, *exhome* |
| Done to itself (the doer is also the receiver) | `self-` | verb, noun | auto- (in this meaning) | *selfclean*, *selfteach*, *selfdefend*, *selfbiography* (*autobiography*) |
| Done without outside control, automatic | `auto-` | verb, noun | — | *autofocus*, *autolock*, *autopilot*, *automover* (*automobile*) |
| Do more than, do better than | `out-` | verb | — | *outrun*, *outsee*, *outbuild* |
| Put in, give | `en-` | noun | em-, be- | *encage*, *enpower* (*empower*), *enfriend* (*befriend*) |
| Half, partly | `semi-` | noun, adj | hemi-, demi-, half- | *semisphere* (*hemisphere*), *semicircle* |
| One | `uni-` | noun | mono-, single- | *uniwheel*, *unirail* (*monorail*) |
| Two | `bi-` | noun | di-, twi-, double- | *biwheel*, *bilight* (*twilight*); not in chemical names (P6) |
| Three | `tri-` | noun | — | *triwheel* (*tricycle*), *triangle* |
| Many | `multi-` | noun, adj | poly-, many- | *multicolor*, *multisided* (*polygonal*) |

Notes:
- *under-* and *over-* now have one meaning each (amount). Place and rank use *sub-* and *super-*.
- *self-* and *auto-* are different. A *selfclean* oven cleans its own inside. An *autoclean* print head starts its cleaning cycle with no operator.
- *en-* has no *em-* variant. *enpower* is easy to say (§5).

#### 4.4.2 Suffixes

| Meaning | Affix | Attaches to | Replaces | Examples |
|---|---|---|---|---|
| Small X | `-let` | noun | -ling, -ette, -kin, -ie, -y, mini- | *ducklet* (*duckling*), *kitchenlet* (*kitchenette*), *doglet* (*doggy*), *carlet* |
| Like X, in the manner of X | `-like` | noun | -ish (on nouns), -ly (on nouns), -esque, -oid | *childlike* (*childish*), *friendlike* (*friendly*), *humanlike* (*humanoid*) |
| Somewhat X, almost X | `-ish` | adj, number | -y (on colors) | *reddish*, *coldish*, *tenish* |
| Place where X is done or made | `-ery` | verb, noun | -ory, -arium, -ary, -age, room words | *bakery*, *washery* (*laundry*), *readery* (*library*), *cookery* (*kitchen*), *fishery* |
| All X as a group; area ruled by X | `-dom` | noun | -ry, -ery (in this meaning), -age, -ware | *kingdom*, *machinedom* (*machinery*), *bagdom* (*baggage*), *kitchendom* (*kitchenware*) |
| Toward X | `-ward` | noun | -wards | *homeward*, *skyward*, *doorward* |
| With respect to X | `-wise` | noun | — | *costwise*, *timewise* |
| Belief or system of X | `-ism` | noun, adj | -cracy | *realism*, *peopleism* (*democracy*) |
| Study or science of X | `-ology` | noun | -ics, -logy, -nomy, -graphy | *earthology* (*geology*), *animalology* (*zoology*), *starology* (*astronomy*), *lifeology* (*biology*) |
| From place X; language of place X | `-ese` | proper noun | -ian, -ish, -an, -i, -ic, -er | *Italyese*, *Englandese* (*English*), *Franceese* → *Francese* (*French*), *Iraqese* (*Iraqi*) |
| Number X in order (ordinal) | `-th` | number | irregular ordinals | *oneth* (*first*), *twoth* (*second*), *threeth* (*third*), *fiveth*, *eighth*, *twentyth* |
| X times as many | `-fold` | number | -ple, -ble | *twofold* (*double*), *threefold* (*triple*) |

Notes:
- `-ese` overwrites names of peoples and languages too (P5). The name of this language is *Consistentized Englandese*. More examples: *Chinaese* (*Chinese*), *Thailandese* (*Thai*), *Spainese* (*Spanish*, *Spaniard*), *Walesese* (*Welsh*), *Netherlandsese* (*Dutch*), *Japanese* (no change).
- A people or language whose name is itself the base word does not take `-ese`. Examples: *Tamil*, *Yoruba*, *Basque*, *Latin*, *Esperanto*.
- Place names themselves do not change (*England*, *Malaysia*). Only the derived forms change.
- *-like* and *-ly* are different. *-like* makes an adjective from a noun. *-ly* makes an adverb from an adjective. So *friendly* (adjective, "like a friend") becomes *friendlike*.
- *-ish* and *-like* are different. *childish* (like a child) becomes *childlike*. *reddish* (somewhat red) does not change.

### 4.5 Removed affixes

These affixes have no CE form. Use a separate word.

| Affix | Meaning | CE form | Examples |
|---|---|---|---|
| -ess, -ette, -trix, -ine | female | *female* + noun | *actress* → *female acter*, *heroine* → *female hero* |
| -ly (on time nouns) | every X | *each* + noun | *daily* → *each day*, *weekly* → *each week* |

Reason for *-ly* on time nouns: *-ly* already means "in an X way" (§4.2). *daily* would break P2.

## 5. Allowed allomorphs

**Rule: the base word never changes.** An affix never adds, removes or changes a letter of the base. All variation is in the affix.

An affix may have a variant only to prevent awkward spelling or pronunciation (P3). It is not enough that the traditional form is more familiar. So *un-* has no *im-*, *il-* or *ir-* variant: *unpossible* and *unlegal* are easy to say.

These are the only allowed variants. A rule always chooses the form.

### 5.1 Add a vowel to the affix (break a consonant cluster)

| Affix | Variant | Condition | Examples |
|---|---|---|---|
| `-s` | `-es` | Base ends in *s, x, z, ch, sh* | *box* → *boxes*, *wish* → *wishes* |

### 5.2 Remove the first letter of the affix (prevent an overlap)

When the base ends in the letter that the affix starts with, and keeping both would be awkward, the affix loses its first letter. Awkward means one of these:

- a doubled *e*
- a triple letter
- *tth*

| Affix | Variant | Condition | Examples |
|---|---|---|---|
| Any suffix that starts with *e* (`-ed`, `-er`, `-ee`, `-ery`, `-ese`) | drop the *e* | Base ends in *e* | *bake* → *baked*; *make* → *maker*; *use* → *usee*; *bake* → *bakery*; *France* → *Francese* |
| Any affix | drop its first letter | The result would have three of the same letter | *full* + `-ly` → *fully*; *skill* + `-less` → *skilless* |
| `-th` | `-h` | Base ends in *t* | *eight* → *eighth* |

### 5.3 Results of the rule

Because the base never changes, these traditional spelling changes are not used:

| Traditional | CE | Rule removed |
|---|---|---|
| *tried*, *happiness* | *tryed*, *happyness* | *y* → *i* |
| *stopped*, *running* | *stoped*, *runing* | double the final consonant |
| *making*, *usable* | *makeing*, *useable* | drop the final *e* |
| *simply* | *simplely* | *-le* → *-ly* |
| *panicked* | *paniced* | *c* → *ck* |

Note: without doubling and *c* → *ck*, some spellings no longer show the sound of the base (*stoped* looks like it has a long *o*; *paniced* looks like it has an *s* sound). See Q3.

## 6. Collisions with existing words

Some regular CE forms have the same spelling as an existing English word with a different meaning. CE gives the word its CE meaning. List of known collisions:

| CE form | CE meaning | Existing English meaning |
|---|---|---|
| *seed* | past tense of *see* | part of a plant |
| *goodly* | in a good way | large in amount (archaic) |

(Open question Q2.)

## 7. Dictionary

CE uses its own core dictionary. It is not a copy of the STE100 dictionary. Each entry has:

- the base word
- its one part of speech
- its one meaning
- one example sentence
- the unapproved words it replaces (optional)

The dictionary is to be done. Only base words go in the dictionary. Affixed forms are made by the rules in §4 and are not listed.

## 8. Open questions

- **Q1.** Do we regularize *be* (*I be, he bes, he beed*)?
- **Q2.** How do we handle collisions such as *seed* (see §6)? Options: accept the collision, add a hyphen (*see-ed*), or change the allomorph rule.
- **Q3.** Do we need a variant that keeps the sound of the base without changing its spelling? Example: a hyphen or a written mark between base and affix (*stop-ed*, *panic-ed*).
- **Q4.** Process nouns with `-ing` and gerunds have the same form. Do we need a separate affix for the *result* of an action (*a connection* as a thing, not an act)?
- **Q5.** Should `-er` cover both persons (*teacher*) and tools (*computer*), or should tools use a separate affix?
- **Q6.** Plural place names make awkward forms (*Netherlandsese*, *Philippinesese*). Do we need an `-ese` variant after *s*?

## Appendix A. Example translation

### A.1 Text

**Standard English**

> Before you begin, make sure the machine is completely disconnected from the power supply. It is impossible to safely inspect the electrical components while the unit is running. The technician who carried out the last inspection found that several bolts had been loosened and two of the seals were broken. These problems are not easily visible, so you should check each joint carefully. If a seal is unusable, replace it immediately. The replacement must be done by a qualified operator.

**Consistentized Englandese**

> Deconnect the machine completely from the power supply before you start. It is unpossible to examine the electric parts safely when the machine operates. The techniquer who did the last inspecting finded that some bolts were looseized and two seals were breaked. These problems are not easyly seeable. Examine each joint carefully. If a seal is unuseable, replace it immediately. Only a trained operater can do the replacing.

### A.2 Changes

| Standard | CE | Rule |
|---|---|---|
| *disconnected* | *deconnect* | `de-` is the only "reverse the action" prefix (§4.2) |
| *impossible*, *unusable* | *unpossible*, *unuseable* | `un-` is the only "not" prefix (§4.2) |
| *technician*, *operator* | *techniquer*, *operater* | one agent suffix, `-er`; `-r` after *e* (§4.2, §5.2) |
| *inspection*, *replacement* | *inspecting*, *replacing* | one process-noun suffix, `-ing` (§4.2) |
| *found*, *broken* | *finded*, *breaked* | every past form uses `-ed` (§4.1) |
| *loosened* | *looseized* | one "make X" suffix, `-ize` (§4.2) |
| *visible* | *seeable* | affix goes on the plain base (P4) |
| *easily* | *easyly* | the base never changes (§5) |
| *carried out*, *make sure* | *did*, (removed) | no phrasal verbs (§3.1) |
| *while … is running* | *when … operates* | simple tenses only (§3.2) |
| *must be done by* | *can do* | active voice (§3.2) |

### A.3 One base, all forms

A learner who knows one base word and the affix rules can make every related form. Standard English uses roots from three sources (*see*, *view*, *vis-*) and two irregular forms. CE uses one base.

| Meaning | Standard English | CE |
|---|---|---|
| past | *saw* | *seed* (see Q2) |
| past participle | *seen* | *seed* (see Q2) |
| one who sees | *viewer* | *seer* |
| can be seen | *visible* | *seeable* |
| cannot be seen | *invisible* | *unseeable* |
| state of being seeable | *visibility* | *seeableness* |
| see again | *review* | *resee* |

### A.4 Cost

To an ordinary English reader, CE forms such as *finded*, *easyly* and *techniquer* look like mistakes, although they are easy to understand. CE accepts this cost in exchange for predictable word forms.
