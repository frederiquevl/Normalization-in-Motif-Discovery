# Normalization in Motif Discovery
Motif discovery can be used as a subroutine in many time series data mining tasks such as classification, clustering and anomaly detection. Motifs represent two or more highly similar subsequences of a time series. The vast majority of the motif discovery methods implicitly assume that subsequences need to be normalized before determining their similarity. While normalization is widely adopted, it may affect the discovery of motifs. We examine the effect of normalization on motif discovery using 96 real-world time series. To determine if the discovered motifs are meaningful, all observations of each time series are labeled. These labels indicate the underlying states of the system generating the time series. Our experiments show that in over half of the considered cases, motif discovery is negatively affected by normalization. Evidently, the assumption underlying normalization does not always hold for real-world time series and thus should not be uncritically adopted.

This repository includes:
- Code used to obtain results.
- Time Series mentioned in section 4.1.
- Results of all other time series. These time series can be retrieved from the UCR Archive.
