# Resources
A collection of resources, both CS and non-CS that I have found useful.

Credits to Dan Murphy for directing me to a lot of these resources.

## Books:
- Spark: The Definitive Guide by Bill Chambers and Matei Zaharia
- Java SE 8 For the Really Impatient by Cay S. Horstmann
- Effective Java by Joshua Bloch

## Online Resources:
- [Execute Program][https://www.executeprogram.com/](https://www.executeprogram.com/)
- [Destroy Software][https://www.destroyallsoftware.com/screencasts](https://www.destroyallsoftware.com/screencasts)

## Art References:

![Elephant Art - Liam Collins](https://user-images.githubusercontent.com/54238206/154375854-df36da6c-c97c-4889-8ac6-c5e0708436d5.jpg "Elephant Art")


Useful Recommendations I've been given. Big credit to @Murphydbuffalo here!
## Algorithms
+ [Visualize sorting algorithms](https://www.toptal.com/developers/sorting-algorithms)
+ [How hash tables/dictionaries work](https://stackoverflow.com/questions/730620/how-does-a-hash-table-work)

## APIs
+ [REST vs GraphQL](https://philsturgeon.uk/api/2017/01/24/graphql-vs-rest-overview/)

## Authentication and Single Sign On
+ [OAuth](https://gist.github.com/mziwisky/10079157)
+ [JSON Web Tokens](https://jwt.io/introduction/)
+ [OAuth vs JWT](https://community.apigee.com/questions/21139/jwt-vs-oauth.html)
+ [SAML](https://developers.onelogin.com/saml) (similar to JWT, but XML based instead of JSON based). Also, the SAML specification describes both the token (the XML document) format, and the protocol for issuing tokens. JWT only describes the token format and leaves the mechanism for using those tokens up to the developer. Eg, you can use JWTs with the OAuth2 protocol.

## Blockchain and Bitcoin
+ [Why Blockhain isn't better than existing solutions to most problems](https://medium.com/@kaistinchcombe/decentralized-and-trustless-crypto-paradise-is-actually-a-medieval-hellhole-c1ca122efdec)
+ [How Bitcoin works under the hood](https://www.youtube.com/watch?v=Lx9zgZCMqXE)
+ [Blockchain 101](https://www.youtube.com/watch?v=_160oMzblY8)

## Build Your Own [Insert Name of Technology Here]
+ [Awesome GitHub repo](https://github.com/danistefanovic/build-your-own-x)

## Cryptography
+ [Brit Cruise's amazing video series on RSA and public key cryptography](https://www.youtube.com/playlist?list=PLB4D701646DAF0817)

## Design Patterns
+ [Are small methods good?](https://www.bignerdranch.com/blog/youre-killing-me-smalls-are-small-methods-good/)

## Distributed Systems & Peer-To-Peer
+ [Some pros and cons of a P2P web](https://blog.datproject.org/2016/12/12/reader-privacy-on-the-p2p-web/)

## Favicons
+ [Real Favicon Generator](https://realfavicongenerator.net/) makes you favicons that work across all platforms. It's amazing.

## Fun
+ [Parsing HTML with RegExps... classic](https://stackoverflow.com/questions/1732348/regex-match-open-tags-except-xhtml-self-contained-tags)

## Git
+ Useful [examples](http://travisjeffery.com/b/2012/02/search-a-git-repo-like-a-ninja/#practical-examples) of how to use `git grep`. Eg, grepping by commit, branch, or within your uncommited changes.
+ [Shell command](https://stackoverflow.com/questions/9456550/how-to-find-the-n-largest-files-in-a-git-repository) to find the 10 biggest files in a git repo: `git ls-tree -r -l --abbrev --full-name HEAD | sort -n -r -k 4 | head -n 10`

## Hardware
+ [Code by Charles Petzold](https://www.goodreads.com/book/show/44882.Code) fanatastic intro to computer hardware
+ [Learning Computer Architecture with Raspberry Pi](https://www.wiley.com/en-us/Learning+Computer+Architecture+with+Raspberry+Pi-p-9781119183938)

## JavaScript
+ [Tom Dale on how JS frameworks are evolving to cater to mobile](https://medium.com/@tomdale/making-the-jump-how-desktop-era-frameworks-can-thrive-on-mobile-3b611008118d)


## Linux
+ [YouTube series on Linux and sysadmin fundamentals](https://www.youtube.com/playlist?list=PLtK75qxsQaMLZSo7KL-PmiRarU7hrpnwK)

## Machine Learning
+ [The greatest explanation of backpropagation ever](http://cs231n.github.io/optimization-2/)

## Network Protocols
+ [Gary Bernhardt does it again](https://www.destroyallsoftware.com/compendium/network-protocols?share_key=5d410cb65c6e81bd)

## Strings
+ Understanding and working with UTF8 and Unicode, [part 1](https://www.bignerdranch.com/blog/unicode-and-utf-8-explained/) and [part 2](https://www.bignerdranch.com/blog/elixir-and-unicode-part-2-working-with-unicode-strings/). The code is in Elixir, but the principles are generally applicable.

+ [Greedy and non-greedy regexs](http://eloquentjavascript.net/09_regexp.html)

## Time Zones
+ [Working with time zones in Rails](https://robots.thoughtbot.com/its-about-time-zones)

## Type Systems
+ [Gary Bernhardt's breakdown reigns supreme](https://www.destroyallsoftware.com/compendium/types?share_key=427306bd5c0dc2c9)

## Versioning
+ [Speculation](https://www.youtube.com/watch?v=oyLBGkS5ICk) by Rich Hickey. Is semantic versioning stupid?
