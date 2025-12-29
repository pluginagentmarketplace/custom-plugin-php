---
name: testing-quality
description: Master testing strategies and quality assurance. Covers unit testing, integration testing, E2E testing, automation frameworks, and testing best practices.
sasmp_version: "1.3.0"
bonded_agent: 01-web-frontend
bond_type: PRIMARY_BOND
---

# Testing & Quality Assurance Skill

Master testing strategies and quality practices.

## Testing Types

### Unit Testing
- Testing individual functions
- Test isolation with mocks/stubs
- Fast feedback
- High code coverage goal
- Tools: Jest, Vitest, PyTest, JUnit

### Integration Testing
- Testing component interactions
- Database integration
- External service mocking
- Slower than unit tests
- Tools: Pytest, TestNG, Mocha

### End-to-End (E2E) Testing
- Full application workflows
- Real browser/device
- Slow but comprehensive
- Catch UI and integration bugs
- Tools: Playwright, Cypress, Selenium

### Performance Testing
- Load testing - concurrent users
- Stress testing - peak loads
- Endurance testing - sustained load
- Tools: JMeter, K6, Artillery, Gatling

### Security Testing
- OWASP vulnerabilities
- SQL injection, XSS, CSRF
- Penetration testing
- Tools: Burp Suite, OWASP ZAP, Snyk

### Accessibility Testing
- WCAG compliance
- Screen reader compatibility
- Keyboard navigation
- Tools: Axe, WAVE, Lighthouse

## Frontend Testing

### Unit Testing
- Jest - JavaScript testing
- Vitest - Vite-native testing
- React Testing Library - Component testing
- Vue Test Utils - Vue component testing

### E2E Testing
- **Playwright** - Modern, reliable, multi-browser
- **Cypress** - Developer-friendly
- **Selenium** - Mature but complex
- **Puppeteer** - Headless Chrome automation

### Visual Testing
- Screenshot comparisons
- Percy, Chromatic tools
- Regression detection

## Backend Testing

### Unit Testing
- PyTest (Python)
- JUnit (Java)
- Go testing package
- Rust #[cfg(test)]

### API Testing
- **Postman** - Manual and automated
- **REST Assured** - Java framework
- **Supertest** - Node.js API testing
- **Requests** - Python HTTP library

### Database Testing
- Test fixtures and factories
- In-memory databases (H2, SQLite)
- Database migrations testing

## Testing Frameworks

### JavaScript/TypeScript
- **Jest** - All-in-one testing
- **Vitest** - Fast alternative
- **Mocha** - Flexible runner
- **Cypress** - E2E focused

### Python
- **PyTest** - Powerful and simple
- **Unittest** - Built-in
- **Nose2** - Unittest extension

### Java
- **JUnit** - Industry standard
- **TestNG** - Advanced features
- **Mockito** - Mocking library
- **Selenium** - Web automation

### Go
- Built-in testing package
- **Testify** - Assertions and mocks
- **GoConvey** - BDD-style testing

## Best Practices

1. **Write Tests First** (TDD)
   - Write failing test
   - Implement feature
   - Refactor and optimize

2. **Good Test Characteristics**
   - Isolated (no dependencies)
   - Fast (quick feedback)
   - Reliable (consistent results)
   - Descriptive (clear intent)

3. **Coverage Goals**
   - 70-80% overall coverage
   - 90%+ for critical paths
   - 100% for core business logic

4. **Test Organization**
   - AAA Pattern: Arrange, Act, Assert
   - Descriptive test names
   - Test per use case
   - Avoid test interdependencies

5. **Mocking & Stubbing**
   - Mock external dependencies
   - Stub slow operations
   - Test behavior, not implementation

## Test Automation

### CI/CD Integration
- Run tests on every commit
- Fail build if tests fail
- Parallel test execution
- Coverage reports

### Test Environments
- Staging environment
- Test data management
- Isolated test infrastructure
- Cleanup after tests

## Quality Metrics

- **Code Coverage** - % of code tested
- **Defect Density** - Bugs per 1000 lines
- **Test Pass Rate** - % passing tests
- **MTTR** - Mean time to recovery
- **Deployment Frequency** - How often to production

## Recommended Learning Path

1. Unit testing fundamentals
2. Mocking and test isolation
3. Integration testing
4. E2E testing with Cypress or Playwright
5. Performance testing basics
6. Test automation in CI/CD
7. Specialized testing (security, accessibility)

---

[Explore Testing on Roadmap.sh](https://roadmap.sh/)