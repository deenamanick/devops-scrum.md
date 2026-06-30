# DevOps and Scrum: 6-Day Practical Program

## Audience

This program is designed for II-year college students who are new to software delivery, DevOps, and Scrum.

## Program Duration

- **Total duration:** 6 days
- **Daily duration:** 8 hours
- **Daily structure:** 1 main topic + 1 practical session
- **Teaching style:** Simple explanation, examples, discussion, hands-on practice, and recap

## Program Goal

By the end of this program, students should be able to explain how modern software teams plan, develop, test, release, and improve software using DevOps and Scrum practices.

## Daily Schedule Template

| Time | Activity |
|---|---|
| 09:30 - 10:00 | Recap / icebreaker / learning objective |
| 10:00 - 11:30 | Topic explanation |
| 11:30 - 11:45 | Break |
| 11:45 - 01:00 | Examples, discussion, and mini exercises |
| 01:00 - 02:00 | Lunch |
| 02:00 - 04:00 | Practical session |
| 04:00 - 04:15 | Break |
| 04:15 - 05:15 | Practical review / presentation |
| 05:15 - 05:30 | Quiz, reflection, and homework |

---

# Day 1: DevOps Foundations

## Main Topic

Introduction to DevOps and the DevOps lifecycle.

## Learning Objectives

Students will be able to:

- Explain what DevOps means.
- Understand why DevOps is important in modern software development.
- Compare traditional software delivery with DevOps delivery.
- Identify the main stages of the DevOps lifecycle.

## Simple Explanation

DevOps is a way of working where development teams and operations teams collaborate to deliver software faster, safer, and with better quality.

In traditional software delivery, developers write code and then hand it over to operations teams for deployment. This often creates delays, misunderstandings, and blame when something goes wrong.

DevOps reduces this gap by encouraging:

- Better communication
- Shared responsibility
- Automation
- Continuous testing
- Faster feedback
- Continuous improvement

DevOps is not only a tool or a job title. It is a combination of culture, process, and technology.

## Key Concepts

### 1. Development Team

The development team writes application code. For example, they create a login page, student dashboard, or payment feature.

### 2. Operations Team

The operations team manages servers, deployments, infrastructure, performance, and production stability.

### 3. DevOps Culture

DevOps culture means both teams work together instead of working separately. Everyone is responsible for delivering value to users.

### 4. Automation

Automation means using tools or scripts to reduce manual work. For example, automatically testing code whenever a student pushes code to GitHub.

### 5. Feedback

Feedback helps teams know whether the software is working correctly. Feedback can come from tests, users, logs, monitoring tools, or team reviews.

## DevOps Lifecycle

The DevOps lifecycle has the following stages:

| Stage | Meaning |
|---|---|
| Plan | Decide what to build |
| Code | Write the program |
| Build | Convert code into a runnable application |
| Test | Check whether the application works |
| Release | Prepare the application for users |
| Deploy | Put the application into a live environment |
| Operate | Keep the application running |
| Monitor | Watch errors, performance, and user behavior |

## Example

Suppose a college wants to build an online event registration system.

- Plan: Decide features like login, event list, and registration.
- Code: Students write the application.
- Build: The application is packaged.
- Test: The team checks whether registration works.
- Deploy: The app is published online.
- Monitor: The team checks if students face errors.

## Practical Session

### Practical Title

Map a DevOps Lifecycle for a College Application

### Practical Goal

Students will understand the DevOps lifecycle by applying it to a simple real-world college project.

### Group Activity

Divide students into groups of 4 or 5. Each group chooses one project idea:

- College event registration system
- Library book request system
- Student attendance tracker
- Canteen pre-order system
- Placement preparation tracker

### Task

Each group should create a DevOps lifecycle table for their project.

| DevOps Stage | What Will Happen in This Project? |
|---|---|
| Plan |  |
| Code |  |
| Build |  |
| Test |  |
| Release |  |
| Deploy |  |
| Operate |  |
| Monitor |  |

### Expected Output

Each group presents:

