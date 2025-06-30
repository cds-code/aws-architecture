```mermaid
graph TD
    A[バケット] --> B[SQS]
    B --> C[Lambda<br/>処理終了後sleep(1 minute)]
    
    style A fill:#ff9999
    style B fill:#ffcc99
    style C fill:#cc99ff
```
