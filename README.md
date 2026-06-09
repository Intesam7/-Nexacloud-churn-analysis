<h1>🎯 NexaCloud Inc. — Customer Churn Analytics &amp; Revenue Retention Strategy</h1>
<h3>A Full-Cycle Business Analysis &amp; Data Analytics Capstone Project</h3>
<blockquote>
<p><strong>Reducing monthly customer churn from 8.2% to 2.8% through stakeholder-driven analysis, predictive modeling, and integrated solution design — generating a projected $5.88M in annual revenue recovery on a $166K investment (3,445% ROI).</strong></p>
</blockquote>
<hr>
<p><img src="https://img.shields.io/badge/Status-Complete-success" alt="Status"><br>
<img src="https://img.shields.io/badge/Type-Capstone%20Project-blue" alt="Type"><br>
<img src="https://img.shields.io/badge/Tools-Python%20%7C%20SQL%20%7C%20Power%20BI%20%7C%20XGBoost-orange" alt="Tools"><br>
<img src="https://img.shields.io/badge/Domain-SaaS%20%7C%20B2B%20%7C%20Customer%20Success-purple" alt="Domain"></p>
<hr>
<h2>📋 Table of Contents</h2>
<ol>
<li><a href="#executive-summary">Executive Summary</a></li>
<li><a href="#-the-business-problem">The Business Problem</a></li>
<li><a href="#-project-methodology">Project Methodology</a></li>
<li><a href="#-repository-structure">Repository Structure</a></li>
<li><a href="#-quick-access-links">Quick Access Links</a></li>
<li><a href="#-stakeholder-analysis">Stakeholder Analysis</a></li>
<li><a href="#-data-analysis--modeling">Data Analysis &amp; Modeling</a></li>
<li><a href="#-power-bi-dashboard">Power BI Dashboard</a></li>
<li><a href="#-financial-impact">Financial Impact</a></li>
<li><a href="#-proposed-solutions">Proposed Solutions</a></li>
<li><a href="#-implementation-roadmap">Implementation Roadmap</a></li>
<li><a href="#-skills-demonstrated">Skills Demonstrated</a></li>
<li><a href="#-about-the-author">About The Author</a></li>
</ol>
<hr>
<h2>Executive Summary</h2>
<p><strong>NexaCloud Inc.</strong> is a fictional B2B SaaS company offering a Project Management &amp; Collaboration Platform with <strong>8,500 active accounts</strong> and <strong>$12.4M Annual Recurring Revenue (ARR)</strong>. The company is experiencing a critical <strong>8.2% monthly churn rate</strong> — nearly double the SaaS industry benchmark of 3–5% — resulting in <strong>$1.02M in lost MRR every month</strong>.</p>
<p>This capstone project delivers a complete end-to-end Business Analyst engagement: from stakeholder requirement gathering through process mapping, exploratory data analysis, predictive modeling, financial scenario planning, solution design, implementation roadmapping, and interactive dashboard delivery.</p>
<hr>
<h2>🔴 The Business Problem</h2>
<div class="table-wrapper"><table><thead><tr><th>Metric</th><th>Current State</th><th>Industry Benchmark</th><th>Status</th></tr></thead><tbody><tr><td>Monthly Churn Rate</td><td><strong>8.2%</strong></td><td>3–5%</td><td>🔴 CRITICAL</td></tr><tr><td>Annual Churn Rate</td><td><strong>63.7%</strong></td><td>5–7%</td><td>🔴 CRITICAL</td></tr><tr><td>Customer LTV</td><td><strong>9.3 months</strong></td><td>24–36 months</td><td>🔴 LOW</td></tr><tr><td>Net Revenue Retention</td><td><strong>87%</strong></td><td>&gt;100%</td><td>🟡 BELOW</td></tr><tr><td>CAC Payback Period</td><td><strong>18.4 months</strong></td><td>&lt;12 months</td><td>🔴 TOO LONG</td></tr><tr><td>Feature Adoption</td><td><strong>27%</strong></td><td>&gt;60%</td><td>🔴 CRITICAL</td></tr><tr><td>Onboarding Completion</td><td><strong>41%</strong></td><td>&gt;80%</td><td>🔴 CRITICAL</td></tr></tbody></table></div>
<blockquote>
<p><strong>Bottom line:</strong> NexaCloud loses <strong>$33,893 every single day</strong> to preventable churn. Without intervention, the business cannot achieve Series B fundraising metrics.</p>
</blockquote>
<hr>
<h2>🧭 Project Methodology</h2>
<p>This project follows the <strong>CRISP-DM framework</strong> combined with classical <strong>Business Analyst methodology</strong> (Requirement Gathering → Process Mapping → Solution Design → Implementation).</p>
<pre><code>┌─────────────────────────────────────────────────────────┐
│  PHASE 1: BUSINESS UNDERSTANDING                        │
│  → Stakeholder interviews (CEO, CFO, CS Head, Product)  │
│  → Industry benchmarking                                │
│  → Problem statement (SCQ Framework)                    │
│  → SMART objectives + KPI framework                     │
├─────────────────────────────────────────────────────────┤
│  PHASE 2: REQUIREMENT GATHERING                         │
│  → Functional Requirements Document (FRD)               │
│  → Non-Functional Requirements (NFR)                    │
│  → MoSCoW prioritization                                │
│  → Requirements Traceability Matrix                     │
├─────────────────────────────────────────────────────────┤
│  PHASE 3: PROCESS MAPPING                               │
│  → As-Is BPMN Swimlane (5 stages, 24 pain points)       │
│  → Gap Analysis (10 critical gaps)                      │
│  → To-Be redesigned customer journey                    │
├─────────────────────────────────────────────────────────┤
│  PHASE 4: DATA ANALYSIS                                 │
│  → EDA on 8,500 customer accounts                       │
│  → SQL business intelligence queries                    │
│  → XGBoost predictive model (81.2% accuracy)            │
│  → Feature importance + correlation analysis            │
├─────────────────────────────────────────────────────────┤
│  PHASE 5: FINANCIAL MODELING                            │
│  → True cost of churn calculation                       │
│  → LTV / CAC / NRR analysis                             │
│  → 3 scenario models (Do Nothing / Partial / Full)      │
│  → Sensitivity analysis + ROI per solution              │
├─────────────────────────────────────────────────────────┤
│  PHASE 6: SOLUTION DESIGN                               │
│  → 3 integrated solutions designed                      │
│  → Cost-benefit + risk assessment per solution          │
│  → Stakeholder impact mapping                           │
├─────────────────────────────────────────────────────────┤
│  PHASE 7: IMPLEMENTATION ROADMAP                        │
│  → 12-month phased delivery plan                        │
│  → RACI matrix (16 workstreams)                         │
│  → Change management + escalation protocols             │
├─────────────────────────────────────────────────────────┤
│  PHASE 8: DASHBOARD DELIVERY                            │
│  → 3-page Power BI dashboard                            │
│  → 18 custom DAX measures                               │
│  → Available as downloadable .pbix file                 │
└─────────────────────────────────────────────────────────┘
</code></pre>
<hr>
<h2>📁 Repository Structure</h2>
<pre><code>nexacloud-churn-analysis/
│
├── 📄 README.md                          ← You are here
│
├── 📁 01_Report/                         
│   └── NexaCloud_Capstone_Report.pdf     (75+ page consulting-grade report)
│
├── 📁 02_Presentation/                   
│   └── NexaCloud_Presentation.pptx       (Executive presentation deck)
│
├── 📁 03_Python_Analysis/                
│   ├── nexacloud_churn_analysis.ipynb    (Full Jupyter notebook)
│   └── nexacloud_churn_data.csv          (8,500 row synthetic dataset)
│
├── 📁 04_PowerBI/                        
│   ├── NexaCloud_Dashboard.pbix          (Power BI source file)
│   └── Dashboard_Screenshots/
│       ├── page1_executive_dashboard.png
│       ├── page2_churn_risk_dashboard.png
│       └── page3_financial_dashboard.png
│
└── 📁 05_Visualizations/                 
    ├── chart1_churn_rate.png             (Industry benchmark comparison)
    ├── chart2_segment.png                (Churn by customer segment)
    ├── chart3_contract.png               (Monthly vs Annual contracts)
    ├── chart4_onboarding.png             (Onboarding &amp; feature adoption)
    ├── chart5_correlation.png            (Churn driver correlation heatmap)
    ├── chart6_model_performance.png      (Confusion matrix + ROC curve)
    └── chart7_feature_importance.png     (XGBoost feature ranking)
