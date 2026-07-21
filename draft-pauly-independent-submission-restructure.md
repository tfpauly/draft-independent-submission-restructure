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
a small board appointed both by the IAB and IESG, that acts as the stream approver.
The ISB responsible for activities within the Independent Submission stream,
working with draft editors and reviewers, and interacts with the RFC Production Center
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

The structure of the ISB is intended to make it easier to find and appoint willing
volunteers. By sharing the work of shepherding documents on the Independent Submission stream,
each member of the ISB will have lesser responsibilities (time commitments, etc) as
compared to a single ISE.

Additionally, having an ISB composed of multiple members with staggered terms allows
for more continuity when appointees step down. This improves both sharing of
institutional knowledge and smooth processing of documents on the stream.

The ISB approves documents with a public, ballot-based record. This provides
transparency to the interested communities (both the IETF community and the broader
community of contributors to the Independent Submissions stream) about document
processing and approval rationale. The decision to approve or not also does not
depend on a single individual.

The appointment structure and conflict review process for the ISB intentionally
involves both the IESG and the IAB. The ISE model involved an appointment of
an individual by the IAB, but documents go through conflict review only with the
IESG {{!RFC5742}}.

RFCs published on the Independent Submission stream can be broadly grouped into:

- technical specifications that define protocols, register codepoints, etc., which
could potentially overlap with IETF work; and,
- broader informational documents that express opinions, architectural commentary,
humor, etc., which could potentially overlap with either IETF or IAB work.

ISB members are appointed by both the IESG and IAB, and the ISB requests conflicts
reviews from both the IESG and IAB when appropriate. This shares responsibility
for review of the Independent Submission stream more broadly. This is not intended
to reduce the independence of the stream in any way, but instead improve communication
and awareness across the streams where potential overlaps might exist.

# Independent Submission Board

Four members, two appointed by IAB, two appointed by IESG.

## Responsibilities

- Individuals on the ISB shepherd/are responsible for the documents
- May solicit reviews and run a team of people to help with reviews
- Run conflict reviews. All documents run conflict reviews with IESG {{RFC5742}}; ISB chooses which documents to run as conflict review with IAB.
- Approve documents, modelled on IESG document balloting. No more than one ABSTAIN/DISCUSS. Ballot comments are public.
- Select one member (or someone else) to serve on RSAB {{!RFC9920}}

- ISB determines its own meeting schedule for processing and approving documents.

- Maintaining technical quality of the Independent Submission stream.
- Reviewing, approving, and processing Independent Submissions.
- Forwarding draft RFCs in the Independent Submission stream to the RFC Production Center.
- Reviewing and approving RFC errata for Independent Submissions.
- Coordinating work and conforming to general RFC Series policies as specified by the IAB and RSE.
- Providing statistics and documentation as requested by the RSE and/or LLC.

## Appointments and Terms

- 2 appointed by IESG
- 2 appointed by IAB
- Should be generally knowledgable, but expected to be able to represent and help drive documents that would otherwise overlap with IETF work or IAB work

- 3 year terms. Can be reappointed up to 3 terms.
- Staggered start to terms (1 - IAB, 2 - IESG, 3 - IAB, 3 - IESG). Terms continue to cycle.

# Security Considerations

This document has no specific security implications, however the same security
considerations as those in {{!RFC9920}} apply.

# IANA Considerations

This document has no IANA actions.