- Project name
- Main users
- DevOps lifecycle explanation
- Possible risks
- How they will collect feedback

### Assessment Questions

1. What is DevOps?
2. Why is communication important in DevOps?
3. Name any four stages of the DevOps lifecycle.
4. Is DevOps only about tools? Why or why not?

---

# Day 2: Git and CI/CD

## Main Topic

Version control using Git and introduction to CI/CD.

## Learning Objectives

Students will be able to:

- Understand why version control is needed.
- Explain repository, commit, branch, merge, and pull request.
- Understand Continuous Integration and Continuous Delivery.
- Describe the basic flow of a CI/CD pipeline.

## Simple Explanation

When many students work on the same project, they need a way to manage code changes. Git helps teams track changes, collaborate safely, and go back to older versions if needed.

GitHub, GitLab, and Bitbucket are platforms where Git repositories can be stored online.

CI/CD helps teams automatically build, test, and prepare code for release.

## Key Concepts

### 1. Repository

A repository is a project folder managed by Git. It stores code and history.

### 2. Commit

A commit is a saved change. It is like a checkpoint in the project.

### 3. Branch

A branch is a separate workspace. Students can create a branch to work on a feature without disturbing the main code.

### 4. Merge

Merge means combining changes from one branch into another branch.

### 5. Pull Request

A pull request is a request to review and merge code. It helps teams check code before adding it to the main branch.

### 6. Continuous Integration

Continuous Integration means developers frequently add code to a shared repository, and the system automatically checks the code.

### 7. Continuous Delivery

Continuous Delivery means the code is always kept ready for deployment after passing tests.

### 8. CI/CD Pipeline

A pipeline is a sequence of automated steps.

Example pipeline:

1. Code is pushed to GitHub.
2. The application is built.
3. Tests are executed.
4. The result is shown to the team.
5. The application is prepared for deployment.

## Example

A student creates a new login page. After pushing code to GitHub, the CI pipeline automatically checks whether the code builds successfully. If the build fails, the student fixes the issue before merging.

## Practical Session

### Practical Title

Create a Git Workflow and Simple CI/CD Pipeline Design

### Practical Goal

Students will understand how teams manage code changes and automate checks.

### Part A: Git Workflow Activity

Students create a workflow diagram using paper, whiteboard, or any drawing tool.

The diagram must include:

- Main branch
- Feature branch
- Commit
- Pull request
- Code review
- Merge

### Part B: CI/CD Pipeline Design

Students design a simple CI/CD pipeline for their Day 1 project.

| Pipeline Step | Purpose |
|---|---|
| Code push | Developer submits code |
| Build | Check whether the app can run |
| Test | Check whether features work |
| Review | Team reviews code |
| Deploy | Publish to users |

### Optional Hands-On Git Commands

If computers are available, the trainer can demonstrate:

```bash
git init
git status
git add .
git commit -m "Initial commit"
git branch feature-login
git checkout feature-login
```

### Part C: Hands-on GitHub Actions CI/CD Setup
If the `vagrant-ansible-terraform-docker` lab environment is available, students can:
1. Fork and clone the lab repository.
2. Generate a GitHub Personal Access Token (PAT).
3. Connect a local VM as a self-hosted GitHub Actions runner.
4. Push a code change to trigger a pipeline that builds a Docker image and deploys it using Terraform.

### Expected Output

Each group submits:

- Git workflow diagram
- CI/CD pipeline table
- Short explanation of how errors will be found early

### Assessment Questions

1. What is a Git commit?
2. Why do teams use branches?
3. What is Continuous Integration?
4. What happens if a pipeline fails?

---

# Day 3: Containers, Cloud, and Monitoring

## Main Topic

Introduction to containers, cloud deployment, and monitoring.

## Learning Objectives

Students will be able to:

- Explain the difference between a virtual machine and a container.
- Understand the basic purpose of Docker.
- Explain why cloud platforms are used.
- Understand logs, metrics, alerts, and monitoring.
- Understand the basic idea of DevSecOps.

