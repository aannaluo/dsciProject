# Data Science Final Project

Project created within a group of 4, using R, to analyze if there is a correlation between voting preference and annual income.

## Introduction

### Relevant Background

Political parties play a large role in promoting participation from citizens in Canadian democracy and representing their needs. The Canadian government is formed by a number of political parties that make up the House of Commons. Federal elections happen every 4 years to determine the distribution of seats for each party, each seat represents their respective constituencies. The proportion of seats to parties determine which party leads the government, as the party with the most seats is able to select the Prime Minister. 
Analyses surrounding voting results and behaviour are commonly viewed in comparison to factors such as age, province, and livelihood. In this project we want to explore the relationship between who people voted for in 2015 and their average income level that year. Most of us assume that each party appeals to a specific demographic, and creates legislation that benefits them. Hence, we plan on analyzing how each electoral district voted in comparison to the average income to derive if there is a trend in increase in income and party preference. 
Assuming that income distribution is a large factor for voting decisions among citizens when choosing their representatives, we intend to seek evidence of this relationship between income and vote proportions per party. 

### Research Question

Does a correlation exist between the average income of electoral districts and the voting outcomes for the 4 largest political parties (excluding Bloc Quebecois) in Canada?

## Methods

In this project, we referred to two separate data sets provided by the Canadian government in 2015: the Federal Electoral District Tax Statistics (FEDS) which provides data on the average income levels of the electoral districts, and the 42nd general election: Official Voting Results for the 2015 election results for each district. 
We plan to create scatterplots for each political party with income levels on the x-axis and the percentage of votes the party received within the electoral district (%) on the y-axis. Each point will represent an electoral district and we will use the distribution of the points to analyze any patterns in regards to an increase or decrease in income and voter preference. In this analysis we will be removing the variable of time by keeping it as a static analysis of 2015 election results.
Initially we planned to explore this relationship between the Liberal, Conservative, NDP, Green and Bloc Quebecois parties of Canada. After further consideration we decided to remove Bloc Quebecois from our project as it is a geographically-centralized party and the votes received are largely due to Quebec-separatist rhetoric, with income most likely not a driving factor. Due to possible complications such as selection bias and centralization in Quebec, Bloc Quebecois is not an option for most electoral districts.

## Expected outcomes and significance:

### What do you expect to find?

One of the trends we were expecting was that as the average income rate decreased, voter preference would shift to parties which focus on policies that benefit the low and middle income families. Similarly, as the average income rate increased, voter preference would shift to parties who have less focus on these policies.
For example, the Conservative Party is known to promote the reduction of income tax, which is typically supported by higher income groups. On the other hand, the NDP promises to “[ensure] that large profitable corporations pay a fair share of taxes” and “tax reductions to help the middle class, working families, and the poor” (NDP, 2016) which may be opposed by large business owners and the wealthy.
We also expect to notice that when we compare the parties, the Liberal and Conservative party will have more data samples which may contribute to a more reliable analysis of income to vote trends. With this in mind we expect to see more changes on the KNN nearest neighbour line in a major party such as the Liberal Party when compared to smaller parties such as the Green Party. 

### What impact could such findings have?

Using these findings, we may be able to predict the possible outcomes of an election per electoral district based on its income level. This data could also be used to help parties plan their approach to gaining more seats by targeting the income demographics who do not typically vote for them. We can also identify a trend between income and party preference, allowing us to figure out if specific income demographics believe a party could benefit them more than others. 
Conducting this research will also be helpful for the government to predict the public reaction to new bills or changes to policies surrounding the topics of income distribution, minimum wage, taxes, immigration and labour. 


### What future questions could this lead to?

In this project we only explored one estimator to voter choice, income, if there is a relationship between income level and voter choice as we predict there may be other predictors that can explain the deciding factors for popular political parties. This could lead to questions about which parties receive the most support from high and low earning households. Do the rich prefer certain parties because their legislation focuses on protecting their wealth or because these parties represent their moral and ethical views? 
Some ways we can expand or add to this research is if we look into social inequalities that may affect voter participation. Further research on gender differences, immigration status, and socioeconomic inequalities may help with predictions and solutions. If we were to add onto this project we would focus on the effect of gender inequity and how the wage gap affects the decision to support certain political parties.
