# Azerbaijan

The Republic of Azerbaijan is a country lies in the crossroads of Eastern Europe and Western Asia. In this project, this country will be described in following aspects: **political subdivisions** and **population distribution**. In addition, two administrative subdivisions--**_Lankaran District_** and **_Lankaran City_** will be examined in **population distribution**, **distributions of human settlements**, and its relation to **road networks** and **healthcare facilities**.

## Political Subdivisons

Azerbaijan has **10 _first level administrative subdivisons_ (adm1)** and **79 _second level administrative subdivisons_ (adm2)**, and the subdivsions **_Lankaran District_** and **_Lankaran City_** are located in the Southeast Corner of _Lankaran_ (adm1), which also lies in the Southeast of the country, on the West coast of Caspian Sea and bordering Iran, as is shown in the following plots:

![](Aze_Subdiv.png)

###### (Note that in this plot and following desription the adm2 **_Lankaran District_** will be simplified as **_Lankaran_**.)

It is worth mentioning that **_Lankaran_** consists of 2 parts, with penisulas and islands in the East, whose boundary is incorporated into the the adm2 boundary, and **_Lankaran City_** locates in the trapzoidal "gulf" on the Eastern boundary in the Southern part:

![](Aze_Lankaran_Topo.png)

In general, despite the simplified jagged coastline, the administrative subdivisons of Azerbaijan are normally distributed, except for the _Nakhchivan Autonomous Republic of Azerbaijan_ (_Nakhchivan_ in the plot), which is isolated from all other adm1s due historical conflicts between Azerbaijan and Armenia.

## Population Distribution (Azerbaijan)

### Population and Modeling

According to data from _Humanitarian Data Exchange_ (HDX), the total population of Azerbaijan in 2019 is **10,115,498** (10 million). And population distribution on adm2 level is presented in the following plot:

![](Aze_Pop19_Adm201.png)

The 3-dimensional versions of the plot:

![](Aze_Pop19_3D01.png)

![](Aze_Pop19_3D02.png)

The population comparison on adm1 level and the the share of population of adm2s within each adm1:

![](Aze_Pop19_Adm202.png)

Based on these plots it can be observed that the population in almost all adm2s are rather similar except for in adm1 _Absheron_. There, the population is exceptionally larger and among the four adm2s in the adm1, Baku City--the Capital--has much larger population than any other amd2s. It is reasonable that the capital is the most economically developed area in the country and thus has the largest population, and the large total population in surrounding adm2s could be explained by satellite cities with provide housing urban populations, and the influence and expansion of the urban area and economies in the capital.

All in all, the population distribution of Azerbaijan follows the general trend that populations concentrate in major cities (especially the capital), and spread thin in the vast rural areas.

To further investigate how population distribution is affected by various conditions, a linear model is used and inputs include vegetation cover, urban cover, topograph, water body, slope, **nighttime light** (NTL), and so on. The regression line and confidence interval are shown as follow:

![](Aze_Crltn_Fttd-Rsdl.png)



### Density, Nighttime Lights, and Correlations

Based on the following plots, **density** seems to more or less follow a positive correlation with **population** on the **adm1 level**, that larger popluation seems to indicate higher density:

![](Aze_Pp19&Den_Adm1.png)

However, on the **adm2 level**, the correlation between **density** and **population** seems different:

![](Aze_BrPlt_LgPp19-Dnsty.png)

As can be seen in the overlay of the _histogram_ and the _probability density function_ (pdf) of **density** and the **logarithm of population** (in which case makes the plot more interpretable), the density reaches its maximum long before the log(pop19) does. Such outcome could be caused be the large areas of populous adm2s (such as _Baku City_) or limited areas of the adm2s result in high density with moderate population. Either way, it can be concluded that Azerbaijan shows various patterns of relationship between population and density.

In addition, the correlation between **NTL** and **population** also provides useful information:

![](Aze_BrPlt_NTL-Dnsty.png)

Similarly, **logarithm of population** is used to provide sonsistency and interpratability, and the similar shape of this overlay suggests the positive correlation between **density** and **NTL**. Besideds, this overlay also further confirms the conclusion drawn from the former overlay, that populous adm2s might be generally large, while some adm2s covering smaller areas might produce very high density.





















