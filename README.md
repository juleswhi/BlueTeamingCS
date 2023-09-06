# Blue Team / Cyber Security
### [What is a Blue Team?](https://www.crowdstrike.com/cybersecurity-101/red-team-vs-blue-team/ "Red Team VS Blue Team")



Main Concept:
+ A network completely offline from the internet.
+ Risk free environment
+ No permanent consequences
+ Sandbox for using and understanding common attack vectors


## Option One ( ***Direct Connection*** )

This option involves a direct connection between two Pi's ~~With either a switch or not~~.
This allows direct communication between the two.
In the example, Left RPI would be the "Attacker" and Right would be the "Target". 

The target could have intentional vulnerabilties which would need to be found and fixed/used

_Advantages_
+ Simple and Quick

_Disadvantages_
+ Lack of scalability

![Option One Image](https://github.com/juleswhi/BlueTeamingCS/assets/62078259/2c67b772-3cfd-434f-8a60-e898a61acf67)

## Option Two ( ***Star Topology*** )

This option would involve multiple RPIs, all connected from one switch to each other.

_Advantages_
+ Easy to add new Pis

_Disadvantages_
+ Needs Switch

![Option Two Image](https://github.com/juleswhi/BlueTeamingCS/assets/62078259/458a0892-f7fa-415d-b4f8-34449bc66698)

## Option Three ( ***Star Topology*** )

This option is very similar to *Option Two* BUT it uses one Pi as a [Router](https://openwrt.org/ "Free and Open Source Router Software"). 

Using a Pi as a router can help replicate a real life network, as the router is a common attack point for [Black Hats](https://en.wikipedia.org/wiki/Black_hat_(computer_security) "What is a Black Hat?")

_Advantages_
+ All the same as Option Two
+ Can help teach about DHCP, DNS etc.

_Disadvantages_
+ May be difficult to setup.

![Option Three Image](https://github.com/juleswhi/BlueTeamingCS/assets/62078259/375feae0-662b-427f-b602-2c353c8deb08)

## Option Three Point Five ( ***Star Topology*** )

This option is more of a continuation of *Option Three*.
It involves creating a DNS server to resolve local hostnames etc. 

_Advantages_
+ Emulate real life technologies, that are used everywhere.
+ Understand Low and High level concepts

_Disadvantages_
+ Same as Option Three
+ Does not fully replicate a real DNS server


![Option 3.5 Image](https://github.com/juleswhi/BlueTeamingCS/assets/62078259/f8a64180-c350-4e0d-b3f6-9f42959681f4)



### List of requirements:

+ Pis
+ Switch?



