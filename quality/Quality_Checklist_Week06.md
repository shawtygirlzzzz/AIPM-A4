# Quality Definition (Week 06)

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
| Dataset collection | Sample commands gathered for all required intents | Pending |
| Dataset cleaning | No duplicates, consistent formatting, labelled correctly | Pending |
| Class balance | Intents not severely imbalanced (±20%) | Pending |
| Model architecture | Clear design diagram prepared | Pending |
| Intent model performance | ≥ 90% accuracy achieved | Pending |
| Entity extraction performance | ≥ 85% F1-score | Pending |
| API integration | Telegram bot connects to model without errors | Pending |
| Dashboard UI | Responsive layout, clear text, working buttons | Pending |
| System integration | Telegram bot + Streamlit dashboard run smoothly together | Pending |
| Functionality testing | At least 10 test cases covering intents/entities | Pending |
| User validation | Minimum 5 user feedback sessions conducted | Pending |
| Documentation | Updated, includes installation, usage, architecture overview | Pending |
| Security | API key hidden, bot token not exposed | Pending |
| Final review | All quality checkpoints passed | Pending |

---

# Integration Notes

- Quality checks inserted after **Model Training (WBS 4.1 & 4.2)** and again after **Dashboard + Bot Integration (WBS 6.2)**.  
- Highest risk areas occur in **Phase 4 (Model Training)** and **Phase 6 (System Integration)**.  
- Planner schedule updated to include **model performance verification**, **integration testing**, and **user validation buffer time**.

