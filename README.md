# AppraiseNow – ServiceNow Application Quality Assessment Platform

## Overview

AppraiseNow is a ServiceNow-based application quality assessment platform that automates the auditing of custom applications by analyzing security, performance, maintainability, code quality, and update set practices.

The platform scans scoped applications, identifies implementation issues, calculates quality scores, benchmarks applications against predefined standards, generates AI-powered recommendations using the Groq LLM, provides interactive analytics dashboards, and exports professional audit reports.

---

# Features

## Automated Application Scanning

AppraiseNow performs automated analysis of ServiceNow applications through custom scanner engines.

Current scanners include:

* Security (ACL) Scanner
* Script Quality Scanner
* Maintainability Scanner
* Performance Scanner
* Update Set Scanner

Each scanner automatically creates findings categorized by:

* Security
* Performance
* Maintainability
* Quality
* Update Set

---

## Intelligent Scoring Engine

After every scan, AppraiseNow automatically calculates:

* Security Score
* Performance Score
* Quality Score
* Maintainability Score
* Update Set Score
* Overall Score
* Final Grade (A–F)

Scores are stored inside Scorecards for historical comparison and reporting.

---

## Benchmark Comparison

Applications are evaluated against predefined benchmark values.

Benchmark categories include:

* Community Average
* Industry Standard
* Top Quartile

This enables developers to compare application quality against expected standards.

---

## AI-Powered Audit Advisor

AppraiseNow integrates with the Groq API using the Llama 3.3 70B model to generate intelligent audit insights.

The AI analyzes:

* Overall score
* Individual quality dimensions
* Generated findings

It automatically produces:

* Executive Summary
* Key Strengths
* Potential Risks
* Improvement Recommendations
* Grade Justification

The generated insights are stored directly in the Scorecard.

---

## Professional Audit Report

Every completed scan can generate a professional audit report.

The report contains:

* Application Information
* Overall Grade
* Score Breakdown
* AI Executive Summary
* AI Strengths
* AI Risks
* AI Recommendations
* Grade Explanation
* Complete Findings Table

The report is optimized for printing and sharing with administrators and developers.

---

## Interactive Analytics Dashboard

The Platform Analytics dashboard provides real-time visibility into application quality.

### Executive Overview

* Total Scans
* Average Overall Score
* Critical Findings
* Average Security Score

### Analytics & Trends

* Overall Score Trend
* Findings by Dimension
* Findings by Severity
* Overall Score Distribution
* Grade Distribution

### AI Insights

* Total AI Reports Generated
* Average AI Audit Score
* AI Performance Visualization

Dashboard widgets update automatically as new scan results are generated.

---

# System Architecture

```text
Application
        │
        ▼
Scan Manager
        │
        ▼
Scanner Engines
 ├── ACL Scanner
 ├── Script Scanner
 ├── Performance Scanner
 ├── Maintainability Scanner
 └── Update Set Scanner
        │
        ▼
Findings
        │
        ▼
Benchmark Engine
        │
        ▼
Scorecard Generation
        │
        ▼
Groq AI Advisor
        │
        ▼
Audit Report Generator
        │
        ▼
Platform Analytics Dashboard
```

---

# Application Components

## Custom Tables

* Scan
* Finding
* Scorecard
* Benchmark

## Script Includes

* Scan Manager
* ACL Scanner
* Script Scanner
* Benchmark Engine
* AI Advisor
* Report Generator

## UI Components

* Platform Analytics Dashboard
* Report UI Page
* PDF Report UI Action

---

# Dashboard Preview

## Executive Overview

<p align="center">
  <img src="https://github.com/user-attachments/assets/b1f30d0d-7f18-4bde-bda4-84537b37d852" alt="Executive Overview" width="75%">
</p>

---

## Analytics & Trends

<p align="center">
  <img src="https://github.com/user-attachments/assets/b1fa0846-fbf6-49a8-bf6e-0c5e148a1bbf" alt="Analytics & Trends" width="75%">
</p>

---

## AI Insights

<p align="center">
  <img src="https://github.com/user-attachments/assets/287bd52b-7434-45f9-92d8-96431518d30a" alt="AI Insights" width="75%">
</p>

---

# Technology Stack

## Platform

* ServiceNow App Engine Studio

## Development

* Script Includes
* GlideRecord API
* Business Rules
* UI Actions
* UI Pages
* Platform Analytics

## Artificial Intelligence

* Groq API
* Llama 3.3 70B Versatile

## Reporting

* HTML Report Generation
* Print-Friendly Audit Reports

---

# Project Structure

```text
AppraiseNow
│
├── Tables
│   ├── Scan
│   ├── Finding
│   ├── Scorecard
│   └── Benchmark
│
├── Script Includes
│   ├── ScanManager
│   ├── ACLScanner
│   ├── ScriptScanner
│   ├── BenchmarkEngine
│   ├── AIAdvisor
│   └── ReportGenerator
│
├── UI
│   ├── Dashboard
│   ├── Report Page
│   └── PDF Export Action
│
└── Platform Analytics
```

---

# Workflow

```text
Start Scan
      │
      ▼
Run Scanner Engines
      │
      ▼
Generate Findings
      │
      ▼
Calculate Scores
      │
      ▼
Compare with Benchmarks
      │
      ▼
Generate Scorecard
      │
      ▼
Generate AI Insights
      │
      ▼
Generate Audit Report
      │
      ▼
Display Dashboard Analytics
```

---

# Future Enhancements

* Native ServiceNow Now Assist Integration
* Historical Scan Comparison
* Scheduled Automated Scans
* Email Audit Report Delivery
* CI/CD Integration
* Predictive Quality Trends
* Custom Benchmark Profiles

---

# Author

**Animesh Sharma**

ServiceNow Application Developer | Java Backend Developer
<img width="1923" height="1164" alt="executive-overview" src="https://github.com/user-attachments/assets/614ba07e-b91d-4e9c-954d-503ad4fd27d8" />
