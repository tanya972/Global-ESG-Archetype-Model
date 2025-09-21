# Global-ESG-Archetype-Model

## Background  
The paper *A Machine Learning and Panel Data Analysis of N₂O Emissions in an ESG Framework* found fertilizer use and agricultural intensity to be the main drivers of global nitrous oxide emissions, while institutional quality and R&D acted as mitigating factors. However, its analysis assumed consistent effects across countries and highlighted the lack of revealing latent heterogeneity and cluster-specific dynamics.  

## Our Approach  
We use **spectral clustering** to fill in the gaps.  
<img width="1484" height="721" alt="image" src="https://github.com/user-attachments/assets/cf5ff1d2-f288-4ea7-aa5d-91c11a295957" />

## Results  
Our spectral clustering approach revealed highly heterogeneous effects across country groups:  

- **Fertilizer use**: insignificant in all clusters once fixed effects were added.  
- **Regulatory quality**: negative in Cluster 1 (high-population, low-income, –0.12), slightly positive in Cluster 2 (low-population, low-income, +0.05).  
- **R&D spending**: positive in Cluster 1 (+0.18), negative in Cluster 2 (–0.09).  
- **Rule of law**: negative in Cluster 1 (–0.15), positive in Cluster 3 (low-population, high-income, +0.11).  
- **Fertility rate**: weakly negative in Cluster 3 (–0.04), negligible elsewhere.  
- **Unemployment**: insignificant across all clusters.  

## Takeaway  
Our results highlight both the variation in **sign** and the smaller, less certain **coefficient magnitudes** compared to the original paper, showing that ESG–emission relationships are highly **cluster-dependent**.


