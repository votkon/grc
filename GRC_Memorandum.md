# Memorandum of the Gonka Restitution Committee (GRC)

## 1. Purpose and Scope

1.1. The Gonka Restitution Committee (GRC) exists to identify network incidents, collect victim feedback, group incidents into cases, and assemble those cases into GRC proposals for restitution.

1.2. The GRC's scope is limited to restitution for losses caused by **confirmed protocol bugs, provable from on-chain state**. The following are explicitly out of scope:
- External attacks;
- Vulnerability exploitation;
- Hardware failures;
- Other external factors not caused by the protocol itself;
- Losses attributable to assumptions, market movements, or ordinary network consequences.

1.3. Cases predating epoch 132 (when the first GRC case was handled) are out of scope. The GRC only moves forward from that point.

1.4. The on-chain-data rule is the foundational, verifiable standard of the GRC. All case validation must be checkable against on-chain state.

## 2. Organization

2.1. The GRC operates as a group chat with polling used for votes.

2.2. The official language of GRC communication is English. Discussion in the GRC is held in English and is limited strictly to matters within the GRC's scope.

2.3. Only host representatives may vote on committee decisions. In particular, the following decisions are made exclusively by host representatives:
- Setting bounties and their vesting;
- Case inclusion and exclusion.

2.4. Voting parameters:
- Voting period: 24 hours, or earlier if an irreversible majority is reached;
- For now, votes take place in the GRC chat;
- Decisions are made by 50% + 1 of votes cast, except where this memorandum requires a 2/3 vote;
- Quorum: 66% of members;
- No veto option - voting options are Yes / No / Abstain only.

2.5. No vote may override this memorandum. Any decision that contradicts the memorandum is void; the rules may only be changed through the amendment procedure in Section 10. The Coordinator is responsible for enforcing this.

## 3. Membership

3.1. Any host may access the GRC. By default, any host active on the network for the last 30 days is eligible to participate. The activity period may be changed by amendment.

3.2. A minimum network-weight threshold for participation may be applied by amendment, but no threshold is set by default.

3.3. Requirements for participants:
- Must represent an eligible host;
- Must have a technical understanding of how the network works;
- No more than one participant per host;
- Must have the ability and motivation to participate actively.

3.4. Hosts who are not public or cannot be identified by the Coordinator may be asked to set their moniker to confirm their identity. This is a last-resort measure, not a standing requirement.

## 4. Coordinator

4.1. The Coordinator serves until replaced.

4.2. The Coordinator is replaced by electing a new Coordinator by a vote of 2/3 of members. The newly elected Coordinator replaces the current one immediately, so the position is never vacant.

4.3. The Coordinator's responsibilities:
- Enforcing this memorandum;
- Assigning developers as investigator and reviewer for each case;
- Assembling cases into proposals;
- Publishing proposals;
- Helping establish communication with victims and the community;
- Facilitating GRC decision-making by proposing polls and decisions.

## 5. Developers

5.1. Developers who wish to execute case investigation and validation may be asked to prove their skills through a short interview or a sample case before being assigned.

5.2. Developers who do not represent an active host have no voting rights and do not count toward quorum, but may consult the GRC and express their opinion in discussions.

## 6. Case Workflow

6.1. **Case election.** Case election must precede investigation and must pass a proper GRC vote.

6.2. **Investigation and review.** The Coordinator assigns one developer as investigator and one as reviewer. If the investigator and reviewer do not reach consensus, a third developer is assigned as an additional reviewer.

6.3. **Reproducible evidence.** Each investigated case must be delivered with reproducible code that fetches data from the chain to recreate the issue and calculate the resulting losses.

6.4. **Rejected cases.** A rejected case must not go to public consideration until the committee reaches internal consensus on how it is presented and what options are offered.

6.5. **Proposals.** The Coordinator assembles validated cases into proposals and publishes them. Any case added to a GRC proposal must have sufficient on-chain or in-code proof. GRC proposals may only contain cases with calculations performed by the investigator and reviewer - no amendments, no coefficient changes, no joining with other initiatives. Proposals are pure restitutions based on code.

## 7. Conflict of Interest and Recusal

7.1. A host representative may not investigate a case in which their own host appears on the victim list, with an exception for big cases where many hosts were involved.

7.2. Such a representative may still act as validator on that case, with exceptions permitted for smaller cases, manpower shortages, or big cases where many hosts were involved.

7.3. Members or developers working on a case may not participate in bounty votes for that case.

## 8. Bounties

8.1. Bounties are set prior to any proposal or case work.

8.2. Bounties vest over 30 days.

8.3. Bounty amounts may only be changed by GRC vote. Any member may bring a bounty change to a vote.

## 9. Discipline

9.1. The Coordinator may pause a member's GRC presence for up to one month if the member is not participating in votes or if the member's actions are harmful to the GRC.

9.2. In particular, a member who misses 3 out of 5 polls (closed within their 24-hour voting period) may be suspended from the GRC for up to one month.

9.3. Paused members are excluded from quorum and voting-threshold calculations. This is done to keep GRC decision-making active and encourage involvement.

9.4. The Coordinator removes members whose host has not had an active weight on the network in the last 30 days. A removed member may rejoin under the standard membership requirements in Section 3.

## 10. Amendments and Dissolution

10.1. Any change to this memorandum requires a vote of 2/3 of members.

10.2. The GRC may be dissolved by a vote of 2/3 of members.
