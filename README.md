# BixoPDF dictionary packs

Language packs for the dictionary of [BixoPDF](https://www.bixopdf.com): English, Korean, Japanese, Chinese, German,
French and Russian, linked by sense, so that a word can be looked up from any of the seven languages into any other.

The packs are attached to the [releases](https://github.com/nimis0612/bixopdf-dict/releases). BixoPDF downloads them
when you press **Download** or **Check for updates** in its Dictionary panel; you can also download a file here and add
it with **Import dictionary files**.

| File | Language | Download | Installed |
|---|---|---|---|
| `en.sqlite.br` | English | about 69 MB | 224 MB |
| `ko.sqlite.br` | Korean | about 22 MB | 78 MB |
| `ja.sqlite.br` | Japanese | about 35 MB | 124 MB |
| `zh.sqlite.br` | Chinese | about 27 MB | 87 MB |
| `de.sqlite.br` | German | about 60 MB | 290 MB |
| `fr.sqlite.br` | French | about 47 MB | 159 MB |
| `ru.sqlite.br` | Russian | about 46 MB | 212 MB |
| `packs.json` | the list: file, sizes, SHA-256, build date | | |

Each pack is one SQLite database, compressed with Brotli. Its tables: `lexeme` (headwords with their frequency),
`form` (inflected forms, readings and other spellings leading to a headword), `sense` (part of speech, definition,
example), `gloss` (translations written in another language) and `concept` (the senses shared across languages),
with `source` naming where each sense comes from.

## Sources

| Source | Used for | Licence |
|---|---|---|
| [Basic Korean Dictionary](https://krdict.korean.go.kr) (한국어기초사전), National Institute of Korean Language | Korean definitions, examples, inflections; their English, Japanese, Chinese, French and Russian translations | CC BY-SA 2.0 KR |
| [English Wiktionary](https://en.wiktionary.org), via [Wiktextract](https://github.com/tatuylonen/wiktextract) / [kaikki.org](https://kaikki.org) | all seven languages; translation tables | CC BY-SA 4.0 and GFDL |
| [Korean Wiktionary](https://ko.wiktionary.org) (한국어 위키낱말사전), via Wiktextract | Korean glosses of words of the other languages | CC BY-SA 4.0 and GFDL |
| [Japanese Wiktionary](https://ja.wiktionary.org) (ウィクショナリー日本語版), via Wiktextract | Japanese definitions and translation tables | CC BY-SA 4.0 and GFDL |
| [German Wiktionary](https://de.wiktionary.org) (Deutsches Wiktionary), via Wiktextract | German definitions, inflections and translation tables | CC BY-SA 4.0 and GFDL |
| [French Wiktionary](https://fr.wiktionary.org) (Wiktionnaire), via Wiktextract | French definitions, inflections and translation tables | CC BY-SA 4.0 and GFDL |
| [Russian Wiktionary](https://ru.wiktionary.org) (Русский Викисловарь), via Wiktextract | Russian definitions, inflections and translation tables | CC BY-SA 4.0 and GFDL |
| [JMdict](https://www.edrdg.org/wiki/index.php/JMdict-EDICT_Dictionary_Project), Electronic Dictionary Research and Development Group | Japanese words, readings, English glosses | CC BY-SA 4.0 |
| [CC-CEDICT](https://www.mdbg.net/chinese/dictionary?page=cc-cedict), MDBG | Chinese words, pinyin, English glosses | CC BY-SA 4.0 |
| [Japanese WordNet](https://bond-lab.github.io/wnja/) 2.1, NICT and Francis Bond | Japanese senses linked to WordNet | WordNet licence ([text](licenses/japanese-wordnet.txt)) |
| [Open Multilingual Wordnet](https://github.com/omwn/omw-data) 2.0: Princeton WordNet 3.0 (English), Chinese Open WordNet | English and Chinese senses linked to WordNet | WordNet licences ([English](licenses/omw-english-wordnet.txt), [Chinese](licenses/omw-chinese-wordnet.txt)) |
| [wordfreq](https://github.com/rspeer/wordfreq) 3.1.1, Robyn Speer | word frequencies (which words to keep, how to rank translations) | CC BY-SA 4.0 (data) |

This publication has included material from the JMdict (EDICT, etc.) dictionary files in accordance with the
licence provisions of the Electronic Dictionaries Research Group. See <http://www.edrdg.org/>.

## Licence

The packs are derived from the sources above and are published under the
[Creative Commons Attribution-ShareAlike 4.0 International licence](https://creativecommons.org/licenses/by-sa/4.0/)
(CC BY-SA 4.0); the material from the Basic Korean Dictionary remains under CC BY-SA 2.0 KR, and the WordNet material
under its own licences, whose notices are in [`licenses/`](licenses). See [LICENSE.md](LICENSE.md).

The packs are provided as they are, without warranty of any kind.
