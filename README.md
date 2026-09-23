# Sindhi Word Frequency List
This Sindhi word-frequency dataset was created from a corpus containing approximately 149 million words. From the corpus, words occurring with a minimum frequency of 3 were extracted, resulting in an initial vocabulary of approximately 180,000 unique word forms. This verified vocabulary is being used in our [Android Sindhi keyboard](https://hellosindh.com/en/sindhikeyboard) for word suggestions and spell checking/autocorrection.

From this larger vocabulary, 28,303 words have been manually reviewed and proofread, and the review is still ongoing. Most words in this verified list have a frequency of 114 or higher; some lower-frequency words are also included where they were confirmed through matching or related word forms. We are continuing to review and verify words below 114 frequency.



## Normalization
The vocabulary is normalized to improve matching and prediction. Common orthographic variations of Heh (ه/ھ and related forms) are normalized where appropriate, and the vowel diacritics zabar (َ), zer (ِ), and pesh (ُ) are generally removed during normalization. However, necessary diacritics are retained where they are required to distinguish or correctly represent a word.

This vocabulary should not be interpreted as a list of only native or “pure” Sindhi words. The objective of the project was broader: to collect the words and word forms that are actually used in Sindhi-language writing and communication. Therefore, the dataset also contains loanwords, borrowed vocabulary, and transliterated words from other languages that are commonly written in Sindhi script. This reflects real-world Sindhi usage rather than restricting the dataset to words of purely native Sindhi origin.

## Authenticity 
The manually reviewed 28,303-word list is estimated to have approximately 99% accuracy based on our checking and proofreading process. As with any large human-curated lexical resource, a small number of incorrect, uncommon, or overlooked forms may remain.

## License
MIT License

Copyright (c) 2026 Hellosindh

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
