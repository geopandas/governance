# GeoPandas Project Governance

## Summary

GeoPandas is a community-owned and community-run project. To the maximum extent
possible, decisions about project direction are made by community consensus.
Some members of the community additionally contribute by serving as [GeoPandas
Project Maintainers](#project-maintainers), where they are responsible for
facilitating the everyday activities of the project, or on the
[GeoPandas Steering Council](#steering-council), where they are
responsible for facilitating the establishment of community consensus, for
stewarding project resources, and – in extreme cases – for making project
decisions if the normal community-based process breaks down.

## The Project

The GeoPandas Project (The Project) is an open source software project
affiliated with the 501(c)3 [NumFOCUS Foundation](https://numfocus.org/).
The primary goal of The Project is to develop support for geospatial data in
[Pandas](https://pandas.pydata.org/) objects. Software developed by The Project
is released under the BSD (or similar) open source license, developed openly,
and hosted on public GitHub repositories under the
[GeoPandas GitHub organization](https://github.com/geopandas).
In addition to the main [GeoPandas repository](https://github.com/geopandas/geopandas),
the GeoPandas project includes subprojects focused on geospatial I/O, geospatial
data exploration and visualization, and parallelized geospatial computations.

The Project is developed by a team of distributed Contributors. Contributors are
individuals who have contributed code, participated in GitHub Issues, Pull
Requests, and Discussions, or provided community help/building, education,
outreach, and other activities that benefit the Project and the Community.
Anyone can be a Contributor, and contributors can be affiliated with any legal
entity or none.

The Project Community consists of all Contributors and Users of The Project.
Contributors work on behalf of and are responsible to the larger Project
Community and we strive to keep the barrier between Contributors and Users as
low as possible.

Anyone can participate in The Project by submitting, reviewing, and offering
feedback on GitHub Issues, Pull Requests, and/or Discussions, or by
communicating through the Gitter chat room, mailing lists, and other channels.
All members of the Community are welcome to participate in regular GeoPandas
Community Meetings that occur online on a monthly basis. The schedule and
archive of meeting notes are available within the [GeoPandas Community
repository](https://github.com/geopandas/community).

Participation in The Project follows the
[GeoPandas Project Code of Conduct](./CodeOfConduct.md),
which ensures that members of the Community treat each other with respect,
provide an environment that welcomes participation, and provides a mechanism for
reporting and enforcing violations.

The Project is integrated within the larger Python data science and geospatial
communities, and project Contributors are often involved in the ongoing
maintenance, expansion, and creation of software projects within the
broader ecosystem.

## Governance

The foundations of Project governance are:

-   Openness and transparency
-   Active contribution
-   Institutional neutrality

### Consensus-based decision-making by the community

Normally, project decisions will be made by consensus of all interested
Contributors. The primary goal of this approach is to ensure that the people who
are most affected by and/or involved in any given change can contribute their
knowledge in the confidence that their perspective will be acknowledged.
Thoughtful review from a broad community is the best mechanism we know of for
creating high-quality software.

In this context, consensus does not require:

-   that we solicit everybody's opinion on every change
-   that we ever hold a vote on anything
-   that everybody is happy or agrees with every decision

Consensus means that we entrust everyone with the right to veto any change if
they feel it necessary.

To achieve consensus, we use a combination of best judgment and best efforts:

-   A simple and uncontroversial bug fix posted on GitHub and reviewed by a core
    developer is probably fine.
-   Substantive or controversial API changes may involve one or more GitHub
    issues, Pull Requests, or Discussions that are open for longer periods of
    time to provide greater opportunity for feedback from the Community and may
    specifically solicit feedback from targeted members of the Community.

We expect that anyone who cares enough about The Project will raise their
concerns or express their formal veto within one of these channels within a
reasonably short period of time (up to a few weeks). If no major unresolved
concerns exist after a period of time appropriate for the scope of the change,
we will assume that consensus has been reached. If we find that a given change
is more controversial than expected or a critical input is delayed because
someone was unavailable, we can back out or further modify those changes based
on the additional feedback.

If necessary, a formal veto should consist of:

-   an unambiguous statement that a veto is being invoked
-   an explanation of why it is being invoked
-   a description of what conditions (if any) would convince the vetoer to
    withdraw their veto

We expect that most people will take this responsibility seriously and only
invoke their veto when they judge that a serious problem is being ignored and
that their veto is necessary to protect The Project. We expect such vetoes to be
rare in practice because Contributors are motivated from the start to find some
solution that everyone can live with.

If all proposals for resolving some issue are vetoed, then the status quo wins
by default. In the worst case, if a Contributor is genuinely misusing their veto
in an obstructive fashion to the detriment of the project, then they can be
ejected from the project by consensus of the Steering Council – see below.

For more information about the overall approach we use to achieve consensus, we
highly recommend that all Contributors additionally read
[Chapter 4: Social and Political Infrastructure](http://producingoss.com/en/producingoss.html#social-infrastructure)
of Karl Fogel's classic Producing Open Source Software, and in particular the
section on
[Consensus-based Democracy](http://producingoss.com/en/producingoss.html#consensus-democracy),
for a more detailed discussion.

### Project Maintainers

Project Maintainers are Project Contributors that have shown that they are
dedicated to the ongoing development of the project through active engagement
with the Community and facilitation of everyday Project activities. Maintainers
are typically granted write access to one or more repositories within The
Project, provide feedback on Github Issues and Discussions, review and merge
Pull Requests, participate in monthly Community Meetings (which are open to all
community members), vote on Steering Council members, and may be actively
involved in setting the overall direction of the project. Project Maintainers
are nominated by other Project Maintainers by sending a notification to the
Project Maintainer's private mailing list. Other Project Maintainers will have a
period of at least two weeks in which to veto a nomination; otherwise, the
nominee shall become a Project Maintainer. No voting is necessary for selecting
Project Maintainers.

Project Maintainers who have not actively contributed to The Project for a
period of 12 months will be asked if they wish to resign their write access and
voting rights until they become active again.

Project Maintainers may have their write access and voting rights revoked by the
Steering Council if they are deemed to be actively harmful to The Project's
well-being, and attempts at communication and conflict resolution have failed.
Depending on the nature of the conflict, if any, the Code of Conduct
Subcommittee may be involved in conflict resolution or specifically recommend
revoking a Maintainer's write access and voting rights.

Current and retired Project Maintainers will be
[listed by subproject](./membership/Maintainers.md).

To the maximum extent possible, the communications and activities of Project
Maintainers are conducted publicly within the channels described above. Project
Maintainers will have a private mailing list that may be used for topics that
are sensitive in nature, such as the nomination of new Project Maintainers, or
time-sensitive topics, such as grant application deadlines of interest to the
Community, or to start initial work on project-related materials before opening
those more broadly for input within the GeoPandas community. These topics and
materials are then typically discussed and distributed as part of the monthly
development meetings or related communication activities.

In general, Pull Requests should be approved by at least one maintainer that did
not submit the Pull Request, but are not required for especially small or
trivial changes such as typo fixes.

### Steering Council

The Project will have a Steering Council that consists of Project Contributors
who have produced contributions that are substantial in quality and quantity and
sustained over a period of time sufficient to demonstrate their understanding of
the needs of the project and community. The overall role of the Council is to
ensure – with input from the Community – the long-term well-being of the
project, both technically and as a community.

Council Members participate in everyday project activities, including
discussions and code review, as peers with all other Contributors and the
Community. Council Members do not have any special power or privilege through
their membership on the Council when participating in these everyday activities.
However, it is expected that because of the quality and quantity of their
contributions and their expert knowledge of the Project, Council Members will
provide useful guidance, both technical and in terms of project direction, to
potentially less experienced Contributors.

If necessary, The Steering Council may:

-   make decisions about the overall scope, vision, and direction of the project
-   make decisions about strategic collaborations with other organizations or
    individuals
-   make decisions about specific technical issues, features, bugs, and Pull
    Requests
-   make decisions when regular community discussion doesn't produce consensus
    on an issue in a reasonable time frame
-   update policy documents such as this one

However, the Council's primary responsibility is to facilitate the ordinary
community-based decision-making procedure described above. If we ever have to
step in and formally override the Community for the health of the Project, then
we will do so, but we will consider reaching this point to indicate a failure in
our leadership.

#### Council Membership

The Steering Council is composed of up to 5 Members that serve for 2-year terms.
Council Members are nominated by Project Maintainers or themselves. Project
Maintainers will vote on nominees during a voting period of at least one week
that is announced sufficiently far in advance (e.g., 1 month) to ensure that all
Project Maintainers that wish to vote are able to do so. No quorum of Project
Maintainers is necessary for this voting process.

The Council will be initially formed from the set of existing Project
Maintainers who, as of mid-2022, have been significantly active over the last
year.

To become eligible to join the Steering Council, an individual must be a Project
Contributor who has produced contributions that are substantial in quality and
quantity, and sustained over a period of time sufficient to demonstrate their
understanding of the needs of the project and community. These contributions may
include, but are not limited to code, code review, participation in GitHub
Issues, Pull Requests, and Discussions, community help/building, education,
outreach, and other activities that benefit the Project and the Community. We
want to encourage a diverse array of backgrounds, talents, and perspectives on
the Council, which is why we explicitly do not define code or code-related
metrics as the sole metric on which Council membership will be evaluated.

Any former Council member can be considered for membership again at any time in
the future, like any other Project Contributor; there is no maximum term length.

If a Council member becomes inactive in the project for a period of one year,
they will be considered for removal from the Council. Before removal, they will
be contacted to determine if they plan on returning to active participation. If
not, they will be removed immediately upon a vote of the remaining Council
members, and their vacancy will be filled in the process outlined above.

The Council reserves the right to eject current Members if they are deemed to be
actively harmful to The Project's well-being, and attempts at communication and
conflict resolution have failed. This requires the consensus of the remaining
Members.

Current and retired Steering Council Members will be listed on
[Steering Council Membership document](./membership/SteeringCouncil.md).

To the maximum extent possible, Council discussions and activities will be
public and done in collaboration and discussion with the Project Contributors
and Community. The Council will have a private mailing list that will be used
sparingly and only when a specific matter requires privacy. When private
communications and decisions are needed, the Council will do its best to
summarize those to the Community after eliding personal/private/sensitive
information that should not be posted to the public internet.

#### Conflict of Interest

It is expected that the Council Members will be employed at a wide range of
companies, universities, and non-profit organizations. Because of this, it is
possible that Members will have conflicts of interest. Such conflict of
interests include, but are not limited to:

-   financial interests, such as investments, employment, or contracting work,
    outside of The Project that may influence their work on The Project
-   access to proprietary information of their employer that could potentially
    leak into their work with The Project

All members of the Council shall disclose to the rest of the Council any
conflict of interest they may have. Members with a conflict of interest in a
particular issue may participate in Council discussions on that issue but must
recuse themselves from voting on the issue.

#### Subcommittees

The Council can create subcommittees that provide leadership and guidance for
specific aspects of the project. Subcommittees may include non-Council members
as appropriate. Like the Council as a whole, subcommittees should conduct their
business in an open and public manner unless privacy is specifically called for.
Private subcommittee communications should happen on the main private mailing
list of the Council unless specifically called for.

The Project shall have a Code of Conduct Subcommittee responsible for
maintaining the [GeoPandas Code of Conduct](CodeOfConduct.md), responding to
reports of Code of Conduct Violations, and enforcing Code of Conduct Violations.
This subcommittee shall not be entirely composed of Steering Council Members.
The members of the Code of Conduct Subcommittee shall be posted on the
[Code of Conduct Subcommittee Membership document](membership/CodeOfConductSubcommittee.md).

## Changing the Governance Documents

We anticipate that changes to these Governance documents will be rare and will
warrant careful consideration, except in the case of typos or minor language
errors.

Any member of the Community may suggest a change to these Governance documents
by opening a GitHub Issue or Pull Request on the GeoPandas Governance
repository. The Steering Council may elect not to pursue changes outlined in the
Issue or Pull Request and may close the issue with a brief explanation of that
choice.

The Steering Council may solicit input from the person that initially raised the
Issue or Pull Request and/or other members of the Community.

Members of the Steering Council then approve or veto the final version of the
Pull Request. Once approved, the Pull Request will be merged and the updated
Governance documents will be posted publicly within this repository.

## Acknowledgements

Text adapted from [Jupyter](https://jupyter.org/governance/governance.html),
[NumPy](https://numpy.org/doc/stable/dev/governance/governance.html), and
[Pandas](https://github.com/pandas-dev/pandas-governance/blob/master/governance.md)
projects and modified by the GeoPandas Project. We are grateful to those
projects for contributing these materials under open licensing terms for us to
easily reuse.

## License

To the extent possible under law, the authors have waived all copyright and
related or neighboring rights to this document, as per the
[Creative Commons Public Domain Dedication](https://creativecommons.org/publicdomain/zero/1.0/)
license.
