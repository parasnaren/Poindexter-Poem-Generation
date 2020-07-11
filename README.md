# Poindexter-Poem-Generation
A poem generation model, that generates poems modeled on the famous Christopher Poindexter's poems and quotes.

### Dataset

The Christopher Poindexter poems and quotes are obtained by:
  - Scrapping [goodreads](https://www.goodreads.com/author/quotes/8197776.Christopher_Poindexter)
  - OCR text extraction from his poems on [Pinterest](https://in.pinterest.com/daijahvigo/christopher-poindexter/)

All the poems and quotes are stored in the file **quotes.txt** delimited by line breaks **\n**

### Code

Two models have been created.
  - Using [**word-level embeddings**](https://github.com/parasnaren/Poindexter-Poem-Generation/blob/master/Poem%20Generation%20(word-level).ipynb)
  (*Generates text one word at a time*)
  - Using [**character-level embeddings**](https://github.com/parasnaren/Poindexter-Poem-Generation/blob/master/Poem%20Generation%20(char-level).ipynb)
  (*Generates text one character at a time*)
