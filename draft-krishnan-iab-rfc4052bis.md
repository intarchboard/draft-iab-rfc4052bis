---
title: "IAB Processes for Management of IETF Liaison Relationships"
abbrev: "IAB Liaison Management"
category: info

docname: draft-krishnan-iab-rfc4052bis-latest
submissiontype: IAB
obsoletes: 4052
date:
v: 3
venue:
  group: "Internet Architecture Board"
  type: "Internet Engineering Task Force"
  mail: "iab@iab.org"
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
liaison relationships.


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
relationships are generically referred to as "liaison relationships".

In such cases, a person is designated by the IAB to manage a given
liaison relationship; that person is generally called the "IETF
liaison manager" to the other organization. Often,
the other organization will similarly designate their own liaison
manager to the IETF.

This document is chiefly concerned with:

- the establishment and maintenance of liaison relationships, and
- the appointment and responsibilities of IETF liaison managers.

The management of other organizations' liaison managers to the IETF,
whether or not in the context of a liaison relationship, is outside
the scope of this document.

The IETF has chartered the Internet Architecture Board to manage
the formal liaison relationships.  Consistent with its charter {{!BCP39}},
the IAB acts as representative of the interests of the IETF
in technical liaison relationships with other organizations
concerned with standards, and other technical and organizational
issues relevant to the worldwide Internet.  Liaison relationships are
kept informal whenever possible, and must possess demonstrable value to the
IETF's technical mandate.  Individual participants from the IETF community are
appointed as liaison managers to other organizations by the IAB.

In general, a liaison relationship is most valuable when there are
areas of technical development of mutual interest. For the most
part, SDOs would rather leverage existing work done by other
organizations than recreate it themselves (and would like the same
done with respect to their own work).  Establishing a liaison
relationship can provide the framework for ongoing communications to

- prevent inadvertent duplication of effort, without obstructing
  either organization from pursuing its own mandate;
- provide authoritative information of one organization's
  dependencies on the other's work.

It is important to note that participation in the IETF work is open to everyone,
and all the working documents and RFCs are freely available to everyone without
the need for a formal liaison relationship. Hence, in almost all cases the need
for a formal relationship is mostly driven by other organizations rather than by
the IETF.

## Changes compared to RFC4052

This version of the document contains the following updates:

1. Notes in the Introduction and Section 2.1 on "Liaison Relationships" that the
   IETF process itself does not require a formal liaison relationship, e.g. for
   document access or meeting participation, and therefore the need for a formal
   liaison relationship is often driven by processes of the peer organization.
2. Statement that the "IAB acts as representative of the interests of \[..] the
   Internet Society" has been removed.
3. Role of the Liaison Representative (Section 2.3) has been removed since this role
   is not used in practice.
4. Clarification in section on "Liaison Communication" (now 2.3; was 2.4) that informal
   channels are preferred, with and without a formal liaison relationship, and further
   that liaison statements have no "special standing" in the IETF process.
5. Section on Summary of IETF Liaison Manager Responsibilities reworked.
6. Section 4 on "Approval and Transmission of Liaison Statements" has been moved to 4053bis.
7. Description of formal and informal relationships.
8. Better description of both the aspects of requirements for establishing a
   formal relationship
9. Clarified there are no specific establishment procedures for informal
   relationships and described handling of liaison communications that don't have a
   formal relationship.
     
# Aspects of Liaisons and Liaison Management

The IETF communicates with other organizations (such as other SDOs)
through two different types of relationships: Formal Liaison
Relationships {{formal}} and Informal Relationships {{informal}}.
The type of relationship needed depends on the resources that groups within each
organization (for example ,"Working Groups" in the IETF) require in order to communicate
and collaborate effectively.

## Formal Liaison Relationships {#formal}

A formal liaison relationship is established between the IETF and
another organization when it is mutually agreeable and beneficial to do so.  From the
IETF's perspective this is needed only when required for specific
purposes.
However, there might be formal requirements from the
peer organization to enable collaboration within the peer
organization's processes.

The IAB uses two different aspects when it considers whether or not to establish a formal relationship with a peer organization.
The first aspect deals with the level of collaboration needed,
and the second deals with any restrictive nature of communication that impedes open collaboration.

a) There is an overlap in work between one or more groups in each organization that requires close
   collaboration that would not be possible without a formal relationship.
   This might include situations where one group in one organization has a dependency on a document produced in the other
   organization and is requesting in-depth support or would like feedback on internal documents. However note that the agreeded need
   for close collaboration is a pre-condition for establishing a formal liaison relationship but is not alone sufficient for the IETF
   to require the establishment of a formal liaison relationship.

b) The peer organization of the IETF may require a more formal communication structure in order to
   allow the IETF to work directly within the peer organization's processes.
   Some potential formal requirements from the peer organizations include:

    - Access restrictions for accessing the peer organization's working documents or standards.
    - Ability to participate and contribute directly in the peer organization's groups and forums.
    - Ability to participate in and contribute to the ongoing work of the peer organization.

Without the combination of both the need and the requirements for a formal liaison relationship,
the IETF will collaborate with the peer organization in an informal relationship ({{informal}}).

