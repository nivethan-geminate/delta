# Project Team Instructions - AI-Assisted Collaboration Guide

## Overview
This document provides guidelines for the entire team (Product Manager, Business Analyst, Developer, and QA) to collaborate effectively using AI assistance, similar to mob programming principles.

---

## 🎯 General Principles

### AI Mob Collaboration Rules
1. **One Driver, Multiple Navigators**: One person interacts with AI tools while others guide and review
2. **Rotate Regularly**: Switch the "driver" every 15-30 minutes
3. **Think Out Loud**: Verbalize decisions and AI prompts for team learning
4. **Collective Ownership**: All outputs are team responsibilities
5. **Question AI Output**: Always validate and verify AI-generated content

---

## 📋 Product Manager (PM) Instructions

### Responsibilities
- Define product vision and requirements
- Prioritize features and backlog
- Stakeholder communication
- Success metrics definition

### AI-Assisted Tasks
1. **Requirements Gathering**
   ```
   Prompt example: "Generate user story template for [feature] targeting [user persona]"
   ```

2. **Product Roadmap Creation**
   ```
   Prompt example: "Create a quarterly roadmap structure for [product type]"
   ```

3. **Competitive Analysis**
   ```
   Prompt example: "What are key features to analyze when comparing [product category]?"
   ```

4. **Metrics Definition**
   ```
   Prompt example: "Suggest KPIs for measuring success of [feature/product]"
   ```

### Best Practices
- ✅ Always validate AI-generated user stories with real user feedback
- ✅ Use AI for initial drafts, refine with team input
- ✅ Document decisions and rationale alongside AI suggestions
- ❌ Don't rely solely on AI for prioritization decisions
- ❌ Don't share sensitive business data with AI tools

---

## 📊 Business Analyst (BA) Instructions

### Responsibilities
- Requirements analysis and documentation
- Process mapping and optimization
- Bridge between business and technical teams
- Acceptance criteria definition

### AI-Assisted Tasks
1. **Requirements Documentation**
   ```
   Prompt example: "Convert this meeting transcript into functional requirements for [system]"
   ```

2. **Use Case Development**
   ```
   Prompt example: "Generate use case scenarios for [user role] interacting with [feature]"
   ```

3. **Process Flow Creation**
   ```
   Prompt example: "Describe the process flow for [business process] in steps"
   ```

4. **Gap Analysis**
   ```
   Prompt example: "Compare current state [X] with desired state [Y] and identify gaps"
   ```

5. **Acceptance Criteria Writing**
   ```
   Prompt example: "Generate acceptance criteria for user story: [story]"
   ```

### Best Practices
- ✅ Validate requirements with stakeholders before finalizing
- ✅ Use AI to identify edge cases and scenarios
- ✅ Create templates for consistency across documentation
- ❌ Don't accept AI-generated requirements without domain validation
- ❌ Don't skip stakeholder review sessions

---

## 💻 Developer (Dev) Instructions

### Responsibilities
- Code implementation
- Technical architecture decisions
- Code reviews
- Technical documentation

### AI-Assisted Tasks
1. **Code Generation**
   ```
   Prompt example: "Implement [function/feature] in [language] following [pattern/standard]"
   ```

2. **Code Review**
   ```
   Prompt example: "Review this code for security vulnerabilities, performance issues, and best practices: [code]"
   ```

3. **Debugging**
   ```
   Prompt example: "Explain this error and suggest fixes: [error message and context]"
   ```

4. **Refactoring**
   ```
   Prompt example: "Refactor this code to improve readability and maintainability: [code]"
   ```

5. **Documentation**
   ```
   Prompt example: "Generate API documentation for this endpoint: [code]"
   ```

6. **Test Case Creation**
   ```
   Prompt example: "Generate unit tests for this function: [code]"
   ```

### Best Practices
- ✅ Always review and understand AI-generated code before committing
- ✅ Test all AI-generated code thoroughly
- ✅ Use AI for boilerplate and repetitive tasks
- ✅ Verify security implications of AI suggestions
- ❌ Don't blindly copy-paste code without understanding
- ❌ Don't commit untested AI-generated code
- ❌ Don't share proprietary code or sensitive data

