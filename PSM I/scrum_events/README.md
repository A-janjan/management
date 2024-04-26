# Scrum Events


## Getting ready to Sprint

we examined the concept of developing software in short iterations,
where each iteration builds upon the working software provided by its predecessors. We
call such an iteration a Sprint. A Sprint is a container event, as all the other Scrum Events
take place within the duration and context of a Sprint. The ultimate purpose of the Sprint
is to have the Developers produce an Increment. An Increment is a piece of working and
potentially shippable software that leverages previous Increments.


![scrum events](./docs/scrum_events.png)

Each Sprint begins with a planning phase. The is represented in Scrum by the Sprint
Planning event. The implementation phase, where all the development work happens,
is enabled by the Daily Scrum Event. Finally, the last phase of the Sprint (Inspection &
Adaptation) is marked by two events, the Sprint Review and the Sprint Retrospective.


### Deciding on the Sprint duration

A Sprint is time-boxed to a maximum duration of a calendar month. Most organizations
choose to interpret this as 4 working weeks, as it's easier to organize recurring events
by weeks rather than by calendar dates. The Scrum Guide does not specify a minimum
length for the Sprint, although – for practical reasons – a duration of less than 1 week
would not be realistic. Most Scrum Teams use a Sprint duration of 2-3 weeks. Once a
Sprint starts, its duration cannot be changed.


Having short Sprints is a risk limitation strategy. By producing shippable code often, we
are more likely to discover unfeasible requirements or technical dead-ends early, without
having committed a large amount of time and effort. Having Sprints longer than a month
would increase that risk.

### Setting the Sprint Goal

When setting the Sprint Goal, the team should be asking these questions:

• What value are we trying to deliver with this Sprint? And to whom? Some Sprints may
be focused solely on adding new features, while others may include some effort for
code re-factoring or optimizations. The important point is to identify who benefits
from the Sprint and how.

• Is the goal reachable and realistic? If the goal reaches for something that the
Developers cannot deliver within a single Sprint, it will cause confusion and loss
of morale among the team.

• How do we know the goal has been met? We need to identify some validation
methods or criteria so that we can know whether the goal has been achieved. This
could be as simple as asking a client stakeholder to test the Increment.


### Defining Done as working and potentially shippable software

The first indication of working software is software that has been tested. Testing works
on multiple levels: unit, component, integration, and so on. Whatever our testing levels
are, we must ensure that all tests are successful, before we can call our software working.
Another indication of working and also potentially shippable software is that it functions
as specified. Having a specification is very important. A specification is an agreement
between us and our customer about how our system should function. Specifications
written in Behavior-Driven Development (BDD) style (see the Further reading section)
express system behavior in a clear and consistent manner. It then becomes easy to verify
that our code enacts this behavior. This can take place either manually or by automated
scripts. Many Scrum Teams not using BDD impose the addition of acceptance criteria on
user stories the team is working on. Working and potentially shippable software should
always pass those criteria.


For many teams, Done may mean that, as well as tested and functioning to specification,
code has also been merged into a particular source repository branch or that it has been
deployed successfully to a staging environment. The Definition of Done should fit the
needs of each organization, team, and product. For instance, an organization may define
Done to include coded, unit-tested, code-reviewed, checked in to master branch and
integration-tested on the staging environment. Other organizations may choose to use
different operational criteria for their own Definition of Done.


## Starting the Sprint with Sprint Planning

Sprint Planning's purpose is to define the work to be performed during the Sprint. This
plan is created by the collaborative work of the entire Scrum Team. The duration of
the Sprint Planning should be no more than 8 hours for a 1-month Sprint. It should be
proportionately shorter for shorter Sprints.


The Sprint Planning aims to answer two questions:

• What can be delivered in the Increment resulting from the upcoming Sprint? This
is achieved by the Scrum Team estimating which Product Backlog items can be
realistically delivered in the Sprint, in order to achieve the Sprint Goal. The Product
Owner will have a clear idea of which items need to be delivered, but this must be
filtered by the Developers' estimation of how many of these items can be delivered
within the Sprint.


• How will the work needed to deliver the Increment be achieved? This is
accomplished by the Developers creating a plan on how they will deliver the
selected items. They represent this plan as a number of tasks. These tasks could
involve coding, infrastructure, research, or some other work that contributes
toward delivering a backlog item.



The inputs for the Sprint Planning are as follows:


• The Product Backlog. This is an ordered list of everything that is needed in order
to create the product.

• The latest Product Increment, which is the cumulative work the team has produced
so far.

• Projected developer capacity for the Sprint.

The outputs of the Sprint Planning are as follows:

• The Sprint Goal for the upcoming sprint.

• A list of Product Backlog items that can be Done by the Developers within the
Sprint, along with any planned tasks needed to get these items Done. We call this
list the Sprint Backlog.


### Sprint Planning for the Scrum Master

