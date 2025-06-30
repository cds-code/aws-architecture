```mermaid
graph TD
    A[バケット] --> B[SQS]
    B --> C["Lambda<br/>sleep(1 minute) after processed"]
    
    style A fill:#ff9999
    style B fill:#ffcc99
    style C fill:#cc99ff
```
