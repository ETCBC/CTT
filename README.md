# Short Description of a CTT file

CTT stands for Coded Text Tabulated. It is a human-readable ASCII file which offers an overview of the clause atom hierarchy. The information is displayed in nine fields of fixed width, which are the following.

1. Verse Label
2. Person/Number/Gender of the predicate
3. Clause Atom Type of the daughter
4. Indication of the mother
5. Text Type
6. Paragraph Number
7. Clause Atom Number
8. Tabulation and Subtypes
9. Hierarchy with surface text and parsing labels

## Field 4. Indication of the mother
This can be either:
1. the clause atom type of the mother, for example `WayX`;
2. the marker `[Q]`, which indicates that the mother introduced direct speech;
3. the marker `[R]`, which means that this atom is the root of the clause atom hierarchy;
4. a clause constituent relation, for instance `[adjunct]`.

## Field 5. Text Type
Text type is a feature of a clause. In clauses that consist of more than one clause atom, the value for text type is repeated with every subsequent clause atom of the clause. The values are constructed in a cumulative manner. The clause `L> T>KLW M-KL <Y H-GN` in Genesis 3:1, for instance, is a quotation within a quotation in a narrative passage, and therefore marked `NQQ`. Text type is a concatenation of any of the following characters. 

Sign | Meaning
-|-
? | Unknown
D | Discursive
N | Narrative
Q | Quotation

## Field 8. Subtypes
The two subtypes are indicated by two characters. The first subtype indicates whether the clause atom effectively contains a predicate, and if not, why. The character codes are summarised in the table below. 

Sign | Meaning
-|-
. | _empty_
c | casus pendens
d | defective
l | ellipsis
m | macrosyntactic sign
r | reopening
v | vocative
x | extraposition

The second subtype indicates the status of the clause atom in the text. The character codes are summarised in the table below. 

Sign | Meaning
-|-
# | new paragraph
. | _empty_
N | no connection
\ | downward connection
e | embedding
p | proleptic ellipsis
q | direct speech

## Field 9. Parsing Labels

### Phrase Atom Relations
Label | Meaning
-|-
`<ap>`  |  Apposition
`<cj>`  |  Link
`<pa>`  |  Parallel
`<ss>`  |  Suffix specification
`<sp>`  |  Specification

### Phrase Function within Clause
Label | Meaning
-|-
`<..>`  |  Unknown
`<Aj>`  |  Adjunct
`<Co>`  |  Complement
`<Cj>`  |  Conjunction
`<Ep>`  |  Enclitic personal pronoun
`<Xs>`  |  Existence with subject suffix
`<eX>`  |  Existence
`<Fr>`  |  Fronted element
`<Ij>`  |  Interjection
`<Is>`  |  Interjection with subject suffix
`<Lo>`  |  Locative
`<Mo>`  |  Modifier
`<Ms>`  |  Modifier with subject suffix
`<NC>`  |  Negative copula
`<Ns>`  |  Negative copula with subject suffix
`<Ng>`  |  Negation
`<Ob>`  |  Object
`<Pj>`  |  Predicative adjunct
`<PS>`  |  Predicate complement with subject suffix
`<PC>`  |  Predicate complement
`<Pr>`  |  Predicate
`<PO>`  |  Predicate with object suffix
`<Ps>`  |  Predicate with subject suffix
`<po>`  |  Participle with object suffix
`<Qu>`  |  Question
`<Re>`  |  Relative
`<Su>`  |  Subject
`<sc>`  |  Supplementary constituent
`<Ti>`  |  Time reference
`<Vo>`  |  Vocative
