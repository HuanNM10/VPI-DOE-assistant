# DOE-assistant
DOE assitant for enginner
# VPI-DOE-assistant

AI-powered Design of Experiments (DOE) assistant for research and development.

---

## Overview

**VPI-DOE-assistant** is a digital tool developed to support **Design of Experiments (DOE)** workflows in research, teaching, and industrial R&D.

The application combines:
- **ChatGPT-based conversational guidance**
- **Python-based statistical analysis**
- **Interactive DOE dashboard**
- **Automated export of results**

This tool is designed to help users generate experimental matrices, input response data, run ANOVA, visualize key effects, and receive AI-assisted recommendations for optimization.

---

## Main Functions

### 1. AI-assisted DOE setup
The assistant can guide users to:
- select the application domain
- define factors and levels
- choose suitable DOE types:
  - Full Factorial
  - Fractional Factorial
  - Central Composite Design (CCD)
  - Response Surface Methodology (RSM)
  - Taguchi design

### 2. Experimental matrix generation
The system automatically generates a **Design Matrix** based on user inputs.

### 3. Statistical analysis
The application supports:
- ANOVA
- regression modeling
- significance testing
- interpretation of factor effects
- model adequacy checking

### 4. Data visualization
The system can display:
- Pareto chart
- contour plot
- surface plot
- residual plot

### 5. Export and sharing
Results can be exported to:
- Excel
- CSV
- report-ready tables and figures

---

## Typical Workflow

1. User selects the experimental domain  
2. AI suggests factors, levels, and design type  
3. DOE matrix is generated  
4. User inputs response data  
5. ANOVA and visualization are performed  
6. AI provides comments and improvement suggestions  
7. Results are exported for reporting or further use  

---

## System Architecture

```text
User
  ↓
Chat Interface (ChatGPT / Teams / Zalo / Google)
  ↓
AI Guidance Layer
  ↓
DOE Engine
  ├── design.make
  ├── analyze.anova
  ├── plot.screen
  └── export.xlsx
  ↓
Dashboard / Output Files