There is no set process or form for establishing a formal liaison relationship;
the IETF participants and the peer organization can initiate a conversation with
the IAB, and after discussion may come to an agreement to form the relationship.
In some cases, the intended scope and guidelines for the collaboration are documented
specifically (e.g., see {{?RFC3113}}, {{?RFC3131}}, and {{?RFC3356}}).

In setting up a formal liaison relationship, the IAB expects that there will be a
mutual exchange of views and discussion of the best approach for
undertaking new standardization work items.  Any work items resulting
for the IETF will be undertaken using the usual IETF procedures, defined
in {{!BCP9}}.  The peer organization often has different organizational
structures and procedures than the IETF, and these differences
will require some flexibility on the part of both organizations to accommodate.
There is an expectation that both organizations will use the relationship
carefully, allowing sufficient time for the requests they make on
the other organization to be processed.

## Informal Relationships {#informal}

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

There is no specific procedure for establishing an informal relationship, as
one exists by defacto when members of both organizations simply
cross-collaborate and participate in the groups with overlapping
interest.

Note that formal communications in the form of liaison statements, if needed,
can be used without establishing a formal liaison relationship.
In this case, since a formal liaison manager
does not exist, the IAB itself will be responsible for ensuring
liaison statements are handled appropriately.

## Liaison Manager

### Speaking for the IETF

The mandate for IETF liaison managers is strictly limited to
conveying IETF consensus to the liaised organization.  The liaison
manager must not send liaison statements on their own initiative to a
liaised organization on behalf of IETF, or any of its areas and
working groups. The liaison manager speaks on behalf of the IETF on
the subject matter of the liaison, but only after making sure that
the IETF consensus is understood.

### Main Function of the Liaison manager

As described above, most work on mutually interesting topics will be
carried out in the usual way within the IETF and the peer
organization.  Therefore, most communications will be informal in
nature (for example, Working Group (WG) or mailing list discussions).

An important function of the liaison manager is to ensure that
communication is maintained, productive, and timely.  He or she may
use any applicable businesslike approach, from private to public
communications, and bring in other parties as needed.  If a
communication from a peer organization is addressed to an
inappropriate party, such as being sent to the WG but not copying the
Area Director (AD) or being sent to the wrong WG, the liaison manager
will help redirect or otherwise augment the communication.

Since the IAB is ultimately responsible for liaison relationships,
anyone who has a problem with a relationship (whether an IETF
participant or a person from the peer organization) should first
consult the IAB's designated liaison manager, and if that does not
result in a satisfactory outcome, the IAB itself.

IETF liaison managers should also communicate and coordinate with
other liaison managers where concerned technical activities overlap.

## Liaison Communications

Communications between organizations use a variety of formal and informal
channels irrespective of established liaison relationships. The stated
preference of the IETF, which is largely an informal organization, is to
use informal channels (e.g., discussion on expert level in specific Working
group Meeting or mailing list), as these have integrated better into IETF
process and historically worked well to expedite matters. In some cases,
however, a more formal communication is appropriate, either as an adjunct
to the informal channel or in its own place with or without liaison
relationship. In the case of formal communications, the established
procedures of many organizations use a form known as a "liaison statement".
Procedures for sending, managing, and responding to liaison statements are
discussed in {{?RFC4053}}.

Note that communications between organizations have no difference to
any other IETF contributions and should follow the same IETF process and
polices and should be open to everyone for inputs and contributions, e.g.,
input discussion in specific working group in the IETF.

# Summary of IETF Liaison Manager Responsibilities

The main responsibility of the liaison manager is to ensure good and formally
correct communication between the organizations. This often includes:

- Ensure received liaison statements are recorded and delivered to the relevant groups.
- Ensure replies are sent in time or it is appropriately communicated why a reply
  is delayed or not sent.
- Ensure liaison statements from the IETF adhere to the formal requirements of the
  peer organization (e.g. formatting) and are delivered to the appropriate groups.
- Provide additional communication on e.g. process or known consensus positions in
  the IETF. This may also require participation in relevant meetings of the peer
  organization and potentially report back to the appropriate IETF organization any
  material information that is intended to be shared by the peer organization.

Formal messages from the IETF to the peer organization are usually carried in liaison
statements. In certain situations, the liaison manager may carry additional messages, when
specifically instructed. However, if these communications aim to "represent the IETF",
they must have consensus, e.g. by being based on an RFC or some other formal statement
by a group within the IETF.

Optionally liaison manager may provide updates to the IAB on technical matters. Especially
if a concern e.g. regarding technical overlap or incorrectness is detected this should be
communicated to the IAB. However, given most organization are quite large, it is not expected
that the liaison manager can have the full overview about everything that is going on.

# Security Considerations

The security of the Internet is not threatened by these procedures.


# IANA Considerations

This document has no IANA actions.


--- back

# Acknowledgments
{:numbered="false"}

{{?RFC4052}} was authored by Leslie Daigle and developed as part of a conversation regarding the
management of {{?RFC4053}}, and the authors of {{?RFC4053}} contributed
significantly to it as well.

This version of the document is based on {{?RFC4052}} and brings it in line with currently followed
procedures. Further updates to all parts of the text are expected in the process of gathering
community feedback for this document.

