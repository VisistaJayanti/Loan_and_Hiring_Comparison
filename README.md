# Loan_and_Hiring_Comparison


In this project, we are determining the hiring rate of an individual based on previous loan history of the same. This project is going to follow a prediction based model structure and going to take into account the socio-economic parameters and financial parameters. 

The following socio-economic parameters taken into consideration are the following: 
1) Age of the individual (Relevance: An individual of 20 yearss with loan has a greater probability of being hired than a middle aged person having backup loans in some organizations)
2) Gender of the individual (Relevance: In some organizations, a female employee or a candidate with loans has a lower hiring rate than a male with loan history)
3) Marital Status of the individual (Relevance: An individual having a family with loans is more likely to be hired than an individual without a family)
4) Credit Score of the individual (Relevance: Credit score determines stability of the person and the capability of the person to repay the loans)
5) Types of loans (Relevance: Type of loan usually plays an indirect role in deciding the placement, almost none, but in some countries or organizations there is a slight discrimination based on personal financial history)
6) Ethnicity of Nationality (Relevance: Since individuals from different countries have a different currency rate, a loan in one country may be higher in value or lower in value in another or in the location of recruitment, example: An individual coming from an underdeveloped country or a developing country with loans maybe tested more than an individual with loans in a developed country)
7) Location of living (Relevance: If an individual is living in an urban area, he/she has higher chances of repaying the loan than an individual in rural area)
8) Education (Relevance: This determines the qualifications of the individual)


The following financial paraemters taken into consideration are the following: 
1) Duration it took to repay the previous loans (Relevance: The time taken will gurantee an individual's return value)
2) Occupation of immediate family (Relevance: This describes the family status)
3) Financial criminal background (Relevance: This is important to organizations to check if an indiviudal has been previously engaged with any sort of financial fraud or scams, because when an employee of the organization is caught in such acts, it will damage the reputation of the organization)
4) Outstanding debt to income ratio (Relevance: Can discover if it has a positive relation or negative one)
5) Income stability (Relevance: The avergae annual income will provide security)
6) Loan purpose alignment (Relevance: Will check if the purpose of the loan logically correlates with a person's career path)
7) Current income vs return capacity 
8) Outstanding debt to income ratio


Data collection strategy to be used would be a mix of primary data and secondry data. 

1) Primary data generation
The primary data generation would happen by collection of raw data from questionnares or surveys targeted towards working youth. The sample size, age criteria and number of questions is yet to be decided.

2) Seocndary data gathering
Pre-existing secondary data from credible sources will be used for the creation of the prediction model.

Once data is collected, existing data will be fine tuned based on the goal of the problem statement, this will be done by data preprocessing tools and we aim to create a balanced dataset before training the model with the same.
