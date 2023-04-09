# A/B Test Resources Appendix

We wrote post... 


## Starter Kit Resource Overflow

* [Optional stopping in data collection: p values, Bayes factors, credible intervals, precision](https://doingbayesiandataanalysis.blogspot.com/2013/11/optional-stopping-in-data-collection-p.html): shows how different stopping criteria balloons error rates and one safe option. Helpful if you’re Bayesian curious, especially if you hope credible intervals are safe stopping criteria.
* [Making Big Changes](http://iterative.club/)
* [Designing with Data](https://www.amazon.com/Designing-Data-Improving-Experience-Testing/dp/1449334830) – book, ideal for designers/PMs or Analysts looking to improve their partnership with designers.
* [Statistical Methods in Online A/B testing](https://www.amazon.com/Statistical-Methods-Online-Testing-commerce/dp/1694079724) – book mapping statistical concepts to A/B testing. Good for a thorough deep dive or as a reference. Recommend reading the Trustworthy Experiments book first.
* [Trustworthy Online Controlled Experiments: Five Puzzling Outcomes Explained](https://notes.stephenholiday.com/Five-Puzzling-Outcomes.pdf) (Microsoft)
* [Communicating A/B Test Results for Conversion Rates with Ratios and Uncertainty Intervals](https://medium.com/@HarlanH/communicating-a-b-test-results-for-conversion-rates-with-ratios-and-uncertainty-intervals-4141ac66f343) how and what metrics to show stakeholders (use a forest plot on % lift). Helpful if you design exp platform UIs. 
* Netflix - [It’s All A/Bout Testing: The Netflix Experimentation Platform](https://medium.com/netflix-techblog/its-all-a-bout-testing-the-netflix-experimentation-platform-4e1ca458c15)  
* [The top 3 mistakes that make your A/B test results invalid](https://www.widerfunnel.com/blog/3-mistakes-invalidate-ab-test-results/) 
* [How Not to Run an A/B Test](https://www.evanmiller.org/how-not-to-run-an-ab-test.html)
* [Statistical Challenges in Online Controlled Experiments: A Review of A/B Testing Methodology](https://arxiv.org/abs/2212.11366?t) - Call for more statisticians to collaborate with industry 
* [Democratizing Online Controlled Experiments at Booking.com](https://arxiv.org/pdf/1710.08217.pdf)


## Advance Topics


* [Pitfalls of Long-Term Online Controlled Experiments](https://www.exp-platform.com/Documents/2016%20IEEEBigDataLongRunningControlledExperiments.pdf) (Microsoft)
* [From Infrastructure to Culture: A/B Testing Challenges in Large Scale Social Networks](https://content.linkedin.com/content/dam/engineering/site-assets/pdfs/ABTestingSocialNetwork_share.pdf) (LinkedIn)
* [Data-Driven Metric Development for Online Controlled Experiments: Seven Lessons Learned](http://www.exp-platform.com/Documents/2016KDDMetricDevelopmentLessonsDengShi.pdf)
* Run faster experiments
    * [Improving the Sensitivity of Online Controlled Experiments by Utilizing Pre-Experiment Data](http://www.exp-platform.com/Documents/2013-02-CUPED-ImprovingSensitivityOfControlledExperiments.pdf) 
    * [Innovating Faster on Personalization Algorithms at Netflix Using Interleaving](https://medium.com/netflix-techblog/interleaving-in-online-experiments-at-netflix-a04ee392ec55)
    * [Early Detection of Long Term Evaluation Criteria in Online Controlled Experiments](https://arxiv.org/pdf/1906.05959.pdf)
    * [Improving the Sensitivity of Online Controlled Experiments: Case Studies at Netflix](https://www.kdd.org/kdd2016/papers/files/adp0945-xieA.pdf)
* [Peeking at A/B Tests](http://library.usc.edu.ph/ACM/KKD%202017/pdfs/p1517.pdf) Understand Optimizely’s statistical approach (false discovery rate control)
* [A/B Testing with Fat Tails](https://www.gwern.net/docs/statistics/decision/2019-azevedo.pdf) Meta analysis of Bing’s experiments found fat tailed impact (ie huge impact from “outlier” positives); implication is run more experiments for less time. Helpful for DS’s at bigger companies debating policies and if reasoning about lift distributions (priors, meta-analysis).
* [Integrating Mediators and Moderators in Research Design](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3366634/#S7title)
* Meta science more broadly
    * Add classic “most published results are false” paper that kickstarted open science movement (Ionadas author I think)
    * [P-Curve: A Key to the File-Drawer](https://pages.ucsd.edu/~cmckenzie/Simonsohnetal2014JEPGeneral.pdf)
    * [The influence of hidden researcher decisions in applied microeconomics](https://onlinelibrary.wiley.com/doi/abs/10.1111/ecin.12992)
* Quasi experimental alternatives
    * [Switchback Tests and Randomized Experimentation Under Network Effects at DoorDash](https://medium.com/@DoorDash/switchback-tests-and-randomized-experimentation-under-network-effects-at-doordash-f1d938ab7c2a)
    * [Estimating Network Effects Using Naturally Occurring Peer Notification Queue Counterfactuals](https://arxiv.org/pdf/1902.07133.pdf) – haven’t read fully
* [How Airbnb Measures Future Value to Standardize Tradeoffs](https://medium.com/airbnb-engineering/how-airbnb-measures-future-value-to-standardize-tradeoffs-3aa99a941ba5)
    * Airbnb’s system to predict long term value of actions without experiments 
* [Experimentation in a Ridesharing Marketplace](https://eng.lyft.com/experimentation-in-a-ridesharing-marketplace-b39db027a66e) - randomization units besides user
    * [To-do: find other paper from a social network (LinkedIn?) on this]
* [Understanding noninferiority trials](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3510268/)
* [Recursive partitioning for heterogeneous causal effects | PNAS](https://www.pnas.org/content/113/27/7353) for an ML based approach to find segments with HTE in experiments - have not fully read
* [Limiting bias from test-control interference in online marketplace experiments](https://dspace.mit.edu/handle/1721.1/117999) – haven’t read
* Recent papers (2020-23) that are partially read or not at all
    * [An Empirical Meta-analysis of E-commerce A/B Testing Strategies](https://mackinstitute.wharton.upenn.edu/wp-content/uploads/2020/11/FP0398a_WP_2020Mar.pdf) for a meta-analysis of experiments 
    * [https://arxiv.org/pdf/2107.08995.pdf](https://arxiv.org/pdf/2107.08995.pdf) – compares observational studies where treatments are opt in vs randomized A/B tests – they seem unreliable