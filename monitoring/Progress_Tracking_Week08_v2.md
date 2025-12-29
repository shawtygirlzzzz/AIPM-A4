# Project Progress & Performance Tracking

## 1. Project Baseline Summary
**Reference:** [planning/WBS_Week04.md] & [budget/Cost_Resource_Plan_Week05.md]

* **Project Title:** AI-Based To-Do List Assistant
* **Planned Duration:** 2025-10-20 to 2026-01-20 (3 Months)
* **Planned Budget:** RM 1005.00
* **Key Milestones:** 
    * Requirements Finalized: 2025-11-10 (Completed)
    * Model Training Completed: 2025-12-15 (Completed)
    * Model Evaluation Completed: 2025-12-26 (Delayed)
    * Dashboard Development Completed: 2026-01-10 (Upcoming)

## 2. Progress Tracking (Status Date: 2025-12-29)

| WBS ID | Task Name | Owner | Planned End | Planned % | Actual % | Status |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| 4.1 | Train intent recognition model | Alicia Goh | 2025-12-15 | 100% | 100% | ✅ Complete |
| 4.2 | Fine-tune entity extraction model | Siti Nuurin | 2025-12-22 | 100% | 85% | 🔴 Behind |
| 5.1 | Evaluate model accuracy | Hor Ying Huai | 2025-12-26 | 100% | 20% | 🔴 Behind |
| 6.1 | Develop Streamlit dashboard | Alicia Goh | **2026-01-10** | 40% | 60% | 🟢 Ahead |
| 6.2 | Integrate Telegram bot | Siti Nuurin | 2026-01-15 | 0% | 0% | ⚪ Not Started |

## 3. Performance Analysis

### Major Deviations 
* **Task 4.2 (Fine-tune entity extraction)** is **15% behind**. It was scheduled to finish on Dec 22.
* **Task 5.1 (Evaluate model accuracy)** is **80% behind**. It depends on Task 4.2, so the delay has cascaded.

### Root Cause Analysis 
* **Data Complexity (Scope):** The dataset collected contained unstructured text that was harder to label than anticipated, delaying the training process for the Entity Extraction model (Task 4.2).
* **Dependency Block (Resource):** Hor Ying Huai (Task 5.1) cannot fully evaluate the model until Siti (Task 4.2) releases the final weights.

### Impact on Project 
* The **"Model Evaluation Completed"** milestone (Dec 26) has been missed.
* The Critical Path is currently delayed by roughly 1 week, threatening the final submission date if not corrected.