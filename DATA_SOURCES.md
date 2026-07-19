# Vocabulary App data packages

This repository contains public runtime data packages used by the Vocabulary App. The app downloads and SHA-256 verifies these files in the background on Wi-Fi, then stores them in its private local cache.

- core-libraries-v1.json: complete default vocabulary books
- word-scores-v1.json: frequency and complexity scores
- sentence-bank-v1.json: bilingual example sentence bank

## Attribution

Sentence data is derived from Tatoeba exports (CC BY 2.0 FR, with a subset under CC0 1.0): https://tatoeba.org/en/downloads

Frequency-derived scores use FrequencyWords / OPUS OpenSubtitles 2018 (CC BY-SA 4.0): https://github.com/hermitdave/FrequencyWords

Lexical complexity scores include data derived from CompLex (CC BY 4.0): https://github.com/MMU-TDMLab/CompLex