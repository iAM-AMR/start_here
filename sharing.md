
[![TLP White Level Badge](https://img.shields.io/badge/TLP-WHITE-lightgrey)](sharing.md)


# Information Sharing

## Summary

This document describes how we share information in the iAM.AMR project.

- Summary
- Purpose 
- TLP
  - about
  - use
    - shre you
    - shre
  - badges
- Beyond the TLP 



- [Summary](#summary)
- [Purpose](#purpose)
- [Traffic Light Protocol (TLP)](#tlp)
  - [About the TLP](#about-tlp)
  - [Use the TLP](#use-tlp)
    - [Share **your** information](#share-yours)
    - [Share/use **others'** information](#share-mine)
  - [Using Badges in GitHub](#using-badges-in-github)
  - [Context and Default Levels](#context-and-default-levels)
    - [Default Levels](#defaults)
- [Beyond the TLP](#beyond-the-tlp)

## Purpose

When working on a large project like the iAM.AMR, it can be difficult to determine what information is public; what information is private; and what information is shared only within the team.

This isn't because we're dealing with anything secret or classified; it's because data, models, or code is valuable intellectual property -- "*we hope!*" scream the grad students -- or are simply incomplete.


## <a name="tlp"></a> Traffic Light Protocol (TLP)

Wondering what those [![TLP White Level Badge](https://img.shields.io/badge/TLP-badges-lightgrey)](sharing.md) are all about?


We've decided to use the **Traffic Light Protocol (TLP)** to try and make information sharing easier.


### <a name="about-tlp"></a> About the TLP

The [Traffic Light Protocol (TLP)](https://en.wikipedia.org/wiki/Traffic_Light_Protocol) was created by the UK's [Centre for the Protection of National Infrastructure](https://www.cpni.gov.uk/) in order to facilitate greater sharing of information, and has been adopted by organizations like the [Department of Homeland Security](https://www.us-cert.gov/tlp) to indicate to collaborators when and how to share sensitive information. We've adapted the protocol here for the academic context -- for more help, see [FIRST](https://www.first.org/tlp/).

### <a name="use-tlp"></a> Use the TLP

When you exchange or share information, you label the exchange with one of four TLP colours, which indicates how private you should keep the information. You've probably noticed this document (and the rest of the repo) is labeled **TLP:WHITE**, for public. We use badges in GitHub repos -- for e-mail: 

> TLP-designated email correspondence should indicate the TLP color of the information in the Subject line and in the body of the email, prior to the designated information itself. The TLP color must be in capital letters: TLP:RED, TLP:AMBER, TLP:GREEN, or TLP:WHITE. -- [CISA](https://www.cisa.gov/tlp)

The levels are described below.

| Color       | Summary                                                          | When should it   be used?                                                                                                                                                                                                                                            | How may the information be   shared?                                                                                                                                                                                                                                          |
|-------------|------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|  TLP:RED ![TLP Level Badge](https://img.shields.io/badge/TLP-RED-red)   | Not for   disclosure, restricted to participants only.           | When information   cannot be effectively acted upon by additional parties, and could lead to   impacts on a party's privacy, reputation, or operations if misused.        > e.g. personally identifiable information, early manuscripts,   unpublished works         | Recipients may   not share TLP:RED information with any parties outside of the specific   exchange, meeting, or conversation in which it was originally disclosed.                                                                                               |
|  TLP:AMBER ![TLP Level Badge](https://img.shields.io/badge/TLP-AMBER-yellow) | Limited   disclosure, restricted to participants’ organizations. | When   information requires support to be effectively acted upon, and carries risks   to privacy, reputation, or operations if shared outside of the organizations   involved.      > e.g. unfinished models, raw datasets, internal communications, meeting   notes | Recipients   may only share TLP:AMBER information with members of the iAM.AMR team. This   is the default level for all information stored in the iAM.AMR GitHub   repository (and other private repos).                                                         |
|  TLP:GREEN ![TLP Level Badge](https://img.shields.io/badge/TLP-GREEN-brightgreen)  | Limited   disclosure, restricted to the community.               | When information is useful for the   awareness of all participating organizations as well as with peers within the   broader community or sector.      > e.g. student update presentations, posters, the online documentation,   preliminary results                 | Recipients may share TLP:GREEN   information with peers and partner organizations within their sector or   community as necessary. Care should be taken to highlight the preliminary nature of any conclusions not reviewed by the wider team. |
|  TLP:WHITE ![TLP Level Badge](https://img.shields.io/badge/TLP-WHITE-lightgrey) | Disclosure is   encouraged!                                      | When   information has been released to the public.      > e.g. peer-reviewed publications, external presentations                                                                                                                                                   | Subject   to standard copyright rules, TLP:WHITE information may be distributed without   restriction.                                                                                                                                                           |

#### <a name="share-yours"></a> Sharing **Your** Information

When you want to indicate how widely information may be shared, you include one of the four **TLP LEVELS** in the format **TLP:COLOUR** in the subject of your email, or while describing a shared file. Even better, include it in the file name so the recipients can't forget!

e.g. my_lifes_work_cash_money_bitcoin_wallet_TLPRED.xlsx     


#### <a name="share-mine"></a> Sharing/Using **Others'** Information

When you want to share others' information (or include others' information in your own work) you check the **TLP:COLOUR** in the GitHub repo, the folder contents, or file name and:

- if that level prohibits use, you ask the owners' explicit permission to use/share it.
- if that level permits use, you use/share it responsibly, and **give attribution**.
- if you can't determine the specified level (or unambiguously infer a level -- see below) you ask the owner.


### Using Badges in GitHub

The badges are generated from [shields.io](https://shields.io/). Scroll down to the *Your Badge* section on [shields.io](https://shields.io/) for instructions on creating your own! For public projects, these badges can also be used to describe stats, version numbers, or othe data.

The TLP badges can be copied from the table above as images, or inserted using:

```
TLP:RED   ![TLP Level Badge](https://img.shields.io/badge/TLP-RED-red)
TLP:AMBER ![TLP Level Badge](https://img.shields.io/badge/TLP-AMBER-yellow)
TLP:GREEN ![TLP Level Badge](https://img.shields.io/badge/TLP-GREEN-brightgreen)
TLP:WHITE ![TLP Level Badge](https://img.shields.io/badge/TLP-WHITE-lightgrey)
```


## Context and Default Levels

It's easy to forget to label our own information, and often we rely on implied or contextual cues when others share information with us. 

It is important to note:

- if you don't include a **TLP LEVEL**, one may be otherwise inferred by context
- assigning a **TLP LEVEL** does not guarantee privacy
  - it is up to users to respect TLP levels
  - it is up to users to control access to private information
- **TLP:RED** material should **ALWAYS** be labeled
- if in doubt, ask!

### Defaults

By default, anything shared on a service that you have to log in to (e.g. Slack, Dropbox, or a GitHub **private repo**) is **TLP:AMBER**. Do not share this information outside of the iAM.AMR team.

By default, anything shared on a service that is accessible to the world, but is not of immediate interest to the public (e.g. the documentation repo, the kumu, unfinished works, etc.) is **TLP:GREEN**. You may use or share it, but it is not designed for public consumption, and may be provisional or semi-private.

By default, anything shared on a service that is accessible to the world and/or is designed for public consumption (e.g. this **public repo**, or the documentation site) is **TLP:WHITE**. Use it, cite and link to it, go wild! These are public-facing data or resources that should be promoted and shared widely!


## Beyond the TLP

Can I be more specific in my sharing? Of course! The TLP is a general framework for information sharing, and you are free to specify additional limitations, or different TLP levels for different use-cases. Or, eschew the TLP all together! But recognize that the more you make strange, one-off exceptions, the more likely a mistake may happen.

As an example, consider the CEDAR database. While the data in aggregate is **TLP:AMBER** until a paper is published (wherein it becomes **TLP:WHITE**), the subsets of data included in each model may be **TLP:GREEN** and later **TLP:WHITE** independent of the whole of CEDAR.
