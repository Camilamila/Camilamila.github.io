---
name: Who won the contract? An analysis of bidder networks and collusion in public procurement
tools: [R, Social Network Analysis]
image: https://drive.google.com/uc?export=view&id=1jSDAPH5PeCBaLv1dVxAF5mVI0kNya7HH
description: Capstone project for the Msc in Applied Social Data Science at The London School of Economics with Distinction. 
---

# Who won the contract? An analysis of bidder networks and collusion in public procurement

### Abstract

This research analyses procurement markets as co-bidding networks, in which firms that sell goods and services to the government are linked if they bid together on the same tender, to detect suspicious bidding patterns, potential bid-rigging and collusive structures in public contracting. I argue that groups that have similar bidding patterns and interact frequently in the market are more likely to present collusion markers. The method is applied to public tenders in Paraguay from 2014 to 2018. Using a community detection algorithm based on the co-bidding similarity of firms and the frequency of interactions, suspicious groups were found in 23 of 76 markets studied. I applied collusion screens to each group, based on price differences of tenders won, market shares and the success rate of firms. The groups detected present different patterns of interaction that in some cases do not align with collusion practices, or do it partially. For instance, some of the flagged markets had a high concentration, stable market shares and were captured by members of the suspicious groups. Also, firms can use other strategies to win contracts, such as diving the market according to the geographic location, or bidding under different legal names. The method can be useful to detect anomalous behaviour and filter suspicious cases for further analysis in procurement markets, where no previous data about bid-rigging is available.

***

#### Key findings

* Using an index of the co-bidding similarity of firms, and a community detection algorithm to identify communities that had similar patterns of interaction, I identified 23 groups of firms that presented particular connections in the market that could align with collusive patterns. 

![alt text](https://drive.google.com/uc?export=view&id=1FwzSTZEu_bCoaa1CElEAK-0qH6H9v4I3){:height="300px" width="300px"}

* Applying collusive screens to these flagged communities, I found different suspicious behaviours.  First, some of the markets were captured by firms in the suspicious group, since they participated in most or all of the tenders, had a **high winning rate and a high market share**, that was a result of consistent participation in the market and not of winning a single high value tender.  Moreover, firms can use other strategies to win contracts, such as **dividing the market according to the geographic location, or bidding under different legal names**.  The price cartel screens that fail to detect collusive behaviour, could mean that markets are indeed competitive and communities just reflect firms that interact a lot in the market but do not get a high market share; or, for some markets it could be a result of the few tenders not won by firms outside the cluster, which does not make the comparison very valuable.  Additionally, in some cases, the segmentation was based on the goods procured, which could reflect that for some products firms tend to have more intensive and similar patterns of interaction than others, and the price differences are reflecting differences in the items procured. 


<p class="text-center">
{% include elements/button.html link="https://github.com/Camilamila/Capstone-project" text="See code on Github" %}
</p>
