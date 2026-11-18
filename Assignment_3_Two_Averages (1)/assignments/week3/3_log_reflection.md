Cleaning Log, AI Audit and Reflection

Overview

I used descriptive statistics to compare the mean, median and first-to-last percentage change for four staple items. I also compared the mean and median for one item with and without a flagged value.

Data limitation

The original teaching_prices_clean_working.csv and Week 2 cleaned file were not present in the Assignment 2 ZIP that was supplied as a style reference. The figures in this submission are therefore illustrative. The value 1250 was mentioned as a flagged Staple A observation in the previous Assignment 2 draft, but the other comparison values are examples and are not recovered source data. I have kept this limitation visible instead of presenting invented figures as verified observations.

1. Statistics Table

       Item  Mean (PKR/kg)  Median (PKR/kg)  First-to-last change (%)
   Staple A         106.50            106.0                     15.00
    Pulse C         232.83            231.0                     13.64
Sweetener D         157.33            157.5                     10.00
      Oil B         313.33            312.5                     10.00

2. Flagged-value comparison

Illustrative Staple A values: 100, 102, 104, 108, 110, 1250.

- Mean including 1250: 295.67
- Median including 1250: 106.00
- Mean excluding 1250: 104.80
- Median excluding 1250: 104.00

The mean changes substantially because the flagged value is much larger than the other observations. The median changes less because it is based on the middle of the ordered values. The flagged value should be investigated and documented; it should not be deleted without a reason.

3. Interpretation Auditor: Audit Table

The following is a worked audit of example interpretations. It is not presented as a transcript from an external AI session. If an AI tool gives different statements, those statements should be checked and logged separately.

| Example AI interpretation | Colour | Decision | Reason |
|---|---|---|---|
| The mean and median for Staple A are close in the illustrative series. | Green | Accept | This can be checked directly from the calculated table. |
| The flagged value may pull the mean upwards. | Amber | Accept as a possibility | The calculation shows the mean changes; the explanation is statistical interpretation. |
| Inflation caused the increase in all staple prices. | Red | Reject | The dataset does not contain evidence identifying the cause. |
| Every household paid the prices shown. | Red | Reject | The data does not establish household-level prices or coverage. |
| The first-to-last percentage change describes every price movement during the period. | Red | Reject | It compares only the first and last observations. |

4. Prompt for the Interpretation Auditor

I would paste the statistics table into an AI tool and use this prompt:

"Act as an interpretation auditor. Explain what the mean, median and first-to-last percentage change show. Identify statements that are directly supported by the table, possible explanations, and causal claims that the data cannot prove. Do not rewrite my referee's note."

5. Confused Classmate: Example Excerpt

The excerpt below is a practice example showing the type of explanation required. It is not claimed to be a verbatim transcript of a separate conversation.

Classmate: "The mean is always the typical price, so why do we need the median?"

Me: "The mean uses every value, so an unusually high or low value can pull it away from most observations. The median is the middle value after arranging the prices in order."

Classmate: "So is the median always better?"

Me: "No. If the data has no extreme values and is fairly balanced, the mean can be useful because it uses all observations. If there is an extreme value, the median may describe the centre more fairly."

Classmate: "Does a higher mean prove that prices went up?"

Me: "Not by itself. We need to compare observations over time. The mean describes the average level, while the first-to-last percentage change compares the two endpoints."

6. Reflection

At first, it is easy to treat a higher mean as proof that the typical price has increased. However, the mean can be affected by an unusually high observation. The median gives another view of the centre and is less sensitive to an extreme value.

I also need to be careful about the difference between an observation and a cause. The data can show that the first recorded price is lower than the last recorded price, but it cannot explain why this happened. It would be too strong to blame inflation, government policy or transport costs unless there is separate evidence.

The main lesson from this exercise is that the mean and median should be considered together. Neither one is automatically correct in every situation. The choice depends on the data and on what the question is asking.

7. Attempt-before-AI Snapshot

SHA-256 of 1_attempt.md:

77f136c1a03417440e9be659540d9b5f884d487bfa6fb75746300428309cb821

This hash identifies the exact draft saved in 1_attempt.md at the time this package was created. If the file is edited later, its hash will change.
