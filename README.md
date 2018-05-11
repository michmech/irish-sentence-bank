# Irish Sentence Bank

This is a collection of approximately 4,500 sentences in Irish, tokenized and lemmatized, with English translations. Most of the sentences have been hand-picked from published language-learning texts and would serve well as example sentences in a dictionary. Many of the sentences do in fact occur as example sentences in the [Pota Focal House Glossary](https://github.com/michmech/pota-focal-gluais), but many others don't. The tokenization and lemmatization has been done by hand and is believed to be to practically 100% correct.

## License

Available under the [Open Database License](http://opendatacommons.org/licenses/odbl/summary/).

## Format

Each sentence is enclosed in a `<sentence>` tag, consisting of an `<original>`, a `<translation>` and a number of `<flex>` elements. The `<original>` tag contains the sentence in Irish. It consists of a sequence of `<token>` tags interlaced with whitespace and punctuation. Each `<token>` tag has an index number in its `@slot` attribute, and its corersponding lemma is given in a `<flex>` tag with the same `@slot` number.

## Notes

- The relation between tokens and lemmas is one-to-many: in some cases a single token corresponds to more than one lemma, for example the token "ón" ('from the') corresponds to the lemmas "ó" ('from') and "an" ('the').
 
 - In some cases of indeterminacy I had to take an executive decision as to what is a lemma and what isn't, whether a token is a word form of another lemma or whether it is a lemma in its right, and so on. My decisions may have been arbitrary but they are consistent: I have tried to apply the same thinking to all sentences.

