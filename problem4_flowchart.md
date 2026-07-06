~~~ mermaid
flowchart TD
    A[Start] --> B(Input)
    B --> C[Numb1]
    B --> D[Numb2]
    B --> E[Numb3]
    C --> F{Add}
    D --> F 
    E --> F 
    F --> G(Divide by the amount of numb)
    G --> H[Display Average]
    H --> I[END]