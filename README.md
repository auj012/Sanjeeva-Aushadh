# Sanjeeva-Aushadh
A Cross-Functional Data Science and AI Trilogy Platform for Patient Allergy Safety (Divya Drishti -> Lakshman Rekha -> Sanjeevani).

Folder Structure
Sanjeeva-Aushadh/                       #  Repo Root
├── .github/workflows/
│   └── generate_portfolio_workspace.yml  # (We will create this in Step 3)
├── documentation/
│   ├── 01_ideation/
│   │   ├── product_trilogy_vision.md   # The Master Vision
│   │   ├── elevator_pitch.md           # 30-Second Blueprint
│   │   └── yc_pitch_deck.md            # Y-Combinator Proposal Text
│   ├── 02_product_spec/
│   │   ├── PRD_phase1_divya_drishti.md # Module 1: Descriptive Analytics PRD
│   │   ├── PRD_phase2_lakshman_rekha.md# Module 2: Safety Gatekeeper PRD
│   │   └── PRD_phase3_sanjeevani.md    # Module 3: Recommendation Engine PRD
│   ├── 03_architecture/
│   │   ├── system_design_v1_divya.md   # V1 System Flow (Mermaid)
│   │   └── system_design_v2_predictive.md # V2 LLM/Graph Architecture
│   ├── 04_project_mgmt/
│   │   └── portfolio_roadmap.md        # Gantt / Timeline Document
│   └── 06_qa_evals/
│       ├── test_plan_clinical_safety.md# Master Software QA Guidelines
│       └── model_evaluation_report.md  # Precision/Recall Evaluation Metrics
├── src/                                # Your Production Code
│   ├── data_generation/
│   │   └── synthetic_meds_generator.py # Script making mock FDA/EHR data
│   ├── phase1_divya_drishti/
│   │   └── descriptive_indicators.py   # Code calculating percentages & modes
│   ├── phase2_lakshman_rekha/
│   │   └── clinical_decision_rules.py  # Code intercepting allergen crossings
│   └── phase3_sanjeevani/
│       └── alternative_router.py       # Code routing safe alternative excipients
├── tests/
│   ├── test_divya_engine.py            # Automated tests for your data math
│   └── test_safety_rules.py            # Automated tests for safety rules
├── CHANGELOG.md                        # Product Release Notes
├── README.md                           # Main Profile Page
└── tasks.json                          # 
