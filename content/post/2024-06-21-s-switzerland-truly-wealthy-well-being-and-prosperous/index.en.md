---
title: "Is Switzerland Truly Wealthy, Well-being, and Prosperous?"
subtitle: "Unraveling the Complexity of  Measuring Wealth and Well-Being in Switzerland"
date: '2024-06-21'
tags: ["GDP", "Macroeconomics", "Measurement", "Statistics", "Switzerland", "Well-being" ]
header-includes:
    <script src="https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
    <script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>
output:
  html_document:
    df_print: kable
    theme: default
    toc: yes
    toc_depth: 4
    toc_float: yes
    fig_width: 9
    fig_height: 6
    out.width : 60%
  pdf_document:
    toc: yes
    toc_depth: '4'
editor_options:
  
  chunk_output_type: console
---



## Introduction

When one enters *Why is Switzerland so rich?* into Google, the results seem endless. A recent documentary by Swiss television is titled *How did the Swiss become so rich?*[^1] while the liberal think tank Avenir Suisse recently pondered, *Where does Switzerland's prosperity originate?*[^2]. Although Switzerland's wealth and prosperity might appear self-evident, determining which indicators truly capture these attributes is a complex task. This complexity often leads to a lack of clarity in the evidence presented by these sources. The indicators utilized can vary greatly and sometimes even suggest that Switzerland isn't as affluent or prosperous as perceived when compared to other countries.

[^1]: <https://www.swissinfo.ch/eng/swiss-made/how-did-the-swiss-become-so-rich/48115940>.

[^2]: <https://www.avenir-suisse.ch/woher-der-schweizer-wohlstand-kommt/>.

Confirming this shadow complexity, this article aims to demonstrate that the inquiry into Swiss wealth and its implicit normative connection to prosperity and well-being is heavily reliant on the metrics employed. Just as with the previous article about unemployment, the analysis of causes is sidestepped by challenging how these normative concepts are defined and measured.

## The historical convention of wealth measurement

The question of what constitutes the wealth of a territory has been central to economic theory since its inception. The mercantilist, physiocrat, and classical[^3] schools focused on wealth to justify the economic power of the sovereign amidst the modern state's emergence[^4].

[^3]: Except for Marx.

[^4]: Valier, J. (2011). Brève histoire de la pensée économique: d'Aristote à nos jours. Flammarion.

However, the development of a dominant and technically advanced measurement system was greatly enhanced by the context of the Second World War[^5]. With the increasing demand for organizing war efforts, establishing national accounts became crucial[^6]. Additionally, the emergence of Keynesian macroeconomics further emphasized the need for a production-oriented measure[^7]. From that point on, wealth and macroeconomic performance began to be progressively measured in terms of Gross Domestic Product (GDP).

[^5]: In the 17th century, mercantilists such as William Petty and Gregory King were the first to measure wealth by estimating national income. However, it wasn't until the Great Depression of the 1930s that this work was significantly expanded. In response to the economic crisis, the U.S. Senate tasked the National Bureau of Economic Research (NBER) with estimating American national income. In 1932, Simon Kuznets' work provided the first estimate of the gross national product (GNP), introducing it as a national statistic. Méda, D., & Jany-Catrice, F. (2022). Faut-il attendre la croissance?. La documentation française.

[^6]: ibidem.

[^7]: ibidem.

## The diversity of GDP measures

In macroeconomics, GDP is basically « the measure of aggregate output »[^8] : it measures the wealth produced by a given territory over a given year using cash flows.

[^8]: Blanchard, O (2020). Macroeconomics, Global edition. 8th edition, Pearson, p.40.

While this basic definition may seem straightforward, the method used to calculate GDP is multifaceted and more complex. Indeed, GDP can be calculated using three approaches: expenditure, income, and production. The most used approach, the expenditure approach, is represented by the following equation (1):

$$
GDP=C+I+G+(X−M)  \quad \text{(1)}
$$ where

-   <font color="black">$C$</font>: Consumption by households
-   <font color="black">$I$</font>: Investment by companies
-   <font color="black">$G$</font>: Government spending
-   <font color="black">$(X−M)$</font>: Net exports, i.e Exports ($X$) minus Imports ($M$)

As you could imagine, however, in an evolving economy, GDP at current prices, in itself is irrelevant. Indeed, « if our goal is to measure production and its change over time we need to eliminate the effect of increasing prices on our measure of GDP »[^9]. In this context, the growth rate is used to evaluate GDP, which is the rate of change of GDP measured in volume, i.e at constant prices.

[^9]: ibidem, p.42.

