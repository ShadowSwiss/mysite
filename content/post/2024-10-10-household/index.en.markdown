---
title: "How public finances and corporate power have trapped Swiss households in debt?"
subtitle: "An econometric analysis of the financialization of Swiss households"
date: '2024-10-15'
tags: ["Financialization", "Indebtness", "Econometrics", "Households", "Switzerland", "Public finances" ]
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

While in Switzerland, public debt draws significant attention, there is one type of debt that seems to escape scrutiny: household debt. According to researcher Solène Morvant-Roux, «there is sometimes a sense of indifference towards this issue»[^1]. This lack of concern is particularly troubling given the central role debt plays in Swiss households. In today's era of financialization[^2], household indebtedness and investment have become routine financial practices[^3]. This is evident in **Figure 1** below, which highlights the extent of Swiss household financialization, measured by debt as a percentage of GDP, in comparison to the United States, Germany, France, Austria, and the United Kingdom from 1999 to 2022. Swiss households are significantly more indebted than their international counterparts, with debt levels exceeding 100% of the country's GDP.

<iframe src="/HTML/Fig1.html" width="100%" height="500" frameborder="0">

</iframe>

[^1]: <https://www.blick.ch/fr/news/economie/en-comparaison-aux-autres-pays-du-monde-pourquoi-les-suisses-sont-ils-aussi-endettes-id18842843.html>.

[^2]: While financialization can be defined in various ways, this article focuses on the «increasing dominance of financial actors, markets, practices, measurements, and narratives» at the household level. Aalbers, M. B. (2016). The financialization of housing: A political economy approach. Routledge, p.2.

[^3]: Bobek, A., Mikuš, M., & Sokol, M. (2023). Making sense of the financialization of households: state of the art and beyond. Socio-Economic Review. Online First: 1-26.

Despite this Swiss anomaly, it has attracted surprisingly little political or analytical attention. This oversight is particularly striking given that such high levels of indebtedness contradict the prevailing notion of Switzerland as a land of wealth and prosperity. In fact, household debt is a key factor driving inequality in the country[^4].

[^4]: Morvant-Roux, S., Bertoli, M. A., Clerc, S., Rees, M., & Saiag, H. (2023). Survival debts versus accumulation debts: Financialization and social inequalities in Switzerland. Revue Francaise de Socio-Economie, 30(1), 219-244.

This article aims to explore the underlying correlations that explain the financialization of Swiss households. To do so, it undertakes an econometric analysis, while also considering the political context and historical background behind the variables examined.

## Why household indebtedness is problematic and how could we explain it

In mainstream economic theory, household debt was long perceived as beneficial for the economy[^5]. However, it is increasingly recognized that medium and long-term indebtedness is particularly problematic. Since the 2008 crisis, which saw widespread mortgage defaults trigger one of the most severe economic crises in the history of capitalism, no economist views household debt as risk-free. A recent IMF report even warns of potential dangers: «Growth is slower than it would have been otherwise, and the odds of a financial crisis increase»[^6].

[^5]: In this approach, households are rational and seek to maintain their consumption over time (permanent income hypothesis and life cycle consumption). If the future budget constraint has an effect on their consumption, then households will go into debt and smooth out their consumption. Debt is therefore not negative and results solely from households' future expectations. For a review, see: Karacimen, E. (2013). Dynamics behind the Rise in Household Debt in Advanced Capitalist Countries An Overview. Financialisation, Economy, Society & Sustainable Development (FESSUD) Project Working papers.

[^5]:<https://www.imf.org/en/Blogs/Articles/2017/10/03/rising-household-debt-what-it-means-for-growth-and-stability>.

More specifically, the report notes that «highly indebted households may need to cut back on spending to repay their loans. That's a drag on growth. And as the 2008 crisis demonstrated, a sudden economic shock, such as a decline in home prices, can trigger a spiral of credit defaults that shakes the foundations of the financial system.[^7]»

[^6]: <https://www.imf.org/en/Blogs/Articles/2017/10/03/rising-household-debt-what-it-means-for-growth-and-stability>.
[^7]:ibidem.

Aware of the risks induced by households debt, the literature has devoted considerable attention to its causes. According to a selection of non-exhaustive articles[^8], household debt can be explained by real estate variables (house prices; mortgage credit interest rates), labor variables (unemployment; real wages; income inequality; working age population), public finances (public expenditures; public deficit) and financial asset prices.

