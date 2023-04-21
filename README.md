# A/B Testing Resources Appendix

This GitHub is a companion to our blog post ["Recommend Resources for Starting A/B Testing."](https://eddiewharton.com/2023/04/19/recommend-resources-for-starting-a-b-testing/) If there are any resources you think we should add, please file an issue or add a pull request!

## Starter Kit Overflow

* [Making Big Changes](http://iterative.club/)
* [Designing with Data](https://www.amazon.com/Designing-Data-Improving-Experience-Testing/dp/1449334830) – Book, ideal for designers/PMs or Analysts looking to improve their partnership with designers.
* [Statistical Methods in Online A/B testing](https://www.amazon.com/Statistical-Methods-Online-Testing-commerce/dp/1694079724) – Book, maps statistical concepts to A/B testing. Good for a thorough deep dive or as a reference book.
* [Trustworthy Online Controlled Experiments: Five Puzzling Outcomes Explained](https://notes.stephenholiday.com/Five-Puzzling-Outcomes.pdf) - Microsoft.
* [Communicating A/B Test Results for Conversion Rates with Ratios and Uncertainty Intervals](https://medium.com/@HarlanH/communicating-a-b-test-results-for-conversion-rates-with-ratios-and-uncertainty-intervals-4141ac66f343) - How and what metrics to show stakeholders. Especially helpful if you're designing an exp platform UI. 
* [It’s All A/Bout Testing: The Netflix Experimentation Platform](https://medium.com/netflix-techblog/its-all-a-bout-testing-the-netflix-experimentation-platform-4e1ca458c15) - Netflix.
* [How Not to Run an A/B Test](https://www.evanmiller.org/how-not-to-run-an-ab-test.html) - A classic on stats mistakes.
* [Statistical Challenges in Online Controlled Experiments: A Review of A/B Testing Methodology](https://arxiv.org/abs/2212.11366?t) - Call for more statisticians to collaborate with industry. 
* [The top 3 mistakes that make your A/B test results invalid](https://www.widerfunnel.com/blog/3-mistakes-invalidate-ab-test-results/) 

## Advanced Topics

* [Pitfalls of Long-Term Online Controlled Experiments](https://www.exp-platform.com/Documents/2016%20IEEEBigDataLongRunningControlledExperiments.pdf) - Microsoft.
* [Optional stopping in data collection: p values, Bayes factors, credible intervals, precision](https://doingbayesiandataanalysis.blogspot.com/2013/11/optional-stopping-in-data-collection-p.html) - Shows how different stopping criteria balloons error rates and one safe option. Helpful if you’re Bayesian curious, especially if you hope credible intervals are safe stopping criteria.
* [From Infrastructure to Culture: A/B Testing Challenges in Large Scale Social Networks](https://content.linkedin.com/content/dam/engineering/site-assets/pdfs/ABTestingSocialNetwork_share.pdf) - LinkedIn.
* [Data-Driven Metric Development for Online Controlled Experiments: Seven Lessons Learned](http://www.exp-platform.com/Documents/2016KDDMetricDevelopmentLessonsDengShi.pdf) - Use past experiment results to pick metrics with good properties. 
* [Improving the Sensitivity of Online Controlled Experiments by Utilizing Pre-Experiment Data](http://www.exp-platform.com/Documents/2013-02-CUPED-ImprovingSensitivityOfControlledExperiments.pdf) - Run faster experiments. Industry standard for big tech.
* [Innovating Faster on Personalization Algorithms at Netflix Using Interleaving](https://medium.com/netflix-techblog/interleaving-in-online-experiments-at-netflix-a04ee392ec55) 
* [Early Detection of Long Term Evaluation Criteria in Online Controlled Experiments](https://arxiv.org/pdf/1906.05959.pdf)
* [Improving the Sensitivity of Online Controlled Experiments: Case Studies at Netflix](https://www.kdd.org/kdd2016/papers/files/adp0945-xieA.pdf)
* [Peeking at A/B Tests](http://library.usc.edu.ph/ACM/KKD%202017/pdfs/p1517.pdf) - Understand Optimizely statistical approach when paper was published (controlling the false discovery rate).
* [A/B Testing with Fat Tails](https://www.gwern.net/docs/statistics/decision/2019-azevedo.pdf) - Meta analysis of Bing’s experiments found fat tailed impacts (ie huge impact from “outlier” positives).
* [Integrating Mediators and Moderators in Research Design](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3366634/#S7title) - Crucial concepts in experiment design and analysis.
* [Why Most Published Research Findings Are False](https://upload.wikimedia.org/wikipedia/commons/8/8e/Ioannidis_%282005%29_Why_Most_Published_Research_Findings_Are_False.pdf) Classic paper early in the replication crisis. 
* [P-Curve: A Key to the File-Drawer](https://pages.ucsd.edu/~cmckenzie/Simonsohnetal2014JEPGeneral.pdf) - Useful tool to analyze evidence quality for a set of experiments. 
* [The influence of hidden researcher decisions in applied microeconomics](https://onlinelibrary.wiley.com/doi/abs/10.1111/ecin.12992) - Important concept for experiment generalizability.
* [Switchback Tests and Randomized Experimentation Under Network Effects at DoorDash](https://medium.com/@DoorDash/switchback-tests-and-randomized-experimentation-under-network-effects-at-doordash-f1d938ab7c2a)
* [How Airbnb Measures Future Value to Standardize Tradeoffs](https://medium.com/airbnb-engineering/how-airbnb-measures-future-value-to-standardize-tradeoffs-3aa99a941ba5) - Airbnb’s system to predict long term value of actions without experiments.
* [Estimating Network Effects Using Naturally Occurring Peer Notification Queue Counterfactuals](https://arxiv.org/pdf/1902.07133.pdf)
* [Experimentation in a Ridesharing Marketplace](https://eng.lyft.com/experimentation-in-a-ridesharing-marketplace-b39db027a66e) - Some domains require a different randomization unit than users. Example in ridesharing.
* [Understanding noninferiority trials](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3510268/) 
* [Recursive partitioning for heterogeneous causal effects | PNAS](https://www.pnas.org/content/113/27/7353) - An ML approach to find segments with heterogeneous treatment effects.
* [Limiting bias from test-control interference in online marketplace experiments](https://dspace.mit.edu/handle/1721.1/117999)
* [An Empirical Meta-analysis of E-commerce A/B Testing Strategies](https://mackinstitute.wharton.upenn.edu/wp-content/uploads/2020/11/FP0398a_WP_2020Mar.pdf) - See which types of ecommerce treatments performed well in a meta-analysis. YMMV.
* [https://arxiv.org/pdf/2107.08995.pdf](https://arxiv.org/pdf/2107.08995.pdf) - Compares observational studies where treatments are opt in vs randomized A/B tests. Opt in "experiments" produce unreliable results.


## Just For Fun

* [Still Not Significant](https://mchankins.wordpress.com/2013/04/21/still-not-significant-2/) - List of creative phrases used to describe non significant results over the years. 
* [Estimated Costs of Pivotal Trials for Novel Therapeutic Agents Approved by the US Food and Drug Administration](https://jamanetwork.com/journals/jamainternalmedicine/fullarticle/2702287) - Cost estimate for pivotal clinical trials. Good to share when people complain about costs/inconvenience of A/B tests.
* [What is a p-value anyway? 34 Stories to Help You Actually Understand Statistics](https://www.amazon.com/p-value-Stories-Actually-Understand-Statistics/dp/0321629302) - Medical researcher presenting the essential concepts in thirty-four stories

## Web Apps Tools

* [Sample Size Calculator](https://www.evanmiller.org/ab-testing/chi-squared.html) - Simple, frequentist approach for conversation rates.
* [Bookings.com power calculator](https://bookingcom.github.io/powercalculator/) - Plan sample sizes with more advanced features. 
* [Chi Squared Test](https://www.evanmiller.org/ab-testing/chi-squared.html) - Simple, frequentist analysis for conversion rate differences.
* [So You Think You Can Test](https://www.lukasvermeer.nl/confidence/) - Simulation game to test and develop your experiment analysis skills.
* [Test and Roll](https://testandroll.shinyapps.io/testandroll/) - Sample size planning with the Test and Roll framework (advanced).
* [GoodUI](https://goodui.org/) - Repository of winning UIs from A/B tests. YMMV.


## Software Packages

* [Test and Roll](https://github.com/eleafeit/testandroll) - R package to set sample sizes based on test and roll framework.
* [Multtest](http://www.bioconductor.org/packages/release/bioc/html/multtest.html) - R package for resampling-based multiple hypothesis testing.
* [PyMC](https://www.pymc.io/welcome.html) - Python package for bayesian analysis.
* [PlanOut](http://facebook.github.io/planout/) - FB’s experimentation planning.
* [PlanAlyzer](https://github.com/KDL-umass/PlanAlyzer/tree/master/ocaml) - Linter for experimental designs implemented in PlanOut.
* [Ax](https://github.com/facebook/Ax?source=post_page-----6bab1e0d7845----------------------) - Python package to implement adaptive experiments from FB.



