```mermaid
graph TD
   
    classDef minimal fill:none,stroke:#333,stroke-width:1px;

    %% Main Studio / Vision Root
    Root([RealTime])


    Root --> TW[Tradewinds]
    TW --> TW1[Tradewinds ]
    TW --> TW2[Meteor Garden]
    TW --> TW3[Pier Uno]
    TW --> TW4[Tradewinds 4]
    TW --> TW5[GITM]

 
    TW5 --> GP[Ghostprojects]
    GP --> GP1[GITM]
    GP --> GP2[Ghost_Writer]
    GP --> GP3[GhostWhisper]
    GP --> GP4[GhostControl]

    %% Apply style to every node
    class Root,TW,TW1,TW2,TW3,TW4,TW5,GP,GP1,GP2,GP3 minimal;