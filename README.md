# Poindexter-Poem-Generation
A poem generation model, that generates poems modeled on the famous poet **Christopher Poindexter**.

### Dataset

The Christopher Poindexter poems and quotes are obtained by:
  - Scrapping [goodreads](https://www.goodreads.com/author/quotes/8197776.Christopher_Poindexter)
  - OCR text extraction from his poems on [Pinterest](https://in.pinterest.com/daijahvigo/christopher-poindexter/)
  
*Notebook [Quote Scrapper](https://github.com/parasnaren/Poindexter-Poem-Generation/blob/master/Quote%20Scrapper.ipynb) contains the code used for scrapping.*

All the poems and quotes are stored in the file [**quotes.txt**](https://github.com/parasnaren/Poindexter-Poem-Generation/blob/master/quotes.txt) delimited by line breaks **\n**

### Code

Two models have been created, using Bidirection LSTM and GRU respectively.
  - Using [**word-level embeddings**](https://github.com/parasnaren/Poindexter-Poem-Generation/blob/master/Poem%20Generation%20(word-level).ipynb)
  (*Generates text one word at a time*)
  - Using [**character-level embeddings**](https://github.com/parasnaren/Poindexter-Poem-Generation/blob/master/Poem%20Generation%20(char-level).ipynb)
  (*Generates text one character at a time*)
  
### Output

- **Character-level**

    **Input text:** *Love*

    **Output generated poem:** *Love my sleepy eyes but I am starting to see things differently because of you. Now I see beans on in the ashes.
    She was passionate about the rain and I was passionate about the way she loved it.*


- **Word-level**

    **Input text:** *My dear*

    **Output generated poem:** *my dear come i will never be a morning person
    for the moon and I are too much in love with the way her loneliness fell softly and suddenly asleep in his chest
    we we love them only to uncurl our fingers later and softly give them back to the earth
    sing until your lungs cave in be silent until the world*

