[Click here to install Zenhub!](https://zenhub.com) :tada:

We use [ZenHub](https://www.zenhub.io/) to more effectively manage our issues within GitHub. ZenHub can be [downloaded here](https://zenhub.com) for Chrome or Firefox browsers. The plugin adds extra features to the UI of Github that allows better management and tracking of issues.

## Milestones

Sprints are 2 weeks long. Sprint 1 began on <kickoff date>.

There is a milestone for each sprint, to support [ZenHub reporting burndown data](https://www.zenhub.com/guides/burndown-charts) on a sprint-by-sprint basis.

Issues shouldn't span multiple milestones and should be scoped to be accomplished within an individual sprint. If an issue requires work over multiple sprints, it should be discussed to be promoted to the level of an Epic. [Read about ZenHub Epic's here](https://www.zenhub.io/blog/working-with-epics-in-github/).

## Pipelines
[Take a look at our project planning kanban board here](/<username>/<reponame>#boards?repos=138744)

| Pipeline | Description|
| -------- | ---------- |
| `Backlog` | Issues without a milestone, or assigned a milestone other than the current/next sprint. |
| `Epics` | Container pipeline for epics only. For easy reference to filter by epics. |
| `To Do` | Issues assigned to the current milestone, waiting to be worked on. |
| `In Progress` | Issues currently being worked on. |
| `Ready for Review` | Issues that have all work completed, but not yet finalized. |
| `Closed` | Final state of an Issue, once all work has been complete and deliverable has been attached. |

## Story Point Estimation
**Required reading:** [this _excellent_ write up from ZenHub on how to tackle software estimation](https://www.zenhub.com/blog/software-estimates/)

We use story point estimation to track and plan how much work is complete and still outstanding.

Our story point estimates do not correlate directly with hours of work. They are a representation of synthesizing time, effort, complexity, and (un)certainty of each issue as a team. From the article, we use a combination of planning poker and triangulation to determine estimates for each issue as a team.

As an informal guide, our story points represent the following:  

| Story Point | Definition |
| ----------- | ---------- |
| 1           | Complete certainty, no unknowns, very predictable. A simple chore - can be completed in less than a day. |
| 2           | High certainty, no unknowns, predictable. Around a day's worth of work, maybe a bit more/less. |
| 3           | High certainty, no unknowns, predictable. Around a day or two's worth of work. |
| 5           | Certainty, but a potential for unknowns. Might require a meeting or some conversation to complete. Could require some research, or exploration. A few days worth of work. |
| 8           | Low uncertainty, an unknown or two, predictable. No outside dependencies or coordination on others. Could be completed in less than a week. |
| 13          | Medium uncertainty, a few unknowns, fairly predictable, no dependencies. Not much outside coordination or reliance on other individuals. Could be completed in less than a week. |
| 21          | High uncertainty, many unknowns, and somewhat predictable. Requires some coordination of multiple people. Likely will take half the sprint to complete.  |
| 40          | Highest uncertainty, lowest predictability, most unknowns, many dependencies, requires a lot of coordination, requires involvement from many individuals, likely will take the entire sprint to complete. <br> Tasks of this size should be considered to be elevated to an Epic, and broken up into multiple subtasks with their own individual estimates. |
