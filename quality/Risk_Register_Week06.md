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

### Quality Check Insertions
Quality review points were added at eight major milestones:
1. Requirement validation after completing Task 1.1 and 1.2  
2. Dataset quality verification after completing Task 2.1 and 2.2  
3. Architecture review after completing Task 3.1 and 3.2  
4. Model performance evaluation after completing Task 4.1 and 4.2  
5. Final model selection review after Task 5.1 and 5.2  
6. Integration validation after Task 6.1 and 6.2  
7. Usability and functionality assessment after Task 7.1 and 7.2  
8. Documentation and submission readiness check before Task 8.1 and 8.2  

### Risk Mapping
High-risk items were linked to the following tasks:
- Dataset insufficiency: Tasks 2.1–2.2  
- Model underperformance: Tasks 4.1–4.2  
- Integration failures (API/Bot): Tasks 6.1–6.2  
- User acceptance issues: Tasks 7.1–7.2  

Medium-risk items were associated with:
- Misalignment of features or architecture: Tasks 3.1–3.2  
- Class imbalance and label errors: Tasks 2.2  

### Schedule Adjustments
Several tasks required duration extensions:
- Dataset-related tasks extended by 2 days each  
- Model-training tasks extended by 1 day each  
- Model evaluation tasks extended by 1 day  
- Integration tasks extended by 1 day each  
- Testing and validation tasks extended by 2 days 