[^8]: Karaçimen, E. (2014). Financialization in Turkey: The case of consumer debt. Journal of Balkan and Near Eastern Studies, 16(2), 161-180; Dumitrescu, B. A., Enciu, A., Hândoreanu, C. A., Obreja, C., & Blaga, F. (2022). Macroeconomic determinants of household debt in OECD countries. Sustainability, 14(7), 3977; Romão, A., & Barradas, R. (2024). Macroeconomic determinants of households' indebtedness in Portugal: What really matters in the era of financialisation?. International Journal of Finance & Economics, 29(1), 383-401.

## Econometric analysis

To create our model for the period 1999-2022, we excluded variables linked to property ownership, since 61% of Swiss households are tenants[^9]; and financial asset prices, which decrease the explanation of our model. In order to avoid multicollinearity, we select only one labor independent variable, real wages, which has the advantage to take into account inflation in the model. We then added public spending and public debt as a proportion of GDP as independent variables. The model presented in equation (1) explains 85% of the variance in households debt and performed satisfactorily in multicollinearity tests.

$$
Hd=β0+β1(Rw)+β2(Pe)+β3(Pd)+ϵ  \quad \text{(1)}
$$ where

-   <font color="black">$Hd$</font>: Households debt as % of GDP (Source: IMF)
-   <font color="black">$β0$</font>: Intercept (constant term)
-   <font color="black">$β1(Rw)$</font>: Coefficient for real wages (Source: FSO)
-   <font color="black">$β2(Pe)$</font>: Coefficient for public expenditures (central government, as % of GDP, Source: FFA)
-   <font color="black">$β3(Pd))$</font>: Coefficient for public debt (central government, as % of GDP, Source: IMF)
-   <font color="black">$ϵ$</font>: Error term

**Table 1** below presents the results of our econometric model, showing that each independent variable has statistically significant coefficients. This indicates that all the variables are meaningfully correlated with households debt as a proportion of GDP. To visually represent these findings, **Figure 2** illustrates the correlation diagrams for each independent variable, offering the following key insights:

-   Increasing the public debt reduces households debt. This suggests that public debt is not inherently harmful and, in the Swiss case, may even be beneficial.

-   Rising real wages (i.e., purchasing power) reduces households debt. This implies that improving workers' purchasing power could lower households debt, indicating that debt is often a response to social needs.

-   Higher public expenditures increase households debt. This could mean that increased public spending does not always financially support households, and/or that additional spending is financed through higher revenues extracted directly from households, which can have counterproductive effects.

<iframe src="/HTML/table.html" width="100%" height="400" frameborder="0">

</iframe>

<iframe src="/HTML/Fig2.html" width="100%" height="500" frameborder="0">

</iframe>

While the results for real wages and public debt may seem intuitive, the finding on public spending is more surprising. It is therefore important to examine more closely the links between public expenditures and household debt in Switzerland.

[^9]:https://www.bfs.admin.ch/bfs/fr/home/statistiques/construction-logement/logements/logements-locataires.html 

## Examining the correlation between public expenditures and household debt

**Figure 3** provides an overview of the socio-political sources of Swiss central government revenue as a proportion of GDP from 1990 to 2022. It clearly shows that, like many other countries entering the neoliberal era, Switzerland «shifted a portion of the tax burden from capital owners to the majority of wage earners»[^10]. Indeed, in 1990, the shares of revenue attributed to households and capital[^11] were roughly equivalent as a proportion of GDP. However, from 1994 onwards, following the end of turnover taxation, capital's contribution to the Confederation’s revenues steadily declined, disproportionately affecting households. This suggests that increased public expenditures alone does not alleviate household financial strain if a large portion of that spending is financed by households themselves.

<iframe src="/HTML/Fig3.html" width="100%" height="500" frameborder="0">

</iframe>

Moreover, in Switzerland's historically anti-Keynesian context[^12], with relatively low public spending, the introduction of the debt brake in 2003 has further constrained the government’s ability to provide financial support to households. Although the debt brake can be temporarily relaxed in response to economic conditions, Swiss law generally requires that any increase in public expenditure be matched by a corresponding rise in revenue. This mechanism typically limits public spending or, at best, keeps it fixed in real terms[^13].

**Figure 4** illustrates the variations in public spending on households[^14] in Switzerland and the Eurozone from 1999 to 2022, expressed as a percentage of GDP. One critical point is that, over this period, Swiss public spending on households averaged 15% of GDP, compared to 28% in the Eurozone. Notably, Switzerland has seen a reduction in public spending relative to 1999, except during the two years of the COVID-19 pandemic, in contrast to the trend in the Eurozone. This shows that, while public expenditures is on the rise, it is targeting other areas.

<iframe src="/HTML/Fig4.html" width="100%" height="500" frameborder="0">

</iframe>

This comparison therefore highlights Switzerland's restricted fiscal environment, where limited public spending, combined with the transfer of the tax burden to households and the failure to increase public expenditures on households, has probably exacerbated the problem of household indebtedness.

