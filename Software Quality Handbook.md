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

Testing is an important part of building reliable software. It helps developers check that code works as expected and catches problems before they reach production.

In our team, testing has not always been done consistently. This has made progress less predictable and has allowed bugs to slip into live systems. Without a shared approach, it is harder to trust code changes and maintain quality across projects.

This section focuses on two main types of testing:
- Unit testing – testing small parts of the code on their own
- Integration testing – testing how different parts of the system work together

Using both types of testing helps reduce defects, improve confidence in changes, and make releases more stable. This section gives practical guidelines, common mistakes to avoid, and useful resources for further reading.






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

CI/CD pipelines play an important role in improving software quality by making builds, testing, and deployments more consistent and reliable. In a fast-moving team, relying on manual processes increases the chance of delays, missed issues, and production errors. A clear CI/CD process helps reduce these risks by ensuring that code is checked and released in a more structured way.

The main value of CI/CD is not just speed, but consistency. When every change goes through the same automated process, the team can catch problems earlier, release updates more confidently, and maintain a more stable product. Over time, this supports better collaboration, fewer defects, and a more predictable development workflow.

Overall, CI/CD should be treated as a core part of the development process rather than an optional extra. When kept simple, fast, and reliable, it helps the team deliver software more efficiently while maintaining a higher standard of quality.


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
