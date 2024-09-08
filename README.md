# Uber-POOL-project-analysis

**Overview**
Uber, founded in 2009 as a luxury car service, rapidly grew with the introduction of UberX in 2012, offering more affordable rides. By 2018, Uber had expanded globally with 75 million riders and a valuation of $62 billion, despite competition from other ride-sharing platforms. Data science played a pivotal role in its innovation, while the launch of UberPOOL in 2014 faced challenges, becoming unprofitable by 2016 due to unmatched rides.

**Objective**- to Understand How could Uber improve the POOL experience?

**Data collection**
- Surveys: Involves asking users hypothetical questions about new products; offers wide reach but lacks accuracy.
- Simulation: Tests new features using historical or artificial data; limited by assuming rather than measuring customer choices.
- Experiments: Introduces new features to users randomly and measures responses; accurate but costly and may negatively impact user experience.

**The project**
- The team comprised product managers, operations specialists, engineers, and data scientists, facing trade-offs
between rider experience and cost efficiency.
- The team aimed to quantify positive trip experiences with **specific metrics** rather than relying on vague feelings,
focusing on revenue generation through increased riders on shared trips.
- Metrics for rider experience included opt-in rates and rider cancellation rates, while cost efficiency was
measured by the number of occupied seats per minute and per mile, aiming for three riders to one driver.

**Type of experiments in Uber**
- User-level A/B: Randomly assigns users to treatment or control groups to measure the impact of changes on user behavior, such as product placement.
- Switchback experiments: Alternates between standard and revised features over time for all users, ensuring balanced exposure to both versions.
- Synthetic control experiments: Randomizes treatment and control at the city level, comparing outcomes (e.g., demand) between cities with and without new features like a rider app.

**Observations and Results**
- The average saving from 2mins to 5mins is approximately 0.36$.
- The average number of trips is approximately 3880.
- There are nine periods in each day.
- Thus, Uber can save about 12K daily only in Boston!
⇒ More than 4 million dollars of savings per year in only one city.
- The results of the experiments indicate a decrease in cost and quality of service.
- The changes in cost were significant, in contrast to the cancellation rate.
- However, the total number of Express trips also decreased.
