# Anime Recommendation System

This project is an Hybrid Recommendation System for users that rated different animes. It is based on both user preferences and anime ratings.


## Dataset 
The dataset contains information on user preference data from 73,516 users on 12,294 anime. Each user is able to add anime to their completed list and give it a rating and this dataset is a compilation of those ratings.
### Anime.csv

| **Variable** | **Definition** |
| :-------- | :------- |
| **anime_id :** | myanimelist.net's unique id identifying an anime. |
| **name :** | full name of anime. |
| **genre :** | comma separated list of genres for this anime. |
| **type :** | movie, TV, OVA, etc. |
| **episodes :** | how many episodes in this show. (1 if movie). |
| **rating :** | average rating out of 10 for this anime. |
| **members :** | number of community members that are in this anime's "group". |

### Rating.csv

| **Variable** | **Definition** |
| :-------- | :------- | 
| **user_id:** | non identifiable randomly generated user id. |
| **anime_id:** | the anime that this user has rated. |
| **rating:** | rating out of 10 this user has assigned (-1 if the user watched it but didn't assign a rating). |

I do not have any rights on the dataset. It is available for access in: 
https://www.kaggle.com/datasets/CooperUnion/anime-recommendations-database

## Run on your PC

Clone the project

```bash
  git clone https://github.com/cagkangrsy/anime_recommendation_system
```

Go to project directory

```bash
  cd anime_recommendation_system
```

Run the notebook.





  
