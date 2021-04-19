# Guidelines for selecting words

## What we need

-   \~400 words
-   suitable for children between 2 and 7 years of age
-   equally spread out in terms of age of acquisition
-   some very easy words (spoken by most 2-year-olds) and some very difficult ones (spoken by very few 7-year-olds)

## Columns in the data file

-   `german` : word in German
-   `word_freq` : how frequent is the word in the language (normalized lemma frequency per million)
-   `familiarity_m` : how familiar are adults with the concept
-   `aoa_german_b_m` : age of acquisition rating according to Brysbaert et al
-   `aoa_german_s_m` : age of acquisition rating according to Schröder et al
-   `aoa_german_l_m` : age of acquisition rating according to Łuniewska et al
-   `aoa_german_comb` : combined age of acquisition rating for all german sources
-   `clt` : is the word included in the CLT?
-   `english` : British English translation
-   `aoa_mor`0 : age at which children could name pictures according to Morrison et al. (1997)
-   `aoa_rating_english`: english age of acquisition rating
-   `select` : type "x" to select the word

## Things to consider

-   Age of acquisition ratings are not correct in terms of absolute age. However, they tend to be correct in terms of relative difficulty. That is, a waord that has a rated age of acquisition of 2.5 years is probably not learned at 2.5 years of age, but it's likely to be learned earlier than a word that has a rating of 3.5 years.

## Select words based on the following principles

-   all words that are part of the CLT (already marked in the `select` column)
-   avoid words that are likely to be used by only a subgroup of children (e.g. words that are associated with a certain hobby)
-   avoid words that have changed their meaning recently  
