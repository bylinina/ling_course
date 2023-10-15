# Appendix: Linguistic puzzles

This page contains three linguistic puzzles grouped by topic: phonetics/phonology, morphology, syntax. I am not the author of these puzzles! I use them in my course as a tool for practicing linguistic analysis: inferring underlying rules and structures from linguistic data. These puzzles are one of several activities offered during seminars / practical sessions. The puzzles appeared online in collections of linguistic puzzles (in Russian) and I translated them into English and leave them here as examples of student activity for different topics. If you are a teacher reading this and want to use these puzzles, make sure to attribute them correctly (not to me!); and if you think I should take them down, let me know and I will!


## Puzzle 1: Stress in Muscogee


`````{margin}
Puzzle by Aleksey Pegushev ([source](https://elementy.ru/problems/1885/Krik_dushi))
`````

This puzzle is linked to the topic of weeks 2 and 3 'Transmitting and capturing language'. Here, you will be given (limited) linguistic data, and your task is to uncover a rule that explains these data. Moreover, the data is unlocked in three portions, each new portion of data challenging your previous generalization. The language this puzzle focusses on is the [Muscogee language](https://en.wikipedia.org/wiki/Muscogee_language), a language that has roughly 5000 speakers and belongs to the Muskogean language family in North America. Presumably, this is a language you don't know much or anything about. That's the whole point! Existing Large Language Models also don't have any knowledge about Muscogee and actually weren't able to solve this puzzle last time I checked. Enjoy! 

### Problem 1

```{toggle}
Look at the following several words in the Muscogee language with stress marked: 

|            |
|:----------:|
| _cokó_ 'house' |
| _yanása_ 'bison' |
| _iyanawá_ 'his/her cheek' |
| _imahicíta_ 'to look out for' |
| _lafotaháya_ 'melon' |
| _itiwanayipíta_ 'to tie each other down' |



Mark stress on the following words: 

|            |
|:----------:|
| _ifa_ 'dog' |
| _ifoci_ 'puppy' |
| _wanayita_ 'to knit' |
| _awanayita_ 'to tie' |


```

### Problem 2

```{toggle}

Here are more Muscogee words with stress marked: 

|            |
|:----------:|
| _sókca_ 'bag' |
| _pocóswa_ 'axe' |
| _aktopá_ 'bridge' |
| _akkopánka_ 'game' |
| _inkosapitá_ 'to beg' |
| _acahankatíta_ 'to consider me' |
| _pokkałakkoaopankacóko_ 'basketball gym' |


Mark stress on the following words: 

|            |
|:----------:|
| _hoktaki_ 'women' |
| _isiskitoci_ 'small glass' |
| _ilitohtałita_ 'to cross legs' |

Did you have to revise the stress rules you found in Problem 1 in order to finish the task?

```

### Problem 3

```{toggle}

Here are even more Muscogee words with stress marked: 

|            |
|:----------:|
| _cá\:lo_ 'trout' |
| _wa\:kocí_ 'calf' |
| _famí\:ca_ 'pumpkin' |
| _hî\:spákwa_ 'American robin' |
| _aklowahí_ 'mud' |
| _tapassó\:la_ 'cellar spider' |
| _tokna\:photí_ 'wallet' |
| _co\:kakiłłitá_ 'study' |
| _cokpilâ\:pilá_ 'nightjar' |


Mark stress on the following words: 

|            |
|:----------:|
| _nâ\:naki_ 'things' |
| _sâ\:sakwa_ 'goose' |
| _a\:tamihoma_ 'hood' |
| _homanta\:ki_ 'men' |


Did you have to revise the stress rules you found in Problem 2 in order to finish the task?

**Note**: _ł_ is a consonant; the hat over a vowel (e.g. _â_) marks falling tone; vowel length is marked with a colon (e.g. _a\:_).

```

`````{admonition} Hint 1
:class: tip, dropdown
Count the number of syllables in the first group of words.
`````

`````{admonition} Hint 2
:class: tip, dropdown
The basic rule remains the same, but the second and the third group of words provide data to make it more precise.
`````

`````{admonition} Hint 3
:class: tip, dropdown
In order to formulate this more precise rule, try to figure out what makes word structure in each of the groups unique.
`````

`````{admonition} Solution
:class: danger, dropdown

I hid the solutions for now. Contact me if you want to get them.
<!---
**Problem 1 solution**

Let's start with the first group of words only. We notice immediately that stress is somewhere close to the end of the word -- either the last or the penultimate syllable. But how do we know which one of those? Let's count the number of syllables in each of the words (I'll put the number in parentheses):

Stress on the last syllable: _cokó_ (2), _iyanawá_ (4)
Stress on the penultimate syllable: _yanása_ (3), _imahicíta_ (5), _lafotaháya_ (5), _itiwanayipíta_ (7)

Words with even number of syllables have stress on the final syllable, the ones with odd number of syllables get stress on the penultimate one. We can formulate a rule that puts stress on the last even syllable of the word. Then this will be the answer to Problem 1: _ifá_, _wanayitá_, _ifóci_, _awanayíta_


**Problem 2 solution**

When the second group of words is introduced, we see that our rule does not work anymore. For example, the 2-syllable word _sókca_ has stress on the first syllable, not on the second one. Can we revise the rule so that it explains the new portion of data? The first thing to notice is that there's something different about the new group of words compared to the first one. Namely, the first group contained only words in which each consonant is followed by a vowel, while in the second group there are clusters of consonants, which give rise to closed syllables (the first consonant of the cluster belongs to the previous syllable, which is then a 'closed syllable' -- closed by the consonant). Let's count syllables in words as before:

Stress on the last syllable: _aktopá_ (3), _inkosapitá_ (5)
Stress on the penultimate syllable: _sókca_ (2), _pocóswa_ (3), _akkopánka_ (4), _acahankatíta_ (6), _pokkałakkoaopankacóko_ (10)

One thing to notice is that whenever the closed syllable is the penultimate one, it has stress on it. This observation leads us to connect the 'closed' status of the syllable to where stress is put. Let's make another observation: all final-stress words in this group have odd number of syllables -- which is the opposite of the generalization about the first group of words. They also have closed syllables in the very first position. Let's put it this way: if the initial closed syllable didn't exit, the stress would go to the last even syllable. Does this generalise to the words of this group with stress on the penultimate syllable? Yes, if we formulate it like this: the stress falls on the last even syllable of the word assuming that closed syllables restart the count (are position 0).

Now we can solve problem 2: _hoktakí_, _isiskitóci_, _ilitohtałíta_

**Problem 3 solution**

In the third group, long vowels appear. Syllables with long vowels behave exactly like closed syllables, restarting the syllable count. We can now solve problem 3 as well: _nâ:nakí_, _a:tamihomá_, _sâ:sákwa_, _homantá:ki_

**The final rule** says: The stress falls on the last even syllable of the word, assuming that the last closed syllable or syllable with a long vowel restarts the count.


**P.S.** Why is this rule so complicated? In fact, there is a way to formulate the rule in a more simple way, but it would involve notions like **mora** and **prosodic foot**, which we haven't covered in the lecture. In these terms, the stress falls on the last syllable of the final full foot of the word, where a foot is either one 2-moraic syllable or two 1-moraic ones! 
--->
`````

## Puzzle 2: Imperatives in Arabic

This puzzle is related to the topic of Week 4: Morphology. It allows you to dive deeper into morphological analysis of a set of forms that combine a verbal stem and different verbal affixes -- and as a result, given the data, you come up with a rule behind these combinations. This is a direct extension of what we talked about in class.

`````{margin}
Puzzle by Anton Somin ([source](https://elementy.ru/problems/1324/Kolenopreklonennyy_verblyud))
`````

The table below contains verbs in Arabic in different forms, all of them 2nd person singular: 

- indicative present tense singular masculine (as in 'you [masc.] are spinning'), glossed IND.PRS.2.SG.M; 
- imperative singular masulune (as in 'spin! [masc.]'), glossed IMP.2.SG.M;
- imperative singular feminine (as in 'spin! [fem.]'), glossed IMP.2.SG.F.

The forms are given in simplified transcription. Some forms are missing, with corresponding cells containing question marks.



|     IND.PRS.2.SG.M     |     IMP.2.SG.M       |     IMP.2.SG.F       |      translation      |
|:----------:|:----------:|:----------:|:----------:|
| _tadūru_ | _dur!_ | _dūrī!_ | spin |
| _taktubu_ | _'uktub!_ | _'uktubi!_ | write |
| _tamšī_ | _'imši!_ | _'imšī!_ | go |
| _taqsimu_ | _'iqsim!_ | _'iqsimī!_ | split |
| _tarğū_ | _'urğu!_ | _'urğī!_ | hope |
| _tasmaʕu_ | _'ismaʕ!_ | _'ismaʕī!_ | listen |
| _tastabriku_ | _'istabrik!_ | _'istabrikī!_ | make camel kneel |
| _tarīmu_ | _rim!_ | ? | leave |
| _tarmī_ | _'irmi!_ | ? | throw |
| _tanāmu_ | ? | _nāmī!_ | sleep |
| ? | _fi!_ | ? | carry out |
| _tadʕū_ | ? | ? | call |

**Note**: line over the vowel marks long vowels; ğ, ḫ, q, š, ṯ, ', ʕ are consonants.

### Problem 1

```{toggle}
Fill in the missing forms. Explain your solution.
```

### Problem 2

```{toggle}
Do the same for the following verbs:

|     IND.PRS.2.SG.M     |     IMP.2.SG.M       |     translation      |
|:----------:|:----------:|:----------:|
| _tafqišu_ |  ? | break |
| _taktariṯu_ | ? | take care |
| _taḫruğu_ | ? | go out |

```

`````{admonition} Hint
:class: tip, dropdown

In order to solve this puzzle, you need to answer three main questions:
1. In what case does the imperative verb get a prefix?
2. In what case this prefix will be _'i-_ and when is it _'u-_?
3. When do long vowels become short vowels?
`````


`````{admonition} Solution
:class: danger, dropdown

I hid the solutions for now. Contact me if you want to get them.
<!---
When building imperative masculine forms (2nd column) from indicative forms (1st column), the following things are happening:
- prefix _ta-_ is deleted;
- if the remaining part of the verb starts with **two consonants**, the imperative will have a prefix: either _'u-_ or _'i-_. Otherwise, the prefix is not needed. The choice of the prefix depends on the vowel in the root (including the final long vowels): if the vowel in the root is _u_, then _'u-_ is chosen; if the vowel is _a_ or _i_, then the prefix will be _'i-_;   
- if the verb ends in short _-u_, this vowel is dropped;
- long vowels become short vowels: both in the middle of the word (_tad**ū**ru_ \> _d**u**r!_) and at the end (_tarğ**ū**_ \> _'urğ**u**!_; _tamš**ī**_ \> _'imš**i**!_). This does not depend on whether the prefix is needed in this form.

Imperative feminine forms (3rd column) are formed from the imperative masuline forms (2nd column) by adding the suffix _-ī_: _'uktub!_ \> _'uktubī!_. Additionally, the vowel in the root that was long in the indicative form and lost its length during the formation of the imperative masculine form, becomes long again: _tad**ū**ru_ \> _d**ur**!_ \> _d**ū**rī!_. Finally, if the indicative form of the word ends in a long vowel (**ū** or **ī**) that become short in the corresponding imperative masculine form, then in the corresponding imperative feminine form this vowel will be replaced by the suffix _-ī_:  _tarğ**ū**_ \> _'urğ**u**!_ \> _'urğ**ī**!_; _tamšī_ \> _'imši!_ \> _'imšī!_.

Now we can fill in the gaps in the tables.

**Problem 1 solution**

|     IND.PRS.2.SG.M     |     IMP.2.SG.M       |     IMP.2.SG.F       |      translation      |
|:----------:|:----------:|:----------:|:----------:|
| _tarīmu_ | _rim!_ | _rīmī!_ | leave |
| _tarmī_ | _'irmi!_ | _'irmī!_ | throw |
| _tanāmu_ | _nam!_ | _nāmī!_ | sleep |
| _tafī_ | _fi!_ | _fī!_ | carry out |
| _tadʕū_ | _'udʕu!_ | _'udʕī!_ | call |


**Problem 2 solution**

|     IND.PRS.2.SG.M     |     IMP.2.SG.M       |     translation      |
|:----------:|:----------:|:----------:|
| _tafqišu_ |  _'ifqiš!_ | break |
| _taktariṯu_ | _'iktariṯ!_ | take care |
| _taḫruğu_ | _'uḫruğ!_ | go out |
--->

`````

## Puzzle 3: Simple sentences in Straits Salish

This puzzle is meant to give hands-on experience in analyzing the structure of simple sentences, and in this it connects mostly to the topic of Week 6: Syntax. The puzzle is based on data from [Straits Salish](https://en.wikipedia.org/wiki/North_Straits_Salish_language) -- a language with a very different syntax from the familiar languages of the European standard. 

`````{margin}
Puzzle by Peter Arkadiev ([source](https://elementy.ru/problems/1404/Ya_vizhus_vorom))
`````
The table below contains sentences in Straits Salish and their English translations.

|      |          |        |
|:----------:|:----------:|:----------:|
| 1. |   t'iləm-sx<sup>w</sup> | You sing.  |
| 2. | čey cə swiʔqoʔəɫ | The lad works. |
| 3. | leŋt-sx<sup>w</sup> cə qen'qən' | You see the thief. |
| 4. | leŋtŋ-sən ʔə cə qen'qən' | The thief sees me. |
| 5. | ʔətat-sən | I sleep. |
| 6. | qen'qən' cə ʔətat | The one who sleeps is a thief. |
| 7. | t'iləm cə swəy'qəʔ | The man sings. |
| 8. | χčətŋ-sx<sup>w</sup> ʔə cə čey | The one who works recognizes you. |
| 9. | t'əm't-sən cə ʔətat | I hit the one who sleeps. |
| 10. | ɫəɫik<sup>w</sup> cə sɫeniy' | The woman hurries. |

### Problem 1

```{toggle}
Translate into English:

11. qen'qən'-sx<sup>w</sup>
12. t'əm'tŋ-sən ʔə cə sɫeniy'
13. χčət-sx<sup>w</sup> cə t'iləm
```


### Problem 2

```{toggle}
Translate into Straits Salish:

14. I am a man.
15. The one who hurries sleeps.
16. The lad sees you.
```

`````{admonition} Hint 1
:class: tip, dropdown
Pay attention to word order in Straits Salish.
`````

`````{admonition} Hint 2
:class: tip, dropdown
What do counterparts of _I_, _me_, _you_ look like in Straits Salish look like?
`````


`````{admonition} Solution
:class: danger, dropdown


I hid the solutions for now. Contact me if you want to get them.

<!---

Comparing sentences 1 and 7, 2 and 8, 5 and 6, you might notice that word order in Straits Salish is not like in English: the verb comes first, after that comes the subject or the object, and if the subject or object is the 1st or 2nd person, it's not expressed as a separate word, but combines with the verb as a suffix: 1P is _-sən_, 2P is _-sx<sup>w</sup>_. If the subject or object is not 1P/2P, it is preceding by _cə_. So, for instance, in sentence 10 _ɫəɫik<sup>w</sup>_ is 'hurries' and _sɫeniy'_ is 'woman'.

Comparing sentences 3, 4 and 6, as well as 5 and 6 and 2 and 8, you can see that Straits Salish does not have a formal distinction between verbs and nouns: all open-class words can appear in the verbal position and in the nominal position without any derivational morphology. In sentence 5 the word _ʔətat_ 'sleep' is the verb, appears in the initial position in the sentence and takes the 1P suffix _-sən_. In sentences 6 and 9 the same word appears in the second position after _cə_ as subject and object, respectively. In those cases we translate it involving a construction 'the one who..'.

Comparing sentences 3 and 9 with sentences 4 and 8 (as well as sentence 9 with sentence 12 and sentence 8 with sentence 13), one can notice that when 1P/2P is the object in the English translation and the full noun is the subject, in Straits Salish the 1P/2P suffix still attaches to the verb as in cases when it corresponds to the subject in English (compare _leŋtŋ-**sən**_ 'sees **me**' and _t'əm't-**sən**_ '**I** hit'), the verb gets suffix _-ŋ-_ (compare _**leŋtŋ**-sən_ 'sees me' and _**leŋt**-sx<sup>w</sup>_ 'you see') and the full noun that corresponds to the subject in the English translation is preceded by preposition _ʔə_. In other words, sentences with 1P/2P corresponding to the object in English are translated into Straits Salish as a passive construction, quite like English 'I was seen by the woman' (vs. 'The woman sees me'): the object becomes the subject, the old subject is preceded by a preposition, the verb also changes to the form used in passive constructions. 

Here is how sentence structure works in Straits Salish:

- Intransitive (1-participant) verb + 1P/2P suffix (subject) (1, 5);
- Intransitive verb + _cə_ + subject (2, 6, 7, 10);
- Transitive (2-participant) verb + 1P/2P suffix (subject) + _cə_ + object (3, 9);
- Transitive verb + _ŋ_ + 1P/2P suffix (object) + _ʔə_ + _cə_ + subject (4, 8).

Now we can solve the problems. 

**Problem 1 solution**

11. qen'qən'-sx<sup>w</sup>: 'You are a thief' (thief-2P)
12. t'əm'tŋ-sən ʔə cə sɫeniy': The woman hits me (hit.PASS-1P PREP ART woman)
13. χčət-sx<sup>w</sup> cə t'iləm: You recognize the one who sings (recognize-2P ART sing)



**Problem 2 solution**

14. I am a man: swəy'qəʔ-sən (man-1P)
15. The one who hurries sleeps: ʔətat cə ɫəɫik<sup>w</sup> (sleep ART hurry)
16. The lad sees you: leŋtŋ-sx<sup>w</sup> ʔə cə swiʔqoʔəɫ (see.PASS-you PREP ART lad)

--->

`````