## Opening: Ideology, overproduction crisis, banking power and financial instability

To sum up, we have demonstrated that the high indebtedness of Swiss households is largely due to limited purchasing power and restrictive public finances. This reveals how socially underdeveloped the Swiss economy is. Employers and corporations wield such significant power that they are able to limit real wages growth, leaving households to turn to debt as a compensatory measure.

The role of public finances, however, is more complex. The stringent control over public debt and, more broadly, the obsession with “balancing” public finances seem detached from economic realities. As we have previously noted, Switzerland has never experienced large-scale public spending[^15], which makes the alarmist discourse around its public finances appear exaggerated. The **Figure 5** below shows Swiss public debt as a proportion of GDP from 1986 to 2022, compared to France, Austria, Germany, the United Kingdom, and the United States. This demonstrates Switzerland’s relatively modest debt levels in an international context. Combined with a favorable economic environment, some economists have even suggested that Switzerland has room to increase deficits, arguing that austerity measures are unnecessary[^16]. Others have pointed out that historically, Swiss public debt has had no adverse effects on growth or interest rates[^17]. 

<iframe src="/HTML/Fig5.html" width="100%" height="500" frameborder="0">

</iframe>

This evidence supports the argument that public debt, and public finance policy more broadly, primarily serve a political purpose[^18]. The aim is to curtail social spending, despite the lack of empirical support for such a policy[^19]. The justification is purely ideological. As economist Olivier Blanchard noted, «it is clear that we can probably tolerate debt levels above 100% in many countries, and it’s not the end of the world»[^20].

However, this ideological stance has tangible consequences. Combined with declining demand due to limited purchasing power, the dominance of corporations forces Swiss households into greater debt. This debt serves a critical economic function: it compensates for overproduction. Supply and demand do not naturally balance out; rather, they are sustained by a banking system that capitalizes on low purchasing power and lack of public spending, often at the expense of household financial stability. In other words, the entire Swiss production system now relies heavily on household credit, which grants the banking sector a central role from which it derives significant profits. Banks, in effect, have assumed the role that the state could have played, which in turn increases the risk of a financial crisis in Switzerland.

There are, however, solutions to this problem. We have shown that increasing wages reduces household indebtedness and possibly reduces the likelihood of a financial crisis in Switzerland. Additionally, increasing public spending targeted at household support, and not financed by households themselves, can also help improve household financial health. To achieve these, we need to overcome the Swiss ideology, rooted in a caricatured version of laissez-faire economics, which selectively applies this doctrine depending on who benefits.

[^10]: Guex, S. (2003). La politique des caisses vides: État, finances publiques et mondialisation. Actes de la recherche en sciences sociales, 146(1), 51-62, p.58.
[^11]: We have compiled the following for capital (in % GDP): stamp and issue duties; customs duties; withholding tax; direct federal tax on legal entities; sales tax and patents and concessions. And for households (in % GDP): Duty on premium receipts and other receipts; direct federal personal income tax; tax on beer, spirits and mineral oils; traffic tax; tax on exemption from compulsory service; value-added tax and co2 tax. 
[^12]:Guex, S. (2012). L’État fédéral et les crises économiques du début du xxe siècle à nos jours: la Suisse, un bastion anti-keynésien. Société suisse d’histoire économique et sociale, 27, 160.
[^13]:For a review, see Desgraz, R. (2023). The less, the better? The Political Economy of the Swiss Debt Brake. Archive Ouverte of the University of Geneva. 
[^14]:We have compiled the following COFOG (Classification of  of the functions of government) together (in % GDP) : Health; Social protection ; Housing and community amenities ; Recreation, culture and religion. 
[^15]:Guex, S. (2012).
[^16]: Tille, C. (2019). Le" fardeau" de la dette publique suisse: Eclairages des recherches scientifiques et pistes pour le futur. Graduate Institute of International and Development Studies Working Paper. 
[^17]:Guex, G., & Guex, S. (2018). Debt, economic growth, and interest rates: an empirical study of the Swiss case, presenting a new long-term dataset: 1894–2014. Swiss Journal of Economics and Statistics, 154, 1-13.
[^18]:Chesnais, F. (2011). Les dettes illégitimes. Quand les banques font main basse sur les politiques publiques. Raisons d'agir.
[^19]:https://dievolkswirtschaft.ch/fr/2019/04/schaltegger-salvi-05-2019fr/. 88% of public finance forecasts since 2003 have turned out to be more pessimistic than reality.   
[^20]:https://www.nytimes.com/2020/08/21/business/economy/national-debt-coronavirus-stimulus.html



