# AI-Assisted Patient Workflow for Ophthalmic Care

An AI-assisted patient workflow designed for ophthalmic care to reduce patient waiting time, improve patient flow, and assist healthcare staff with early patient triage.

## 📌 Project Overview

This Final Year Project (FYP) proposes an AI-assisted workflow for ophthalmology services at Hashmanis Hospital.

The system focuses on automating routine administrative tasks and assisting with patient triage while keeping the doctor responsible for all final clinical decisions.

> **Note:** This is a proposed system design for academic and planning purposes. It is not a currently deployed hospital system. AI features, timings, and estimated time savings are planning estimates that require future pilot validation.

## 🎯 Objectives

* Reduce patient waiting time.
* Improve overall patient flow.
* Automate routine booking, payment, and check-in processes.
* Assist with patient triage using symptoms, vitals, and available history.
* Identify emergency, urgent, and routine cases.
* Keep the doctor responsible for final diagnosis and treatment decisions.

## 🔄 Proposed 7-Step Workflow

1. **Online Booking & Payment**
2. **Travel & Parking**
3. **QR Check-in & Vitals**
4. **AI-Assisted Triage**
5. **Smart Waiting Queue**
6. **Doctor Consultation**
7. **Eye Tests (if required)**

## 🤖 AI Triage Module

The proposed AI triage module uses:

* Patient symptoms
* Recorded vitals
* Available patient history

The system suggests one of three priority levels:

* 🔴 Emergency
* 🟠 Urgent
* 🟢 Routine

The AI output is used for patient routing and decision support. The doctor can confirm or override the AI-generated priority label.

## 🏥 System Architecture

**Patient → Booking → QR Check-in / Vitals → AI Triage → Smart Queue → Doctor → Eye Tests**

## ⏱️ Estimated Time Saving

The proposed workflow estimates:

* **23–27 minutes** for visits without eye tests.
* **33–42 minutes** for visits requiring eye tests.
* Estimated time saving: **15–36 minutes per visit**, depending on the scenario.

These are planning estimates and are not measured results from a live hospital deployment.

## 🔐 Safety & Privacy

* Doctor remains responsible for diagnosis and treatment.
* AI only provides decision support.
* Doctors can override AI triage results.
* Patient data is intended to remain within secure hospital systems.
* Access should be restricted to authorized staff.
* A manual fallback process should remain available if the system is unavailable.

## 📋 Functional Requirements

The proposed system includes:

* Online appointment booking
* Online payment
* QR-based patient check-in
* Vitals recording
* AI-assisted patient classification
* Smart queue management
* Doctor review and override
* Diagnosis and treatment recording
* Digital payment receipts

## 🛠️ Future Enhancements

* Pilot testing at a single hospital branch.
* Validate actual patient waiting times.
* Analyze doctor overrides.
* Improve triage rules based on pilot results.
* Extend the system to other suitable specialties.
* Add patient-facing estimated waiting-time updates.

## 📄 Documentation

The complete FYP documentation is available in:

`documentation/AI-Assisted-Patient-Workflow-FYP-Documentation.pdf`

## 🎓 Project Type

**Final Year Project (FYP)**
**Field:** Computer Science / Artificial Intelligence
**Domain:** Healthcare AI / Ophthalmic Care

## ⚠️ Disclaimer

This project is an academic system proposal. It is not intended to replace doctors or provide autonomous medical diagnosis or treatment.
