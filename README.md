# DBMS
all you need to know to handle data
__________________________________________________________
```mermaid
graph TB;
    A[Database Concepts] -->|Covers| B[Basic Concepts]
    A -->|Covers| C[Characteristics of DBMS]
    A -->|Covers| D[Concepts & Architecture]
    A -->|Covers| E[Data Models & Instances]
    A -->|Covers| F[DBMS Architecture]
    A -->|Covers| G[Database Languages]
    A -->|Covers| H[Data Modelling - ER Model]
    A -->|Covers| I[SQL]
    A -->|Covers| J[Constraints]

    subgraph "Basic Concepts"
        B1[Database]
        B2[Database Users]
        B2 --> B3[End Users]
        B2 --> B4[Application Programmers]
        B2 --> B5[DBAs]
        B2 --> B6[Sophisticated Users]
    end

    subgraph "Characteristics of DBMS"
        C1[Self-describing]
        C2[Data Independence]
        C3[Multiple Views]
        C4[Data Sharing]
        C5[Integrity & Security]
        C6[Transaction Management]
    end

    subgraph "Concepts & Architecture"
        D1[Three-Schema Architecture]
        D1 --> D2[External Level]
        D1 --> D3[Conceptual Level]
        D1 --> D4[Internal Level]
        D2 --> D5[Logical Independence]
        D3 --> D6[Physical Independence]
    end

    subgraph "Data Models & Instances"
        E1[Data Models]
        E1 --> E2[Relational]
        E1 --> E3[Hierarchical]
        E1 --> E4[Network]
        E1 --> E5[Object-Oriented]
        E6[Schema]
        E7[Instance]
    end

    subgraph "DBMS Architecture"
        F1[Centralized]
        F2[Client-Server]
        F3[Distributed]
    end

    subgraph "Database Languages"
        G1[DDL - Data Definition Language]
        G2[DML - Data Manipulation Language]
        G3[DCL - Data Control Language]
        G4[Interfaces - Forms, GUIs, APIs]
    end

    subgraph "Data Modelling - ER Model"
        H1[Entities]
        H2[Attributes]
        H3[Relationships]
        H4[ER Diagrams]
        H5[Enhanced ER Concepts]
        H5 --> H6[Specialization]
        H5 --> H7[Generalization]
        H5 --> H8[Aggregation]
        H9[Mapping ER to Relational Model]
    end

    subgraph "SQL"
        I1[DDL]
        I1 --> I2[CREATE]
        I1 --> I3[ALTER]
        I1 --> I4[DROP]
        I5[DML]
        I5 --> I6[INSERT]
        I5 --> I7[UPDATE]
        I5 --> I8[DELETE]
        I5 --> I9[SELECT]
        I10[DCL]
        I10 --> I11[GRANT]
        I10 --> I12[REVOKE]
        I13[Views]
        I14[Indexes]
    end

    subgraph "Constraints"
        J1[Primary Key]
        J2[Foreign Key]
        J3[Unique]
        J4[Not Null]
        J5[Check]
        J6[IN Operator]
    end
```
 