## Simple Explanation

After software is built, it must run reliably on different computers or servers. Containers help package the application with everything it needs to run.

Docker is a popular container tool. It helps developers create a consistent environment.

Cloud platforms allow teams to host applications on the internet without buying physical servers.

Monitoring helps teams know whether the application is healthy after deployment.

## Key Concepts

### 1. Container

A container is a lightweight package that includes the application and its required environment.

### 2. Docker Image

A Docker image is a template used to create containers.

### 3. Docker Container

A Docker container is a running instance of an image.

### 4. Virtual Machine vs Container

| Virtual Machine | Container |
|---|---|
| Heavier | Lightweight |
| Includes full operating system | Shares host operating system |
| Slower to start | Faster to start |
| Uses more resources | Uses fewer resources |

### 5. Cloud

Cloud means using computing services over the internet. Examples include AWS, Azure, Google Cloud, and Cloudflare.

### 6. Monitoring

Monitoring means watching the application after deployment.

Common monitoring data:

- Logs: Text records of what happened
- Metrics: Numbers such as response time or error count
- Alerts: Notifications when something goes wrong

### 7. DevSecOps

DevSecOps means adding security into DevOps from the beginning. Security should not be checked only at the end.

Examples:

- Do not store passwords in code.
- Scan dependencies for vulnerabilities.
- Use environment variables for secrets.
- Review access permissions.

## Example

A college attendance app works on one student laptop but fails on another laptop because the required software version is different. Docker can solve this by packaging the app and environment together.

## Practical Session

### Practical Title

Design a Container Deployment and Monitoring Plan

### Practical Goal

Students will understand how an application can be packaged, deployed, and monitored.

### Task

Using the same project idea from Day 1, each group creates a deployment plan.

| Area | Student Answer |
|---|---|
| Application name |  |
| What should be packaged? |  |
| What environment is needed? |  |
| Where can it be deployed? |  |
| What logs should be collected? |  |
| What metrics should be monitored? |  |
| What security risks should be checked? |  |

### Optional Docker Demonstration

If Docker is available, the trainer can show:

```bash
docker --version
docker run hello-world
```

The goal is not to master Docker on Day 3. The goal is to understand why containers are useful.

### Part B: Infrastructure as Code (IaC) & Configuration Management Lab
Using the `vagrant-ansible-terraform-docker` lab environment, students can practice:
1. **Provisioning with Vagrant:** Running `vagrant up` to automatically create a virtual machine environment.
2. **Configuration with Ansible:** Running simple Ansible playbooks (`ansible-playbook install_nginx.yml`) to configure the VM and install software like Nginx.
3. **Infrastructure as Code with Terraform:** Using Terraform commands (`terraform init`, `plan`, `apply`, `destroy`) to deploy a Docker container running Nginx, demonstrating how code can manage infrastructure reliably.

### Expected Output

Each group submits:

- Container idea
- Cloud deployment idea
- Monitoring checklist
- Basic DevSecOps checklist

### Assessment Questions

1. What is a container?
2. Why do teams use Docker?
3. What is monitoring?
4. Give one example of DevSecOps practice.

---

# Day 4: Scrum Foundations

## Main Topic

Agile basics, Scrum values, Scrum roles, and Scrum theory.

## Learning Objectives

Students will be able to:

- Explain Agile in simple words.
- Understand the difference between Agile and Waterfall.
- Explain what Scrum is.
- Identify Scrum roles and responsibilities.
- Understand Scrum values.

## Simple Explanation

Agile is a way of building software step by step. Instead of waiting for months to deliver a full product, Agile teams deliver small useful parts regularly and improve based on feedback.

Scrum is a popular Agile framework. It helps teams plan work, collaborate, review progress, and improve continuously.

## Agile vs Waterfall

| Waterfall | Agile |
|---|---|
| Work happens step by step in fixed order | Work happens in small repeated cycles |
| Feedback comes late | Feedback comes early |
| Changes are difficult | Changes are expected |
| Delivery takes longer | Delivery is frequent |

