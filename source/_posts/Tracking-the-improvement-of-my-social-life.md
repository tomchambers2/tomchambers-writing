title: Tracking the improvement of my social life
date: 2015-10-23 12:09:52
tags:
---

In the [last post](/2015/10/23/Improving-my-social-life/) I described the means by which I’m going to improve my social life. You can’t change what you don’t measure. So I need some metrics. Here’s a graph (made with [d3](http://d3js.org)) of my current social network. You can click and drag the nodes to ping them about.

{% iframe http://tomchambers2.github.io/social-graph/social-graph.html 500 500 %}

I graded every connection between me and my connections and between my connections from 0-5 and the nodes on the graph arrange themselves with respect to the strength of their connection with other nodes.

0 - have never met
1 - have met, but wouldn’t approach in supermarket
2 - have met, would say hello in the street, but not chat in supermarket
3 - would stop to chat for 5 minutes with person in the supermarket, see at events, no active contact
4 - actively go out together every so often, don't call to chat
5 - comfortable calling, speak weekly, go out regularly

There are some caveats. Originally I’d planned to make various ones for people I’d known over the years, but it turned out to be too hard to remember that far back. The relationships below 3/‘would stop for a 5 minute chat’ are too numerous and nebulous to recall precisely and the effect of adding them makes the labour of determining the connections immense (n^2 - n). At that point whether I do or don’t ‘know’ someone gets too fuzzy to calculate.

I excluded professional contacts, simply because it screwed with the rating. There are some people I talk to a lot but are not high contacts, because it’s all work related.

The graph isn’t that accurate. I spent quite a while trying to configure it so that it would all be precise, but it doesn’t really work like that because the resulting graph is a simulation of forces which depends on the randomised starting points of the nodes. Dave for instance should be closer to me, but because of his strong ties to his subgroup he ends up quite far away. So this kind of visualisation might actually reveal unconsidered impacts of the strengths of relationships.

So this is one useful visualisation of how my life will change over the next 3 months. Of course there are lots more interesting things I’d like to understand. For example, where and what kind of events help me meet new people? What behaviours, like alcohol consumption, lead to a change in the number of new people met and relationships developed? How do initial contacts pan out over time? Do some sources of meeting people lead to more friendships than others? On the micro level, I’d like to understand how well the personalities of myself and others lead to rapport when meeting for the first time.

Here’s a full list of the data I’ll be capturing. In about 3 months I’ll be using this data to make a whole bunch of visualisations and see what insight I can divine into what I can do to grow my network and make more friends, and increase the quality of my social life.

- Social network (evaluated monthly)
    - Number of connections at rank 4 and 5
    - Number of new nodes added to network as a whole
    - Density of network (number of friends that have mutual friends with me)
- Social activity (records kept in calendar)
    - Events attended (invited to/instigated) (location, start time, end time)
    - Records of people met (location, time, source, meeting #)
    - Analysis of call logs, text messages and emails (frequency, time, distribution)
    - Alcohol consumption (units per day)
    - Time spent in different locations (recorded by Moves)
- Romantic activity (evaluated monthly)
    - Number of people asked on dates
    - Number of dates (separated by stage) + success metrics like reply rate
- Social skills (recorded on rolling basis, evaluate at non specific intervals)
    - Qualitative analysis of my own and other’s social behaviour on first meeting - answering the question "what makes for a good conversation between new people?"
    - Qualitative analysis of actions and events in new relationships as they develop - answering the question "how and why does a first meeting evolve into a friendship?"
    - ? - perhaps survey data collected from old and new friends on social abilities