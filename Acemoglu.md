<script type="text/javascript" src=js/latexit.js></script>
# The colonial Origins of Comparative Development: An Empirical Investigation 

******************************************************************* 
*A summary of the paper by Daron Acemoglu, Simon Johnson, and James A. Robinson*

******************************************************************* 

 

## Introduction


Is there a causal relationship between the quality of institutions and a country's GDP or is the renowned correlation between the two due to the simple fact that only rich countries seem to be able to afford good institutional structures?


Three premises:

1. Different types of colonization policies yielded different types of institutions: on the one hand  *extractive colonies* were exclusively exploited for their precious resources and their occupation did not resulted in extended development of institutions and protection of property rights, on the other hand *Neo-Europes* were regions, which Europeans colonized with a long-term perspective of settlement, i.e. replicating European institutions, safeguarding the private property and imposing strong checks on government power;

2. More favorable environments brought to settlement, while regions where settlement was less feasible were only exploited;

3. Even after gaining independence, colonial states survived with their institutions.

Hence, Acemoglu et al. refers to the mortality rates expected by the first colonists as the instrument emplyoed in the process of confirming the causal relationship between the quality of a countries institution and its economic performance (in terms of GDP).
To determine the variable *current institutions* the authors used the protection against risk of expropriation index from [Political Risk Services](http://www.prsgroup.com/about-us/our-two-methodologies/prs). 

#### First-stage

When regressing it on the colonists'  mortality rates between the XVII and XIX century they obtain a strong first stage, meaning that there is a significantly strong correlation between the two variables (taken as logs). In particular, the pattern in the relationship between the two seem to be following the path theorised by Acemoglu, Johnson and Robinson:

| N. | Correlation |
| --- | ----------- |  
| 1. | `potential settler mortality rates` major determinant in `settlements`<sup id="a1">[[1]](#f1)</sup> |
| 2. | `settlements` major determinant in `institutions in 1900`|
| 3. | `institutions in 1900` major determinant in `institutions today`|



#### Exclusion Restriction

It is fairly straightforward to demonstrate that the colonists expected mortality rate between the seventeenth and nineteenth century (our instrument) are in no way directly related to nowadays performance in each specific country. Actually, the only concern that might arise relates to current diseases: in such case the instrument's effect on GDP might be a mere reflection of the disease environment and not a consequence of the country's quality of institutions. However, it has been shown that the colonists' mortality rates were maily due to their lack of immunities against diseases such as malaria and yellow fever, immunities that had been developed by the indigenous population over the centuries. It is therefore unlikely that such diseases fullfil a central role in causing some former colonies to be extremely poor. Hence,  
> "The advantage of our approach is that conditional on the variables that we already control for, settler mortality more than 100 years ago should have no effect on output today, other than through its effect on institutions."                                                                                           
> _Acemoglu et al., 2001_

<span lang="latex"> log y_{i} = \mu + \alpha R_{i} + __X__^{'} _{i} + \epsilon_{i} </span>

<a id="f1">[1]</a>: The Pilgrim Fathers decided to emigrate to the U.S. instead of Guyana because of their awareness about mortality rates in the latter country. [↩] (#a1)

                                     
