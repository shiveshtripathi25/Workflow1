# Workflow1
# Compliance Check Flowchart

```mermaid
flowchart TD
    A[Start] --> B[Log into the CLMS portal]
    B --> C[Navigate to the 'Completed Contract' section]
    C --> D[Initiate Compliance Check]
    D --> E[Select the contractor and completed purchase order]
    E --> F[Verify Bonus and Leave Wages Compliance]
    F --> G[Check Form-C]
    F --> H[Check leave with wage register]
    F --> I[Mark step as complete]
    I --> J[Verify CLRA Compliance]
    J --> K[Generate Form VII]
    J --> L[Check payment of wages]
    J --> M[Mark step as complete]
    M --> N[Verify PF Compliance]
    N --> O[Check payment of contributions]
    N --> P[Verify late/delayed contributions and correct challans]
    N --> Q[Mark step as complete]
    Q --> R[Verify ESI Compliance]
    R --> S[Check payment of contributions]
    R --> T[Verify late/delayed contributions and correct challans]
    R --> U[Mark step as complete]
    U --> V[Security/Bank Guarantee Release]
    V --> W[Update final compliance status]
    W --> X[Enable option to submit letter for release]
    X --> Y[End]
