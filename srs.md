### Definition

**Kira** : Kira is an ai agent for frontend component creater using nextjs typescript and openai using openai agent sdk

## features

- Create Components by prompting
- make changes to existing components
- get access to code
- see preview on browser

## Tech Stack

- Nodejs
- Typescript
- openai SDK

## Working

### High Level Architecture Diagram

```mermaid
flowchart TB
    User[User]
    Prompt[Prompt]
    Agent[Agent]
    Output[Component]
User -->|text| Prompt -->|process| Agent --> Output
```

### Agent Low Level Architecture

```mermaid
flowchart TB
    Prompt[Prompt]
    subgraph Agent
        Input_Gaurdreils[Input Gaurdreils]
        Accept
        Reject
        CodingAgent[Coding Agent]
    end
Prompt --> Input_Gaurdreils
Input_Gaurdreils --> Accept
Input_Gaurdreils --> Reject
Accept --> CodingAgent
Reject --> Output[Rejected Output Reason]
```
