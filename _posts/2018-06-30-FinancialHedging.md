---
title: 'Financial Hedging, Corporate Cash Policy, and the Value of Cash'
date: 2021-04-27 00:00:00
description: This paper is a co-publication with Yeqin Zeng and Chao Yin. It has been presented on 2020 FMA Annual Conference, 2020 FMA Annual Conference, and 2020 World Finance Conference. It has been lised on the semi-finalist for the best paper from 2020 FMA Annual Conference. 
featured_image: '/images/hedging1.jpg'
---

## Abtract 

We study the implications of financial hedging for corporate cash policy and the value of cash holdings. Using a web crawler program to collect data on the use of financial derivatives between 1993 and 2016, we find that US public firms with financial hedging programs have smaller cash reserves but a higher value of cash than firms without hedging contracts in place. Our empirical results are robust when controlling for potential endogeneity issues, corporate governance, cash regimes, and alternative measures of cash holdings. Further, we find that financial hedging not only increases the investment sensitivity to internal cash, but also has a positive effect on investment efficiency. The positive effect of financial hedging on the value of cash is more pronounced for firms with more financial constraints, higher information asymmetry, and weaker corporate governance. Collectively, our paper highlights the importance of corporate cash policy as a channel through which financial risk management increases firm value.

## Textual Analysis: Web-scraping from 10-K filings 

To collect corporate financial hedging data, we adopt a textual analysis of firms' annual financial reports and search for the keywords related to the use of financial derivatives. We develop an automatic web crawler program in Python and use the program to evaluate all the 10-K and 10-K405 filings stored in the Electronic Data Gathering, Analysis, and Retrieval system (EDGAR) database.

Based on the keywords commonly used in previous financial hedging literature, we employ three lists of keywords to identify the use of foreign exchange (FX) currency, interest rate (IR) and commodity (COMMD) derivatives. The first list (List A) of keywords identifies the underlying asset. The second list (List B) detects the type of derivatives. The final list (List C) confirms the hedging position with financial hedging related keywords. If a firm mentions at least one word from each of these lists, or their plural forms, within a paragraph in EDGAR filings, we confirm that this firm uses derivative hedging. In many cases, firms disclose their financial hedging positions using more than one sentence. If the annual finanicla report of a firm--year contains at least one word or its plural form from each of these three lists within a paragraph, we classify the firm as a derivatives user in the corresponding year.

Keyword lists:

* List A: “foreign exchange”, “currency”, “interest rate”, “loan rate”, and “commodity”. 
* List B: “forward”, “future”, “option”, “swap”, “spot”, “derivative”, “hedge”, “hedging”, “hedged”, “put”, “call”, “cap”, and “collar”. 
* List C: “contract”, “position”, “instrument”, “agreement”, “obligation”, “transaction”, and “strategy”. 

We require that the distance between any two keywords from the above three lists is less than 25 words within a paragraph. If a window with 25 words is found to contain keywords from the above three lists, it is called a "hit". For each firm--year observation, we count the “hit” frequency for each type of financial derivatives and the hedging position. We classify a firm as a derivatives user in the corresponding year if the number of  “hit” is positive, and a non-user otherwise. To enhance the accuracy of our identification, we drop a “hit” if the paragraph contains false-positive terms such as “in the future”, “forward-looking”, “not material”, “insignificant”, “do not/don't use”, “do not/don't enter”, “do not/don't cover”, or their past tense forms. 

***Suggested citation: Sun, Wenyi and Yin, Chao and Zeng, Yeqin, Financial Hedging, Corporate Cash Policy, and the Value of Cash (April 10, 2020). British Journal of Management, forthcoming, Available at SSRN: https://ssrn.com/abstract=3572747 or http://dx.doi.org/10.2139/ssrn.3572747.

<a href="http://dx.doi.org/10.2139/ssrn.3572747" class="button button--large">View this paper</a>
