# Openutau-Yaml-Dictionaries
Openutau Yaml Dictionaries for Arpasing, En VCCV, and Delta phonemizers to support Japanese, Korean, Chinese, and French (more languages to support soon)

`English to Japanese`, `English to Korean`, `English to Chinese`, and `English to French` (languages auxiliary support for now) for Arpasing, En VCCV, and Delta banks for [Openutau](https://www.openutau.com/) .yaml dictionaries, tweacked based on [Slidingwall's synth dictionary](https://github.com/Slidingwall/synthv-dictionaries).

#### 📍 As of now, the bigger the `.yaml` file, the slower Openutau changes the phonemes or any changes in general, as of Ou doesn't support yet the dictionary picking like on Synthv, for now, you can choose and download the single language dictionary or the compiled one.

## Credits
credits for [mmemim](https://github.com/mmemim) for the [Synthv French .json Dictionary](https://github.com/mmemim/OpenUTAU-French-Dictionary) and also credits [Halo/BagelHero](https://github.com/BagelHero) & Mim for the [Ou En VCCV Custom Dictionary](https://github.com/mmemim/OU-EN-VCCV-Custom-Dictionary)

- if there's any issue, and language request to support Openutau's dictionary, you can contact me through my [Twitter](https://twitter.com/cadlaxa).

#### 📍 There may be wrong entries and mispronunciation in the dictionary, please report them if so. Making your english voicebanks sings in different languages will still require phoneme editing as this lexicon is by no means a plug-and-play solution especially Korean, Chinese, and the French one.

⭐ The dictionaries are updated regularly so feel free to download the latest one [here]()or in this [mirror link](https://mega.nz/folder/BjhATYZb#s3dYIDZxlBRG7TF0QBG6Xw). ⭐

### Table of contents
- [How to download and install dictionaries on Windows](https://github.com/Cadlaxa/Openutau-Yaml-Dictionaries/edit/main/README.md#how-to-download-and-install-dictionaries-for-openutau)
- [How to use the dictionary + the suffix support](https://github.com/Cadlaxa/Openutau-Yaml-Dictionaries/edit/main/README.md#how-to-use-the-dictionary--the-suffix-support)
- [How to edit dictionary to fit a specific voicebank](https://github.com/Cadlaxa/Openutau-Yaml-Dictionaries/edit/main/README.md#how-to-edit-dictionary-to-fit-a-specific-voicebank)


## How to download and install dictionaries for Openutau

- To download any .yaml dictionary, click on the filename and then click on the download icon in the upper left corner of the file browser, as shown in the image below.
no img yet
-  Open your Openutau folder and go to `Plug-ins` folder. Drag and drop the yaml there and you are ready to go


![yamls](https://user-images.githubusercontent.com/92255161/216483581-7249910a-e9f1-4af0-ae3f-ac197c1250e9.png)


- Reload the english voicebank by choosing any phonemizers then back to the english one or changing voicebanks then going back again to the desired voicebank and you should now be able utilize the dictionary.

## How to use the dictionary + the suffix support

### Japanese Dictionary Usage
- You can input `Hiragana`, `Katakana` and `romaji c v` in the notes to utilize the japanese dictionary. It also supports the usage of `っ` eg: `っば`, `っいぇ`, `っしょ` and glottal stops on vowels eg: `あ2`, `い2`, `う2`, `え2`, `お2`, `ん2`

![Japanese Dictionary](https://user-images.githubusercontent.com/92255161/216487321-01cbc836-a4b1-4b4a-a368-29fa2eb18745.png)

### Korean Dictionary Usage
- You can input `Hanguul` and `Romaja` with `.` after the romaja word in the notes to utilize the Korean dictionary. Some have alternate pronunciations by inputing `1`, `2`, and `3` after the word. **Note that korean consonant assimilation is not supported because of the complex character-to-phoneme system with the `Hangul` input, so using `Romaja` to place consonants such as `ss.`, `p.`, `bb.` and so on the note.**

![Korean Dictionary](https://user-images.githubusercontent.com/92255161/216488297-f4c373c8-595f-4f10-9abf-31f09916cd62.png)

- **consonant assimilation**
![kr consonant assimilation](https://user-images.githubusercontent.com/92255161/216489533-014c19a7-f41f-4524-b5c7-92aed36601c2.png)

### Chinese Dictionary Usage
- Only `Pinyin` character with `/` after the word to utilize the Chinese dictionary.
 
![Chinese Dictionary](https://user-images.githubusercontent.com/92255161/216489976-4335a8b9-6b5e-407b-9e53-ea738bb194b9.png)


### French Dictionary Usage
- You can input `French`, with `*` after the word in the notes to utilize the French dictionary. Based with [mmemim's](https://github.com/mmemim) [Synthv French .json Dictionary](https://github.com/mmemim/OpenUTAU-French-Dictionary), If you want to say words like l'année or j'en you'll have to split them in two notes l' + année and j' + en as shown below.

![French Dictionary](https://user-images.githubusercontent.com/92255161/216492460-20da6e8a-940c-44e4-b115-3b4bfb727788.png)

![fr1](https://user-images.githubusercontent.com/92255161/216493122-26d897c0-3c19-4b3e-aeba-236e294ae08f.png)


- In French, you also have [liaisons](https://en.wikipedia.org/wiki/Liaison_(French)), and some words might not always be pronounced the same way. Because of that, you may sometimes need to put `word(2)`, `word(3)` or even `word(4)`. For example, `absentes` has 4 entries.

![WordEntries](https://i.imgur.com/MsXgO0o.png)

## How to edit dictionary to fit a specific voicebank
- Some voicebanks come with extra phonemes especially with En VCCV and Delta voicebanks, test out first the dictionary so you will know if its there are errors you will encounter like on this picture below:
![example](https://user-images.githubusercontent.com/92255161/216491969-82eb325e-9077-423d-97c6-2ab73f5b1caa.png)

- Editing the `.yaml` file via notepad or any other editing software you have to edit your desired phoneme per voicebank. I recommended to copy first one language then edit with the instructions inside the `.yaml` file

![vccv yaml](https://user-images.githubusercontent.com/92255161/216492284-95afa267-ead7-4703-9722-a7a0dba1084f.png)
