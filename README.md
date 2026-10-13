# ArogyaNet AI

## Overview

ArogyaNet AI is an intelligent, offline-capable telehealth and resource triage platform built to bridge healthcare delivery gaps in rural and underserved communities. It empowers local clinics and patients to report symptoms via text or regional voice input, evaluate clinical risk levels instantly, generate printable OP consultation tickets, and coordinate emergency hospital resource allocation.

## Problem Statement

Many rural communities face severe healthcare accessibility barriers due to acute doctor shortages, delayed disease detection, and weak or intermittent internet connectivity. Furthermore, central district hospitals often struggle to track real-time resource demands from peripheral primary health centers, leading to delayed medical intervention and inefficient emergency dispatch.

## Core Objectives

* Collect patient vitals, symptoms, and medical history with dynamic priority routing
* Predict potential health risks and categorize clinical severity into Emergency, Urgent, or Routine
* Enable multilingual, voice-based symptom reporting for low-literacy accessibility
* Issue formatted, thermal-printable digital OP e-tickets and consultation summaries
* Optimize hospital fleet logistics and resource distribution (ventilators, ambulances, specialists)
* Maintain resilient local operation with automatic cloud synchronization when connected

## Offline Data Architecture

The platform operates on a robust offline-first methodology:
When a patient logs symptoms via form or voice input, records are stored immediately within the local SQLite database.
If internet connectivity drops, core triage analysis, registration, and slip generation continue without interruption.
Once an active internet connection is re-established, local consultation records synchronize seamlessly with district hospital servers.

## Technology Stack

Frontend: HTML5, Modern CSS3 (Grid & Flexbox), Vanilla JavaScript

Backend: Python (Flask)

AI & ML: Scikit-learn, Pandas, NumPy

Voice Processing: Sarvam AI Voice APIs, Web Audio APIs

Database: SQLite

Authentication & Security: Session Authentication, Secure Password Hashing, Environment-based Secret Isolation

Version Control: Git, GitHub

## AI Models Used

* Logistic Regression for baseline health risk evaluation
* Random Forest for symptom-driven condition and department classification
* Natural Language Processing (NLP) for multilingual clinical speech and symptom transcription

## User Interface Components

Central Analytics Dashboard -- track total patient visits, active resource shortages, and emergency alerts

Rural OP Kiosk -- intuitive patient self-registration and multilingual symptom intake interface

Fleet & Resource Control -- dual-column dispatcher tracking critical regional hospital shortages and deploying emergency fleet units

Printable OP Slips -- clean thermal-formatted print views for tangible patient token records

## Voice Support

The platform integrates regional voice recognition using Sarvam AI. Patients can speak their symptoms naturally in their local language; the speech is converted into normalized medical text and analyzed by predictive models to determine triage urgency and clinical department routing.

## Author

V. Laxmi Narasimha Reddy

GitHub: [https://github.com/Anjureddy99](https://www.google.com/search?q=https://github.com/Anjureddy99)

## Conclusion

ArogyaNet AI enhances rural healthcare infrastructure by uniting AI diagnostic triage, multilingual speech interfaces, and district resource optimization into an offline-resilient solution. It streamlines primary outpatient care, cuts emergency response latency, and ensures healthcare remains accessible to every community.
