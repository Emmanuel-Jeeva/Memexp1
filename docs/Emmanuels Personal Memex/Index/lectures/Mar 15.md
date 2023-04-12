October 29th, 1969 != 'birth of the internet'




"Most of the current crop of histories of the Internet can be characterized as 'teleologies' or 'Whig history'...as they seek simplistic explanations to draw a line from the ARPANET to the Internet"

-   Russell and Shafer, drawing on Campbell-Kelly and Garcia-Swartz

RUSSELL, A. L., & SCHAFER, V. (2014). In the Shadow of ARPANET and Internet: Louis Pouzin and the Cyclades Network in the 1970s. _Technology and Culture_, _55_(4), 880–907. [http://www.jstor.org/stable/24468474](http://www.jstor.org/stable/24468474)

One network does not an _inter_network make.

Meanwhile, in France...
They wanted bombs to compete with everyone else

![](https://shawngraham.github.io/hist1900/assets/slides/312px-De_Gaulle-OWI_(cropped)-(c).jpg)![](https://shawngraham.github.io/hist1900/assets/slides/320px-M._Louis_POUZIN_2013.jpg)




CYCLADES - 1971 - demo'd in 1973 - fully operational 1976

![](https://shawngraham.github.io/hist1900/assets/slides/cyclades.png)"One should retain the image [of the Cyclades islands]; the processing centers are still today islands isolated in the middle of an ocean of data, which overhelms our civilization. Now, thanks to the networks, these islands will be able to connect and thus contribute to a wide circle of information exchanges which will shape the future development of our society."
-   project led by Louis Pouzin
-   coins the term 'datagram' ; data + telegram
    -   gets the hosts to do the error correction, not the routers;
    -   makes the hosts responsible for delivery of the data on a 'best-effort' means (ie timeouts)
    -   the routers ensure transparency end-to-end
    -   this greatly simplifies interconnectivity
-   explicitly designed from the _outset_ to connect different networks together (unlike ARPANET)

## ALOHANET

-   University of Hawaii - main campus near Honolulu, other campuses on the main island and on Oahu, Kauai, Maui, and Hawaii - radius of about 300 km
-   1968 department of Electrical Engineering begin planning a way to broadcast data over radio, rather than wire
-   to permit sharing of the main campus computer
-   technical issues solved and goes into use June 1971


## SATNET

-   proposal from Larry Roberts in 1970 to connect ARPANET to Davis' National Physical Laboratory network
-   eventually comes to fruition by 1973, but to University College London instead

![](http://ed-thelen.org/comp-hist/CORE-3-1-SRI-cover.jpg)

## PRNET

-   packet radio network
-   Inspired by alohanet, but hey, let's make things _mobile_ too!
-   develops a radio receiver/broadcaster that can use packets - basically, a mobile router
-   of great interest to the military side of things

## Elsewhere in Europe:

## European Informatics Network

-   share resources
-   promote computer science
-   testbed for techniques
-   proposed in 1971, work begins 1973, 10 countries wired up by 1976

**There are others.**

Finding a 'history of' 'internetworking' 'country' would be a good thing to add to your memex.




Some were commercial

-   Telenet

Some of them aren't even official.

![](https://shawngraham.github.io/hist1900/assets/slides/gorin.png)
[[Pam Hardt]] drops out of Comp sci to protest Vietnam war
![](https://shawngraham.github.io/hist1900/assets/slides/Community-Memory-c-1974_20170207_180047.jpg)
Start of underground telephone
First social network
**So how do you internetwork these things?**


Elizabeth 'Jake' Feinler

Eventually develops a 'handbook' (both physical, and digital database)

-   resources at evey host
-   responsible technical administrators
-   1000 pages, record of every node, insitution, and person who together made 'ARPANET'
-   goes on to create a directory, ever person on the arpanet and how to find them
-   registers all new hosts, all new documentation, all new how-tos


-   Ok. So - 1969 - 1973 ish - a period of ferment
-   other networks starting up, other ways of implementing similar ideas
-   in a context of national competition and paranoia
-   including non-government operations
-   and ways of being mediated through these networks
-   and ways of being augmented by computers and the networks.

ARPANET project oversight:

Bolt, Beranek and Newman: IMP hardware, software, operations

UCLA- analysis (how well is the network working?)

Network Analysis Corporation - topology (how well is the network connected?)

SRI - network information center

Network Working Group - host protocols

And, in the early 1970s, wasn't really _working_ beyond the mere technical sense.

## ARPANET project oversight:

Bolt, Beranek and Newman: IMP hardware, software, operations

UCLA- analysis (how well is the network working?)

Network Analysis Corporation - topology (how well is the network connected?)

SRI - network information center

Network Working Group - host protocols

And, in the early 1970s, wasn't really _working_ beyond the mere technical sense.

First International Conference on Computer Communications in Washington 1972

-   lots of things being demo'd, including
    -   air traffic simulation,
    -   real time conferencing
    -   computerized chess player
    -   Joseph Weizenbaum's [ELIZA](https://www.masswerk.at/elizabot/) program
-   they set up a terminal / host system at the conference demonstrating ARPANET

Digression. This photo supposedly from the conference:

![](https://shawngraham.github.io/hist1900/assets/slides/adot.png)

Reverse image search suggests it comes from [here](https://azdot.gov/node/7545)

Do you know how to reverse image search?

**Users:**

-   consulant: 'the network user, new and established, is probably the most neglected element within the the present development atmosphere'

**Unintended Users**

-   Michael Hart at U of Illinois - posts Declaration of Independence on his site's computer in 1972- the start of Project Gutenberg
-   users at MIT found they could use the IMP to speed up local data communications on their own campus, not even sending material onto ARPANET - a Local Area Network
-   games

Xerox Palo Alto Research Center adapts Alohanet method for wired communcation around its facilities

**Vint Cerf and Robert Kahn**

Cerf and Kahn oversee a series of meetings and seminar to hammer out details amongst interested parties

-   datagrams from cyclades
    
-   error correction and random access from ethernet/alohanet,
    
-   and also: no more imps or network control protocol. The host itself has to handle this.
- Transmission Cotnrol Protocol (TCP) hammered out by 1973


At the boundaries between networks, the creation of Gateways

![](https://shawngraham.github.io/hist1900/assets/slides/datacenter.png)

Companies emerge to physically handle those gateways.


![[Pasted image 20230315140327.png]]



BBN starts packaging TCP/IP into Unix operating system; it gets incorporated into other flavours of computing machinery too. Including in IBM machines.

But... most hosts on ARPANET continued to putter along with the original specifications: they were quite happy just talking amongst themselves.

Decision from on high: You **will** shift to TCP/IP by January 1983 or be cut out of ARPANET entirely.

The clock is ticking....

## Summary

-   before you can internet, you need to network
-   users have to find a reason to use
-   your users aren't who you might think they are
-   what they'll use it for isn't what you think it'll be
-   simpler wins out over complex
-   military & politics are always in the background
-   The internet is 'invented' 1973-1983.
-   Internet Culture is happening at the same time, and not even mostly on ARPANET

next day (maybe):

growth of consumer grade computers

quick history of video games

hacker culture, phreak culture

emergence of BBSs and online culture that _isn't_ internet

including MUDs too I think

Nelson and Xanadu are coming, not sure where to fit them in yet.

[https://en.wikipedia.org/wiki/Computer_Fraud_and_Abuse_Act](https://en.wikipedia.org/wiki/Computer_Fraud_and_Abuse_Act)