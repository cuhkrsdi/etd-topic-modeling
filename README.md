# etd-topic-modeling
The electronic theses and dissertations topic modeling project was conducted by the Chinese University of Hong Kong Library (CUHK Library). 

## Observation

### Trend of Hong Kong Related Thesis
Based on the extracted data, our team found that there were a total of 20,423 theses in the ETD collection. Of these, 3,878 were related to Hong Kong studies. This indicates that approximately 20% of the total postgraduate theses are associated with the theme of Hong Kong. Base on the dataset, our team had below findings:

- The total number of theses showed an increasing trend over time. (Figure 2)
- The proportion of Hong Kong-related theses exhibited a decrease among the overall research topics. (Figure 1)
- A change point was identified in the year 1995. (Figure 2) 
 
In concluded, the gap between the number of Hong Kong-related theses and the total number of theses increased. This indicates a significant divergence in research topics, with a lesser emphasis on Hong Kong-related subjects post-1995. Our team has a hypothesis that this may be related to two reasons:

- There has been a significant increase in the number of research theses across various disciplines in recent years.
- The business faculty in Hong Kong has shown less interest in Hong Kong-related fields.

#### <center>Figure 1 - Proportion of Hong Kong Related Thesis</center>
![alt text](/image/statistic1.png)
#### <center>Figure 2 - Compared the Trends</center>
![alt text](/image/statistic2.png)

### Five Different Clusters

By employing k-means clustering, the ETD theses were segregated into five distinct clusters:
- Marketing and Business: 1115 titles
- Cultural and Political: 792 titles
- Urbanization and Land use: 788 titles
- Population: 656 titles
- School and Education: 527 titles

![alt text](/image/clustering.png)

## Research Cycle
- Data Collection: The data were cataloged in previous years. Our team extracted this valuable data from Alma by conducting simple queries.
- Data Processing: Based on the thesis titles and subject headings created by the cataloguer, our team extracted the titles related to Hong Kong from the data.
- Topic Modeling: Base on sentence embedding, discover similar titles.
- Clustering: Divide all the titles into five different clusters using the K-means algorithm.
 
## Acknowledgement
CUHK Digital Repository (Electronic Theses & Dissertations Collection): https://repository.lib.cuhk.edu.hk/en/collection/etd

BERTopic website: https://maartengr.github.io/BERTopic/index.html
