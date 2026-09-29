# Rubric: is this a good first issue?

## Checks

| Check | Evidence | Pass condition | Weight |
|---|---|---|---|
| Maintainer activity | Repo-facts block: recent default-branch commit dates and recent maintainer issue or pull request activity. | Pass if the repository has at least one default-branch commit or maintainer issue/pull request activity within the last 90 days. | required |
| Repository in use | Repo-facts block: the last 5 default-branch commit dates and recent issue or pull request activity. | Pass if at least 2 of the last 5 default-branch commits happened within the last 180 days, or there has been maintainer issue/pull request activity within the last 90 days. | required |
| Newcomer-sized scope | Issue body and comment thread: requested change, number of distinct behaviors requested, architecture changes, migrations, refactors, and number of major components involved. | Pass if the issue asks for one focused bug fix or feature and does not require a repository-wide refactor, major architectural redesign, data migration, broad dependency upgrade, or coordinated changes across more than 4 major components. Multiple files may still pass if they support one focused change. | required |
| Issue has enough direction | Issue body and comment thread: problem statement, requested behavior, examples, acceptance criteria, reproduction steps, or maintainer clarification. | Pass if the issue provides enough information to identify the requested change and determine when it is complete. It does not need both explicit reproduction steps and formal acceptance criteria. | required |
| Not already being worked on | Repo-facts block for assignee information, plus the issue body and comment thread for claim or work-in-progress statements. | Pass if the issue has no current assignee and no non-Path-Review contributor has clearly stated within the last 30 days that they are actively working on it. In Path Review live mode, ignore student claim comments according to the house rule in `scope.md`. | required |
| No contributor-policy blocker | Issue body, comment thread, and repo-facts block for contribution restrictions, maintainer-only work, security-sensitive handling, or instructions that outside contributors should not implement the issue. | Pass if there is no explicit policy or maintainer instruction stating that the issue is reserved, internal-only, security-sensitive, maintainer-only, or otherwise not open to normal contributor implementation. | required |
| Helpful guidance | Issue body and comment thread. | Pass if the issue includes at least one of the following: reproduction steps, file or component names, expected behavior, acceptance criteria, example output, or maintainer implementation guidance. | preferred |

## Verdict rule

Accept an issue only if every required check passes.

Preferred checks never change the accept or reject verdict. They are only used to help rank issues that already passed all required checks.

If a required check is graded `unclear`, treat it as a fail and reject the issue because there is not enough evidence to confirm that it is a good first contribution.