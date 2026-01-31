# Architecture Overview

IncidentGuard uses a multi-agent architecture implemented using IBM watsonx Orchestrate.

1. The IncidentGuard Agent performs primary incident analysis and risk classification.
2. The RiskReview Agent validates the classification and recommended actions.
3. For high-risk incidents, an automated workflow generates a structured incident summary.

This design mirrors real enterprise incident management workflows and improves decision reliability through agent collaboration and governance.
