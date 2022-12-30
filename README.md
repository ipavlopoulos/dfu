# Distance from Unimodality for the Assessment of Opinion Polarization

__Purpose__: Commonsense knowledge is often approximated by the fraction of annotators who classified an item as belonging to the positive class. Instances for which this fraction is equal to or above 50% are considered positive, including however ones that receive polarized opinions. This is a problematic encoding convention that disregards the potentially polarized nature of opinions and which is often employed to estimate subjectivity, sentiment polarity, and toxic language.
 
__Methods__: We present the distance from unimodality (DFU), a novel measure that estimates the extent of polarization on a distribution of opinions and which correlates well with human judgment. We applied DFU to two use cases. The first case concerns tweets created over nine months during the pandemic. The second case concerns textual posts crowd-annotated for toxicity.

__Results__: We specified the days for which the sentiment-annotated tweets were determined as polarized based on the DFU measure and we found that polarization occurred on different days for two different states in the USA. Regarding toxicity, we found that polarized opinions are more likely by annotators originating from different countries. Moreover, we show that DFU can be exploited as an objective function to train models to predict whether a post will provoke polarized opinions in the future.
 
The code is wrapped into `lib.py` and three notebooks are shared with all of our experiments. All the data are included in this repository.

Please cite us as:
```
@article{pavlopoulos-likas-2022,
    title = "Distance from Unimodality for the Assessment of Opinion Polarization",
    author = "Pavlopoulos, John  and Likas, Aristidis",
    journal = "Cognitive Computation",
    doi = "10.1007/s12559-022-10088-2",
    year = "2022",
}
```
