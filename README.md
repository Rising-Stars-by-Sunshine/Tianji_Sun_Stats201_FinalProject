# Analyzing the Foreign Direct Investment’s effect on domestic saving in China using a Machine Learning approach

## Project information
* Author: Tianji Sun, Data Science students from class of 2024, Duke Kunshan University
* Instructor: Prof: Luyao Zhang, Duke Kunshan University
* Disclaimer: Submissions to the Problem Set 2 for STATS201 Introduction to Machine Learning for Social Science, 2022 Autumn Term (Seven Week - Second) instructed by Prof. Luyao Zhang at Duke Kunshan University.
* Acknowlegement: Prof. Luyao Zhang guided the entire project through. Xin Ma (helped with the VM set up)
* Project Summary:  &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;&nbsp; &nbsp; Project 1: Machine Learning for Explanation:
Based on professor Luyao Zhang's Blockchain Decentralization research, this project guide us to query, process and visualize the decentralization index of three token "Aave", "Comp", and "Lusd".&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; Project 2: Machine Learning for Prediction:
In this project, I have used world bank data on direct foreign investment in China to predict future foreign  direct investments. Using the demo code's given algorithms and additional KNN MLP regression I can deeply analyze the data set.

## Project Summary
* Background and motivation
In the globalized economy, Foreign direct investments (FDI) are shifting economical structures. Since the Reform and Opening up, foreign companies and investors are allowed to take part in China’s economy. And they have since then made an impact on China’s economic structure. From Zhang’s(2001) study, FDI will be increasing in China for the foreseeable future, and the increase in FDI will decrease domestic savings in China. As viewing data from 2001 to 2020, FDI in China has increased yearly. In this research, I aim to use historical FDI data from China to analyze its correlation with domestic savings.

## Table of content
| Tables        | Content                                                |
| ------------- |:-------------:                                     |
| Data    | Queried and Processed Data for both projects |
| Code     | Query, Process, and Annalyze Data|
| Spotlight | figures generated from the two parts of the project|  



## Code
| Tables        | URL                                                |
| ------------- |:-------------:                                     |
| Explanation Queey and Process Data     | https://github.com/Alexsun12/portfolio-/blob/main/Problem%20set%202/Code/Explanation/Query%20and%20Processed%20Data.ipynb |
| Explanation Analyze Data     | https://github.com/Alexsun12/portfolio-/blob/main/Problem%20set%202/Code/Explanation/Analyze%20Data(Visualization).ipynb |
| Prediction Query and Process data (Part 1) | https://github.com/Alexsun12/portfolio-/blob/main/Problem%20set%202/Code/Prediction/Query_and_Process_Data.ipynb|  
| Prediction Analyze data (Part 2) |https://github.com/Alexsun12/portfolio-/blob/main/Problem%20set%202/Code/Prediction/Analyze_Data.ipynb |  



## Spotlight
#### For Machine Learning for Explanation
![image](https://user-images.githubusercontent.com/117652452/205329125-1f3cdb5f-104a-42a8-b8e2-78a8b41f8197.png)
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; figure 1. the Aave token decentralization index heatmap

![image](https://user-images.githubusercontent.com/117652452/205329480-afd763b9-2e38-42c8-ad70-831d9514931b.png)
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; figure 2. the Comp token decentralization index heatmap

![image](https://user-images.githubusercontent.com/117652452/205330578-dc5550ae-2570-4d89-a632-4741e346d4f9.png)
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; figure 3. the Lusd token decentralization index heatmap

In the Machine Learning for explanation part, I have used the heat map to generate the dencentrilization index of the three tokens (Aave, Comp, Lusd) The x axis is the date and the y axis is the value. In the graph we can more directly see how centrized each token are. From the graphs we can see that each token are getting more decentralized by time.

Acknowlegdement: 

data source: https://github.com/SciEcon/SoK_Blockchain_Decentralization/tree/main/Data_TokenIndex

code source: https://github.com/SciEcon/SoK_Blockchain_Decentralization/blob/main/code/Top_DeFi_Decentralization_Visualizations.ipynb

heatmap generated by plotly, data are aquired and generated from SoK: Blockchain Decentralization (https://arxiv.org/abs/2205.04256)
Using heatmap to map the data set is inspired by Kroon Isabella's readme file
           
#### For prediction:
![image](https://user-images.githubusercontent.com/117652452/205502912-f0c3403e-1b3c-4acd-8ccc-0c35407e476d.png)
A confusion matrix present a table that is used to define the performance of a classification algorithm. A confusion matrix visualizes and summarizes the performance of a classification algorithm.(https://www.sciencedirect.com/topics/engineering/confusion-matrix)
![image](https://user-images.githubusercontent.com/117652452/205506979-001cd299-b407-47e3-a274-01eca0581dff.png)
results generated by the KNN regression. KNN regression approximates the association between independent variables and the continuous outcome by averaging the observations in the same neighbourhood(https://bookdown.org/tpinto_home/Regression-and-Classification/k-nearest-neighbours-regression.html). Using this algorithm I can see the association of time and the DFI data.

## More about the Author
![image](https://user-images.githubusercontent.com/117652452/206921127-d87279c7-1e7c-4493-9797-9cb7a86574a6.png)
- self-introduction
The author Tianji Sun is a Duke Kunshan University  data science student in class of 2024. His interest lies in applying data analysis and new tools to social problems such as environmental issues, gender inequalities etc.
- Final reflections 


## References

### Data Source
- Data Source Title and URL
### Code Source
- Code Source Title and URL
### Articles
- Article Source Title and URL
### Literature
- Literature References in [Chicago Author-Date](https://www.chicagomanualofstyle.org/tools_citationguide/citation-guide-2.html) Style and [BibTex](https://scholar.google.com/) 

Levin, Dan, and Luyao Zhang. 2020. “Bridging Level-K to Nash Equilibrium.” *The Review of Economics and Statistics* 104 (6): 1329–40. https://doi.org/10.1162/rest_a_00990.

```
@article{levin2022bridging,
  title={Bridging level-k to nash equilibrium},
  author={Levin, Dan and Zhang, Luyao},
  journal={Review of Economics and Statistics},
  volume={104},
  number={6},
  pages={1329--1340},
  year={2022},
  publisher={MIT Press One Rogers Street, Cambridge, MA 02142-1209, USA journals-info~…}
}
```

