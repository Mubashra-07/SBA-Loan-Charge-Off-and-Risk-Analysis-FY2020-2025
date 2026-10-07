SBA Loan Charge-Off and Risk Analysis

An exploratory and statistical analysis of 346,930 SBA-backed loans approved in fiscal years 2020–2025, built in Python.

#Business Problem

Which SBA loan segments show higher observed default risk, and where is financial exposure from charged-off loans concentrated?

#Executive Summary


Overall charge-off rate is 9.2%. Of 74,938 loans that have reached a final outcome (paid in full or charged off), 6,893 were charged off and 68,045 were paid in full.
Risk is uneven across vintages. Among resolved loans, 2022 and 2023 approvals show the worst outcomes (about 14.4% and 16.9%), versus roughly 6–7% for 2020–2021.
Program matters. Community Advantage Initiative loans charged off at 28.3% and SBA Express at 12.2%, versus about 6% for Preferred Lenders and 7(a) General.
Dollar losses concentrate in restaurants and trucking. Limited-Service and Full-Service Restaurants, plus two trucking categories, lead charged-off dollars among large industries.
Interest rate is a strong risk signal. Charge-off rates climb from about 2% for loans under 4% to over 30% for loans above 12%. Each additional percentage point is associated with roughly 49% higher odds of charge-off after controlling for other factors.
Loan term, rate type and collateral are among the strongest drivers. Variable-rate loans carry about 2.7x the odds of charge-off, and uncollateralized loans about 1.7x, all else equal.



 #Recommendations

These follow from the patterns above and should be validated before being used for policy or underwriting decisions.

1.Prioritize monitoring of short-term (under 120 months), variable-rate and uncollateralized loans, which show the largest adjusted risk.

2.Apply extra scrutiny or portfolio limits to high-loss industries, particularly trucking and restaurants for dollar exposure, and the small high-rate categories for frequency.

3.Examine the Community Advantage Initiative and SBA Express programs for targeted support or tighter underwriting, since both combine elevated rates with significant volume.

4.Compare lenders on a risk-adjusted basis before drawing conclusions about underwriting quality, as raw bank rankings reflect loan mix.

