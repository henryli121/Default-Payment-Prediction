# Default-Payment-Prediction
Developed a predictive model for whether an account will default next month, given the historical payment data

<!DOCTYPE html>
<html>
  <body>
    <h1>Dataset Description</h1>
    <p>Our client is a credit card company. They have brought us a dataset that includes some demographics and recent financial data, over the past 6 months, for a sample of 30,000 of their account holders. This data is at the credit account level; in other words, there is one row for each account. Rows are labeled by whether, in the next month after the 6-month historical data period, an account owner has defaulted, or in other words, failed to make the minimum payment.</p>
    <h2>Goal</h2>
    <p>Your goal is to develop a predictive model for whether an account will default next month, given demographics and historical data.</p>
    <h2>Data Dictionary</h2>
    <p>The target label is a binary variable: default payment next month (Yes = 1, No = 0). The data set has the following 23 variables as explanatory variables, together with an ID variable defining the cases:</p>
    <ul>
      <li>LIMIT_BAL: Amount of the given credit (NT dollar): it includes both the individual consumer credit and his/her family (supplementary) credit</li>
      <li>SEX: Gender (1 = male; 2 = female)</li>
      <li>EDUCATION (1 = graduate school; 2 = university; 3 = high school; 4 = others)</li>
      <li>MARRIAGE: Marital status (1 = married; 2 = single; 3 = others)</li>
      <li>AGE: (year)</li>
      <li>PAY_1 - PAY_6: History of past payment. We tracked the past monthly payment records (from April to September, 2005) as follows:</li>
      <ul>
        <li>PAY_1 = the repayment status in September, 2005;</li>
        <li>PAY_2 = the repayment status in August, 2005;</li>
        <li>...</li>
        <li>PAY_6 = the repayment status in April, 2005.</li>
      </ul>
      <p>The measurement scale for the repayment status is: -1 = pay duly; 1 = payment delay for one month; 2 = payment delay for two months; ...; 8 = payment delay for eight months; 9 = payment delay for nine months and above.</p>
      <li>BILL_AMT1 - BILL_AMT6: Amount of bill statement (dollar).</li>
      <ul>
        <li>BILL_AMT1 = amount of bill statement in September, 2005;</li>
        <li>BILL_AMT2 = amount of bill statement in August, 2005;</li>
        <li>...</li>
        <li>BILL_AMT6 = amount of bill statement in April, 2005.</li>
      </ul>
      <li>PAY_AMT1 - PAY_AMT6: Amount of previous payment (dollar).</li>
      <ul>
        <li>PAY_AMT1 = amount paid in September, 2005;</li>
        <li>PAY_AMT2 = amount paid in August, 2005;</li>
        <li>...</li>
        <li>PAY_AMT6 = amount paid in April, 2005.</li>
      </ul>
    </ul>
  </body>
</html>
