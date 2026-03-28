## Testing (Unit & Integration)

### Introduction

Testing is an important part of building reliable software. It helps developers check that code works as expected and catches problems before they reach production.

In our team, testing has not always been done consistently. This has made progress less predictable and has allowed bugs to slip into live systems. Without a shared approach, it is harder to trust code changes and maintain quality across projects.

This section focuses on two main types of testing:
- Unit testing – testing small parts of the code on their own
- Integration testing – testing how different parts of the system work together

Using both types of testing helps reduce defects, improve confidence in changes, and make releases more stable. This section gives practical guidelines, common mistakes to avoid, and useful resources for further reading.

### Key Practices

- Write small and focused unit tests that test one piece of functionality at a time  
- Run tests automatically as part of the development process  
- Use integration tests to ensure different parts of the system work together correctly  
- Keep tests independent so they do not rely on each other  
- Run tests frequently to catch issues early  

### Bad Practices to Avoid

- Relying too much on manual testing  
- Writing tests that are slow or difficult to maintain  
- Ignoring failing tests  
- Not testing edge cases or unusual inputs  
- Having inconsistent testing practices across the team  

### Test Pyramid Diagram
               [ End-to-End Tests ]
       ---------------------
      [ Integration Tests ]
     -----------------------
    [     Unit Tests      ]
   -------------------------

The test pyramid shows the recommended balance of tests in a project:

- **Unit Tests (bottom):** Fast, small tests that cover most of the code  
- **Integration Tests (middle):** Test how components work together  
- **End-to-End Tests (top):** Full system tests, slower and fewer in number  

A good testing strategy focuses on having many unit tests, fewer integration tests, and minimal end-to-end tests to keep the test suite fast and reliable.

## Conclusion 
Testing should be consistent and an essential part of how we build software, not something added at the end. By combining unit and integration testing, the team can catch issues earlier, reduce bugs in production, and improve overall confidence in code changes. 

A strong testing approach helps make deveopment more predictable and reduce the risk of breaking existing features. It also makes it easier for new team members to understand and safely contribute to the codebase. 

Going forward, the goal is to treat testing as a shared responsibility across the team. By following the practices outlined above and avoiding common mistakes, we can build a more reliable, maintainable, and scalable system. 