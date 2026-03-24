# Software Quality Handbook 

Intro to handbook 
Team Guide 

---

## Table of Contents 
- [Testing : unit/integration testing]
- [CI/CD pipelines]
- [Bug Tracking & QA processes]
- [Best Practices]

### Testing : Unit/Integration Testing 
Intro 

Topic Info

Conclusion



### CI/CD Pipelines 

Continuous Integration and Continuous Deployment (CI/CD) pipelines are a set of automated processes that allow development teams to build, test, and release software more efficiently and reliably. Instead of manually handling each stage of development, CI/CD introduces automation to streamline the entire software delivery lifecycle.

Continuous Integration (CI) focuses on regularly merging code changes into a shared repository, where automated builds and tests are run to detect issues early. Continuous Deployment (CD) extends this process by automatically releasing tested code into production or staging environments, reducing the time between development and delivery.

By automating key stages such as testing and deployment, CI/CD pipelines help teams identify bugs earlier, improve code quality, and reduce the risk of errors in production. This leads to faster development cycles and more consistent releases.

Overall, CI/CD pipelines enable teams to respond quickly to changes, deliver updates more frequently, and maintain a high standard of software quality in fast-moving environments.

---

## CI/CD Pipeline Overview 

```md 
## CI/CD Lifecycle 
![CI/CD Pipeline](images/CI-CD-Pipeline-diagram)

## How it Works
1. Commit - Developer pushes code 
2. Build - Code compiles + dependencies install
3. Test - Automated tests run 
4. Deploy - App released to staging/production
5. Monitor - Performance + errors tracked 

## Guidelines 
Do: 
- Use one CI/CD tool (GitHub)
- Keep Pipelines simple
- Standardise templates 

Avoid: 
- Over-engineering
- Too many tools 
- Manual QA bottlenecks 

## Good vs. Bad CI/CD
![CI/CD Pipeline](images/gooc-vs-bad-Pipeline)

## Core Rules
- Commit small changes frequently
- Every commit triggers CI 
- No manual demployments 
- Keep builds fast (<10 mins)
- Use dev -> staging -> production 
- Always support rollback 

# Developer Checklist 
Before pushing : 
[] Code compiles
[] Test pass 
[] No secrets in code 
[] Changes are small

After pipeline : 
[] Build passed 
[] Tests passed
[] Deployment successful
[] No alerts 

---

## Conclusion



### Bug Tracking & QA Processes 

---

## What is Bug Tracking & QA Processes? 
Bug Tracking and Quality Assurance(QA) are processes used to ensure that software is reliable, functional, and meets user expectations before and after release. 

- Bug Tracking is the process of identifying, recording, prioritising, and resolving defects(bugs) in the system.

- Quality Assurance (QA) is a broader practice focused on preventing defects by improving development and testing processes.

Together, they ensure that issues are not only fixed, but also systematically prevented in the future. 

Goal: Deliver high-quality software with minimal defects, while maintaining fast and efficient development in a startup environment.

---

## Topic Info 

## Conclusion 
