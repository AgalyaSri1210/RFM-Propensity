RFM Propensity Project

Steps involved:

1. importing packages
2. Generating dataset
3. RFM Modelling:
   
       * using lambda function creating the recency, frequency and monetary features from datetime, count of source_case id and total price respectively.
   
       * Ranking the RFM (recency frequency and monetary) in the way that R is inversely proportional to FM.
   
       * Concating the ranks and converting it as a score.
   
       * Grouping the customers as per the loyalty level using the score.
   
5. Visualizing the insights.
