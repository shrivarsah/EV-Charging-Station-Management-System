# EV Charging Station Management System

A small runnable project prepared for SonarQube/SonarQube Cloud analysis.

## Requirements
- Node.js 18+
- npm
- Git
- SonarQube Cloud account (for cloud analysis)

## Run the project

```bash
npm install
npm start
```

Open:
http://localhost:3000

## Run tests and coverage

```bash
npm test
```

Coverage is generated in `coverage/` and the LCOV report is available at:
`coverage/lcov.info`

## SonarQube local scanner

After installing/configuring SonarScanner:

```bash
sonar-scanner
```

For SonarQube Cloud, connect the GitHub repository to SonarQube Cloud and use the generated project analysis instructions/token.

## Main metrics
The SonarQube analysis can report:
- Lines of Code
- Complexity / Cyclomatic Complexity
- Coverage
- Duplications
- Bugs
- Vulnerabilities
- Code Smells
- Technical Debt
- Security Hotspots
- Quality Gate

The project-specific metrics from the academic report should be calculated from application measurements:
- Charging Workflow Efficiency
- Station Availability Response Index
