# Freedom Rankings Per Country 2013-2022

![](https://www.googleapis.com/download/storage/v1/b/kaggle-user-content/o/inbox%2F12064410%2F2520af6c71c8c2eb7b37af614ccc0ce0%2Ffreedom%20global%20flag.png?generation=1676790229329887&alt=media)

# DAY ~3,700 (January 1st, 2012 to December 31st, 2021)
This is a dataset that tracks the quality of political rights and civil liberties for each country from 2013 to 2022. 

All data are official figures from the Freedom House that have been compiled and structured by myself. Please read my explanation of the rating system and the 40+ variables to understand the inner workings of the dataset. I ensured you that the payoff will be worthwhile due to the importance of the data featured. Personally, I was intrigued at how countries with questionable human rights records shifted in ratings over the past decade.

# Data Sources
##### The primary data source used was the **Freedom House**, an organization that is widely-renowned for its publication of the annual *Freedom in the World* reports that focus on political rights and civil liberties. Considering that the Freedom House has been tracking global trends in political rights and civil liberties for 50 years, the institution is uniquely qualified to make the featured evaluations in the "most widely read and cited report of its kind". 

1. [Freedom House's *Freedom in the World* Report](https://freedomhouse.org/report/freedom-world) - The majority of the data was procured through this particular webpage, which featured other freedom-related collections with varying time periods. 
2. [Freedom House's *Freedom in the World* Research Methodology](https://freedomhouse.org/reports/freedom-world/freedom-world-research-methodology) - Initially, I found myself extremely confused on how the rating system worked and the peculiar letter-based variables. After looking through their detailed methodology and accompanying explanations, I was able to clean the data to maximize efficacy.

# Rating System Explanation (IMPORTANT)
A country or territory is awarded **0 to 4 points** for each of **10 political rights indicators** and **15 civil liberties indicators**, which take the form of questions; a score of 0 represents the *smallest degree of freedom* and 4 the *greatest degree of freedom*. The political rights questions are grouped into three subcategories: Electoral Process (3 questions), Political Pluralism and Participation (4), and Functioning of Government (3). The civil liberties questions are grouped into four subcategories: Freedom of Expression and Belief (4 questions), Associational and Organizational Rights (3), Rule of Law (4), and Personal Autonomy and Individual Rights (4). The highest overall score that can be awarded for *political rights* is **40** (or a score of 4 for each of the 10 questions). The highest overall score that can be awarded for *civil liberties* is **60** (or a score of 4 for each of the 15 questions).

# Significant Statistics Being Tracked
- **C/T:** Indicates whether the entry is a country (c) or territory (t)
- **Status:** F=Free, PF=Partly Free, NF=Not Free
- **PR Rating:** Political Rights Rating
- **CL Rating:** Civil Liberties Rating
- **A:** Aggregate score for the "A. Electoral Process" subcategory&gt;
--&gt; A1: Was the current head of government or other chief national authority elected through free and fair elections?
--&gt; A2: Were the current national legislative representatives elected through free and fair elections?
--&gt; A3: Are the electoral laws and framework fair, and are they implemented impartially by the relevant election management bodies?
- **B:** Aggregate score for the "B. Political Pluralism and Participation" subcategory
--&gt; B1: Do the people have the right to organize in different political parties or other competitive political groupings of their choice, and is the system free of undue obstacles to the rise and fall of these competing parties or groupings?
--&gt; B2: Is there a realistic opportunity for the opposition to increase its support or gain power through elections?
--&gt; B3: Are the people’s political choices free from domination by forces that are external to the political sphere, or by political forces that employ extrapolitical means?
--&gt; B4: Do various segments of the population (including ethnic, racial, religious, gender, LGBT+, and other relevant groups) have full political rights and electoral opportunities?
- **C:** Aggregate score for the "C. Functioning of Government" subcategory
--&gt; C1: Do the freely elected head of government and national legislative representatives determine the policies of the government?
--&gt; C2: Are safeguards against official corruption strong and effective?
--&gt; C3: Does the government operate with openness and transparency?
- PR: Aggregate score for the Political Rights category
- **D:** Aggregate score for the "D. Freedom of Expression and Belief" subcategory
--&gt; D1: Are there free and independent media?
--&gt; D2: Are individuals free to practice and express their religious faith or nonbelief in public and private?
--&gt; D3: Is there academic freedom, and is the educational system free from extensive political indoctrination?
--&gt; D4: Are individuals free to express their personal views on political or other sensitive topics without fear of surveillance or retribution?
- **E:** Aggregate score for the "E. Associational and Organizational Rights" subcategory
--&gt; E1: Is there freedom of assembly?
--&gt; E2: Is there freedom for nongovernmental organizations, particularly those that are engaged in human rights– and governance-related work?
--&gt; E3: Is there freedom for trade unions and similar professional or labor organizations?
- **F:** Aggregate score for the "F. Rule of Law" subcategory
--&gt; F1: Is there an independent judiciary?
--&gt; F2: Does due process prevail in civil and criminal matters?
--&gt; F3: Is there protection from the illegitimate use of physical force and freedom from war and insurgencies?
--&gt; F4: Do laws, policies, and practices guarantee equal treatment of various segments of the population?
- **G:** Aggregate score for te "G. Personal Autonomy and Individual Rights" subcategory
--&gt; G1: Do individuals enjoy freedom of movement, including the ability to change their place of residence, employment, or education?
--&gt; G2: Are individuals able to exercise the right to own property and establish private businesses without undue interference from state or nonstate actors?
--&gt; G3: Do individuals enjoy personal social freedoms, including choice of marriage partner and size of family, protection from domestic violence, and control over appearance?
--&gt; G4: Do individuals enjoy equality of opportunity and freedom from economic exploitation?
- **CL:** Aggregate score for the Civil Liberties category
- **Total:** Aggregate score for all categories

# Dataset History
2023-02-18 - Dataset is created (3,700 days after temporal coverage start date).

[Kaggle Dataset](https://www.kaggle.com/datasets/justin2028/freedom-in-the-world-2013-2022) - The same data but on Kaggle.

# Code Starter
[Link to Notebook](https://www.kaggle.com/code/justin2028/global-freedom-rankings-2013-2022-code-starter)

# Acknowledgements
Please refer to the Freedom House's methodology for more details: https://freedomhouse.org/reports/freedom-in-the-world/freedom-in-the-world-research-methodology
