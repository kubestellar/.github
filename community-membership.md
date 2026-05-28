# KubeStellar Community Membership

This document outlines the responsibilities and requirements for membership in the KubeStellar GitHub organization, including how inactive members are handled and the Emeritus path for contributors stepping away from the project.

For the full contributor ladder (Contributor → Intern → Mentor → Maintainer), see the [KubeStellar Contributor Ladder](https://kubestellar.io/docs/contributing/contributor_ladder).

---

## Membership Overview

Being a member of the KubeStellar GitHub organization comes with elevated permissions, including write access to repositories, the ability to trigger CI workflows, and visibility into security advisories. These permissions carry responsibility — members are expected to remain familiar with project practices and actively engaged.

---

## Inactive Members

### Definition

A member is considered **inactive** if they have made **no contributions** across any repository in the KubeStellar GitHub organization within the past **9 months**.

Contributions include, but are not limited to:
- Code commits and pull requests
- Code reviews and PR comments
- Issue triage and discussion
- Documentation updates
- Community meeting participation
- Mentoring other contributors

### Process

1. **Notification**: When a member approaches 9 months of inactivity, a maintainer will reach out via GitHub issue or email to check in and offer support.
2. **Grace period**: The member has **30 days** from notification to resume contributions or respond with a plan to re-engage.
3. **Removal**: If no response or activity occurs within the grace period, the member is removed from the KubeStellar GitHub organization and moved to **Emeritus** status.
4. **Voluntary step-down**: Members may proactively request Emeritus status at any time without waiting for the inactivity process.

### What Removal Means

- Removed from all GitHub teams in the KubeStellar organization
- Write access, CI trigger permissions, and triage permissions are revoked
- The member's past contributions remain attributed and visible in git history
- The member is listed as Emeritus in the project's contributor records

### What Removal Does NOT Mean

- It is **not** a judgment on the quality or value of past contributions
- It does **not** prevent the member from participating as an external contributor (filing issues, submitting PRs for review)
- It does **not** prevent reinstatement (see below)

---

## Emeritus Status

Emeritus is a recognition that a contributor has made meaningful contributions to KubeStellar but is no longer actively participating. It preserves their legacy while ensuring that active permissions reflect active engagement.

### Rights of Emeritus Members

- Listed in the project's Emeritus roll (in the contributor ladder documentation)
- Acknowledged in release notes or project communications when relevant
- Welcome to participate in community discussions, meetings, and public channels
- May submit pull requests and issues as external contributors

### What Emeritus Members Do NOT Have

- GitHub organization membership
- Write access to any repository
- Approval or review permissions in OWNERS files
- CI trigger permissions
- Access to private maintainer channels or security advisories

---

## Reinstatement from Emeritus

Emeritus members have a **streamlined path back** to active membership. They do not need to start from scratch.

### Requirements

1. **Signal intent**: Open an issue on the [kubestellar/.github](https://github.com/kubestellar/.github) repository or contact a maintainer directly.
2. **Demonstrate renewed engagement**: Make a minimum of **3 meaningful contributions** (PRs, reviews, or issue triage) within a 30-day period to show re-familiarization with current project state.
3. **Maintainer sponsor**: An active maintainer must vouch that the returning member is up to speed with current practices, CI, and project direction.
4. **Approval**: A simple majority of active maintainers approves reinstatement.

### What Reinstatement Restores

- The member is restored to the **same level** they held before going Emeritus (e.g., if they were a Maintainer, they return as a Maintainer), provided they meet the current requirements for that level.
- If the project has evolved significantly, maintainers may recommend reinstatement at a lower level with a path to regain the previous level.

---

## Non-Code Contributors

Activity tracking primarily uses GitHub metrics, which may not capture all forms of contribution. If a member who contributes through non-code means (community organizing, outreach, user support, meeting facilitation) is flagged as inactive, they may open an issue to clarify their contributions and request that the inactivity determination be reconsidered.

---

## Review Cadence

Maintainers will review organization membership **quarterly** to identify potentially inactive members and initiate the notification process described above.

---

## Modifying This Policy

Changes to this policy require a pull request to the [kubestellar/.github](https://github.com/kubestellar/.github) repository, approved by a majority of active maintainers.
