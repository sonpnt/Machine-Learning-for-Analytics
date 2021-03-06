# Machine Learning for Data Analytics
This repository includes three case studies for the course **Applications of Artificial Intelligence for Data-Driven Decision Making** at the University of Mannheim. The case desciptions, datasets, source code, and presentation of the results are included in the respective folders. Below is a brief description of each case:

### Case 1. Descriptive Analytics for Waterjet Cutting
#### 1. Core competencies:
- Data cleasing & preparation
- Visualization of multi-dimensional dataset 
- Recognize patterns in data through visual inspection
- Provide recommendations based on the insights from data analytics

#### 2. Topic Summary
Water jet cutting is a technology for cutting a wide variety of materials using a very high- pressure jet of water. Cutting soft materials is possible using pure water jet. Adding abrasives to the water allows for cutting harder materials such as steel and concrete. Figure 1 depicts an abrasive water jet (AWJ) cutter in practice and a stylized sketch of it.
<img src="https://github.com/sonpnt/Machine-Learning-for-Analytics/blob/main/Descriptive%20analytics%20for%20waterjet%20cutting/descriptive_waterjet.png" width="600" />

Task: AIRMINIBUS, the company that uses AWJ cutting to cut metal pieces used in aircraft, wants to improve its understanding of the AWJ machining process. 
Using the given dataset, support this effort by conducting a descriptive analytics study. The study has to identify the main drivers of the quality measures in the AWJ cutting process performed in the company. Support your answer by suitable visualizations of the provided data and quantitative statistical measures. Provide and explain ideas for future improvements of the process.


### Case 2. Unsupervised Learning for Failure Mode Detection
#### 1. Core competencies:
- Apply principal component analysis (PCA) to reduce the complexity of the dataset
- Apply data clustersing techniques (e.g. K-Means) to group datapoints by the similarity of their features; thereby detect outliers, production errors, or defects
- Provide recommendations based on the insights from data analytics

#### 2. Topic Summary
Sunflower Bikes is a leading bike manufacturer in Germany. To enhance its market position in the rapidly growing European e-bike market (see Figure 1), the company wants to improve the quality of its bikes. One of the initial steps for the quality management group of the company is to better understand the current state of the production process and its output.
<img src="https://github.com/sonpnt/Machine-Learning-for-Analytics/blob/main/Unsupervised%20learning%20for%20failure%20mode%20detection/unsupervised_statista.png" width="600" />

Over the last year, the company has gathered data for two key components of finished bikes of their flagship product the ???SuperWatt??? bike. The data for the first set of features is gathered after the production of the frame. The main features measured for each frame as well as their nominal values are depicted in Figure 2. Deviations from the nominal values in any direction are undesirable.
<img src="https://github.com/sonpnt/Machine-Learning-for-Analytics/blob/main/Unsupervised%20learning%20for%20failure%20mode%20detection/unsupervised_bike.png" width="600" />

**Task:** Assist the quality management team of the company to better understand the quality of their manufactured bikes and failures in the production process by applying unsupervised learning methods:

a. Use the machine learning methods to reveal the patterns hidden in the data. Explain the purpose of the methods, justify the order in which you apply the methods, and the selection of parameters used for the methods.

b. Analyze the obtained patterns quantitatively and visualize your results.

c. Discuss the managerial implications of your findings and how they can be used to improve the quality of the manufacturing process.


### Case 3. Supervised Learning for Data Driven Tomato Yield Prediction and Control of Greenhouses
#### 1. Core competencies:
- Perform data cleansing and preparation for supervised learning
- Build neural network model for tomato yield prediction, select network structure, and fine-tune hyperparameters to maximize the accuracy of the prediction model
- Utilize the output model to propose the optimal sales decision & production plan that maximize profits

#### 2. Topic Summary
Kelby Company Ltd. is a multinational agriculture company with greenhouses in Spain and the Netherlands. In an effort to account for the trend of locally grown fruits and vegetables supported by many supermarket chains, Kelby Company Ltd. plans to establish a new large site in Germany. The company needs to decide on how much space in the greenhouses should be devoted to the different vegetables and how to control key parameters of how they operate the greenhouses. Advanced technology in modern greenhouses allows for computer climate control that permits a year-around production with up to six harvests per year.

**Task:**
- Using a dataset with 1,894 observations on different greenhouse inputs and their respective yields, create and train a neural network which predicts the yield of tomatoes per sqm given the features
- Determine the optimal pesticide, applied irrigation, chosen inside temperature, and area devoted to tomato production that minimize the sum of all relevant costs
- Conduct a sensitivity analysis on the demand by varying the demands compared to the data provided in Task 3 from -20% to +20% (for all three cycles) in steps of 10%. Report the resulting optimal decisions and costs. Provide the company with insights on how the costs and decisions will change if the demand changes.
