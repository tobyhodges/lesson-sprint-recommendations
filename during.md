# During the Sprint

- **Set up a place for shared note-taking.**
  This document should be visible to all participants
  and persist beyond the end of the sprint.
- **Hold regular, scheduled check-ins** to allow contributors to report
  on their progress, including what they've achieved,
  what's blocking their progress,
  and what they intend to do next.
- **Record the check-ins.**
  If technically possible, and provided all participants consent,
  record these check-ins so that those who could not join can catch up
  on the latest progress when they (re-)join the sprint.
  This is particularly important for sprints taking place
  across mutliple sessions/days and/or a wide range of timezones.
  If you cannot record the check-in discussions,
  make sure to take extensive notes in a shareable location.
- **Assign roles for check-ins.**
  To ensure everyone has an equal chance to contribute to the discussion
  and the sprint,
  the lead organiser(s) should assign meeting roles for the check-in calls.
  To further promote equity of participation,
  these roles should be rotated for each day of the sprint,
  or each separate sprint event.
  Roles may include:
  - a _Facilitator_ who coordinates the discussion and keeps it moving,
    watching out for raised hands and making sure those with something to contribute
    get the chance to do so;
  - a _Timekeeper_ who monitors the time remaining for the check-in and
    ensures that all topics are covered in a timely fashion.
    The Timekeeper prompts the
    Facilitator/speaker to move on when necessary to cover everything.
  - an _Issue/Task Creator_, who keeps track of actions that arise
    from the check-in discussion and creates an issue or
    describes the task in the shared notes.
  - a _Notetaker_, who takes minutes of what is discussed in the check-in.
    In some instances, it may be possible to combine the roles of Notetaker and Task Creator.
- **Make note of who is working on/is going to work on what.**
  This helps to avoid duplication of effort during the sprint,
  and gives participants a way of coordinating additional discussions
  among themselves where appropriate to make progress on a task.
- **Use a chat channel for communication outside check-ins.**
  To allow participants to "unplug" from video calls for the bulk of the sprint,
  use a text-based chat such as Slack or Mattermost for discussion when not
  checking in.
  If your chosen platform allows it, minimise global notifications
  to sprint participants by making use of threaded conversations.
  This will allow contributors to focus on their chosen task unless involved in
  a conversation directly relevant to them.
- **Prep breakout rooms for small group discussion and co-working between check-ins.**
  Open a small number of break out rooms for sprint participants to use during working sessions.
  This allows the participants to self-organize if they need to discuss something they are working on or co-work on a particular task.
  In Zoom, select the option to "Let participants choose room".
- **Provide a way for contributors to mark their work ready for review.**
  If you prefer to require material is reviewed before being included in the lesson,
  give participants a way to signal when their contributions are ready.
  You might consider providing guidance/assigning responsibilty for reviewers
  of particular sections/types of contribution.
  If your lesson is being developed on GitHub, see the section below for more
  specific recommendations on this topic.
- **Record information about participants and contributions.**
  Prompt participants to add their details to the shared notes,
  so you can refer to it later and ensure everyone's contributions are recorded.
  Information to collect might include names, affiliations, preferred pronouns,
  Orcid identifiers, GitHub usernames, and any other identifiers/handles that
  are relevant or frequently used in your domain.
  You may also wish to record the different ways in which participants are
  contributing to the lesson during the sprint, to ensure proper credit is
  given later e.g. when publishing the lesson.

## Recommendations for GitHub

- **Flag Pull Requests as draft and ready for review as you work.**
  Opening draft Pull Requests early, while work on a task is ongoing,
  can help contributors understand where progress is being made and identify
  tasks/issues that still need to be tackled.
  Marking Pull Requests as ready for review helps maintainers prioritise their
  focus during the sprint and maintains momentum by ensuring that completed work
  is merged into the lesson as soon as possible.
  Opening draft pull requests is particularly important at the end of a sprint,
  to capture progress up to that point even if a task hasn't yet been completed.
- **Plan who will review Pull Requests.**
  Make a plan for who will review each Pull Request.
  As a group you can create list of reviewers by subject so the person who opens the Pull Request knows who is interested and capable of reviewing and can request a review accordingly.
  Alternatively, you may decide on a circle of reviewers. E.g. Aaliyah reviews Juan's PRs, Juan reviews Alex's PRs, and Alex reviews Aaliyah's PRs.
  Another option might be to ask for a reviewer when planning who will do the task.
  For particularly small groups where reviewing is more likely to become a bottleneck, or in cases where the main objective of the sprint is to create quantity rather than quality, you may decide it is acceptable for contributors to merge their own pull requests.
- **Link Pull Requests to open issues.**
  Mentioning open issues in Pull Requests (even when a work in progress)
  informs people about which issues are being worked on.
  As mentioned in the point above, this is particularly useful to ensure progress
  can continue on the lesson after the sprint has finished.
- **Record contributions that do not (directly) result in commits.**
  Some participants may be more comfortable writing matrial on a different platform
  e.g. Google Docs, which is later transferred to GitHub by someone else.
  Make use of GitHub's [commit co-author](https://github.blog/2018-01-29-commit-together-with-co-authors/) feature where possible or,
  if the author does not have a GitHub account,
  make sure their name and other details are included in your README, AUTHORS,
  or any other listing/metadata about contributors to the project
  (`.zenodo.json`, `.allcontributorsrc`, etc).
