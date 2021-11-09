# Amazon-reviews-fraud-detection

[Watch the complete project video here!](https://www.youtube.com/watch?v=fDV3ELWiaAk&t=1s) 

## Backgorund
- The majority of listings on amazon aren't sold directly by amazon, 54% of units sold on amazon in the second quarter of 2019 were from third-party sellers this is hard to
- This makes it hard to differentiate honest sellers from dishonest sellers
- Global sales of counterfeits are increasing 15% a year and it is estimated to reach 1.82 trillion by 2020 

## Objective
- Scraping reviews of products to confirm if the product is counterfeit or not then building models to distinguish between the two classes of outcomes 
- Examine key words that signal counterfeit complaints or not, the aim is to bring awareness about counterfeit products sold on Amazon to the general public 

## Product used
- Anastasia Beverly Hills COntour kit and brow kit.


- These counterfeit products that are of a lesser quality can very much damage the brand's reputation as well as Amazon's reputation. To further investigate this problem, three to four hundred reviews for each makeup product were scraped from Amazon.
- Each indivdual reviews were examined and keywords will distinguish between a counterfeit and non-counterfeit claim.
-  To further preprocess reviews, stop words were removed along with removing any unnecessary words or punctuation like  removing any points or extra commas characters etc
that would alter with model performance

## Model Creation
- 0 label: No counterfeit complaint
- 1 label: Counterfeit complaint


