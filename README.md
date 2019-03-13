# Law_Order
Law &amp; Order Natural Language Processing

Law and Order was one of the longest running shows on television, with 20 seasons totaling 456 episodes. The show filmed on-location in New York at a time when it was more common to represent the city from a distant soundstage in Los Angeles. As a result, the show serves as a document of the real-life texture of New York urbanism in a way that shows like Friends or Seinfeld do not. Law & Order premiered in 1990 at a time when the city grappled with rampant violence. That year, 2,245 people were murdered. By the time the show concluded its run 20 years later, New York had become the safest big city in America. This project uses Natural Language Processing (NLP) to analyze Law and Order scripts to examine how the show changed over time to reflect a radically safer New York City. 

Law & Order Episode Scripts:
https://www.springfieldspringfield.co.uk/episode_scripts.php?tv-show=law-and-order-1990 

One of the challenges in topic-modeling Law & Order scripts with NLP was related to the long tenure of the show: there were so many long-running casts that the initial topic modeling simply classified into clusters of characters. The first step was to eliminate character names from the script corpus. In additional, common geographical terms from New York, New Jersey and Connecticut also generated strong topic clusters, so they were also removed. Common surnames and given names were also problemmatic, so they were also excluded.

Stopword Sources: 

Law & Order Characters: 
https://en.wikipedia.org/wiki/List_of_Law_%26_Order_characters

New York Geography: 
https://en.wikipedia.org/wiki/List_of_towns_in_New_York_(state)

New Jersey Geography: 
https://en.wikipedia.org/wiki/List_of_municipalities_in_New_Jersey

Connecticut Geography: 
https://en.wikipedia.org/wiki/List_of_towns_in_Connecticut

Common Surnames:
https://en.wikipedia.org/wiki/List_of_most_common_surnames_in_North_America#United_States_(American) 

Common Given Names:
http://www.cs.cmu.edu/afs/cs/Web/Groups/AI/areas/nlp/corpora/names/0.html

Using TFIDF word vectors and NMF modeling, I clustered the Law & Order episodes into the 16 topics, shown in relative rates over each of the 20 seasons. Over time, episodes dealing with drugs/gangs/robbery were always present, while financial and organized crime decreased over time. Sexual assault topics also decreased over time, however that is likely due to the premiere of Law & Order: Special Victims Unit in 1999. Topics related to political corruption, the military, and bombing/terrorism increased over time. 

View the complete project at https://www.dnlhui.com/law-and-order 
