# Search-Engine

### A python base web search engine to generate list of songs and lyrics based on user's mood.

The project objective is to create a search engine that takes user input in the form of an emotion that the user is feeling and lists out songs and corresponding lyrics which match that emotion.
User can enter their mood and get corresponding songs and lyrics accordingly.
<br>


### Sections
<hr>

- [Techniques Used](#Techniques-Used)
- [Search Algorithm](#Search-Algorithm)
- [Results](#results)

<hr>
<br>

Picked a data source that would guarantee to have all songs ever made and that it is frequently updated so that we have an updated repository as well.
www.azlyrics.com

## Techniques Used
[back to top](#sections)

- Scraping the site to get all the song and lyrics --> SiteSucker

- Cleaning the data --> Spacy

- Tf-idf and vectorization --> Spacy

- Array of all songs --> Numpy.array()

- Cosine Similarity for matching query and results -->sklearn.metrics

- Integration with HTML webpage as Frontend --> Flask

- User Testing
<br>
<br>

## Search Algorithm

[back to top](#sections)

The search algorithm is based on mapping vector values

The user input is converted into its vector representation.

All the songs in the database are vectorized and stored in an array.

The cosine similarity is calculated between the user query and the available songs vector matrix.

The closest matching values and hence the corresponding songs are returned to the user on the web page.

<br>
<br>

## Results

[back to top](#sections)

[](./images/Picture1.png)

[](./images/Picture2.png)
<br>
