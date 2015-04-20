# CMSC498J-Movie-Reviews
Main repository for the CMSC498J project

<b>Review dataset:</b> <a href="http://snap.stanford.edu/data/web-Movies.html">SNAP page</a>

<b>Web Crawlers:</b>
<ul><li>Chrome add on: webscraper.io</li>
<li>Python Packages: Beautiful Soup and <a href="http://docs.python-requests.org/en/latest/index.html">Requests</a></li>
<li>Node.js: <a href="https://www.npmjs.com/package/imdb-api">Alternative IMDB API</a>
</ul>

<b>Sentiment Analysis:</b>
<ul><li>NTLK with <a href="http://nltk-trainer.readthedocs.org/en/latest/">NTLK Trainer</a></li>
<li>Positive/Negative classification with NTLK, no negator words taken into account <a href="http://andybromberg.com/sentiment-analysis-python/">tutorial</a>.</li>
<li>Utilizing <a href="http://stackoverflow.com/questions/21107075/classification-using-movie-review-corpus-in-nltk-python">movie review corpus</a> in NLTK</li>
<li><a href="http://www.nltk.org/book_1ed/">NTLK Book</a></li>
</ul>

<b>Current Ideas</b>
<ul><li>Do helpful common words/sentiment evolve over time?</li>
<li>What predicts strong reviews? (Sentiment, length, originality, date, reviewer, genre)</li>
<li>Do good reviewers only review good movies? Do bad reviewers review bad movies?</li>
<li>Do the words in reviews help define a director's brand? Are actors type casted by other directors based off that?</li>
<li>Strength of Triadic closure with actors in movies/actors with directors. We can project the network into actor->actor by saying actors are connected if in the same movie/worked with the same director.</li>
</ul>
