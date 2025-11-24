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

