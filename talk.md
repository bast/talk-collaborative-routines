name: inverse
layout: true
class: center, middle, inverse

---

# Efficient collaborative routines for teams

## [Radovan Bast](http://bast.fr)

### [NeIC](https://neic.nordforsk.org)/ [UiT The Arctic University of Norway](https://uit.no)

Free to share and remix under [CC-BY-SA-4.0](https://creativecommons.org/licenses/by-sa/4.0/).

---

## ~ or ~

### How can we stay on top of things and manage and contribute to code projects without making our heads explode?

---

## Teamwork is about .red[communication]

### Discuss .red[scaling] with respect to .red[team size] and .red[number of teams]

---

layout: false

class: split-50-50

## Goals

.column[
### Communicate

- Meet and discuss
- Ask questions
- Answer questions
- Make decisions
- Write documentation

### Coordinate

- Track progress
- Track issues
]
.column[
### We wish to avoid

- Confusion
- Being uninformed
- Leaving colleagues uninformed
- Double work
- Idling
- Wasting time
- Frustration
]

---

## Email

- Default if no other medium agreed

### .red[What are problems with emails?]

---

## Email

- Default if no other medium agreed

### Problems

- Too much, too many, too soon, too long
- Often changing subjects
- Not enough control of whether you want to follow an issue or not
- No clear lifetime for issues ("is this issue still relevant?")
- No clear owner ("who is working on it? me?")
- Easy to write to the wrong audience (forget somebody or reply all)
- Lost knowledge for people who will join your team later
- Difficult to find knowledge after some time

.blue[*"I have already made this paper too long, for which I must crave pardon, not having now time to make it shorter."*]
[Benjamin Franklin]

---

## Forum

- Answers can be organized
- Not ideal to track issues or progress
- Popular: [Discourse](http://www.discourse.org)

## Mailing list

- Often difficult to search
- Hard to see what problems are still open
- Popular: [Google Groups](https://groups.google.com) (possibly not reachable from China)

---

template: inverse

## Why are we using .red[chat apps] (WhatsApp, Hangouts, Facebook Chat, Snapchat, Telegram, ...) and not just email?

---

## [Slack](https://slack.com) (team chat)

### Problems

- Out of sight, out of mind
- Old messages get lost
- Invite only
- Problem with transcontinental flight in a busy team

### Suggestions

- If something requires action, use email
- Agree on Slack times when people are available to get teams connected

### Alternatives

- [Gitter](https://gitter.im) (unlimited history, open to join)
- [Mattermost](https://about.mattermost.com) (open source and you can host it)

---

## Issue tracking

### Advantages

- Clearly defined lifetime (auto-close with commit messages)
- Clearly defined owner
- Close to the repository (possible to cross-reference commits)
- Easy to follow/unfollow
- Easy to reference later (by your .red[future] users and colleagues)
- .blue[@mentions]

### Suggestion

- Track issues on your issue tracker and not via emails
- Make issues public

---

## [Trello](https://trello.com): web based project management

### Advantages

- Intuitive and lightweight task tracking

### Problems

- Hierarchy of tasks is hard to track and visualize
- Dependencies between tasks
- Disconnected from the source code

### Would be nice to have "Trello functionality" closer to the code

- [ZenHub](https://www.zenhub.com) for [GitHub](https://github.com)
- [GitLab Issue Board](https://about.gitlab.com/solutions/issueboard/)

---

## Recipe for efficient meetings

### Prepare

- Debug the technology ([Google Hangouts](https://hangouts.google.com) works)
- Have an agenda, make it accessible, distribute it before the meeting
- Be on time and stay on time (respect and cost)

### Document

- Take minutes (people who cannot attend want to be informed)
- Use **live minutes** (Google Doc which everybody in the meeting can view and edit live at the same time in the same place)
- Keep the document as a record/trace
- Document decision points and todo items (each todo item gets an owner)
- If relevant, transfer todo items to your progress tracking
- If you are paid by public money, be transparent about your minutes

---

template: inverse

## Recommendations

### There is no one size fits all

---

## Recommendations for communication

- Agree on channels
- **Document your channels** (every team will agree on something else)
- Use the right channel (if there is no documentation, how will you know?)
- Moderate: sometimes you need to move a discussion to a more appropriate channel
- Do not duplicate information (guarantee for confusion and divergence)
- Maximize transparency

---

## Recommendations for code development

- Use a distributed version control
- Use a web platform
- Use an issue tracker
- Only maintainers should have push access to the repository
- Work on forks
- Patches must adhere to contribution guidelines
- Maintainers shall not accept their own patches
- Maintainers shall not make value judgments on correct patches

Source: ZeroMQ [Collective Code Construction Contract](http://rfc.zeromq.org/spec:42) [list shortened]

---

## Contribution guide

A contribution guide should document:

- Code style
- Testing policy
- Licensing and copyright transfer
- Commit message format
- Code review policy
- Changelog policy
- Feature branch base point
- Discussion medium for new features (issues? enhancement proposals?)

---

## Social architecture toolbox

- Strong mission (the stated reason for the group's existence)
- Transparency (how openly and publicly decisions are made)
- Remixability (how far contributors can remix each others' work)
- Strong protocols (how well the rules are written)
- Fair authority (how well the rules are enforced)
- Smooth learning (how easy it is to get started and keep learning)
- Minimalism (how much excess work the group does)

Source: [Pieter Hintjens, Social Architecture, 2009](https://www.gitbook.com/book/hintjens/social-architecture/details) [list shortened]
