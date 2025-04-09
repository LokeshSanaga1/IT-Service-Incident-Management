
# IT Incident Management Optimization

## Overview  
This project analyzes IT incident data from **ABC Tech**, aiming to enhance service desk efficiency and customer satisfaction by leveraging **Machine Learning (ML)** for predictive analytics and automation. Despite mature ITIL practices, customer dissatisfaction highlights the need for data-driven improvements.

### Key Objectives  
- Predict high-priority tickets to enable proactive action  
- Forecast incident volumes for better staffing and resource planning  
- Auto-classify and tag tickets to reduce handling delays  
- Predict RFC (Request for Change) failures to avoid service disruptions  

## Domain Analysis  
The project operates within the **ITIL (Information Technology Infrastructure Library)** framework — a global standard for IT Service Management (ITSM). It focuses on improving service delivery, incident resolution, and change management using historical incident data.

### Influential Feature Categories:
- **Configuration Items**: CI Name, Category, Subcategory  
- **Ticket Info**: Incident ID, Status, Category, KB Number  
- **Time Data**: Open Time, Resolved Time, Closed Time, Handle Time  
- **Severity & Priority**: Impact, Urgency, Priority  
- **Change Management**: Related Changes, RFC outcomes  
- **Customer Experience**: Reassignments, Related Interactions, Closure Code  

## Business Case  
- **Goal**: Boost service desk efficiency and customer experience using predictive modeling  
- **Benefits**:  
  - Reduced critical incident delays  
  - Improved workload forecasting and staffing  
  - Fewer reassignments through accurate auto-tagging  
  - Better change implementation with risk prediction  

## Installation
```bash
git clone https://github.com/LokeshSanaga1/Employee-Performance-Analysis.git
cd Employee-Performance-Analysis
pip install -r requirements.txt
```

## Requirements
```
pandas  
numpy  
matplotlib  
seaborn  
scikit-learn  
xgboost  
```

## Usage
```bash
# Train model
python train_model.py
```
Evaluate using classification and regression metrics (accuracy, MAE, F1-score).

## Results  
The model pipeline enables smarter incident handling by identifying risk-prone tickets and automating manual processes — enhancing the overall service experience.

## Contributing  
Open to feedback, collaboration, and improvements via pull requests or issues.

