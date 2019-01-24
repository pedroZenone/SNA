# Social Network Analysis

In this project the main idea was to undestand an influencer. Which is her/his capabilities to broadcast messages and the engagement and persuation that it has with others.

For this case, I scraped millions of tweets from twitter looking at the mentions and comments to the influencers and the friends of his friends (radius 2) and generate the ego network. With this, I cut bounds with low engagement in order to get a real network of trust.



Finally, I measured centrality so as to understand which were principal authors, those bottleneck users, effective diameter (without redundancies) and interpretable clusters using infomap.

With all this metrics I was able to advise communities that the influencer can persuade (it's stength and weight of the connection), which are secondary users that will centralize information and how many redundancies it has.