## Scrum Theory

Scrum is based on empiricism. Empiricism means decisions are made based on experience, observation, and evidence.

Scrum has three pillars:

- Transparency
- Inspection
- Adaptation

## Scrum Values

| Value | Meaning |
|---|---|
| Commitment | Team commits to the goal |
| Focus | Team focuses on sprint work |
| Openness | Team shares progress and problems |
| Respect | Team respects each person's contribution |
| Courage | Team speaks honestly and solves hard problems |

## Scrum Roles

### 1. Product Owner

The Product Owner decides what should be built and prioritizes the Product Backlog.

### 2. Scrum Master

The Scrum Master helps the team follow Scrum, removes obstacles, and supports collaboration.

### 3. Developers

Developers build the product. In Scrum, developers can include programmers, testers, designers, and other people who create the product.

## Example

For a college event app:

- Product Owner decides that event registration is more important than certificate download.
- Scrum Master helps the team conduct Daily Scrum and remove blockers.
- Developers design, code, test, and prepare the feature.

## Practical Session

### Practical Title

Scrum Roleplay for a College Product

### Practical Goal

Students will experience how Scrum roles work in a team.

### Task

Each group chooses a product idea and assigns specific cross-functional roles to make the simulation realistic:

- **1 Product Owner:** Focuses on the "What" and "Why" (features, business value).
- **1 Scrum Master:** Focuses on the "How" (process, removing blockers, facilitating).
- **1 Lead Frontend Engineer:** Focuses on User Interface and user experience.
- **1 Lead Backend Engineer:** Focuses on databases, APIs, and data storage.
- **1 DevOps / Security Engineer:** Focuses on where the app will live, pipelines, and security risks.
*(If groups are larger, add QA/Testing Engineer or UI/UX Designer)*

The Product Owner writes the product goal. The Scrum Master facilitates discussion. The specialized developers ask specific technical questions to identify what can be built first.

### Product Goal Template

```text
Our product is __________.
It is for __________.
It helps users to __________.
The first useful version should include __________.
```

### Role-Specific Discussion Questions (Roundtable)

To make the simulation effective, the Scrum Master should ask these specific questions:
- **To Product Owner:** "Are the requirements clear enough for the team to start?"
- **To Frontend Engineer:** "What API data do you need from Backend to build the screens?"
- **To Backend Engineer:** "Are there any database or architecture blockers?"
- **To DevOps Engineer:** "Do we have the environments ready to deploy the first feature?"
- **To All:** "What is the biggest risk that might prevent us from finishing our first feature?"

### Expected Output

Each group presents:

- Product name
- Product goal
- Assigned Scrum roles
- First three features to build

### Assessment Questions

1. What is Agile?
2. What is Scrum?
3. Name the three Scrum roles.
4. What does a Scrum Master do?

---

# Day 5: Scrum Events, Artifacts, and User Stories

## Main Topic

Scrum events, Scrum artifacts, user stories, and estimation.

## Learning Objectives

Students will be able to:

- Explain Scrum events.
- Understand Scrum artifacts.
- Write simple user stories.
- Create acceptance criteria.
- Understand basic estimation using story points.

## Simple Explanation

Scrum teams work in short cycles called Sprints. During each Sprint, the team plans work, meets regularly, builds the product, reviews the output, and improves the process.

Scrum artifacts help the team organize work and track progress.

User stories describe features from the user's point of view.

## Scrum Events

| Event | Purpose |
|---|---|
| Sprint | A short cycle where work is completed |
| Sprint Planning | Decide what to do in the Sprint |
| Daily Scrum | Short daily meeting to inspect progress |
| Sprint Review | Show completed work and collect feedback |
| Sprint Retrospective | Discuss how the team can improve |

## Scrum Artifacts

| Artifact | Meaning |
|---|---|
| Product Backlog | Full list of product work |
| Sprint Backlog | Work selected for the current Sprint |
| Increment | Completed usable product output |

## Commitments

