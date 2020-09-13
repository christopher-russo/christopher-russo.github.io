---
layout: post

title: The sizes of federal liabilities are uncertain and state-contingent.

categories: [Financial Crises, Fiscal Policy]

excerpt: Properly accounting for federal liabilities is difficult because their sizes are uncertain and state-contingent, with off-balance-sheet liabilities structured like short, out-of-the-money puts. In good times, the government's creditworthiness may nonetheless allow it to borrow extraordinary amounts at low interest rates. In bad times, these liabilities expose the government to extreme and correlated losses which threaten fiscal solvency and financial stability.
---

Continued from: ["The U.S. faces increased risk of debt crisis."](https://christopher-russo.github.io/debt-crisis/)

As previously discussed, Treasury "debt held by the public" (currently about 98 percent of GDP) substantially understates the federal government's true liabilities. By incorporating major liabilities held at the Federal Reserve, I placed the federal government's on-balance-sheet liabilities at 130 percent of GDP. This measure is still flawed because it does not incorporate the government's many off-balance-sheet liabilities. I mentioned three: the exposure to loss from MBS guarantees; the exposure to loss from student loans and loan guarantees; and the unfunded obligations of the Social Security, Medicare, and Highway programs. There are many others: for example, the Treasury's backstop of the FDIC and the Fed's crisis facilities, their guarantee of state and local pensions, and their obligations for federal retirement benefits.

It is difficult to properly account for off-balance-sheet federal liabilities. First, the underlying programs are legally complex and modeling results are highly sensitive to one's assumptions. For example, while the size of the agency MBS universe stands at about $9 trillion, Treasury's true liability is only some (unknown) fraction of this value. This fraction depends on which of the mortgages underlying these securities will default; this itself depends on a complex interaction between economic growth, housing prices, borrower-and-loan-specific characteristics, the legal terms of the mortgages, etc.

Aside from this, we often lack enough data to estimate realistic models of default. Instead, we're forced to make very strong assumptions (e.g. Gaussian copulas) which will break down during a crisis. Continuing with the MBS example, Freddie Mac's "Single Family Loan-Level Dataset" provides data on the credit performance of a portion of the mortgages they have purchased or guaranteed.[[1]](#note1)<a name="back1"></a> Yet, since these data only run through 2018, they provide no insight into the credit deterioration of the 2020's mortgage market. More fundamentally, our limited historical default data--most of which is from non-crisis times--may not be statistically informative about an unprecedented crisis. These same points also hold for the commercial paper, corporate bonds, and municipal bonds now on the Fed's balance sheet.

Second, the size of these liabilities is driven by a kind of state contingency. For example, despite the "quiet period" in U.S. commercial banking following the 1930's, runs on commercial deposits re-emerged in 2008Q3. 

> At a variety of institutions, depositors withdrew significant amounts of money in just days or weeks... Most notably, Wachovia and Washington Mutual, the fourth and sixth largest depository institutions in the country at the time, experienced heavy deposit outflows and other important liquidity pressures that led to the rapid sale of each to other institutions. Depositors at Washington Mutual withdrew 9 percent of its deposits in just 9 days, and supervisors envisioned stress scenarios in which certain institutions could lose 1.5-2.0 percent of deposits a day.[[2]](#note2)<a name="back2"></a>

In normal times, programs such as FDIC insurance and bank supervision are effective at preventing bank runs on commercial deposits. In such times, although the FDIC insures a large volume of deposits, its actual liability is low. However, in crisis times like 2008, these programs can become ineffective and the potential liability becomes large. Like in the Diamond-Dybvig model[[3]](#note3)<a name="back3"></a>, we can think of this as a kind of regime switching. "Sunspots" (events which cause a switch from the normal to crisis regime) could include bad news about other aspects of the government's fiscal position. 

In this way, these {% include pullquote.html quote="off-balance-sheet liabilities constitute a portfolio of short, out-of-the-money put options. Said differently, the government is exposed to extreme losses in the worst states of the world." %} Just as asset-return correlations spike in crises, so do the correlations of factors underlying these puts: if one option is exercised, then the probability increases that the others will be, too. In my view, this is the essence of debt-crisis risk. The issue is not large, stationary debt-to-GDP ratios at low interest rates; these may be appropriate for industrialized, growing, and well-run nation states. Rather, the problem is the systemic risk introduced from ever-increasing leverage. This risk is magnified by increasingly-ineffective governance, as well as obscured by the use of put-like liabilities and poor accounting practices. It threatens fiscal solvency and financial stability.

Here's a hypothetical sketch of how dominoes can fall. This is an illustration of one of many possibilities, not a specific prediction.

> The government barely meets the deadline for raising the debt limit. However, there is surprise glitch with the Fed's antiquated Treasury auction platform. The auction delay causes a "technical" default in which Treasury fails to make payments on the national debt. All major credit agencies downgrade the U.S. rating by a notch. Savy depositors begin to question the health of their banks' assets and the availibility of FDIC insurance. They know that the Liquidity Coverage Ratio regulation causes banks to hold a large proportion of their assets in Treasuries and reserves.[[4]](#note4)<a name="back4"></a> Banks begin to experience runs.
> 
> Banks attempt meet deposit redemptions by selling and repoing Treasuries in an illiquid market, but refuse to use the discount window due to stigma. Fed funds and secured-funding rates spike. Seeing a fire sale, the Fed rushes in to act as a buyer and lender of last report. They buy up trillions in Treasuries (including the technically-defaulted securities), conduct repos with aggregate operational limits over a trillion dollars, and start outright purchases of U.S. stocks for good measure. 
> 
> The Fed fixes their software glitch and begins auctions. Treasury must now quickly increase issuance to be able to backstop the FDIC, in addition to raising funds to meet the backlog of federal obligations. The primary dealers cannot fund this amount of flow; both domestic and foreign demand is insufficient at the Fed's zero interest rate peg. The Fed cannot purchase the securities directly due to *Federal Reserve Act* prohibitions. This financial dysfunction begins to bleed into the economy: nominal interest rates and inflation must rise, credit conditions tighten, and GDP sharply contracts.

In the end, we have the cautionary tale of AIG, Bear, Lehman, and many others as applied to government: large, obscure, off-balance-sheet leverage looks fine until a big enough shock hits. The U.S. bailed out some of those firms, but who will bail out the United States? 

___

<a name="note1"></a> [[1]](#back1) Freddie Mac, "Single Family Loan-Level Dataset". Retrieved from <http://www.freddiemac.com/research/datasets/sf_loanlevel_dataset.page>, September 12, 2020.

<a name="note2"></a> [[2]](#back2) Jonathan D. Rose (Board of Governors), "Old-Fashioned Deposit Runs", as published in 2015. Retrieved from <https://www.federalreserve.gov/econresdata/feds/2015/files/2015111pap.pdf>, September 12, 2020.

<a name="note3"></a> [[3]](#back3) Douglas W. Diamond, Philip H. Dybvig, "Bank Runs, Deposit Insurance, and Liquidity," as republished in 2000. Retrieved from <http://minneapolisfed.org/research/QR/QR2412.pdf>, September 12, 2020.

<a name="note4"></a> [[4]](#back4) Federal Deposit Insurance Corporation, "FDIC Law, Regulations, Related Acts: 2000 - Rules and Regulations; Part 329--Liquidity Risk and Measurement Standards". Retrived from <https://www.fdic.gov/regulations/laws/rules/2000-5300.html>, September 12, 2020.

 ___

&copy; 2020 Christopher Russo. All rights reserved.