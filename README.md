AI-assisted budget vs. actual analysis
Allsun Howe

This FP&A case study uses six months of synthetic data for a subscription business. It shows how to reconcile a revenue miss, explain the operating profit variance, and check an AI-drafted briefing before sharing it.
- [Excel model](Subscription_Budget_vs_Actual.xlsx)
- [One-page CFO briefing](CFO_Briefing.pdf)
What the model shows
June 2026	Budget	Actual	Actual less budget
Subscription revenue	$100,000	$94,500	($5,500)
Payroll	$45,000	$47,000	$2,000
Marketing	$15,000	$14,200	($800)
Other operating costs	$10,000	$10,600	$600
Operating profit	$30,000	$22,700	($7,300)


The June revenue miss was the largest of the six months. The business billed 1,125 subscribers against a budget of 1,250. Revenue per subscriber was $84 versus $80 budgeted. The volume effect was ($10,000) and the price/mix effect was +$4,500, which reconciled to the ($5,500) revenue variance. The $4 per subscriber difference could reflect pricing or subscription mix. The dataset tracks the average rate only.
AI-assisted commentary review
The drafting prompt and review below show how the AI was used. Excel supplies the numbers, and the briefing reflects the checked interpretation.
Draft a short CFO update using the June budget and actual figures and the revenue bridge. Explain the revenue and operating profit variances, flag anything the available data cannot establish, and suggest one follow-up.

Illustrative first-pass AI wording	Review against the workbook	Final treatment
“Revenue missed by $5,500 as lower subscriber volume outweighed the higher average rate.”	The revenue bridge ties to the June variance.	Kept the explanation and quantified both effects.
“Churn drove the subscriber shortfall.”	The inputs show total billed subscribers. They do not track cancellations, renewals, or signups.	Removed the churn claim. The briefing calls for a reconciliation of the 125-account gap.
“Marketing savings offset the payroll overage.”	Marketing saved $800 against a $2,000 payroll overage. Other operating costs were $600 over plan.	Described the partial offset and showed the $1,800 net cost overage.


How to use the workbook
1. Open Budget vs Actual for the six-month summary, monthly results, and June revenue bridge.
2. Edit blue cells on Sample Inputs. Revenue equals billed subscribers multiplied by average revenue per subscriber. Operating profit deducts payroll, marketing, and other operating costs.
3. Check Reconciliation under the June bridge. It should read 0.00. The volume effect uses budgeted revenue per subscriber. The price/mix effect uses actual billed subscribers.
All budget and actual figures are synthetic. Operating profit excludes interest and taxes. The PDF records the supplied sample case and is a static snapshot.
