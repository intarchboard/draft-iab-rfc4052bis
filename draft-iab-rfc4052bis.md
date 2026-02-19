---
title: "IAB Processes for Management of IETF Liaison Relationships"
abbrev: "IAB Liaison Management"
category: info

docname: draft-iab-rfc4052bis-latest
submissiontype: IAB
obsoletes: 4052
date:
v: 3
venue:
  group: "Internet Architecture Board"
  github: "intarchboard/draft-iab-rfc4052bis"

author:
 -
    fullname: Suresh Krishnan
    organization: IAB
    email: suresh.krishnan@gmail.com
    role: editor
 -
    fullname: Mirja Kuehlewind
    organization: IAB
    email: ietf@kuehlewind.net
 -
   fullname: Qin Wu
   organization: IAB
   email: bill.wu@huawei.com

normative:

informative:


--- abstract

This document discusses the procedures used by the IAB to establish
and maintain formal liaison relationships between the IETF and other
Standards Development Organizations (SDOs), consortia and industry
fora. This document also discusses the appointment and responsibilities
of IETF liaison managers, and the expectations of the IAB in establishing
formal liaison relationships.


--- middle

# Introduction

The IETF, as an organization, has the need to engage in direct
communication or joint work with various other formal
organizations.  For example, the IETF is one of several Standards
Development Organizations, or SDOs, and SDOs including the IETF
find it increasingly necessary to communicate and coordinate their
activities involving Internet-related technologies. This is useful
in order to avoid overlap in work efforts, and to manage interactions
between their groups.  In cases where the mutual effort to
communicate and coordinate activities is formalized, these
relationships are generically referred to as "formal liaison relationships".

In such cases, a person is designated by the IAB to manage a given
formal liaison relationship; that person is generally called the "IETF
liaison manager" to the other organization. Often,
the other organization will similarly designate their own liaison
manager to the IETF.

This document is chiefly concerned with:

- the establishment and maintenance of formal liaison relationships {{relationship}}, and
- the appointment and responsibilities of IETF liaison managers {{manager}}.

The management of other organizations' liaison managers to the IETF,
whether or not in the context of a formal liaison relationship, is outside
the scope of this document.

The IETF has tasked the Internet Architecture Board to manage
formal liaison relationships.  As stated in its charter {{!BCP39}} 2.(f),
"The IAB acts as a representative of the interests of the IETF
in technical liaison relationships with other organizations
concerned with standards, and other technical and organizational
issues relevant to the worldwide Internet.  Liaison relationships are
kept informal whenever possible, and must possess demonstrable value to the
IETF's technical mandate.  Individual participants from the IETF community are
appointed as liaison managers to other organizations by the IAB."

In general, a formal liaison relationship is most valuable when there are
areas of technical development of mutual interest. For the most
part, SDOs would rather leverage existing work done by other
organizations than recreate it themselves (and would like the same
done with respect to their own work).  Establishing a formal liaison
relationship can provide the framework for ongoing communications to

- prevent inadvertent duplication of effort, without obstructing
  either organization from pursuing its own mandate;
- provide authoritative information of one organization's
  dependencies on the other's work;
- allow for the collaboration and coordination of efforts between the IETF
  and other organizations.

It is important to note that participation in the IETF work is open to everyone,
and all the working documents and RFCs are freely available to everyone without
the need for a formal liaison relationship. Hence, in almost all cases the need
for a formal relationship is mostly driven by other organizations rather than by
the IETF.

If tighter coordination is needed, the IAB might consider
additional activities such as meetings or calls with the relevant
people (e.g. chairs, ADs, and authors). Such activities could be
one-time events or organized in a standing groups. The liaison manager
should be involved in the organization and the running of these activities.
Such activities can e.g. make sense in cases where there are
a large number of document dependencies; this often happens when
specifications are developed in parallel.

Since the IAB is ultimately responsible for liaison management,
anyone who has an issue with a relationship (whether an IETF
participant or a person from the peer organization) should first
consult the IAB's designated liaison manager, and if that does not
result in a satisfactory outcome, then consult the IAB itself.

## Changes compared to RFC4052

This version of the document contains the following updates:

