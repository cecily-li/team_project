# DSI Project 1 - Team 19

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
* Shahrzad Soltanieh

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


## Individual Learnings and Experiences Videos:
* Belchin(Balkan) Naumov: https://www.youtube.com/watch?v=L17xnrZrr9k
* Yu (Cecily) Li: https://youtu.be/aa8R4SE09_o
* Luiz Oliveira: https://www.youtube.com/watch?v=qS3hN-iVuR4
* Shahrzad Soltanieh: https://youtu.be/8n2krR-nw0Y
