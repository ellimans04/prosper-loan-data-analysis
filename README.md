# Prosper Loan Data Analysis

## by Elliot Manuel Sithole


## Dataset

>Prosper Marketplace, Inc. is a San Francisco, California-based company involved in the peer-to-peer lending industry. Prosper Funding LLC, one of its subsidiaries, operates Prosper.com, a website where individuals can either invest in personal loans or request to borrow money.The Propser loan data set(https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv&sa=D&ust=1581581520570000) contains 113,937 loan entries with 81 variables on each loan, including loan amount, borrower rate, current loan status, borrower income, and many others. This data dictionary(https://www.google.com/url?q=https://docs.google.com/spreadsheet/ccc?key%3D0AllIqIyvWZdadDd5NTlqZ1pBMHlsUjdrOTZHaVBuSlE%26usp%3Dsharing&sa=D&ust=1554486256024000) elaborates on the features contained in the data set.


## Summary of Findings
### Main Goal
This investigation goal was  focused on loan status and borrower-APR features, loooking at how they interact with other categorical and numerical variables in the data set in order to gain insights on possible relationships and trends. To help  review key factors that affects loan status outcomes, and explain important determinants for borrower APR. 
#### Key Insights
1.There was  positive correlation between Borrower APR and Borrower Rate, similarly a positive correlation outcome was observed with original loan amount and monthly loan payment.

2. A negative correlation was observed between both borrower-APR and borrower rate to credit score average, albeirt not strong.

3. Frequency of Borrower-APRs was centered more around 0.1 to 0.3, with monthly income levels of between 2500 and 6000, a bracket which reflects most borrowers income levels.

4. As for the loan status, the completed loans had a median borower- APR of approximately 0.2,  lower than other categories, particularly charged-off and past-due loans.

5. The borrower-APR was lower within the group of excellent credit scores, with the pattern consistently inversely related across other credit score categories.

6. Owning a home had a bearing on loan status, with the majority having current and completed loans, and this trend reflected slightly the opposite with those defaulted and charged-off.

7. Most borrowers with excellent credit scores had current or completed loans, consequently as expected borrowers with defaulted and charged-off had poor credit scores more often.

8. The borrower rate and APR were lower with the higher the credit scores. Borrow rate and APR were roughly below 0.2 and 0.3 respectevely for excellent and good credit scores. And these values concentrated higher up in fair and poor credit score groups. And also the plots reviewed  a slight decreases in borrower rate and APR points when borrowers are homeowner than othrewise.

9. There wasn't any clear picture of any association between loan amounts, borrower ARP and loan status. But however, the majority of points were concentrated at the ARP rate of 0.35 and amounts close to or less than 5000. Hence, no clear systematic interaction of these 3 features observed.

10. The strength of the correlation between borrower rate and borrower ARP seems not to be affected by any other features assessed in the data set.

11. Higher credit scores appeared to have a significant effect in lowering borrower rate and APR and so is owning a home.

12. It seems the longer the loan term, the lower the borrower ARP, with five year term often attracting a lower borrower ARP. While, there was much variability in borrower ARP at shorter 1 year terms but with otherwise higher borrower ARPs.


## Key Insights for Presentation

The whole presentation will be focused on features; the borrower ARP and loan status outcome, and how they interact with other variables.But my explanatory will highlight only those intaractions with clear and informative trends. Fisrtly,  I will review features distribution with histograms and countplots for univariate visuals and then bivariate and finally multivariate visuals; borrower ARP vs loan status, loan status vs borrower-APR with borrower rate, credit score vs borrower-APR, credit score and home-ownership with loan status, a hitmap highlighting intarations with correlation matrix for numerical variables and lastly loan status vs Borrower-APR and Loan amount.