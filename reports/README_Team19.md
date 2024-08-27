# DSI Project - Team 19

## Dataset Exploration:
### How will you select your dataset?
We explored different open-source datasets from different platforms. We chose one related to finance which focuses on vehicular insurance data. We evaluated the dataset's content for usability and reviewed the dataset ranking on Kaggle to ensure it is robust and suitable for our analysis needs.
### How will you make sure all team members can contribute to the project?
Tasks will be assigned based on each member’s strengths and interests. We will use GitHub for version control and collaboration. We will use Slack for communication and  Google Drive for sharing and organizing documentation to ensure everyone is actively contributing and informed about the project’s progress.
### How will you make decisions?
We will have daily meetings to discuss progress and make decisions, and use Slack for day-to-day communications. We will ensure that everyone agrees on a decision before moving forward. In case of any disagreements, we resolve them through voting to ensure agreement.

### What is the question you're trying to answer through your data analysis?
Will policy holders who have health insurance be interested in purchasing additional vehicle insurance?
### What tasks need to be completed to get to your final output?
After selecting the dataset, we will use heat maps of regression variables to identify correlations and and visualize key variables and attributes within the dataset. We will assign numerical values to binary variables and further explore the dataset relationships using visualization methods and modeling (scatter plots, histograms, box plots, etc.). Using this information, we will then design, implement, and test regression.

## Data Workbooks: 
### 1. Preliminary_Study.ipynb
This workbook explores the relationships between key data attributes and variables within the selected dataset. 
### 2. Learning from Imbalanced Insurance Data_Analysis with Regression.ipynb
This workbook contains the design, implementation, and test of regression using the selected dataset.


## Rules of Engagement - Team 19
### Team Members
* Belchin(Balkan) Naumov
* Yu (Cecily) Li
* Luiz Oliveira

### Communication and Feedback 
#### Channels and Purposes:
* Use Slack for quick questions and updates.
* Zoom call for official discussions. Agenda shared beforehand;
* Response Time: Respond to messages within 24 hours. Communicate to the team if you will be late or unavailable. 
* Decision Making: Consensus for major decisions; additional discussions held as a team for tie-breakers.

#### Work Allocation
* Tasks: Assign tasks based on strengths and interests, aligning with DSI team project requirements. 
* Deadlines: Set realistic deadlines; update if necessary. Communicate to the team ahead of the deadline if you experience a delay or issue. 
* Accountability: Raise issues promptly in the Slack group chat.

#### Collaboration
* Respect diverse opinions; encourage open dialogue.
* Active listening during discussions, be open to others’ ideas and perspectives.
* Conflict Resolution: Address conflicts privately, escalate to the team if unresolved.
* Commitment: Commit to deadlines and quality standards as a team member.
* Proactivity: Initiate communication and problem-solving.

#### Feedback and Evaluation
* Feedback: Regular feedback sessions during Zoom calls. Constructive criticism to be delivered respectfully.
* Evaluation: Review milestones; celebrate achievements!!!

### Self-Organization of Work 
* Work Environment Tools and Resources: GitHub repository for code; Google Drive for documents.
* Access: Ensure all members have access to necessary tools and resources.

### Clear Tracking of Progress
#### Version Control and Documentation
* Repository: Use Git branching model (feature branches), create pull requests to team-project-1 for code review.
* Documentation: Update Google Sheets project plan for decisions and progress.



## Questions Discussed During Dataset Review
### What are the key variables and attributes in your dataset?
#### Raw Dataset: Learning from Imbalanced Insurance Data


| Data Attribute/ Variable | Description | Data Type  |
| ------------- | ------------- | ------------- |
| ID  | Unique identifier for each record (Numerical) | int  |
| Gender | Gender of the customer (Categorical: (Male, Female). Binary values were assigned for analysis: 'Male' = 1 and 'Female' = 0) |  object |
| Age  | Age of the customer (Numerical) | int  |
| Driving_License  |Indicates whether the customer has a driving license (Categorical (0 for No, 1 for Yes)) | int |
| Region_Code  | Code representing the region of the customer (Numerical) | float  |
| Previously_Insured  | Indicates whether the customer previously had insurance (Categorical (0 for No, 1 for Yes)) | int  |
| Vehicle_Age  | Age of the customer’s vehicle (Categorical (< 1 Year, 1-2 Year, > 2 Years). Binary values were assigned for analysis: 1,2,3 respectively) | object |
| Vehicle_Damage  | Indicates whether the customer’s vehicle has been damaged in the past (Categorical ( No, Yes). Binary values were assigned for analysis: No= 0 and Yes= 1) | object |
| Annual_Premium  | The amount of premium the customer needs to pay annually (Numercial) | float |
| Policy_Sales_Channel  | Code representing the channel through which the policy was sold (Categorical) | float  |
| Vintage  | Number of days the customer has been associated with the insurance company (Numerical) | int  |
| Response  | The target variable indicating whether the customer responded positively to the insurance offer (Categorical (0 for No, 1 for Yes)) | int  |


### How can we explore the relationships between different variables?
Use visualization techniques such as heat maps, scatter plots, box plots, and histograms.

