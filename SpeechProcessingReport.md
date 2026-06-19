# Indian Languages 

India comprises of over 120 languages and dialects 

Union/Central government have English & Hindi as official languages 

Indian constitution recognizes 22 official languages: 

1. Hindi 
2. Bengali 
3. Tamil 
4. Telugu 
5. Kannada 
6. Malayalam 
7. Marathi 
8. Urdu 
9.  Gujarati 
10. Konkani 
11. Punjabi 
12. Odia 
13. Sanskrit 
14. Sindhi 
15. Maithili 
16. Kashmiri 
17. Assamese 
18. Dogri 
19. Nepali 
20. Bodo 
21. Manipuri 
22. Santali 

## Why does the language matter in speech-processing? 

Every language has different: 
* Grammar 
* Vocabulary 
* Writing systems(scripts) 
* Sounds 

This matters in processes like Speech -> Text, Text-> Speech, or something as simple as language identification. 

Also, Indian languages (Indic) are low-resources languages as the models used for processing have low training data. 

## Hockett's Design Features
Hocket's design features of language(1960),proposed by Charles F. Hockett, are a set of 13 characteristics(framework) used to distinguish human language from communication systems(like animal signals):

* Communication System: Organized methoed to transfer information
* Human Language: Highly complex communication system with special properties

1. **Duality of Patterning**:
  * In Human language, there are two levels of patterning/structure:
    *  compounding of words/morphemes(primary level)
    *  compounding of sounds/phonemes(secondary level)
  Animals communication consists of meaningful cries and signals but cannot be broken down/patterned into smaller words/syllables
2. **Creativity**
  * With various ways of combining units of language, keeping the laws of language construction in mind(clauses, sentences etc.), we can get creative with formation as sentences within sentences can occur(*recursiveness*).
    * e.g. "This is the cow with crumples horns *that* tossed the dog *that* tossed the ..."
  * Animal signals, however don't offer much creative space or recursiveness
  * Human language is an '*open-ended system*'
  * e.g. Jokes, Idioms like Hungry + Angry = 'Hangry'
3. **Arbitrariness**
   * There is no inherent relation between the word and it's meaning
     * e.g. We call a particular creature dog just because it's convention. No other reason/relation to the actual creature or meaning in general
4. **Displacement**
   * Animal communication is '*content-bound*' while Human communication is '*content-free*'.
   * Human beings can talk about experiences they have not necessarily lived. Can change betweem tenses(past,present, future), unlike Animals whose signals as communication are only a response to the current,immediate stimulus
   * Animals are not capable of coming to an agreement as to certain signals/symbols/sounds to indicate a particular situation/meaning
   * e.g. Human beings can ask for what food they want but animals can only indicate that they're hungry
5. **Redundancy**
   * e.g. 1. 'The dogs are running'. In this sentence, it is obvious that it is a plural number of dogs, so why 'are' again?
   * e.g. 2. 'Is he still there?'.  The iterrogation is intended by both, the helping word 'Is' and the rising tone in speech(along with interrogation mark in terms of speech). Instead writing, 'he still ther' would be enough to convey meaning (similarly with 'She is going.' 'She going' would be just enough to convey meaning.)
   * BUT the redundancy(different from repetition which is more intendede.g. come here, come here!) allows communication to survive noise, errors,pronunciation differences, grammar etc.
6. **Culture-preserving and Culture-transmitting features**
   * Language(majorly), along with architecture, painting, music etc. prevent culture from dieing down(preserve) and passes it onto future generations.
7. **Dynamic**
  * Language keeps changing and adapting generation by generation to meet the needs and demands of the people using it.
  
