# Customer Segmentation Portfolio

A portfolio of customer segmentation projects on real transaction data: Online Retail II (UCI) and Olist (Brazilian e-commerce). Each project is its own GitHub repository with tests, an executed notebook, and a README. Where a result was negative or a check failed, the README says so.

## Projects

| # | Name | Dataset | Main method | Repository |
|---|------|---------|-------------|-------------|
| CS01 | RFM Segmentation with KMeans | Online Retail II (UCI) | RFM features, KMeans with silhouette-based k | [rfm-kmeans-segmentation](https://github.com/Patotricks15/rfm-kmeans-segmentation) |
| CS02 | Customer Value Regression | Online Retail II (UCI) | Gradient-boosted future spend, time-ordered snapshots, beats segment-mean baseline | [customer-value-regression](https://github.com/Patotricks15/customer-value-regression) |
| CS03 | Soft Segments with Gaussian Mixtures | Online Retail II (UCI), substituted for E-Commerce Data | GMM with BIC selection and membership probabilities | [gmm-soft-segments](https://github.com/Patotricks15/gmm-soft-segments) |
| CS04 | Hierarchical Segment Profiling | Olist | Ward clustering on a sample, decision-tree surrogate for readable rules | [hierarchical-segment-profiling](https://github.com/Patotricks15/hierarchical-segment-profiling) |
| CS05 | Segment Stability Bootstrap | Online Retail II (UCI) | Bootstrap ARI and cross-window ARI, thresholds fixed before the run | [segment-stability-bootstrap](https://github.com/Patotricks15/segment-stability-bootstrap) |
| CS06 | Segment-Level Offer Economics | Olist | Break-even uplift per segment with explicit uplift assumption and bootstrap intervals | [segment-policy-simulation](https://github.com/Patotricks15/segment-policy-simulation) |

## Scope

Each repository is self-contained and can be cloned, tested, and run independently. Raw data is not committed. Olist is licensed CC BY-NC-SA 4.0 (non-commercial), so check that licence before reuse. CS03 uses Online Retail II instead of the planned E-Commerce Data set, whose licence could not be confirmed.
