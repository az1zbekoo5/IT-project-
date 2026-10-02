# IT-project-
# IT Project Management — Work Breakdown Structure

## Project: Time Capsule for Lovers

```mermaid
flowchart TB

    ROOT["💗<br/><b>1.0 TIME CAPSULE<br/>FOR LOVERS</b>"]

    ROOT --> PM
    ROOT --> SA
    ROOT --> DEV
    ROOT --> QA
    ROOT --> DEP

    %% PROJECT MANAGEMENT
    subgraph PM["1.1 PROJECT MANAGEMENT"]
        direction TB
        PM1["📋 1.1.1<br/><b>PROJECT CHARTER</b>"]
        PM2["📅 1.1.2<br/><b>PROJECT PLAN & SCHEDULE</b>"]
        PM3["⚠️ 1.1.3<br/><b>RISK MANAGEMENT PLAN</b>"]
        PM4["💰 1.1.4<br/><b>COST MANAGEMENT & BUDGETING</b>"]
        PM5["💬 1.1.5<br/><b>STAKEHOLDER COMMUNICATION</b>"]
        PM1 --> PM2 --> PM3 --> PM4 --> PM5
    end

    %% SYSTEM ANALYSIS
    subgraph SA["1.2 SYSTEM ANALYSIS & DESIGN"]
        direction TB
        SA1["👥 1.2.1<br/><b>USER REQUIREMENTS & STORIES</b><br/><small>• Lovers' needs<br/>• Edge of breakup triggers</small>"]
        SA2["📄 1.2.2<br/><b>FUNCTIONAL & NON-FUNCTIONAL REQUIREMENTS</b>"]
        SA3["🏗️ 1.2.3<br/><b>SYSTEM ARCHITECTURE DESIGN</b>"]
        SA4["🗄️ 1.2.4<br/><b>DATABASE DESIGN</b><br/><small>Capsules, Users, Triggers</small>"]
        SA5["🎨 1.2.5<br/><b>UI/UX WIREFRAMING & DESIGN</b>"]
        SA1 --> SA2 --> SA3 --> SA4 --> SA5
    end

    %% DEVELOPMENT
    subgraph DEV["1.3 DEVELOPMENT & INTEGRATION"]
        direction TB
        DEV1["📱 1.3.1<br/><b>FRONTEND DEVELOPMENT</b><br/><small>Mobile App</small>"]
        DEV2["🖥️ 1.3.2<br/><b>BACKEND DEVELOPMENT</b><br/><small>APIs, Server</small>"]
        DEV3["🗄️ 1.3.3<br/><b>DATABASE IMPLEMENTATION</b>"]
        DEV4["💗 1.3.4<br/><b>TIME CAPSULE CREATION FUNCTIONALITY</b>"]
        DEV5["💬 1.3.5<br/><b>TRIGGER LOGIC & MESSAGING SYSTEM</b><br/><small>Event-based triggers, e.g. low communication, SOS button</small>"]
        DEV6["🔗 1.3.6<br/><b>CAPSTONE INTEGRATION</b>"]
        DEV1 --> DEV2 --> DEV3 --> DEV4 --> DEV5 --> DEV6
    end

    %% TESTING
    subgraph QA["1.4 TESTING & QA"]
        direction TB
        QA1["🛡️ 1.4.1<br/><b>UNIT TESTING</b>"]
        QA2["🔗 1.4.2<br/><b>SYSTEM INTEGRATION TESTING</b>"]
        QA3["👤 1.4.3<br/><b>USER ACCEPTANCE TESTING</b><br/><small>UAT with university staff/student feedback</small>"]
        QA4["✓ 1.4.4<br/><b>PERFORMANCE & SECURITY TESTING</b>"]
        QA1 --> QA2 --> QA3 --> QA4
    end

    %% DEPLOYMENT
    subgraph DEP["1.5 DEPLOYMENT & CAPSTONE WRAP-UP"]
        direction TB
        DEP1["📄 1.5.1<br/><b>FINAL CAPSTONE DOCUMENTATION & REPORT</b>"]
        DEP2["🎓 1.5.2<br/><b>PROJECT PRESENTATION & DEFENSE</b>"]
        DEP3["📱 1.5.3<br/><b>APP STORE DEPLOYMENT</b><br/><small>Beta/Prototype</small>"]
        DEP4["⚙️ 1.5.4<br/><b>PROJECT CLOSURE & REFLECTION</b>"]
        DEP1 --> DEP2 --> DEP3 --> DEP4
    end

    %% COLORS
    classDef root fill:#31577A,stroke:#18384F,color:#FFFFFF,stroke-width:3px;
    classDef pm fill:#D8F0ED,stroke:#4C9996,color:#173B3A,stroke-width:2px;
    classDef sa fill:#DCECF8,stroke:#4C88A8,color:#17384A,stroke-width:2px;
    classDef dev fill:#FBE0CE,stroke:#C97945,color:#4A2818,stroke-width:2px;
    classDef qa fill:#FCE7C5,stroke:#D89A35,color:#4A3212,stroke-width:2px;
    classDef dep fill:#F1DCEB,stroke:#9C5785,color:#45253A,stroke-width:2px;

    class ROOT root

    class PM,PM1,PM2,PM3,PM4,PM5 pm