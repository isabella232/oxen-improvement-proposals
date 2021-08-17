# OIP (Oxen Improvement Proposal)
Oxen Improvement Proposals (OIPs) are the formalized methods by which the Oxen Project Team, external contributors or contractors can make proposals for any major Oxen or Lokinet upgrades, this can including core protocol specifications, client APIs, and additional features.

A OIP is supposed to be championed by the proposer, this means that OIP’s do not always present an objective view of the situation, ultimately it is the role of the Service Nodes or The OPTF (depending on the proposed voter) to decide of the efficacy of a OIP, these decisions should be impacted by community sentiment and dissenting technical arguments.  

OIPs can also act as supplementary documents for funding applications  to the OPTF, or Oxen funding system.

# Contributing

Anyone is free to propose an OIP, if they follow the formatting rules setout in this document. 

 1. Fork the repository by clicking "Fork" in the top right.
 2. Read the [LIP-x](lip-X.md) template to understand how a OIP should be structured
 2. Add your OIP, in the OIP's folder [Here](https://github.com/oxen-io/oxen-improvement-proposals/tree/master/LIPS) of your fork.
 3. Submit a Pull Request to Oxen's [LIPs repository](https://github.com/oxen-io/oxen-improvement-proposals) from your fork.

Your first PR should be a first draft of the final OIP. An editor will manually review the first PR for a new OIP and assign it a number before merging it. All discussion should occur inside of the OIP.

If your OIP requires images, the image files should be included in a subdirectory of the `assets` folder for that OIP as follow: `assets/lip-X` (for lip **X**). When linking to an image in the OIP, use relative links such as `../assets/lip-X/image.png`.

There are two main progression routes for OIP's

**Submitting your OIP for Vote**

If you are submitting your OIP for vote by the OPTF or the Oxen Service Nodes you should tag the title of your request as per OIP-x Specs with either [Foundation Vote] or [Service Node Vote]. If the OPTF or Service Nodes approve your OIP then an editor will tag your OIP as finalized. If the Service Nodes or the Foundation denies your OIP then your pull request will be closed, you are free to make another proposal which addresses any concerns raised by the foundation or Service Node operators and re-propose your OIP.

**OIP Assessment by the Oxen Project Team**

If you believe your OIP does not need to be voted on by the OPTF or Service Nodes then you can tag your OIP as a [No Vote]. If a OIP is tagged with [No Vote] your OIP editor may still refer your OIP to a vote by the Foundation or Service Nodes if they believe the OIP is controversial or the discussion around the OIP does not reach consensus.
If the OIP does not need to go to a vote then the OIP editor should decide when the OIP is ready to be marked as final. 

**OIP Finalized**

Once an OIP is finalized the Oxen development team will work alongside you to help you merge your changes into the development branch of Oxen, any pull request to Oxen should reference relevant OIPs if the change is major. if your OIP is marked as Final but does not yet have developed code, we encourage regular communication to the community using the OIP pull request as a sounding board.

# OIP Status Terms
* **Draft** - an OIP that is undergoing rapid iteration and changes
* **Last Call** - an OIP that is done with its initial iteration and ready for review by a wide audience
* **Denied** - an OIP that has been rejected by either a vote from the Oxen Service Nodes, the OPTF or the OIP editor.
* **Final** - an OIP that the Oxen Project team have decide to implement and release in a future hard fork or has already been released in a hard fork
