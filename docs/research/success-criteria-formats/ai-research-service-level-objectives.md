# [06] Service-Level Objectives

> AI-driven research: compiled and analyzed with AI assistance. Source-supported findings and AI-generated interpretations are distinguished in the research; claims should be checked against the cited sources.

## Classification
- Type: Reliability measurement framework
- Evidence status: Primary-source guidance; not a student success case or proof of assessment results
- Research date: 2026-10-06

## Source-Supported Description
SLOs set targets for service-level indicators; Google discusses ratios of good events to total events and defined measurement periods. [Google SRE](https://sre.google/workbook/implementing-slos/)

## Working Structure
Indicator → good-event definition → target → measurement window

The structure is a concise research adaptation, not a mandatory template quoted from the source.

## Strengths and Limitations; Analysis
- Strength: Captures repeated reliability and latency rather than a single successful demonstration.
- Limitation: Designed for operational services; local-device testing needs adaptation and a sufficient number of trials.

## Project Relevance; Analysis
Useful for repeated AI request completion and response performance on the chosen phone.

## Illustrative Application
> Measure the proportion of eligible requests completed within a justified time limit across a predefined device test run.

This example is authored for comparison. It is not taken from the source and does not establish the project's final criteria or thresholds.

## Useful Lesson
Borrow event definitions, denominators, and measurement windows rather than cloud-service practices wholesale.

## Sources
- [Google SRE](https://sre.google/workbook/implementing-slos/)
