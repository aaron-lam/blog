---
{"dg-publish":true,"dg-permalink":"design-technical-roadmap-as-tech-lead","permalink":"/design-technical-roadmap-as-tech-lead/"}
---

202406291453
tags: #engineering-management

# What is Technical Roadmap?

## Definition

A technical roadmap is a long-term, comprehensive, actionable plan that aligns product direction among engineering and other stakeholders (PM, design, marketing, etc.).

## Key steps

1. Background and data collection
2. Identify and analyze problems
3. Tech stack selection and conduct technical design
4. Aligns long term plans and outcomes with stakeholders
5. Execution
6. Iteratively evaluate and adjust based on results

# Why design technical roadmap?

From a personal perspective:

- Accelerate career growth
- Strengthen data analytical skills
- Consolidate domain knowledge
- Increase influence at work

From a company perspective:

- Identify opportunities to decrease costs / increase efficiency
- Align technical and product direction
- Establish common ground with stakeholders
- Provide reasoning to apply more company resources

# Who should design technical roadmap?

A technical roadmap can be initiated either by executives (top-down) or by tech leads / team managers (bottom-up).

# When should design technical roadmap?

A technical roadmap can be done bi-monthly, quarterly, or annually. It can also be initiated when a new product direction is kicked off, or when a new team is established.

Please note, we shouldn't wait until these timeframes to think of those problems. We should proactively think and identify these during our daily work.

# How to design technical roadmap?

## Step 1: Identify Problems

The book "Are Your Lights On?" explains how we can identify the real problems at work.

 >- What is the problem?
>- Who all are facing this problem?
>- (For each unique answering party) - What is the essence of their problem?
>- Whose problem is it to solve?
>- Where is the problem coming from?
    - Could the source of problem be **me**? perceiving a problem where there is none?
    - The **ultimate** source may be nowhere. For e.g. make-works problems coming from bureaucratic management.
>- Is the person facing the problem really wants it to be solved?
>- Can we solve a different perhaps simpler problem that will have the same effect?
>- What new problems will our solution create?

### Finding a Problem

#### Induction

Identify a problem by finding repeated and common issues across teams.

AbstractIon: Middleware, platforms to support core infra capabilities (SSO, SMS, etc.)

Process Optimization: Sprint management, approval flow

Engineering efficiency: Debugging tools

#### Deduction

We can also identify a problem by thinking of the product and engineering goals.

Product goals:
* A healthy product lifecycle
* Strengthening the hypothesis
* North star metrics

Engineering goals:
* Performance
* Availability
* Consistency
* Engineering Productivity
* Extensible
### Analyze a Problem
#### Clearly describe the problem

- Who is facing the problem?
- What problem are they facing?
- What is the impact?
- How much have we lost due to the problem?

#### Does the problem truly exist?

- What's the essence of the problem?

#### Should you be the one to solve this?

- Are there other good candidates to solve this problem?
- Should we collaborate with anyone to solve this?
- Has anyone resolved this problem before? (Inside the company or in industry practice)

### Discuss a Problem

Discuss with different stakeholders:

- Upper management: Identify business pain points and align expectations
- Subordinates: Brainstorm with team members
- XFN engineering teams: Research and align upstream/downstream service collaboration models
- Tech committee: Establish best practices, identify latest technology trends

Four key questions while discussing a problem:

1. What's the correlation with the core business?
2. What would be the impact after resolving this problem, according to our core values and long-term vision?
3. Is there any simpler solution?
4. Is this problem important to my team?

## Step 2: Technical Design

### Principles

The technical design needs to follow the principles below:

- Fit: The design doesn't have to be trending or the latest. It should fit based on the current team capacity and business needs.
- Simple: The structure, logic, and dependency relationships should be simple. There is no silver bullet.
- Evolution: Refactor, extend, or rewrite code along the way if necessary.

### Architecture Overview

Use a pyramid structure to describe the high-level architecture:

1. Background
2. Problem Statements
3. Research Outcome (Optional)
4. Design Overview and Detailed Explanations
5. Execution Steps
6. Impact Estimation
7. Resources Needed

In the Design Overview and Details section, we should use diagrams and images to visualize the architecture. This makes the logic and flow easier to understand.

The Design Overview and Details should also cover the following parts:

- Layout roles and involved cross-functional (XFN) teams
- Objectives and directions separation
- Code module and layer separation
- Data flow diagram
- Strategy pyramid diagram

## Step 3: Execution Plan

### Design the execution plan

#### Separation of concerns with modules

Analyze the module dependencies. Determine whether they can be developed in parallel or not. The modules should satisfy the MECE (Mutually Exclusive Collectively Exhaustive) principle.

#### Prioritization

Prioritize work and projects using the following tools:

- Eisenhower Matrix
- SWOT Analysis
- Find the best ground-hitting project to maximize impact with lowest cost (Amazon Flywheel Theory)
- Team resource estimation

#### Who will take it / Who can take it

- Evaluate the lead capabilities
- Build the team
- Ensure enough cross-functional (XFN) team support

#### Breakdown execution steps

Each objective or direction should have:

- Goal, risks, rewards
- Prioritization, team resource allocation, XFN team
- Concrete tasks
- Set-up milestones

#### Align the Roadmap with stakeholders

- Align the big picture with XFN teams and project details with own team members
- Persuade teams to accept your ideas
- Proactively push all teams forward
- Reject outdated, incorrect methods and replace with new, efficient ones
- Negotiate with teams until consensus is reached

### XFN team Collaboration

#### Basic Principles

- Benefits Alignment: Make sure the roadmap benefits all of the XFN teams
- Empathy: Build trust. Think from the XFN team perspective: Why would they want to help you?

#### Daily Tasks

- Relationship management
- Technical conversations
- Collaboration with business partners

#### Review progress periodically

Check the execution progress at regular intervals. Follow the PDCA cycle.

---
# Reference

https://www.goodreads.com/book/show/1044831.Are_Your_Lights_On_