### Code Quality Checklist
- [ ] Code follows team standards and conventions
- [ ] All edge cases are handled
- [ ] Error handling is implemented
- [ ] Code is properly tested
- [ ] Documentation is complete
- [ ] Security considerations are addressed

---

## 🧪 Quality Assurance (QA) Instructions

### Responsibilities
- Test planning and strategy
- Test case design and execution
- Bug reporting and tracking
- Quality metrics and reporting

### AI-Assisted Tasks
1. **Test Case Generation**
   ```
   Prompt example: "Generate test cases for [feature] covering positive, negative, and edge cases"
   ```

2. **Test Data Creation**
   ```
   Prompt example: "Generate test data for [scenario] with [constraints]"
   ```

3. **Bug Report Enhancement**
   ```
   Prompt example: "Improve this bug report with steps to reproduce: [initial report]"
   ```

4. **Test Automation Scripts**
   ```
   Prompt example: "Generate Selenium/Cypress test script for [user flow]"
   ```

5. **API Testing**
   ```
   Prompt example: "Create API test cases for [endpoint] with various payloads"
   ```

6. **Exploratory Testing Guidance**
   ```
   Prompt example: "Suggest exploratory testing scenarios for [feature]"
   ```

### Best Practices
- ✅ Validate AI-generated test cases against requirements
- ✅ Execute AI-generated tests and verify results
- ✅ Use AI to identify missing test scenarios
- ✅ Combine AI suggestions with domain expertise
- ❌ Don't rely solely on AI-generated test coverage
- ❌ Don't skip manual exploratory testing
- ❌ Don't assume AI understands all business rules

### Testing Checklist
- [ ] All acceptance criteria are covered
- [ ] Positive and negative scenarios tested
- [ ] Edge cases identified and tested
- [ ] Integration points verified
- [ ] Performance tested (if applicable)
- [ ] Security tested (if applicable)
- [ ] Accessibility checked (if applicable)

---

## 🤝 Cross-Functional Collaboration

### Daily AI Mob Sessions
1. **Morning Stand-up Enhancement** (15 min)
   - Use AI to generate sprint progress summary
   - Identify blockers and get AI suggestions for solutions

2. **Refinement Sessions** (60 min)
   - PM shares requirement → BA uses AI to draft detailed specs
   - Dev estimates complexity with AI assistance
   - QA generates test scenarios using AI
   - Team reviews and refines all outputs together

3. **Problem-Solving Sessions** (30-45 min)
   - Team identifies problem
   - One person drives AI interaction
   - Others navigate and validate suggestions
   - Document decisions and rationale

### Mob Programming/Working Sessions
**Setup:**
- One screen shared with entire team
- One person interacts with AI (driver)
- Others provide input, questions, validation (navigators)
- Rotate driver every 15-30 minutes

**Session Flow:**
1. **Define**: PM/BA clarifies what needs to be built
2. **Design**: Team discusses approach, uses AI for suggestions
3. **Develop**: Dev implements with AI assistance
4. **Review**: QA validates and suggests test scenarios
5. **Document**: Team ensures all artifacts are complete

---

## 🛠️ Recommended AI Tools by Role

### All Roles
- **GitHub Copilot Chat**: Code and documentation assistance
- **ChatGPT/Claude**: General problem-solving and content generation
- **Miro AI**: Collaborative diagramming and brainstorming

### PM-Specific
- **AI Product Management Tools**: Roadmap generation, user story creation
- **Analytics AI**: Data interpretation and insights

### BA-Specific
- **Process Mining AI**: Process discovery and optimization
- **Documentation AI**: Requirements and specification generation

### Dev-Specific
- **GitHub Copilot**: Code completion and generation
- **AI Code Review Tools**: Automated code analysis
- **AI Debugging Tools**: Error diagnosis and fixes

