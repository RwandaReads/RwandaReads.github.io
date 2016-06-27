# RwandaReads: Software Requirements Specification

## Table of Contents

1. Introduction
  1. Purpose
  2. Scope
  3. Definitions, Acronyms, and Abbreviations
  4. References
  5. Overview
2. General Description
  1. Product Perspective
  2. Product Functions
  3. User Characteristics
  4. General Constraints
  5. Assumptions and Dependencies
3. Specific Requirements
  1. External Interface Requirements
    1. User Interfaces
    2. Hardware Interfaces
    3. Software Interfaces
    4. Communications Interfaces
  2. Functional Requirements
    1. <Functional Requriement OR Feature #1>
    2. <Functional Requirement OR Feature #2>
  3. Use Cases
    1. Use Case #1
    2. Use Case #2
  4. Classes / Objects
    1. <Class / Object #1>
    2. <Class / Object #2>
  5. Non-Functional Requirements
    1. Performance
    2. Reliability
    3. Availability
    4. Security
    5. Maintainability
    6. Portability
  6. Inverse Requirements
  7. Design Constraints
  8. Logical Database Requirements
  9. Other Requirements
4. Analysis Models
  1. Sequence Diagrams
  2. Data Flow Diagrams (DFD)
  3. State-Transition Diagrams (STD)
5. Change Management Process
6. Appendices
  1. Appendix 1
  2. Appendix 2

## Introduction

The introduction to the Software Requirement Specification (SRS) document should provide an overview of the complete SRS document.  While writing this document please remember that this document should contain all of the information needed by a software engineer to adequately design and implement the software product described by the requirements listed in this document.   (Note: the following subsection annotates are largely taken  from the IEEE Guide to SRS).

### Purpose

What is the purpose of this SRS and the (intended) audience for which it is written.

### Scope

This subsection should:
(1)	 Identify the software product(s) to be produced by name; for example, Host DBMS, Report Generator, etc
(2)	Explain what the software product(s) will, and, if necessary, will not do
(3)	Describe the application of the software being specified. As a portion of this, it should:
(a) Describe all relevant benefits, objectives, and goals as precisely as possible. For example, to say that one goal is to provide effective reporting capabilities is not as good as saying parameter-driven, user-definable reports with a 2 h turnaround and on-line entry of user parameters.
(b) Be consistent with similar statements in higher-level specifications (for example, the System Requirement Specification) , if they exist.What is the scope of this software product.

### Definitions, Acronyms, and Abbreviations

This subsection should provide the definitions of all terms, acronyms, and abbreviations required to properly interpret the SRS. This information may be provided by reference to one or more appendixes in the SRS or by reference to other documents.

### References

This subsection should:
(1)	Provide a complete list of all documents referenced elsewhere in the SRS, or in a separate, specified document.
(2)	Identify each document by title, report number - if applicable - date, and publishing organization.
(3)	Specify the sources from which the references can be obtained. 
This information may be provided by reference to an appendix or to another document.

### Overview

This subsection should:
(1) Describe what the rest of the SRS contains
(2) Explain how the SRS is organized.

## General Description

This section of the SRS should describe the general factors that affect 'the product and its requirements.  It should be made clear that this section does not state specific requirements; it only makes those requirements easier to understand.

### Product Perspective

This subsection of the SRS puts the product into perspective with other related products or
projects.  (See the IEEE Guide to SRS for more details).

### Product Functions

This subsection of the SRS should provide a summary of the functions that the software will perform. 

### User Characteristics

This subsection of the SRS should describe those general characteristics of the eventual users of the product that will affect the specific requirements.  (See the IEEE Guide to SRS for more details).

### General Constraints

This subsection of the SRS should provide a general description of any other items that will
limit the developer’s options for designing the system. (See the IEEE Guide to SRS for a partial list of possible general constraints).

### Assumptions and Dependencies

This subsection of the SRS should list each of the factors that affect the requirements stated in the SRS. These factors are not design constraints on the software but are, rather, any changes to them that can affect the requirements in the SRS. For example, an assumption might be that a specific operating system will be available on the hardware designated for the software product. If, in fact, the operating system is not available, the SRS would then have to change accordingly.

## Specific Requirements

This will be the largest and most important section of the SRS.  The customer requirements will be embodied within Section 2, but this section will give the D-requirements that are used to guide the project’s software design, implementation, and testing.

Each requirement in this section should be:
Correct
Traceable (both forward and backward to prior/future artifacts)
Unambiguous
Verifiable (i.e., testable)
Prioritized (with respect to importance and/or stability)
Complete
Consistent
Uniquely identifiable (usually via numbering like 3.4.5.6)

Attention should be paid to the carefuly organize the requirements presented in this section so that they may easily accessed and understood.  Furthermore, this SRS is not the software design document, therefore one should avoid the tendency to over-constrain (and therefore design) the software project within this SRS.

### External Interface Requirements

#### User Interfaces

#### Hardware Interfaces

#### Software Interfaces

#### Communications Interfaces

### Functional Requirements

This section describes specific features of the software project.  If desired, some requirements may be specified in the use-case format and listed in the Use Cases Section.

#### <Functional Requirement OR Feature #1>

##### Introduction

##### Inputs

##### Processing

##### Outputs

##### Error Handling

#### <Functional Requirement OR Feature #2>

...

### Use Cases

#### Use Case #1

#### Use Case #2

### Classes / Objects

**DELETE THIS**

### Non-Functinal Requirements

Non-functional requirements may exist for the following attributes.  Often these requirements must be achieved at a system-wide level rather than at a unit level.  State the requirements in the following sections in measurable terms (e.g., 95% of transaction shall be processed in less than a second, system downtime may not exceed 1 minute per day, > 30 day MTBF value, etc). 

#### Performance

#### Reliability

#### Availability

#### Security

#### Maintainability

#### Portability

### Inverse Requirements

State any *useful* inverse requirements.

### Design Constraints

Specify design constrains imposed by other standards, company policies, hardware limitation, etc. that will impact this software project.

### Logical Database Requirements

**DELETE THIS**

### Other Requirements

Catchall section for any additional requirements.

## Analysis Models

List all analysis models used in developing specific requirements previously given in this SRS.  Each model should include an introduction and a narrative description.  Furthermore, each model should be traceable the SRS’s requirements.

### Sequence Diagrams

### Data Flow Diagrams (DFD)

### State-Transition Diagrams (STD)

## Change Management Process

Identify and describe the process that will be used to update the SRS, as needed, when project scope or requirements change.  Who can submit changes and by what means, and how will these changes be approved.

## Appendices

Appendices may be used to provide additional (and hopefully helpful) information.  If present, the SRS should explicitly state whether the information contained within an appendix is to be considered as a part of the SRS’s overall set of requirements.

Example Appendices could include (initial) conceptual documents for the software project, marketing materials, minutes of meetings with the customer(s), etc.

### Appendix 1

### Appendix 2