Another widely used measure is GDP per capita, which shows a country's GDP divided by its total population. This measure is, however, often used not to indicate wealth, but to assess the well-being and standard of living of a geographical area. In order to correct variations in exchange rates and systematic differences in prices across countries, GDP per capita is often adapted using Purchasing Power Parities (PPP)[^10].

[^10]: This involves « revising upwards the GDP of countries where prices are lower than average and reducing it where they are higher ». Halbeisen, P., Müller, M., & Veyrassat, B. (Eds.). (2017). Wirtschaftsgeschichte der Schweiz im 20. Jahrhundert. Schwabe Verlag (Basel), p.98.

## Growth and GDP per capita in a comparative perspective

**Figures 1** and **2** below present the GDP growth rate in PPP and GDP per capita growth rate in PPP for Switzerland, the Euro Zone, the European Union, the United States of America, France, Germany, and Austria from 7 cycles between 1991 to 2022. Coming from the World Bank database, these data were already adjusted at constant 2011 international PPP dollars. However, the GDP growth rate and GDP per capita growth rate were not available for every cycle and were therefore calculated using an arithmetic average of the two followings equations (2) and (3):

$$
Gr_TP=(GDP_TP/GDP_tP)-1 *100  \quad \text{(2)}
$$ where 
- <font color="black">$Gr_TP$</font>: Growth rate at constant 2011 international PPP dollars for year \$T\$. 
- <font color="black">$GDP_TP$</font>: GDP at constant 2011 international PPP dollars for year \$T\$. 
- <font color="black">$GDP_tp$</font>: GDP at constant 2011 international PPP dollars for previous year \$t\$.

$$
Cr_ TP=(C_TP/C_tP)-1 *100  \quad \text{(3)}
$$ where

-   <font color="black">$Cr_TP$</font>: GDP per capita growth rate at constant 2011 international PPP dollars for year \$T\$.
-   <font color="black">$C_TP$</font>: GDP per capita at constant 2011 international PPP dollars for year \$T\$.
-   <font color="black">$C_tp$</font>: GDP per capita at constant 2011 international PPP dollars for previous year \$t\$.

<iframe src="/HTML/Figa.html" width="100%" height="500" frameborder="0">

</iframe>

<iframe src="/HTML/Figb.html" width="100%" height="500" frameborder="0"></iframe>

Two main conclusions could be provided from Figures 1 and 2. First, Switzerland underperformed in most of the cycles. Indeed, if we exclude the 2006-2010 cycle (which is characterized by a Swiss performance) Switzerland's GDP per capita growth rate and overall growth underperformed during the 1991-1995 cycle compared to other geographical entities and was the second worst in the 1996-2000, 2001-2005, and 2021-2022 cycles.

Second, Switzerland has a nuanced performance between 2011-2015. During the 2011-2015 cycle, Switzerland's growth was the second-best performance behind the USA, but its GDP per capita growth rate was lower than that of Germany, the USA, and the EU.

Therefore, in short, there is nothing to suggest that Switzerland is inherently wealthier. This result confirm recent work in economic history, which shows that « the 1990s, growth rates in GDP and GDP per capita were significantly lower than in comparable countries »[^11]. Moreover, according to long series of GDP data, « the high growth rates of the post-war years were not unique to Switzerland, nor was the situation during the long period of growth after the Second World War »[^12].

[^11]: ibidem, p.118.

[^12]: ibidem, p.119.

## Rethinking GDP as an irrelevant measure of well-being

While we have just shown that Switzerland does not appear to be richer from a monetary point of view, it is important to remember that GDP is not just seen as an economic indicator. Since economics is also based on philosophical and normative assumptions[^13], wealth seems to improve a society in economic terms, but also in terms of well-being. In this view, GDP = wealth, and wealth = well-being and prosperity.

[^13]: Keen, S. (2001). Debunking economics: The naked emperor of the social sciences. Zed Books. ; Bréban, L. (2019). Bonheur et richesse: Adam Smith face à l'économie du bonheur. Doctrines et réalité (s) du bonheur.

However, GDP has significant limitations as an indicator of well-being. Increases in GDP per capita do not necessarily translate into increased individual well-being, as demonstrated by Easterlin's paradox[^14]. Additionally, reports like the Meadows report[^15] and the Stiglitz report[^16] and the work of Tobin-Nordhaus[^17] have highlighted GDP's shortcomings, especially regarding environmental externalities.

[^14]: Easterlin, R. A. (1974). Does economic growth improve the human lot? Some empirical evidence. In Nations and households in economic growth (pp. 89-125). Academic press.

[^15]: Meadows, D. H., Meadows, D. L., Randers, J., & Behrens III, W. W. (1972). The limits to growth, Universe Books.

