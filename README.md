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

```mermaid
journey
    title My working day
    section Go to work
      Make tea: 5: Me
      Go upstairs: 3: Me
      Do work: 1: Me, Cat
    section Go home
      Go downstairs: 5: Me
      Sit down: 5: Me
```