1. Notes were added in the Introduction and Section 2.1 on "Liaison Relationships" that the
   IETF process itself does not require a formal liaison relationship, e.g. for
   document access or meeting participation, and therefore the need for a formal
   liaison relationship is often driven by processes of the peer organization.
2. Statement that the "IAB acts as representative of the interests of \[..] the
   Internet Society" has been removed.
3. Role of the Liaison Representative (Section 2.3) has been removed since this role
   is not used in practice.
4. Clarification was added in section on "Liaison Communication" (now 2.3; was 2.4) that informal
   channels are preferred, with and without a formal liaison relationship, and further
   that liaison statements have no "special standing" in the IETF process.
5. Section on Summary of IETF Liaison Manager Responsibilities was reworked.
6. Section 4 on "Approval and Transmission of Liaison Statements" has been moved to 4053bis.
8. The description of both the aspects and requirements for establishing a
   formal relationship ws improved.
9. Text was addded to clarify there are no specific establishment procedures for informal
   collaboration and formal liaison communications in form of liaison statement
   don't require a formal liaison relationship
8. Update was made of the description of aspects for establishing a formal relationship and clarifications
   about informal collaborations
10. Liaison manager responsibilities sections was merged
10. One level in the dcoument structure was removed
11. Section on "Liaison Communication" was moved into a subsection of "Establishing a Liaison Relationship" and some redundant text was merged
12. Wording was aligned to consistently use “formal liaison relationship”
13. Small clarification was added that the appointment of a liaison manager establishes the formal relationship



# Establishing Formal Liaison Relationships {#relationship}

There is no set process or form for establishing a formal liaison relationship;
the IETF participants and the peer organization can initiate a conversation with
the IAB, and after discussion may come to an agreement to form the formal liaison relationship.
Once the IAB and the other organization mutually agree that a formal liaison
relationship is beneficial, the IAB appoints a liaison manager to establish it.
In some cases, the intended scope and guidelines for the collaboration are documented
specifically (e.g., see {{?RFC3113}}, {{?RFC3563}} , {{?RFC3718}}, {{?RFC4965}},
{{?RFC4965}}, {{?RFC6756}}, and {{?RFC7241}}).

## IETF's Preference for Informal Collaboration

Generally informal collaboration between the IETF and peer
organizations is preferred whenever direct working
relationships between the members of both organizations is possible.
Specifically, there are no processes in the IETF that require a formal
liaison relationship as our work is conducted in open public meetings and on
mailing lists where anyone can contribute.
Inputs from all participants in the IETF, regardless of the type of relationship,
are given equal weight and standing.  When a similar structure exists in the peer
organization and all participants have access to open working documents and
communication mechanisms, there may not be a need for a more formal
structure.

There is no specific procedure to enable informal collaboration.
Such an working relationship simply exists by defacto when members of both organizations
cross-collaborate and participate in the groups with overlapping
interest.

## Purposes and Expectations for Formal Liaison Relationships

From the IETF's perspective a formal liaison relationship is needed only when required for specific
purposes, such as:

1. There is an overlap in work between one or more groups in each organization that requires close
   collaboration that would not be possible without a formal liaison relationship.
   This might include situations where one group in one organization has a dependency on a document produced in the other
   organization and is requesting in-depth support or would like feedback on internal documents. However note that the agreed need
   for close collaboration is a pre-condition for establishing a formal liaison relationship but is not alone sufficient for the IETF
   to require the establishment of a formal liaison relationship.

2. The peer organization of the IETF may require a more formal communication structure in order to
   allow the IETF to work directly within the peer organization's processes.
   Some potential formal requirements from the peer organizations include:
   - Access restrictions for accessing the peer organization's working documents or standards.
   - Ability to participate and contribute directly in the peer organization's groups and forums.
   - Ability to participate in and contribute to the ongoing work of the peer organization.

In setting up a formal liaison relationship, the IAB expects that there will be a
mutual exchange of views and discussion of the best approach for
undertaking new standardization work items.  Any work items resulting
for the IETF will be undertaken using the usual IETF procedures, defined
in {{!BCP9}}.  The peer organization often has different organizational
structures and procedures than the IETF, and these differences
will require some flexibility on the part of both organizations to accommodate.
There is an expectation that both organizations will use the formal liaison relationship
appropriately, allowing sufficient time for the requests they make on
the other organization to be processed.