**NOTE:** 
* Human language (major communication system for humans) is different from other communication systems due to human brains' wiring and composition being different to animals. Humans have a capacity of learning languages creatively.  
* Artificial languages like Morse Code(more like a representatin system), are closed systems as:
    * Semantic (conveys meaning) - YES
    * Arbitrariness(dots,dashes and meaning have no correlation. Just convention) -YES
    * Productivity (can freely create new, meaningful sentences never heard before e.g. The elephant is dancing on planet Mars) - NO
    * Traditional Transmission - NO (people learn the code, but it is not a cultural system which evolves naturally)
    * Duality of Patterning(dots, dashes being broken down like combining of sounds/words)- NO
    * Displacement/Creativity - NO (bound by it's designed purpose)
  
**My Own Comments**
* We tend to term animal signals as just 'communication systems' and not 'language' using principles like "Hockett's design principles" e.g. productivity, displacement, arbitrarines etc.
* Animal signals like bird signals have been studied and demonstrated variation in mating signals, predator warnings, social interaction etc.
* But, it is possible that we don't understand the comlex structures and grammar of bird signals.

## Language Families 

**Indo-Aryan**:  
   * Most North Indian languages (Dogri, in J&K region is a part of it) 
   * Descendants of Sanskrit language 

**Dravidian**: 
   * Most South Indian Languages 
   * NOT descendants of Sanskrit language, but have borrowed words from the language 

**Sino-Tibetian**
* Includes Chinese, Tibetan,South-East Asian(Myanmar, Thailand, Hongkong, Philippines, etc.), and a few Northeast Indian languages
   * Sinitic(Chinese):
      * Mandarin
      * Cantonese
  * Tibeto-Burman: 
      * Mostly North-East Indian languages 
      * e.g Bodo, Manipuri, Mizo


**Austroasiatic**: 
   * Stretches from south to south-east of Asia (Austro means south), similarly Australia also means southern land! (it is to the south of the globe) 
   * e.g. Santali 

Language Families are important as languages from the same family share similar vocabulary, grammar, and sentence structure. 

Transfer of knowledge can occur more easily between languages of the same language family in speech processing. 

| Language Code       | Name      | Family        | Sub-family               | Script              | Sample  | Class | # Native Speakers |
| ------------------- | --------- | ------------- | ------------------------ | ------------------- | ------- | ----- | ----------------- |
| asm_Beng            | Assamese  | Indo-Aryan    | Eastern Indo-Aryan       | Bengali             | ভাৰত    | 2     | 15.3M             |
| ben_Beng            | Bengali   | Indo-Aryan    | Eastern Indo-Aryan       | Bengali             | ভারত    | 5     | 97.2M             |
| brx_Deva            | Bodo      | Sino-Tibetan  | Boroic                   | Devanagari          | भारत    | 1     | 1.4M              |
| doi_Deva            | Dogri     | Indo-Aryan    | Northern Indo-Aryan      | Devanagari          | भारत    | 1     | 2.5M              |
| gom_Deva            | Konkani   | Indo-Aryan    | Southern Indo-Aryan      | Devanagari          | भारत    | 1     | 2.2M              |
| guj_Gujr            | Gujarati  | Indo-Aryan    | Western Indo-Aryan       | Gujarati            | ભારત    | 4     | 55.4M             |
| hin_Deva            | Hindi     | Indo-Aryan    | Central Indo-Aryan       | Devanagari          | भारत    | 5     | 528.3M            |
| kan_Knda            | Kannada   | Dravidian     | South Dravidian          | Kannada             | ಕರ್ನಾಟಕ | 5     | 43.7M             |
| kas_Arab            | Kashmiri  | Indo-Aryan    | Northern Indo-Aryan      | Perso-Arabic        | —       | 1     | 6.7M              |
| kas_Deva            | Kashmiri  | Indo-Aryan    | Northern Indo-Aryan      | Devanagari          | भारत    | —     | —                 |
| mai_Deva            | Maithili  | Indo-Aryan    | Eastern Indo-Aryan       | Devanagari          | भारत    | 1     | 13.5M             |
| mal_Mlym            | Malayalam | Dravidian     | South Dravidian          | Malayalam           | കേരളം   | 4     | 34.8M             |
| mar_Deva            | Marathi   | Indo-Aryan    | Southern Indo-Aryan      | Devanagari          | भारत    | 4     | 83.0M             |
| mni_Beng / mni_Mtei | Manipuri  | Sino-Tibetan  | Central Tibeto-Burman    | Bengali / Meitei    | ꯃꯅꯤꯄꯨꯔ  | 1     | 1.7M              |
| npi_Deva            | Nepali    | Indo-Aryan    | Northern Indo-Aryan      | Devanagari          | भारत    | 2     | 2.9M              |
| ory_Orya            | Odia      | Indo-Aryan    | Eastern Indo-Aryan       | Odia                | ଭାରତ    | 3     | 37.5M             |
| pan_Guru            | Punjabi   | Indo-Aryan    | North Western Indo-Aryan | Gurmukhi            | ਭਾਰਤ    | 3     | 33.1M             |
| san_Deva            | Sanskrit  | Indo-Aryan    | Indo-Aryan               | Devanagari          | भारत    | 2     | 0.02M             |
| sat_Olck            | Santali   | Austroasiatic | Munda                    | Ol Chiki            | ᱥᱟᱱᱛᱟᱲᱤ | 1     | 7.3M              |
| snd_Arab / snd_Deva | Sindhi    | Indo-Aryan    | North Western Indo-Aryan | Arabic / Devanagari | भारत    | —     | 2.7M              |
| tam_Taml            | Tamil     | Dravidian     | South Dravidian          | Tamil               | பாரத்   | 4     | 69.0M             |
| tel_Telu            | Telugu    | Dravidian     | South Central Dravidian  | Telugu              | భారత్   | 4     | 81.1M             |
| urd_Arab            | Urdu      | Indo-Aryan    | Central Indo-Aryan       | Urdu                | بھارت   | 5     | 50.7M             |

 
## Scripts 

* A writing system used to represent a language 

* Fonts are like different styles for the script, whereas script is a system (e.g. letter structure, characters, consonants, matras, etc.) 
   * Devanagari (for Hindi, Marathi, Nepali) 
   * Telugu 
   * Kannada 
   * Tamil 
   * Malayalam 
   * Bengali 
   * Urdu scripts etc. 

* Scripts are important as they decide the final outcome.  

* Speech -> language elements -> written text 

* E.g., You say Namaste in Urdu (Namaste is also used in Hindi), so if not specified, might give namaste in Hindi script instead of Urdu script. 
   * Same spoken word, different script outputs 

## History of Scripts
### Indian
1. Indus Script (~3300–1900 BCE)
* Earliest known writing system in the Indian subcontinent which emerged during the Indus Valley Civilization.
* e.g. Symbols  on seals, pottery, and other artifacts.
* logo-syllabic script (combining symbols to make words and sounds.)
* After disappearance of Indus script, Vedas used to be transmitted orally

2. Kharosthi Script (~5th Century BCE – 3rd Century CE)
![alt text](image-4.png)

* Appeared in northwestern India(current-day Pakistan)
* Influenced by writing systems of Achaemenid Empire(First Persian Empire, but later fell to Alexander the Great)
* Written from right to left (atypical)
* Used mainly for administrative records and Buddhist texts

3. Brahmi Script (~3rd Century BCE – 6th Century CE)
![alt text](image-5.png)
* Most influential script in Indian history
* Became widespread during Mauryan Empire and popularized in Ashokan inscriptions. 
* Written left to right (unlike Kharosthi)
* Later evolved
  * Evolution of Brahmi Script:
    * Northern-Brahmi
      * Gupta
      * Nagari
      * Devanagari
    * Souther-Brahmi
      * Tamil-Brahmi
        * Telugu
        * Tamil
        * Kannada
        * Malayalam

## Language Typology
Asks "How are languages built?" </br>
**NOT** </br>
"Where do the languages come from?"
Language Typology is the classification of languages based on their **structure and patterns**, not their geographical location or history.
* Types of Language Classification based on Typology
  1. ***Morphological Typology (word structure)***
    * **Isolating languages**
      * Words usually contain a single morpheme. Grammar is often shown through word order, than changing the word form itself.
      * e.g. Chinese (Mandarin)
        * Sentence: Wǒ chī fàn, I eat rice
        * Words do not change form for tense, gender, or number.
    * **Agglutinative languages**
      * Words are formed by adding clear affixes/morphemes, each having a clear grammatical role.
        * e.g. Pustaka-lu (Pustaka = book, lu=plural)
        * e.g. Illu-lu-lo-nunchi(Illu-house, lu-plural, lo-inside, nunchi-from)
        * NOTE: English is not an agglutinative language. cat-s, walk-ed, tall-er BUT chil-?(children), good+?(better), go+past?(went) - words have to be changed entirely
        * So, in agglutinated languages, we should clearly separate the affix and should represent one grammatical meaning.
    * **Fusional/Inflectional languages**
      * A single change can represent many meanings. 
      * The change is typically towards the end and is not an agglutination but a change in form of the word itself(but can still use affixes)
        * e.g. Sanskrit: रामः (rāmaḥ) = Rama (as the subject)
          * rāma + ḥ
          * The ending -ḥ indicates: masculine,singular, nominative/subject role
          * Isn't clear based on word itself, so is dependent on context.
    * **Polysynthetic languages**
      * A single word can contain the meaning of an entire sentence
        * e.g. Inuktitut(language in arctic canadian regions)
        * tusaatsiarunnanngittualuujunga(Inuktitut): "I cannot hear very well"
  2. ***Syntactic Typology (word order)***
  * This looks at the order of Subject(S) + Object(O)+ Verb(V)
  * SVO(Subject-Verb-Object)
    * e.g. I eat rice(English): S-V-O
  * SOV(Subject-Object-Verb)
    * e.g. Hindi 
      * मैं चावल खाती हुँ (I rice eat): S-O-V
  * VSO(Verb-Subject-Object)
    * e.g. Arabic
      * Akala Muhammad al-tuffaha: Ate Muhammad the apple
## Phonemes 

* Phonemes are the smallest units of sound 

* e.g. in bat vs pat 
   * /b/ and /p/ phoneme is the only difference.  

* Audio -> Phonemes -> Words -> Script/Text 
  
 

## Writing Systems

**Alphabetic**
* Each symbol represents one sound 
* Every sound gets its own letter 
   * e.g. CAT: /c/ /a/ /t/ 

* Vowels and Consonants are separated 
* Languages: English, Spanish, French, German 

**Abugida** 

* Most Indian languages 
* Constants and Vowels are NOT separated 
* Each consonant automatically contains a default vowel(in-built) 
  * e.g. क -> ka or कि  -> ki (a single symbol has both constant with inbuilt vowel of ka, instead of k + a like in English) 

**Abjad**  

* Mainly contains consonants; omits vowels 
   * e.g. Ktb is interpreted as kutub, kitab, katab based on context (easier for those who know the language) 
   * e.g. Arabic, Hebrew, Urdu (although does use some vowels) 

**Logographic**
* Symbol can represent an entire word/meaning unit(morpheme)
* Morpheme: smallest meaningful unit in language. 
   * e.g. Mandarin: 是 = is/are 

 

**Syllabaries** 
* Symbol for each syllable.
* Similar syllables do not have to be represented by visually similar symbols.
   * e.g. Japanese 

  

## Transliteration
* Language, meaning, pronunciation kept same, BUT script is changed 
* e.g. భారత్ (Telugu script) --> Bharat (English script) 
* e.g. नमस्ते (Hindi, Devanagari script) -> نمستے (Urdu script) 

### Transliteration Schemes
* e.g. Take the Hindi word: भारत
  * Some people write this in English(Roman/Latin script) as:
    * Bharat
    * Bhaarat
    * Bharath
    * Bhaarath
  
This becomes very inconsistent for computers.

So, transliteration schemes offer a **standardized mapping**.

#### Major Indian Transliteration Schemes
*All Schemes are designed to convert Indian script to Roman/Latin but can be used in both directions*

* Think of schemes as spellings
1.  **IAST (International Alphabet of Sanskrit Transliteration)**
  * Used mainly in Academic work, Sanskrit, Dictionaries and Linguistics in general
  * Uses diacritics
    * e.g. भारत --> Bhārata, कृष्ण --> Kṛṣṇa
  * Pros: Very accurate, Used in academia
  * Cons: Hard to type, Requires special characters
2. **ITRANS**
* Allows users to type Indian-language text using only standard english keyboard and ASCII characters.
* It is a one-to-one mapping
  * If I type Ram, instead of Raama, ITRANS won't transliterate
  * **ITRANS is designed to be unambiguous**
* e.g. Raama --> राम, kR^iShNa --> कृष्ण
  - Google Input serves a similar purpose to ITRANS: allowing users to type Indian language words using an English keyboard and converting them into Indian scripts.
  - ITRANS uses fixed transliteration rules (one-to-one mapping).
  - Google Input is more flexible and predictive.
  - For example, "Ram", "Raam", and "Rama" may all be converted to "राम", whereas ITRANS would typically expect a specific spelling such as "raama".

3. **Harvard-Kyoto** (HK)
* Similar to IAST and ITRANS, but special symbols are replaced with capital letters
* e.g. rAma --> राम
4. **ISO 15919** (International Organization for Standardization, Standard No. 15919)
* e.g. ISO 8601 - standard date and time format, ISO 216 - Paper sizes format, ISO 15919 - Indic script transliteration format.
* So, number is just an identfier of the standard
* International standard for transliterating all major Indian scripts
* Very similar to IAST
  * IAST --> Specific to Sanskrit, Hindi
  * ISO 15919 --> Covers Sanskrit, Hindi along with other Indian languages like Bengali, Telugu, Tamil etc.
  * e.g. Tamiḻ, the ḻ sound is specific to Tamil.

5. **WX** 
* Designed primarily for computational processing.
* Prioritizes unambiguous machine processing over human readability
* Strict one-to-one mapping to prevent unambiguity
* e.g. BArawa --> भारत
* ट --> ta, त --> w
* Uses capital letters and sometimes ASCII characters as well
  
NOTE: Unicode is a universal system that gives every character in every writing system unique numerical code so computers can store, process, and display code correctly.

#### Transliteration Tables
##### Vowels
| Hindi | Telugu | Unicode (Hindi) | Unicode (Telugu) | IAST | ISO 15919 | ITRANS | HK | WX |
| ----- | ------ | --------------- | ---------------- | ---- | --------- | ------ | -- | -- |
| अ     | అ      | U+0905          | U+0C05           | a    | a         | a      | a  | a  |
| आ     | ఆ      | U+0906          | U+0C06           | ā    | ā         | aa     | A  | A  |
| इ     | ఇ      | U+0907          | U+0C07           | i    | i         | i      | i  | i  |
| ई     | ఈ      | U+0908          | U+0C08           | ī    | ī         | ii     | I  | I  |
| उ     | ఉ      | U+0909          | U+0C09           | u    | u         | u      | u  | u  |
| ऊ     | ఊ      | U+090A          | U+0C0A           | ū    | ū         | uu     | U  | U  |
| ऋ     | ఋ      | U+090B          | U+0C0B           | ṛ    | r̥        | RRi    | R  | q  |
| ॠ     | ౠ      | U+0960          | U+0C60           | ṝ    | r̥̄       | RRI    | RR | Q  |
| ऌ     | ఌ      | U+090C          | U+0C0C           | ḷ    | l̥        | LLi    | L  | lY |
| ॡ     | ౡ      | U+0961          | U+0C61           | ḹ    | l̥̄       | LLI    | LL | LY |
| ए     | ఏ      | U+090F          | U+0C0F           | e    | ē         | e      | e  | e  |
| ऐ     | ఐ      | U+0910          | U+0C10           | ai   | ai        | ai     | ai | E  |
| ओ     | ఓ      | U+0913          | U+0C13           | o    | ō         | o      | o  | o  |
| औ     | ఔ      | U+0914          | U+0C14           | au   | au        | au     | au | O  |

##### Consonants
| Hindi | Telugu | Unicode (Hindi) | Unicode (Telugu) | IAST | ISO 15919 | ITRANS | HK    | WX |
| ----- | ------ | --------------- | ---------------- | ---- | --------- | ------ | ----- | -- |
| क     | క      | U+0915          | U+0C15           | ka   | ka        | ka     | ka    | ka |
| ख     | ఖ      | U+0916          | U+0C16           | kha  | kha       | kha    | kha   | Ka |
| ग     | గ      | U+0917          | U+0C17           | ga   | ga        | ga     | ga    | ga |
| घ     | ఘ      | U+0918          | U+0C18           | gha  | gha       | gha    | gha   | Ga |
| ङ     | ఙ      | U+0919          | U+0C19           | ṅa   | ṅa        | ~Na    | Ga    | fa |
| च     | చ      | U+091A          | U+0C1A           | ca   | ca        | cha    | ca    | ca |
| छ     | ఛ      | U+091B          | U+0C1B           | cha  | cha       | Cha    | cha   | Ca |
| ज     | జ      | U+091C          | U+0C1C           | ja   | ja        | ja     | ja    | ja |
| झ     | ఝ      | U+091D          | U+0C1D           | jha  | jha       | jha    | jha   | Ja |
| ञ     | ఞ      | U+091E          | U+0C1E           | ña   | ña        | ~na    | Ja    | Fa |
| ट     | ట      | U+091F          | U+0C1F           | ṭa   | ṭa        | Ta     | Ta    | ta |
| ठ     | ఠ      | U+0920          | U+0C20           | ṭha  | ṭha       | Tha    | Tha   | Ta |
| ड     | డ      | U+0921          | U+0C21           | ḍa   | ḍa        | Da     | Da    | da |
| ढ     | ఢ      | U+0922          | U+0C22           | ḍha  | ḍha       | Dha    | Dha   | Da |
| ण     | ణ      | U+0923          | U+0C23           | ṇa   | ṇa        | Na     | Na    | Na |
| त     | త      | U+0924          | U+0C24           | ta   | ta        | ta     | ta    | wa |
| थ     | థ      | U+0925          | U+0C25           | tha  | tha       | tha    | tha   | Wa |
| द     | ద      | U+0926          | U+0C26           | da   | da        | da     | da    | xa |
| ध     | ధ      | U+0927          | U+0C27           | dha  | dha       | dha    | dha   | Xa |
| न     | న      | U+0928          | U+0C28           | na   | na        | na     | na    | na |
| प     | ప      | U+092A          | U+0C2A           | pa   | pa        | pa     | pa    | pa |
| फ     | ఫ      | U+092B          | U+0C2B           | pha  | pha       | pha    | pha   | Pa |
| ब     | బ      | U+092C          | U+0C2C           | ba   | ba        | ba     | ba    | ba |
| भ     | భ      | U+092D          | U+0C2D           | bha  | bha       | bha    | bha   | Ba |
| म     | మ      | U+092E          | U+0C2E           | ma   | ma        | ma     | ma    | ma |
| य     | య      | U+092F          | U+0C2F           | ya   | ya        | ya     | ya    | ya |
| र     | ర      | U+0930          | U+0C30           | ra   | ra        | ra     | ra    | ra |
| ल     | ల      | U+0932          | U+0C32           | la   | la        | la     | la    | la |
| व     | వ      | U+0935          | U+0C35           | va   | va        | va     | va    | va |
| श     | శ      | U+0936          | U+0C36           | śa   | śa        | sha    | za/Sa | Sa |
| ष     | ష      | U+0937          | U+0C37           | ṣa   | ṣa        | Sha    | Sa    | Ra |
| स     | స      | U+0938          | U+0C38           | sa   | sa        | sa     | sa    | sa |
| ह     | హ      | U+0939          | U+0C39           | ha   | ha        | ha     | ha    | ha |


## Romanisation
* Subset of Transliteration: All romanisation is transliteration but not all transliteration is romanisation.
* Transliteration, but target script is always Roman/Latin(A,B,C,D,...).
* e.g. भारत(Hindi, Devanagari script) --> Bharat(Roman/Latin script)
* NOT नमस्ते (Hindi, Devanagari script) -> نمستے (Urdu script) as target or end script is not Roman/Latin
* NOTE: Pinyin is a system in itself followed to romanise Mandarin, Chinese.

### Simple Romanisation 
* e.g. भारत → Bharat
* Pronunciation might be lost

### Scholarly Romanisation
* e.g. भारत → Bhārat
* The line above a (macron), provides emphasis on the stressed 'aa' sound/ that the vowel is long
* Improved pronunciation
  * In linguistics, and scholarly work, Romanisation uses symbols called **'diacritics'**
  * ā ī ū ṭ ḍ ṇ ś ṣ
  * |Devanagari| Precise Romanisation|
    |:----:|:----:|
    |भारत| Bhārat|
    |राम| Rāma|
    |कृष्ण| Kṛṣṇa|
   * Diacritics are NOT specific to Devanagari, but every other script. They are simply marks or symbols added to characters to enhance pronunciation(NOT specific to romanisation, but transliteration in general) 
  
## Translation
* e.g. नमस्ते (Hindi) -> Hello (English)
* Language, script, pronunciation changed, BUT meaning preserved
  
## Transcription
* Focuses on preserving sound.
* Transcription is often confused with transliteration. While transliteration converts text between scripts and preserves the written form of a word(usually is able to maintain pronunciation), transcription aims to represent its pronunciation as accurately as possible.
* e.g. Bharat --> /bʱaːrət/ 
* Knight --> /naɪt/
  
  ### Verbatim vs Normalized
  * Verbatim transcription transcribes speech exactly as spoken
  * Normalized transcription transcribes speech by removing/filtering out filler words, converting it to a standardized speech form. 
  
|Sample|Verbatim|Normalized|
|------|--------|----------|
|Original: "Uhh... I, um, I think it's five."|Uhh... I, um, I think it's five.|I think it's five.|
|Original: "My number is nine eight two one."|My number is nine eight two one.| My number is 9821.|

### Verbatim, Normalized Examples for Indian Languages
* Analyzing samples from ai4Bharat Dataset for unsanitized verbatim and unsanitized normalized in Hindi language: https://huggingface.co/datasets/ai4bharat/IndicVoices/viewer/hindi?row=26
* unsanitized verbatim: raw transcript exactly as collected
* unsanitized_normalized: cleaned/standardized transcript for model training
  
|unsanitized verbatim|unsanitized normal|Scenario| District|State|Area|Age| Gender| Qualification| Occupation| Analysis|
|----|----|----|----|----|----|----|----|----|----|----|
|```<Persistent-noise-start> इस्थानीय कला <breathing> रूप या सिल्प <breathing> होसंगाबाद जिले के लिए एक <Persistent-noise-end>```|```<Persistent-noise-start> स्थानीय कला <breathing> रूप या शिल्प <breathing> होसंगाबाद जिले के लिए एक (<Persistent-noise-end>```|Extempore(impromptu)|Hoshangabad| Madhya Pradesh|Rural|30-45|Male|Post-Grad + phD|Fermar(farmer)| **1.** **इस्थानीय** (verbatim) vs **स्थानीय** (normalized) <br>Adding a vowel sound before the word is common in hindi belt, specifically rural areas. <br> **2.** Not shuddh or clean hindi originally, indicating lower education level(contrary to Post-Grad + phD qualification shown in the dataset) and occupation(blue collar job)<br> **3.** **सिल्प** (verbatim) vs **शिल्प** (normalized) 'Sh' sound/pronunciation is originally missed out.
|```<Persistent-noise-start> अनोखे हैं <inhaling> ये कला के रूप में <Persistent-noise-end>,```| ```<Persistent-noise-start> अनोखे हैं <inhaling> ये कला के रूप में <Persistent-noise-end>```|Extempore| Hoshangabad|Madhyapradesh|Rural|30-45|Male|Post-Grad + phD| Fermar(farmer)|Both contain the same spoken words, but verbatim (original) consists of a **','** towards the end unlike in normalized version. Similar reasoning as first example
|लोग जाते हैं देखते हैं अच्छा है|लोग जाते हैं देखते हैं अच्छा है| Extempore|Jaunpur|Uttar Pradesh|Rural| 18-30| Male| Undergrad and Grad.| Student| No difference between verbatim and normalized. Less accented and cleaner hindi, indicating literacy|
वहाँ पे हर चीजें मिलती हैं|वहाँ पर हर चीज मिलती हैं| Extempore|Jaunpur| Uttar Pradesh| Rural| 18-30| Male| Undergrad and Grad.| Student| **1.** **वहाँ पे** (verbatim) vs **वहाँ पर** (normalized) <br> Colloquial language converted to standard form. <br> **2.** **चीजें** (verbatim) vs **चीज** (normalized) <br> Speaker used a plural form which is converted to singular form to match the grammatical structure<br> Other similar obervations as above observation for student
| ```हाँ एक्चुअली सर <uhh> आपके बच्चे ने एक होमबर्क करके नहीं आया था और वो मैथ में थोड़ा सा वीक है```| ```हाँ एक्चुअली [actually] सर [sir] <uhh> आपके बच्चे ने एक होमबर्क [homework] करके नहीं आया था और वह मैथ [math] में थोड़ा सा वीक [weak] है```| Conversation| Betul| Madhya Pradesh| Urban|30-45|Male| Post Grad + phD| Indian Army| **1.** **actually, homework, math, weak** English words are tagged, indicating code-switching. Individual is probably well educated. **2.** **वो मैथ में थोड़ा सा वीक है** (verbatim) vs **वह मैथ [math] में थोड़ा सा वीक [weak] है** Pronoun normalization to satisfy standard conventions.<br> **3.** **[uhh]** is preserved, indicating a disfluency/filler and possibly a conversational setting.



## Distinguishing Between the 3T's
|Process|Result|
|----|----|
|Original|भारत|
|Transliteration|Bhārat|
|Transcription|/bʱaːrət/|
|Translation|India|

## Transcreation
* Adapting content from one language to another. 
* Instead of translating the literal meaning, you add some cultural references/context from the language you are translating to, to make the audience *'feel'* the same thing.
* **Trancreation = Translation + creative rewriting**
* e.g. In a Tamil movie: ""He runs faster than an auto driver in Chennai traffic.". But in Telugu movie, Chennai is changed to Vizag so the Telugu audience can associate with it better(movie dubbing)
* What undergoes transcreation depends on the demands of the script and language audience.

## Speech Processing
1. ASR (Automatic Speech Recognition)
* ASR listens to audio and converts Speech --> Text
* e.g. Audio --> "Hello, how are you?", Text  --> "Hello, how are you?"
* e.g. Google Assistant, Siri, Voice Typing

2.  TTS (Text-to-Speech)
  * Opposite of ASR 
  * Input: Text --> “Hello, how are you?” , Output: Spoken Audio --> “Hello, how are you?” 
  * e.g. Screen readers, Audio books, GPS (Navigation systems generate text, TTS system converts text to Audio) 
    * Specific to GPS: Text --> “Turn left in 200 m onto Mahatma Gandhi Road”, Audio --> “Turn left in 200 m onto Mahatma Gandhi Road"
3.  Speaker Recognition/ Speaker Processing
* Focuses on **who** is speaking
  * e.g. Bank Voice Authentication

4. Speech Emotion Recognition (SER)
* Determines and classifies the emotion in speech
  * e.g. "Why did you do that?" can be classified into angry,sad,happy.
5.  Speech Enhancement
* Improves speech quality
* e.g. Speech + noise (Before) -> Clean Speech (After)
6. Speech Separation (Cocktail Party Problem as mentioned by Prof. Haizhou Li)
* e.g. Person A + Person B (Input), Audio 1 -> Person A, Audio 2 -> Person B (Ouput)
* This separation can occur using language, noise, linguistic cues, spatial training etc.
7. Speech Translation 
* Speech in one language -> Speech/Text in another language
8. Speech Generation/Voice Cloning
* Creating new speech or copying a voice
  * e.g. 5 seconds of someone's voice -> Generate new sentences in that voice
9. Language Identification
* Detects which language is being spoken
* e.g. Audio (input) -> Telugu/Hindi/Tamil
10. Speech Analytics
* Extracts information from speech
  * e.g. Keywords, topics
* Used in call centres, meetings
  
## Prosody
* Rhythm (timing pattern of speech), stress (which syllables are getting emphasis), pitch (High or low voice), and intonation (rise or fall of voice) of speech. 
* It’s not what you say, but HOW you say it 
* e.g. I didn’t say you stole the money vs I DIDN’T say you stole the money 
* Same words, different emphasis 
* Without prosody, speech would be robotic 

### ASR + Prosody
* Prosody can help ASR determine if it's "let's eat, grandma" or "let's eat grandma"
### TTS + Prosody
* Prosody can help TTS predict and determine the audio it's speaking out based on:
  * pitch ranges
  * speaking rate
  * pauses
  * emphasis
  * rising/falling voice

### Summary Table
|Term|Input|Output|
|----|----|----|
|ASR|Speech|Text|
|TTS|Text|Speech|

***No input and output for Prosody as it's not a system , but a property of speech.***

## Linguistics
Scientific study of language
* Phonetics
* Phonology
* Morphology
* Syntax
* Semantic
* Pragmatic

### Phonetics
Study of how sound is physically produced and heard
* Tongue movement
* Lip movement
* Mouth movement
* Vocal chord usage

### Phonology
Study of how phonetic differences affect meaning in a particular language.

* e.g. in Hindi /k/ and /kh/ or even /b/ and /bh/ in बाग and भाग are considered to be 2 different phonemes as they affect meaning. However in English, they can be considered the same phoneme as meaning is not affected(aspirated and unaspirated are both treated as the same phoneme)
* e.g. Mandarin is a tonal language. Although the syllable is the same, the tone matters. So, tone is phonemic However, in languages like Hindi and English, tone doesn't matter.
  * NOTE: You can't say different tones make different phonemes as it's a bit vague. Phoneme is the smallest unit of sound. 
  * mā, má, mǎ, mà can't each be a separate phoneme as they are words in itself. Just like how बाग and भाग are not considered phonemes but words directly. /b/ and /bh/ are phonemes.
    * mā = /m/ + /a/ + Tone 1
    * má = /m/ + /a/ + Tone 2
    * linguistics hesitate to call Tone 1, and Tone 2 as phonemes(although /m/, /a/ are phonemes) as they sit on top of a letter and are not directly vowels or consonants.
  

### Morphology
Study of how words are built(internal structure and formation of words)
* How are words formed from smaller, meaningful units?
* Morpheme: Smallest unit of meaning
* e.g. un(not)+happy(happy)+ness(state/quality) = unhappiness
* Morphology ≠ Script structure
* Morphology looks are prefixes, suffixes, word formation etc.

#### Types of Morphemes
1. **Free morphemes**
   * These can exist as independent words
     * e.g. book, run, happy

2. **Bound morphemes**
   * These cannot stand alone, must attach to another morpheme
   * e.g.1. -s, -ed, -un, -ing
   * e.g.2. walked = walk(free) + ed(bound)
     * Derivational morphemes(type 1)
       * Create a new word/change the word/class meaning
         * e.g. un-happy, teach-er,kind-ness
     * Inflectional morphemes(type 2)
       * These add grammatical information but do not create a new word
       * Show tense, comparison, possession, gender etc(depends on the language as well)
         * e.g. tall -> tall-er, walk -> walk-ed, cat -> cat-s

#### Types of Morphology
* Inflectional
  * Changes grammatical form of a word but usually doesn't change core meaning
  * Changes in:
    * singular/plural
    * masculine/feminine
    * past/present
    * case  (to whom, whose, from whom, to whome, where)
      * English: Ram, Ram's (Core word: Ram)
  
* Derivational
  * Forms new words, changes word meaning, and can change word class also (Adjective--> Noun/Word --> Verb)
  * E.g. un + happy --> unhappy
  * happy(Adjective) --> happiness(Noun)
  * teach(verb) --> teacher(Noun)
  
***English Examples***

|Root Word| Inflectional| Derivational|
|----|----|----|
|Cat|Cats|Catlike|
|Walk|Walked|Walker|
|Run|Running|Runner|
|Happy|Happier(comparative form only)| Happiness
|Kind|Kindest|Unkind|
|Teach|Teaches|Teacher|
|Write|Writing|Rewrite|


***Hindi Examples***
|Root Word| Inflectional| Derivational|
|----|----|----|
|लड़का|लड़के|लड़कापन|
|सुंदर|—|सुंदरता|
|मित्र|मित्रों|मित्रता|
|मानव|मानवों|मानवता|


### Syntax
* Study of how words form grammatical sentences
* e.g. Hindi uses Subject + Object + Verb
  * मैं आम खाता हूँ।
  * English literal: I mango eat
  * Correct English sentence: I eat Mango
  * English uses Subject + Verb + Object

### Semantics
* Study of literal meaning (what does a word or a sentence mean?)
* e.g. The cat ate the rat
  * Semantically: The cat consumed the rat
* However, semantics are very literal. ***Context is ignored.***
  
### Pragmatics
* Study of how context influences meaning and speaker intent
* e.g.1 Original: It's cold in here.
  * Semantic: The room is cold.
  * Pragmatic: Please close the window. *(intent aspect)* 
* e.g.2 Original: Can you pass me the marker?
  * Semantic: Are you capable of passing me the marker?
  * Pragmatic: Pass me the marker.
* NOTE: There's a thin line between Semantics and Pragmatics. E.g., if you give an LLM, larger data(e.g. a book instead of a sentence/phrase), it might be able to get the intent right. But, idioms and figures of speech is hard to decode for the LLM and sometimes even for humans (e.g. Using memes with a person who doesn't have meme knowledge) 
* Idioms and Figures of speech would definitely be considered 'Pragmatic'.

