## Ideas help and code performance analysis:
Query:
```
Read this file.
Let me ask you a question about the difference between calculate_bigram_probabilities() for japanese vs (russian or finnish) functions?

I don't understand why japanese ones use tokenizers - would it be better if others did, too?

The results for perplexity metric for japanese is absurd (10e18 range, while finnish and russian is at solid 1k-5k)
```
Answer:
```
The notebook begins with importing modules (including janome and nltk) and setting reproducibility parameters, followed by dataset loading. For language-specific bigram probabilities, it defines tokenization approaches that diverge based on language. Specifically:

Finnish uses nltk.word_tokenize, separating words directly.
Russian likely uses a similar direct tokenization approach (though the exact function hasn’t appeared in these initial lines).
Japanese requires a unique setup: it imports janome and leverages its Tokenizer class, indicating a dependency on specialized tokenization for segmentation of Japanese text.
I'll locate and review the calculate_bigram_probabilities function definitions for these languages to address your question about using tokenizers across languages and to understand the perplexity disparity you observed.
```
----
Query:
```
```
Answer:
```
```
----
Query:
```
```
Answer:
```
```
----
Query:
```
```
Answer:
```
```
----
Query:
```
```
Answer:
```
```
----
Query:
```
```
Answer:
```
```
----
Query:
```
```
Answer:
```
```
----
Query:
```
```
Answer:
```
```
----
Query:
```
```
Answer:
```
```
----
Query:
```
```
Answer:
```
```
----
Query:
```
```
Answer:
```
```
----
Query:
```
```
Answer:
```
```
