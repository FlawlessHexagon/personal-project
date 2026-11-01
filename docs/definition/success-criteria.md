# Product Success Criteria

## Requirement Records Table

| **ID** | **Title**                       | **Description**                                                                         | **Type**                      | **Priority** | **Justification** | **Passing Condition**                                                     | **Evidence** | **Status**  |
| ------ | ------------------------------- | --------------------------------------------------------------------------------------- | ----------------------------- | ------------ | ----------------- | ------------------------------------------------------------------------- | ------------ | :---------- |
| SC-01  | Basic application functions     | Create, view, edit, and delete notes                                                    | Acceptance criteria           | 1            |                   | All acceptance criteria pass                                              |              | Not checked |
| SC-02  | Data preservation and recovery  | Export and restore notes through a file                                                 | Acceptance criteria           | 3            |                   | All acceptance criteria pass                                              |              | Not checked |
| SC-03  | Privacy and offline operation   | Store and process notes locally without requiring an internet connection after setup    | Acceptance criteria           | 1            |                   | All acceptance criteria pass                                              |              | Not checked |
| SC-04  | Long context understanding      | Understand and use information provided in long contexts                                | Benchmark                     | 2            |                   | Achieve at least # on the selected LongBench tasks                        |              | Not checked |
| SC-05  | Response performance            | Provide AI responses within acceptable waiting times on a target device                 | Service-level objectives      | 2            |                   | Meet all defined response time targets across the specified test requests |              | Not checked |
| SC-06  | User experience                 | To create, organize, and retrieve notes easily without assistance                       | Usability metrics and targets | 2            |                   | Meet all defined usability targets in user testing                        |              | Not checked |
| SC-07  | Persistent memory and grounding | Retain, update, and accurately ground answers in stored information across sessions     | Benchmark                     | 1            |                   | Achieve at least # on the selected LongMemEval tasks                      |              | Not checked |
| SC-08  | Proactive assistance            | Utilize relevant stored information proactively when relevant without explicit requests | Benchmark                     | 3            |                   | Achieve at least # on the selected ProactiveBench tasks                   |              | Not checked |

## Entires

### SC-01: Basic application functions - Acceptance criteria

| **ID**   | **Title** | **Description**                                                     | **Status**  |
| -------- | --------- | ------------------------------------------------------------------- | ----------- |
| SC-01-01 | Create    | Saving a new note makes it appear in the notes list                 | Not checked |
| SC-01-02 | View      | Opening a saved note displays its saved contents                    | Not checked |
| SC-01-03 | Edit      | Saving changes and reopening the note displays the updated contents | Not checked |
| SC-01-04 | Delete    | Deleting a note removes it from the notes list                      | Not checked |

### SC-02: Data preservation and recovery - Acceptance criteria

| **ID**   | **Title**        | **Description**                                                     | **Status**  |
| -------- | ---------------- | ------------------------------------------------------------------- | ----------- |
| SC-02-01 | Export           | Users can export selected notes to a file in a location they choose | Not checked |
| SC-02-02 | Export integrity | Exported file preserves every selected note’s contents              | Not checked |
| SC-02-03 | Import           | Users can import a previously exported file into the app            | Not checked |
| SC-02-04 | Import integrity | Imported notes retain their contents                                | Not checked |

### SC-03: Privacy and offline operation - Acceptance criteria

| **ID**   | **Title**              | **Description**                                                                                  | **Status**  |
| -------- | ---------------------- | ------------------------------------------------------------------------------------------------ | ----------- |
| SC-03-01 | Offline note functions | Users can create, view, edit, and delete notes without an internet connection                    | Not checked |
| SC-03-02 | Offline AI functions   | Note organization and question answering work without an internet connection after model setup   | Not checked |
| SC-03-03 | Local processing       | Note contents and questions are processed locally and are not transmitted to external services   | Not checked |
| SC-03-04 | Transparency           | Setup clearly explains all required downloads, their purpose, and when internet access is needed | Not checked |

### SC-04: Long context understanding - Benchmark

| **Field**      | **Details**                                            |
| -------------- | ------------------------------------------------------ |
| Benchmark      | [LongBench Github](https://github.com/THUDM/LongBench) |
| Version        | TBD                                                    |
| Selected tasks | TBD                                                    |
| Scoring method | TBD                                                    |
| Target score   | TBD                                                    |

### SC-05: Response performance - Service-level objectives

| **ID**   | **Title**            | **Description**                                                    | **Target** | **Status**  |
| -------- | -------------------- | ------------------------------------------------------------------ | ---------- | ----------- |
| SC-05-01 | Model loading time   | Time from loading model until it is ready for a request            | TBD        | Not checked |
| SC-05-02 | Time to first output | Time from submitting a question until the first output token       | TBD        | Not checked |
| SC-05-03 | Total response time  | Time from submitting a question until the complete reponse appears | TBD        | Not checked |

### SC-06: User experience - Usability metrics and targets

| **ID**   | **Title**            | **Assessment**                                                 | **Metric**                                           | **Target** | **Status**  |
| -------- | -------------------- | -------------------------------------------------------------- | ---------------------------------------------------- | ---------- | ----------- |
| SC-06-01 | Note creation        | Task: Create and save a note                                   | Percentage of users completing the task without help | TBD        | Not checked |
| SC-06-02 | Information retrieve | Task: Find specified information in stored notes               | Percentage of users completing the task without help | TBD        | Not checked |
| SC-06-03 | Note organization    | Task: Use AI organization, then correct an unwanted suggestion | Percentage of users completing the task without help | TBD        | Not checked |
| SC-06-04 | Ease of use          | Question: “How easy was it to complete these tasks?”           | Rating on a scale from 1 to 5                        | TBD        | Not checked |

### SC-07: Persistent Memory & Grounding - Benchmark

| **Field**      | **Details**                                                     |
| -------------- | --------------------------------------------------------------- |
| Benchmark      | [LongMemEval Github](https://github.com/xiaowu0162/LongMemEval) |
| Version        | TBD                                                             |
| Selected tasks | TBD                                                             |
| Scoring method | TBD                                                             |
| Target score   | TBD                                                             |

### SC-08: Proactive Assistance - Benchmark

| **Field**      | **Details**                                                       |
| -------------- | ----------------------------------------------------------------- |
| Benchmark      | [ProactiveBench Github](https://github.com/thunlp/ProactiveAgent) |
| Version        | TBD                                                               |
| Selected tasks | TBD                                                               |
| Scoring method | TBD                                                               |
| Target score   | TBD                                                               |
