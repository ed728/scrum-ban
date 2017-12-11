# scrum-ban

## Description
This document is meant to sum-up my personal experiences, and advice I have received along the way for discussion and presentatation purposes.

## Idea
Some of the good points I see in Scrum:
* Well structured and organized.
* All team members get visibility of what is going on.
* Helps with planning and estimation.
* Should allow for swift unblocking of team members.

Some of the negatives I see in Scrum:
* Can be implemented too rigidly, with too much beaurocracy, thus wasting the team's time.
* Meetings, if not prepared for, can drag on too much.
* The whole concept of "anyone can do anything" is a tad too idealistic in my view, especially in smaller companies.
* Does not cope with external effects as well - change in priotirites from higher up.

I have recently found a thing called "Scrum-ban", which seems to address the issues I have with Scrum, while still keeping the good things. In my view, the word "Agile" should be taken to heart, and teams should not be afraid of implementing changes that work for them, even if that means breaking the rules of traditional Scrum.

## Flow
Scrum is usually implemented via time-boxed chunks of development called Sprints. Each Sprint is often 2 or 4 weeks in length, and is the often used as the unit for longer term planning. These sprints are also used to facilitiate incremental and continuous improvement by retrospectively looking back at how it went, compiling ideas, and then trying to improve the next one.

### Scrum Master
The SM is the person who facilitates the process, however the Scrum Master's main task is "to unblock the team". Implementing the process should just be a means to achieve that, not the goal, as a well implemented process should allow the team to be more efficient.

If any impediments arise, it is the Scrum Master's duty to resolve them as soon as possible. SM should act a representative of the team when it comes to dealing with management and should represent the interests of the members. SM should escalate issues as high as necessary, when necessary.


### Meetings
#### Daily Scrum
The namesake of the methodology. This involves a usually 15 minute gathering each day, where each team member should present the following:
* What they accomplished yesterday.
* What they plan on doing today.
* Whether they are blocked on anything.
This is done to monitor the health of the sprint, and also helps give Scrum Master visibility of any problems.

Additionally, the team lead should provide updates on any changes to the roadmap, or changes in the task priorities.

#### Planning
Usually done before starting a sprint. Based on how many people are in the team, there is a finite amount of work that can be completed. The amount of work a team can complete, should be based around the computed velocity of the team - the amount of tasks the team completes per sprint on average for example.

Pure Scrum does not intend for member specialization, however Scrum-ban allows for this, and I also believe it to be the better option. Team members, based on their interests or specialities, can choose their first task based on what they prefer to do next sprint - this can be done in advance if possible. If it is not possible to solve any conflicts of interest in advance, then during the planning meeting the team should go in a randomly-generated order and pick tasks. Any subsequent tasks should be individually picked upon completion of the first task.

The actual meerting often can end up being very short, and mainly consist of a short discussion of whether any tasks need re-estimation, and whether everyone feels comfortable with the sprint tasks.

"Everyone does everything" should not be artifically enforced by making sure everyone takes different tasks each time.

Scrum Master should track what team members are mainly doing, and make sure someone shadows this work at the very least.

A method to improve knowledge sharing within the team may be to define tasks in a vertical manner, thus a task on completion will provide new functionality, and it can be split into sub-tasks which can be shared between team members interested in different aspects of a single feature. There should still be one person who owns the overarching task.

#### Grooming
Grooming/Refinement is a meeting where the team should estimate the time it takes to perform a task.

Once an Epic or Project has been created following some feature requirement, a person should be assigned to investigate, break down and define tasks which are needed to implement this feature. Each task should have a decent implementation-level description which can be understood by people not familiar with the code, and a Defition-of-Done(DoD).

All tasks once created should be reviewed by Scrum Master and Team Lead, or one other team member in case SM and TL are the same person(which I would not recommend), thus ensuring the task itself has enough information in it, and is understandable enough for it to be allowed to proceed to the grooming session.

During grooming, once the task is understood, each team member should propose an estimate. If the range is small enough, the average can be taken for the overall task estimate. If the range is too large, then the people with the most extreme estimate should explain their reasonings. If a consensus cannot be reached - the task should be sent off for more investigation. How small of a range is "small enough" is team-dependent and can be discussed during the meeting.

If during grooming two "experts" start having a heated discussion, then some kind of timer/hourglass can be used - any person can turn it over and once the time is up everyone should try to estimate. If the estimates converge nicely - you are done and no more discussion is needed. (This approach has been suggested to me, but has not been tested, though it does conceptually promising.)

Investigation tasks can be either done off sprint ot be time-boxed. If there are constant investigation tasks popping up, doing them off sprint is fine, since that should be consistent engough for velocity to take care of.

#### Retrospective
This meeting as the name suggests serves as an opportunity to look back at the Sprint and discuss what went well and what were the issues.

If there are incomplete tasks remaining it should be discussed why and whether the velocity estimates are accrate.

It is also a time for the Scrum Master to gather feedback on how well the process is going.

Ideally, actions should be raised for next sprint to improve on any problems that have been identified.
