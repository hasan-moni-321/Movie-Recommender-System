## Movie-Recommender-System

Recommendation Technique is becoming very popular day by day. Some company for example, Netflix the use recommendation technique. Recommendation technique is 
very useful for user because when a viewer click a movie/drama or any other series, nerest series for next episode will appear in front of the window.

I solved Kaggle movie-recommender-dataset. Dataset will be found here https://www.kaggle.com/rounakbanik/movie-recommender-systems 

### Name of recommendation techniques that I used
1. Colaborative Recommendation
2. Content Based Recommendation
3. Hybrid Recommendation

### What I did:-

1. In Colaborative Recommendation I used SVD(Singular Value Decomposition) and predict next recommended movie.
2. In Content Based Recommender I did in two way 
    i) Recommender based on movie description.
          In movie description I used tagline and overview columns.
    ii) Recommender based on metadata.
          In metadata I used cast, crew, keywords and genres columns
    
3. in Hybrid Recommendation I used both Colaborative and Content Based Recommendation. 





## Netflix-Movie-Recommendation

Netflix is very popular site around the world. And day by day it's popularity increasing dramatically. I solved Kaggle Netflix-Recommendation-movie problem. 
The link of this dataset is here https://www.kaggle.com/laowingkin/netflix-movie-recommendation

### Necessary Library
1. numpy
2. pandas
3. matplotlib
4. seaborn
5. surprise


### What I did
1. There are no movie ID for every movie. For this I took movie ID using array. Using array because there need lot's of number, to overcome kernel restarting 
I used array for ID.
1. There are 4 big dataset. I took only 1 dataset for simplicity. From this 1 dataset I took 500000 rows, so that can train model soon and to reduce time
2. Then U drop some rows which are less important using quantile. 
3. In simple recommendation I used Rating and Movie_Id columns.
4. In collaborative recommendation I used SVD(singular value decomposition) 
5. In Pearson's R correlation, at first I made a pivot table, And then correlation with given movied. 

