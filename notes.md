**Types of Tests:**

- Unit Tests
Usually pretty simple, test whether a single method will spit out the correct outputs based on inputs you give it
- Integration Tests
More complex, you usually have to spin up a server, hit an endpoint, maybe DB up and running - usually backend stuff
- E2E Tests
Pull up the entire application and go through - as close as possible - it like an end user would
- Acceptance Tests
- Regression Tests
- Performance Tests
- Stress Tests
- Penetration Tests
- Accessibility (a11y)
- Smoke Tests


The more closely your tests resemble how the software is actually used, the more value the test has

Make sure all your assertions are actually running. You could test this by breaking the source code and making sure
every assertion breaks, which means all assertions are running.