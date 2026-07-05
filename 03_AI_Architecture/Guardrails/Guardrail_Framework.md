
```mermaid
flowchart TD

A[User Message]

A --> B[Core AI Guardrails]

B --> C[Persona Guardrail]
B --> D[Conversational Logic]
B --> E[Route Confirmation]

D --> F[Travel Intelligence Guardrails]

F --> G[Transportation]
F --> H[Destination Intelligence]
F --> I[Cultural Etiquette]
F --> J[Packing]
F --> K[Weather]
F --> L[Currency]
F --> M[Visa]

G --> N[Quality & Safety Guardrails]
H --> N
I --> N
J --> N
K --> N
L --> N
M --> N

N --> O[Memory]
N --> P[State Management]
N --> Q[RAG]
N --> R[Hallucination Prevention]

O --> S[Response Builder]
P --> S
Q --> S
R --> S

S --> T[React Frontend]
