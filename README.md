# Mermaid-Hands-On

```mermaid
flowchart TD
    A[Start / Input x] --> B{x > 0}
    B -- Y --> C[/positif/]
    B -- N --> D{x < 0}
    D -- Y --> E[/negatif/]
    D -- N --> F[/nol/]
    C --> G([End])
    E --> G
    F --> G
