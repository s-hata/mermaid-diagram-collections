# Mermaid Diagram Collections

```mermaid
erDiagram
    USER {
        string id
        string email
    }

    ORDER {
        string id
        date created_at
    }

    USER ||--o{ ORDER : places
```
