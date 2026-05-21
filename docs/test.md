```mermaid
graph TD
    %% Define a class with no background fill and a clean border
    classDef minimal fill:none,stroke:#333,stroke-width:1px;

    A[Traditional Art] -->|Visualizes Data Only| B(Digital/Physical Output)
    C[Our Data Sculpture] -->|Pico-Data Center| D(Houses Real Data)
    E[Renewable Energy] --> D
    D --> F[Can Be Installed Anywhere]

    %% Apply the style to all nodes
    class A,B,C,D,E,F minimal;