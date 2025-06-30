```mermaid
graph TD
    A["EventBridge<br/>rate(1 minute)"] --> B[Lambda]
    B --> C[バケット]
    
    style A fill:#ff9999
    style B fill:#99ccff
    style C fill:#99ff99
```
