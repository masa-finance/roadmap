# SCRUM Ceremonies

## Dailies

Daily standups should focus on current sprint goals and potential blockers. 
Each engineer has the opportunity to discuss their daily agenda and any challenges they face. 
A recommended approach is to start with one person chosen randomly who then nominates the next speaker. Ideally each engineer has a maximum of 3 to 5 minutes, anything else has to be taken offline, or decide to arrange a follow-up call to discuss the specific topic.

### Async bots

Async bots are helpful to sync teams in different TZs, and also gives a glimpse for anyone on the teams requirements and blockers. Dailies can be also considered optional if async bots are presents, as ideally should give enough context to everyone on the team status.

Example async bots:

- https://app.dailybot.com
- https://supbot.com

Suggestion: have separate check-ins for every team to keep workflows scoped.

## Plannings

During planning sessions, for each team, the Scrum Master should:

- Review the "Done" column with the team to confirm the completion of tasks. If required, ask team members to update the card and add the contextual information in order to close the card with the information needed (cross-reference with PRs, follow-ups have to be listed in the card if needed). Once all the cards were analyzed, "archive all" of them to not make them visible anymore in the sprint view.
- Assess tasks with the team in the "Under Review/QA" column to determine necessary actions for completion, going one by one to the tickets.
- Examine the "In Progress" tasks, checking the status of each with the team.
- Groom the "No Status/Backlog" items, moving relevant tasks into the sprint backlog.
  - Every card in the sprint:
    - Should have enough information for anyone in the team to pick that up
    - Every card should have a clear Problem statement,  an Acceptance criteria list if it's a spike, Action items if it's an implementation card
    - Ask for every card if it's clear for everyone
- Optionally, the team and the Scrum Master may estimate task sizes.
- Optionally, calculate the team's velocity.
- Review planned releases and prioritize tasks for the sprint backlog by looking at the next release ( https://github.com/orgs/masa-finance/projects/12 ).
- Identify and prioritize any critical tasks needing immediate attention (issues with a swimlane priority tag).
- P.O. order tickets in the Sprint column
- P.O. might ask to get items in the board and be triaged during planning
- Scrum master help the team to commit to selected items in the sprint backlog, establishing a clear boundary of commitment (waterline) by considering team velocity.
- Assign a release captain if a release is scheduled during the sprint.
- Optionally, rotate the responsibility of handling interruptions in the team.

## Cards

Spike(optional) -> Epics (optional)? -> Implementation card

### Spike

Spike tasks should comprehensively document all research findings. Necessary follow-ups should be identified and linked to the spike tasks. Ideally, spike documentation should provide sufficient context for any engineer to take over the task without needing prior knowledge of the topic. 

### Epic

Epics should be bigger issues that does not fit into a single ticket. It is best to have epic tickets to track big features, breaking changes, or changes that imply changes in different codebases.

### Implementation card

If the action items are well known an implementation card can be directly created. The implementation card needs to have a Problem statement, and Action items.

### Cards tags

- "triage" - all new cards opened during a sprint that needs to be discussed during planning
- "release" - release tracker cards
- "epic" - epic cards (see above)
- "spike" - spike cards (see above)
- "swimlane" - priority cards that needs to be picked up during planning/sprint if urgent
- "qa" - cards that requires only QA check
- "doc" - documentation card
- "blocked" - cards that are blocked by other (dependencies)
- "pairing-needed" - A card that calls an implementation, or a spike with a team member (XP)
- "question" - A non-clear issue that needs more context added
- "chore" - small cards that does not need estimation or complex planning

### Notes

- Do keep tickets active: document the iterative thought process
   - if it's a spike, remind to update with a comment, ideally daily, on what's the conclusions
   - if it's an implementation, remember to close the issue by linking the relevant PRs that are related to it
- If there are PRs scoped into epics/trackers, reference that issue in the commit or in the PR description
- add links to cross-reference follow-ups
- Make it sure it has a checklist for each issue
- Make it sure that the checklist has at least an item for QA and one for documentation
- No more then 2 people working together on the same card. Rotations are OK, but having many hands on the same ticket is an engineering waste of time.
- Scrum master should let engineers fill the technical details of the tickets during planning: the scrum master has to hand over to engineering filling the details of the ticket and giving context more technical context, especially when coming up with action items - this is also a good mental exercise to check if there is understanding in the engineering team about a specific problem or ticket scope. Architects should be there to provide gudance and context over the roadmap/feature.

## Extreme programming - `pairing-needed`

Two programmers work together by pairing in a call (if remotely) or in a single workstation. One writes the code(driver) while the other reviews each line of code as it is typed in and provides feedback, reasoning if the approach would be able to work(navigator). The roles switch frequently. Often paired with TDD (Test-Driven Development).

## Demos

Teams should schedule bi-weekly or monthly demos to showcase their work to peers. If applicable, a dedicated page should be set up for team members to request presentation slots.

## Team healthchecks

Team healthchecks were introduced in Spotify. It's a way to assess the whole team healthcheck at least, in a bi-quarter basis. An example of such a document is: https://miro.com/miroverse/squad-health-check/.

The document needs to be completed async by the team members, and sent to the scrum master to collect and get the output - the output then is presented to the team to discuss action items to fix/address.

## Team size

An ideal team size would be from 3 up to 6 people at maximum.

## Watercooler meeting

Informal watercooler meetings can be helpful to maintain team morale and foster a positive work environment.

Something to play also in the meeting can be:

- https://skribbl.io/
- https://supertuxkart.net/Main_Page
- http://sauerbraten.org/
- CS:GO
- ... suggest yours!

## Retros

Retrospectives should be conducted monthly or bi-weekly using tools like Jamboards. These sessions aim to categorize events of the previous sprint into three groups: positive (good), negative (bad), and neutral (meh) experiences.

## Notes

We are trying to get only the good things of scrum! Do consider which things of the process to use depending on the current team state. 

https://x.com/rita_codes/status/1800151063602811159

Do not have "too many meetings" but try to strike a balance - that's why dailies should be optional, or demos and retros often planned as bi-weekly or even monthly. Keep always a room for watercooling, and leave sync-ups and pairing to the team in order to meet deadlines. Context switch is often unnecessary and steal precious engineer focus away.
