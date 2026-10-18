# Disagreement Examples: dlong37 & dpate172

## Example 1: https://github.com/ketch/nodepy (HasRecovered)
**Author (dpate172):** Partly: two commits on September 4, 2024; sustained recovery is not established.

**Validator (dlong37):** Yes

**Discussion:** We agreed that after an 11-month gap (Oct 2023 to Aug 2024), maintainer David Ketcheson pushed one code change (`1ea45f7`, improved SSP(5,4) coefficients) and one README-badge merge, and nothing since. Dhrumil argued that two commits are too few to call it a recovery. I pointed out that the Coding Guide only allows yes/no, so `Partly` is not a valid value. They agreed that any commit after the gap counts as recovery, and that the recovery being thin belongs in the comments.

**Resolution:** ValidatorKept (Yes).

## Example 2: https://github.com/microsoft/fhir-server (CurrentStatus)
**Author (dpate172):** Active

**Validator (dlong37):** Inactive

**Discussion:** The Coding Guide defines status as of 2025-09-30 (cutoff 2025-04-01). Dhrumil applied it as written. I had treated the year as a typo for 2026 and used the course snapshot, which ends in Nov 2025. We agreed to use the date as written. Under it, the newest commit (PR #5168, 2025-09-30) falls inside the window. This one decision also settled the same disagreement for esri_geoportal-server, pytransit, opencalphad and pinocchio.

**Resolution:** AuthorKept (Active).

## Example 3: https://github.com/stack-of-tasks/pinocchio (RecentThemes)
**Author (dpate172):** Dependency updates:Automated bot contributions

**Validator (dlong37):** Automated bot contributions:Feature development

**Discussion:** Of the 10 most recent commits, 6 are bot-driven: two Dependabot bumps, a `github-actions[bot]` lock-file update, and the three merges of those PRs. Dhrumil had counted the human merges as Dependency updates. I pointed to the Coding Guide, which lists Dependabot updates under Automated bot contributions. For the second theme, I had read the viser/nix work as feature development. Dhrumil showed it is environment and path work ("nix: add meshlab & viser", "fix erd path"). We decided to keep Dhrumil's two themes, ordered by count with bot contributions first.

**Resolution:** Compromise (Automated bot contributions:Dependency updates).