| Artifact | Commitment |
|---|---|
| Product Backlog | Product Goal |
| Sprint Backlog | Sprint Goal |
| Increment | Definition of Done |

## User Story Format

```text
As a [type of user],
I want [some feature],
so that [some benefit].
```

## Example User Stories

```text
As a student,
I want to register for a college event,
so that I can reserve my seat.
```

```text
As a faculty coordinator,
I want to view registered students,
so that I can plan event arrangements.
```

## Acceptance Criteria

Acceptance criteria explain when a user story is complete.

Example:

User story:

```text
As a student, I want to register for an event, so that I can reserve my seat.
```

Acceptance criteria:

- Student can see available events.
- Student can click Register.
- Student receives confirmation.
- Student cannot register twice for the same event.

## Story Points

Story points are used to estimate effort. They are not exact hours. They represent complexity, effort, and uncertainty.

Simple scale:

- 1 point: Very easy
- 2 points: Easy
- 3 points: Medium
- 5 points: Difficult
- 8 points: Very difficult

## Practical Session

### Practical Title

Create Product Backlog and Sprint Plan

### Practical Goal

Students will create user stories, acceptance criteria, and a Sprint Backlog.

### Task

Each group uses its product idea and creates:

- Product Backlog with at least 8 user stories
- Acceptance criteria for 3 user stories
- Story point estimate for each story
- Sprint Goal
- Sprint Backlog with 3 to 5 stories

### Product Backlog Template

| ID | User Story | Priority | Story Points |
|---|---|---|---|
| US-01 |  | High |  |
| US-02 |  | High |  |
| US-03 |  | Medium |  |
| US-04 |  | Medium |  |
| US-05 |  | Low |  |

### Acceptance Criteria Template

| User Story ID | Acceptance Criteria |
|---|---|
| US-01 |  |
| US-02 |  |
| US-03 |  |

### Sprint Backlog Template

| Sprint Goal | Selected User Stories |
|---|---|
|  |  |

### Expected Output

Each group presents:

- Product Backlog
- Sprint Goal
- Sprint Backlog
- One user story with acceptance criteria

### Assessment Questions

1. What is a Sprint?
2. What is a Product Backlog?
3. Write one user story.
4. What is acceptance criteria?

---

# Day 6: Integrated DevOps and Scrum Capstone

## Main Topic

End-to-end product delivery simulation using Scrum and DevOps.

## Learning Objectives

Students will be able to:

- Connect Scrum planning with DevOps delivery.
- Simulate a Sprint from planning to review.
- Create a basic delivery workflow.
- Present a product idea professionally.
- Reflect on team improvement.

## Simple Explanation

Scrum helps the team decide what to build and how to collaborate. DevOps helps the team deliver software faster and more safely.

In real companies, Scrum and DevOps often work together:

- Scrum organizes the work.
- DevOps supports coding, testing, deployment, and monitoring.

## End-to-End Flow

| Scrum Activity | DevOps Connection |
|---|---|
| Product Backlog | Plan stage |
| Sprint Planning | Plan and code preparation |
| Development work | Code and build stages |
| Definition of Done | Test and quality checks |
| Sprint Review | Release feedback |
| Retrospective | Continuous learning |

## Capstone Project Options

Each group chooses one:

- College event registration system
- Library book request system
- Student attendance tracker
- Canteen pre-order system
- Placement preparation tracker
- Mini helpdesk ticket system

## Practical Session

### Practical Title

Scrum + DevOps Product Delivery Simulation

### Practical Goal

Students will combine all learning into one final team activity.

### Task

Each group must prepare and present a delivery plan for a small product.

The delivery plan must include:

1. Product goal
2. Scrum roles
3. Product Backlog
4. Sprint Goal
5. Sprint Backlog
6. Git workflow
7. CI/CD pipeline
8. Deployment idea
9. Monitoring checklist
10. Retrospective notes

## Capstone Template

### 1. Product Goal

```text
Our product is __________.
It helps __________ to __________.
The first version will deliver __________.
```

