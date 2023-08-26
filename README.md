# Openutau Yaml Dictionaries
Openutau Yaml Dictionaries for Arpasing, En VCCV, Delta phonemizers, En Enunu, and En EnunuX/EnunuX to support Japanese, Korean, Chinese, and French (more languages to support soon)

 #### 📍 When using this dictionaries with Arpasing banks with few or missing phonemes especially with Arpasing 0.1.0 and 0.2.0 banks, I recommend using my [Syllable-Based ARPAsing Phonemizer]()

`English to Japanese`, `English to Korean`, `English to Chinese`, `English to Cantonese`,`English to French`, and `English to Spanish` (languages auxiliary support for now) for Arpasing, En VCCV, Delta banks, and Enunu/Enunux English banks for [Openutau](https://www.openutau.com/) .yaml dictionaries, tweaked based on [Slidingwall's synth dictionary](https://github.com/Slidingwall/synthv-dictionaries).

#### 📍 As of now, the bigger the `.yaml` file, the slower Openutau changes the phonemes or any changes in general, as of Ou doesn't supports yet the dictionary picking like on Synthv, for now, you can choose and download the single language dictionary or the compiled one. You can customize the dictionary as you please.

## Credits
credits for [mmemim](https://github.com/mmemim) for the [Synthv French .json Dictionary](https://github.com/mmemim/OpenUTAU-French-Dictionary). Credits to [Halo/BagelHero](https://github.com/BagelHero) & Mim for the [Ou En VCCV Custom Dictionary](https://github.com/mmemim/OU-EN-VCCV-Custom-Dictionary) and credits to [Lotte's](https://github.com/lottev1991) [Spanish cmudict](https://github.com/lottev1991/OpenUTAU-Spanish-Dictionary) for the en2sp base.
 - - - -
- if there's any issue on the dictionary, and language request to support Openutau's dictionary, you can contact me through my [Twitter](https://twitter.com/cadlaxa). Let me know if there's a problem tehee.

#### 📍 There may be wrong entries and mispronunciation in the dictionary, please report them if so. Making your english voicebanks sings in different languages will still require phoneme editing as this lexicon is by no means a plug-and-play solution especially Korean, Chinese, French and the Spanish.

⭐ The dictionaries are updated regularly so feel free to download the latest one [here](https://github.com/Cadlaxa/Openutau-Yaml-Dictionaries.git) or in this [mirror link](https://mega.nz/folder/BjhATYZb#s3dYIDZxlBRG7TF0QBG6Xw). ⭐

### Table of contents
- **[How to download and install dictionaries on Windows](https://github.com/Cadlaxa/Openutau-Yaml-Dictionaries#how-to-download-and-install-dictionaries-for-openutau)**
- **[How to use the dictionary + the suffix support](https://github.com/Cadlaxa/Openutau-Yaml-Dictionaries#how-to-use-the-dictionary--the-suffix-support)**
    - **[Japanese](https://github.com/Cadlaxa/Openutau-Yaml-Dictionaries#japanese-dictionary-usage)**
    - **[Korean](https://github.com/Cadlaxa/Openutau-Yaml-Dictionaries#korean-dictionary-usage)**
    - **[Chinese](https://github.com/Cadlaxa/Openutau-Yaml-Dictionaries#chinese-dictionary-usage)**
    - **[Cantonese](https://github.com/Cadlaxa/Openutau-Yaml-Dictionaries#cantonese-dictionary-usage)**
    - **[French](https://github.com/Cadlaxa/Openutau-Yaml-Dictionaries#french-dictionary-usage)**
    - **[Spanish](https://github.com/Cadlaxa/Openutau-Yaml-Dictionaries#spanish-dictionary-usage)**
- **[How to edit dictionary to fit a specific voicebank](https://github.com/Cadlaxa/Openutau-Yaml-Dictionaries#how-to-edit-dictionary-to-fit-a-specific-voicebank)**

 - - - -
## How to download and install dictionaries for Openutau

- To download any .yaml dictionary, click on the filename and then click on the download icon in the upper left corner of the file browser, as shown in the image below.

![dl](https://user-images.githubusercontent.com/92255161/216503673-be812287-8c2f-42f8-82dd-a108b9eceb52.png)

- If it doesn't show up like that, click Raw...


![dl2](https://user-images.githubusercontent.com/92255161/216503748-3cfe3a8e-33ff-4213-9cf5-7e741f78baa0.png)

- Then right click, and click save as...


![dl3](https://user-images.githubusercontent.com/92255161/216503826-ba5c7f96-dcbe-4022-91d1-99b5e4a140ef.png)

- Rename the extension to `.yaml` not `.txt` then save


![dl4](https://user-images.githubusercontent.com/92255161/216503933-00dbda4e-d280-4f4f-84e2-e9f08f753a16.png)

-  Open your Openutau folder and go to `Plug-ins` folder. Drag and drop the yaml there and you are ready to go

![yamls](https://user-images.githubusercontent.com/92255161/216483581-7249910a-e9f1-4af0-ae3f-ac197c1250e9.png)


- Reload the english voicebank by choosing any phonemizers then back to the english one or changing voicebanks then going back again to the desired voicebank and you should now be able utilize the dictionary. If it doesn't load up, close and reopen [OpenUtau](https://www.openutau.com/)
 - - - -
## How to use the dictionary + the suffix support

### Japanese Dictionary Usage
- You can input `Hiragana`, `Katakana` and `romaji c v` in the notes to utilize the japanese dictionary. It also supports the usage of `っ` eg: `っば`, `っいぇ`, `っしょ` and glottal stops on vowels eg: `あ2`, `い2`, `う2`, `え2`, `お2`, `ん2`

![Japanese Dictionary](https://user-images.githubusercontent.com/92255161/216487321-01cbc836-a4b1-4b4a-a368-29fa2eb18745.png)

### Korean Dictionary Usage
- You can input `Hanguul` and `Romaja` with `.` after the romaja word in the notes to utilize the Korean dictionary. Some have alternate pronunciations by inputing `1`, `2`, and `3` after the word. **Note that [korean consonant assimilation](https://www.koreanwikiproject.com/wiki/Category:Consonant_assimilation#:~:text=Consonant%20assimilation%20is%20when%20the,or%20both%20of%20them%20changes.&text=1.,becomes%20%2F%E3%84%B4%2B%E3%84%B4%2F.) is not supported because of the complex character-to-phoneme system with the `Hangul` input, so using `Romaja` to place consonants such as `ss.`, `p.`, `bb.` and so on the note.**

![Korean Dictionary](https://user-images.githubusercontent.com/92255161/216488297-f4c373c8-595f-4f10-9abf-31f09916cd62.png)

- **consonant assimilation**
![kr consonant assimilation](https://user-images.githubusercontent.com/92255161/216489533-014c19a7-f41f-4524-b5c7-92aed36601c2.png)

### Chinese Dictionary Usage
- Only `Pinyin` characters with `/` after the word to utilize the Chinese dictionary. Multiple pronunciations now supported. eg: `ra/1` as `[zh, ah]`, `chun/` as `[ch, w, ax, n]`, `chun/1` as `[ch, uw, n]`
 
![Chinese Dictionary](https://user-images.githubusercontent.com/92255161/216489976-4335a8b9-6b5e-407b-9e53-ea738bb194b9.png)
- Multiple pronunciation variations

![ch new](https://user-images.githubusercontent.com/92255161/222963424-75319578-a70f-4222-816e-4246a95bbae5.png)

### Cantonese Dictionary Usage
- Only `Jyutping` characters with `\` after the word to utilize the Cantonese dictionary. Multiple pronunciations aresupported. eg: `yuk\` as `[y, ih, k]`, `yuk\1` as `[y, k]`, `byui\1` as `[b, y, ih]`, `byui\1` as `[b, y, iy]`.

![canto](https://user-images.githubusercontent.com/92255161/235335471-fa60737a-cdc4-4711-9f34-cb5762d30da6.png)

### French Dictionary Usage
- You can input `French`, with `*` after the word in the notes to utilize the French dictionary. Based with [mmemim's](https://github.com/mmemim) [Synthv French .json Dictionary](https://github.com/mmemim/OpenUTAU-French-Dictionary), If you want to say words like l'année or j'en you'll have to split them in two notes l' + année and j' + en as shown below.

![French Dictionary](https://user-images.githubusercontent.com/92255161/216492460-20da6e8a-940c-44e4-b115-3b4bfb727788.png)

![fr1](https://user-images.githubusercontent.com/92255161/216493122-26d897c0-3c19-4b3e-aeba-236e294ae08f.png)


- In French, you also have [liaisons](https://en.wikipedia.org/wiki/Liaison_(French)), and some words might not always be pronounced the same way. Because of that, you may sometimes need to put `word(2)`, `word(3)` or even `word(4)`. For example, `absentes` has 4 entries.

![WordEntries](https://i.imgur.com/MsXgO0o.png)

### Spanish Dictionary Usage
- You can input `español` with `~` after the spanish word in the notes to utilize the Spanish dictionary. **Note that rolled r's or `rr` doesn't support by default on the dictionary itself, if your voibecank have a rolled r extras, you can add them to the dictionary by specifying the phoneme to the symbol list and replacing the `dx, dx` phoneme with the rolled r phoneme. If your vb doesn't have rolled r extras, you can find a way to do them, mine I just add as many `r q r q` or `r/dx` then glottals to the rolled r part of the word**
![spa 2](https://user-images.githubusercontent.com/92255161/222963332-be424bc0-88eb-4aee-86d1-43fb048191fd.png)
- Rolled r's with r's and glottal magic ✨✨
![spa rr](https://user-images.githubusercontent.com/92255161/222963387-f97f236e-12c3-4e73-9adb-76d78a37d12e.png)

- **also words without accent doesn't work eg: `útiles~` and you typed `utiles~`, ou will output the english pronunciation eg: `utiles~` to `[y, uw, t, ah/ax, l, z]` so it is important to add the symbol accents. If this feature is annoys you (also myself as well lmao) just let me know, I'll make a variant without the symbol accents**

 - - - -
## How to edit `.yaml` dictionary to fit a specific voicebank
- Some voicebanks come with extra phonemes especially with En VCCV and Delta voicebanks, test out first the dictionary so you will know if its there are errors you will encounter like on this picture below:
![example](https://user-images.githubusercontent.com/92255161/216491969-82eb325e-9077-423d-97c6-2ab73f5b1caa.png)

- Editing the `.yaml` file via notepad or any other editing software you have to edit your desired phoneme per voicebank. I recommended to copy first one language then edit with the instructions inside the `.yaml` file

- If it doesn't work, batch rename your vb's oto or wait for the dev team to make an phoneme fallback to fix the issue.

![vccv yaml](https://user-images.githubusercontent.com/92255161/216492284-95afa267-ead7-4703-9722-a7a0dba1084f.png)
