# SDLC
The Software Development Life Cycle (SDLC) is a structured process used by software development teams to design, develop, test, and deploy software applications. It provides a systematic approach to software development, ensuring that the final product meets the requirements and is of high quality. 

## SDLC Models 
There are several models of SDLC, each with its own approach to managing the phases of software development.
1. Waterfall Model: A linear and sequential approach where each phase must be completed before the next begins.
2. V-Model: An extension of the Waterfall Model that emphasizes validation and verification at each stage.
3. Iterative Model: Develops the system through repeated cycles, allowing for incremental improvements.
4. Spiral Model: Combines iterative development with risk management, focusing on early identification and mitigation of risks.
5. Agile Model: Emphasizes iterative development, collaboration, and flexibility for rapid delivery of functional software.
6. DevOps Model: Integrates development and operations to improve collaboration and automate the deployment process.
   
# What is Agile?
- Agile is a project management and software development approach that aims to be more effective.
- Agile means move quickly.
- It focuses on delivering smaller pieces of work regularly instead of one big launch.
- This allows teams to adapt to changes quickly and provide customer value faster.
- Agile is not just a methodology; it’s a mindset. Agile isn’t about following specific rituals or techniques. Instead, it’s a bunch of methods that show a dedication to quick feedback and always getting better.
- Everyone in the team works on the same level there is no hierarchy.
- They prioritize flexibility, collaboration, and customer satisfaction.
- Major companies like Facebook, Google, and Amazon use Agile because of its adaptability and customer-focused approach.

### Advantages
1. Frequent delivery
2. Face to face communication with the client.
3. Frequent changes
4. Less time is required

### Disadvantages
1. Less documentation
2. Maintainance problem

### Popular Agile Frameworks
- Scrum: Focuses on fixed-length iterations called sprints.
- Kanban: Uses a visual board to manage work in progress and optimize flow. It emphasizes continuous delivery without fixed-length iterations.

## SCRUM
- One of the most popular agile methodology.
- It is a lightweight, iterative and incremental framework.
- It breaks down the development phases into stages called "Sprints".

### Key Roles
1. Product Owner: Responsible for defining the features of the product and prioritizing the backlog. The Product Owner represents the stakeholders and ensures that the team is working on the most valuable tasks.
2. Scrum Master: Facilitates the Scrum process and ensures that the team adheres to Scrum practices and principles. The Scrum Master helps remove any impediments that the team might face.
3. Development Team: A cross-functional group of professionals who do the actual work of developing the product. The team is self-organizing and decides how to accomplish the tasks in the backlog.

### Keywords
1. Backlog: The Product Backlog is a prioritized list of work for the entire project, while the Sprint Backlog is a list of work for a specific sprint.
2. Sprint: A fixed-length period during which the team works to complete a set of tasks from the Sprint Backlog.
3. Daily Scrum: A daily meeting to synchronize team efforts and plan the next 24 hours.

### Advantages
1. Freedom & Adaption
2. High-quality, low-risk product.
3. Reduce the development time up to 40%
4. Scrum customer satisfaction is very important.
5. Reviewing the current sprint before moving to new one.


### Disadvantages
1. More efficient for small team size.
2. No changes in the sprint.

