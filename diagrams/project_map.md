```mermaid


graph LR
   
    P_Int([Public Interventions])
    PH_C([PH_collagian])
    GS([Golden Sigbin])
    TW([TradeWinds])
    ST([Stations])
    GP([GhostProjects])
    PN([P1sonet])
    PN22([P1sonet2022])
    IRL([In_Real_Life2021])
    404([404])
    PRL([Parallel Projects])
    CODW([Colors of the Wind])
    LPWA([Low Pressured Areas2017])
    PPV([Pay/View 2019])
    MS([Mission Control])
    FCO([For Content Only])
    FW([FreeWall2016])
 

    P_Int --> PH_C
    P_Int --> PRL
    P_Int -->PN
    P_Int --> LPWA
    P_Int --> GS
    P_Int --> 404
    P_Int --> PPV
    P_Int --> FW
    
    PH_C --> PN
    
    FW --> LPWA
    FW --> PRL
    FW --> PN
    
    PPV --> FCO
    PPV --> IRL
    
    CODW --> ST
    CODW --> TW1
    
    LPWA --> PRL
    LPWA --> GS
    
    GS --> PN
    
    PRL --> PRL1[Parallel2018]
    PRL --> PRL2[ParallelSpace]
    PRL --> PRL3[ParallelComix]
    PRL2 -->GP4
    
    PN --> PN22
    PN --> TW
    PN --> IRL
    PN --> 404
    PN --> MS
    
    
    PN22 --> PH_C
    

    TW --> TW1[Tradewinds2021]
    TW --> TW2[Meteor_Garden2022]
    TW --> TW3[PierUno2022]
    TW --> TW4["TradeWinds4_2023"]
    TW --> TW5[Ghost_in_the_Machine2024]
    
    GS --> GS1[Brunswick_Project]
    
    PH_C --> GS1
    PH_C --> TW4

    TW5 --> GP
    GP --> TW5
    GP --> GP2[Ghost_Writer2024]
    GP --> GP3[GhostWhisper2025]
    GP --> GP4[Ghost_Control2026]
    
    GP --> MS
    
    ST -->GP3

    classDef coreNode fill:transparent,stroke:transparent,stroke-width:0px,color:#000000,font-weight:bold;

    classDef otherNode fill:transparent,stroke:transparent,stroke-width:0px,color:#000000,font-weight:normal;
    
    class P_Int,PH_C,GS,TW,ST,GP,PN,PN22,IRL,404,PRL,CODW,LPWA,PPV,MS,FCO,FW coreNode;
    class PRL1,PRL2,PRL3,TW1,TW2,TW3,TW4,TW5,GS1,GP2,GP3,GP4 otherNode;


