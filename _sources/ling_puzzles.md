# Linguistic puzzles

This page contains linguistic puzzles grouped by topic. I am not the author of these puzzles! I use them in the 'Linguistics for Language Technology' course as a tool for practicing linguistic analysis: inferring underlying rules and structures from linguistic data.



## Puzzle 1: Stress in Muscogee


`````{margin}
Puzzle by Aleksey Pegushev.
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
`````

