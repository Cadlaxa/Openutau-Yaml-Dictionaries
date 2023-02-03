# Openutau-Yaml-Dictionaries
Openutau Yaml Dictionaries for Arpasing, En VCCV, and Delta phonemizers to support Japanese, Korean, Chinese, and French (more languages to support soon)

`English to Japanese`, `English to Korean`, `English to Chinese`, and `English to French` (languages auxiliary support for now) for Arpasing, En VCCV, and Delta banks for [Openutau](https://www.openutau.com/) .yaml dictionaries, tweacked based on [Slidingwall's synth dictionary](https://github.com/Slidingwall/synthv-dictionaries).

#### 📍 As of now, the bigger the `.yaml` file, the slower Openutau changes the phonemes or any changes in general, as of Ou doesn't support yet the dictionary picking like on Synthv, for now, you can choose and download the single language dictionary or the compiled one.

## Credits
credits for [mmemim](https://github.com/mmemim) for the [Synthv French .json Dictionary](https://github.com/mmemim/OpenUTAU-French-Dictionary) and also credits [Halo/BagelHero](https://github.com/BagelHero) & Mim for the [Ou En VCCV Custom Dictionary](https://github.com/mmemim/OU-EN-VCCV-Custom-Dictionary)

if there's any issue, and language request to support Openutau's dictionary, you can contact me through my [Twitter](https://twitter.com/cadlaxa).

#### 📍 There may be wrong entries and mispronunciation in the dictionary, please report them if so. Making your english voicebanks sings in different languages will still require phoneme editing as this lexicon is by no means a plug-and-play solution especially Korean, Chinese, and the French one.

⭐ The dictionaries are updated regularly so feel free to download the latest one [here]()or in this [mirror link](https://mega.nz/folder/BjhATYZb#s3dYIDZxlBRG7TF0QBG6Xw). ⭐

### Table of contents
- [How to download and install dictionaries on Windows](https://github.com/mmemim/SynthV-FrenchDictionary#how-to-download-install-dictionaries-on-windows)
- [How to use the dictionary + the suffix support](https://github.com/mmemim/SynthV-FrenchDictionary#how-to-use-the-dictionary)
- [How to edit the phonemes to fit a specific voicebank](https://github.com/mmemim/SynthV-FrenchDictionary#how-to-add-a-word)
- [Phoneme table](https://github.com/mmemim/SynthV-FrenchDictionary#phoneme-table)
- [FAQ](https://github.com/mmemim/SynthV-FrenchDictionary#faq)
- [Wiki](https://github.com/mmemim/SynthV-FrenchDictionary/wiki)


## How to download and install dictionaries for Openutau

- To download any .yaml dictionary, click on the filename and then click on the download icon in the upper left corner of the file browser, as shown in the image below.

![dictionaryDL](https://i.imgur.com/hKnkNCB.png)



-  Open SynthV and load the voice you want to use with the dictionary you downloaded. In the `Dictionary`panel, click on `New...` and then name the dictionary with the same name as the .json file (`CHN2FRA`, `ENG2FRA`, `JPN2FRA` or `ANY2FRA`). Make sure the language and phonemes match with your dictionary. The `ANY2FRA` dictionary can be used with any language or phonemes.

![CreateDictionary](https://i.imgur.com/XwpXmlU.png)

- You can now drag and drop the .json file in the `mandarin-xsampa`, `japanese-romaji` or `english-arpabet` folder in your Synthesizer V install, the path should be `Dreamtonics/Synthesizer V/dicts/language-alphabet`. The `ANY2FRA` dictionary can be dropped in every folder.

![DictionaryFolder](https://i.imgur.com/Wc8jn3S.png)

- Reload Synthesizer V and you should now be able to select your dictionary.

## How to add a word

If you want to add a word to the dictionary, please add it to the [Open Utau Dictionary](https://github.com/mmemim/OpenUTAU-French-Dictionary#how-to-add-a-word). You can also request words to be added [here](https://github.com/mmemim/SynthV-FrenchDictionary/issues/1).

## How to use the dictionary

You can type a word in French and split it in syllables with `+`. Because of the way Synth V handles syllables in Chinese, you'll have to add additional splits for CCs as shown below.

![WordSplitting](https://i.imgur.com/QoQ5RSi.png)

If you want to say words like `l'année` or `j'en` you'll have to split them in two notes `l'` + `année` and `j'` + `en` as shown below.

![WordCombination](https://i.imgur.com/6zxP6SR.png)

In French, you also have [liaisons](https://en.wikipedia.org/wiki/Liaison_(French)), and some words might not always be pronounced the same way. Because of that, you may sometimes need to put `word(2)`, `word(3)` or even `word(4)`. For example, `absentes` has 4 entries.

![WordEntries](https://i.imgur.com/MsXgO0o.png)

With the ANY2FRA dictionary, you can switch between Chinese, English & Japanese phonemes. You just need to add `*` for Japanese or `$` for English.

![ANY2FRA](https://i.imgur.com/eMq2Nda.png)

## Phoneme table

Here is a table of the phonemes used for conversion in both dictionaries (in bold), additional phonemes are added.
For more information on each phoneme you can consult the wiki (WIP).

| [IPA](https://en.wikipedia.org/wiki/Help:IPA/French) | Chinese X-SAMPA | English Arpabet | French Arpabet |
| ------------- | ------------- | ------------- | ------------- |
| a/ɑ : p**a**tte | a | ah | aa |
| e : cl**é** | e | **ih**/eh | ei |
| ɛ/ɛ: : b**ai**e | e | ae | ai |
| ə/ø : r**e**poser,  c**eu**x | 7/@ | uh | ee/eu |
| œ :  s**œu**r | **A**/@ | ax | oe |
| i : s**i** | i | **iy**/ih | ii |
| o : s**au**t | iU | ow | au |
| ɔ : p**o**mme | o | ao | oo |
| u : c**ou**p | u | uw | ou |
| y : r**u**e | y | **uh**/uw | uu |
| ɑ̃ : s**an**g, v**en**t | A N | aa ng | an |
| ɛ̃/œ̃ : v**in**, **un** | **7 n:**/7 N | ah ng | in/un |
| ɔ̃ : s**on** | o N | ao ng | on |
| b : **b**as | p | b | bb |
| d : **d**eux | t | d | dd |
| f : **f**aire | f | f | ff |
| g : **g**arçon | k | g | gg |
| k : **c**orps | kh | k | kk |
| l : **l**aisser | l | l | ll |
| m : **m**a | m | m | mm |
| ɲ : champa**gn**e | n j | n y | gn |
| ŋ : campi**ng** | N\:n | ng | unused |
| p : **p**ère | ph | p | pp |
| ʁ : **r**ega**r**der | x | hh | rr |
| s : **s**ans | s | s | ss |
| ʃ : **ch**ance | s` | sh | ch |
| t : **t**out | th | t | tt |
| v : **v**ous | f | v | vv |
| z : **z**éro | ts | z | zz |
| ʒ : **j**amais | ts` | zh | jj |
| j : pa**y**er | j | y | yy |
| w : **ou**i | w | w | ww |
| ɥ : h**ui**t | y | **uw**/uh | uy |

## FAQ

To be updated
