# Job board platform: A simplistic job platform, built with a microservices pattern.

The purpose of this project is educational and throughout implementing this project, we will be able to learn and practice all studied concepts of microservices architecture as well as a few common design patterns.

## 1. Introduction

This simple job platform project is intended to offer an integrated system in which employers are able to post jobs and job seekers can apply for them.

The employers will have an exclusive panel for managing job posts and reviewing job applications.

On the other hand, job seekers will also have a different panel for building CVs and reviewing the history of their applications.

This is a .Net based project but it is likely to include some other technologies thanks to the microservices platform independent feature.

## 2. Tech Stacks and Decided Infrastructres

This is a .Net based project but it is likely to include some other technologies thank to the microservices platform independent feature.

 - The main tech stack used in this project is **Microsoft .Net** with the latest version possible.

 - Most of the APIs and services will be built with **ASP.Net core** and will be containerized with **Docker containers**.

 - Orchestration will be possible using **Kubernetes**.

 - The message broker will be **RabbitMQ**.

 - As of now, relational database will be **PostgreSQL** and document base database will be **MongoDB**. (TBD)

## 3. Road Map

To make the progress simple, the project is split into a few phases.

**Note:** This road map is highly possible to change in the future

### Phase I
 - [ ] Employer panel for job posting.
 - [ ] Job seeker panel.
 - [ ] CV builder.
 - [ ] Public website.
 - [ ] Generic static file manager.

### Phase II
 - [ ] Freelancer platform.
 - [ ] Extending employer panel for project definition.
 - [ ] Biding and escrows.
 - [ ] Freelancer performance history system.

### Phase III

 - [ ] Blogging and content building system.

### Phase IV
 - [ ] Online learning platform

## 4. Why Microservices?

Microservices architecture concepts are both complex and complicated. You might heard this famous quote that says:

> The best advice on microservices, is not to go microservices.

The reason is quite simple; The architecture introduces many complexities and new challenges while they are nonexistent in a monolithic system.

Each design pattern and architecture are like medicines I believe; They have some side effects while solving a problem.
We need to make sure what are we trading off when implementing those.
Of course, it wouldn't make sense to implement a design pattern if we don't have any problem that they solve.
This way we gain nothing and at the same time, we are creating new problems.

Starting a project with a microservices pattern from scratch is also considered as a foul.

With all being said, Microservices are still a powerful tool for large-scale projects.

Adding this powerful tool to our toolbox requires practice and some trials and errors.

Starting educational projects like this can assist us to grasp the concepts by trying them out, facing the challenges, and solving them.
