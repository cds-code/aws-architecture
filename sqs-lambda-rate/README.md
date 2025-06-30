```mermaid
graph TD
    A["EventBridge<br/>rate(1 minute)"] --> B[Lambda]
    B --> C[バケット]
    
    style A fill:#dc143c
    style B fill:#ffa500
    style C fill:#008000
```
