# Sprint One DevSecOps

## DevSecOps 101

### What is DevSecOps

DevSecOps is an organizational software engineering culture and practice that aims at unifying software development (Dev), security (Sec) and operations (Ops). 

The main characteristic of DevSecOps is to automate, monitor, and apply security at all phases of the software lifecycle: 
- plan 
- develop
- build 
- test 
- release 
- deliver 
- deploy
- operate
- monitor

In DevSecOps, testing and security are shifted to the left through automated unit, functional, integration, and security testing. This is a key DevSecOps differentiator since security and functional capabilities are tested and built simultaneously.

DevSecOps provides demonstrable quality and security improvements over the traditional software lifecycle, which can be measured with these metrics:
- Mean-time to production: the average time it takes from when new software features are required until they are running in production.
- Average lead-time: how long it takes for a new requirement to be delivered and deployed.
- Deployment speed: how fast a new version of the application can be deployed into the production environment.
- Deployment frequency: how often a new release can be deployed into the production environment.
- Production failure rate: how often software fails during production.
- Mean-time to recovery: how long it takes applications in the production stage to recover from failure.

In addition, DevSecOps practice enables:
- Fully automated risk characterization, monitoring, and mitigation across the application lifecycle.
- Software updates and patching at a pace that allows the addressing of security vulnerabilities and code weaknesses.

### The benefits of adopting DevSecOps include:
- Reduced mean-time to production: the average time it takes from when new software features are required until they are running in production;
- Increased deployment frequency: how often a new release can be deployed into the production environment;
- Fully automated risk characterization, monitoring, and mitigation across the application lifecycle;
- Software updates and patching at "the speed of operations".

## Agile Software Development

### What is Agile?
Agile is the ability to create and respond to change. It is a way of dealing with, and ultimately succeeding in, an uncertain and turbulent environment.
The authors of the Agile Manifesto chose “Agile” as the label for this whole idea because that word represented the adaptiveness and response to change which was so important to their approach.
It’s really about thinking through how you can understand what’s going on in the environment that you’re in today, identify what uncertainty you’re facing, and figure out how you can adapt to that as you go along.
### What is Agile Software Development?
Agile software development is more than frameworks such as Scrum, Extreme Programming or Feature-Driven Development (FDD).
Agile software development is more than practices such as pair programming, test-driven development, stand-ups, planning sessions and sprints.
Agile software development is an umbrella term for a set of frameworks and practices based on the values and principles expressed in the Manifesto for Agile Software Development and the 12 Principles behind it. When you approach software development in a particular manner, it’s generally good to live by these values and principles and use them to help figure out the right things to do given your particular context.
One thing that separates Agile from other approaches to software development is the focus on the people doing the work and how they work together. Solutions evolve through collaboration between self-organizing cross-functional teams utilizing the appropriate practices for their context.
There’s a big focus in the Agile software development community on collaboration and the self-organizing team.
That doesn’t mean that there aren’t managers. It means that teams have the ability to figure out how they’re going to approach things on their own.
It means that those teams are cross-functional. Those teams don’t have to have specific roles involved so much as that when you get the team together, you make sure that you have all the right skill sets on the team.
There still is a place for managers. Managers make sure team members have, or obtain, the right skill sets. Managers provide the environment that allows the team to be successful. Managers mostly step back and let their team figure out how they are going to deliver products, but they step in when the teams try but are unable to resolve issues.
When most teams and organizations start doing Agile software development, they focus on the practices that help with collaboration and organizing the work, which is great. However, another key set of practices that are not as frequently followed but should be are specific technical practices that directly deal with developing software in a way that help your team deal with uncertainty. Those technical practices are essential and something you shouldn’t overlook.
### Agile is a Mindset
Ultimately, Agile is a mindset informed by the values contained in the Agile Manifesto and the 12 Principles behind the Agile Manifesto. Those values and principles provide guidance on how to create and respond to change and how to deal with uncertainty.
You could say that the first sentence of the Agile Manifesto encapsulates the whole idea: “We are uncovering better ways of developing software by doing it and helping others do it.”
When you face uncertainty, try something you think might work, get feedback, and adjust accordingly.
Keep the values and principles in mind when you do this. Let your context guide which frameworks, practices, and techniques you use to collaborate with your team and deliver value to your customers.

