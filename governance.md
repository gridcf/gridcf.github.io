
[GridCF Community Governance](#gridcf-community-governance)
===========================================================

The GridCF is a nexus point for supporting core software packages in grid computing.

However, support is not just the technical quantities of the software package but also
the quality of the community surrounding it.  This governance document is the agreed-upon
standards and practices for the GridCF.

The GridCF is not a legal entity; it is meant to be a lightweight forum.  We aim to have
this governance document be corresponding lightweight, providing advice on how to move
forward with our goals but not to serve as a legal document.

[Contributions and Community Participation](#contributions-and-community-participation)
---------------------------------------------------------------------------------------

We aim to be a welcoming community; all contributors are expected to abide by the [contributor
code of conduct](http://contributor-covenant.org/version/1/4).

[Standards and Practices](#standards-and-practices)
---------------------------------------------------

To encourage code contributions, we aim to aggressively invite technically adept individuals to
help maintain the code base.  All contributions should follow the GitHub pull request workflow.
To merge code, the pull request must have at least one approved code review from a project member
and no disapprovals from project members.

All software maintained by the GridCF is expected to rely on continuous integration and any new
code should not be merged if build is broken.  Project members should use their best judgement
when overriding the CI results.

No overwriting of branch history or tags is allowed except through [project management committee](#project-management-committee) vote.

Any project member may prepare a release candidate for a new version of the toolkit and call for
a release vote.  If the release vote passes, the release is considered complete once the corresponding
version tag has been pushed to the repository.  Any tag without a corresponding release vote is
considered a candidate.

[Project Management Committee (PMC)](#project-management-committee-pmc)
-----------------------------------------------------------------------

Project managers serve as a special custodians of the community forum, making significant decisions
for the forum, such as adding new members, changing the governance, or disbanding the forum itself.

The PMC's decision process is based on voting; each PMC member recieves one vote.  To hold a vote:

- A vote must be proposed by a community member.
- The vote must be opened for at least 48 hours; 24 of those hours must occur between Monday and Friday (GMT).
- At the end of the vote, the results must be posted on a public mailing list.

The mechanism for collecting votes is left up to the PMC.  For a vote to pass (and a decision to be approved), we require:

1. Three fourths of the participants to vote in favor.
2. One half of the project management committee to participate.

A special case is the release vote -- in such a case, only a majority of participants need to vote in favor and a minimum of two PMC members must participate.

In addition to releases, activities that require a vote include:

- Adding or removing members from the PMC.  A PMC member may decide to leave at any time.
- Adopting a new code base into the GridCF.
- Adding or removing a community member from the list of committers.
- Removing a member from the community.
- Changing the governance document.
- Disbanding the GridCF.

[PMC members](#pmc-members)
---------------------------

As of 12 March 2021, these are the current members for the PMC:

- Jim Basney
- Mattias Ellert
- Maarten Litmaath
- Brian Lin
- Mischa Salle
- Frank Scheiner
- Matthew Viljoen
