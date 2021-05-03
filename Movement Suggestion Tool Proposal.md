# Movement Suggetion Tool Proposal
## Introduction
When we decide to move to another city, many people, including me, have a similar concern that whether the new place I choose is suitale for me or not. Will I feel comfortable
after I move there? For example, around my old apartment, there are several markets I can choose from, like Whole food, Target, Trader-joe. There is a park near my house, so I can 
take a walk through the park to enjoy myself, and on its way, I would buy a coffee or a bubble tea and etc. What if my new place doesn't have a park nearby, or drink shop, or I need 
to drive at least 30mins to the market just to get some mushrooms. Now, my tool can help here. The tool will take the name of your neighborhood where you live right now and the city 
you want to move to, then give you some recommendations that you are more likely satisfied with. 

## Clarify Problems
1. Get the coordinates of your old house and the city you want to move to.
2. Identify the arributes of your old house.
3. Cluster the neighborhoods of the future city into several clusters.
4. Match your old house into one of those cluster.
5. Give you recommendations which are all the neighborhoods in the cluster in step 4.

## Solution
1. Geopy to get the coordinates of places.
2. For now we only use the venue attributes that can be obtained by foursquare
3. Use K mean clustering method
4. Use KNN or other algorithm like logistic regression, decision tree to classfy your house into one cluster.
5. Make recommendation.

## Further scopes
This project for now only take the attributes that I have in hand into consideration, in the future exploration, we can add the weather condition, traffic, crime rate, house price
in to our attributes if data are available
