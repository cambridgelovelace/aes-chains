# aes-chains

At the [Hackathon](http://www.cambridgelovelace.org/), six of us worked on several chains of programming cards for the [Analytical Engine simulator](http://www.fourmilab.ch/babbage/cards.html Analytical Engine simulator). Some of these chains appear on the [event wiki](https://github.com/cambridgelovelace/cambridgelovelace.github.io/wiki), but some of us expressed an interest in working on larger programs, or tools to allow their expression at a higher level. This repository was set up to help coordinate this work.

Suggested conventions:
* Use `.aes` as a file extension.
* We expect chains of cards to build into more complex ones. To keep things tidy, store the chains under a subdirectory which suggests the end goal of the chains defined within it. Where the chain performs a general function, `util/` probably makes sense.
* Commit any tools (scripts, etc) used to generate chains.
