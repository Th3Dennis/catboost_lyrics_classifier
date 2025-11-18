# Genre classifier

Hey there! I worked on a project for my Federal Vocational Baccalaureate, and the idea was to create a new AI centered around songs and their genres. I used a Catboost classifier model for this.

The project involved digging into a bunch of song data covering different genres. The goal was to make the AI smart enough to recognize patterns in songs and accurately put them into their respective genres.

I chose the Catboost classifier model because it's good at handling different features and does a solid job predicting stuff. I fed it loads of examples with labeled genres during the training process. This helped the model figure out the connections between different musical elements and genres.

As the AI went through training, it got better at generalizing its understanding of songs and genres. This meant it could classify new songs it hadn't seen before. The more it learned, the more accurate it became.

Beyond the tech stuff, the project also made me think about the bigger picture. Like, how does AI fit into the music scene, and what does it mean for human creativity? It sparked discussions about how machines and humans could work together.

In the end, this project shows what happens when tech and creativity come together. By training an AI to focus on songs and genres, I wanted to explore how machine learning can play a role in music, joining in on the ongoing conversation about where AI fits in our artistic experiences.

## AI Steps

### Train

1. **Get the optimized data which has already been lemmatized and stopwords where removed from** - This creates a word occurrence frequency (sparse) matrix.
2.  **Vectorize the data using TFIDF**
3. **Split the data to 85% training and 15% test data**
4. **Train model**

### Test

1. **Get lyrics from user**
2. **Lemmatize Text and remove stopwords**
3. **Vectorize the data**
4. **Predict Genre**


    
