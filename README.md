##Overview of the Hackathon
Financial institutions need to assess whether customers are likely to meet their repayment obligations. Reliable risk estimates can support account review, credit-limit decisions, and early intervention while avoiding unnecessary restrictions on customers who are likely to repay.

In this competition, you will use anonymised customer credit information, including credit limits, demographic attributes, repayment history, bill amounts, and previous payments, to estimate whether a customer will default on their next payment.

The training set contains 24,000 labelled customers, while 6,000 customers are included in the hidden test set. The split is stratified so that the proportion of default cases remains comparable across both sets.

The target is default:

1 indicates default on the next payment. 0 indicates no default.

Your model must produce a probability of default rather than only a binary decision.

Participants should consider the consequences of different errors. A false negative may expose a lender to unexpected financial loss, while a false positive may lead to unnecessary restrictions for a reliable customer. Participants are also encouraged to consider model calibration, interpretability, and responsible use of demographic information.
