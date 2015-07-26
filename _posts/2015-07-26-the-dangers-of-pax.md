---
layout: default
title: Dangers of a Pax Technica
subtitle: The Other Side of the Coin
date: 2015-07-26
author: Travis Scholten
---

[Previously]({% post_url 2015-07-15-pax-technica %}), I had written about a book on the subject of the "Pax Technica", the idea that we are entering a new period of global statiblity brought about by the Internet of Things (IoT). In particular, the data provided by the IoT will inform policy making and personal decisions, be it addressing questions such as "Where do we need to increase childhoold literacy?" to "Where are the best school districts around me?". The implicit assumption of this Pax is that as we gain more information about the world around us, we will put that information to good use.

Recently the _downsides_ of the pax have been on my mind. Similar to the skepticism of Ian Malcom in "Jurassic Park" regarding the feasibility of an amusement part with 65 million year old attractions, the negative consequences of a "data-driven society" need to be taken into consideration as data proliferates in our world.

#Integration - Friend and Foe#
One major danger of the pax is its strength - the increasing integration of all humans across different countries, connected by the Internet and social media. Integration can be a very positive force as it helps root out prejudice and bigotry. In an integrated society, you have no reason not to ignore the "other side", to see how they live, to understand their struggles, etc.

On a human level, integration is useful. On a technological level, however, integration is complicated. How do I mean that? Consider that the IoT involves millions, probably billions, of sensors on everyday things - the roads, cars, busses, industrial equipment, your doorknob, your windows, etc. If all of those devices are to share data, communicate, and possibly make decisions based on that data, then they all must speak some common set of languages. Such languages are commonly referred to as _standards_.

Unforunately, a proliferation of standards all but ensures a handful of powerful and well-placed companies maintain a monopoly over the market. Will it be possible to use an Android phone to access Apple's [HomeKit](https://developer.apple.com/homekit/)? Will I have to have a Gmail account to use a Nest thermostat? Sometimes companies agree to develop shared standards, but that may not always be the case. 

Further, all this integration leads naturally to the question of failure mechanisms. The Internet itself was designed as a way to prevent a single point of failure causing a cascade of defaults and interruptions in the system of command and control for the US military. The protocols in place for how data is transmitted across the Internet are suppose to help ensure survivability of the network in the event of multiple failures.

In this sense, one might surmise that increasing integration in the Pax Technica could also help prevent cascading failures in human society and economy. However, any integrated system can exhibit complex failure modes, not all of which are obvious _a priori_. Further, without an explicit design philosophy which takes this problem into account, it becomes increasingly likely that such failure mechanisms will naturally arise in the process of building a complicated system. (To quote from the [Zen of Python](https://www.python.org/dev/peps/pep-0020/), it is important to remember that "Complex is better than complicated.". The IoT can be complex, but manageable, if we think about how to prevent critical dependencies from failing simultaneously, or ensuring cascading failures do not create such a critical dependency.)

These sorts of dangers all seem relatively abstract and removed from our day-to-day lives. Are there any dangers which affect us personally? Absolutely. As mentioned, the Pax requires data. Who provides it? We do. In the course of our daily existence, we produce lots of data - how we spend our time, how productive we are, what we work on, when we shop, what we eat, how fast we drive, the list goes on and on. As it becomes easier to collect and store that kind of data, there will be a market incentive to do so to help companies gain a competitive advantage. 

That data represents some of the more intimate aspects of our lives. Do we really want that data shared with businesses or governments? If we do, who owns it? How do we ensure our rights are respected? What rights do we even have in a digital age when everything about us can be collected and analyzed? What does it mean for us to have a private life? These sorts of questions will have to be answered by citizens, politicians, and governments or else the pax will not last very long.

Similarly, just because this data can be collected does not necessarily mean it should. For instance, a Nest thermostat uses sensors to detect if anyone is in the house and adjusts the temperature accordingly. A nice feature to help minimize heating and cooling costs, but in order to do, we have to share information such as "I am not home right now".

Finally, we should be wary of the kinds of inferences that may be made using the prolific amount of data available to us. As the saying goes, "Numbers never lie, but liars use numbers." With huge quantities of data at their fingertips, ideologues, regardless of stripe or persuasion, can find figures, tables, and graphics to support their arguments, no matter how outlandish they may appear. One of the great success stories in science is the recognition that data is agnostic as to what it means. What you conclude using that data says a lot about you. We will need to be ever-vigilant in reminding people of this point. Otherwise we may descend into a series of tit-for-tat arguments in which neither side really listens to the other, and both "have the numbers" to support their claims.


#Conclusions#
In sum, while the Pax Technica could bring about a new period of global stability built upon the notions of openness, data, and transparency, there is reason to be concerned. Some ways the increasing integration of the pax could be harmful include:

* Domination of the marketplace by a few companies who write standards for protocol and communication on the Internet of Things.

* Increasingly complex failure mechanisms, most of which cannot be predicted in advance, and from which recovery may be difficult.

* An increasing lack of privacy in the personal lives of the citizenry as businesses and government seek to extract the maximum amount of information about our day-to-day lives.

* A lack of clear guidance and thinking on whether such integration is necessary. To paraphrase Ian Malcom, are we so preoccupied with new technology and tools that we do not stop to think if we should pursue them?

* Data is agnostic as to what it means. People interpret data through an ideological lens. A proliferation of data makes it easier for ideologues to selectively slice and dice datasets to reach a preconceived conclusion.