## Audio
* Audio is any form of speech signal which can be recorded, transmitted, or processed by a system.
* It is a mechanical wave created by vibrations that travel through a medium (typically air) and can be perceived by humans.
1. **Acoustics** (Environmental Sounds)
* Non-speech sounds around us (e.g. walk*ing, tapping, glass breaking)
2. **Speech** 
* Audio generated by the human speech production system
* e.g. formants, vocal cords, flaps, larynx
* Source = Vocal Cord vibration, Filter = Vocal tract shaping the sound
  1. **Read Speech**
   * Speaker reads a prepared text
   * Characteristics: complete sentences, planned speech, careful pronunciation, fewer mistakes, consistent pacing
   * WER is lower
  2. **Conversational Speech**
   * Natural interaction between people
   * Characteristics: informal-language, turn-taking, interruptions, fillers, code-switching
   * WER is Medium
  3. **Spontaneous Speech**
   * Speech created without planning
   * Characteristics: Hesitations,self-corrections, false starts, incomplete sentences, repetitions
   * WER is the highest
3. **Music**
* Audio produced by intentionally using instruments, human voice, and electronic synthesis
 
## Speech LLMs (SLLMs)
A type of AI model that can directly understand and generate speech, rather than only working with text.

Speech input - > Speech LLM -> Speech output
* SLMs are different from normal LLMs as the latter mainly understands text tokens. But, speech contains so much more information and features that only an SLM can capture and understand
* Information in speech signal:
  1. **Linguistic**: information represented as words,symbols, phonemes, morphemes
  2. **Paralinguistic**: informative factors that can be consciously controlled by the speaker
    * e.g. Prosody, attitude, emphasis
  3.  **Non-linguistic**: informative factors that cannot be controlled by the speaker
    * e.g. Gender, age, physical build, idiosyncracy (unique behaviours specific to a person, group, object. e.g. fillers, mother-tongue)
    * More on mother-tongue: 
      * Hindi-belt: i-style, i-school (vowel at beginning of word)
      * Telugu-belt: bus-u, car-u (vowel at end of word)
      * Punjab-belt: s-a-chool (vowel in the middle)
  
  4. **Background Information**:
   * Acoustic environment
   * e.g. **'Lombard effect'**: is the involuntary tendency of speakers to increase their vocal effort when speaking in a loud environment (railway station, when wearing earphones etc.)

