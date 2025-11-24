# Risk Register (Week 06)

| Risk ID | Description | Category | L | I | Score | Response |
|---------|-------------|----------|---|---|--------|----------|
| R1 | Dataset too small or unbalanced for intent/entity recognition | Technical | 3 | 4 | 12 | Mitigate |
| R2 | Intent model fails to reach 90% accuracy | Technical | 4 | 5 | 20 | Reduce |
| R3 | Entity extraction model performance too low | Technical | 3 | 4 | 12 | Mitigate |
| R4 | Integration issues between Telegram bot and backend API | Technical | 3 | 5 | 15 | Mitigate |
| R5 | Team member delay affects training and integration timeline | Schedule | 3 | 3 | 9 | Monitor |
| R6 | Limited GPU or compute resources slow down model training | Resource | 4 | 4 | 16 | Mitigate |
| R7 | Unexpected bugs in Streamlit dashboard impacting UI/UX | Technical | 3 | 3 | 9 | Reduce |
| R8 | Miscommunication or inconsistent updates within group | Stakeholder | 2 | 3 | 6 | Improve communication |
| R9 | Increase in cloud costs (if using cloud training or hosting) | Cost | 2 | 3 | 6 | Monitor |
| R10 | Telegram API changes or instability during development | Technical | 2 | 4 | 8 | Accept |

---

# Top Priority Risks (Mitigation Plans)

## 1. **R2 – Intent model fails to reach 90% accuracy**  
- **Score:** 20  
- **Mitigation:** Expand dataset, tune epochs/layers/lr, try different architectures (BERT, DistilBERT, CNN-based).  
- **Owner:** Hor Ying Huai, Alicia Goh  
- **Deadline:** 2025-10-31  

## 2. **R6 – Limited GPU or compute resources**  
- **Score:** 16  
- **Mitigation:** Use Google Colab GPU scheduling, reduce model complexity, optimise batch size, use early stopping.  
- **Owner:** Siti Nuurin Hayati  
- **Deadline:** 2025-10-29  

## 3. **R4 – Telegram bot and API integration issues**  
- **Score:** 15  
- **Mitigation:** Start integration early, test endpoints individually, maintain fallback rule-based commands.  
- **Owner:** Fareen Nathrah  
- **Deadline:** 2025-11-14  

---

# Integration Notes

- Risk mitigation scheduled during **Phase 4 (Model Training)** and **Phase 6 (Integration)**.  
- Integration-related risks mapped directly to WBS tasks **6.1** and **6.2**.  
- Extra buffer time added in schedule for debugging and integration tests.

