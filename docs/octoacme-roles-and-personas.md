# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## QA/Testing Lead

### Role Summary
QA/Testing Leads own the quality assurance strategy, testing methodology, and acceptance criteria validation for a project. They ensure features meet quality standards before release and collaborate with product and development teams to prevent defects.

### Responsibilities
- Define and execute test plans aligned with project scope and quality gates
- Validate that all acceptance criteria are met before features move to done
- Identify, document, and triage defects with severity and impact assessment
- Collaborate with developers on test-driven development and testability
- Conduct manual QA and end-to-end smoke tests before release
- Ensure security and performance testing is completed per project requirements
- Participate in retrospectives to improve testing processes and quality metrics

### Goals
- Maintain high quality standards while supporting rapid iteration
- Reduce production defects through proactive testing and risk identification
- Enable fast, confident releases through comprehensive test coverage
- Build a quality culture where all team members take ownership of quality

### Typical Communication
- Daily standups and sprint planning
- Test case reviews and defect discussions with developers
- Quality metrics and trend analysis in weekly syncs
- Release readiness assessments before deployment

### How it Interacts with Other Roles
- **Product Managers**: Collaborate on acceptance criteria clarity and prioritization of quality concerns
- **Developers**: Partner on test-driven development, investigate defects, and discuss testability
- **Project Managers**: Report quality metrics, escalate blockers, and provide release readiness sign-off
- **Security Champions**: Coordinate on security testing requirements and results

---

## Technical Architect

### Role Summary
Technical Architects design system solutions, evaluate technical trade-offs, and ensure that implementations align with long-term technical strategy. They provide technical guidance on scalability, maintainability, and integration challenges.

### Responsibilities
- Design technical solutions that meet functional and non-functional requirements
- Conduct technical design reviews and provide guidance on implementation approaches
- Identify and assess technical risks, dependencies, and integration points
- Evaluate technology choices and propose solutions for scalability and performance
- Mentor developers on architectural patterns and best practices
- Ensure implementations align with security, compliance, and operational requirements
- Document technical decisions and maintain system architecture documentation

### Goals
- Deliver scalable, maintainable technical solutions
- Reduce technical debt and long-term operational risk
- Enable teams to make informed technical trade-offs
- Foster a culture of architectural thinking and technical excellence

### Typical Communication
- Technical design discussions and code reviews
- Architecture decision logs and design documentation
- Risk assessments in project planning and execution
- Guidance during sprint planning and complex problem-solving

### How it Interacts with Other Roles
- **Developers**: Provide architectural guidance, review designs, and mentor on best practices
- **Product Managers**: Advise on technical feasibility and help prioritize technical debt work
- **Project Managers**: Assess technical risks, estimate complexity, and identify architectural dependencies
- **QA/Testing Leads**: Collaborate on performance, scalability, and integration testing strategies

---

## Security Champion

### Role Summary
Security Champions embed security practices into projects by conducting threat assessments, leading security reviews, and ensuring compliance with security policies. They serve as the primary escalation point for security concerns.

### Responsibilities
- Conduct threat modeling and security risk assessments during planning
- Perform security code reviews and penetration testing assessments
- Ensure security scanning and compliance checks are configured in CI/CD pipelines
- Advise on secure design patterns, authentication, and data handling
- Lead incident response and post-incident security reviews
- Maintain security documentation and communicate security best practices
- Escalate critical security issues and coordinate remediation efforts

### Goals
- Prevent security vulnerabilities from reaching production
- Build security awareness and a culture of shared responsibility
- Ensure compliance with security policies and industry standards
- Minimize security-related incidents and their business impact

### Typical Communication
- Security reviews in design and planning phases
- Code review comments and security issue discussions
- Security incident response and post-incident retrospectives
- Security metrics and compliance status reporting

### How it Interacts with Other Roles
- **Developers**: Partner on secure coding practices, review code for vulnerabilities, and escalate security issues
- **Product Managers**: Advise on security implications of features and help prioritize security work
- **Project Managers**: Assess security risks, escalate incidents, and coordinate security incident response
- **QA/Testing Leads**: Collaborate on security testing, penetration testing, and vulnerability validation

---

## Executive Sponsor

### Role Summary
Executive Sponsors provide executive-level sponsorship, remove organizational blockers, and ensure alignment with business strategy and organizational priorities. They are the ultimate decision authority for go/no-go decisions and priority trade-offs.

### Responsibilities
- Provide executive sponsorship and remove organizational barriers
- Make go/no-go decisions on project initiation and significant milestones
- Ensure alignment with business strategy and organizational priorities
- Authorize resource allocation and budget for the project
- Escalate critical business or political risks
- Communicate project importance to the broader organization
- Review and approve project outcomes and business impact

### Goals
- Ensure projects align with and support business strategy
- Remove organizational blockers that prevent project success
- Maximize business impact and ROI from project investments
- Maintain executive visibility and organizational alignment

### Typical Communication
- Project initiation and approval meetings
- Monthly or quarterly business impact reviews
- Escalation of critical business risks and dependencies
- Executive steering committee updates and presentations

### How it Interacts with Other Roles
- **Project Managers**: Receive escalations on critical business blockers and provide decision authority
- **Product Managers**: Align on business strategy, priorities, and success metrics
- **Stakeholders**: Communicate project importance and strategic alignment
- **Developers**: Occasionally provide context on business priorities and constraints

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference these personas when defining role-specific responsibilities and escalation paths in project processes.