### Are there any patterns or trends in the data that we can identify?
Yes, there are trends between various sets of variables such as vehicle age and damage, ages and genders of customers interested in vehicle insurance, impact of prior vehicle damage on customer interest in purchasing vehicle insurance, etc. Refer to Preliminary_Study.ipynb for further details and analysis.

### Who is the intended audience for our data analysis?
The intended audience for this data analysis is the insurance company that provided the data. The company can use the analysis to understand the characteristics of customers who are interested in vehicle insurance and to identify potential customers who are likely to purchase insurance. The analysis can help the company develop targeted marketing strategies and improve customer acquisition and retention.

### What is the question our analysis is trying to answer?
Our analysis provides value to shareholders of the insurance company by answering the question "What are the characteristics of customers who are interested in vehicle insurance, and how can the insurance company identify potential customers who are likely to purchase insurance?". The analysis aims to investigate the relationships between various customer attributes.

### Are there any specific libraries or frameworks that are well-suited to our project requirements?
* Numpy - data manipulation and cleaning
* Pandas - for numerical operations
* Matplotlib - for creating static and visualizations in Python
* Seaborn -  provides a high-level interface for drawing attractive and informative statistical graphics
* SciPy - for statistical analysis
* Statsmodels - for conducting statistical tests and fitting statistical models
* Sklearn - for ML tasks, classification, regression, and clustering

## Data Visualization
### What are the main goals and objectives of our visualization project?
The primary goals of the visualization project are to allow users to identify patterns and trends in relationships between variables at a glance, such as the impact of age of prospective customers and vehicle age on the likelihood of purchasing additional insurance. By presenting data in a clear and understandable format, we seek to provide insights that may be actioned on by the insurance company's stakeholders, including those without a technical background. We hope that users are able to leverage our visualizations in identifying prospective customers more effectively, and refine their marketing strategies to capture more of the customer segment. 

### How can we tailor the visualization to effectively communicate with our audience?
To tailor the visualization for insurance companies, we focused on relevance of data, managing the complexity of data visualizations and terminology used, and highlighting key insights that could directly impact business decisions or strategic planning.

### What type of visualization best suits our data and objectives (e.g., bar chart, scatter plot, heatmap)?
Based on the objectives and data, we considered the following visualizations:
Heatmaps: Ideal for showing correlations between different numerical variables, such as annual premium and customer age.
Scatter Plots: Useful for visualizing relationships between continuous variables, such as age versus annual premium.
Bar Charts: Effective for comparing categorical data, such as the distribution of responses based on gender or vehicle damage.
Box Plots: Good for understanding the distribution of numerical variables, such as annual premiums across different vehicle ages.
Histograms: Useful for examining the distribution of single variables, such as the frequency of different ages or annual premiums.

### Are there any specific libraries or frameworks that are well-suited to our project requirements?
Yes, the following libraries and frameworks are well-suited:
Matplotlib: For basic and customizable static visualizations.
Seaborn: For attractive statistical graphics and easy-to-use interfaces for visualizing complex datasets.
Plotly: For interactive and web-ready visualizations that can enhance user engagement.
Altair: For concise and declarative visualizations, suitable for interactive charts.

### How can we iterate on our design to address feedback and make iterative improvements?
To identify potential issues with our design and increase accessibility for our users, we can look to collect feedback and input on the initial visualizations and make adjustments as needed. Further testing will be conducted on these iterations to ensure improvements purposeful and effective. Additionally, all changes revisions will be logged for version management and to document the rationale for changes being made. 

### What best practices can we follow to promote inclusivity and diversity in our visualization design?
To promote inclusivity and diversity in our visualization design, we used accessible colour schemes which are distinguishable for users who may be visually impaired, and ensured that all labels and legends are clear and visible. An additional practice to consider for future iterations are text alternatives which may include descriptive text or tooltips for those who use assistive technologies and screen readers. 

### How can we ensure that our visualization accurately represents the underlying data without misleading or misinterpreting information?
To avoid misleading information and to prevent misinterpretation, we paid attention to context in the form of axes labels, titles, legends, etc., as well as data integrity checks and data validations prior to creating the data visualizations. Additionally, we used appropriate scales for our visuals to avoid distortion and misrepresentation of data.

### Are there any privacy concerns or sensitive information that need to be addressed in our visualization?
Prior to creating our visualization, we removed privacy factors such as location, name, etc., and left in only ambiguous identifiers such as age and gender where the combination of these variables could not be used to identify the individual. By anonymizing the data, we are practicing good data privacy policy in the handling of sensitive personal information and avoiding the possibility of breached individual privacy concerns. 


## Individual Learnings and Experiences Videos:
# Team Project 1
* Belchin(Balkan) Naumov: https://www.youtube.com/watch?v=L17xnrZrr9k
* Yu (Cecily) Li: https://youtu.be/aa8R4SE09_o
* Luiz Oliveira: https://www.youtube.com/watch?v=qS3hN-iVuR4
* Shahrzad Soltanieh: https://youtu.be/8n2krR-nw0Y

# Team Project 2
* Belchin(Balkan) Naumov:
* Yu (Cecily) Li: https://youtu.be/_2lHpJpLCec
* Luiz Oliveira:
