```mermaid
flowchart TD
    A([Start]) --> B[/Input raf1/]
    B --> C{raf1 MOD 2 = 0?}
    C -- Yes --> D[/Display "Even"/]
    C -- No --> E[/Display "Odd"/]
    D --> F([End])
    E --> F
```