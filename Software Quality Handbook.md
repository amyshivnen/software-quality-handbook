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
Intro : what is it?
Goal : 

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
