# Pymaceutical - Research and Development
## Exploring the Efficacy of Capomulin as a Treatment for Tumours (Matplotlib-Challenge)
![09 optimized](https://user-images.githubusercontent.com/115101031/204073511-3e28d8e1-deaa-4d34-8597-a38adde9d57a.gif)

### Background
Research and development is always been an integral part of the pharmaceutical industry. Companies aim at developing the best and most effective products. As such, big data can add value to the traditional research and development chain.

“Data is like crude. It’s valuable, but if unrefined, the real value of data can’t be used”.

The real value of data is derived only when organization apply visualization tools to analyze their data and derive valuable insights that have implications to the health and welfare of our communities.  The evolutionary breakthrough of data in every field is generating vast volumes of data to be analyzed. And understanding the volume, variety, velocity, and veracity of the data using statistical tools is a hard task for the R&D team in building a data-driven strategy. 

#### Big data in research and development has a wider impact on how data is leveraged by R&D today. 
Industries in manufacturing, pharmaceuticals, healthcare, space research, etc., mostly rely on the R&D department for developing new products or services. And leveraging big data tools can save time and cost, which is the biggest concern for these businesses in performing R&D. The strategies built using big data in R&D can deliver results with the utmost accuracy, and it reduces repetitive work. 

#### How does Big Data Power Research and Development?
Organizing research and monitoring changes throughout the research life cycle and implementing the driven values for the development of the treatment program is a challenging task. Storing, analyzing, and evaluating the data to derive meaningful insights is tougher when dealing with large volumes of data.

1. Big data and other AI tools can be leveraged together to extract actionable insights from massive amounts of unstructured data.

2. Most traditional R&D practitioners rely on historical data values. And leveraging big data analytics can help research organizations in building predictive analytical models that can generate real-time insights for constant up-gradation of research models throughout the research life-cycle.

3. Big data is at the rescue when researchers need to analyze large chunks of data, and these big data tools also help the segregation of data for better analysis.

4. Data representation and visualization are the biggest concern. As the insights can be extracted, the presentation of extracted insights for the development and implementation of the taken decision can be possible only with data analytics and data visualization tools. 

SOURCE: https://soulpageit.com/the-value-of-big-data-in-research-development/ 

### Using Matplotlib to Boost Data Analysis
Data Visualization is an important part of business activities as organizations collect large amounts of data.  All of this data holds key insights for stakeholders and visualizations make these insights easy to interpret.  

Data is only as good as it’s presented.

Visualizations are the easiest way to analyze and absorb information. Visuals help to easily understand the complex problem. They help in identifying patterns, relationships, and outliers in data. It helps to build a compelling story based on visuals. Insights gathered from the visuals help in building strategies for businesses. It is also a precursor to many high-level data analysis for Exploratory Data Analysis(EDA) and Machine Learning(ML).

Human beings are visual creatures. Countless studies show how our brain is wired for the visual, and processes everything faster when it is through the eye.

Data visualizations in python can be done via many packages, including Matplotlib. 

SOURCE: https://towardsdatascience.com/data-visualization-using-matplotlib-16f1aae5ce70

### Project Details
Having just joined Pymaceuticals, Inc., a new pharmaceutical company that specializes in anti-cancer medications, I will be analyzing data collected from the company's research and development in screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.

As a senior data analyst at the company, I've been given access to the complete data from their most recent animal study. In this study, 249 mice who were identified with SCC tumors received treatment with a range of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals’ drug of interest, Capomulin, against the other treatment regimens.

The executive team has tasked me with generating all of the tables and figures needed for the technical report of the clinical study. They have also asked for a top-level summary of the study results.

### Technical Observation
Data visualization provides a powerful tool to explore, understand, and communicate the valuable insights and relationships that may be hidden within data. Whether it’s an initial exploratory analysis or a presentation to non-technical colleagues, proper visualization lies at the heart of data science. When it comes down to choosing how to visualize one’s data, the best tool for the job depends on the type of data, the purpose of  the visualization, and the aesthetics which you hope to achieve. In this article, I will compare and demonstrate two common visualization tools used in Python: matplotlib and plotly.

Matplotib is a versatile and powerful visualization tool that offers and extensive library of plotting functions.  Matplotlib is extremely powerful because it allows users to create numerous and diverse plot types. It is an ideal option for our project.

### Observations on the Results
The obtained results showed that:
* Variance: examining the variance in the results, shows that Capomulin and Ramicane are statistically significant and have the smallest spread of all the regimens.  Its clustering close to the mean, means that its efficacy is consistent across the population.  Expectantly. the standard deviation across the different regimens also shows a statisitically small dispersion of the dataset relative to the mean for Capomulin and Ramicane.  This is also true for the standard error of the mean, which shows that the results are highly representative of the population mean. 
<img width="458" alt="Screen Shot 2022-11-26 at 1 22 06 AM" src="https://user-images.githubusercontent.com/115101031/204075287-172bb7d2-8254-4355-bf61-f6b2aa2bc085.png">

* Capomulin and Ramicane are the most rigorously tested and documented among the treatment regimens, with Capomulin including the largest population of mice among all the regimens.  
<img width="595" alt="Screen Shot 2022-11-26 at 1 25 15 AM" src="https://user-images.githubusercontent.com/115101031/204075405-79c506ff-ccf3-4fae-b1c0-c75313380829.png">

* Among the population of a nearly equal ration of male to female mice, both Capomulin and Ramicane showing the smallest tumour volume among the top performing treatment regimens.  Looking closely at subject #r554. it is clear that Capomulin has proven to be highlyly efficacious in the treatment of skin cancer.
<img width="637" alt="Screen Shot 2022-11-26 at 1 28 37 AM" src="https://user-images.githubusercontent.com/115101031/204075503-1b080a1c-2908-4012-8815-cd3ced24f983.png">
<img width="568" alt="Screen Shot 2022-11-26 at 1 30 54 AM" src="https://user-images.githubusercontent.com/115101031/204075589-3d298172-02f4-4443-aa3e-0daf8f06f20d.png">

* Looking at the correlation between weight of the mice and the volume of tumours, we find a positive correlation, informing that a relationship exists, where as weight increases, the volume of the tumours increases.  While correlation is not necessarily causation, it could provude a useful avenue for future research.
<img width="558" alt="Screen Shot 2022-11-26 at 1 31 46 AM" src="https://user-images.githubusercontent.com/115101031/204075782-bee7cd31-060c-4552-b024-d9de6ee02472.png">
