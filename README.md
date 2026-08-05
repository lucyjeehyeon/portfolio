[🇺🇸 English](./README.md) | [🇰🇷 한국어](./README_KO.md)

# 📂 Data Analysis Portfolio

Hello, I’m **Jeehyeon Lee**, an aspiring data analyst.

This repository presents data analysis projects completed through university coursework, capstone research, and data analytics bootcamp projects.  
Rather than simply listing project outcomes, it documents the process of **defining problems, validating data, and translating analytical findings into actionable next steps**.

> **Turning complex data into clear insights and practical next steps.**  
> I turn complex data into clear insights and actionable next steps.

<p>







</p>

---

## 👩‍💻 About Me

I am interested in transforming user behavior and service-related problems into concrete analytical questions, then connecting the results to practical improvement strategies.

My projects span public safety and urban data, product and user behavior, conversion and retention, machine learning, text analysis, and AI ethics. When working on a project, I prioritize **reviewing data definitions and preprocessing rules first, distinguishing observed relationships from causality, and communicating findings clearly through dashboards, reports, and presentations**.

- **Business Question Structuring** — Translating ambiguous problems into measurable analytical questions and metrics
- **User Behavior Analysis** — Identifying conversion and churn bottlenecks through funnel, segmentation, and retention analysis
- **Data Validation** — Reviewing data definitions, missing values, duplicates, join relationships, and analytical assumptions
- **Evidence-Based Analysis** — Applying statistical inference and machine learning while distinguishing association, prediction, and causality
- **Visualization & Storytelling** — Communicating complex findings through dashboards and structured analytical narratives
- **Actionable Recommendations** — Connecting analytical findings to experiments, operational improvements, and service strategy

---

## 📌 Project Summary