### Conditions to Qualify as a SLLM
1. Either input/output side there should be speech
2. Be able to solve a variety of spoken language tasks
3. Take info/prompts in the form of speech

**NOTE**: ChatGPT may qualify condition 1 and 3, but not condition 2.

### Speech Synthesis
The process of creating human-like speech from text (typically) or other inputs from the computer
* TTS methods
1. **Concatenative Synthesis (Template Matching)**
* Stitches pre-recorded speech units (phonemes, syllables, words)
* Pros: Natural sound quality (if well-designed)
* Cons: Rigid, Hard to scale, limited expressiveness, memory usage

2. **Statistical Parametric Synthesis (Statistical Approach)**
* Models speech production mechanism with a smaller set of parameters
* Pros: Compact, flexible, easy to  control prosodic parameters
* Cons: Typically less natural than concatenative synthesis

3. **Neural End-to-End Synthesis (Neural Approach)**
* Learn to directly map text to spectograms/waveforms
* Called end-to-end as from input to output, everything is learnt from data, directly
* Pros: High naturalness and adaptability
* Cons: Typically less natural than concatenative synthesis


**Explanation with Analogy:**
* Concatenative: Keep ready-made food pieces and combine them
  * e.g. said 'hello', take a prerecorded 'he' + 'llo'
