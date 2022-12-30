# Detecting fraud on credict card transactions

This project including script and powebi was present as a conclusion project for "Machine Learning Project" a subject of "Data Science and Machine Learning" course at PUC-Campinas University (December 2022).

The dataset used can be found on <https://www.kaggle.com/datasets/dhanushnarayananr/credit-card-fraud>. 

Once scripts and powerbi was present to Portuguese speakers, the script's first two cells explain and translate to Portuguese the following information: 

Feature Explanation:

distancefromhome - the distance from home where the transaction happened. <br>
distancefromlast_transaction - the distance from last transaction happened. <br>
ratiotomedianpurchaseprice - Ratio of purchased price transaction to median purchase price. <br>
repeat_retailer - Is the transaction happened from same retailer. <br>
used_chip - Is the transaction through chip (credit card). <br>
usedpinnumber - Is the transaction happened by using PIN number. <br>
online_order - Is the transaction an online order. <br>
fraud - Is the transaction fraudulent. <br>

The original version did not distinguish between used_chip or not. It was definetely a mistake! Here I corrected it!!! So we only work with credict card data.