### 2. Scrum Roles

| Role | Student Name | Responsibility |
|---|---|---|
| Product Owner |  | Prioritizes backlog |
| Scrum Master |  | Facilitates Scrum |
| Developer |  | Builds and tests product |
| Developer |  | Builds and tests product |

### 3. Product Backlog

| ID | User Story | Priority | Story Points |
|---|---|---|---|
| US-01 |  | High |  |
| US-02 |  | High |  |
| US-03 |  | Medium |  |
| US-04 |  | Medium |  |
| US-05 |  | Low |  |

### 4. Sprint Goal

```text
In this Sprint, our team will complete __________ so that users can __________.
```

### 5. Sprint Backlog

| Selected Story | Task | Owner | Status |
|---|---|---|---|
|  |  |  | To Do |
|  |  |  | In Progress |
|  |  |  | Done |

### 6. Git Workflow

Students should explain:

- Which branch will be the main branch?
- How will feature branches be created?
- Who will review code?
- When will code be merged?

### 7. CI/CD Pipeline

| Stage | What Happens? |
|---|---|
| Code | Students push code |
| Build | Application is checked |
| Test | Basic tests are run |
| Review | Team reviews changes |
| Deploy | App is released or demoed |

### 8. Deployment Idea

Students explain where the application can run:

- Local computer
- College server
- GitHub Pages
- Cloud platform
- Container-based environment

### 9. Monitoring Checklist

| Monitoring Item | Why It Matters |
|---|---|
| Error logs | To find failures |
| Response time | To know if app is slow |
| User activity | To understand usage |
| Failed login attempts | To detect security issues |

### 10. Retrospective Notes

Each group answers:

- What went well?
- What problems did we face?
- What can we improve next time?

## Final Presentation

Each group gets 7 to 10 minutes to present:

- Product idea
- Scrum plan
- DevOps delivery plan
- Learning experience

## Evaluation Rubric

| Criteria | Marks |
|---|---:|
| Product idea clarity | 10 |
| Scrum roles and backlog | 20 |
| User stories and acceptance criteria | 20 |
| DevOps lifecycle and CI/CD plan | 20 |
| Monitoring and security awareness | 10 |
| Team presentation | 10 |
| Retrospective and learning | 10 |
| **Total** | **100** |

## Final Assessment Questions

1. How does Scrum help a software team?
2. How does DevOps help in software delivery?
3. What is the connection between Sprint Planning and the DevOps Plan stage?
4. Why is CI/CD useful?
5. Why should monitoring continue after deployment?

---

# Trainer Notes

## Teaching Tips

- Use simple examples from college life.
- Avoid too much tool complexity in the beginning.
- Keep students in groups for all 6 days.
- Use the same project idea throughout the program.
- Encourage every student to speak during presentations.
- Focus on understanding first, tools second.
- **Making Roleplay Effective:** During the Day 4 and Day 6 roleplays, step in as a "Stakeholder" to ask challenging questions. Ensure that the "Scrum Master" isn't acting like a boss, but rather asking the developers (Frontend, Backend, DevOps) what they need to succeed.

## Materials Required

- Whiteboard or projector
- Sticky notes or paper slips
- Markers
- Internet connection if GitHub or Docker demo is planned
- Student laptops for optional hands-on activities

## Suggested Homework

| Day | Homework |
|---|---|
| Day 1 | Write the DevOps lifecycle for one mobile app you use daily |
| Day 2 | Learn 5 Git commands and their purpose |
| Day 3 | Write 5 things that should be monitored in an online app |
| Day 4 | Identify Scrum roles in your project group |
| Day 5 | Write 5 user stories for your capstone product |
| Day 6 | Submit final reflection: what did you learn from DevOps and Scrum? |

## Expected Student Outcome

After completing this program, students should be able to confidently explain:

- What DevOps is
- What Scrum is
- How teams plan software work
- How Git supports collaboration
- How CI/CD supports faster delivery
- Why monitoring and feedback are important
- How to create simple user stories and Sprint plans
