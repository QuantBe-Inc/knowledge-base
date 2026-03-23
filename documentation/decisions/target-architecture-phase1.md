# Target Architecture (Phase 1)

```mermaid
flowchart TB
  subgraph FE[Frontend]
    A1[Portal Platform]
    B[Sub Applications]
    C1[vue-ux-library package]
    C3[advanced-charting package]
  end

  subgraph BFF[API/BFF]
    D1[Portal Services]
    E8[Event BFF]
  end

  subgraph Core[Core Services]
    E1[Core Data]
    E2[Indicator Data]
    D3[Live Trading]
    D4[Backtest]
    D5[User Management]
  end

  subgraph Shared[Shared Packages]
    F1[QuantBe.FinancialIndicators]
    E17[QuantBe.CommonEvents]
  end

  subgraph Data[Data & Pipelines]
    H1[calculation-data-services]
    H3[Mage pipelines]
  end

  A1 --> B
  A1 --> D1
  B --> D1
  D1 --> E1
  D1 --> E2
  D3 --> E1
  D4 --> E1
  E8 --> E17
  E1 --> F1
  E2 --> F1
  H3 --> H1
  H1 --> E1
  H1 --> E2
  A1 --> C1
  B --> C3
```

Notes:
- CI/CD baseline moved to Azure DevOps YAML pipelines.
- GitHub Actions removed from KEEP repos audited in Phase 1.
- Deprecated/empty/POC repos archived per Phase 1 scope.
