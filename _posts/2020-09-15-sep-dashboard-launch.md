---
layout: post

title: The SEP Dashboard visualizes Federal Reserve economic projections to better inform the public's decision making.

categories: [Dashboard, Monetary Policy]

excerpt: Today, I launched the Summary of Economic Projections (SEP) Dashboard. Its purpose is to better communicate the economic projections of the Federal Open Market Committee (FOMC), the body which sets monetary policy for the United States. The dashboard is free to access, with the intention of helping the public make better-informed economic decisions. In this post, I provide additional guidance on understanding these data and projections.
---

Today, I launched the [Summary of Economic Projections (SEP) Dashboard](https://christopher-russo.github.io/dashboard/sep/). Its purpose is to better communicate the economic projections of the Federal Open Market Committee (FOMC), the body which sets monetary policy for the United States. The dashboard is free to access, with the intention of helping the public make better-informed economic decisions. In this post, I provide additional guidance on understanding these data and projections.

The FOMC regularly prepares and releases these projections as part of their public communications strategy. Each FOMC participant submits their projections for inflation, unemployment, GDP growth, and the federal funds rate. These projections are their individual assessments of how the economy will evolve under appropriate monetary policy. In my experience, participants take great care in compiling their submissions. Underlying these submissions are weeks of work by research staffs around the Federal Reserve System. For each economic variable, I show the median projection of FOMC participants. I also show two measures of disagreement: range and central tendency. Finally, I contextualize these projections using historical data. 

In addition to projecting the next few years, participants provide “longer-run” projections. These values represent the policymaker’s belief about where the economy would ideally converge over time in the absence of further disruption. For illustration purposes, I assume that these “longer-run” values are attained within about five years. In practice, we may arrive at these longer-run figures sooner, later, or not at all.

Policymakers submit projections for five economic variables.

**PCE Inflation:** The Personal Consumption Expenditures (PCE) price index is the Federal Reserve’s preferred price measure. It measures the prices of goods and services purchased by consumers in the United States. The Fed has a price stability mandate from Congress and, under its interpretation of this mandate, the Fed targets a 2 percent annual increase in this index.

> The inflation rate over the longer run is primarily determined by monetary policy, and hence the Committee has the ability to specify a longer-run goal for inflation. The Committee reaffirms its judgment that inflation at the rate of 2 percent, as measured by the annual change in the price index for personal consumption expenditures, is most consistent over the longer run with the Federal Reserve's statutory mandate.[[1]](#note1)<a name="back1"></a>

As of writing, PCE inflation has generally run below 2 percent since the adoption of this target in January 2012. Still, policymakers have regularly emphasized that 2 percent is an intended average and not a cap. If policymakers are successful under their recently-adopted policy of Average-Inflation Targeting, PCE inflation will first overshoot before returning to 2 percent.

> The Committee seeks to achieve inflation that averages 2 percent over time, and therefore judges that, following periods where inflation has been running persistently below 2 percent, appropriate monetary policy will likely aim to achieve inflation moderately above 2 percent for some time.[[2]](#note2)<a name="back2"></a>

So far, policymakers have been intentionally ambiguous about how high they intend to let inflation run, as well as for how long. As recently explained by FOMC Chairman Powell,

> In seeking to achieve inflation that averages 2 percent over time, we are not tying ourselves to a particular mathematical formula that defines the average... Our decisions about appropriate monetary policy will continue to reflect a broad array of considerations and will not be dictated by any formula.[[3]](#note3)<a name="back3"></a>

As a result, I have omitted the “longer-run” projections for PCE inflation. Consistent with their consensus target, all participants have a longer-run projection of 2 percent.

**Core PCE Inflation:** The Personal Consumption Expenditures Excluding Food and Energy (PCEXFE) price index ignores the volatility in food and energy prices. Policymakers generally use changes in PCEXFE, or so-called “core” inflation, to better understand inflation trends. FOMC participants do not submit a longer-run projection for core PCE inflation.

**Unemployment Rate:** The Unemployment Rate (also called U-3) measures the number of people without a job who are actively looking and available for work, as a percentage of the labor force. Although the Fed has a maximum employment mandate from Congress, the Fed does not specify a fixed target for U-3. While U-3 is informative, policymakers consider a range of indicators.

>The maximum level of employment is a broad-based and inclusive goal that is not directly measurable and changes over time owing largely to nonmonetary factors that affect the structure and dynamics of the labor market. Consequently, it would not be appropriate to specify a fixed goal for employment; rather, the Committee’s policy decisions must be informed by assessments of the shortfalls of employment from its maximum level, recognizing that such assessments are necessarily uncertain and subject to revision. The Committee considers a wide range of indicators in making these assessments.[[4]](#note4)<a name="back4"></a>

**Real GDP Growth:** Real GDP is a comprehensive measure of U.S. economy activity. It measures the value of goods and services in the United States after accounting for changes in prices. This adjustment allows for comparisons between different periods. Real GDP is closely tied to the income of houses and firms in the United States, and hence growth in real GDP is a key economic indicator.

**Federal Funds Rate:** The fed funds rate is the rate at which banks borrow from each other overnight. Under current policy, this rate is closely tied to the interest rate the Fed pays eligible banks on their reserve deposits held at the Fed.

The fed funds rate is the Fed’s primary tool for monetary policy. Raising (lowering) the fed funds rate tends to raise (lower) other dollar-denominated interest rates. This includes interest rates on Treasury securities, repurchase agreements, mortgages, auto loans, and consumer savings. Using this transmission, the Fed adjusts the fed funds rate to expand or contract credit in the economy, thereby stimulating or constraining growth in economic activity.

**Acknowledgements:** I created the [SEP Dashboard](https://christopher-russo.github.io/dashboard/sep/) using the Bokeh (pronounced “bouquet”) visualization library for Python. My sincere thanks to the Bokeh and Python teams, contributors, and sponsors. For more information, please see [https://bokeh.org](https://bokeh.org) and [https://www.python.org](https://www.python.org).

___

<a name="note1"></a> [[1]](#back1) Federal Open Market Committee, “Statement on Longer-Run Goals and Monetary Policy Strategy”, as amended effective August 27, 2020. Retrieved from <https://www.federalreserve.gov/monetarypolicy/files/FOMC_LongerRunGoals.pdf>, September 15, 2020.

<a name="note2"></a> [[2]](#back2) *ibid.*

<a name="note3"></a> [[3]](#back3) Jerome Powell (Board of Governors), “New Economic Challenges and the Fed’s Monetary Policy Review”, published August 27, 2020. Retrieved from <https://www.federalreserve.gov/newsevents/speech/powell20200827a.htm>, September 15, 2020.

<a name="note4"></a> [[4]](#back4) See note 1.

___

&copy; 2020 Christopher Russo. All rights reserved.