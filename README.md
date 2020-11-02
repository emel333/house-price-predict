# house-price-predict
--
Completed by: Marvin Lee

# Big Question: How can one predict U.S. tokenized real estate asset prices in a trustless manner?
--

<ul>
    <li>Can a reliable price prediction model be developed without more subjective evaluations like "conditon" and "grade"?</li>
    <li>How reliable can a "location-agnostic" house price predictor be?</li>
    <li>What should a conservative price prediction model determining borrower collateral parameters be based on?</li>
</ul>


# Process (& Data Science Tools) Used:
--

<ul>
    <li>Used the <i>kc_house_data</i> set provided by Flatiron School for cleaning, analyzing and modeling</li>
    <li>Research conducted on tokenized real estate investment platforms in the cryptocurrency space</li>
    <li>With "price" as the target dependent variable, developed a multivariate regression model</li>
    <li>Evaluated independent variables according to assumptions for linear regressions</li>
    <li>Completed select feature engineering to test hypotheses and explore independent variable relationships</li>
    <li>Separated data into train-test splits for the modeling process</li>
    <li>Focused on the R-squared value of OLS table outputs to determine model effectiveness</li>
    <li>Used stepwise addition (given large number of variables) to identify key independent variables best for model</li>
    <li>As well -- used skikit-learn, scipy, matplotlib, numpy and more</li>
</ul>


# Findings:
--

### Strong positive correlation between Livable Square Footage and number of Bathrooms

### R2 value of "0.832" without more subjective variables like "grade" or "condition" included and with minimal features beyond zipcode (the most significant factor)

### The bare minimum variables (when zipcode data is available)



# Final Model:
--

The final model reveals an adjusted R2 of 0.832. Here's a screenshot of the first OLS table run:

And now, here's a screen shot of the final OLS table:

The key adjustments made along the way:

<ul>
    <li>
</ul>



# Summary + Further Research:
--

<ul>
    <li>Given the dataset used here, creating a reliable and trustless method for home price prediction needs location-specific data</li>
    <li>Livable square footage is most important (along with zicpode details) to determine convservative price predictions to be used for loan collateral amount levels</li>
    <li>REC #1: Develop "condition" or "grade" score by leveraging <i>trustless</i> independent variables</li>
    <li>REC #2: Perform "segmented modeling" according to home price ranges (i.e. 0-250,250-500,500-750, 750-1M, etc.)</li>
    <li>REC #3: Evaluate the impact of a "finished basement" (having a basement + have a renovation done) on the model</li>
</ul>