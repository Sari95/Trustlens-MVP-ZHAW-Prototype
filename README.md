# Trustlens-MVP - ZHAW-Prototype
Trustlens is a students project from Zurich University of Applied Science, Centre for AI, Responsible AI Group.

This MVP is based on trustworthiness guidelines from the EU and displays relevant questions for the given context (role, AI-Lifecycle-Stages, and TRL-Stages).

## Roles in the tool
The tool distinguishes between three key roles that reflect different perspectives and responsibilities in the AI lifecycle.
Each role focuses on a specific aspect of developing and maintaining trustworthy AI systems, as defined within the context of this student project.

### Developer
**Main focus: Technical implementation and data responsibility**

Developers prepare and process data, train and validate AI models, and ensure technical robustness and reproducibility.
They also apply privacy-by-design principles, perform bias detection and mitigation, and manage version control or monitoring pipelines (e.g., MLOps).

Example tasks:
- Preparing datasets and cleaning data
- Training, testing, and documenting models
- Implementing data protection and security measures
- Automating reproducible workflows

### Designer
**Main focus: Human-centered design and ethical use**

Designers define how the AI system will be used and experienced.
They focus on user interaction, feedback mechanisms, fairness, and accessibility.
Their goal is to ensure transparency, inclusiveness, and clarity in system design and communication.

Example tasks:
- Designing user interfaces and feedback loops
- Communicating system limitations
- Ensuring fairness and accessibility in design
- Documenting ethical considerations

### Assessor
**Main focus: Governance, risk, and compliance**

Assessors evaluate AI systems from a governance and accountability perspective.
They conduct audits, ensure ethical and legal compliance, and monitor deployed systems for risks or unintended impacts.

Example tasks:
- Conducting AI system audits and compliance checks
- Reviewing ethical, legal, and social implications
- Monitoring models after deployment for bias or drift
- Approving AI models for production use

## AI Lifecycles in the tool
The tool is structured around the main stages of the AI lifecycle. Descriptions are based on the NIST AI Risk Management Framework (https://nvlpubs.nist.gov/nistpubs/ai/NIST.AI.100-1.pdf)

### 1. Plan / Design
Define the system’s objectives, context, and underlying assumptions. Identify stakeholders, requirements, and constraints.
Consider ethical, legal, and societal implications before development begins.

Examples: defining project goals, identifying users and risks, ensuring feasibility and ethical compliance.

### 2. Collect / Process Data
Gather, document, and preprocess data. Ensure data quality, relevance, fairness, and compliance with privacy and data governance standards.

Examples: data collection, cleaning, validation, and documentation of metadata and sources.

### 3. Build / Use Model
Design model architectures, choose algorithms, train models, and tune parameters.
Focus on fairness, robustness, and explainability throughout the model development process.

Examples: model design, feature engineering, algorithm selection, parameter tuning, bias mitigation.

### 4. Verify / Validate
Evaluate and test model performance and reliability.
Validate outputs, assess accuracy, reproducibility, and potential risks. Ensure results meet defined goals and ethical standards.

Examples: model testing, cross-validation, risk analysis, performance evaluation, reproducibility checks.

### 5. Deploy / Use
Integrate and deploy the AI system into production or organizational workflows.
Verify compatibility, compliance, and user acceptance. Manage operational readiness and documentation.

Examples: deployment testing, release management, integration into business systems, compliance verification.

### 6. Operate / Monitor
Continuously monitor the system’s performance and impact.
Detect drifts, biases, or malfunctions. Implement mechanisms for oversight, accountability, and model updates.

Examples: performance monitoring, error tracking, drift detection, ongoing maintenance and auditing.

### 7. Used / Impacted By
Assess the system’s real-world impact on users and society.
Gather feedback, identify unintended consequences, and take corrective actions to mitigate harm.

Examples: user feedback analysis, societal impact review, transparency reporting, corrective measures.

## TRL Stages in the tool
The tool also aligns with the Technology Readiness Levels (TRL) framework to reflect the maturity of AI systems — from early research to operational deployment.

### 1. Research (TRL 1–3)
Early-stage exploration and experimentation.
This phase involves literature review, hypothesis formulation, data collection, and initial algorithm design.
Bias detection, ethical assessment, and documentation of assumptions are key elements at this level.

Examples:
- Exploratory model testing
- Data collection and preprocessing
- Risk identification (ethical and social)
- Early bias and fairness checks

### 2. Development (TRL 4–6)
Model building, validation, and iterative testing.
This stage focuses on explainability, safety validation, and robustness assessments, including the integration with data pipelines or interfaces.
Security, privacy, and deployment readiness are also considered.

Examples:
- Model validation and testing
- Explainability evaluations
- Integration with data pipelines
- Internal audit and documentation

### 3. Deployment & Operation (TRL 7–9)
Integration of AI systems into production environments.
Includes human-in-the-loop mechanisms, continuous monitoring, and feedback loops for safety and accountability.
Emphasis is placed on real-world explainability, post-deployment risk mitigation, and sustainability.

Examples:
- Production deployment and monitoring
- Incident management and audit logging
- User explainability and transparency
- Post-deployment impact assessment