### QA-Specific
- **Test Case Generation AI**: Automated test scenario creation
- **AI Testing Platforms**: Intelligent test automation
- **Bug Analysis AI**: Root cause analysis

---

## 🚨 Common Pitfalls to Avoid

### For All Team Members
1. **Over-reliance on AI**: Always apply critical thinking
2. **Skipping Validation**: Every AI output needs human review
3. **Ignoring Context**: AI doesn't know your specific business rules
4. **Security Risks**: Don't share sensitive data with AI tools
5. **Lack of Documentation**: Document why decisions were made
6. **Not Learning**: Use AI as a learning tool, not just automation

### Role-Specific Warnings

**PM:**
- Don't let AI make strategic decisions
- Don't skip user research in favor of AI insights

**BA:**
- Don't accept AI-generated requirements without stakeholder validation
- Don't assume AI understands domain-specific terminology

**Dev:**
- Don't commit code you don't understand
- Don't ignore security implications of AI suggestions
- Don't skip code reviews

**QA:**
- Don't assume AI-generated tests provide complete coverage
- Don't skip manual exploratory testing
- Don't trust AI for compliance/regulatory testing without validation

---

## 📈 Success Metrics

### Team Collaboration Metrics
- Reduced time from requirement to implementation
- Improved documentation quality and completeness
- Faster issue resolution
- Increased knowledge sharing across roles

### Individual Role Metrics
**PM:** Faster requirements documentation, better-defined success criteria
**BA:** More comprehensive use cases, reduced ambiguity in requirements
**Dev:** Faster implementation, fewer bugs, better code quality
**QA:** Increased test coverage, faster test case creation, earlier defect detection

---

## 🔄 Continuous Improvement

### Weekly Retrospective Questions
1. How effectively did we use AI this week?
2. What AI-generated outputs needed significant revision?
3. Where did AI save us time?
4. Where did AI create additional work?
5. What new AI techniques should we try?

### Monthly Reviews
- Review AI tool effectiveness
- Update prompts and templates
- Share learnings across team
- Adjust collaboration processes

---

## 📚 Learning Resources

### AI Prompt Engineering
- Learn effective prompt writing techniques
- Build a library of successful prompts
- Share and refine prompts as a team

### AI Ethics and Governance
- Understand AI limitations and biases
- Follow data privacy guidelines
- Maintain human accountability

---

## 🎓 Onboarding New Team Members

### Week 1: AI Fundamentals
- Introduction to AI tools used by team
- AI ethics and security training
- Shadow experienced team members

### Week 2: Role-Specific AI Usage
- Practice with role-specific AI tasks
- Review prompt templates
- Participate in mob sessions as navigator

### Week 3: Active Participation
- Take driver role in mob sessions
- Create and share own prompts
- Provide feedback on AI outputs

---

## 📞 Support and Questions

### When You're Stuck
1. Ask the team first
2. Use AI to explore solutions
3. Document the solution for others
4. Update this guide with learnings

### Escalation Path
1. Team discussion
2. Tech lead / Senior team member
3. Management (for process/tool decisions)

---

## 🔒 Security and Compliance

### Data Handling Rules
- ❌ Never share: Customer data, credentials, proprietary algorithms, unreleased features
- ✅ OK to share: Public documentation, open-source code, general technical concepts
- ⚠️ Use caution: Internal process descriptions, architecture patterns

### Compliance Checklist
- [ ] AI tool is approved by security team
- [ ] Data shared with AI is classified as public or approved
- [ ] AI-generated code reviewed for license compliance
- [ ] Security vulnerabilities checked in AI outputs
- [ ] Audit trail maintained for AI-assisted decisions

---

## 📝 Version History

| Version | Date | Changes | Author |
|---------|------|---------|--------|
| 1.0 | 2026-02-14 | Initial creation | Team |

---

## 📄 License and Usage

This document is for internal team use. Update regularly based on team feedback and evolving AI capabilities.

**Last Updated:** 2026-02-14
**Next Review Date:** 2026-03-14
