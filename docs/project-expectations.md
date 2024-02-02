# Project Expectations

## Project Storage

Please use the repository provided by the teaching team.

All repos should be owned by UAlberta-CMPUT401, so if you need additional repos, please ask your TA to create any additional repos you need and add you to them. This so if a student drops, deletes their github, or we need to revist something after the end of the semester. (Instructors are required to keep assignments & exams for 1 year in case of grade appeals or cheating, etc.).

## Third Party Applications and Github Integrations

Third party applications and Github integrations such as Jira are generally not allowed in this course.   

All marking will be done on work in your Github repository, not on any third party tool usage.

REMEMBER: A big part of this course is focusing on MVP. That means not spending too much time on tooling.

If there is a strong case for a third party application or Github integration, send an e-mail to the teaching team.

## Github Actions

Github gives us 3000 action minutes per month with Github Education, but they're all pooled and so because some teams use more than others we will eventually run out.

To ensure you can still run your actions, please set up a Runner on Cybera. There are some instructions here: <https://youtu.be/SASoUr9X0QA>

## Meeting Minutes

Meeting minutes are meant to keep track of what has been discussed during a meeting. 
It can serve as a reference to resolve problems that can arise as the project progresses.

Meeting minutes will record the: date and time, location, attendees, agenda of what is to be discussed, minutes of what was discussed, and action items arising from the meeting.

* You should be meeting with your team every week at the beginning of the week.
* You should be meeting with your TA every week during the assigned lab.
* You should be meeting with your client every week (minimum: once per sprint).
* Meeting minutes should be immediately submitted after each meeting via a Google Forms link on eClass.

## 401 IP Agreement Form

Please make sure everyone on the team & the client sign the IP agreement form. It's listed on the eClass. The purpose & rationale of the form is:

* Clients want to be able to own the code after the end of the project to do as they please, for example: keep working with the code.
* The idea for the project belongs to the client and the code comes from the team's work.
* The client can use the code for their idea.
* The team can use the code for any other ideas that they may have
* It is required because the project ideas are creative and related to the client's business/project.

If you have any further concerns, please email the instructor. 

## Project Documentation

You will be working on these documents during Sprint 1. In Sprint 2, you will refine and finalize the project documentation. After Sprint 2, you will update the Project Management page. All other documents will be considered final after the end Sprint 2.

Example: <https://ualberta-cmput401.github.io/example-documentation/>.

The example serves as reference only and should not be considered a gold standard.

### Project requirements

The purpose of this document is to explain the requirements of your software product. It should have the following sections. 

#### Executive summary

Write a short overview of the project (one paragraph), including the following:

* The problem that the product will solve (use your client’s language);
* Value proposition (what will be the essential functionality or your product);
* Who will use your product;
* How your product will be used.

#### Project glossary

Define any special terminology in the application domain (i.e., the terms that your client is using; not development, programming, or implementation terms).

#### User stories

User stories should be formulated using the standard notation (“As a [persona], I [want to], [so that].”). Think carefully about who will be the users of your product, and formulate user stories for specific personae. Your collection of user stories should be complete and cohesive, it must clearly show how exactly the client’s requirements will be met with your product.

For each user story, you must formulate detailed acceptance tests. 

User stories must be prioritized using the MoSCoW method.

#### Similar products

List competitive or similar products that you may use as a reference and/or inspiration.
At a minimum, similar products that can be found trivially via Google should be included.

#### Open-source products

List any open-source products that might somehow benefit your product, e.g.:

* As a reference or inspiration;
* As an external interface that you might want to use;
* As a source of information and insights.

Be creative and think outside the box.

#### Technical resources

List useful informational resources around the tools and frameworks that you plan to use.

### Software design

The software design document should be consistent with the requirements document, it should document and explain how the design will actually deliver the required features.

There is no one “right” way to create this document. Use your best judgement to choose the notations and tools. In any case, make sure that this document is meaningful with respect to your system. Be selective in what you portray about the architecture -- don’t go into too much detail but don’t make it overly superficial either. Suppose a new developer comes to the project: describe what is not obvious and definitely important to know. As for practical guidelines, each diagram should be described and motivated; you should use a consistent naming convention, and key elements should be annotated with further comments to explain their roles.

