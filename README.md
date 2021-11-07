# Music Recommendation Engine
With the number of songs as well as music streaming websites being released each year growing exponentially the need for a good music recommender system is now more than ever. This
paper presents a hybrid recommender system which incorporates the contextual multi-armed bandit problem wherein each arm is a feature vector containing the users’ preferences and the song’s
details. Our model makes use of context-based filtering methods which can further be boosted with collaborative filtering to recommend the best possible songs to the user. The model recommends
songs to the user, asks the user to rate the songs (reward), and based on the ratings, it computes the Euclidean distance between the features of the toprated songs and other non-rated songs and further
recommends a new set of songs which have the least distance. We also present a solution to deal with the cold-start problem which arises in most recommender systems. Our model performs highly
and is capable of reliably recommending good songs based on the user’s rating history.
