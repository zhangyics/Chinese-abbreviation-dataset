# A corpus of Chinese abbreviation

This is the dataset released by the paper "A Chinese Dataset with Negative Full Forms for General Abbreviation Prediction" [[pdf]](https://arxiv.org/pdf/1712.06289.pdf).

Abbreviation is a common phenomenon across languages, especially in Chinese. In most cases, if an expression can be abbreviated, its abbreviation is used more often than its fully expanded forms, since people tend to convey information in a most concise way. For various language processing tasks, abbreviation is an obstacle to improving the performance, as the textual form of an abbreviation does not express useful information, unless it's expanded to the full form. Abbreviation prediction means associating the fully expanded forms with their abbreviations. However, due to the deficiency in the abbreviation corpora, such a task is limited in current studies, especially considering general abbreviation prediction should also include those full form expressions that do not have valid abbreviations, namely the negative full forms (NFFs). Corpora incorporating negative full forms for general abbreviation prediction are few in number. In order to promote the research in this area, we build a dataset for general Chinese abbreviation prediction, which needs a few preprocessing steps, and evaluate several different models on the built dataset.

# Annotation Format
On the right of the colon is the full form expression of a word. The full form expression is segmented and labeled with Part-of-speech tags. On the left of the colon is the abbreviation of the full form expression. If the full form expression does not have valid abbreviations, a special notation "n" is marked on the left of the colon.

