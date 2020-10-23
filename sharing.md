

## Information Sharing

When working on a large project like the iAM.AMR, it can be difficult to determine what information is public, what is private, what is shared with the team, and what should be shared on a need-to-know basis -- either because the data are valuable intellectual property (we hope - says the grad students), or more commonly because the data are preliminary in nature.

We've decided to use the **Traffic Light Protocol (TLP)** to try and make information sharing easier.


### Traffic Light Protocol (TLP)

The [Traffic Light Protocol (TLP)](https://en.wikipedia.org/wiki/Traffic_Light_Protocol) was created by the UK's [Centre for the Protection of National Infrastructure](https://www.cpni.gov.uk/) in order to facilitate greater sharing of information, and has been adopted by organizations like the [Department of Homeland Security](https://www.us-cert.gov/tlp) to indicate to collaborators when and how to share sensitive information. We've adapted the protocol here for the academic context -- for more help, see [FIRST](https://www.first.org/tlp/).


#### <a name="share-yours"></a> Sharing **Your** Information

When you want to indicate how widely information may be shared, you include one of the four **TLP LEVELS** in the format **TLP:COLOUR** in the subject of your email, or while describing a shared file. Even better, include it in the file name so the recipients can't forget!

e.g. my_lifes_work_cash_money_bitcoin_wallet_TLPRED.xlsx     


#### <a name="share-mine"></a> Sharing/Using **Others'** Information

When you want to share others' information (or include others' information in your own work) you check the **TLP:COLOUR** in the GitHub repo, the folder contents, or file name and:

- if that level prohibits use, you ask the owners' explicit permission to use/share it.
- if that level permits use, you use/share it responsibly, and **give attribution**.
- if you can't determine the specified level (or unambiguously infer a level -- see below) you ask the owner.


#### TLP Levels (Colours)

| Color       | Summary                                                          | When should it   be used?                                                                                                                                                                                                                                            | How may the information be   shared?                                                                                                                                                                                                                                          |
|-------------|------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|  TLP:RED ![TLP Level Badge](https://img.shields.io/badge/TLP-RED-red)   | Not for   disclosure, restricted to participants only.           | When information   cannot be effectively acted upon by additional parties, and could lead to   impacts on a party's privacy, reputation, or operations if misused.        > e.g. personally identifiable information, early manuscripts,   unpublished works         | Recipients may   not share TLP:RED information with any parties outside of the specific   exchange, meeting, or conversation in which it was originally disclosed.                                                                                               |
|  TLP:AMBER ![TLP Level Badge](https://img.shields.io/badge/TLP-AMBER-yellow) | Limited   disclosure, restricted to participants’ organizations. | When   information requires support to be effectively acted upon, and carries risks   to privacy, reputation, or operations if shared outside of the organizations   involved.      > e.g. unfinished models, raw datasets, internal communications, meeting   notes | Recipients   may only share TLP:AMBER information with members of the iAM.AMR team. This   is the default level for all information stored in the iAM.AMR GitHub   repository (and other private repos).                                                         |
|  TLP:GREEN ![TLP Level Badge](https://img.shields.io/badge/TLP-GREEN-brightgreen)  | Limited   disclosure, restricted to the community.               | When information is useful for the   awareness of all participating organizations as well as with peers within the   broader community or sector.      > e.g. student update presentations, posters, the online documentation,   preliminary results                 | Recipients may share TLP:GREEN   information with peers and partner organizations within their sector or   community as necessary. Care should be taken to highlight the preliminary nature of any conclusions not reviewed by the wider team. |
|  TLP:WHITE ![TLP Level Badge](https://img.shields.io/badge/TLP-WHITE-lightgrey) | Disclosure is   encouraged!                                      | When   information has been released to the public.      > e.g. peer-reviewed publications, external presentations                                                                                                                                                   | Subject   to standard copyright rules, TLP:WHITE information may be distributed without   restriction.                                                                                                                                                           |


#### Default and Contextual Levels

If you don't include a **TLP LEVEL**, one may be otherwise inferred by context.

By default, anything shared in an iAM.AMR group forum accessible only to the team (e.g. team-public Slack channel, Dropbox, Google Drive, private GitHub Repo) is **TLP:AMBER**. It should not be shared outside of the team.

By default, anything shared in a forum accessible to the world (e.g. the documentation site, student presentations, posters) is **TLP:GREEN**. It is accessible to the world, with the understanding that the results may be preliminary and not yet published.

By default, any peer-reviewed paper is **TLP:WHITE**. Use it, cite it, tweet it, just beat it -- the world is your oyster. And like anything TLP:WHITE, these are public-facing data or resources that should be disclosed and shared widely!


### Beyond the TLP

Can I be more specific in my sharing? Of course! The TLP is a general framework for information sharing, and you are free to specify additional limitations, or different TLP levels for different use-cases. Or, eschew the TLP all together! But recognize that the more you make strange, one-off exceptions, the more likely a mistake may happen.

As an example, consider the CEDAR database. While the data in aggregate is **TLP:AMBER** until a paper is published (wherein it becomes **TLP:WHITE**), the subsets of data included in each model may be **TLP:GREEN** and later **TLP:WHITE** independent of the whole of CEDAR.
