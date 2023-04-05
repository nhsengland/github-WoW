## Github - Ways of Working

Collection of documentation to support ways of working for our Github Organisation.  See [Github's documentation](https://docs.github.com/en) for most questions realting to the technical aspects of github - here we focus on applying these for our orgasniation. Please add to [open issues](https://github.com/nhsengland/github-WoW/issues) suggestions.

[![status: active](https://github.com/GIScience/badges/raw/master/status/active.svg)](https://github.com/GIScience/badges#active)

### Open Source Policy

See the draft NHS [Open Source Policy](https://github.com/nhsx/open-source-policy/blob/main/open-source-policy.md#e-assurance-requirements) here.  This document discusses the What, When and How of open source code.

### Repository Contents

The three main files are held in 'docs'. 
- REPO_WoW.md
- TEAM_WoW.md
- ORG_WoW.md
These set out ways of working for repo owners, team maintainers and organisation owners.

Alongside these are example OPEN_CODE_CHECKLIST.md, and Escalation.md

### Github - How we use it

It is important to be aware of best practice when using github and making open code.  However, not every use-case requires all the suggested components and thus best practice needs to be balanced with pragmatism.  Here are a few example incremental use cases, however in reality each use-case needs to be considered individually by the developer. 

- **Use Case 1: Individual Exploration / Training** 
To try out a new technique, piece of code or training for personal/team development.   Repo fully controlled by member with publication trusted to the member.   These projects would not be updated, managed or monitored but would expect to be clearly described and labelled to inform that this work is exploratory.  Main aim is to give the member flexibility to trial work and share examples easily.  \
**Scrutiny required -** Only public or fake data used in public repos.  Possible use of simple io template or link to google collab to present visualisation and learning.  For this use case we need to focus on NHS values, ensuring no information is released that should remain closed and project level assignment.

- **Use Case 2: Internal Code Sharing** 
To try out a new technique, piece of code or training for personal/team development.  Additionally, use of real world data and sharing across the team for demonstrating/prototyping and learning.    Members need to be able to quickly share the code, but as this has been run against possibly sensitive data, no public, no public sharing is expected.  If the project is to progress to a managed or public element then a migration to a new repo is expected. \
**Scrutiny required -** This code may have been run against sensitive data and elements of that might have been embedded in the code or files, and so Private repos are necessary with a clear review process if there is a desire to make the repo public at a later stage.  For this use case we need to focus all the points from use case 1 and that the readme is clear and that the repo is stored in the organisation github rather than a personal one.

- **Use Case 3: Pre-release Code Sharing** 
To develop a piece of work towards open sharing but which requires testing before release.  Members need quick access to allow for the interactive development.  Expectation on applying best practice from the beginning where possible but use of non-sensitive data protects the repo if later published.  Migration to a fully monitored pipeline before sensitive data brought in. \
**Scrutiny required -** Non-sensitive, public or fake data used.  Private repo with intension of eventually moving to use case 4: external code sharing and so time needs to be spent on best practice at this stage.  For this use case we need to focus all the points from use case 1 and 2 and clear contribution guidelines, license and any regulatory requirements checked.

- **Use Case 4: External Code Sharing** 
To provide a hosted code for Proof of Concepts, Alpha, Beta versions of small projects or training/demonstration resources.  Usage of non-sensitive data allows member to publish without full sign-off.  Main aim is collaboration and so clarity and best practice expected.  Repo would be lightly managed (monitored but not updated regularly). \
**Scrutiny required -** Non-senstive, public or fake data so a public repo with example notebooks would be acceptable.  For this use case we need to focus on all best practice and ensuring we are creating safe, useable code.

- **Use Case 5: Public Hosting of Proof of Concept** 
To host analysis on a server for others to interact with and use.  Purpose is to demonstrate, support and advertise.  Repo needs to be controlled and owned to support issues and users.  Relatively light touch as updates expected to be rare.  Needs connections to external apps with admin permissions.  Sign-off for publication required. \
**Scrutiny required -** Non-senstive, public or fake data.  Any sensitive data required would need to be behind a secure barrier in a corporately managed service.  A public repo attached to collaborative hosting services such as streamlit, RShiny, etc..  For this use case we need to focus on all best practice and ensuring we are creating safe, useable code

- **Use Case 6: Product Pipelines** 
To manage pipelines in a collaborative controlled environment.  Fully managed and monitored repos.  Version control with full branching strategy needed.  Purpose is to provide CI/CD environment.  For corporate tools this should be handled in Azure DevOps. \
**Scrutiny required -** Mix of public and sensitive data and so both public and private repos used for methods and config files respectively.   IO pages such as 'read the docs' used to describe work.  For this use case we need to focus on all best practice and ensuring we are creating safe, useable code

- **Use Case 7: Showcasing work** 
Use of github to build public facing website with technical non-sensitive projects and discussions.  As public facing content needs to be fully signed-off with updates properly managed.  Non-sensitive data used but as the space is used for showcasing then need to keep an eye on policy and comms breaches. \
**Scrutiny required -** Public or fake data only with public repo and IO site.  For this use case we need to focus on all best practice and ensuring we are creating safe, useable code


### License

Unless stated otherwise, the codebase is released under [the MIT Licence](https://opensource.org/licenses/MIT).
This covers both the codebase and any sample code in the documentation.

_See [LICENSE](./LICENSE) for more information._

The documentation is [© Crown copyright][copyright] and available under the terms
of the [Open Government 3.0][ogl] licence.

[mit]: LICENCE
[copyright]: http://www.nationalarchives.gov.uk/information-management/re-using-public-sector-information/uk-government-licensing-framework/crown-copyright/
[ogl]: http://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/

### Contact

To find out more about the [Digitial Analytics and Research Team](https://www.nhsx.nhs.uk/key-tools-and-info/nhsx-analytics-unit/) visit our [project website](https://nhsx.github.io/AnalyticsUnit/projects.html) or get in touch at [analytics-unit@nhsx.nhs.uk](mailto:analytics-unit@nhsx.nhs.uk).