| Project | Period | Main Focus | Main Skills | Repository |
|---|---|---|---|---|
| **Shared Office Free-Trial Conversion Funnel Diagnosis** | 2026.07 | Free-trial funnel, repeat-visit conversion signals, branch-level bottleneck diagnosis | Python, Funnel Analysis, Statistical Testing, ML, Tableau | [Repository](https://github.com/lucyjeehyeon/shared-office-trial-conversion-analysis) |
| **Subscription-Based Education Service Conversion & Retention Analysis** | 2026.05-06 | Early learning funnel, activation threshold, first-payment conversion, user segmentation | Python, User Segmentation, Funnel Analysis, A/B Test Design | `Repository URL to be added` |
| **Seoul Subway Accident Cause Analysis & Safety Improvement** | 2026.04 | Temporal, spatial, and structural risk factors by accident type; escalator and elevator accident analysis | Python, EDA, Public Data, Correlation Analysis, Tableau | [Repository](https://github.com/lucyjeehyeon/seoul-subway-safety-analysis) |
| **ToxMod AI Ethics Impact Assessment** | 2025.09-12 | Privacy, fairness, and transparency assessment of a voice moderation AI system | AI Ethics, Risk Analysis, Impact Assessment, Policy Review | - |
| **Steam Game Popularity Prediction Based on Game Attributes** | 2025.03-06 | Classification of top-downloaded games using structured game attributes | Orange3, Decision Tree, Classification, Model Evaluation | - |
| **Analysis of Key Factors Associated with Pothole Occurrence Using Tree-Based Machine Learning** | 2024.09-2025.02 | Integration of spatial, weather, and traffic data and analysis of feature importance | Python, Spatial Data, Feature Engineering, LightGBM | [Repository](https://github.com/lucyjeehyeon/pothole-risk-factor-analysis) |
| **Customer Acquisition Strategy for OTT Platform WATCHA** | 2023.03-06 | Survey-based analysis of user perceptions, usage factors, and marketing direction | Survey Analysis, User Behavior, Statistical Analysis, Strategy | - |
| **Voice Phishing Pattern Analysis** | 2022.09-12, 2023.09-12 | Collection of case scripts and YouTube data, followed by text pattern analysis | Crawling, Text Preprocessing, KoNLPy, WordCloud, Sentiment | [Repository](https://github.com/lucyjeehyeon/voicefishing_analysis) |

---

## 🛠 Skills Demonstrated

| Area | Demonstrated Capabilities | Related Projects |
|---|---|---|
| **Data Preparation & Validation** | Reviewing data definitions, handling missing values and duplicates, validating join keys, designing derived variables, and building analytical marts | Shared Office, Subscription Service, Subway, Pothole, Voice Phishing |
| **Product & User Behavior Analytics** | Funnel analysis, behavioral segmentation, conversion bottleneck analysis, retention and renewal analysis, and branch-level performance diagnosis | Shared Office, Subscription Service, WATCHA |
| **Statistics & Experiment Design** | Proportion comparison, chi-square tests, correlation analysis, confidence intervals, multiple testing, and A/B test design | Shared Office, Subscription Service, Subway, WATCHA |
| **Machine Learning** | Classification modeling, tree-based model comparison, time-series demand forecasting, threshold adjustment, and feature importance interpretation | Shared Office, Steam, Pothole |
| **Spatial & Public Data Analysis** | Coordinate and road-link mapping, public data integration, and combination of external environmental variables | Shared Office, Subway, Pothole |
| **Text, NLP & Survey Analysis** | Web crawling, Korean text preprocessing, noun extraction, word clouds, sentiment analysis, and survey analysis | Voice Phishing, WATCHA, Shared Office Review Analysis |
| **AI Ethics & Risk Analysis** | Stakeholder analysis, privacy, fairness, and transparency assessment, ethical dilemma analysis, and improvement recommendations | ToxMod |
| **Visualization & Communication** | Tableau dashboards, data visualization, analytical storytelling, and report, paper, and presentation development | Shared Office, Subscription Service, Subway, Pothole, Voice Phishing |
| **Project Leadership & Documentation** | Project and team coordination, role assignment, meeting facilitation, preprocessing documentation, code integration, meeting notes, collaboration records, presentations, and Q&A | Shared Office, Subscription Service, Seoul Subway, Pothole, Voice Phishing |

---

## 🗂 Portfolio Categories

| Category | Projects |
|---|---|
| 📊 **Product & User Behavior Analytics** | Shared Office Free-Trial Conversion, Subscription-Based Education Service Conversion & Retention, WATCHA Customer Acquisition |
| 🚇 **Public Safety & Urban Analytics** | Seoul Subway Accident Cause Analysis, Pothole Occurrence Factor Analysis |
| 🤖 **Machine Learning & Predictive Modeling** | Pothole Occurrence Factor Analysis, Steam Game Popularity Prediction, Shared Office Visit Demand Forecasting |
| 🌐 **Spatial & External Data Integration** | Shared Office Branch Analysis, Seoul Subway Accident Analysis, Pothole Occurrence Factor Analysis |
| 📝 **Text, NLP & Survey Analysis** | Voice Phishing Pattern Analysis, WATCHA Customer Acquisition, Shared Office Review Analysis |
| 🛡️ **Risk, Ethics & Social Data Analysis** | ToxMod AI Ethics Impact Assessment, Voice Phishing Pattern Analysis |
| 📈 **Dashboard & Data Storytelling** | Shared Office Branch Performance Dashboard, Seoul Subway Safety Dashboard, Project Presentation Materials |

---

# 🌟 Featured Projects

<a id="project-shared-office"></a>
## 1. Shared Office Free-Trial Conversion Funnel Diagnosis

**Project Type:** Bootcamp Team Project  
**Period:** 2026.07  
**Role:** Team coordinator, external data integration and preprocessing, landmark modeling, multi-branch and branch-level analysis, master table and code integration, Q&A  
**Link:** [Repository](https://github.com/lucyjeehyeon/shared-office-trial-conversion-analysis)

> **Key Finding:** The behavior most consistently associated with free-trial payment conversion was not staying for a long time in a single visit, but making **repeat visits across different dates**.

| Problem | Approach | Result |
|---|---|---|
| Why did payment conversion decline even though applications and visits remained stable? | Change-point detection and decomposition of the application → visit → payment funnel | After September 2023, the bottleneck occurred not at the visit stage, but at the **visit → payment stage** |
| How did the trial behavior of payers differ from that of non-payers? | Comparison of stay time, number of visit days, multi-branch use, time of day, and landmark models | Even among single-branch users, users who visited on multiple dates showed an **8.38 percentage-point higher payment rate** than one-day visitors |
| Where did branch-level performance differences occur? | Integration of behavior and payment data with foot traffic, infrastructure, and map and blog reviews | Branches were diagnosed by **acquisition, experience, and conversion bottlenecks** instead of being ranked |

<details>
<summary><b>🔍 View Analysis Details</b></summary>

### Data & Analysis

- Free-trial behavior and payment data for **9,624 applicants** and **6,026 visitors**
- Funnel analysis and time-series change-point detection across application → visit → payment stages
- Creation of variables for stay time, visit days, check-in count, primary usage time, and multi-branch usage
- Stratified analysis and logistic regression to distinguish the effects of repeat visits and multi-branch usage
- Landmark models adding D0, D1, and D2 behavior sequentially to identify when conversion signals emerged
- Integration of subway foot traffic, nearby infrastructure, and map and blog reviews within a 1 km radius of each branch
- PCA, clustering, and diagnosis of branch-level acquisition, experience, and conversion performance

### Key Insights

- Payment conversion declined from 39.6% before the change point to 25.8% after it
- Users who visited on multiple dates, even for shorter durations, showed a **22.02 percentage-point higher payment rate** than users who stayed longer in a single visit
- The raw payment advantage of multi-branch users diminished substantially after controlling for visit days and behavioral intensity
- Conversion signals strengthened more clearly after D1, suggesting that the period around the **second-day visit** is the most practical intervention point
- The fit between weekday and weekend foot-traffic patterns and actual trial demand mattered more than absolute location foot traffic

### Recommendations

- An **Evening Return Pass** combining D1 rebooking with a reward after behavior completion
- A staged lock-in structure that encourages repeat visits during the trial and multi-branch access and bundled benefits after payment
- Differentiated branch strategies for acquisition capture, monetization and onboarding, structural review, and operating-model standardization

</details>

<details>
<summary><b>🙋‍♀️ Role & Reflection</b></summary>

- **Team coordinator:** facilitated meetings, assigned and adjusted roles during the project, supported major decisions, and managed meeting notes and collaboration records
- Participated in shared preprocessing and the construction of the **master table** connecting application, visit, and payment data
- Integrated and preprocessed **external data**, including subway foot traffic, nearby infrastructure, and map and blog reviews
- Conducted **landmark modeling** using cumulative D0, D1, and D2 behavior to identify when conversion signals strengthened
- Compared multi-branch usage with repeat visits and refined the interpretation by controlling for visit days, check-ins, and stay time
- Conducted **branch-level performance and bottleneck analysis** integrating behavior, payment, infrastructure, review, and foot-traffic data
- **Integrated and organized the team’s analysis code** into a single notebook and validated execution flow and outputs
- Co-created the presentation deck with the team and handled **Q&A** during the final presentation
- Learned the importance of team coordination, analytical documentation, and collaboration structure through a team-lead role distinct from the project lead

</details>

---

<a id="project-subscription"></a>
## 2. Subscription-Based Education Service Conversion & Retention Analysis

**Project Type:** Bootcamp Team Project  
**Period:** 2026.05-06  
**Role:** Early learning funnel analysis, activation threshold analysis, lesson-completion threshold analysis, content improvement prioritization, user segmentation, co-creation of presentation deck, and presentation  
**Link:** `Repository URL to be added` <!-- TODO: Replace with actual repository URL -->  

> **Key Finding:** Early learning progress was a stronger signal for first-payment conversion, while the **number of active learning days after payment** was more closely associated with subscription renewal.

| Problem | Approach | Result |
|---|---|---|
| How could first-payment conversion be improved after the removal of the free trial? | Comparison of behavior during the 7 days before payment with first payment within 30 days | Selected **completion of 7 lessons** as the first operational activation target |
| Did all non-learning users have the same conversion potential? | Defined four segments using content experience and completed lessons | A large difference was observed between inactive users at 1.08% and explorers at 10.98% |
| Which post-payment behavior was associated with renewal? | Low-, medium-, and high-activity segments based on post-payment active learning days | The 60-day renewal rate increased from **48.0% → 56.9% → 63.2%** |

<details>
<summary><b>🔍 View Analysis Details</b></summary>

- Compared sign-ups, first-payment conversion, payment amount, discounts, and early behavior before and after the removal of the free trial
- Analyzed the number of lessons completed within 7 days before payment and first payment within 30 days
- Defined inactive, explorer, weak learner, and strong learner segments using content experience and lesson completion
- Created post-payment active-day segments to capture learning continuity rather than only total learning volume
- Compared user share and expected revenue contribution by payment plan
- Designed an onboarding A/B test and expected-revenue simulation to move inactive users into the explorer segment

### Action Directions

- Inactive users: encourage the first content experience with beginner recommendations and a one-click start CTA
- Weak learners: encourage completion of 7 lessons with next-action guidance and motivational messaging
- Payers: expand active learning days through experience points, rewards, and repeat-visit mechanisms

</details>

<details>
<summary><b>🙋‍♀️ Role</b></summary>

- Reviewed user, content, and event-log definitions and created **7-day post-sign-up preprocessing rules and analytical tables**
- Diagnosed the **lesson page entry → lesson completion funnel** for new users after the removal of the free trial
- Compared whether first-lesson completion was associated with subsequent learning, question-clicking, and payment behavior
- Evaluated payment rate and user scale by lesson-completion count and identified **completion of 7 lessons** as a candidate high-activation threshold
- Segmented users who entered a lesson but did not complete it and proposed improvement actions by behavior level
- Explored **beginner-content improvement priorities** by considering both starting-user scale and incompletion volume
- Analyzed behavior differences across difficulty transition paths, such as beginner → advanced
- Analyzed the relationship between daily discount rate and first-payment conversion
- Designed **user segments**—inactive, explorer, weak learner, and core learner—using content experience and lesson completion count
- Co-created the presentation deck and delivered the final presentation with one other team member

</details>

<details>
<summary><b>⚠️ Interpretation Limitations</b></summary>

- Without advertising-channel and acquisition-quality data, it was difficult to isolate changes in user composition before and after the removal of the free trial
- Some event-log definitions appeared inconsistent, such as course starts being recorded without a prior view event
- Without actual plan policies and billing-cycle definitions, renewal structures by plan required further validation
- Behavioral relationships with payment were not causal, so the impact of proposed actions should be tested through A/B experiments

</details>

---

<a id="project-subway"></a>
## 3. Seoul Subway Accident Cause Analysis & Safety Improvement

**Project Type:** Bootcamp Team Project  
**Period:** 2026.04  
**Role:** Project lead, meeting facilitation, role assignment, decision-making, escalator and elevator accident analysis, co-presentation, and Q&A participation  
**Link:** [Repository](https://github.com/lucyjeehyeon/seoul-subway-safety-analysis)

> **Key Finding:** Rather than attributing accidents to a single cause, the analysis showed that temporal, spatial, and structural risk factors combined differently depending on the accident type.

| Analysis Area | Key Observation | Improvement Direction |
|---|---|---|
| On-board train accidents | Risk patterns were observed during the morning commute, at major transfer hubs, on curved platforms, and in older stations | Crowd management, additional vertical handrails, and consideration of motion-reduction systems |
| In-station accidents | Accident density was highest during the morning commute and concentrated at large transfer stations | Time-based staffing and focused management of complex passenger-flow areas |
| Door and platform-gap accidents | Accident share increased on curved platforms, wider platform gaps, and older stations | Prioritized improvement of risky platform-gap sections and strengthened passenger guidance |
| Escalator and elevator accidents | Facility scale, aging, and external conditions such as rainfall were considered together | Weather-linked inspections and preventive maintenance by equipment type |

<details>
<summary><b>🔍 View Analysis Details</b></summary>

- Classified five years of Seoul Metro safety-accident data by accident type
- Integrated boarding and alighting volume, congestion, platform type and curvature, platform gap, construction year, platform screen doors, escalators and elevators, and weather data
- Preprocessed and merged data by station name and examined 12 analytical hypotheses by accident type
- Distinguished raw accident counts from hourly accident density for time-of-day comparisons
- Visualized accident patterns by line, station, transfer status, platform curvature, and facility age
- Built an interactive subway-safety dashboard in Tableau

### Strengths Highlighted in Project Feedback

- Multi-dimensional integration of weather, congestion, and facility characteristics with accident data
- Consistent visualization using subway-line colors and a subway-themed design
- An interactive dashboard enabling users to explore selected conditions

</details>

<details>
<summary><b>🙋‍♀️ Role</b></summary>

- Served as **project lead**, coordinating analytical direction, assigning roles, facilitating meetings, and representing the team in key decisions
- Participated with all team members in shared preprocessing and aligned common rules for merging accident, usage, facility, and weather data
- Led the individual analysis of **escalator and elevator accidents**, examining station scale, equipment age, rainfall, and other external conditions
- Worked with team members to prioritize analytical findings and define safety-improvement directions
- Co-created the presentation deck and presented with one other team member
- Participated in the Q&A session after the presentation

</details>

<details>
<summary><b>💡 Reflection</b></summary>

Because the analysis included many findings, I learned that communication becomes more effective when the key conclusion is presented first and non-significant or repetitive analyses are condensed. I also learned that variables such as complex passenger flow and congestion require especially clear operational definitions because results can change depending on how they are measured.

</details>

---

<a id="project-toxmod"></a>
## 4. ToxMod AI Ethics Impact Assessment

**Project Type:** University Course Team Project  
**Period:** 2025.09-12  
**Role:** Proposed the assessment target, researched international official documents and academic materials, and co-authored the AI ethics impact assessment report  

> **Key Finding:** The system should be evaluated not only by its toxic-speech detection performance, but also by how voice-data collection and automated sanctions affect user rights and trust.

| Assessment Principle | Main Issue | Recommendation |
|---|---|---|
| Privacy & Data Governance | Separate consent for sensitive voice data, child protection, and transparency of encryption practices | Separate consent, parental verification, and disclosure of encryption policies |
| Fairness | Risks of false positives and cumulative sanctions caused by accents, non-native speech, and cultural context | Representative data, group-level performance monitoring, and staged human review |
| Transparency | Users may not sufficiently understand the reason or criteria for a sanction | Detailed explanations, more accessible appeals, external audits, and transparency reports |

<details>
<summary><b>🔍 View Assessment Details</b></summary>

- Analyzed ToxMod Voice Moderation AI, adopted by Activision to manage in-game voice chat
- Conducted a qualitative impact assessment based on official policies, FAQs, technical documents, academic studies, and domestic and international laws and guidelines
- Analyzed stakeholders including developers, operators, players, children and adolescents, streamers, regulators, and civil-society organizations
- Identified the ethical dilemma between user protection and freedom of expression
- Proposed a staged enforcement process in which AI performs initial detection and humans review final sanctions, supported by periodic external audits

### Role

- Proposed **ToxMod as the assessment target** and helped define the initial project direction
- Researched **international sources**, including Activision and Modulate documentation, international news articles, and academic studies
- Shared findings with the team and co-authored the privacy, fairness, transparency, and improvement sections of the report

</details>

---

<a id="project-steam"></a>
## 5. Steam Game Popularity Prediction Based on Game Attributes

**Project Type:** University Course Individual Project  
**Period:** 2025.03-06  
**Role:** End-to-end individual project execution—problem definition, data cleaning, target design, Orange3 workflow construction, and model evaluation  

> **Key Finding:** Using structured game attributes, I classified whether a game belonged to the top 25% by download count. The Decision Tree model achieved approximately **86% accuracy** and **0.96 ROC-AUC**.

### Project Structure

- **Data:** Kaggle `Best-Selling Steam Games of All Time`, 2,380 games
- **Main Variables:** Price, reviews, ratings, difficulty, age restriction, and other structured attributes
- **Target:** `top_downloaded`, indicating whether a game belonged to the top 25% by download count
- **Workflow:** File → Select Columns → Logistic Regression·Tree → Test & Score → Confusion Matrix
- **Evaluation:** Accuracy, confusion matrix, and ROC curve

<details>
<summary><b>📊 Results & Potential Applications</b></summary>

- Decision Tree confusion matrix: TN 477, FP 52, FN 22, TP 163
- A prototype for estimating whether a game is likely to belong to the high-popularity group before release
- Potential applications include pricing strategy, marketing targeting, and platform-promotion prioritization
- Future analysis could incorporate review text and user tags to improve explanatory power

</details>

---

<a id="project-pothole"></a>
## 6. Analysis of Key Factors Associated with Pothole Occurrence Using Tree-Based Machine Learning

**Project Type:** Capstone Research Team Project  
**Period:** 2024.09-2025.02  
**Role:** Co-collected and preprocessed data, led machine-learning modeling, and led paper writing  
**Links:** [Repository](https://github.com/lucyjeehyeon/pothole-risk-factor-analysis) · [Paper](https://www.dbpia.co.kr/journal/articleDetail?nodeId=NODE12132267)  
**Achievement:** Presented at the 2025 KICS Winter Conference and published as a conference paper

> **Key Finding:** LightGBM achieved the most balanced performance for the pothole class with an **F1-score of 0.81**, and wind speed, inbound and outbound traffic volume, bus-route count, and weather variables emerged as major factors.

| Data | Method | Result |
|---|---|---|
| Pothole, road network and characteristics, risk index, incidents, traffic, bus, and weather data | Spatial coordinate and road-link mapping, monthly integration, undersampling, GridSearchCV | Final dataset of **333,858 rows and 37 variables**; LightGBM accuracy 78% and F1-score 0.81 |

<details>
<summary><b>🔍 View Research Details</b></summary>

- Integrated Seoul pothole and related data from December 2022 to January 2024
- Converted addresses to latitude and longitude and mapped them to road-network links
- Imputed continuous missing values with means, categorical values with modes, and applied one-hot encoding
- Adjusted pothole and non-pothole class imbalance through 1:1 undersampling
- Compared XGBoost, LightGBM, and CatBoost and adjusted the classification threshold using Precision-Recall curves
- Interpreted risk factors through feature importance for preventive road-maintenance planning

### Role

- Participated in collecting and preprocessing selected pothole, road, traffic, and weather datasets through team-based role allocation
- Took primary responsibility for **modeling**, including XGBoost, LightGBM, and CatBoost comparison, hyperparameter tuning, threshold adjustment, and feature-importance interpretation
- Led the process of structuring the analysis and results in an academic format and took primary responsibility for **paper writing**
- Extended the capstone project into a conference presentation and publication

### Research Significance

- Proposed a preventive management perspective for identifying road sections with elevated pothole risk instead of relying only on post-occurrence detection
- Gained experience integrating spatial, traffic, and weather data from multiple institutions at the road-section and monthly levels
- Extended a capstone analysis into a conference presentation and paper publication

</details>

---

<a id="project-watcha"></a>
## 7. Customer Acquisition Strategy for OTT Platform WATCHA

**Project Type:** University Course Team Project  
**Period:** 2023.03-06  
**Role:** Final presentation  

> **Key Finding:** Based on an original survey, the team analyzed reasons for using or not using WATCHA, service perceptions, and marketing opportunities, then proposed differentiated promotion and target-marketing strategies.

### Data & Analysis

- **97 survey responses** and external statistical data, including KOSIS
- Analysis of brand awareness, subscription intention, reasons for usage and non-usage, content preferences, and awareness of supplementary services
- Comparison of gender and age characteristics with brand awareness and subscription intention
- Benchmarking of content and marketing strategies from Netflix and TVING

### Main Recommendations

- Address shortages in original content, mainstream content, and genre diversity
- Promote WATCHA’s differentiated recommendation, rating, and supplementary-service features
- Develop targeted messaging for major user groups, including women in their 20s and 30s
- Reduce entry barriers through free content, promotions, and account-sharing strengths

---

<a id="project-voice-phishing"></a>
## 8. Voice Phishing Pattern Analysis

**Project Type:** Capstone and Follow-up Practice Team Project  
**Period:** 2022.09-12, 2023.09-12  
**Role:** Proposed the topic, wrote crawling code, collected data, co-created the presentation deck, and presented  
**Link:** [Repository](https://github.com/lucyjeehyeon/voicefishing_analysis)

> **Key Finding:** The initial capstone focused on data collection and prototype analysis, and the follow-up practice project improved the preprocessing pipeline and text-analysis workflow.

### Data

- **185 `.doc` scripts** collected from voice-phishing case videos
- Crawled YouTube data including video titles, descriptions, and keywords related to voice phishing

<details>
<summary><b>🔍 View Processing & Analysis</b></summary>

#### Role

- Proposed the **initial idea** of analyzing recurring patterns in voice-phishing cases using data
- Wrote **web-crawling code** to collect relevant YouTube data
- Collected voice-phishing case scripts and video metadata for analysis
- Co-created the presentation deck and delivered the final presentation

#### Script Data

- Converted `.doc` files to `.docx`
- Merged multiple documents into a single DataFrame
- Cleaned Korean text and removed stopwords
- Extracted nouns using KoNLPy
- Visualized the top 100 nouns with word clouds

#### YouTube Data

- Crawled YouTube videos related to voice phishing
- Removed duplicates and filtered irrelevant content such as pranks, comedy, and hidden-camera videos
- Created word clouds from descriptions and keywords
- Conducted sentiment analysis using VaderSentiment
- Built a keyword-based prediction prototype

### Reflection

This was the first project in which I experienced the importance of transforming noisy unstructured data into an analyzable form. By revisiting the initial capstone in a follow-up practice project, I gained experience across the full text-analysis pipeline, including document conversion, merging, cleaning, morphological analysis, and visualization.

</details>

---

# 🗃 Repository Status

This portfolio currently documents the **problem definition, analysis process, key findings, and roles for eight projects**.

- Project with a public repository: Voice Phishing Pattern Analysis
- Repositories to be organized: Shared Office Free-Trial Conversion, Subscription-Based Education Service Conversion & Retention, Seoul Subway Accident Cause Analysis, and Pothole Occurrence Factor Analysis
- Remaining projects are documented through portfolio summaries and key deliverables
- Original project datasets may not be publicly available due to licensing, security, or educational-use restrictions

---

# 📫 Contact

- **GitHub:** [github.com/lucyjeehyeon](https://github.com/lucyjeehyeon)
- **LinkedIn:** [linkedin.com/in/jeehyeon-lee-6100a9223](https://www.linkedin.com/in/jeehyeon-lee-6100a9223)
- **Email:** lucy567888@gmail.com
