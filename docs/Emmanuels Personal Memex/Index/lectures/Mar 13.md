
##  Is it time for the internet yet?

Competences

-   existence of digital computers
-   existence of telecommunication networks
-   existence of information theory
-   ideas around flow control, logic, algorithms
-   demonstration of control of a calculator over a phone line in 1940


Remember, info theory allows us to separate meaning of a message from its 'information', the measure of its redundancy, hence, the amount of damage it can take and still be understood.

Without that insight, nothing else can work. It's what makes digital communications _work_.


Timesharing

-   technique for using the speed of the computer to present the appearance of multiple simultaneous users
-   terminal - a keyboard/teletype/whatever for transmitting instructions, displaying results

The humble modem

![](https://images.computerhistory.org/timeline/timeline_networking.web_1949_modem.jpg)

But which computer to use?

How to effectively get your data into and out of that computer?

Discrete circuits? Or something else?


UK Political Context

-   Harold Wilson's fears of losing out on tech
-   Donald Davis, National Physical Laboratory

![](https://shawngraham.github.io/hist1900/assets/slides/IBM_2741_(I197205).png)IBM 2741, ca 1965

-   a direct connection in adjacent rooms at first
-   then local phone lines
-   but long distance rates interfere
-   high cost of communication makes users work fast, which undermines purpose of timesharing

-   Davis unveils packet switching in 1966 at a conference.
-   learns from a British military officer afterwards that it's already been invented by Baran
-   Baran uses words like 'survivable', 'kill', 'salvos', 'target'
-   Davis reads Baran's work, says, y'know, we don't need this in a civilian context


Meanwhile, back in the US

-   ARPA - Advanced Research Projects Agency - _oh shit Sputnik!_ - created 1957
-   AT&T greet Baran's ideas with hostility; Defence Communication Agency populated with telephone people, so Baran's ideas dead in the water

Lyndon Johnson, in 1965 - directed agencies to support basic university research, and that centers of excellence should be created throughout the university

Lawrence Roberts - manager, ARPANET project, 1966

## Early computer science centres

UCLA- time sharing

RAND - graphics

SDC - time sharing

SRI- time shraing

Stanford - AI

Berkely - timesharing

Illinois - supercomputing

CMD - AI

BBN- time shraing

MIT - AI, graphics, timesharing

Harvard - graphics

ARPA calls a meeting in 1967 of computer scientists with an interest in computerized communications

-   that is, IPTO called the meeting

First RFQ for the ARPANET - August 1968

## Who will build these IMPs?

-   coming from Honeywell, yes, but extensive customization needed
-   Boston company: Bolt, Beranek and Newman gets the contract
    -   Licklider _just happened_ to have worked for them in the 1950s.
-   How do you make this thing, a 'router'? How do you actually make 'packet switching' work?

The thing that gets designed ultimately is a fusion of Baran and Davis' designs and concerns

-   fewer of the 'hardened' cold-war survivability features
-   more of the high-speed transmission, adaptive routing



Not just the Internet. The same structure gives us.... the [Mother of All Demos](https://invention.si.edu/mother-all-demos)

-   SRI, December 1968
    -   Douglas Englebart demonstrations the 'NLS', the oNLine-System


Anyway...

-   By focusing on IMPs and how to automatically read the network for congestion and figure out the best route, BBN & IPTO & ARPA sidestep the local mainframe people
-   local mainframe people only have to figure out how to make the first link to IMP; not every centre with a mainframe was on board with this project.

-   by 1968-9 things are happening fast
    -   BBN working on the honeywells, routing algoritms, protocols for IMPs
    -   main frame teams form themselves into a 'Network Marking Group' to figure out their end
        -   Standford Research Institute comes up with the LOGIN command
    -   ideas like skipping IMPs and going computer-to-computer, treating each other as a terminal of the other... lots of ideas are kicked around
    -   different groups form around the different problems