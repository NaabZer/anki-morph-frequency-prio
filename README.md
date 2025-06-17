# Anki Morph Frequency
Small tool to grab all morphemes from a deck to a list to allow them to be extracted to a priority file using [AnkiMorphs](https://github.com/mortii/anki-morphs), which can then be sorted using frequencies from frequency dictionaries.
Inspired by the [JP-resources](https://github.com/MarvNC/JP-Resources/tree/main) repository for frequency sorting.

## Process
1. Use [Anki-Connect](https://git.sr.ht/~foosoft/anki-connect) to extract all sentences from your deck.
2. Use this list of words to generate a priority list using the [AnkiMorphs](https://github.com/mortii/anki-morphs) addon in Anki.
3. Sort this priority list by frequency using the same method as [JP-resources](https://github.com/MarvNC/JP-Resources/tree/main).
4. Enter this back into the [AnkiMorphs](https://github.com/mortii/anki-morphs) addon in Anki.

## Setup
1. Get japanese frequency dictionaries.
2. Extract them into a subfolders in the dicts folder with a structure like this:
```
   └─ dicts
       ├── dict1
       │   ├── index.json
       │   ├── term_meta_bank_1.json
       │   ├── term_meta_bank_2.json
       │   └── ...
       └── dict2
           └── ...
```
3. Run through the [First_Testing.ipynb jupyter-notebook](notebooks/First_Testing.ipynb)