* Statistical Parametric: Learn the recipe
  * e.g. A voice has this pitch, this speech, this tone -> generate something similar

## Datasets
* General procedure: Build a model --> Train it --> Test it --> Evaluate its performance
* **Dataset**: collection of data used to train, validate, and test a model(in this case a speech processing system)
* E.g. for speaker recognition:
  
|Audio|Speaker|
|----|----|
|Recording 1| Person A|
|Recording 2| Person B|
|Recording 3| Person C|

The models learns voice --> speaker identity
**General Datasets**
|Dataset|Primary Use|
|----|----|
|LibriSpeech|ASR|
|Mozilla Common Voice|ASR, Language Identification|
|FLEURS||Multilingual ASR, Speech Translation|
|AISHELL|ASR|
|VoxCeleb|Speaker Recognition|
|RAVDESS|Emotion Recognition|
|LJ Speech|TTS, ASR|

**Indic Datasets**:
|Task|Indic Datasets|
|----|----|
|ASR (Speech → Text)|	IndicSpeech, Kathbath, Vakyansh, Common Voice Indic, FLEURS Indic|
|TTS (Text → Speech)|	IndicTTS, IndicVoices, OpenSLR Indic
|Speaker Recognition|	IndicVoices, IIIT-H datasets|
|Emotion Recognition|	Indic emotion speech datasets (e.g., IITKGP/Emo datasets)|
|Language Identification|	Common Voice Indic, FLEURS Indic|
|Speech Translation|	FLEURS, AI4Bharat IndicTrans speech resources