The Scrum Master ensures that the event takes place and that attendants understand
its purpose. The Scrum Master also ensures that the event is kept within its time-box
(maximum duration). The Scrum Master may also ask the Developers for clarification on
how they intend to achieve the Sprint Goal or create the Sprint's anticipated Increment.

### Sprint Planning for the Product Owner

The Product Owner performs two main functions during the Sprint Planning. The first
one is that they help set the Sprint Goal. The Sprint Goal will be set in accordance with
the product roadmap, current market needs, and the previous Scrum Increment, that is
the product functionality that has already been delivered. Although the Product Owner
may have the best view on what the best Sprint Goal is, consensus should be reached by
the whole of the Scrum Team. The second one is that they help to clarify selected Product
Backlog items for the Sprint Backlog and make trade-offs between items when needed.
The Product Owner may also ask the Developers for clarification on how they intend to
achieve the Sprint Goal or create the Sprint's anticipated Increment.


### Sprint Planning for the Developers

The Developers help the Product Owner set a Sprint Goal for the upcoming Sprint.
Although the Product Owner should know what the Sprint Goal ought to be, sometimes
there may be technical or resource-related reasons that render that goal risky or even
unfeasible. This is why the Developers' input in setting the Sprint Goal is invaluable. Once
the Sprint Goal is set, the Developers select a number of items from the Product Backlog
and add them to the Sprint Backlog. Their selection is influenced by a number of factors:

• Whether an item is contributing toward accomplishing the Sprint Goal.

• Developer capacity. This is the Developers' estimated or measured units of work
that can be delivered within a Sprint. 

• The Product Increment. Previously delivered functionality may affect the estimated
cost of an item, as well as its relevance to the Sprint Goal.


## Keeping on the right track with the Daily Scrum

The Daily Scrum is a daily occurring event held at the same time and place every day,
usually at the start of the day. The Daily Scrum is solely for the benefit of the Developers.
The Scrum Master and Product Owner may attend the event, but only as observers. They
are not allowed to disrupt or participate. The Scrum Master may want to be present to
ensure the meeting does not exceed its maximum duration (time-box) of 15 minutes and
that it is not disrupted by external people.

The objective of the event is for the Developers to inspect the work done since the last
Daily Scrum and plan the work for the next 24 hours. The structure of the event and the
way it's conducted is entirely up to the Developers. A common structure is that each team
member gives a brief summary on three things:

• What they've been working on since the last Daily Scrum

• What they plan to work on in the next 24 hours

• Any potential impediments they may be having


## Inspecting the product during the Sprint Review

The Sprint Review is held at the end of the Sprint in order to inspect the Product
Increment and adapt the Product Backlog, if needed. The event's duration is at most 4
hours for 1-month Sprints and proportionately shorter for shorter Sprints. The event is
attended by the whole of the Scrum Team, but also any stakeholders invited at the Product
Owner's discretion.

The inputs of the event are the Product Backlog and the done Product Increment
produced in the Sprint. The output of the event is a revised Product Backlog that identifies
the probable Product Backlog items for the next Sprint. The Product Backlog may also be
adjusted overall to meet new business opportunities.


The roles of the Scrum Team members during this event are as follows:

• The Product Owner explains what Product Backlog items have been Done and what
hasn't been Done. They invite feedback from the stakeholders, and they review
the current position of the product in the marketplace, timescales, budget, future
capabilities, and the next anticipated releases of functionality or capability of the
product.
They also discuss the state of the Product Backlog and they project likely target and
delivery dates based on current metrics (if needed). They also track the total work
remaining to reach certain milestones or releases.


• The Developers discuss what went well during the Sprint, what work had to
be added, and what had to be removed. They also bring up any problems they
encountered and talk about how those problems were solved. Finally, the team
demonstrates the work they did for the Increment, receives feedback on it, and
answers questions about it.

• The Scrum Master ensures that the event takes place and does not exceed its
maximum duration and that the attendees understand its purpose.


By the end of the Sprint Review, both the Scrum Team and the stakeholders should have a
clear view of what to do next. In this sense, the Sprint Review also provides valuable input
for the next Sprint Planning.


## Inspecting the team with the Sprint Retrospective

The Sprint Retrospective is the last event to take place during the Sprint and signifies
the end of the Sprint. It is an opportunity for the Scrum Team to inspect itself and
create a plan for improvements to be enacted during the next Sprint. It is time-boxed
at a maximum of 3 hours for a 1-month Sprint, and proportionately shorter for shorter
Sprints. The event is attended by the entire Scrum Team.

The purpose of the Sprint Retrospective is for the Scrum Team to do the following:

• Inspect how it performed with regard to interpersonal relationships, processes,
and tools.

• Identify and order the things that went well and the things that didn't.

• Create a plan for implementing improvements to the way it works.


Some of the basic questions the team is called to answer during the Sprint Retrospective
are as follows:

• What went well during the Sprint?

• What didn't go well during the Sprint?

• What improvements can we make for the next Sprint?

