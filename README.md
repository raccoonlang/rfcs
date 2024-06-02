# RFCs - Request for changes

We use RFCs to collaborate successfully.

RFCs give us a way to write down ideas and plans so we can communicate, collect thoughtful feedback from others on the team, and make decisions.

An "RFC" literally means a "Request for Changes." Though RFCs can take many forms for different purposes, an RFC is ultimately just a document with a few attributes:

- The author's name(s)
- The date it was written
- A sequential number
- A status label

Our goal is for RFCs to be lightweight, low-process, and effortless to create and use. An RFC can be thought of as an asynchronous conversation. Unlike Slack, email, or other channels, using RFCs helps us because:

- There's no implicit demand for an immediate response.
- Reviewers have time to consider and propose changes.
- More people can collaborate at once without clashing.
- RFCs are easily searchable and referable.
- RFCs are retained indefinitely.

## When to use an RFC

Use an RFC when…

- You want to frame a problem and propose a solution.
- You want thoughtful feedback from team members.
- You want to surface an idea, tension, or feedback.
- You want to define a feature or design brief to drive collaboration.
- You need to surface and communicate around an important, highly cross-functional decision.

## Don't use an RFC when…

- You want to discuss personal or sensitive topics one-on-one with another team member.
- You want to make a decision to change something where you are the decider. In the vast majority of cases, creating an RFC to explain yourself will be overkill. RFCs should only be used if a decision explicitly requires one of the bullets in the section above.

## How we craft RFCs

RFCs are sequentially numbered

Each RFC has a unique, sequential number that appears in the title (e.g. "RFC 485 Review: Rethinking RFCs.") This makes it easier to quickly reference specific RFCs and easier for readers to quickly find that document.

The sequential numbers also provide valuable context about the order in which RFCs were created.

## RFCs have a status

Each RFC has a status label in the title of the RFC (e.g. "RFC 227 WIP: Title.") The author is responsible for keeping the title updated.

These status labels help to provide more context for readers. They're most helpful for readers to understand the RFC's context and shape their feedback accordingly.

### We have a set of status labels we've found helpful:

- **WIP**: The author is still drafting the RFC and it's not ready for review.

- **Reviewing problem**: The Reviewing problem label is used when the RFC has a firm problem statement, and reviews should focus on confirming that the problem definition is correct.

- **Reviewing solution**: The Reviewing solution label is used when the problem is well understood, and a proposal has been written that solves it that is ready for review.

- **Approved**: When the RFC is for the purpose of making a decision, the Approved label indicates that the decision has been made.

- **Implemented**: When the RFC is for the purpose of making a decision, the Implemented label indicates that the RFC's proposal has been implemented. If an important code change has happened due to implementing this RFC, we recommend capturing that in an Architecture Decision Record - ADR and linking the RFC in question in the ADR.

- **Closed**: When the RFC is for the purpose of collaboration or discussion but not necessarily to make a decision or propose a specific outcome that will eventually become Implemented, the Closed label indicates that the RFC is no longer an active collaborative artifact.

- **Abandoned**: When the RFC is for the purpose of making a decision, and there are no plans to move forward with the RFC's proposal, the Abandoned label indicates that the RFC has been purposefully set aside.

While these labels suggest that RFCs move through a series of prescribed stages, this isn't always the case. RFCs are low-process and can be used for all kinds of purposes that may not have an explicit, actionable outcome.

Ultimately, the RFC itself should make it clear what the status and planned process is.

If in doubt about the current status of an RFC, check the update history and contact the author.
