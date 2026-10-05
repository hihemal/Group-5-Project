# Group-5-Project

BioTrack — Personal Health & Biomarker Analytics Platform

My strongest recommendation for you.

A system where users can enter/import health measurements over time and the system analyzes trends rather than pretending to diagnose diseases.

Examples:

Blood pressure
Heart rate
SpO₂
Weight
BMI
Blood glucose
HbA1c
Cholesterol
Hemoglobin
WBC
Vitamin D
Creatinine
Liver enzymes

The interesting part isn't storing the numbers.

The interesting part is longitudinal analysis.

                USER
                  │
                  ▼
        ┌──────────────────┐
        │ Health Records   │
        └────────┬─────────┘
                 │
       ┌─────────┼─────────┐
       ▼         ▼         ▼
    Trends    Correlation  Alerts
       │         │         │
       └─────────┼─────────┘
                 ▼
        ┌──────────────────┐
        │ Health Dashboard │
        └──────────────────┘
Example

A user enters:

Creatinine

Jan     92
Feb     95
Mar    101
Apr    108
May    112

Your system could identify:

Increasing trend detected

and show:

slope
percentage change
moving average
historical graph
reference interval visualization

Importantly, the system should say "trend detected", not "you have kidney disease."

Stack

Frontend

React / Next.js
Tailwind
Recharts

Backend

Django REST Framework
PostgreSQL
Redis/Celery if needed

Analytics

Python
Pandas
NumPy
SciPy
scikit-learn

This is very achievable at a high/moderate lev


Hey this is my project idea,,,make a project proposal from this,, and also make a ppdt file from it