[^16]: Stiglitz, J. E., Sen, A., & Fitoussi, J. P. (2009). Report by the commission on the measurement of economic performance and social progress.

[^17]: Nordhaus, W and Tobin, J. (1972). Is Growth Obsolete?. Economic Research: Retrospect and Prospect, 5.

To address these issues, the Federal Statistical Office of Switzerland (FSO) has been publishing a series of well-being indicators since 2014. These indicators acknowledge that « GDP and NAs provide information on the material economy (income, consumption, savings), but they don't tell the whole story, and there are gaps in their coverage »[^18]. GDP is particularly limited « when it comes to reporting on all aspects of a population's well-being and quality of life »[^19].

[^18]: <https://dievolkswirtschaft.ch/fr/2015/02/comment-les-statisticiens-mesurent-le-bien-etre/>.

[^19]: ibidem.

Let's take an example to illustrate the limitations of GDP as a measure of well-being in the Swiss case. **Figure 3** below shows real GDP per capita and the at-risk-of-poverty rate, calculated by the FSO and transformed, by ourselves, into indices with a 2007 =100 base. If we were to analyze Switzerland alone (without international comparisons, which show that Switzerland is not a high-performing country by nature), we might think that well-being, captured solely by the wealth produced per capita, has improved. However, it is interesting to note that the at-risk-of-poverty rate, which corresponds to the percentage of people at risk of poverty in the total population, albeit more volatile, has also increased. So can we say that well-being and prosperity in Switzerland have increased? Nothing is less certain.

<iframe src="/HTML/Figc.html" width="100%" height="500" frameborder="0"></iframe>


## Moving beyond an anachronistic GDP

If GDP fails to measure well-being, it also fails to take account of voluntary work, social reproduction and the economic, environmental and social damage caused by the production system[^20]. By invisibilising the most recent dynamics of our production system, GDP could therefore be considered an anachronistic measure.

[^20]: For a review of the criticisms of GDP, see Gadrey, J., & Jany-Catrice, F. (2007). Les nouveaux indicateurs de richesse. Paris: La découverte.

Legitimately, we should, therfore, be looking at alternative metrics. One of the most known[^21], the Human Development Index (HDI), which combines GDP per capita, education levels, and life expectancy, offers a broader perspective but still has limitations. As illustrated in **Table 1**, in Switzerland, the increase in life expectancy between 2007 and 2017 does not translate into an equivalent increase in life expectancy in good health. Life expectancy has increased 427% faster than life expectancy in good health for men, and by 185% for women. This discrepancy illustrates the limits of composite indicators in capturing true well-being: reducing it to a small selection of indicators in order to construct a single metric will always reduce our detailed and plural understanding of what well-being really is. As Stiglitz warns, « one couldn't reduce everything to a single number »[^22].

[^21]: For a review of alternative metrics, see ibidem.

[^22]: Stiglitz, J. E. (2009). GDP fetishism. The Economists' Voice, 6(8), p.2.


Table: <span id="tab:table"></span>Table 1:  Healthy life expectancy and Life expectancy in Switzerland (2007-2017)

|Indicator                   |  2007| 2017|      %|
|:---------------------------|-----:|----:|------:|
|M - Healthy life expectancy | 69.39| 69.8|   0.59|
|W - Healthy life expectancy | 70.26| 70.8|   0.77|
|M - Life expectancy         | 79.40| 81.4|   2.52|
|W - Life expectancy         | 84.20| 85.4|   1.43|
|∆M                          |    NA|   NA| 427.12|
|∆W                          |    NA|   NA| 185.71|

## Concluding remarks

In the collective mind, the wealth and quality of life in Switzerland is superior to that of the rest of the world. Unlike this consideration, this article challenges that inherent superiority. Indeed, the analysis of Switzerland's GDP performance over various economic cycles reveals that this country does not consistently outperform its peers.

Furthermore, while traditional economic indicators like GDP growth rate and GDP per capita offer some insights, they fall short in capturing the full picture of well-being and quality of life. Although GDP provides valuable information about production activity, it does not account for factors such as income distribution and environmental changes.

Assessing Switzerland's wealth and prosperity requires, therefore, a multifaceted approach that incorporates social, and environmental dimensions. By embracing a broader range of indicators, policymakers and researchers can gain a more accurate and holistic understanding of well-being, ultimately guiding more effective and inclusive economic policies. Focused solely on the anachronistic measure of growth, Swiss economists could do well to consider other indicators. Otherwise, Switzerland's much-vaunted economic and political success will remain more myth than reality.
