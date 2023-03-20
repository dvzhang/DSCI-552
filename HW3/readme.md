# DSCI HW 3 & 4 
> By Tianzuo Zhang
>
> USC-ID:8849-5991-30
> 
> My contact info: [Twitter](https://twitter.com/dvzhangtz) [Linkedin](https://www.linkedin.com/in/tianzuo-zhang/) Wechat: dvzhangtz

## 1. Time Series Classiﬁcation Part 1: Feature Creation/Extraction
An interesting task in machine learning is classiﬁcation of time series. In this problem, we will classify the activities of humans based on time series obtained by a Wireless Sensor Network.

### (a) Download
Download the AReM data from: https://archive.ics.uci.edu/ml/datasets/ Activity+Recognition+system+based+on+Multisensor+data+fusion+\%28AReM\ %29 . The dataset contains 7 folders that represent seven types of activities. In each folder, there are multiple ﬁles each of which represents an instant of a human performing an activity. 1 Each ﬁle containis 6 time series collected from activities of the same person, which are called avg rss12, var rss12, avg rss13, var rss13, vg rss23, and ar rss23. There are 88 instances in the dataset, each of which contains 6 time series and each time series has 480 consecutive values.

### (b) EDA
Keep datasets 1 and 2 in folders bending1 and bending 2, as well as datasets 1, 2, and 3 in other folders as test data and other datasets as train data.

### (c) Feature Extraction
Classiﬁcation of time series usually needs extracting features from them. In this problem, we focus on time-domain features.

i. Research what types of time-domain features are usually used in time series classiﬁcation and list them (examples are minimum, maximum, mean, etc).

ii. Extract the time-domain features minimum, maximum, mean, median, standard deviation, ﬁrst quartile, and third quartile for all of the 6 time series in each instance. You are free to normalize/standardize features or use them directly.2  Your new dataset will look like this:
where, for example, 1st quart 6 , means the ﬁrst quartile of the sixth time series in each of the 88 instances.

iii. Estimate the standard deviation of each of the time-domain features you extracted from the data. Then, use Python’s bootstrapped or any other method to build a 90% bootsrap conﬁdence interval for the standard deviation of each feature.

iv. Use your judgement to select the three most important time-domain features (one option may be min, mean, and max).

## 2. ISLR 3.7.4