</code></pre>
<hr>
<h2>🔗 Quick Access Links</h2>
<div class="table-wrapper"><table><thead><tr><th>Resource</th><th>Description</th><th>Link</th></tr></thead><tbody><tr><td>📄 <strong>Full PDF Report</strong></td><td>Complete 75+ page consulting report</td><td><a href="./01_Report/">Download</a></td></tr><tr><td>🎤 <strong>Presentation Slides</strong></td><td>Executive presentation deck</td><td><a href="./02_Presentation/">Download</a></td></tr><tr><td>🐍 <strong>Python Notebook</strong></td><td>EDA + Model code (rendered online)</td><td><a href="./03_Python_Analysis/">View</a></td></tr><tr><td>📊 <strong>Power BI File</strong></td><td>Source .pbix file (download to view live)</td><td><a href="./04_PowerBI/">Download</a></td></tr><tr><td>🖼️ <strong>Dashboard Screenshots</strong></td><td>Static images of all 3 dashboard pages</td><td><a href="./04_PowerBI/Dashboard_Screenshots/">View</a></td></tr></tbody></table></div>
<blockquote>
<p>💡 <strong>To explore the live Power BI dashboard:</strong> Download the <code>.pbix</code> file from the <code>04_PowerBI</code> folder and open it in <a href="https://powerbi.microsoft.com/desktop/">Power BI Desktop</a> (free). Dashboard screenshots are provided below for instant preview.</p>
</blockquote>
<hr>
<h2>👥 Stakeholder Analysis</h2>
<p>Stakeholder interviews were conducted using the <strong>SPIN framework</strong> (Situation, Problem, Implication, Need-Payoff). Key requirements were extracted and mapped to functional/non-functional requirements.</p>
<div class="table-wrapper"><table><thead><tr><th>Stakeholder</th><th>Role</th><th>Key Concerns</th><th>Influence</th></tr></thead><tbody><tr><td>Sarah Mitchell</td><td>CEO</td><td>ARR growth, Series B readiness</td><td>🔴 HIGH</td></tr><tr><td>James Okafor</td><td>CFO</td><td>ROI proof, budget justification</td><td>🔴 HIGH</td></tr><tr><td>Tom Reed</td><td>Head of CS</td><td>Workflow gaps, team capacity</td><td>🟡 MEDIUM</td></tr><tr><td>Priya Nair</td><td>Head of Product</td><td>Onboarding redesign, feature usage</td><td>🟡 MEDIUM</td></tr><tr><td>Diana Flores</td><td>Head of Sales</td><td>Acquisition vs retention balance</td><td>🟡 MEDIUM</td></tr><tr><td>Kevin Zhao</td><td>Engineering Lead</td><td>System feasibility, integration scope</td><td>🟡 MEDIUM</td></tr><tr><td>End Customers</td><td>8,500 accounts</td><td>Product value, ease of use</td><td>🔴 HIGH</td></tr></tbody></table></div>
<hr>
<h2>🐍 Data Analysis &amp; Modeling</h2>
<h3>Dataset Overview</h3>
<ul>
<li><strong>Source:</strong> Synthetically generated to reflect realistic SaaS CRM data</li>
<li><strong>Size:</strong> 8,500 customer accounts × 20 features</li>
<li><strong>Period:</strong> January 2023 – December 2024 (24 months)</li>
<li><strong>Quality:</strong> No missing values, no duplicates, all ranges validated</li>
</ul>
<h3>Key Features Engineered</h3>
<pre><code>customer_id                signup_date              customer_segment
subscription_plan          monthly_value            contract_type
onboarding_completed       days_to_first_value      features_adopted
feature_adoption_rate      activation_trifecta      cs_touchpoints
days_since_login           support_tickets          months_as_customer
nps_score                  payment_failures         referred_by_partner
churn_risk_score           risk_category            churned (target)
</code></pre>
<h3>Tools Used</h3>
<div class="table-wrapper"><table><thead><tr><th>Tool</th><th>Purpose</th></tr></thead><tbody><tr><td><strong>Python</strong></td><td>Data manipulation (Pandas, NumPy)</td></tr><tr><td><strong>Matplotlib &amp; Seaborn</strong></td><td>Statistical visualization</td></tr><tr><td><strong>Scikit-learn</strong></td><td>Model evaluation &amp; preprocessing</td></tr><tr><td><strong>XGBoost</strong></td><td>Churn prediction (selected algorithm)</td></tr><tr><td><strong>SQL</strong></td><td>Business intelligence queries (Pandas-based)</td></tr><tr><td><strong>Google Colab</strong></td><td>Notebook environment</td></tr></tbody></table></div>
<h3>Model Performance — XGBoost Classifier</h3>
<div class="table-wrapper"><table><thead><tr><th>Metric</th><th>Result</th></tr></thead><tbody><tr><td><strong>Accuracy</strong></td><td><strong>81.2%</strong></td></tr><tr><td><strong>ROC-AUC Score</strong></td><td><strong>0.879</strong></td></tr><tr><td><strong>Precision (Churn)</strong></td><td>78%</td></tr><tr><td><strong>Recall (Churn)</strong></td><td>76%</td></tr><tr><td><strong>F1 Score</strong></td><td>77%</td></tr></tbody></table></div>
<h3>Top 5 Churn Predictors (Feature Importance)</h3>
<div class="table-wrapper"><table><thead><tr><th>Rank</th><th>Feature</th><th>Importance</th></tr></thead><tbody><tr><td>1</td><td>Feature Adoption Rate</td><td>18.7%</td></tr><tr><td>2</td><td>Onboarding Completed</td><td>15.6%</td></tr><tr><td>3</td><td>Days Since Login</td><td>14.3%</td></tr><tr><td>4</td><td>CS Touchpoints Received</td><td>11.8%</td></tr><tr><td>5</td><td>Activation Trifecta Done</td><td>9.4%</td></tr></tbody></table></div>
<blockquote>
<p><strong>Key insight:</strong> The top 4 features account for <strong>60.4% of all model predictive power</strong> — and ALL are directly addressable through the 3 proposed solutions.</p>
</blockquote>
<hr>
<h2>📊 Power BI Dashboard</h2>
<p>The dashboard delivers <strong>three stakeholder-specific views</strong> designed for different audiences and decision-making needs.</p>
<blockquote>
<p>📥 <strong>Download the <code>.pbix</code> file</strong> from the <a href="./04_PowerBI/">04_PowerBI folder</a> to explore the interactive version. Screenshots below provide instant preview.</p>
</blockquote>
<h3>Page 1 — Executive KPI Dashboard</h3>
<p><strong>Audience:</strong> CEO, Board<br>
<strong>Purpose:</strong> Strategic single-glance view of retention health</p>
<p><img src="./04_PowerBI/Dashboard_Screenshots/page1_executive_dashboard.png" alt="Executive Dashboard"></p>
<p><strong>Visuals Included:</strong></p>
<ul>
<li>4 critical KPI cards (Churn Rate, MRR Lost, NRR, LTV)</li>
<li>Monthly churn rate trend line</li>
<li>Churn rate by customer segment</li>
<li>Monthly vs Annual contract distribution</li>
<li>Customer segment slicer</li>
</ul>
<hr>
<h3>Page 2 — Churn Risk Dashboard</h3>
<p><strong>Audience:</strong> CS Head, Customer Success Team<br>
<strong>Purpose:</strong> Operational daily action list for at-risk accounts</p>
<p><img src="./04_PowerBI/Dashboard_Screenshots/page2_churn_risk_dashboard.png" alt="Churn Risk Dashboard"></p>
<p><strong>Visuals Included:</strong></p>
<ul>
<li>4 risk distribution cards (High / Medium / Low / MRR at risk)</li>
<li>At-risk account priority table (conditional formatting)</li>
<li>Risk distribution by segment</li>
<li>Feature adoption vs churn risk scatter</li>
<li>Login activity histogram</li>
<li>Risk category filter</li>
</ul>
<hr>
<h3>Page 3 — Financial Impact Dashboard</h3>
<p><strong>Audience:</strong> CFO, CEO<br>
<strong>Purpose:</strong> Financial business case and scenario planning</p>
<p><img src="./04_PowerBI/Dashboard_Screenshots/page3_financial_dashboard.png" alt="Financial Dashboard"></p>
<p><strong>Visuals Included:</strong></p>
<ul>
<li>4 financial KPI cards (Annual cost, Daily cost, Investment, ROI)</li>
<li>Revenue scenario comparison (Do Nothing / Partial / Full)</li>
<li>Customer LTV progression line chart</li>
<li>Monthly MRR lost by segment treemap</li>
</ul>
<hr>
<h2>💰 Financial Impact</h2>
<h3>Cost of Churn — Quantified</h3>
<div class="table-wrapper"><table><thead><tr><th>Component</th><th>Monthly</th><th>Annual</th></tr></thead><tbody><tr><td>MRR Lost to Churn</td><td>$1,016,800</td><td>$12,201,600</td></tr><tr><td>CAC Replacement Cost</td><td>$179,826</td><td>$2,157,912</td></tr><tr><td>CS Time on Cancellations</td><td>$47,048</td><td>$564,573</td></tr><tr><td>Failed Onboarding Investment</td><td>$90,270</td><td>$1,083,240</td></tr><tr><td><strong>TOTAL TRUE COST</strong></td><td><strong>$1,333,944</strong></td><td><strong>$16,007,325</strong></td></tr></tbody></table></div>
<h3>3 Strategic Scenarios Modeled</h3>
<div class="table-wrapper"><table><thead><tr><th>Scenario</th><th>Churn Rate</th><th>Annual Saving</th><th>Investment</th><th>ROI</th></tr></thead><tbody><tr><td>Do Nothing</td><td>8.2%</td><td>$0</td><td>$0</td><td>N/A</td></tr><tr><td>Partial Fix</td><td>5.0%</td><td>$4,768,920</td><td>$96,000</td><td>4,868%</td></tr><tr><td><strong>Full Fix (Recommended)</strong></td><td><strong>4.1% → 2.8%</strong></td><td><strong>$6,111,504</strong></td><td><strong>$166,000</strong></td><td><strong>3,682%</strong></td></tr></tbody></table></div>
<h3>Sensitivity Analysis (Worst-Case Stress Test)</h3>
<p>Even at <strong>10% of projected impact</strong>, the program delivers <strong>368% ROI</strong>. There is no realistic scenario where this investment does not pay back.</p>
<hr>
<h2>🚀 Proposed Solutions</h2>
<h3>Solution 1: Early Warning Churn Alert System</h3>
<blockquote>
<p>Automated ML scoring engine flagging at-risk accounts <strong>72 hours before predicted churn</strong></p>
</blockquote>
<div class="table-wrapper"><table><thead><tr><th>Metric</th><th>Value</th></tr></thead><tbody><tr><td>Investment</td><td>$42,000 (one-time)</td></tr><tr><td>Annual Saving</td><td>$3,100,000</td></tr><tr><td>ROI</td><td><strong>7,281%</strong></td></tr><tr><td>Payback</td><td>5 days</td></tr></tbody></table></div>
<p><strong>Stack:</strong> XGBoost model + Amplitude data pipeline + Salesforce integration + Power BI alerts</p>
<hr>
<h3>Solution 2: Structured Customer Success Program</h3>
<blockquote>
<p>30/60/90 day touchpoint framework + intervention playbook for <strong>100% of accounts</strong></p>
</blockquote>
<div class="table-wrapper"><table><thead><tr><th>Metric</th><th>Value</th></tr></thead><tbody><tr><td>Investment</td><td>$96,000/year (2 CS hires)</td></tr><tr><td>Annual Saving</td><td>$1,800,000</td></tr><tr><td>ROI</td><td><strong>1,775%</strong></td></tr><tr><td>Payback</td><td>19 days</td></tr></tbody></table></div>
<p><strong>Includes:</strong> Tiered intervention protocol (Low/Medium/High/Critical), CS performance dashboard, accountability KPIs</p>
<hr>
<h3>Solution 3: Onboarding Experience Redesign</h3>
<blockquote>
<p>Interactive guided tour replacing passive checklist → time-to-value from <strong>14 days to 3 days</strong></p>
</blockquote>
<div class="table-wrapper"><table><thead><tr><th>Metric</th><th>Value</th></tr></thead><tbody><tr><td>Investment</td><td>$28,000 (one-time)</td></tr><tr><td>Annual Saving</td><td>$980,000</td></tr><tr><td>ROI</td><td><strong>3,400%</strong></td></tr><tr><td>Payback</td><td>10 days</td></tr></tbody></table></div>
<p><strong>Framework:</strong> Activation Trifecta (Create Project + Invite Team + Connect Integration)</p>
<hr>
<h3>Combined Solution Impact</h3>
<pre><code>Combined Investment:    $166,000
Combined Annual Saving: $5,880,000
Net Annual Benefit:     $5,714,000
Year 1 ROI:             3,445%
Payback Period:         11 days
</code></pre>
<hr>
<h2>📅 Implementation Roadmap</h2>
<h3>12-Month Phased Delivery</h3>
<div class="table-wrapper"><table><thead><tr><th>Phase</th><th>Duration</th><th>Focus</th><th>Outcome</th></tr></thead><tbody><tr><td><strong>Phase 1 — Foundation</strong></td><td>Month 0–3</td><td>CS hiring + Data pipeline build</td><td>Infrastructure ready</td></tr><tr><td><strong>Phase 2 — Activation</strong></td><td>Month 3–6</td><td>All 3 solutions live + first MRR saved</td><td>Churn ≤ 4.1%</td></tr><tr><td><strong>Phase 3 — Optimization</strong></td><td>Month 6–12</td><td>Model retraining + Scale + Win-back</td><td>Churn ≤ 2.8%</td></tr></tbody></table></div>
<h3>Governance Framework</h3>
<ul>
<li>✅ <strong>RACI Matrix</strong> mapping 16 workstreams across 8 stakeholders</li>
<li>✅ <strong>3-tier KPI tracking</strong> (Business / Operational / Customer Health)</li>
<li>✅ <strong>3-level escalation protocol</strong> for KPI deviations</li>
<li>✅ <strong>Change management plan</strong> addressing CS team mindset shift</li>
<li>✅ <strong>Communication plan</strong> for all stakeholder groups</li>
</ul>
<hr>
<h2>🎓 Skills Demonstrated</h2>
<h3>Business Analysis Core Competencies</h3>
<ul>
<li>✅ <strong>Requirement Gathering</strong> — SPIN framework interviews, FRD, NFR, MoSCoW</li>
<li>✅ <strong>Process Mapping</strong> — BPMN Swimlanes, As-Is/To-Be, Gap Analysis</li>
<li>✅ <strong>Stakeholder Management</strong> — RACI matrices, influence mapping, communication plans</li>
<li>✅ <strong>Solution Design</strong> — Cost-benefit, risk assessment, architectural diagrams</li>
<li>✅ <strong>Implementation Support</strong> — Phased roadmaps, change management, KPI tracking</li>
</ul>
<h3>Data &amp; Technical Skills</h3>
<ul>
<li>✅ <strong>Exploratory Data Analysis</strong> — Python (Pandas, NumPy, Matplotlib, Seaborn)</li>
<li>✅ <strong>SQL Querying</strong> — Business intelligence query writing</li>
<li>✅ <strong>Predictive Modeling</strong> — XGBoost classifier, model selection, evaluation</li>
<li>✅ <strong>Data Visualization</strong> — Power BI dashboard design, custom DAX measures</li>
<li>✅ <strong>Synthetic Dataset Engineering</strong> — Realistic CRM data simulation</li>
</ul>
<h3>Financial &amp; Strategic Skills</h3>
<ul>
<li>✅ <strong>Financial Modeling</strong> — LTV, CAC, NRR, ARR calculations</li>
<li>✅ <strong>Scenario Analysis</strong> — Multi-scenario projections with sensitivity testing</li>
<li>✅ <strong>ROI Quantification</strong> — Investment justification with payback analysis</li>
<li>✅ <strong>Executive Communication</strong> — Board-ready summaries, McKinsey-style narratives</li>
</ul>
<hr>
<h2>🛠️ Complete Tech Stack</h2>
<pre><code>LANGUAGES &amp; LIBRARIES
├── Python 3.10
│   ├── Pandas 2.0+      → Data manipulation
│   ├── NumPy 1.24+      → Numerical computing
│   ├── Matplotlib 3.7+  → Charting
│   ├── Seaborn 0.12+    → Statistical visualization
│   ├── Scikit-learn 1.3+ → Model evaluation
│   └── XGBoost 1.7+     → Predictive modeling
│
└── SQL                  → Business intelligence queries

