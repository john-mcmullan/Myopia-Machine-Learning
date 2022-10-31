# Goals

Taking raw data and fiting it to machine learning models to see if there is a clustering algorithm that can cluster patients into distinct groups.

### Part 1: Prepare the Data

After scaling and removing unnessary data points our final result looks like this

![2022-10-31 08_40_53-Window](https://user-images.githubusercontent.com/100164773/199010334-6b6bb29e-e065-47a9-b195-8f587ff995f4.png)

### Part 2: Apply Dimensionality Reduction

After putting our dataframe through principle component analysis it looks like this

![2022-10-31 08_43_33-Window](https://user-images.githubusercontent.com/100164773/199011332-a5baadec-a39f-4dff-9649-877c9a667efd.png)

With ratio of .9187

Then used tsne to create a scatter plot and came up with this result

![2022-10-31 08_48_10-Window](https://user-images.githubusercontent.com/100164773/199011630-bb8e6715-d469-4624-a9d6-03e94eda14fa.png)

### Part 3: Perform a Cluster Analysis with K-means

K-Means produced this dataframe and line chart:

![2022-10-31 08_50_44-Window](https://user-images.githubusercontent.com/100164773/199012754-4ef3f172-c589-402f-81c2-050a10e404fa.png)

![2022-10-31 08_50_48-Window](https://user-images.githubusercontent.com/100164773/199012769-c08a7d8c-bcbc-4b6e-9ffb-4c519ccacd0a.png)

When put through Cluster Analysis we see three distinct clusters

![2022-10-31 08_56_45-Window](https://user-images.githubusercontent.com/100164773/199012979-e61e489c-6f3e-41f1-8494-b0f5fc930e9f.png)


### Part 4:Recommendation

There are clear recommendations to study our patients. 

Using TSNE is not a viable option to cluster our patients to study. The correct method is to use PCA and a Cluster Analysis using K-Means. This will lead to seeing three clear clusters of patients to study.

It would be interesting to see if these clusters hold as the sample size grows.

## Rubric

[Unit 20 Homework Rubric](https://docs.google.com/document/d/1046PZMnFwxcNkyIewuJc_RYhaErY42HoNUKORkh18A4/edit)




