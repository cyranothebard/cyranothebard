# Brandon Lewis

_Preview draft for profile README review. Live profile README remains in README.md._

> I build at the boundary between industrial systems, data and AI, and production software.

I work on industrial AI and data/AI solution architecture with a foundation in industrial engineering and automation. My work has progressively expanded the portion of technical problems I can own: from operational systems and data foundations, to knowledge and decision intelligence, to production-oriented AI delivery.

Current emphasis: designing systems that connect OT/industrial realities to cloud-native data and AI capabilities in ways that are deployable, observable, and maintainable.

## What I Work On

### Industrial AI
Connecting operational problems and industrial data to usable AI systems.

### Data and ML Systems
Designing pipelines, retrieval systems, analytical layers, and model lifecycle components.

### Production AI and MLOps
Focusing on evaluation, observability, deployment patterns, and lifecycle reliability.

### Solution Architecture
Translating technical architecture into practical organizational outcomes.

### OT and IT Integration
Bridging physical operations, engineering context, and modern data infrastructure.

## Featured Engineering Work

### 1) Engineering Knowledge Assistant
**Problem**
Engineering documentation is often fragmented across formats and teams, which slows troubleshooting and weakens operational knowledge reuse.

**Architecture**
Governed document ingestion and validation, chunking and embeddings, vector retrieval, and citation-backed answer generation with confidence and knowledge-gap signaling.

**Key technical decisions**
- Ground responses in approved corpus documents rather than open-web generation
- Preserve source traceability through explicit citations
- Support multilingual retrieval across English and German
- Add lightweight usage and feedback signals to support iterative improvement

**Production considerations**
- Metadata governance and validation for engineering documents
- Evaluation and quality control for retrieval-backed answers
- Containerized deployment path and testable repository structure

**Repository / demo**
- Repository: https://github.com/cyranothebard/engineering-knowledge-assistant
- Architecture: https://github.com/cyranothebard/engineering-knowledge-assistant/blob/main/docs/architecture.md

### 2) Predictive Maintenance Decision Intelligence
**Problem**
Many predictive maintenance implementations stop at risk scoring without converting model outputs into actionable maintenance decisions.

**Architecture**
Health-state modeling and failure-risk estimation feed a recommendation engine and economic impact layer to support portfolio-level maintenance prioritization.

**Key technical decisions**
- Prioritize explainable recommendation logic over black-box scoring alone
- Integrate risk, RUL context, and action rationale in one decision surface
- Keep a human-in-the-loop operational posture for downstream actions

**Production considerations**
- Reproducible demo workflows and reviewer runbooks
- Explicit boundaries between intelligence recommendations and automation handoff
- Economic framing for action prioritization

**Repository / demo**
- Repository: https://github.com/cyranothebard/Markov_Based_Predictive_Maintenance
- Architecture context: see repository documentation and notebooks

### 3) Industrial IoT Data Platform
**Problem**
Industrial organizations need trustworthy, integrated operational data before AI initiatives can deliver durable value.

**Architecture**
Multi-domain ingestion into a medallion data architecture (Bronze/Silver/Gold), explicit data quality scoring, KPI modeling, and operational dashboarding.

**Key technical decisions**
- Treat data quality as a first-class architecture layer
- Model data domains aligned to operations, reliability, maintenance, quality, and production planning
- Build gold-layer outputs structured for downstream AI use cases

**Production considerations**
- Scalable domain-oriented pipelines with testing
- Quality monitoring and anomaly visibility
- Clear handoff from data foundation to future predictive and AI capabilities

**Repository / demo**
- Repository: https://github.com/cyranothebard/industrial-iot-data-platform
- Architecture: https://github.com/cyranothebard/industrial-iot-data-platform/blob/main/architecture/high-level-architecture.md

## Current Engineering Focus

I am currently extending this portfolio deeper into production AI: cloud-native deployment patterns, MLOps and evaluation workflows, observability, and lifecycle operations for industrial and enterprise data/AI systems.

## Architecture and Engineering Notes

I publish technical notes and architecture decisions to make trade-offs explicit. Priority topics include:

- Azure and AWS reference architectures for enterprise industrial knowledge systems
- RAG evaluation strategy and quality controls
- Kubernetes vs managed/serverless deployment patterns
- Model monitoring and operational observability
- OT-to-cloud ingestion and integration architecture
- Identity, access, and secrets architecture
- Build-vs-buy decision frameworks

## Technology

**AI and Data**: Python, SQL, Pandas, MLflow, vector retrieval patterns

**Application and API**: FastAPI, Streamlit, REST, Pydantic

**Platform and Infra**: Docker, Kubernetes, Terraform, cloud architecture patterns

**Delivery and Operations**: GitHub Actions, CI/CD, testing workflows, observability patterns

**Industrial Domain**: industrial automation context, reliability workflows, OT/IT integration

## Connect

- Portfolio / BridgeOps: https://bridge-ops.ai
- LinkedIn: https://www.linkedin.com/in/lewisbrandonk
- Selected repositories: https://github.com/cyranothebard?tab=repositories
- Contact: https://bridge-ops.ai/kontakt/
