# Analyzing the Foreign Direct Investment’s effect on Domestic Saving in China with a Machine Learning Approach

## Project Information
* **Author**: Tianji Sun, Data Science students from class of 2024, Duke Kunshan University
* **Instructor**: Prof: Luyao Zhang, Duke Kunshan University
* **Disclaimer**: Submissions to the Final Project for STATS201 Introduction to Machine Learning for Social Science, 2022 Autumn Term (Seven Week - Second) instructed by Prof. Luyao Zhang at Duke Kunshan University.
* **Acknowlegement**: Prof. Luyao Zhang guided the entire project through， Xin Ma (helped with the VM set up)，Yutong Quan for the insigtful peer review.
* **Github page**: https://alexsun12.github.io/stats201/

## Project Summary
* **Background and motivation**
In the globalized economy, Foreign direct investments (FDI) are shifting economical structures. Since the Reform and Opening up, foreign companies and investors are allowed to take part in China’s economy. And they have since then made an impact on China’s economic structure. From Zhang’s(2001) study, FDI will be increasing in China for the foreseeable future, and the increase in FDI will decrease domestic savings in China. As viewing data from 2001 to 2020, FDI in China has increased yearly. In this research, I aim to use historical FDI data from China to analyze its correlation with domestic savings.
* **Research Questions:** Is the increase in foreign direct investment correlated with changes in domestic saving? 
* **Application Scenario:** With causal inference established, we can predict one's trend with the other's change.
* **Methodology:** In this project, machine learning algorithms will be applied to explore the relationship between foreign direct investment and domestic savings. The algorithms I will use include a decision tree, random forest, multi-layer classifier, and Auto-ML. The given data on FDI is based on the FDI’s percentage of GDP. By multiplying the FDI percentage by China's GDP we can have the gross FDI for analyzation. 
* **Expected Results:** From this research, I expect to find China’s domestic savings changes to be negatively correlated with China’s foreign direct investments.
* **Interlecture merits**
  Previous studies regarding foreign direct investments focus mainly on GDP growth and foreign relationships because most studies in this area are published more than five years ago. these studies lack analysis using machine learning models. While applying machine learning models in finance is common, it is not in analyzing regional developments. By applying new algorithms and recent data, I can prove theories and predictions made by previous researchers. This method opens up possibilities to increase the accuracy of future predictions. 

## Table of content
* Data
* Code
* Spotlight
* More on the Author
* Reference


## Code
| Tables        | URL                                                |
| ------------- |:-------------:                                     |
| Process Data     | https://github.com/Rising-Stars-by-Sunshine/Tianji_Sun_Stats201_FinalProject/blob/main/code/Process_Data_Prepare_Final_Project.ipynb |
| Analyze Data | https://github.com/Rising-Stars-by-Sunshine/Tianji_Sun_Stats201_FinalProject/blob/main/code/Analyze_Data_Final_Project.ipynb|   