**NOTE**: 
* Datasets for TTS and ASR can be used interchangeably. 
However, a dataset specific for ASR(Speech-->Text) will have a lot of speakers, different accents & noises, real world speech which is not ideal for TTS(needs clean audio and consistent recording conditions, precise pronunciation etc.)
* ASR requires less hours of data compared to TTS which requires more hours of data (to capture clean sound)

## Open Source Models Speech & Language Models

| Type    | General Models                                                                                        | Indic Models                                                                    |
| ------- | ----------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------- |
| **ASR** | **Whisper Large-v3**, **SeamlessM4T-v2**, **WavLM**, **w2v-BERT 2.0**, **OWSM**, **NVIDIA Canary** Conformer, Zipformer | **IndicWhisper**, **IndicConformer**, IndicWav2Vec2, Vakyansh ASR, Bhashini ASR |
| **TTS** | **XTTS-v2**, **F5-TTS**, **VoiceCraft**, **StyleTTS 2**, **Parler-TTS**, SpeechT5                     | **AI4Bharat IndicTTS**, Indic-TTS, Vakyansh TTS, Bhashini TTS                   |
| **MT**  | **SeamlessM4T-v2**, **MADLAD-400**, **NLLB-200**, mBART50, M2M-100, mT5                               | **IndicTrans2**, IndicTrans2-M2M, Bhashini MT                                   |


