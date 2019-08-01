# WorldCover Assignment

Notes:

Most of the issues encountered include seeing repeated variables (for example ‘status’) with the same label in multiple datasets, leading to data cleaning work in order to be able to merge successfully and interpret these variables.  Also, not all variables were documented in the instructions (such as ‘created_at,’ and the notion of the community_payouts table being linked to customer level data at the community level required further clarification.  Other data issues arose when trying to use the ‘farm_size’ variable (most of the data was unusable due to incorrect coding) and large numbers of nulls in the ‘has_mobile_money’ variable, making it also unusable.  For similar reasons of too many nulls, the ‘date_planted’ and ‘date_priced’ variables could not be used.  

In terms of process, fuzzy matching could have been used for connecting district names to the poverty and shapefiles, as this was a particularly time-consuming part of the exercise.  I also did not investigate the meanings of the ‘literacy’ variable, otherwise this could have been ranked and made more meaningful.

With more time and data, it would be great to be able to use machine learning techniques for feature selection, in order to create a model that shows the influence of particular variable on renewal rates.  Climatic data could be brought in, in order to determine the influence of particular climate events on payout rates and renewals (the assumption for this assignment being that droughts trigger payouts), as well as historical climate conditions in the various districts.  Also, historic farming data for the various districts could be used to determine whether customers might be at a disadvantage due to larger farms in the area.

The ‘ussd_created’ variable was not used in this analysis, but it could potentially present more evidence of technology influencing renewal rates.  It would have also been interesting to do a deeper dive on how average premiums themselves influence the size of payouts and renewal rates.  A deeper analysis of various crops grown could also prove interesting, particularly in determining whether some crops are deemed more risky and require higher premiums.  The policy ‘status’ variable could have also been another interesting avenue to explore for a more granular understanding of policies at data creation.


