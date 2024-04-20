# Commercial-building-Energy-Optimization-A-Machine-Learning-Approach-

Abstract—Huge energy consumption is one of the many global concerns regarding the environmental impact, this project aims for the optimization of the energy management in buildings, to be specific by using an archive dataset that has data collected from over 300 sensors for three years. This data consists of information about indoor environment, outdoor environment and HVC. 	The data plays an important role in validating and the model's predictions. A combination of linear and nonlinear machine learning models like Multiple Linear Regression, Random Forest, Support Vector Machines, and Gradient Boosting algorithms are used to carry out this project. This project involves using the already extracted and cleaned data, using the right models to train and evaluate, thought which we get important insights that contribute to sustainable building method.  

The project aims not just for efficient environment usage but also to understand the relationship between the energy consumption by buildings and their impact on the environment by accurately predicting the HVAC cooling and heating load. In implementing advanced machine learning methods, the project hopes to make a sustainable statement about the environment, hoping to make the future healthier and greener. The output expected includes predicting HVAC cooling and heating load based on collected indoor and outdoor environment data.  

 

Motivation 

The ever-increasing significance on environmental conservation and sustainability is otherwise a pressing concern in the present-day world. Having understood this importance, we are highly motivated to pursue this project where we target to address inefficiencies in energy management in building operations. Quite notably, the total energy consumption worldwide is significantly contributed by various buildings. This has a direct impact on greenhouse gas emissions. In this project, we aim to develop various insightful models that optimize energy usage in addition to contributing towards a sustainable future using a three-year building operational performance dataset. We believe this project can drive positive changes, which aligns with our values, commitment, and responsibility towards the environment. By considering our knowledge in data analysis and machine learning, we want to handle real-world problems that helps a more sustainable future for the upcoming generations. We aim, through this project, our meaningful contribution encourages data driven insights for a greener, healthier, and more prosperous tomorrow. 

 

Literature Survey 

Buildings consume about 40% of the primary energy in United States and about one third globally. With modern technologies like temperature sensors and other energy efficiency tools we can achieve energy use reduction of about 50%. The dataset includes whole-building and end-use energy consumption, HVAC load, indoor and outdoor environmental factors. The data was collected for a period of three years from greater than 300 sensors and meters on two office floors of the building (Luo et al. 2022). Global concerns are growing on energy waste and its adverse impact on the environment. When designing efficient buildings, it is inevitable to calculate their cooling load (CL) and heating load (HL) to specify the required cooling and heating equipment to achieve comfortable indoor air conditions. The environmental characteristics of a building are among the main aspects or conditions that can affect its energy consumption, i.e. contribute to sustainability and energy efficiency (Dina et al. 2022). There are several methods available for predicting energy consumption in a commercial building. Multiple Linear regression is a valid approach due to its effectiveness and linearity. Decision trees, neural networks and linear regression gave good performance with minimal difference in error (Tso et al. 2007).  In order to promote buildings energy efficiency and motivate people to adopt sustainable practices, buildings are assigned with ratings and labels (William Chung 2011). Support Vector machines are highly robust machine learning models. Support Vector Machines (SVM) are used for both classification and regression purposes. For buildings, SVM has been used for forecasting energy consumption (Lai et al. 2008) and classification of energy usage of the buildings (Li et al. 2010). 

The main benefit of using random forest as a predictive model is its high generalization ability, which can effectively prevent overfitting in data prediction (Wang et al., 2018). Statistical properties of the variables can be first analyzed with visualization such as histogram of the empirical probability distributions of all the input and output variables e.g. Heating and cooling load (Tsanas & Xifara, 2012). 

The scope of this project covers the course curriculum covered in the class. The project includes implementation of supervised machine learning algorithms such as Multiple Linear Regression, Random Forest, Support Vector Machines and Naïve Bayes. The project will also cover probability distribution of the variables. 

 

Methodology 

The goal of smart building lies in minimizing the energy consumption by the end user. This project aims at optimizing energy consumption by accurately predicting the HVAC cooling and heating load. (Seyedzadeh et al. 2018￼ .The proposed statistical techniques and traditional machine learning algorithms to predict HVAC cooling and heating load based on collected indoor and outdoor environment data. The hypothesis for this project is that outdoor temperature, humidity, solar radiation along with indoor CO2 concentration, heating and cooling temperature set points, interior and exterior zone temperature has impact on HVAC energy load. Different statistical experiments are designed to identify the features with high predictive power. This will contribute towards achieving high performance machine learning by adjusting parameters. Pearson correlation coefficient, Analysis of variance (ANOVA) statistical methods are used in this project to assess relationship between feature variables and analyze the predictive power of the feature variables, respectively. Fig 1 shows the implemented methodology here using supervised machine learning algorithm.  



The overall methodology consists of three stages including 1) data collection 2) data processing and normalization and 3) supervised machine learning model building and prediction of HVAC cooling and heating load attributes. The overall methodology consists of three stages including 1) data collection 2) data processing and normalization and 3) supervised machine learning model building and prediction of HVAC cooling and heating load attributes. Data is collected from more than 300 sensors and meters installed in a two-floor office building in Berkeley, California. (Hong et al. 2022). Data Processing steps involve dimensionality reduction technique, data cleaning and normalization. Multiple traditional machine learning techniques are used in this project such as Multiple linear regression, Random Forest, SVM and Gradient Boosting. Multiple linear regression technique is extensively used when there exists more than one predictor variable with continuous values. Random forest regressor is well-known to capture non-linear relationships between feature variables while increasing generalization ability. Support Vector Machine Regression (SVR) algorithm is also used for non-linear relationships, and it handles overfitting problems more efficiently. Gradient boosting algorithm is another powerful regression technique where multiple weak models are created to create a strong model.  Performance of these models are evaluated using cross validation techniques and using R^2, RMSE evaluation metrics. Hyper tuning of the models through Grid-search techniques often results in optimized solution. Comparison of evaluation metrics among multiple modeling approaches leads towards the most optimized solution.  