# Jira
Jira is a popular project management and issue tracking tool developed by [Atlassian](https://www.atlassian.com/). It is widely used by software development teams to plan, track, and manage software projects. Here are some key features and functionalities of Jira:

1. **Issue Tracking**: Jira allows teams to create, update, and track issues (tasks, bugs, user stories, etc.) throughout the project lifecycle.
2. **Agile Project Management**: Jira supports agile methodologies such as Scrum and Kanban. It provides boards, backlogs, sprints, and other tools to help teams manage their agile workflows.
3. **Custom Workflows**: Teams can define custom workflows to match their specific processes, including custom issue types, statuses, and transitions.
4. **Reporting and Analytics**: Jira offers various reports and dashboards to help teams monitor progress, identify bottlenecks, and make data-driven decisions.
5. **Integration**: Jira integrates with a wide range of other tools and services, including [Confluence](https://www.atlassian.com/software/confluence), [Bitbucket](https://bitbucket.org/), [GitHub](https://github.com/), [Slack](https://slack.com/), and more.
6. **Permissions and Security**: Jira provides robust permission schemes to control access to projects, issues, and other resources.

## Keywords
1. Sprint:
   - Definition: A sprint is a fixed-duration period, usually ranging from 1 to 4 weeks, during which a specific set of tasks must be completed and prepared for review.
   - Purpose: Sprints enable teams to divide their work into manageable segments and consistently deliver increments of value.
   - Process:
   Sprint Planning: Determine what can be accomplished during the sprint and outline the approach to achieve it.
   Daily Standups: Brief meetings to discuss progress and any obstacles encountered.
   Sprint Review: At the sprint's conclusion, evaluate what has been achieved.
   Sprint Retrospective: Reflect on the sprint to identify areas for improvement.

2. Epic:
   - An Epic is a large body of work that can be broken down into smaller tasks or stories.
   - It represents a significant feature or initiative that spans multiple sprints.
   - Epics help in organizing and tracking progress on larger projects or features.

3. Story:
   - It represents a single piece of work that needs to be completed within a sprint.
   - It is a user-centric requirement or feature that delivers value to the end user.
   - Stories are often written in the format of "As a [type of user], I want [an action] so that [a benefit/a value]."
   
4. Story Points:
   - Story Points are a unit of measure used to estimate the effort required to complete a story.
   - Instead of measuring in hours or days, story points take into account the complexity, risks, and effort involved. 
   - Teams assign story points during planning sessions to help gauge the workload for a sprint.
   
   Assignment of story points:
   - Relative Estimation Story points are assigned by comparing stories to each other. This method helps in understanding the relative effort required for each task.
   - Common Scale A popular scale for story points is the Fibonacci sequence (1, 2, 3, 5, 8, 13, etc.).
   - Example
   A straightforward task might be assigned 1 point.
   A moderately complex task could be assigned 5 points.
   A highly complex task might be assigned 13 points.

6. Tasks:
   - A Task in Jira is a type of issue that represents a piece of work that needs to be done.
   - Tasks are typically smaller and more granular than stories and can be used for various purposes, such as technical work, research, or administrative activities.
   - Tasks can also be part of a story or an epic.
   
7. Board:
   - A Board is a visual representation of your project’s workflow.
   - It helps teams manage and track the progress of their work.
  -  Boards can be configured to follow different methodologies, such as Scrum  or Kanban.
   
   Columns on the Board: To Do, In Progress, In Review, Done
   - To Do: This column contains tasks or stories that have been identified but not yet started. It represents the backlog of work that needs to be done.
   - In Progress: This column contains tasks or stories that are currently being worked on. It indicates that the work has started but is not yet complete.
   - In Review: This column is used for tasks or stories that have been completed but are awaiting review or approval. This could include code reviews, testing, or stakeholder approval.
   - Done: This column contains tasks or stories that have been completed and approved. It indicates that the work is finished and no further action is required.
     ![image](https://github.com/user-attachments/assets/92093fa8-8b75-48b9-9dee-909f2b64fba2)

8. Issue:
   An Issue is a generic term that refers to any task, bug, feature request, or any other type of work item that needs to be tracked and managed.
   Issues are the fundamental units of work in Jira and can be categorized into different types, such as:
   - Story: A user-centric requirement or feature.
   - Bug: A problem or error in the software that needs to be fixed.
   - Task: A piece of work that needs to be done, often more granular than a story.
   - Epic: A large body of work that can be broken down into smaller tasks or stories.
   - Sub-task: A smaller piece of work that is part of a larger issue.
     Each issue has various attributes, such as a summary, description, priority, status, assignee, and more, which help in tracking and managing the work.

9. Ticket:
   A ticket is essentially an issue that is created to track a specific request or problem reported by a user or customer. Tickets are commonly used in Jira Service Management  (formerly Jira Service Desk),         where they represent customer support requests, incidents, or service requests.

  Key Difference: The term "issue" is more general and can refer to any type of work item in Jira, while "ticket" is more specific to support or service requests.
  
Example
Epic → big goal [Learn Docker]
Story → as a devops learner i  should learn docker
Task → task needed to achieve goal
install docker on system
Docker file
Docker compose
network

# Practical
Create an account on Jira > choose template as scrum 

### Create a sprint

![image](https://github.com/user-attachments/assets/a75493c1-c0e0-4c3f-b5e9-a30b80e4aa77)

### Create Story
summary > assign story point > assignee > select sprint

![image](https://github.com/user-attachments/assets/f5c6ddd8-a775-435c-99be-4d8a0cf68bdd)

### Adding Members

![image](https://github.com/user-attachments/assets/423234e4-9be2-46c8-87e9-acf4b9e76c14)

### Assigning Tasks

![image](https://github.com/user-attachments/assets/5eb9be8b-98b6-4802-a3c5-3c0bb9043402)

### Starting a sprint

![image](https://github.com/user-attachments/assets/61a1cd27-03ca-4902-ab37-8d56674fa8bc)

# Jira and Slack Integration

Create an account on Slack : Get started > continue with google

![image](https://github.com/user-attachments/assets/45f156ff-fb52-4156-b966-b586d3239780)

Quick start > connet tool > slack > connect > " jira cloud for Slack (official)" > learn more > a page will appear > allow --> Jira is now authenticated to slack > Go to slack

![image](https://github.com/user-attachments/assets/f5fd1171-acfb-44fb-8aa9-0739c364accd)

Type: /jira create, connect ,ISSUEKEY

In Slack, the /jira create and /jira connect commands are used to interact with Jira directly from Slack. These commands are part of the Jira Cloud for Slack integration, which allows users to manage Jira issues without leaving Slack.

Example /jira create test integration

![image](https://github.com/user-attachments/assets/cbf6a039-be96-42e6-8b2c-d69cf6d1a29c)

Click on enter then this will pop up

![image](https://github.com/user-attachments/assets/11925754-d17e-4674-811a-59d35531e8cf)

Now this will be visible in backlog on JIRA

![image](https://github.com/user-attachments/assets/5523a5e2-ec80-4c77-bd03-e58fd39c8ba4)



### Slack Automation

To get a notification on slack whenever there is a change in the board
Project setting > automation > template 
Here you can create workflows of automation
New component > add an action > type “SLACK”

![image](https://github.com/user-attachments/assets/11944f7b-2774-4816-8a55-19ffef64d4b6)

It will ask for webhook URL

![image](https://github.com/user-attachments/assets/6c1d0bb9-df59-40a3-baac-7bdaf75aa4c5)


### Webhooks
A webhook is a method used by web applications to send real-time data from one application to another whenever a specific event occurs. Instead of continuously polling for data, a webhook automatically triggers and sends the data to a specified URL as soon as the event happens.

On your browser search : Create slack app > https://api.slack.com/apps
Slack > Create app > from scratch

![image](https://github.com/user-attachments/assets/8dd87812-0f9a-4b8a-97fe-0dbf565d005b)

Incoming webhooks > activate > on > add new webhooks to workspace

![image](https://github.com/user-attachments/assets/0280080e-bac8-4989-bddc-5ce50ce0a779)

Create a channel in Slack : Redirected webhook to this channel

![image](https://github.com/user-attachments/assets/e1e18ef7-7141-4b9e-9e98-3beab7db1ff8)

Copy webhook and paste > write a message > turn on rule 

Make a transition on board and you will receive a notification on slack

![image](https://github.com/user-attachments/assets/2395e2dc-5289-4fef-8d2e-fddf7d8a6146)

![image](https://github.com/user-attachments/assets/26b0e0e7-3ed4-4479-b4de-2de4024b3a0a)


# Jira and GitHub Integration
Jira > apps > explore more apps > github > get app > get it now > get started > continue > github cloud > install
It is needed because if any updates are made on github that will be automatically updated on Jira

![image](https://github.com/user-attachments/assets/be8798f3-643c-4ca5-ac1b-c00260ee247a)

Create a repo > create a sample file > while committing type ticket ID Eg #SCRUM-4

![image](https://github.com/user-attachments/assets/1161dd8a-0704-42ea-9f55-446eb6e5fcd8)

When you’ll commit that will be reflected in that jira task

![image](https://github.com/user-attachments/assets/b48ea305-98eb-4481-b90d-9a256b10c8c5)