**NOTE**: Not all Bhashini models are Open Source Models.
## Evaluation Metrics
### ASR
1. **WER(Word Error Rate)**
  * Mostly used for speech recognition(ASR) to measure transcription errors
  * WER = (S + D + I)/ N
    * S-substitution, D-deletion, I- insertions, N-total number of words
      * e.g. Speech: " I love apples", Transcribed text: "I love apple".
        * This is a substitution, but still low WER -> better speech recognition
  * Limitations: WER treats all errors equally
    * e.g. "I ate cake" vs "I hate cake"
    * Both are one substitution, but the meaning changes completely
2. **Character Error Rate (CER)**
   * Similar to WER but measures character-level errors.
   * Useful for:
     * languages with complex morphology
     * languages where word boundaries vary
     * e.g. नमस्ते (reference) and नमस्त (output)
     * Only one character difference.

3. **Real Time Factor (RTF)**
   * Measures Speed
   * RTF = Processing Time/Audio Duration
   * Lower the RTF, faster the model
4. Speaker/Noise Robustness

### TTS
1. Mean Opinion Score (MOS)
   * Humans rate generated speech
   * 1 = Very Poor, 5 = Human-like
   * Limitation: Subjective, different listeners may rate differently
2. **Mel-Cepstral Distortion(MCD)**
   * Measures difference between real human speech and generated speech using MFCCs
   * Low MCD = More similarity
3. **Word Error Rate (WER)**
   * Same purpose as in ASR
4. **Speaker Similarity**
   * Evaluated by measuring the cosine similarity of speaker embeddings to check if generated voice matches the target speaker
### Machine Translation (MT)
1. **BLEU Score (Bilingual Evaluation Understudy)**:
  * Compares machine translation output with human translations
  * Checks mainly word overlap and phrase similarity(might miss out on meaning)
  * Higher BLEU -> Closer to reference point
2. **METEOR**
   * Improves BLEU by considering synonyms, stemming, word order
   * e.g. boys <-> child, eat <-> consume
   * So, can allow better semantic matching with BLEU
3. **Translation Edit Rate(TER)**
  * Measures how may edits(insertions, deletions, substitutions) are required to convert the machine translation into the reference
  * Lower TR = better
4. **ROUGE Score**
   * Did the model capture the important content?
   * Focuses on recall, while BLEU score focuses on precision
5. **BERT Score**
   * Compares not only words but meaning(has semantic focus)
   * Uses BERT embeddings
### Text-Generation/LLM Evaluation
* NOTE: In MT, you're transform one language to another(in terms of text) unlike in Text-generation(completely new text is generated)
1. **Perplexity**
  * Measures how well an LM predicts text/how 'suprises' a model is a sequence of words
  * lower perplexity -> Better prediction and vice-versa