## Liaison Communications {#communication}

Communications between organizations use a variety of formal and informal
channels irrespective of established relationships. The stated
preference of the IETF, which is largely an informal organization, is to
use informal channels (e.g., discussion on expert level in a specific working
group meeting or mailing list), as these have integrated better into IETF
process and historically worked well to expedite matters. In some cases,
however, a more formal communication is appropriate, either as an adjunct
to the informal channel or in its own place with or without a formal liaison
relationship. In the case of formal communications, the established
procedures of many organizations produce a "liaison statement" (LS).
Procedures for sending, managing, and responding to liaison statements are
discussed in {{?I-D.iab-rfc4053bis}}.

Liaison statements can be sent without establishing a formal liaison relationship,
if formal communication is desired.
In this case, since a formal liaison manager
does not exist, the IAB itself will be responsible for ensuring
liaison statements are handled appropriately, as also further explained in
{{?I-D.iab-rfc4053bis}}.

Note that communications between organizations have no impact on
any other IETF contributions, and should follow the same IETF process and
policies and should be open to everyone for inputs and contributions, e.g.,
input discussion in a specific working group in the IETF.

# Liaison Manager Responsibilities and Expectations {#manager}

The main responsibility of the liaison manager is to ensure good,
productive, and timely (formal and informal) communication between the organizations.
This often includes:

- Ensure received liaison statements are recorded and delivered to the relevant groups.
- Ensure replies are sent in time or it is appropriately communicated why a reply
  is delayed or not sent.
- Ensure liaison statements from the IETF adhere to the formal requirements of the
  peer organization (e.g. structure/formatting) and are delivered to the appropriate groups.
  If a communication from a peer organization is addressed to an
  inappropriate party, such as being sent directly to the WG but not recorded otherwise
  or being sent to the wrong WG, the liaison manager
  will help redirect or otherwise augment the communication.
- Provide additional communication regarding e.g. process or known consensus positions in
  the IETF. This may also require participation in relevant meetings of the peer
  organization and potentially report back to the appropriate IETF organization any
  material information that is intended to be shared by the peer organization.

Formal messages from the IETF to the peer organization are usually carried in liaison
statements. The liaison manager must not send liaison statements on their own initiative to a
liaised organization on behalf of IETF, or any of its areas and
working groups.

IETF liaison managers should also communicate and coordinate with
other liaison managers where concerned technical activities overlap.

Liaison managers also provide updates to the IAB on technical matters, especially
if concerns regarding technical overlap or incorrectness are detected. However,
given that most organizations are quite large, it is not expected that the liaison
manager needs to have a complete overview of everything that is going on there.

## Speaking for the IETF

In certain situations, the liaison manager may carry additional messages for
providing further context. For such additional communication, liaison managers
may use any applicable businesslike approach, from
private to public communications, and bring in other parties as needed.
However, the mandate for IETF liaison managers is strictly limited to
conveying IETF consensus to the liaised organization.
The liaison manager speaks on behalf of the IETF on
the subject matter of the liaison, but only after making sure that
the IETF consensus is understood. Specifically,
if these communications aim to "represent the IETF",
they must have consensus, e.g. by being based on an RFC or some other formal statement
by a group within the IETF.

# Security Considerations

The security of the Internet is enhanced by robust coordination between SDOs.

# IANA Considerations

This document has no IANA actions.

# Appendix A: Document Process

RFC 4052 was published as a BCP. Since the IAB cannot publish BCPs, this document will follow a two step process. The current draft is marked as Informational until the IAB completes its process and formally approves it. After IAB approval, a member of the IESG needs to sponsor the document, and the document will enter the IETF process to update its intended status to BCP. This appendix should be removed at the time of publication.

--- back

# Acknowledgments
{:numbered="false"}

{{?RFC4052}} was authored by Leslie Daigle and developed as part of a conversation regarding the
management of {{?RFC4053}}, and the authors of {{?RFC4053}} contributed
significantly to it as well.

This version of the document is based on {{?RFC4052}} and brings it in line with currently followed
procedures. The authors would like to thank Leslie Daigle, Roman Danyliw, Dhruv Dhody, Joel Halpern, Wes Hardaker,
and Warren Kumari for their valuable comments and suggestions to improve this document.

