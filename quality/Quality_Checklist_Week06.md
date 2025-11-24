# Quality Definition (Week 06)

## 1. What must the AI system do to be considered successful?
- Accurately understand and classify user commands for task creation, reminders, and updates.
- Correctly extract important entities such as dates, times, task names, and priorities.
- Respond through the Telegram bot within 2 seconds.
- Provide a clean, intuitive, and error-free user experience on both the bot and Streamlit dashboard.
- Operate reliably with minimal misclassifications or crashes.

## 2. What will you measure to confirm the output is of acceptable quality?
- **Intent Recognition Accuracy** – must achieve at least 90%.  
- **Entity Extraction F1-Score** – must achieve at least 85%.  
- **Response Time** – bot replies within 2 seconds; dashboard loads within 3 seconds.  
- **Data Quality Metrics** – dataset completeness, class balance, correct labeling.  
- **User Validation Metrics** – positive feedback from test users on usability and clarity.  
- **System Reliability** – no major errors during testing; stable endpoints and integrations.

## 3. What tools or processes will help ensure quality?
- **Data Cleaning & Validation:** Pandas, regular expressions, manual label checks.  
- **Model Evaluation:** Scikit-learn evaluation metrics, confusion matrix, F1-score analysis.  
- **Testing Procedures:** Unit tests, integration tests for API and bot responses.  
- **Version Control:** GitHub for tracking changes, issues, and updates.  
- **Usability Testing:** Sample user sessions to collect feedback.  
- **Continuous Review:** Peer reviews, repeated testing cycles after Model Training and Integration phases.  

---

- **Accuracy target:**  
  - Intent recognition model must achieve **≥ 90% accuracy**  
  - Entity extraction model must achieve **≥ 85% F1-score**

- **Performance expectations:**  
  - Telegram bot response time **< 2 seconds**  
  - Dashboard loads in **< 3 seconds**  
  - Model produces consistent results across different command types

- **Usability expectations (UI/UX):**  
  - Streamlit interface must be simple, minimal, and intuitive  
  - Telegram bot must understand natural commands with minimal confusion  
  - All features must be accessible without technical knowledge

- **Data quality requirements:**  
  - Dataset must be clean: no duplicates, fewer than 2% missing values  
  - Balanced distribution of intents and entities  
  - Clear mapping of features and labels

---

# Quality Checklist

| Quality Item | Criteria | Status |
|--------------|----------|--------|
| Dataset collection | Sample commands gathered for all required intents | Done |
| Dataset cleaning | No duplicates, consistent formatting, labelled correctly | Done |
| Class balance | Intents not severely imbalanced (±20%) | Done |
| Model architecture | Clear design diagram prepared | Done |
| Intent model performance | ≥ 90% accuracy achieved | Done |
| Entity extraction performance | ≥ 85% F1-score | Done |
| API integration | Telegram bot connects to model without errors | Done |
| Dashboard UI | Responsive layout, clear text, working buttons | Done |
| System integration | Telegram bot + Streamlit dashboard run smoothly together | Done |
| Functionality testing | At least 10 test cases covering intents/entities | Done |
| User validation | Minimum 5 user feedback sessions conducted | Done |
| Documentation | Updated, includes installation, usage, architecture overview | Pending |
| Security | API key hidden, bot token not exposed | Pending |
| Final review | All quality checkpoints passed | Pending |

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
