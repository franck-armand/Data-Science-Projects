# __<u>Movie Rating Analysis</u>__

Many individuals decide whether or not to watch a movie based on the ratings offered by viewers. So, for the Movie Rating Analysis work, we use a dataset including information about the ratings given by each spectator.
The dataset at hand can be downloaded [here](https://storage.googleapis.com/kaggle-data-sets/409851/2315045/bundle/archive.zip?X-Goog-Algorithm=GOOG4-RSA-SHA256&X-Goog-Credential=gcp-kaggle-com%40kaggle-161607.iam.gserviceaccount.com%2F20220629%2Fauto%2Fstorage%2Fgoog4_request&X-Goog-Date=20220629T150255Z&X-Goog-Expires=259199&X-Goog-SignedHeaders=host&X-Goog-Signature=43b1c5eb01c96e3eefdaa50d28ada70378c4fce991f2d4dfe6c4bcf78e372a11e7e31feb78af6fd3fdc80459ef75ba4d5ec458a1ae01b437d0d29bf6e03987afc57c810d7a0e0ffe07c490501988177f9661135b6f0fad2d561a432b902ee7b31a017261050ca47dcf931f557ca31f86eee8724b5b21774b555b9863813d2fa3d03a69ff0c6071d1fa183b5fde068de0de37279ed1b4ed301def5e84f4e16001a000405bdf057080494ffcc7bf1fb921d19e85c40fbd17f2fd2d2180eb7164faf6b87c97858b9976591d4899177bc58f4ee149b185b61e14fc9c8ee6a1e7680d4ff6033ceccdf75e30929b4ba238162a1d9c36375c39466222bfbdbacdac2333)

### 1. <u> _Dataset_</u>:
The dataset is mainly composed of two files:
- A file containing data about the __movie Id, title and the genre__ of the movie.

|   Id | Title                                                | Genre               |
|-----:|:-----------------------------------------------------|:--------------------|
|   10 | La sortie des usines Lumière (1895)                  | Documentary|Short   |
|   12 | The Arrival of a Train (1896)                        | Documentary|Short   |
|   25 | The Oxford and Cambridge University Boat Race (1895) | nan                 |
|   91 | Le manoir du diable (1896)                           | Short|Horror        |
|  131 | Une nuit terrible (1896)                             | Short|Comedy|Horror |

- A file containing user __id, movie id, ratings given by the user and the timestamp__ of the ratings.

|   User |               Id |   Ratings |   Timestamp |
|-------:|-----------------:|----------:|------------:|
|      2 | 499549           |         9 | 1.37675e+09 |
|      2 |      1.30559e+06 |         8 | 1.37674e+09 |
|      2 |      1.42854e+06 |         1 | 1.37131e+09 |
|      3 |  75314           |         1 | 1.59547e+09 |
|      3 | 102926           |         9 | 1.59015e+09 |

---
### 2. <u> _Result analysis_</u>:
- __Movie Ratings Distribution__

...
![](./result_analysis/1.png)
### **_TODO__**
- [x] Data loading
- [x] Data exploratory 
- [ ] Data visualization 
- [ ] Complete readme