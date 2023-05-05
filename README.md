# CryptoClustering

The puprose of the code in this respository is to analyze crypotcurrency and cluster it into groups.

## Methods

- Scale data to enable analysis
- Determine best number of clusters by producing an elbow plot
- Use optimal number of clusters to cluster the data using Kmeans
- Process the data using PCA to condense multiple features into 2
- Determine best number of clusters for PCA Data using an elbow plot
- Use optimal number of clusters to cluster PCA data using Kmeans
- Composite cluster plots for original and PCA data for comparison

## Results

The following is the result of the elbow plot of all of the data:
![image](https://user-images.githubusercontent.com/118322354/236559349-7c2771a5-eebb-4019-a062-b733efc60328.png)

The following is the data clustered using Kmeans:
![image](https://user-images.githubusercontent.com/118322354/236559511-ee69b0f8-c5cc-482a-a087-f07706f5fb13.png)

The following is the elbow plot for the PCA data:
![image](https://user-images.githubusercontent.com/118322354/236559653-bc4aef2e-f140-4dc3-bc82-effb6ec8177a.png)

The following is the PCA data clustered using Kmeans:
![image](https://user-images.githubusercontent.com/118322354/236559783-8c20e4f1-a8f5-404c-a6da-e3696d730f4d.png)

The following are the two elbow plots plotted together, the original plot is in blue and the PCA plot is in red:
![image](https://user-images.githubusercontent.com/118322354/236560122-faa6dcb2-0736-4db2-83a8-5da05ae06e83.png)

The following are the two cluster plots plotted together, the round markers are the original data, the shaped markers are the PCA data:
![image](https://user-images.githubusercontent.com/118322354/236560695-1843e789-81f1-4cac-ad1c-20bda38ceb44.png)