2. **BLEU/ROUGE**
   * Used for summaries, generated responses
3. **BERT Score**
   * To measure semantic similarity
### NLP Classification Tasks
Spam detection, Sentiment analysis, Topic classification
1. **Accuracy**
   * Accuracy = Correct predictions/ Total predictions
2. **Precision**
   * Out of everything the model predicted as positive, how much was already positive?
   * Precision = TP/ (TP+FP)
     * TP-True Positive, FP- False Positive
3. **Recall**
   * Out of all actual positive cases, how many did the model actually find?
   * Recall = TP/(TP+FN)
     * FN-False Negative
   * So, high recall -> few missed cases
4.  **F1-Score**
   * Balances/combines precision and recall into a single metric
   * F1 = 2*(Precision * Recall)/(Precision + Recall)
### Information Extraction/Named Entity Recognition (NER)
e.g. "Elon Musk founded SpaceX"
  * Entities: Elon Musk, SpaceX
1. Precision (Were detected entities right?)
2. Recall (Were all entities found?)
3. F1 (Balance)

## Rich-Speech Characteristics
1. **Named Entities(NEs)**
  * Specific names of people,places,organizations, products, dates, etc.
    * e.g. “I visited Hyderabad last week and saw Charminar.”
    * Hyderabad -> location, Charminar -> landmark(Speech system should be able to recognize the named entities in this manner)
    * e.g. "I went to Apple"
      * Apple is fruit or company in this context?(Speech system should be able to know which one)
2. **Code Mixing**
   * Using of words and phrases from different languages in the same sentence
     * e.g. "Nenu file upload chesanu"

3. **Accent**
   * The way speech sounds due to a speaker's region, community, first language, background
     * e.g. Indian-English, British-English, American-English
  
4. **Mispronunciation**
   * When a speaker produces a word which is different from its standard pronunciation
   * Occurs due to unfamiliar words, second-language influence, speech difficulties, fast speaking
   * e.g. comfortable(standard pronunciation) vs comfterble(mispronunciation)

5. **Disfluencies**
   * Interruptions or irregularities in natural speech
     * Fillers: I, uh, umm
       * e.g. "I,um, wanted to ask something"
     * Repetition: "I I I think..."
     * False starts: " I went to - actually, I stayed home"
     * Self-corrections: " The meeting is on Tuesday - sorry, Wednesday"
  
6. **Paralinguistics**
   * Vocal features beyond the actual words which carry meaning
   * e.g. Tone, pitch, volume, speaking rate, emotion
   * Prosody is a huge part of Paralinguistics, but the latter is broader
   * e.g. non-lexical sounds(crying, sighs, pauses), speech style(hesitation, emphasis) don't come under prosody

## Uncertainty in LLMs (Notes from Dr. Sriram Ganapathy, IISc Lecture)
### Trust
Trust on LLMs or AI in general can typically mean things like factual correctness, reproducibility, and robustness under different conditions.

To evaluate whether an AI system can be trusted, it is important to first understand what trust means in the context of AI systems.

**Need for Trust Assessment**
* Modality Influence: Understanding how different input types (text, image, audio) affect model decisions
* Hallucination Risk: Identifying when models generate unsupported or incorrect outputs
* Sensitivity to Input Domain Shift: Understanding how changes in data distribution or real-world conditions affect model performance and reliability

### Uncertainty & Confidence 
**Uncertainty** is the degree of doubt or lack of knowledge a model has about its output being correct

**Confidence** refers to how confidently a model favours a particular output or prediction

**Ideally:**
* Correction prediction -> High confidence -> Low uncertainty
* Wrong/unknown case -> Low confidence -> High uncertainty\

**Confidence and uncertainty should be inversely proportional**

BUT in the models we have right now, just because it is correct doesn't mean it is confident and vice-versa. Same applies in the context of uncertainty.

Uncertainty has two parts:
* **Aleatoric uncertainty (irreducible) + Epistemic uncertainty (reducible with data) = Total model uncertainty**
* Aleatoric Uncertainty
  * Uncertainty as the world/data itself is noisy
  * Even with inlimited training data, you cannot completely remove it (irreducible)
* Epistemic Uncertainty
  * Uncertainty as the model doesn't have enough knowledge
  * Comes from lack of training data or model understanding
  * Can be reduced by: collecting more data, improving the model, better training (reducible)

### Temperature
Temperature is a parameter that controls how much the LLM's token probabilities are "flattened" or "sharpened" before choosing the next token.

To explain:
1. **LLM first produces logits**
* Before producing the next word/token, the model produces logits
  
**Question: "What is the capital of France?"**

 |Token|Logit|
 |----|----|
 |Paris|10|
 |Lyon| 5|
 |Rome|2|
 * Logits are **raw** scores given to tokens before choosing. 
 * Higher logit = Model prefers that token

2. Softmax equation converts logits --> probabilities

 |Token|Probability|
 |----|----|
 |Paris|99%|
 |Lyon|0.9%|
 |Rome|0.1%|

So, the model is very deterministic. 

However:
* High temperature (T > 1) -> Scaling logits out(flattened)-> lower softmax produced probabilities -> less deterministic, more diverse
* Low temperature (T < 1)-> Scaling logits up (sharpened) -> higher softmax produced probabilities -> more deterministic

**NOTE:**
* flattened: less difference/gap between high and low probability tokens (compared to earlier)
* sharp: more difference/gap between high and low probability tokens (compared to earlier)

High temperature, leading to diversity, doesn't necessarily mean high uncertainty.
It might me sampling uncertainty (uncertainty in selecting among possible tokens from the model’s output distribution) **BUT NOT** epistemic uncertainty (due to lack of knowledge)


### Mentioned Methods: Sampling inputs instead of output for confidence matrix

**Confidence Matrix** is a that shows how confident a model is about its predictions across different classes, inputs, or situations.

Method Example:
Original Qualification: "Is the car under the cat?"
* Equivalent Questions -> "Is the cat on top of the car?" (should give same response) 
* Complementary Questions -> "Is the car on top of the cat" (should give opposite response)

The above example is based on the question which has binary answer. 
However, a question with open-ended answers can also be used, without any options:
  * e.g. "What is the capital of the US"
  * Answers can be varied
  * NOTE: Complementary questions cannot be made at all times, like for this question.("We can't do, "What is the capital of France" as it doesn't really make sense for evaluation. The Complementary question will end up becoming open-ended)

FESTA Score = FEC + FCC

**NOTE:**
* Clustered -> Less Semantic Entropy -> Model has a clear representation
* Spread Out -> High Semantic Entropy -> Representation is uncertain

* FEC (Feature Entropy Component) = "How spread out/uncertain are the features?"
* FCC (Feature Confidence Component) = "How confident is the model's feature representation?"















  