VISUALIZATION &amp; REPORTING
├── Power BI Desktop     → Interactive dashboards
├── DAX                  → Custom measures (18 created)
└── Microsoft Word/PDF   → Professional report

PROCESS &amp; DOCUMENTATION
├── BPMN Notation        → Swimlane process mapping
├── Excel                → Financial modeling
└── Markdown             → Documentation

ENVIRONMENT
└── Google Colab         → Cloud-based notebook
</code></pre>
<hr>
<h2>📈 Key Project Outcomes</h2>
<div class="table-wrapper"><table><thead><tr><th>Deliverable</th><th>Detail</th></tr></thead><tbody><tr><td>📄 <strong>Consulting Report</strong></td><td>75+ pages, 9 sections, board-ready</td></tr><tr><td>🐍 <strong>Python Notebook</strong></td><td>Full EDA + XGBoost model + interpretation</td></tr><tr><td>📊 <strong>Power BI Dashboard</strong></td><td>3 pages, 18 DAX measures, downloadable</td></tr><tr><td>🎨 <strong>Process Diagrams</strong></td><td>As-Is + To-Be BPMN swimlanes</td></tr><tr><td>💰 <strong>Financial Model</strong></td><td>3 scenarios + sensitivity analysis</td></tr><tr><td>📋 <strong>Implementation Plan</strong></td><td>12 months, RACI matrix, milestones</td></tr><tr><td>🤖 <strong>Predictive Model</strong></td><td>81.2% accuracy, 0.879 ROC-AUC</td></tr></tbody></table></div>
<hr>
<h2>💡 What Makes This Project Different</h2>
<blockquote>
<p>Most BA portfolio projects show <strong>either</strong> business documentation <strong>or</strong> data analysis. This project demonstrates <strong>the full BA value chain</strong> — from stakeholder interviews to predictive models to executive dashboards to implementation roadmaps.</p>
</blockquote>
<p><strong>This project proves the ability to:</strong></p>
<ul>
<li>Bridge business and technical worlds (the core BA role)</li>
<li>Translate stakeholder needs into requirements (FRD/NFR)</li>
<li>Move from raw data to executive insight (Python → Power BI)</li>
<li>Justify decisions with financial rigor (ROI, payback, sensitivity)</li>
<li>Plan execution with operational discipline (RACI, milestones, KPIs)</li>
</ul>
<hr>
<h2>🧪 How To Explore This Project</h2>
<h3>Option 1: Quick Preview (No Downloads)</h3>
<ol>
<li>Browse the README sections above</li>
<li>View dashboard screenshots in <a href="./04_PowerBI/Dashboard_Screenshots/">04_PowerBI/Dashboard_Screenshots/</a></li>
<li>View EDA charts in <a href="./05_Visualizations/">05_Visualizations/</a></li>
<li>Click on the <a href="./03_Python_Analysis/">Python notebook</a> — GitHub renders it with all code and outputs</li>
</ol>
<h3>Option 2: Deep Dive</h3>
<ol>
<li>Download the <a href="./01_Report/">full PDF report</a> — read all 9 sections</li>
<li>Download the <a href="./04_PowerBI/">Power BI file</a> and open in Power BI Desktop</li>
<li>Download the <a href="./03_Python_Analysis/">Jupyter notebook</a> and run in Google Colab</li>
<li>Review the <a href="./02_Presentation/">presentation deck</a> for executive summary</li>
</ol>
<h3>Option 3: For Recruiters / Hiring Managers</h3>
<ol>
<li>Start with this README for project overview</li>
<li>Download the PDF report for full methodology</li>
<li>Reach out via <a href="https://www.linkedin.com/in/muhammad-intesam-ur-rehman-178223278">LinkedIn</a> or email for discussion</li>
<li>I'm happy to walk through the project in a screen share</li>
</ol>
<hr>
<h2>👤 About The Author</h2>
<p><strong>Muhammad Intesam Ur Rehman</strong><br>
Business Analyst | Data Analytics | SaaS Strategy</p>
<blockquote>
<p><em>Bridging business problems with data-driven technical solutions.</em></p>
</blockquote>
<p>📧 <strong>Email:</strong> <a href="mailto:intesamchaudhry@gmail.com">intesamchaudhry@gmail.com</a><br>
🔗 <strong>LinkedIn:</strong> <a href="https://www.linkedin.com/in/muhammad-intesam-ur-rehman-178223278">linkedin.com/in/muhammad-intesam-ur-rehman-178223278</a></p>
<hr>
<h2>📝 Project Notes</h2>
<p><strong>NexaCloud Inc.</strong> is a fictional company created for portfolio demonstration purposes. The dataset is synthetically generated to reflect realistic SaaS CRM behavioral patterns. All methodology, frameworks, and analytical techniques reflect real-world business analysis practices used in professional consulting and enterprise environments.</p>
<p>This project is part of my Business Analyst portfolio and is <strong>available for review by recruiters and hiring managers</strong>.</p>
<hr>
<h2>🤝 Connect &amp; Discuss</h2>
<p>I welcome feedback, suggestions, and discussions about this project. If you're a recruiter, hiring manager, or fellow analyst, please feel free to reach out via LinkedIn or email.</p>
<p>If this project demonstrates the kind of work you're looking for in a Business Analyst, <strong>let's talk.</strong></p>
<hr>
<h2>⭐ Acknowledgment</h2>
<p>If you found this project valuable, please consider <strong>starring this repository</strong>. It helps other aspiring BAs discover the work and means a lot to me personally.</p>
<hr>
<p><strong>Project Status:</strong> ✅ Complete<br>
<strong>License:</strong> Available for portfolio review</p>
<hr>
<blockquote>
<p><em>"Most companies don't have a churn problem. They have an engagement problem. The data proves it."</em><br>
— Key insight from NexaCloud analysis</p>
</blockquote>
