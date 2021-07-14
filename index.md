<html>
    <head>
        <title>Midterm Project DHML</title>
    </head>
    <body></body>
        <h1>Midterm Project</h1>
        <h2>Amanda Lin, Anna Muyan Li</h2>
        <h3>Finding the locations or countries in the poems of Marianne Moore using machine learning and natural language processing.</h3>
        <p>
            <ol>
            <li>The method Word2Vec worked well, and LDA did not. <br>
            We could not find the optimal number for the number of passes and the number of topics for LDA. </li>
            <li>Our dataset is limited, so we utilize pre-trained model from google news because their model is trained on a bigger dataset.</li>
            <li>If we have time, we would try Named Entity Recognition (NER). This will allow us to recognize the names which nouns are proper place names, so we can identity the places.
            This could probably work hand in hand with our Word2Vec model. 
            Once we find all the place name, we can plung it in our association function, and find the related features or locations in that country or near that location. </li>
            </ol>
        </p> 
        <h3>Our resources</h3> 
        <a href="https://www.nltk.org/">NLTK Library</a><br>
        <a href="https://radimrehurek.com/gensim/">Gensim Library</a><br>
        <a href="https://spacy.io/">Spacy Library</a><br>
        <a href="https://docs.python.org/3/library/re.html">re Library</a><br>

        <h3>View Our Code!</h3>
        <script src="https://gist.github.com/amklin/e43aee2b7779c658ef223dc52bc0bcc4.js"></script>
    </body>
</html>
