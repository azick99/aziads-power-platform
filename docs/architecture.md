```mermaid
flowchart TD
    C[Customers] --> PP[Power Pages]
    S[Sales and designers] --> MDA[Model-driven app]
    I[Installers] --> CA[Canvas app]
    M[Management] --> BI[Power BI]
    PP <--> DV[(Dataverse)]
    MDA <--> DV
    CA <--> DV
    BI <--> DV
    DV <--> PA[Power Automate]
```