## Spotlight
#### Research Sumary Poster
![image](https://user-images.githubusercontent.com/117652452/207314492-4e4a42af-d760-4489-bc4a-3069c47465b5.png)

Generated by Canva

#### For Machine Learning Algorithms
![image](https://user-images.githubusercontent.com/117652452/207059549-5cb59953-625c-4f19-a932-f76fa0caff62.png)
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; figure 1. confusion matrix generated by random forest classifier

![image](https://user-images.githubusercontent.com/117652452/207059893-0d81092e-9a9a-4e4a-bb51-e5a188faf421.png)
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; figure 2. confusion matrix generated by multi-layer classifier

![image](https://user-images.githubusercontent.com/117652452/207060741-08fa6e55-78fd-4381-9ce1-ddf554aa5ad2.png)
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; figure 3.linear regression

![image](https://user-images.githubusercontent.com/117652452/207103941-5bd0f614-f696-4aaf-9eaa-001ee740621d.png)
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; figure 4.Auto ML

A confusion matrix present a table that is used to define the performance of a classification algorithm. A confusion matrix visualizes and summarizes the performance of a classification algorithm.(https://www.sciencedirect.com/topics/engineering/confusion-matrix)


         
## More about the Author
![image](https://user-images.githubusercontent.com/117652452/206921127-d87279c7-1e7c-4493-9797-9cb7a8657a6.png
- self-introduction
The author Tianji Sun is a Duke Kunshan University  data science student in class of 2024. His interest lies in applying data analysis and new tools to social problems such as environmental issues, gender inequalities etc.
- final-reflection
    During this research, I have gained a lot of important skills and experiences. From this research, I have learned about different aspects of machine learning, and I have gained invaluable experiences in the mindset of doing research. There are parts of this research that I need to reflect upon. For the literature review, the literature I can find related to this topic is relatively outdated, most research related to domestic saving are published in the 1990s and 2000s. Due to this reason, I can’t find any literature that applies machine learning to this causal inference topic. There are many existing types of research and literature on applying machine learning to finance, and social science, but there is limited research regarding this topic. Without previous research, it is harder to determine the quality of the results.  Also, for the machine learning algorithms to work better, I believe I have to use bigger data sets. The data sets I used have 40 years of annual data, but it wasn’t enough for both training and testing. To achieve optimal results, more data is required. For future research, it is important to see if the data sets are fit for the algorithms. In conclusion, for future research, I should find areas with more existing research and be prepared for unexpected results.

## References

### Data Source
- https://data.worldbank.org/?intcid=ecr_hp_BeltD_en_ext
### Code Source
- [https://github.com/SciEcon/SoK_Blockchain_Decentralization/blob/main/code/Top_DeFi_Decentralization_Visualizations.ipynb](https://github.com/Rising-Stars-by-Sunshine/stats201-tutorial-prediction/blob/main/code/Analyze_Data_Machine_Learning_for_Predicting_Market_Congestion.ipynb)
- https://github.com/Rising-Stars-by-Sunshine/stats201-tutorial-prediction/blob/main/code/Process_Data_Prepare_X_and_Y_for_Classification_and_Regressions.ipynb
### Literature
***** Bibliography:

Abusomwan, Success, and Jessy Ezebuihe. 2017. “Gross Domestic Savings and Gross Capital: What Matters to Their Formation in an Era of Economic Regression in Nigeria?” Oradea Journal of Business and Economics 2 (2): 45–55. https://doi.org/10.47535/1991ojbe026.

Aqeel, Anjum, and Mohammed Nishat. 2004. “The Determinants of Foreign Direct Investment in Pakistan.” The Pakistan Development Review 43 (4II): 651–64. https://doi.org/10.30541/v43i4iipp.651-664.

Aziz, Saqib, Michael Dowling, Helmi Hammami, and Anke Piepenbrink. 2022. Machine Learning in Finance: A Topic Modeling Approach. St. Louis: Federal Reserve Bank of St Louis. doi:https://doi.org/10.1111/eufm.12326. https://login.proxy.lib.duke.edu/login?url=https://www.proquest.com/working-papers/machine-learning-finance-topic-modeling-approach/docview/2683838187/se-2.

Bayar, Yılmaz. 2014. “Financial Development and Domestic Savings in Emerging Asian Countries.” Theoretical and Applied Economics XXI (7): 55–66. https://doaj.org/article/18bd7423034a4a7c91cb78642cd5e0ca.

Berthelemy, J.-C., & Demurger, S. (2000). Foreign Direct Investment and Economic Growth: Theory and Application to China. Review of Development Economics, 4(2), 140–155. https://doi.org/10.1111/1467-9361.00083

Blonigen, Bruce A., and Jeremy Piger. 2014. “Determinants of Foreign Direct Investment.” Canadian Journal of Economics/Revue Canadienne D’économique 47 (3): 775–812. https://doi.org/10.1111/caje.12091.

China Economic Review, "China Becomes Top Global Destination for Foreign Direct Investment." 2015. - Daily Briefings, Jan 30. https://login.proxy.lib.duke.edu/login?url=https://www.proquest.com/magazines/china-becomes-top-global-destination-foreign/docview/1775327096/se-2.

Zhang, Luyao. 2022. “Machine Learning for Social Science: Match the Right Tool to the Job.” Whimsical. 2022. https://whimsical.com/machine-learning-for-social-science-match-the-right-tool-to-the--8zuA7Bg5bYQPkRgMJCoywA.

Zhang, Luyao. 2022a. “Machine Learning for Social Science.” Machine Learning for Social Science. https://ms.pubpub.org/.
———. 2022. “Machine Learning for Predictions.” Machine Learning for Social Science, November. https://ms.pubpub.org/pub/ml-prediction/release/3.

Zhang, K. H. (2001). How does foreign direct investment affect economic growth in China? The Economics of Transition, 9(3), 679–693. https://doi.org/10.1111/1468-0351.00095