### What are Agile Methodologies?
If Agile is a mindset, then what does that say about the idea of Agile methodologies? To answer this question, you may find it helpful to have a clear definition of methodology.
Alistair Cockburn suggested that a methodology is the set of conventions that a team agrees to follow. That means that each team is going to have its own methodology, which will be different in either small or large ways from every other team’s methodology.
So Agile methodologies are the conventions that a team chooses to follow in a way that follows Agile values and principles.
“Wait,” you’re probably saying, “I thought Scrum and XP were Agile methodologies.” Alistair applied the term framework to those concepts. They certainly were born from a single team’s methodology, but they became frameworks when they were generalized to be used by other teams. Those frameworks help to inform where a team starts with their methodology, but they shouldn’t be the team’s methodology. The team will always need to adapt its use of a framework to fit properly in its context.
What about Agile Project Management or Agile Business Analysis?
As Agile Software Development became more popular, people that were involved with software development activities but who didn’t personally develop software looked for some way to figure out how these Agile ideas applied in their line of work.
The Agile Manifesto and the 12 Principles were written by a group of software developers (and a tester) to address issues that software developers faced. When you think of Agile as a mindset, that mindset can be applied to other activities.
When you do that, Agile becomes an adjective. It describes the way in which you perform some activity. It does not create a new methodology for the reasons explained above.
When you want to understand Agile project management, ask “How might we perform project management in a way that allows us to create and respond to change and deal with uncertainty?” Agile Alliance and Project Management Institute (PMI) explored this question through a joint effort to create the Agile Practice Guide (Available to Agile Alliance Members).
When you want to understand Agile business analysis, ask “How might we perform business analysis in a way that allows us to create and respond to change and deal with uncertainty?” Agile Alliance and International Institute of Business Analysis (IIBA) explored this question through a joint effort to create the Agile Extension to the Business Analysis Body of Knowledge (Available to Agile Alliance Members).
### What about Business Agility?
The two concepts noted above are examples of an attempt to move Agile “outside of software.” Those efforts have resulted recently in the Business Agility movement.
If you extend the idea of Agile as a mindset, then people seeking Business Agility ask themselves, “How might we structure and operate our organization in a way that allows us to create and respond to change and deal with uncertainty?”
You might say that business agility is a recognition that in order for people in an organization to operate with an Agile mindset, the entire organization needs to support that mindset. Agile software development was never truly Agile until the organization changed its structure and operations to work in an uncertain environment.

## User Stories
### How do we write user stories?
A user story often follows the following ‘equation’:

- As a `<type of user>`, I want `<some feature>` so that <some reason>
- Let’s break this down one step further;
- As a `<type of user>` — this is the WHO. Who are we building this for? Who is the user?
- I want `<some feature>` — this is the WHAT. What are we building? What is the intention?
- so that `<some reason>` — this is they WHY. Why are we building it? What is the value for the customer?

Let’s look at a few simple examples;
As an internet banking customer
I want to see a rolling balance for my everyday accounts
So that I can keep track of my spending after each transaction is applied
OR
As an administrator
I want to be able to create other administrators for certain projects
So that I can delegate tasks more efficiently

### “Why can’t we just write features or tasks instead?”
And it’s a great question. Though most teams asking this question, usually don’t understand the value of writing user stories, and the fact that they serve very different purposes to that of features.

The fact is, it’s easy to get buried in a contextless, feature developing cycle. The objective becomes more about clearing your way through a laundry list backlog, than it is about building solutions that add value to your customers. Your human customers. User stories bring that context and perspective into the development cycle.

### Acceptance Criteria
User stories allow teams to have one hand on the needs, wants and values of their customers, and another, on the activities they need to accomplish to provide that value.
The link pairing these two things together, is acceptance criteria.
Acceptance Criteria or ‘conditions of satisfaction’, provide a detailed scope of a user’s requirements. They help the team to understand the value of the story and set expectations as to when a team should consider something done.
- Acceptance Criteria Goals
to clarify what the team should build before they start work
to ensure everyone has a common understanding of the problem/need of the customer
to help team members know when the story is complete
to help verify the story via automated tests
Let’s look at an example of a completed user story with acceptance criteria;
| As a potential conference attendee, I want to be able to register for the conference online, so that registration is simple and paperless.
- Acceptance Criteria:
Conference Attendance Form
A user cannot submit a form without filling out all of the mandatory fields (First Name, Last Name, Company Name, Email Address, Position Title, Billing Information)
Information from the form is stored in the registrations database
Protection against spam is working
Payment can be made via Paypal, Debit or Credit Cards
An acknowledgement email is sent to the attendee after submitting the form
With this in mind, teams should make sure that their acceptance criteria is ticking all of the following boxes;
### Due this week
- Sprint 1 quiz
- User Stories
