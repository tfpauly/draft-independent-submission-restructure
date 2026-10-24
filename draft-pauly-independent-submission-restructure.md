---
title: "Independent Submission Board Model"
abbrev: "IS Restructure"
category: info

docname: draft-pauly-independent-submission-restructure-latest
submissiontype: IAB
number:
date:
consensus: true
v: 3
# area: AREA
# workgroup: WG Working Group
keyword:
 - ISE
 - RFC
venue:
#  group: WG
#  type: Working Group
#  mail: WG@example.com
#  arch: https://example.com/WG
  github: "tfpauly/draft-independent-submission-restructure"
  latest: "https://tfpauly.github.io/draft-independent-submission-restructure/draft-pauly-independent-submission-restructure.html"

author:
 -
    fullname: Tommy Pauly
    email: tpauly.ietf@gmail.com

normative:

informative:

--- abstract

The Independent Submission stream is one of the stream producers that create draft RFCs.
This document proposes the creation of the Independent Submission Board (ISB),
a small board appointed by both the IAB and IESG, that acts as the stream approver.
The ISB is responsible for activities within the Independent Submission stream,
works with draft editors and reviewers, and interacts with the RFC Production Center
and Publisher, and the RFC Series Editor (RSE).

If approved, this proposal would obsolete RFC 8730, which defines a single
Independent Submission Editor.

--- middle

# Introduction

The RFC Editor Model {{!RFC8728}} defines a set of streams that produce draft RFCs,
which are submitted for publication. This document proposes the management function
for the Independent Submission stream, specifically the role of Independent Submission
Board (ISB).

The existing model for management of the Independent Submission stream defines
a single appointee, the Independent Submission Editor (ISE) as the manager of the
stream {{?RFC8730}}. This proposal would obsolete {{?RFC8730}} if approved.

## Motivation and Background

The model of a single ISE makes the Independent Submission stream unique amongst RFC streams
in having a single person responsible for approvals of documents within an RFC stream.
While the ISE can be supported by an Editorial Board for the purpose of advice
and reviews, the ISE is directly responsible for the processing and approvals of all
documents.

Additionally, the scope of documents for the Independent Submission stream is
quite open-ended, and the potential community of interested parties is very
large (including the IETF community and other communities and parties outside
the IETF community).

The ISE model does not define a visible process or record for how decisions are made.
When a single individual is responsible to an open-ended community for arbitrating
decisions of what should be published, inevitably there are members of the community
who will disagree with the decisions. In all other RFC streams, there are consensus-based
processes that ensure that no single individual is entrusted with the decisions for
publication. Placing this requirement on an individual is a burden to that individual
as well as a potential source of conflict for the community.

The structure of the ISB is intended to make it easier to find and appoint willing
volunteers who can share responsibilities and establish a process of consensus. By
sharing the work of shepherding documents on the Independent Submission stream,
each member of the ISB will have lesser responsibilities (time commitments, etc.) as
compared to a single ISE.

Additionally, having an ISB composed of multiple members with staggered terms allows
for more continuity when appointees step down. This improves both sharing of
institutional knowledge and smooth processing of documents on the stream.

The ISB approves documents with a public, ballot-based record. This provides
transparency to the interested communities (both the IETF community and the broader
community of contributors to the Independent Submission stream) about document
processing and approval rationale. The decision to approve or not also does not
depend on a single individual.

The appointment structure and conflict review process for the ISB intentionally
involves both the IESG and the IAB. The ISE model involved an appointment of
an individual by the IAB, but documents go through conflict review only with the
IESG {{!RFC5742}}.

RFCs published on the Independent Submission stream can be broadly grouped into:

- technical specifications that define protocols, register codepoints, etc., which
could potentially overlap with IETF work; and
- broader informational documents that express opinions, architectural commentary,
humor, etc., which could potentially overlap with either IETF or IAB work.

ISB members are appointed by both the IESG and IAB, and the ISB requests conflict
reviews from the IESG, as well as the IAB when appropriate. This shares responsibility
for review of the Independent Submission stream more broadly. This is not intended
to reduce the independence of the stream in any way, but instead improve communication
and awareness across the streams where potential overlaps might exist.

# Independent Submission Board

The Independent Submission Board (ISB) is composed of four members,
appointed by both the IAB and IESG (see {{appointment}} for details).

The ISB collectively is responsible for processing and approving
documents on the Independent Submission stream.

## Qualifications of Appointees

Appointees to the ISB are expected to have the following qualifications:

1. Technical competence, i.e., broad technical experience and perspective
across a wide range of Internet technologies and applications, and also
the ability to work effectively with portions of that spectrum in which
they have no personal expertise.
1. Thorough familiarity with the RFC series.
1. An ability to define and constitute advisory and document review
arrangements.
1. Good standing in the technical community, in and beyond the IETF.
1. Demonstrated editorial skills, good command of the English language,
and demonstrated history of being able to work effectively with technical
documents and materials created by others.
1. The ability to work effectively in a multi-actor environment with
divided authority and responsibility similar to that described in {{!RFC6635}}.

## Responsibilities

Members of the ISB share the following responsibilities:

- Maintaining technical quality of the Independent Submission stream.
- Reviewing, approving, and processing Independent Submissions. For
each document on the stream, the ISB selects one of its members
as the responsible ISB member to shepherd the document. The
responsible ISB member solicits reviews and helps coordinate
conflict reviews.
- Requesting conflict reviews from the IESG and IAB. All Independent
Submission documents need to run conflict reviews with the IESG, as
described in {{!RFC5742}}. For all documents that the ISB determines
to be relevant, it should also request conflict reviews from the IAB.
- Approving documents for publication on the Independent Submission stream.
Approval is handled similarly to IESG and IRSG balloting on documents,
where each ISB member indicates approval, no objection, or an abstain/discuss
opinion. In order to be approved, documents require at least three approvals
or no objection opinions (one of which must be an approval)
and no more than one abstain/discuss opinion. Ballots and associated
comments are publicly available.
- Forwarding approved draft RFCs in the Independent Submission stream
to the RFC Production Center.
- Selecting the RSAB representative {{!RFC9920}} for the Independent
Submission stream, which will likely be an ISB member, but can also
be another appointee.
- Reviewing and approving RFC errata for Independent Submissions.
- Coordinating work and conforming to general RFC Series policies as specified by the IAB and RSE.
- Providing statistics and documentation as requested by the RSE and/or LLC.

The ISB sets it own schedule for meetings and teleconferences, used
to discuss, process, and approve documents on the stream.

## Appointments and Terms {#appointment}

Of the four ISB members, two are appointed by the IAB, and two are appointed
by the IESG. The appointing bodies are expected to
appoint members based on the qualifications listed above, after calling
for community input.

Each appointment has a three-year term, which can be renewed up to a total
of three consecutive terms. Terms are staggered such that no more than two
appointments renew in the same year.

For the creation of the ISB, the lengths of the initial appointments will
be set up to start staggered renewal. Specifically, there will be a one-year
term appointed by the IAB, a two-year term appointed by the IESG, a
three-year term appointed by the IAB, and a three-year term appointed by
the IESG.

# Security Considerations

This document has no specific security implications, however the same security
considerations as those in {{!RFC9920}} apply.

# IANA Considerations

This document has no IANA actions.
