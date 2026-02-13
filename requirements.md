# AI Supply Chain Risk Alert System – Requirements Document

## 1. Introduction

This document defines the functional and non-functional requirements for the AI Supply Chain Risk Alert System.

---

## 2. Problem Statement

Businesses often face unexpected supply chain disruptions due to:

- Natural disasters
- Geopolitical conflicts
- Port congestion
- Labor strikes
- Policy changes

These disruptions lead to financial losses, delays, and price instability.

---

## 3. Objectives

The system must:

- Detect potential supply chain disruptions
- Assign risk scores to affected regions/routes
- Provide early alerts
- Present insights in simple language

---

## 4. Target Users

- Small and Medium Enterprises (MSMEs)
- Exporters and importers
- Logistics operators
- Farmers dependent on imported inputs

---

## 5. Functional Requirements

### FR1: Data Collection
- The system shall fetch data from news APIs.
- The system shall fetch weather and climate alerts.
- The system shall store collected data in structured format.

### FR2: Risk Detection
- The system shall detect disruption-related events.
- The system shall extract affected regions and industries.
- The system shall classify severity levels.

### FR3: Risk Scoring
- The system shall calculate a risk score for each region.
- The system shall update scores periodically.
- The system shall display risk levels (Low, Medium, High).

### FR4: Alert Generation
- The system shall generate user-friendly alert messages.
- The system shall display alerts on the dashboard.

### FR5: Dashboard
- The system shall display current risk levels.
- The system shall show AI-generated summaries.
- The system shall provide suggested alternatives.

---

## 6. Non-Functional Requirements

### NFR1: Performance
- The system should process new data within a defined time window.
- Risk scores should update at least once daily (hackathon version).

### NFR2: Scalability
- The system should support increasing data sources.
- The architecture should allow global expansion.

### NFR3: Usability
- The dashboard must be simple and non-technical.
- Alerts must be easy to understand.

### NFR4: Security
- The system should use secure authentication.
- No sensitive user data should be required.

---

## 7. Constraints

- Limited access to proprietary trade data
- Dependence on public APIs
- Limited development time (hackathon scope)

---

## 8. Success Criteria

- Accurate detection of disruption events
- Clear and actionable alerts
- Positive feedback from pilot users
- Scalable architecture ready for expansion
