# TripR-2020Large dataset

We present the **Trip**advisor **R**estaurant **2020** **Large** (TripR-2020Large) dataset, a new set of restaurant reviews from Tripadvisor suitable to evaluate Decision Making models that incorporate Sentiment Analysis considering multiple experts.

The Trip-2020Large dataset provides the reviews of 132 experts evaluating 4 restaurants located in the city of London. Not all experts evaluate all the restaurants. The dataset collects 474 reviews. In particular, each review is given by attributes:

- Concerning the restaurant: name, identifier code, location name, and location identifier code.
- Concerning the expert: name, identifier code, and location name.
- Concerning the review: title, body, date, general rating, food rating, service rating, and value rating.

We show the main features of the TripR-2020Large dataset:

| Experts      | Restaurants | Reviews | Sentences |
| ----------- | ----------- | ----------- | ----------- |
| 132 | 4 | 474 | 2,522 |

We annotate the TripR-2020Large dataset at aspect level by depicting the 474 reviews into 2,522 sentences. The dataset is annotated by three experienced researchers following the annotation guidelines TripR-2020Large, that follows the official SemEval-2016 annotation manual. There is substantial agreement of 0.66 between the three annotators based on the Fleiss’s coefficient metrics. We show the main features of the annotation:

| Features      | Value |
| ----------- | ----------- |
| Num. Sentences      | 2,522       |
| Num. Opinions   | 2,586        |
| Num. Pos. Opinions | 2,107 |
| Num. Neg. Opinions | 397 |
| Aspect categories | Restaurant, Food, Service, Drinks, Ambience and Location|
| Polarities value | positive, negative and neutral|

The 474 reviews from the dataset are split into 2,522 sentences. We labelled 2,586 opinions of which 2,107 are positive, 397 are negative and the rest are neutral opinions. Each sentence can have at least an aspect category annotated (Restaurant, Food, Service, Drinks, Ambience and Location).


We consider the TripR-2020Large dataset to evaluate the **C**rowd **D**ecision **M**aking guided by **S**entiment **A**nalysis (**CDM-SA**) model, which is a large scale decision making model with sparse representation able to process evaluations from social networks for leveraging the wisdom of the crowd. If desired, the TripR-2020Large dataset can be used for aspect based sentiment analysis tasks without the need of incorporating decision making.


## Example
We show an example of annotation of a review from the TripR-2020Large dataset:

| Sentence  | Aspect | Category | Polarity |
| ----------- | ----------- | ----------- | ----------- |
| Consistently good.	| *implicit* 	| Restaurant	| positive |
| I have been coming for years.	| *implicit* 	| Restaurant	| positive |
| Always good atmosphere and fun people watching.	| atmosphere 	| Ambience	| positive |
| The food is always good and quick.	| food 	| Food	| positive |

The review is split into sentences. First column presents the text of the sentence. Second column is referred to the aspect terms discussed in the sentence. The aspect is *implicit* when the aspect term is not explicitly mentioned in the sentence. Third column is the aspect category to which the aspect term is categorized. Fourth column is the sentiment polarity about each aspect category.



## Citation
Please use the following citation:

```
Under publication
```


## Contact
María Cristina Zuheros Montes - czuheros@ugr.es
