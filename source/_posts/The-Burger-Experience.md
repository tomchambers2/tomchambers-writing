title: The Burger Experience
date: 2016-04-03 11:00:07
tags:
---
I was in a pub once several years ago. From memory it was the [Royal Albert](http://royalalbertpub.com/). I was with a couple of friends, entirely sober as I didn’t drink at that point, and enjoying the atmosphere. It was dark, there was loud thumping music playing and in general it was difficult to interact with the people around me. So I descended into a solipsistic world until my burger arrived. When I did, the hypnotic trance I’d been led to an enhanced visceral experience. It is my foremost burger memory.

![](/images/burger-experience/burger-2.jpg)

## The experiment

So I resolved to recreate this. I wanted this happy accident to become a reproducible experience that I could create for others. My hypothesis was that by the application of a set of environmental parameters I could drown out the distractions of the environment and one’s own mind. Thus entering a state where flavour is king.

The music, darkness and burger were obvious points. I added a strobe light, fog machine and projected videos to the mix. The idea was to dislocate the participant as much as possible from the actual room they were in so that the only thing left was them and the burger.

![](/images/burger-experience/experiment-setup-1.jpg)

Every hypothesis needs trials. First to throw their hat in the ring was my girlfriend Eleanor. I set up an installation in my living room with the projector on the ceiling and the strobe light and fog machine facing towards the participant on the sofa.

## Making the burgers

For the burgers themselves, I did a lot of testing, finding the best buns, meat, cooking methods etc. A lot of this information came from [Serious Eat's](http://seriouseats.com) [Kenji Lopez-Alt](http://www.seriouseats.com/user/profile/Goodeaterkenji) and his [articles on burgers](http://www.seriouseats.com/search?term=burger). A lot of good stuff, however I found the (expensive!) [blue label burger blend](http://www.seriouseats.com/recipes/2009/10/the-blue-label-burger-blend-recipe.html) to be not particularly special. Mincing your own meat, probably chuck from the butcher, is miles better than pre ground, but various blends don't add a whole lot.

![](/images/burger-experience/types-of-meat.jpg)

## Automation

Doing the cooking while trying to set up lights, a smoke machine and making sure the music and video don’t run out was a bit of a challenge. Fortunately this is pretty much all automatable with node.js. The video can be controlled via chromecast using this package (https://github.com/mafintosh/chromecasts). Audio could be done that way as well, but I have an Apple Airplay compatible speaker, so I can make use of these instead: [airplay server](https://github.com/watson/airplay-server) or [trampoline](https://www.npmjs.com/package/trampoline). The strobe light can be activated with an (Orvibo S20 wi-fi plug)[http://www.amazon.co.uk/Andoer-Wireless-Control-Appliance-Automation/dp/B00PVTCHXS] and then turned on and off using this [node-orvibo](https://www.npmjs.com/package/node-orvibo). The fog machine is a pain, it requires you to heat it up and then press a button to release when ready. That would need taking apart and triggering perhaps with an (arduino hooked up to the control system)[http://www.instructables.com/id/Motion-Triggered-Fog-Machine/], but not a big task if this was a proper installation.

![](/images/burger-experience/experiment-setup-1.jpg)

## Round 1

{% youtube dvoksE3hxXM %}
*Strobe lights are hard to film...*

I made a big initial faux pas by putting cheese on Eleanor’s burger, who is lactose intolerant. I managed to remedy this however and the burger went down a treat. Though chicken burger would have been her preference.

Overall it was an interesting experience, if also ridiculous. Immersion was rated at a 6 or 7. The darkness and music helped (as in the pub experience) but the strobe light was a bit intense.

![](/images/burger-experience/burger-1.png)

I made the mistake of having the strobe light face right at the participant. A strobe light works best when it captures movement and creates that funny juddery effect. If it’s in your eyes it just blinds you repeatedly.

The projections were on the ceiling in this iteration. I thought the participant would lean back and take them in ignoring what was in front of them. The problem is that it’s impossible to eat like this. So it was pretty much ignored in favour of avoiding getting ketchup all over you.

I tried it again with my friend Theo. I didn’t change much this time, and again as he arrived I provided the sensory deprivators (blindfold and earplugs) as I raced about trying to get everything ready. I became aware that this setup was not as efficient as it could have been, as Theo loudly proclaimed his boredom.

## Round 1 - Second participant

Theo described the music (a short loop created with [Figure](https://itunes.apple.com/gb/app/figure/id511269223?mt=8)) as ‘depressing’ and the [trippy visuals](https://www.youtube.com/watch?v=f1kGF0SgOaA) rather than being hypnotising as I’d hoped were distracting to someone interested in the making of generative art. The burger got a pretty good review however.

What these experiments showed me was that I had misjudged the heart of the experience. When I was sitting in that pub, I was deeply relaxed and comfortable. I was allowing myself to sink into the atmosphere. What I’d tried to recreate was something jarring and bizarre, in the hope that that would be overwhelming enough to blot out mundane thoughts. But that’s actually quite unpleasant and it doesn’t really help anything.

## Round 2

{% youtube gsXOU1FBtyc %}

So I tried again. I adjusted the parameters a bit to accommodate what I learned in the initial experiment. Don’t blind people, let them look the same direction as they’re eating in. And the main change in direction was to make the environment hypnotic, to allow the participant to descend into comfort.

The second round was a little bit better. This time I chose music I knew Eleanor would find satisfying (Kraftwerk) and a series of youtube videos called ['Oddly Satisfying'](https://www.youtube.com/playlist?list=PLOngNyNi4JM80tLLw2dgjNhYp_KDgFKca). She reported that this was hypnotising and the strobe light and fog added to this experience in their slightly more muted outputs. The problem with doing this in a small space is that it’s difficult to make the fog atmospheric without having it interfere with the taste and smell of the burger. The burger itself she said was nice but a bit greasy, which reminds me of the need to make the food itself the absolute focus.

![](/images/burger-experience/unpleasant-smoke.png)

## What I thought

I joined in with this one myself. It’s difficult to really get the full experience as the organiser/experimenter as I was making mental notes and checking everything was still working ok - all the things I was trying to get my participants to forget about. Even so I thought it was still partially successful. The biggest flaw being the room itself which was far too mundane, the aspect I tried to correct by having the participant look up at the ceiling. The biggest question I had, which also came up for Eleanor, was ‘if one is successfully overwhelmed, does that add to the burger? Or does the burger add to being overwhelmed? Are both desirable?’.

Overall I think I’d consider the project a success. I learned a key point that being pleasantly overwhelmed, not spooked out that created the experience. Having done these trials I’d like to run this again for a wider audience. A lot of the elements are right. The biggest change would be putting the participant in a properly dark room with a larger projection, surround sound and perhaps a choice of burger type (beef, chicken, fish, veggie). A living room is just too ordinary for this project.