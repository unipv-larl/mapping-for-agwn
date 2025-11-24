**Mapping Ancient Greek lemmas to WordNet synstes via back-translation dictionaries**

This repository contains files mapping Ancient Greek lemmas to their English translation and the corresponding synset(s) description. The data is collected from the Woodhouse back-translation dictionary (S. C. Woodhouse, English-Greek Dictionary,George Routledge & Sons, Limited, 1910).

To cite this work, please acknowledge the repository appropriately.

**Description**

The dictionary entries are stored in the 'english_to_greek.json' and 'english_to_greek.txt' files. The data has undergone cleaning operations to remove information irrelevant for the mapping that was present in the original dictionary. The cleaning operations include the removal of part-of-speech labels, articles and multi-word expressions, and normalization of Unicode encoding.

The 'english_to_greek_synsets.csv' file presents the data in tabular format providing for each dictionary entry of Ancient Greek lemmas all the synsets descriptions available for their English translation. The synset descriptions of each target English lemma were extracted directly from WordNet via the appropriate NLTK library. The data allows for automatic mapping of the Ancient Greek lemmas to the same synset(s) as their English translation.

**Warning**: as the mapping of the synset is automatic and was not manually validated, there can be spurious or anachronistic results within the matches.


**Contact**

For questions or collaboration, feel free to contact:

Chiara Zanchi,
Università di Pavia
chiara.zanchi@unipv.it

Beatrice Marchesi,
Università di Pavia
beatrice.marchesi03@universitadipavia.it


**How to cite**

If you want to cite this work please reference it through these citations:

- Marchesi Beatrice. (2025). Toward semi-automatic synset population: LLM-based approaches for Ancient Greek WordNet expansion. [Master's thesis, Università degli Studi di Pavia].

- Beatrice Marchesi, Annachiara Clementelli, Andrea Maurizio Mammarella, Silvia Zampetta, Erica Biagetti, Luca Brigada Villa, Virginia Mastellari, Riccardo Ginevra, Claudia Roberta Combei and Chiara Zanchi. (Forthcoming). Towards the Semi-Automated Population of the Ancient Greek WordNet. Proceedings of the Eleventh Italian Conference on Computational Linguistics (CLiC-it 2025).

