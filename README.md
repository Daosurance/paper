# Daosurance

[John D. Storey](mailto:johndangerstorey@gmail.com)

V0.2 - Jan 4, 2019

### Table of Contents

[Abstract](#abstract)

[The Problem](#the-problem)

[Uses](#use-cases)

[Roles](#roles)

[Attacks](#attacks)

[FAQ](#faq)

---

## Abstract

Daosurance is a DAO based insurance company where all members are expected to participate at some level or other and enjoy the benefits of increased effeciency.  How this is achieved will be explored in the following sections but draws heavily on a "jury" system where participants are selected at random and expected to perform tasks that catch fraud and allow for improvements to be made to the organization in a decentralized way prolonging it's usefullness to it's members by it's own survival. 

If successfull it will outgrow traditional companies and will start to be somewhat of a borderless nation state that combines money and determines the best use of it's funds in ways that traditional charasmatic leader based governance is based.  While some of the ideas may be ignorantly flawed, it is important to start in order to make the improvements neccessary.

    “There are risks and costs to a program of action. 
    But they are far less than the long-range risks and costs of comfortable inaction.” 
    
    - John F. Kennedy

## The Problem

Currently health insurance is approximately $300 a month for a single member.  $3,600 annually that for the currently health feels like a bottomless hole they are throwing money into that they won't be able to recoup or benefit from because all the profit is going towards a centralized corporation rather than the value created returning back to the members of it's network.

## Use Cases

1. User makes claim against group for an issue.  Needs paperwork to be verified, uploaded for future verification, and after 2 weeks if no suspicious behavior is found the money transfers.
2. Group has excess money in escrow, a member wants to allocate that money back to all the members or fund some other member focused initiative.  They submit a proposal that is investigated and then voted upon.

## Roles

* Member: each individual person paying for the service.  They have a set fee associated with their membership.
* Citizenship Officer: In charge of who joins and who leaves.  Vet and onboard incoming members, and when someone is flagged as suspicious a group of them will investigate and vote on if they can stay in the group or not.  Joining members should have identity verified on chain so that if criminal activity happens the member can be identified.
* Verifier: checks to make sure the issue isn't fradulent, hasn't been claimed against before.
* Investigator: looks into suspicious claims or red flags that verifiers have noticed.  For all proposals (insurance claims, policy changes & surplus escrow use)
* Proposal Sponsor: Person responsible for overseeing the proposal they are putting forth.

## Attacks

* User makes multiple claims against the same issue
  - We'll need to come up with a way to identify each issue, such as a picture of the bills and line items of what they are being reimbursed for.  Then when a claim is made, the verifier should check against their past claims.
* Member colludes with friends to submit false claims.
  - Verifiers are chosen at random, similiar to how jury duty is assigned.  Each verifier can signal red flags for investigators to look into.  If qurom of investigators believe member to be.
* Member has stopped paying dues
  - since everyone will be able to see who is active, this will be easily resolved by Verifier.
* One brand of RV, other other traight found in members is especially problematic and could cause group to go broke
  - Sponsor will submit a policy change, to be investigated by investigation group and voted.  If approved will then be ammended to the existing open source policy.  Up to future investigators to enforce.
* All verifiers get together and decide to verify each other's claims
  - 1) put a reward on successfull whistle blowing 2) have a minimum amount of time (2 weeks) between when a claim is posted and when it is paid out and allow each member to also have a "red flag" they can post to transactions.  If claim starts to get attention, Citizenship Officer will investigate and if member is removed before payout then funds stay in escrow.
* Wealthy member colludes with investigators and citizenship officers to pass fraudulent claims or proposals
  - Same as above, hopefully there is an incentive to members to whistle blow in such scenarios, and if not then the group can superceed the Citizenship Officer, and kick out any member with a majority vote.

## FAQ

Q:  Will we ensure unhealthy people or those with pre-existing conditions?
A:  No, not at first.  We won't be able to afford those kinds of members at the onset.  We wish them well and are gratefull that we have existing insurance companies to treat them. Unless we can get an insurance for our own insurance to cover us until we've built up needed funds. 

Q:  Is there a cap of which one can be insured?
A:  There is a maximum that one is able to pull out from the insurance that increases with time and money given to the platform.  The multiplier is quadratic.

Q:  What will be the underlying currency?
A:  A stable coin such as TUSD, DAI or USDC will be used for paying claims.  Voice credits will be used for voting on policy and resource proposals.

Q:  Will members that have been in the group longer have a more powerful vote than new members.
A:  Yes, we will use quadratic voting to ensure that those that have put more money into the system have a slightly more influential vote, however not powerfull enough to overturn the general will.  For more information on quadratic voting see the [wikipedia page](https://en.wikipedia.org/wiki/Quadratic_voting)