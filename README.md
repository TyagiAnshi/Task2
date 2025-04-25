---DAY 2---
STEP 4-  Identify patterns, trends, or anomalies in the data
Age: Most passengers were between 20 and 40 years old. Some were children, and a few were over 70 — these older ages stand out as rare cases (but not necessarily errors).

Fare: Most passengers paid a low fare (under $50), but a small number paid much more (up to $500+). These are outliers — not wrong, but rare, and might affect models if not handled.

Pclass: Passengers in 1st class paid the most. There's a clear pattern: higher class → higher fare.

SibSp & Parch: Most passengers traveled with few or no relatives. A handful had big families (5+ siblings or parents/kids) — these are uncommon and worth noticing.

STEP 5-Make basic feature-level inferences from visuals.
Age: Younger adults are the most common group. This means the model may rely heavily on that age group unless we group ages into categories (child, teen, adult, senior).

Fare: High fares usually mean better accommodations, likely linked to higher survival. So, Fare is a useful predictor for survival.

Pclass: Strongly tied to both fare and survival. It's a key feature for analysis.

AgeGroup: Turning numerical ages into categories (e.g. Child, Teen, Adult) can make patterns clearer and models easier to understand.
