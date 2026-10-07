# Success Criteria Process

## a) Researched Formats

The examples below are copied from the research reports’ illustrative applications; they are AI-authored examples, not quotations from the cited sources or finalized product criteria.

1. Rubric

> Description: A table that evaluates each criterion against descriptions of different quality levels.
> Example: Answer grounding -> unsupported / partly supported / fully supported, with explicit descriptions for each.

2. Acceptance Criteria

> Description: A set of conditions that a product or feature must meet to be accepted.
> Example: A saved note retains its title and content after the app is closed and reopened.

3. Given-When-Then Scenarios

> Description: A scenario that defines the starting situation, an action, and the expected result.
> Example: Given no note contains the requested appointment date, when the user asks for it, then the app states that the stored information is insufficient.

4. Requirements Verification Matrix

> Description: A table that links each requirement to its source and the method used to verify it.
> Example: PR-01 | Notes remain on-device during specified operations | Privacy purpose | Data-flow inspection and network observation.
> Components:
> - ID
> - Title
> - Description
> - Priority
> - Justification
> - Passing Condition
> - Verification Method
> - Evidence
> - Status

5. Usability Metrics and Targets

> Description: Measures of how easily users complete tasks, paired with targets for acceptable results.
> Example: Record the proportion of first-time participants who create and retrieve a note without assistance; set the passing target before evaluation.

6. Service-Level Objectives

> Description: Measurable targets for reliability or performance over a defined period or set of trials.
> Example: Measure the proportion of eligible requests completed within a justified time limit across a predefined device test run.

7. Definition of Done

> Description: A shared checklist of conditions that must be met before work is considered complete.
> Example: The final Android package installs on the target device, includes setup instructions, and has recorded results for all planned evaluations.

8. UX Benchmarking and Baseline Comparison

> Description: An evaluation that compares user-experience measures against an earlier version, another product, or a baseline.
> Example: Compare task completion and retrieval time for equivalent information-finding tasks using manual browsing and the app.

9. Objectives and Key Results

> Description: A framework that pairs an overall objective with measurable results showing whether it has been achieved.
> Example: 
> - Objective -> reduce organization effort. 
> - Key result -> a predefined improvement in measured effort during a controlled user task.

10. MoSCoW Prioritization

> Description: A method that groups requirements as Must Have, Should Have, Could Have, or Won’t Have this time; it sets priority rather than passing conditions.
> Example: 
> - Must Have: stored-note persistence. 
> - Could Have: an additional organization visualization. 
> - Each still needs its own acceptance condition.

## b) Hybrid Structure: Nested

```
Requirements Verification Matrix
├── Requirement Record 01
│   ├── ID
│   ├── Title
│   ├── Description
│   ├── Priority
│   ├── Justification
│   ├── Passing Condition
│   ├── Evidence
│   └── Status
├── Requirement Record 02
│   ├── ID
│   ├── Title
│   ├── Description
│   ├── Priority
│   ├── Justification
│   ├── Passing Condition
│   ├── Evidence
│   └── Status
└── Requirement Record 03
    ├── ID
    ├── Title
    ├── Description
    ├── Priority
    ├── Justification
    ├── Passing Condition
    ├── Evidence
    └── Status
```

> The Requirements Verification Matrix contains individual Requirement Records, each defining one product requirement using a suitable success criteria format from the researched approaches.

Description replaces the Requirement field; Passing Condition specifies the result needed to verify it.

## c) Develop Product Success Criteria

Define measurable product requirements using the selected nested structure, including justification, priority, passing conditions, and verification methods. Consolidate the finalized records in the [product success criteria](../definition/success-criteria.md).