Before getting started, refresh your understanding of UML, this book is recommended (chapters 1, 3, 4): <https://learning.oreilly.com/library/view/uml-distilled-a/0321193687/>. 

#### High-level architecture

Most likely, you will **not** use any UML notation for the architecture diagram. You are free to invent your own style of architecture diagram. Include a useful legend. Refer to the examples discussed in class for guidance.

What’s the right scope of the architecture diagram? “One that’s big enough to be meaningful, small enough to be comprehensible, and cohesive enough to make sense.” Study [this chapter](https://learning.oreilly.com/library/view/the-software-architect/9781492077534/ch21.html#EmphasisOverCompleteness) to feel the gist of creating good software architecture diagrams: 
Make sure that your diagram includes all layers.

You can have more than one diagram if your project’s complexity requires it. 

#### Major data elements 

If you adopt an object-oriented style for your system, you can present the data as a UML Class diagram. 

If your system is not naturally object-oriented, you can create an Entity Relationship diagram (ERD).

#### Interaction scenarios

To document the dynamic behaviour of the system, for each interesting feature, you should develop a UML Sequence diagram, with components as “objects” and calls between them. Think, which features of your system should be described as sequence diagrams.

#### Low-fidelity user interface

Finally, you should develop low-fidelity sketches/wireframes of a few key screens. At this stage, it’s important to show the overall look and feel of your app, as well as the high-level user-interaction design. Low-fidelity wireframes are usually black and white.

Looking at the wireframes, anyone should be able to get an idea of what will be developed. Test your wireframes with your client, encourage them to give feedback. 


### Project management

There are two sections in this document:

1. Storymap
    * Should include all user stories
2. Project plan (or backlog)

You should start the document with a storymap. Include all five sprints. Don't forget to indicate estimation of each user story (in story points).

The second section should define a project plan.

#### Sprint 1

For **Sprint 1**, you should include the following:

* Due date
* Tasks to be completed (include asignees and due dates)

Most Sprint 1 tasks will not be related to any user story. For example, you will be creating the project documentation, setting up the project repository, setting up the project management tools, etc.

#### Sprint 2

For **Sprint 2**, you should include:

* Due date
* List of user stories to be completed (include estimation of each user story in story points)
* Estimated sprint velocity
* Tasks to be completed (include asignees and due dates)

The tasks should correspond with the user stories.

#### Sprints 3, 4, and 5

For the remaining sprints, you should include:

* Due date
* List of user stories to be completed (include estimation of each user story in story points)
* Estimated sprint velocity

Do not list the tasks yet. You will be planning them later, before the start of each sprint.

### GitHub Issues

Based on the planned **tasks**, set up and keep current Github Issues. 

Close issues by tagging them in a Pull Request or commit (see <https://docs.github.com/en/issues/tracking-your-work-with-issues/linking-a-pull-request-to-an-issue>).

### Teamwork

This document includes three sections:

1. Team canvas
2. Scrum roles
3. Belbin team roles

#### Team canvas

The Team canvas should be based on the template found here <http://theteamcanvas.com/use>/. You must choose the Full version of the canvas.

Use the instructions to facilitate the Team canvas session. An in-person session is recommended. However, if you choose an online format, you may use Mural or any other whiteboard tool. While creating your Team canvas, think about the high-level roles of each team member (e.g.: Scrum Master, Product Owner, Frontend Developer, Backend Developer, QA Engineer, DevOps Engineer, UI/UX Designer, Floater etc.). Think about which roles are necessary for your project. Each team member may be assigned to multiple roles, and each role may include multiple team members. 

#### Scrum roles

There are two special Scrum roles that must be defined for each sprint:

* Scrum Master
* Product Owner

You may choose to elect a Scrum Master and Product Owner for the whole project or switch roles for each sprint so that more team members can get product management experience. A good overview of skills and responsibilities of a Scrum Master and a Product Owner: <https://productmanagerhq.com/scrum-master-vs-product-owner/>.

Please define these roles in a section independent of the team canvas.

#### Belbin team roles

For each of the team member, list their **preferred**, **manageable** and **least preferred** roles.

Then, list all nine Belbin roles and, for each role, provide a brief description and a list of people who are able to fulfill that role.
