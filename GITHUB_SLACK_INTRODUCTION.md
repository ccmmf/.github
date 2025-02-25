# CCMMF GitHub and Slack Guide

## Table of Contents
- [Table of Contents](#table-of-contents)
- [Overview](#overview)
- [Quick Start Summary](#quick-start-summary)
- [Understanding GitHub for Collaboration](#understanding-github-for-collaboration)
	- [What is GitHub?](#what-is-github)
	- [Key Concepts](#key-concepts)
	- [Navigating Key CCMMF Repositories](#navigating-key-ccmmf-repositories)
- [Keeping Up To Date](#keeping-up-to-date)
	- [Watch Repositories Selectively](#watch-repositories-selectively)
	- [Email Filters](#email-filters)
	- [Navigating Repositories](#navigating-repositories)
	- [Milestones](#milestones)
- [Interactions](#interactions)
	- [GitHub Issues](#github-issues)
		- [Providing Feedback (Commenting)](#providing-feedback-commenting)
		- [Creating Issues](#creating-issues)
	- [Discussions](#discussions)
	- [Pull Requests (PRs)](#pull-requests-prs)
		- [How to Review a PR](#how-to-review-a-pr)
	- [Alerting Team Members](#alerting-team-members)
- [Notifications](#notifications)
- [Additional Resources and Support](#additional-resources-and-support)

## Overview

This document introduces GitHub and Slack as communication channels for the CCMMF community. Open science is a key feature of the CCMMF, and GitHub provides a number of features that support open science. In addition to serving as a platform for public, open-source code, it facilitates collaborative development and communication. For example, it provides the community with the ability to track progress, ask questions, provide feedback, and participate in discussions.

The focus of this document is on key GitHub features with CCMMF-specific context. We link to specific pages in [GitHub's own excellent documentation](https://docs.github.com) for additional details.

This guide will teach you how to:
- Track and review project progress in **CCMMF and PEcAn repositories**
- Create and manage **issues** to report concerns or ask questions
- Participate in **discussions** to share ideas and feedback
- Review **pull requests** and provide input
- Monitor **milestones** and project workflows
- Navigate and get notifications about key project repositories.

## Quick Start Summary

1. Review the CCMMF [Contributor Code Of Conduct](https://github.com/ccmmf/.github/blob/main/CODE_OF_CONDUCT.md).
1. **Sign up** for GitHub: [github.com/signup](https://github.com/signup).  
2. **Join** PEcAn Slack:  
   [Slack Invite Link](https://join.slack.com/t/pecanproject/shared_invite/enQtMzkyODUyMjQyNTgzLWEzOTM1ZjhmYWUxNzYwYzkxMWVlODAyZWQwYjliYzA0MDA0MjE4YmMyOTFhMjYyMjYzN2FjODE4N2Y4YWFhZmQ).  
3. **Watch** specific repos including [ccmmf/workflows](https://github.com/ccmmf/workflows), [ccmmf/organization](https://github.com/ccmmf/organization), and [pecanproject/sipnet](https://github.com/pecanproject/pecan/sipnet).  
4. Configure your **notifications** (GitHub-->watch-->custom, email filters, Slack).
5. Review project tasks and milestones in the [CCMMF Organization Repository](https://github.com/ccmmf/organization/milestones).
6. **Open an Issue** or start a **Discussion** for broader conversations. Tag specific CCMMF team members.
7. Or **Slack** the team for quick questions or updates. It is where many conversations start.

## Understanding GitHub for Collaboration

### What is GitHub?

GitHub is a web-based platform for **version control** and **collaboration**:
- Public GitHub activity for CCMMF is viewable by anyone, but a  
  [GitHub account](https://github.com/signup) is required to create or comment on issues.
- If you’re new to GitHub, or if you have questions not covered here, visit the  
  [GitHub Docs](https://docs.github.com/).
- For some conversations, it can be easiest to get started on the [PEcAn Project Slack](https://join.slack.com/t/pecanproject/shared_invite/enQtMzkyODUyMjQyNTgzLWEzOTM1ZjhmYWUxNzYwYzkxMWVlODAyZWQwYjliYzA0MDA0MjE4YmMyOTFhMjYyMjYzN2FjODE4N2Y4YWFhZmQ)

### Key Concepts

- **Repositories:** A repository is primarily a location to store project files, including code and documentation. This is also where you can find links to issues, discussions, pull requests,  and more.
- **Issues:** Can be used to request and discuss new features, ask questions, report bugs, and keep track of work progress - see [github.com/ccmmf/organization](https://github.com/ccmmf/organization/issues). 
- **[CCMMF Milestones](https://github.com/ccmmf/organization/milestones?direction=asc&sort=due_date&state=open):** group key issues into project phases and deliverables. 
- **Discussions:** Provide a place for open-ended and often higher level conversations and knowledge-sharing. This is a relatively new feature and many repositories use issues and Slack for this purpose. CCMMF has created a [single project level discussion board](https://github.com/orgs/ccmmf/discussions).
- **Pull Requests (PRs):** This is where users can propose and discuss specific changes to code and documentation. Code contributions are welcome, but beyond this document's scope.
### Navigating Key CCMMF Repositories

The **main repositories** relevant to the CCMMF project are:

- **CCMMF GitHub Homepage**: [github.com/ccmmf](https://github.com/ccmmf) 
	- **CCMMF 'Organization' Repository**: [github.com/ccmmf/organization](https://github.com/ccmmf/organization) tracking key project tasks in one place 
- **CCMMF Monitoring and Modeling Workflows**: [github.com/ccmmf/workflows](https://github.com/ccmmf/workflows)`
- **PEcAn Project Modeling Workflow Tools:** [github.com/pecanproject/pecan](https://github.com/pecanproject/pecan)
	- Issues and Pull Requests labeled 'ccmmf': [github.com/PecanProject/pecan/labels/ccmmf](https://github.com/PecanProject/pecan/labels/ccmmf)
-  **SIPNET Simplified Biogeochemistry Model:** [github.com/ccmmf/sipnet](https://github.com/ccmmf/sipnet)

## Keeping Up To Date

### Watch Repositories Selectively

1. Go to a **CCMMF** or **PEcAn** repository (e.g.,  
   [github.com/ccmmf/organization](https://github.com/ccmmf/organization)).  
2. Click **Watch** at top-right.  
3. Choose **“All Activity”**, **“Participating and @mentions”**, or **“Custom”**.  
   - **All Activity** can flood your inbox.  
   - **Participating and @mentions** means only emails for items you create or where you are tagged.  
   - **Custom** lets you filter by labels or specific event types (e.g. issues, PRs).

**GitHub Docs:**
- [About Notifications](https://docs.github.com/en/account-and-profile/managing-subscriptions-and-notifications-on-github/setting-up-notifications/about-notifications)


### Email Filters

- Use your email client to **filter** or **label** GitHub notifications (e.g., “ccmmf,” “pecan,” or “sipnet”).
- If something is critical, **CARB or CCMMF staff** should @mention you in an issue and drop a quick note in **Slack**.
  
  See [GitHub docs](https://docs.github.com/en/get-started/exploring-projects-on-github/following-organizations) for details

### Navigating Repositories

- **Review Project Tasks and Milestones** in the CCMMF Organization Repository
	- [Tasks](https://github.com/ccmmf/organization/issues)
	- [Milestones](https://github.com/ccmmf/organization/milestones?direction=asc&sort=due_date&state=open).
- **Check the project boards** for issue tracking and task progress.

### Milestones

Milestones help track major project goals and deadlines.
- Click on the **Milestones** tab in a repository to review progress.
- Follow updates on completed and pending tasks.

## Interactions

### GitHub Issues 

#### Providing Feedback (Commenting)

1. Review open issues.
2. Click on an issue to view details.
3. **Comment** with feedback or questions.
4. Use **reactions** (👍, ❤️).


#### Creating Issues

1. Go to the **Issues** tab.  
2. Click **New Issue**.  
3. Provide a **clear title** and **detailed description**.   
4. Click **Submit new issue**.  
	
**GitHub Docs: [About Issues](https://docs.github.com/en/issues/tracking-your-work-with-issues/about-issues).**


### Discussions

GitHub **Discussions** can be used for **general Q&A, broader ideas, announcements, polls, and announcements**. 

The CCMMF project discussion board is at [github.com/orgs/ccmmf/discussions](https://github.com/orgs/ccmmf/discussions)

### Pull Requests (PRs)

GitHub **Pull Requests (PRs)** allow users to review and approve specific changes to code before they are accepted into a project.

* Interactions are similar to Issues, but have additional features for commenting on or suggesting changes to specific lines of code.
* Submitting Pull Requests is beyond the scope of this document, though certainly encouraged.  

#### How to Review a PR

1. Navigate to the **Pull Requests** tab in the repository.
2. Open a PR and review the proposed changes.
3. Click **Files changed** to examine modifications.
4. Leave **comments** and **suggest or request changes**.
5. If the changes are satisfactory, click **Approve**.

### Alerting Team Members

**@mention** relevant people if you need their input:  
  - `@dlebauer` (David LeBauer)  
  - `@infotroph` (Chris Black)  
  - `@mdietze` (Mike Dietze)  
  - `@Alomir` (Mike Longfritz)  
  - `@robkooper` (Rob Kooper) 

> Tip: it is often helpful to follow up with a **Slack** message to alert specific people about a new issue. 

## Notifications

To **stay informed** without overwhelming notifications:
- **Watch repositories selectively** (choose "Participating" or "Custom").
- **Follow only relevant issues and PRs**.
- **Email notifications**  can be set up in GitHub settings, and email client can be used for additional filters .

## Additional Resources and Support

Reach out to the CCMMF team using your favorite communication channel! If you have questions, reach out via Slack or open a GitHub issue in the  
[ccmmf/organization repo](https://github.com/ccmmf/organization/issues).

**GitHub Docs**
- [GitHub Docs](https://docs.github.com/)
- [GitHub Issues Guide](https://guides.github.com/features/issues/)
- [GitHub Discussions Overview](https://docs.github.com/en/discussions)
