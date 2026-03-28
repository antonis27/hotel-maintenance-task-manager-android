# hotel-maintenance-task-manager-android
Enterprise Android app for hotel facility maintenance, integrated with Softone ERP. Automates damage reporting, task assignments, and real-time syncing for hospitality teams.

# HotelKEEP - Hotel Maintenance & Task Management

A professional Android solution for hotel maintenance crews to report, track, and resolve facility damages in real-time, fully integrated with Softone ERP.

## 🚀 Project Overview
HotelKEEP streamlines the communication between hotel departments (housekeeping, reception) and the maintenance team. It replaces traditional reporting with an instant, digital workflow that accelerates room repairs and overall hotel facility management.

## 🛠 Tech Stack & Integration
* **Platform:** Android (Java)
* **ERP Backend:** Softone ERP (Hotel@Softone module)
* **Communication:** RESTful API with Dynamic IP switching (Local/Remote)
* **Notifications:** Real-time Push Notifications for task assignments

## ✨ Key Features
* **Real-time Task Lifecycle:** Management of tasks through all stages: Created, In Progress, Impossible to Repair, and Completed.
* **Smart Task Creation (Auto-Mode):** Use of saved templates to minimize manual entry for recurring maintenance issues.
* **Network Adaptability:** Automatic switching between Local and Internet IP based on the device's connection status.
* **Multi-level Asset Mapping:** Tasks are categorized across 5 levels (Block, Department Group, Department, Asset Group, Maintenance Asset).
* **Advanced Filtering:** Powerful search engine for tasks based on status, priority, room number, or department.
* **Audit Trail:** Full history log of every action performed on a specific task for accountability.

## 📐 System Architecture
1. **Android Client:** The frontend interface for hotel staff and maintenance "Keepers".
2. **Softone Integration:** Bidirectional data exchange with the ERP for centralized management.
3. **Task Engine:** Logic layer that handles filtering, status updates, and photo attachments.

---
*Note: This repository contains the technical documentation and architectural overview of the HotelKEEP system. The source code is proprietary.*
