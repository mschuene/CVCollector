# CVCollector
Search different web communities (boards, Twitter, Youtube, etc) for new posts of penspinning videos and collect the links.


# Rationale

Penspinning boards grow more and more inactive and the penspinning media scene is fragmented between different social media sites. To help penspinners stay up to date with new videos posted, this projects will search different sites for new video posts and collects the links in a central place.


# Overview 

This program will consist of different Modules, one for each social media site, that provides functionality to scrape the website or use a provided api to search for penspinning videos posted since a given date. 

At regular intervals, the main program will invoke all it's modules and update a central list of links to penspinning videos. 

Optional Functionality: 

- Detection of reposts
- Classification according to single user-, gather-, or collaboration videos


