# Awesome Risk Quantification

Risk quantification attempts to assign numeric values to risks, instead of qualitative labels such as "Critical"
and "High".

Doing this makes it easier to prioritize the different risks we need to mitigate. Also, "you can't
improve what you can't measure"!

This repository focuses primarily on cybersecurity related risks.

## Open Source Projects

- [Raven](https://github.com/idaholab/raven) - a "flexible and multi-purpose uncertainty quantification, regression analysis, probabilistic risk assessment, data analysis and model optimization framework" from the Idaho National Laboratory
- [riskquant](https://github.com/Netflix-Skunkworks/riskquant) - a library for computing risk, using different distributions, from Netflix
- [evaluator](https://github.com/davidski/evaluator) - R package for quantitative risk assessment, based upon [OpenFAIR](https://www.opengroup.org/certifications/openfair)
- [collector](https://github.com/davidski/collector/) - R package for "conducting quantitative risk assessment interviews"

## Blog Posts and Papers

- [Open-Sourcing riskquant, a library for quantifying risk](https://netflixtechblog.com/open-sourcing-riskquant-a-library-for-quantifying-risk-6720cc1e4968) - demonstrates how to use
their [riskquant](https://github.com/Netflix-Skunkworks/riskquant) library
- [2018 in Review: How Our Bug Bounty Program Guided Prioritizing Work](https://hackerone.engineering/posts/2018-in-review-how-our-bug-bounty-program-guided-prioritizing-work)
- [Forecasting Risk inside an Organization](https://wardolphin.party/2020/01/24/Forecasting-risks-inside-an-organisation.html) - a post on how Atlassian attempts to forecast the chance of detecting red team operations, with the goal of improving detection over time.
- [Simple Risk Measurement](https://magoo.github.io/simple-risk/) - in-depth guide covering scenarios, calibration, panels, Brier scores, Monte Carlo simulations, and a lot more.
- [Ryan McGeehan's Blog](https://scrty.io/) - has 30+ posts on measuring risk and forecasting.
- [Risk Management: Out with the Old, In with the New!](https://exploringpossibilityspace.blogspot.com/2013/08/risk-management-out-with-old-in-with-new.html) - proposes we think of risks as parts of an interconnected system, not as isolated entities
- [A New Approach for Managing Operational Risk](https://www.soa.org/globalassets/assets/files/research/projects/research-new-approach.pdf) - expounds on the approach in the article above, applying it to financial risk specifically

## Books

- [Measuring and Managing Information Risk: A FAIR Approach](https://www.amazon.com/Measuring-Managing-Information-Risk-Approach/dp/0124202314) - describes the [FAIR](https://en.wikipedia.org/wiki/Factor_analysis_of_information_risk) framework for measuring risk
- [How to Measure Anything in Cybersecurity Risk](https://www.amazon.com/How-Measure-Anything-Cybersecurity-Risk-ebook/dp/B01J4XYM16) - a spin-off of the author's [How to Measure Anything Book](https://www.amazon.com/How-Measure-Anything-Intangibles-Business-ebook/dp/B00INUYS2U), specifically for cybersecurity risk

## Talks

- [Quantifying Risk](https://www.infoq.com/presentations/risk-quantification-netflix/) by Markus De Shon (2020) - walks through the process of measuring risk, from identifying threats and assets to guessing frequency and magnitude (in terms of money)
- [Forecasting, Browsers, and “In The Wild” Exploitation](https://www.youtube.com/watch?v=vzcmzj-JuWk) by Ryan McGeehan (2019) - Ryan forecasts the probability of a Chrome zero day being exploited in the wild in a certain month  