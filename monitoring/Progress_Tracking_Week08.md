# Project Progress & Performance Tracking

## 1. Project Baseline Summary
**Reference:** [planning/WBS_Week04.md] & [budget/Cost_Resource_Plan_Week05.md]

* **Project Title:** AI-Based To-Do List Assistant
* **Planned Duration:** 2025-10-08 to 2025-11-28 (51 Days)
* **Planned Budget:** RM 1005.00 
* **Key Milestones:**
    * Requirements Finalized: 2025-10-10
    * Model Training Completed: 2025-10-31
    * Model Evaluation Completed: 2025-11-07
    * Dashboard Development Completed: 2025-11-14

## 2. Progress Tracking (Status Date: 2025-11-10)

| WBS ID | Task Name | Owner | Planned End | Planned % | Actual % | Status |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| 4.1 | Train intent recognition model | Alicia Goh | 2025-10-28 | 100% | 100% | ✅ Complete |
| 4.2 | Fine-tune entity extraction model | Siti Nuurin | 2025-10-31 | 100% | 85% | 🔴 Behind |
| 5.1 | Evaluate model accuracy | Hor Ying Huai | 2025-11-04 | 100% | 20% | 🔴 Behind |
| 6.1 | Develop Streamlit dashboard | Alicia Goh | 2025-11-11 | 50% | 60% | 🟢 Ahead |
| 6.2 | Integrate Telegram bot | Siti Nuurin | 2025-11-14 | 0% | 0% | 🟢 Ahead |

## 3. Performance Analysis

### Major Deviations
* **Task 4.2 (Fine-tune entity extraction)** is **15% behind**. It was scheduled to finish on Oct 31.
* **Task 5.1 (Evaluate model accuracy)** is **80% behind**. It depends on Task 4.2, so the delay has cascaded.

### Root Cause Analysis
* **Data Complexity:** The dataset collected in Week 4 contained unstructured text that was harder to label than anticipated, delaying the training process for the Entity Extraction model (Task 4.2).
* **Dependency Block:** Hor Ying Huai (Task 5.1) cannot fully evaluate the model until Siti (Task 4.2) releases the final weights.

### Impact on Project
* The **"Model Evaluation Completed"** milestone (Nov 07) has been missed.
* The Critical Path is currently delayed by roughly 1 week, threatening the final submission date if not corrected.