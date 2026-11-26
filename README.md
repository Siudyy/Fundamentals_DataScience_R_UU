# Fundamentals_DataScience_R_UU
A Repository to keep track of the group assignments within the UU course “Fundamental Techniques in Data Science with R”

### Data used
European Social Survey European Research Infrastructure (ESS ERIC) (2026) ESS11 - integrated file, edition 4.2 [Data set]. Sikt - Norwegian Agency for Shared Services in Education and Research. https://doi.org/10.21338/ess11e04_2.

#### Research questions
*Linear regression:*
Can we predict how much someone trusts politicians based on their education, age, political interest and income?

*Logistic regression:*
Can we predict if someone voted based on their education, age, political intrest and income?

#### Variables and coding
| Concept | Variable name | Coding | Missing value encoding|
| --- | --- | --- | ---|
| Trust in politicians | `trstplt` | 0–10 | 77, 88, 99 |
| Voting behaviour | `vote` | 1 = Yes; 2 = No; 3 = Not eligible | 7, 8, 9 |
| Education | `eisced` | 1-7 | (55 = other), 77, 88, 99 |
| Age | `agea` | Years | 999 |
| Political interest | `polintr` | 1–4 | 7, 8, 9 |
| Household income | `hinctnta` | 1–10 | 77, 88, 99  |

### Contributors
Kacper Siudowski,
Bjorn Klaassen,
Raven Verhallen,
Nicolas Mathews
