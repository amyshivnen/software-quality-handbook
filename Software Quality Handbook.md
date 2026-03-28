# Software Quality Handbook 

Intro to handbook 
Team Guide 

---

## Table of Contents 
- [Testing : unit/integration testing]
- [CI/CD pipelines]
- [Bug Tracking & QA processes]

### Testing : Unit/Integration Testing 

Testing is an important part of building reliable software. It helps developers check that code works as expected and catches problems before they reach production.

In our team, testing has not always been done consistently. This has made progress less predictable and has allowed bugs to slip into live systems. Without a shared approach, it is harder to trust code changes and maintain quality across projects.

This section focuses on two main types of testing:
- Unit testing – testing small parts of the code on their own
- Integration testing – testing how different parts of the system work together

Using both types of testing helps reduce defects, improve confidence in changes, and make releases more stable. This section gives practical guidelines, common mistakes to avoid, and useful resources for further reading.

READ MORE ABOUT OUR UNIT/INTEGRATION TESTING PROCESSES : 
[Go to Unit/Integration Testing Guide](testing.md)

### CI/CD Pipelines 

Continuous Integration and Continuous Deployment (CI/CD) pipelines are a set of automated processes that allow development teams to build, test, and release software more efficiently and reliably. Instead of manually handling each stage of development, CI/CD introduces automation to streamline the entire software delivery lifecycle.

Continuous Integration (CI) focuses on regularly merging code changes into a shared repository, where automated builds and tests are run to detect issues early. Continuous Deployment (CD) extends this process by automatically releasing tested code into production or staging environments, reducing the time between development and delivery.

By automating key stages such as testing and deployment, CI/CD pipelines help teams identify bugs earlier, improve code quality, and reduce the risk of errors in production. This leads to faster development cycles and more consistent releases.

Overall, CI/CD pipelines enable teams to respond quickly to changes, deliver updates more frequently, and maintain a high standard of software quality in fast-moving environments.

READ MORE ABOUT OUR CI/CD PIPELINE PROCESSES : 
[Go to CI/CD Guide](cd-pipelines.md)

### Bug Tracking & QA Processes 

Bug Tracking and Quality Assurance(QA) are processes used to ensure that software is reliable, functional, and meets user expectations before and after release. 

- Bug Tracking is the process of identifying, recording, prioritising, and resolving defects(bugs) in the system.

- Quality Assurance (QA) is a broader practice focused on preventing defects by improving development and testing processes.

Together, they ensure that issues are not only fixed, but also systematically prevented in the future. 

Goal: Deliver high-quality software with minimal defects, while maintaining fast and efficient development in a startup environment.

READ MORE ABOUT OUR BUG TRACKING & QA PROCESSES : 
[Go to CI/CD Guide](bug-tracking&QA-processes.md)