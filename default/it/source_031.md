### Incipit (031)

The field **Incipit** is used for musical information about the opening few measures of the piece and includes music incipits as well as text incipits. Incipits help identify works and facilitate the comparison of sources. Best practice for instrumental music is to include incipits from a high part and a low part, such as vl 1 and bass. For vocal music, include incipits from the highest voice and the first violin or the highest instrumental part.

If the notation you need is not available using the Plaine & Easie code, transcribe the music the best you can and include an explanatory note. You can attach an image of the incipit from the source for further clarification.

Keep in mind that incipit transcription is primarily used for searching and identification, not for replicating the visual appearance of the score. The Plaine & Easie Code is an intentional simplification of Western notation and not all details can (or should) be encoded.

For assistance with transcribing mensural notation, see ["Basic Mensural Notation Reference" by Ted Dumitrescu](http://www.cmme.org/misc/refsheet.pdf).

<!-- Note to translators: If you know of a standard reference document or website for transcribing mensural notation in your language, please use that instead. If not, feel free to link to this English document. -->  

_MARC export note:_  
Records that contain an incipit (anything in field 031) receive $2pe upon saving, indicating that the incipit was created using the Plaine & Easie code.

#### Work number, movement number, incipit number (031 $a, b, c)

**Required field if any field in this section is used.**

The incipit number consists of three digits, which stand for work, movement, and incipit.

The first digit is always a 1. The work number refers to the position of the incipit in the record in question, not its position in the source as a whole. Works in RISM are cataloged in separate records using a parent/child hierarchy, so the each record only has one work.

Movements refer to both the work as a whole but also significant sections of a work, whether they are technically movements (such as a symphony) or different sections (such as a recitative and aria). Movement numbers can be identical if multiple incipits are entered for the movement.

The incipit number is embedded within the hierarchy of the movement or work. Identical movement numbers but different incipit numbers mean that the incipits sound simultaneously, such as a vl 1 and bass.

##### Examples

- 1.1.1 = 1st work, 1st movement, 1st incipit
- 1.1.2 = 1st work, 1st movement, 2nd incipit (sounds at the same time as 1.1.1)
- 1.2.1 = 1st work, 2nd movement, 1st incipit
- 1.3.1 = 1st work, 3rd movement, 1st incipit

Periods between the numbers are automatically added by Muscat.

The three-figure incipit number must be unique within a record. Number incipits consecutively and with respect to the record in question. The incipit number may not imply any comment on the position of the item in a source. Numbering within the source should be reflected in the title description, and any particularities can be explained in a note. This means that the incipit for the fourth song in a song collection will be 1.1.1, as with all songs in the collection.

 Consecutive numbering must be followed even if content is missing from the source. For example, if one song is missing from a collection of six songs, the work number of each incipit will still start with a 1. If the source is a three-movement symphony but the middle movement is missing, the incipits will be numbered 1.1.1 and 1.2.1 (not 1.3.1).


#### Title of movement, tempo (031 $d)

Enter the title of the movement and tempo or similar indications, if specified, as it appears on the source. Use **\|** (the vertical pipe) with a single space before and after the sign to show a line break. Use square brackets to indicate supplements to the original; any such additions should be spelled consistently. Multiple titles or additional tempo markings can be added in separate fields. If you are entering multiple incipits for which the title or tempo indication is the same, enter it only for the first music incipit.

##### Examples
- All|o
- [vol. 1 p. 17:] N. 1: Recit. et Aria

**Obsolete procedures**: Older RISM guidelines allowed the phrase "Without tempo" to indicate that a movement has several tempo indications, of which one or several are not known. Multiple tempo indications were entered after each other, separated by semicolons.


#### Voice/instrument (031 $m)

Enter the voice part or instrument using the list of **RISM instrument abbreviations**. Enter **V** for an unknown vocal part. Enter **i** for an unknown instrumental part. Indicate the tuning of an instrument in the **General note** field. If the instrument is a transposing instrument, you may enter it at notated pitch or at sounding pitch. In the field **General note (031 $q)**, indicate which option you used.

##### Examples

- pf
- Coro T
- org with text

**Obsolete procedures**: Older RISM guidelines required music incipits for transposing instruments to be entered at sounding pitch.

#### Role (031 $e)

Enter the standardized dramatic role name here. If you fill out this field, make sure to also fill out the field **Dramatic role named (595)**. Indicate any editorial additions with square brackets. Indicate any questionable information with a question mark.

#### Text incipit (031 $t)

A text incipit consists of the first few words of the piece or section and can be the first line, first phrase, or other group of words that make linguistic sense. Text incipits serve to identify the text used and do not necessarily need to match the length of music given in the music incipit. Text incipits can be included regardless of whether a music incipit is entered. Note that separate rules apply to texts in Latin (see below).

Text incipits are given in standardized form. Enter the text incipit using modern spelling. Refer to the index **Title/text incipits** to help standardize your entry. Enter new incipits if they are not in the index.

Do not put portions of the text in square brackets or supply missing words. Omit punctuation marks and repetitions in the text.

Accents should be used only as they appear in the dictionary or if they are grammatically correct. Write out numbers at the beginnings of texts as words. Upper- and lower-case letters follow the rules of the respective language, except that designations for God (Herr, Dio, Dieu, Signore, Lord, etc.) always start with a capital letter. If the text incipit is used as the standardized title (240), make sure that the length and spelling agree exactly.

Omit the text entirely if you cannot read it and add a note saying "Text illegible" or similar.

In Romance languages, continue the text directly after an apostrophe and without a space. An exception to this rule is when the first letter of a word is replaced by an apostrophe (for example: Fra l'amante e 'l genitor).

Ascertained or derived texts that do not appear on the source can be given here. In such cases, put the entire text in square brackets. Among these texts are:

- Texts if a vocal part is missing
- Text incipits in the original language of the work when the source contains a translated version
- Texts of vocal compositions which became the theme of a variation or the basis of an instrumental arrangement

**Non-Latin scripts:** If your source has a text incipit that uses non-Latin letters or characters (Cyrillic/Greek/Hebrew/Korean etc. alphabet, Chinese characters, etc.) enter the **Text incipit** using the original script. Translations or transliterations are optional and may be added in additional text incipit fields. Add translations not on the source in square brackets. You may translate into any of the RISM languages.

**Special rules for texts in Latin:** Enter Latin texts, both sacred and secular. If the text incipit is used as the standardized title, make sure that the spelling is identical, but remember that Latin text in standardized titles is only entered up to the comma. Use square brackets to enter Latin texts which are not named on the source but have been determined by research.

Standard Latin texts usually match the texts in the _Liber usualis_. In RISM, these texts usually contain a comma. For example, when you search for the text "Et in terra pax", you will see about a dozen options, but only 1 has a comma and this source is used 4,800 times in the database. Therefore it is the one we want – presuming this matches your source. If your text incipit is only "Et in terra pax" then this means your source (1) contains only these words or (2) continues in a way that is different from the _Liber usualis_. This is of course possible, but in most cases you want the version with the comma.


#### Key or mode (031 $r)

Select the key or mode of the incipit from the list.

**Obsolete procedures**: Older RISM cataloging guidelines allowed multiple key signatures to be entered in this field, separated by a semicolon. This practice was discontinued with the introduction of Muscat.

#### Key signature (031 $n)

Enter **x** for sharp keys or **b** for flat keys, followed by capital letters of the pitches to be raised or lowered. If a piece is clearly in a certain key but a sharp or flat is not in the key signature, the missing sharps or flats may be added in square brackets.

If there is no key signature, leave the field blank.

##### Examples

- xF = F is sharp = G major or E minor
- bBE = B and E are flat = B-flat major or G minor
- xFC[G] = F and C are sharp in the source but the piece is clearly in A major, so the last sharp is added in square brackets

#### Time signature (031 $o)

Enter time signatures as fractions. The following are also allowed:

- **c** = common time or tempus imperfectum cum prolatione imperfecta
- **c/** = cut time, alla breve
- **3** = proportio tripla; also **1**, **2**, etc.
- **c3** = proportio tripla
- **c3/2**
- **c.** = tempus imperfectum cum prolatione perfecta
- **o** = tempus perfectum cum prolatione imperfecta
- **o/** = tempus perfectum cum prolatione minore diminutum
- **o.**  = perfect time, tempus perfectum cum prolatione perfecta

If the meter changes constantly, you can write the first time signature followed by the second, separated by a space.

If the incipit is without a time signature, add one and also add an explanation in the field **General note (031 $q)** such as "Time signature added." Do not put the inferred time signature in square brackets.

**Obsolete procedures**: Older guidelines allowed a blank field here if the source lacked a time signature.

##### Examples

- 4/4
- 6/8
- 3/4 4/4

If the time signature in the source is obviously wrong, correct it to match the incipit given. Include an explanatory note in the field **General note**.

#### Clef (031 $g)

Select a clef from the list. The letter indicates the kind of clef. A hyphen means modern notation. A plus sign means mensural notation. The number refers to position on the staff line.

If no clef is on the source, select one from the list and include an explanatory note in the field **General note (031 $q)**.

#### Validity (031 $s)

Do not enter anything into this field! (It is only used for old data.)

#### Music incipit (031 $p)

Enter the music incipit in encoded form using the Plaine & Easie code (see also [https://www.iaml.info/plaine-easie-code](https://www.iaml.info/plaine-easie-code)). The incipit should be at least two bars (measures) or six notes long.

##### 1. Octaves
' = in the 1st octave above middle C  
'' = in the 2nd octave above middle C  
''' = in the 3rd octave above middle C  
, = in the 1st octave below middle C  
,, = in the 2nd octave below middle C  
,,, = in the 3rd octave below middle C

##### 2. Rhythmic values

0 = longa  
9 = breve  
1 = whole note / semibreve  
2 = half note / minim  
4 = quarter note / crotchet / semiminim  
8 = eighth note / quaver / fusa  
6 = 16th note / semiquaver / semi fusa   
3 = 32nd note / demisemiquaver  
5 = 64th note / hemidemisemiquaver  
7 = 128th note / semihemidemisemiquaver  
7\. = neumatic notation

Periods are used for dotted notes. Multiple periods can be added to a note.

4\. = dotted quarter note / dotted crotchet   
8.. = double dotted eighth note / double dotted quaver

##### 3. Accidentals

x = sharp  
xx = double sharp  
b = flat  
bb = double flat  
n = natural

##### 4. Note names

C, D, E, F, G, A, B

##### 5. Grace notes and ornaments

g = acciaccatura (without rhythmic value, precedes the note name)  
q = appoggiatura (with rhythmic value, precedes the note name)  
qq...r = several appoggiaturas or ornaments which belong together (with rhythmic value)

##### 6. Rests

The '-' (minus sign) is for a single-note rest. Use '=' (equal sign) for a measure rest. For multiple measures of rest, follow the = with the number of measures and a bar line.
- Eighth-note rest
 - 8-/
- One measure of rest
 - -/
 - =1/
- Multiple measures of rest
 - =35/

##### 7. Bar lines

/ = bar line  
// = double bar line  
//: = double bar line with repeat  
:// = double bar line with repeat  
://: = double bar line with repeat

##### 8. Other symbols

t = trill (immediately follows the note)

+ = tie (immediately follows the note; not to be confused with a slur)  
  () = fermata/hold/pause (only a single note letter name or a single rest can be bracketed; accidentals, pitch indications, etc. must be outside the parentheses; see also **10. Special rhythms**, below)

Do not enter slurs.

##### 9. Beaming

{ = beginning of beaming  
} = end of beaming

###### Example

{qq6'CDEDr}

##### 10. Special rhythms

( = beginning of special rhythm  
) = end of special rhythm

The total duration value of the group must be written before the **(**. The rhythmic value of the first note must be given after **(**, even if it is identical with that of the note immediately before the section of special rhythm. The number of notes in the group must be indicated before **)**. It is separated from the last note by **;**.

###### Examples

- 8(3ABCDE;5)   = quintuplet, five demisemiquavers/32nd notes, in the space of a quaver/eighth note.
- 8({3ABCDE};5) = quintuplet, five demisemiquavers/32nd notes, in the space of a quaver/eighth note, beamed

The triplet is a special case. Strictly speaking, it should be encoded as:  
8(6ABC;3) or 8({6ABC};3).  
Instead though, the following shortcut is permitted:  
(6ABC)  
({6ABC})

Do not forget the rhythmic value within the bracket!

##### 11. Shortcuts

###### 11.1. Repeated figures

! = beginning and end of passage  
f = repeat indication   
The figure will be repeated as often as **f** is repeated after the second **!**. This is only possible within a bar.

###### Example

- !{'8ABAG}!ff = this figure will be repeated twice

###### 11.2. Repeated bars

i = repeat last bar  
'i' always goes between two bar lines.

###### Example

- '4ABAG/i/i/ = the bar will be repeated twice

###### 11.3. Rhythmic patterns

When a certain rhythmic sequence is repeated several times, the rhythmic pattern can be given before the respective note letter names.

The rhythmic sequence ends as soon a different rhythmic value occurs. Make sure that all notes as indicated by the pattern are present at least once.

###### Example

- Instead of **8.A6B8C8.D6E8F** the code can be **8.68ABCDEF**


##### 12. Change of clef

If the clef changes within the music incipit, use **%** to change the clef. Follow this with the new clef and a space.

###### Examples

- %C-1 '2A
- %C-1 $xFC '8B

##### 13. Change of key

If the key changes within the music incipit, use **$** to change the key. Follow this with the new key signature and a space. A key signature can only be changed once per measure. You can cancel the previous key signature with $n or move directly to the new key signature.

###### Examples

- $nBE $xFC
- $xFC

##### 14. Change of time signature

If the time signature changes within the music incipit, use **@** to change the time signature. Follow this with the new time signature and a space.

###### Examples

- @3/2 '1C

##### 15. Abbreviations

Abbreviated forms of notation found within the music, such as tremolos or simile signs for repeats, must be written out in full using the actual notation.

###### Examples

- {'8DDDD} = minim/ half tremolo on D

##### 16. Chords

Enter chords from the highest to the lowest note, separated by a **^**.

###### Example

- 4’’C^’G^E^C

**Obsolete procedures**: In older cataloging programs, the field for encoded notation began with the control character $ followed by the key signature ($xFC for $bBE), and then a character that was entered as a ³ (superscript 3) but displayed as an _ (underscore). Incipits with no key signature started directly with an _.

#### General note (031 $q)

Add any other comments, such as the pitch of transposing instruments, mistakes in the incipit, the text incipit with the original spelling and/or punctuation, or any adjustments you had to make. Enter using your cataloging language.

**Obsolete procedures**: Older RISM cataloging guidelines allowed the symbols **?**, **+**, and **t** to represent standardized remarks. This practice was discontinued with the introduction of Muscat, and instead explanatory notes in natural language are put into the field **General note (031 $q)**. The symbols were the following:
- **?** = Error in the incipit could not be corrected.
- **+** = Error in the incipit has been corrected.
- **t** = The incipit has been transcribed into modern notation.


#### Scoring in movement (031 $z)

In this field, you can indicate the specific scoring for the particular movement in question (such as a movement within a complex vocal piece). List the scoring on one line using RISM instrument abbreviations and in the standard order (described in **Scoring summary [240 $m]**). Use a semicolon to separate instrument families.

##### Esempi:

- S (Enrico), T (Vanoldo); vl 1, 2, b; [winds]
- S 2 solo; Coro; ob obl; strings, bc
