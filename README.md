# American Bar Association Data Analysis

In this project, we cleaned data from the American Bar Association that outlined client demographics, attorney demographics, real client-lawyer conversations, and attributes of these conversations. Using Python (Pandas, NumPy), R, and Tableau, we performed an EDA on the data sets with a goal of helping ABA improve their system so that attorneys can be better prepared for their clients, clients can receive better services, and the interactions between the two parties can be more productive overall. 

Below are some of the visualizations with produced, along with the insights we gained from them.

<img width="731" alt="Categories by location" src="https://user-images.githubusercontent.com/121086856/235502085-e9ed8881-3bb4-4276-bcc3-2f25c606eb25.png">

![Family   Children Questions Dist by Age](https://user-images.githubusercontent.com/121086856/235502170-6c26037f-4b40-4ecc-b2c5-e729415a1ccf.png)



<img width="731" alt="Consumer Financial Questions Dist by Ethnicity" src="https://user-images.githubusercontent.com/121086856/235502195-6268fac9-c635-4c02-b4aa-2f5ae44c9626.png">

<img width="736" alt="Education Questions Dist by Ethnicity" src="https://user-images.githubusercontent.com/121086856/235502203-52e10ea7-1f81-4da8-92db-8ec14f9b79c2.png">

<img width="736" alt="Housing Homelessness Dist by Ethnicity" src="https://user-images.githubusercontent.com/121086856/235502220-5d509fd7-4f24-44b7-ba49-3c8bed3cc5fa.png">




<img width="713" alt="Attorney locations" src="https://user-images.githubusercontent.com/121086856/235502113-d98e9b2d-e883-4a14-96d1-af0ecd0c8e2c.png">

## Word maps
Created word maps using the most common words in the responses.
Excluded out the words of the top 100 words from wikipedia table scraped into a csv
This was done using pandas
Then we sparse through the question results and separate them by each word
Counted up the words and joined this data frame with the questions data frame which enabled us to see which categories each question prompt belonged to

#### Housing and Homelessness
Housing and Homelessness (landlords, tenants, leases are a big topic for this: meaning that these people are dealing with the landlords that they are paying to and rent)
![housing](https://github.com/calebtran7/ABA-Pro-bono-Analysis/assets/98145591/56b042ec-fcb3-477c-a0fc-f68f8ab17d31)

#### Consumer Financial Questions
Consumer financial Questions (people are being told to use their better judgment and often have difficulty making decisions with those big purchases like cars, property. Bankruptcy also shows up twice)
![consumer_financial](https://github.com/calebtran7/ABA-Pro-bono-Analysis/assets/98145591/9eb23964-4a82-4255-953c-6591e82cd0f4)

#### Education
Education (deals with school, bullying. suspension, hearing problems?)
![education](https://github.com/calebtran7/ABA-Pro-bono-Analysis/assets/98145591/19b00504-8f5d-4c3b-9a08-eaae9cafab0b)

#### Family and Children
Family and Children (dealing with marriage, father, mother) 
![family](https://github.com/calebtran7/ABA-Pro-bono-Analysis/assets/98145591/1d38fc7d-7794-4e35-8de0-6ab6d5be0f6c)

#### Health and Disability
Health and Disability (nursing, complaints, sister)
![health_disability](https://github.com/calebtran7/ABA-Pro-bono-Analysis/assets/98145591/0ee521fd-7d61-47cd-9d14-86b749457ee4)

#### Income Maintenance
Income Maintenance (trusts like bonds, social security, banks, child support)
![income](https://github.com/calebtran7/ABA-Pro-bono-Analysis/assets/98145591/d238ba6e-4f20-428e-adc4-af5a289e908b)

#### Individual Rights
Individual Rights (people have their individual rights to a lawyer, need to find a lawyer and an attorney. People are worried about their 1st amendment rights like religion. deal with those rights given in the bill of right)
![individual](https://github.com/calebtran7/ABA-Pro-bono-Analysis/assets/98145591/6e27acb2-98dd-4b46-bde9-b23675112aa8)

#### Juvenile
Juvenile (not surprisingly, deals with children)
![juvenile](https://github.com/calebtran7/ABA-Pro-bono-Analysis/assets/98145591/c261aded-11ea-4f71-af74-a98291157ae9)

#### Other
Other (other mainly has words relating to court and cases)
![other](https://github.com/calebtran7/ABA-Pro-bono-Analysis/assets/98145591/8834da53-ddb7-4d5d-b52c-32c71bf364fe)

#### Work Employment and Unemployment
Work employment and unemployment (dealing with health, holiday breaks, and covid. covid layoffs leading to unemployment, people dealing with the contracts given)
![work](https://github.com/calebtran7/ABA-Pro-bono-Analysis/assets/98145591/d06e7702-6806-414f-a8a9-14a4a75d4713)

