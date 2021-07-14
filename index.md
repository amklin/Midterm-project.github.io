<html>
    <head>
        <title>Midterm Project DHML</title>
    </head>
    <body>
        <h1>Midterm Project</h1>
        <h2>Amanda Lin, Anna Muyan Li</h2>
        <h3>Finding the locations or countries in the poems of Marianne Moore using machine learning and natural language processing.</h3>
        <p>
            <ol>
                <li>The method Word2Vec worked well. Our original dataset of poems was limited, so we utilized a pre-trained model from Gensim, trained on data from Google News. Their model was trained on a bigger dataset, which included place names. <br>
                    This allowed us to find associations between a particular place name and objects associated with it. We defined an association function that would go through the list of poems and return the words with a high association to that place name, as well as the location in which those place names are found.<br>
                </li>
            <li>Our LDA model did not work. We could not find the optimal number for the number of passes and the number of topics for LDA. Additionally, because we used the list of poems as our data, the model could not determine which nouns were location names. 
                <br> If we wanted to improve this model, we could have tried to use an pre-trained model.</li>
            <li>If we had time, we would try Named Entity Recognition (NER). This would allow us to recognize which nouns are proper place names, so we can identify the locations. <br>
            This could probably work hand in hand with our Word2Vec model.
            Once we found all the place names, we can plug it into our association function, and find the related features or locations in that country or near that location. </li>
            </ol>
        </p> 
        <h3>Our resources</h3> 
        <a href="https://www.nltk.org/">NLTK Library</a><br>
        <a href="https://radimrehurek.com/gensim/">Gensim Library</a><br>
        <a href="https://spacy.io/">Spacy Library</a><br>
        <a href="https://docs.python.org/3/library/re.html">re Library</a>
        <br><br>

        <h3>View Our Code!</h3>
        <script src="https://gist.github.com/amklin/e43aee2b7779c658ef223dc52bc0bcc4.js"></script>
    </body>
</html>