Deliverables and Milestones 

The project goal is to optimize energy utilization in the building based on the indoor and outdoor environment data. The project deliverable includes a machine learning model which will ensure highest accuracy in predicting cooling and heating load generated by the HVAC system.   

Different regression modeling approaches are deployed using the same dataset, which will give this project a scope to compare the evaluation metrics and achieve the optimized energy consumption goal.    

Members and roles 

Aryama  

Role: Gradient Boosting Implementation: Is responsible for implementing Gradient Boosting. This includes feature selection, training the model and evaluating its performance.  

   

Shikha  

Role: Support Vector Machine: Implementing support vector machine, which involves number of SVM algorithms, hyper tuning and evaluating the model. 

   

Sreelekha  

Role: Random Forest Model Implementation: Implementing the regression model, Random Forest. This includes feature engineering, training and testing random forest models with different parameters and deciding which is the best. 

Ananya  

Role: Linear Regression Model Implementation: 

Works on implementing Multiple Linear Regression, including normalizing the data, selecting the right features, model training and evaluation of the model. 

Collaborative work: 

Each team member has the same number of resources to work and understand the project. Regular check points and checks are mandatory and are followed by everyone in the team to keep track of the progress or detect any bottlenecks. Collaborative discussion and knowledge sharing among the teammates to ensure consistency across the model implementations, data processing, visualizations and evaluation process to extract the best performance. 

Relevance to the Course  

Our project directly relates to our machine learning course by applying important concepts and techniques learned during the semester to a real-world problem. By implementing multiple appropriate machine learning algorithms like Random Forest, Multiple Linear Regression, Support Vector Machines regression (SVM), and Gradient Boosting algorithms, we implemented a practice of supervised learning methods covered in the course. In addition to that we have gained insights into where to apply classification and regression methods, depending on the nature of the problem and the type of data available. We are trying to implement the concepts required for preprocessing, model evaluation, concepts which are helpful to improve performance like normalization, handling outliers and many more which are course in the course. This hands-on application not only boosts our theoretical understanding but also prepares us for applying machine learning techniques in multiple domains beyond the classroom.  

Technical Difficulty 

In implementing the project, it requires careful consideration and strategic solutions. It is important to ensure that there is consistency in the data collection and that it is properly normalized. It is important in identifying the proper features for acquiring model accuracy, additionally avoiding the overfitting. Moreover, dealing with sensitive data regarding privacy adds to the risk and complexity. Also, the input data requires multiple sensors to be installed and monitored in the entire building, which will raise the cost of implementing the mode. However, the traditional machine learning algorithm is computationally less costly than modern deep learning techniques. Feature selection and model training are the time-consuming parts of this project as they follow the traditional techniques. 

Novelty  

This project stands out with its integration of combining linear and nonlinear machine learning algorithms/models. This integration sets this paper apart from the others in this related field. Moreover, we are determined to achieve higher accuracy, adding essence to this project.  

 

Impact 

Carbon emissions and energy waste are a serious present-day problem. Buildings are one of the main causes of this problem. By employing sustainable building energy management solutions, it not only contributes to the solution to this problem, but also leads to significant cost savings for buildings owners and operators. We target impact in multiple key areas through our project. To start with, building owners will be able to utilize our insights to make informed decisions about minimizing operating costs with enhanced occupant comfort and eventually an increased asset value. Subsequently, policy makers and energy distributors can substantially benefit from our models. Effective energy efficient standards and incentives can be developed, which drives broader adoption of sustainable building practices. Above all, our project has a direct impact on reducing carbon emissions, which indirectly aids in mitigating climate change impacts. This will create healthier and resilient communities. Harnessing the power of machine learning and data analytics to build data driven insights and models, which aids in making intelligent decisions in building energy management, we plan to do our part for a greener tomorrow. 

Heilmeier Catechism 

What are you trying to do? Articulate your objectives using absolutely no jargon. – Abstract / Deliverable  

How is it done today, and what are the limits of current practice? - Samples of the data must be large enough to incorporate a variety of scenarios. Then only models can perform well on unseen data. Data was limited in the case of previous literatures and not exhaustive, including multiple cases. 

What is new in your approach and why do you think it will be successful? - Methodology/Novelty  

Who cares? If you are successful, what difference will it make? - It leads to significant cost savings for buildings owners and operators. Efficient energy standards and incentives can be developed, which helps in adoption of sustainable building practices. Above all, our project has a direct impact on reducing carbon emissions. 

What are the risks? Project might deal with sensitive data regarding privacy adds to the risk and complexity. 

 How much will it cost? The input data requires multiple sensors to be installed and monitored in the entire building, which will raise the cost of implementing the mode. However, the traditional machine learning algorithm is computationally less costly than modern deep learning techniques. 

How long will it take? - Our Project design and implementation will take approximately 1.5 months. 

 What are the mid-term and final “exams” to check for success? - Refer to Deliverables and Milestones section of the project proposal. 

 
