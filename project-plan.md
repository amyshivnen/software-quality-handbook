# Project Plan

## Project Overview
The goal of this project is to create a **Software Quality Handbook** for a small startup team of 20 software engineers. The handbook will define best practices that engineers should follow to improve code quality, reduce defects in production, and ensure more predictable project progress.

The handbook will cover three main topics:

- Task Estimation in Scrum
- Code Reviews
- Automated Testing

Each section will summarize practical guidelines based on real-world engineering experiences and include links to useful articles and resources.

The final handbook will be hosted in a **public GitHub repository** using Markdown for formatting. Images and diagrams will be used where possible to clearly explain processes and best practices.

---

## Development Process

The team will follow a **Trunk-Based Development workflow** using Git and GitHub.

The workflow will be:

1. Work is divided into small tasks.
2. Each task is completed in a **feature branch**.
3. Developers commit regularly to their branch.
4. A **Pull Request (PR)** is created to merge into the `main` branch.
5. Another team member reviews the PR.
6. After approval, the changes are merged into `main`.

Example branch names:

- feature/project-plan
- feature/task-estimation
- feature/code-reviews
- feature/automated-testing
- feature/diagrams

---

## Project Tasks and Responsibilities

| Task | Description | Assigned To |
|-----|-------------|-------------|
| Create GitHub repository | Set up repository structure and README | Bjorn |
| Create project plan | Define tasks and responsibilities | Bjorn |
| Define handbook structure | Create markdown files and folders | Agnetha |
| Research Task Estimation | Find 5 articles and identify themes | Bjorn, Benny |
| Write Task Estimation section | Summarise best practices | Bjorn |
| Research Code Reviews | Find articles about code review practices | Agnetha |
| Write Code Review section | Write guidelines and examples | Agnetha, Benny |
| Research Automated Testing | Find resources and examples | Benny |
| Write Automated Testing section | Create best practice guidelines | Benny, Agnetha |
| Create diagrams | Visual explanations for processes | Benny |
| Review formatting | Ensure consistent markdown formatting | Agnetha |
| Peer review content | Review pull requests and suggest improvements | All team members |
| Final review | Check overall quality and clarity | Bjorn |
| Write retrospective | Reflect on team workflow and improvements | All team members |

---

## Repository Structure

The repository will contain the following structure:
software-quality-handbook
│
├── README.md
├── project-plan.md
├── retrospective.md
├── contributions.md
│
├── task-estimation.md
├── code-reviews.md
├── automated-testing.md
│
└── images/

Each topic file will include:

- A short introduction
- Key best practices
- Bad practices to avoid
- Diagrams or visual explanations
- Links to reference articles

---

## Collaboration

All team members are expected to contribute to the repository.

Team collaboration will include:

- Regular commits to feature branches
- Pull request reviews by other team members
- Shared responsibility for improving content
- At least two members contributing to each topic

This process helps maintain consistent quality and ensures that the handbook reflects the experience and knowledge of the whole team.

---

## Success Criteria

The project will be successful if:

- The handbook clearly explains software quality best practices.
- Each topic contains well-researched guidelines.
- The GitHub repository shows clear collaboration between team members.
- The handbook is easy to read and well structured.
- Diagrams and examples help explain important concepts.