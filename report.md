# AlphabetSoup Charity Optimization Report

### Overview

    This analysis is being undetaken for the Alphabet Soup Foundation. Every Year, Alphabet Soup gets applications from business entities looking for fudning for their company and they want to imporve their chasnces of selecting sucessful business ventures to fund. In orde to help them imporve, I will compiling a neural network that will predict the likelihood that a business will succeed if it receives funding.

    While analyzing the data I saw that 25,394 of the applicant were asking for$5,000.00 in funding. I decided it woulod best to focus the analysis in these companies as they make up the bulk of the foundations applicants. Thus, The model I am building will predict the likelihood that a company asking for $5,000.00 in funding will succeed.

### Results

### Data Preprocessing

    The data consists of 34,000 records that include metatdata on each comapny such as the appication type, affiliation, cliassification, use_case, organization, status, income amount, special considerations, the ask amount, and whether it was successful.

    There were a few transformations  done to the data. First, the EIN and name columns were dropped as they would not be usefull for the analysis. Second, some columns with multple values were binned. First, the top 5 most common application types were kept while all of the other application types were grouped into 'other'. Second,  only the top 5 classifications were kept and the rest were converted to 'other'. Thirdly, since  25,394 of the 34,000 applicants were asking for $5,000, I decided to drop the other amounts and only focus on these companies in the analysis. Lastly, there were 5 record where the applcation was not active so these were dropped as well.

### Model Compiling, Training , and Evaluation



### Summary and Recommendations
