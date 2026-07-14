# Quality Assurance & Testing Checklist

This checklist helps QA/Testing Leads establish and maintain quality standards throughout the project lifecycle.

## Pre-Sprint Planning
- [ ] Review acceptance criteria with Product Manager and Developer
- [ ] Identify testing scope (unit, integration, end-to-end, manual)
- [ ] Determine test automation opportunities for regression prevention
- [ ] Assess resource needs (tools, test data, environments)
- [ ] Schedule test planning kickoff if complex feature

## Sprint Execution
- [ ] Develop test cases aligned to acceptance criteria
- [ ] Set up test data and environments
- [ ] Execute manual test scenarios daily/continuously
- [ ] Monitor automated test execution in CI/CD pipeline
- [ ] Log and triage defects with clear reproduction steps
- [ ] Track test coverage metrics
- [ ] Communicate blockers to Project Manager and Technical Lead

## Quality Gate (Pre-Release)
- [ ] Verify all acceptance criteria have been tested and passed
- [ ] Review test coverage against requirements (target: >80% for critical flows)
- [ ] Execute smoke tests on staging environment
- [ ] Validate no critical or high-severity defects remain
- [ ] Confirm automated tests pass in CI/CD
- [ ] Document any known issues and workarounds
- [ ] Sign off on release readiness

## Post-Release
- [ ] Execute smoke tests in production environment
- [ ] Monitor production for anomalies
- [ ] Track defect escape rate
- [ ] Conduct blameless post-mortem if production issues occur
- [ ] Capture learnings and update test strategy

## Ongoing Responsibilities
- [ ] Maintain regression test suite
- [ ] Review and update test automation frameworks
- [ ] Track and report quality metrics to stakeholders
- [ ] Identify trends in defect types and root causes
- [ ] Participate in retrospectives to improve QA processes
- [ ] Support developers on test-driven development practices
