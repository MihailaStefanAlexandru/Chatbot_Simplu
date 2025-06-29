# Construirea unui chatbot pentru întrebări frecvente folosind python

## Obiectiv

Crearea unui chatbot care răspunde la întrebări simple definite de utilizator

## Tehnologii

| Biblioteca | Descriere | Utilizare | Link |
| ---------- | --------- | --------- | ---- |
| Questions-Answer Dataset | set de date cu întrebări și răspunsuri generate manual pentru a fi folosit în cercetarea academică | A fost utilizat pentru a crea seturile de antrenare, validare si testare | [QA Dataset](https://www.cs.cmu.edu/~ark/QA-data/) |
| Natural Language Toolkit (NLTK) | bibliotecă cu implementări pentru clasificare, tokenizare, stemming, tagging, parsare și argumentare semantică | A fost folosită pentru curățarea și tokenizarea textului | [NLTK Documentation](https://www.nltk.org/) |
| Scipy | colecție de algoritmi matematici și funcții construite pe numpy și oferă comenzi și clase high-level pentru utilizarea datelor | A fost folosită pentru implementările funcțiilor cosine și eucledean | [Scipy Documentation](https://docs.scipy.org/doc/scipy/) |
| Pandas | unelte simplu de folosit pentru structuri de date și analiză de date | A fost folosită pentru citirea și stocarea setului de date în vectori care facilitează prelucrarea ulterioară a textului | [Pandas Documentation](https://pandas.pydata.org/docs/) |
| Sentence-Transformers | modul python care este folosit pentru accesarea, utilizarea și antrenarea modelelor embedding și rernaker | A fost folosit pentru modelul preantrenat pentru words embedding | [SBERT Documentation](https://sbert.net/) |

## Pasi

- [x] Tokenizarea întrebărilor
- [x] Compararea similarității între întrebări
- [x] Găsirea celui mai apropiat răspuns
- [x] UI simplă CLI (input + răspuns)

## Resurse

[Euclidian Distance and Cosine Similarity](https://nikoskalikis.medium.com/text-similarity-euclidian-distance-vs-cosine-similarity-3a1167f686a)

[Word Embeddings](https://www.geeksforgeeks.org/nlp/word-embeddings-in-nlp/)

[Semantic Similarity](https://www.geeksforgeeks.org/nlp/different-techniques-for-sentence-semantic-similarity-in-nlp/)

[Text Similarity](https://medium.com/msackiit/what-is-text-similarity-and-how-to-implement-it-c74c8b641883)

