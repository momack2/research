# Protocol Labs - Research
[![](https://img.shields.io/badge/team-research-0f41f4.svg?style=flat-square)](https://github.com/protocol/research)

> :rocket: Making Protocol Labs Protocol _Labs_.

Welcome to the main research landing and launch page.  

Our core mission is to bring research to the front of the organization: enable Protocol Labs to continue to work on not only implementing great tech, but also develop, specify, and improve new tech.

# What's in This Repo?

This repo contains a directory and explanation of the structure of public research at Protocol Labs.  While not all Protocol Labs research will begin in this repository under public scrutiny, most will.  In addition, only under extreme circumstances will we ever make private any progress on a project that was at any point made public.

In addition, this repo will hold the research roadmap, which includes all research that we are engaged in or supporting, including research being conducted by researchers who are not formally members of Protocol Labs.

This repo also contains a list of open problem statements in the issues and serves as a workplace and dicussion venue for those problems.


 - Subscribe to this repo if you want to be updated about new research ideas and discussions

---


# How to Navigate Protocol Labs Research - What's in the Other Repos
In general, research ideas start here as responses to important questions, and then potentially develop into RFPs or their own research topic repositories.  The research repositories within IPFS and Filecoin should take on a similar structure over time.

## Unique structural repos
There are two public structural repos that contain directories, instructions, or other information needed for performing research at PL.


### [protocol/research-RFPs](https://github.com/protocol/research-RFPs)
 - contains grant information and RFPs for applicants

### [protocol/research]  **(this repo)**
 - default location of all research topics before they've reached prototype stage
 - contains index of public research
 - contains links, the list of open problem statements (in the issues)


## Research Topic Repos 
These repositories store work on a specific topic.  Once an idea has sufficiently developed, creating a new respository for that specific topic can be proposed.  Research topic repo names follow the following format (where %org currently includes 'protocol', 'ipfs', 'multiformats', and 'libp2p'): github.com/%org/research-%topic.

### Current Topic Repos
 - [ipld/research](https://github.com/ipld/research)
 - [ipfs/research](https://github.com/ipfs/research)
 - [ipfs/research-bitswap](https://github.com/ipfs/research-bitswap/)
 - [ipfs/research-CRDT](https://github.com/ipfs/research-CRDT/)
 - [ipfs/research-blockchain-data](https://github.com/ipfs/research-blockchain-data/)
 - [ipfs/research-p2p-video](https://github.com/ipfs/research-p2p-video/)
 - [libp2p/research](https://github.com/libp2p/research)
 - [libp2p/research-pubsub](https://github.com/libp2p/research-pubsub/)



## Creating an open problem statement
Open problem statements are to be created by anyone in the community as issues in this repo, and should be used to prompt and focus discussion and investigation.
The purpose of an open problem statement is twofold.  Firstly, it should convince the reader that the problem you are presenting is worth working on.  Secondly, it should provide enough background and understanding of the problem that all design decisions and requirements are comprehensively described and motivated.  Feel free to deviate from the issue template if you prefer, or answer the following questions as succinctly as possible for an easy open problem statement.

While this template was made to support the RFP program, the open problem statements themselves are purely for the benefit of the community, and there is no obligation to make an RFP for each open problem.



## Example Use Cases

### Working on a public research problem
Start with the list of problems (logbook) in the issues of this repo.  Post your thoughts on that issue and help develop potential solutions.  If the project reaches the point of prototyping solutions, propose making a repo for it and copy over the relevant items.

### Turning a problem into an RFP or bounty
Start by writing up the problem statement in Markdown or LaTeX, which should include sections motivating the problem, describing and distinguishing the ideal solution from similar exisitng systems, defining terms and data structures, and listing constraints.  Then create an issue for discussing the scale and importance of the problem so that a timeline and size for the bounty/grant can be determined.  If, at any point in this process, the problem grows quite large, it's possible that the problem, discussion, and problem statement can move out of [research](https://github.com/protocol/research) and into its own repo.  Otherwise, the problem statement and discussion of scale and importance should take place in one of the aforementioned two repositories.  Tag a core Protocol Labs researcher in the discussion, and if funding can be allotted, the final RFP will be posted in [research-RFPs](https://github.com/protocol/research-RFPs) and will link to the problem statement.


