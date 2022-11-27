# nlp-stylometry-test


 It works using Burrows' Delta. Essentially you find the most common n words in a dataset, then for each user get their frequency for each most common word (if n=3 and your most common words are ["the", "a", "I"] and your corpus is "the fish in the ocean is a large one" then your frequency array would be [2/9, 1/9, 0/9]), then for each user compare their normalized frequency arrays with cosine similarity and print the 20 other users with the highest similarity scores.
