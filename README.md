# Mapping the Mental Health Landscape in Tech Workplaces 

*Insights, Signals, and Predictive Patterns from Global Tech Workers*

## Project Overview
“We don’t have to do all of it alone. We were never meant to.” Brené Brown

Tech workplaces are high-pressure environments where long hours, tight deadlines, and digital overload can quietly erode mental well-being. This project explores how personal background, workplace culture, and organizational support influence whether employees seek mental health treatment. Using cleaned, structured survey data and interpretable machine learning, the study uncovers patterns that reveal where support systems succeed, where they fail, and how data-driven tools could guide more empathetic workplace interventions.

## Problem Statement
Despite the growing awareness of mental health, many organizations struggle to identify employees in need until problems escalate. Support systems are often inaccessible, poorly understood, or underutilized. This project examines the subtle and overt signals that predict treatment-seeking, from personal factors like family history and age to workplace factors like leave policies and care availability. By uncovering these patterns, the goal is to provide actionable insights that help tech organizations create safer, more supportive environments without labeling individuals or compromising privacy.

## Objectives
- Identify key predictors of treatment-seeking behavior

- Understand how workplace culture shapes help-seeking

- Build an interpretable predictive model

- Provide actionable recommendations for organizations

- Explore responsible AI applications for early detection

## Data Understanding
This project uses publicly available mental health survey data from the Open Sourcing Mental Illness (OSMI) initiative. The surveys capture how tech employees experience, discuss, and seek support for mental health challenges across multiple years.

For this study, all available survey years were combined to create a comprehensive dataset. Key details include:

- Demographics: age, gender, country, and company size

- Workplace context: policies, leave flexibility, and perceived support

- Mental health indicators: whether treatment was sought, family history, and access to care options

The combined dataset was cleaned and standardized to ensure consistency across years, producing a ready-to-use dataset for exploration, modeling, and storytelling.

Source: [OSMI Mental Health in Tech Datasets (Kaggle)](https://www.kaggle.com/osmihelp/datasets)

## Data Preprocessing and Modelling

The OSMI survey data from multiple years was cleaned and standardized, ensuring consistency across demographics, workplace factors, and mental health indicators. Missing target values were removed, categorical variables harmonized, and the dataset prepared for reliable analysis and modeling.

To uncover patterns that influence treatment-seeking behavior, interpretable machine learning models were applied:

Logistic Regression (Primary Model): Chosen for transparency and strong performance. It highlights the key factors that drive treatment-seeking, such as family history, age, work interference, and access to care.

Random Forest (Supporting Model): Used to validate patterns and provide additional insights through non-linear feature importance.

Models were evaluated using accuracy, F1 score, and ROC AUC. ROC AUC was particularly important because it accounts for class imbalance (treatment-seeking vs non-treatment-seeking) and measures how well the model discriminates between the two groups. Logistic Regression was chosen as the final model because it delivers clear, interpretable results that translate directly into actionable workplace insights.


## Insights and Key Findings 

The analysis uncovers clear patterns that explain what drives treatment-seeking behavior in tech workplaces:

- Personal Factors Matter Most

Employees with a family history of mental illness are significantly more likely to seek treatment. Age also contributes, with older employees. These patterns highlight how personal awareness and experience influence mental health decisions.

- Workplace Environment Shapes Action

Work interference was the most consistent predictor across models. Supportive leave policies and larger company structures correlate with higher treatment-seeking, emphasizing the role of psychological safety and accessible, flexible time-off processes.

- Access to Resources Encourages Help-Seeking

Availability of mental health benefits and care options increases the likelihood of pursuing treatment. Having support systems in place matters as much as the underlying need.

- Gender and Cultural Context Have Secondary Effects

Female and non-binary employees seek help at higher rates than males. Country differences exist but are less influential than personal and workplace factors.

- Consistent Signals Across Models

Both Logistic Regression and Random Forest agree on the top predictors: family history, age, work interference, leave difficulty, company size, and care options. This alignment strengthens confidence in the findings: personal vulnerability + workplace support = core drivers of treatment-seeking behavior.

These insights provide actionable guidance for organizations aiming to improve employee well-being and create supportive work environments.

## Recommendations & AI-Aligned Opportunities

1. **Early Detection & Support**  
- **Insight:** Work interference and family history are strong predictors.  
- **Action:** Implement systems to identify early signs of stress and provide timely support.  
- **AI Opportunity:** Privacy-respecting AI can detect workload patterns, prompt early help-seeking, and nudge employees to resources.

2. **Clear & Accessible Leave Policies**  
- **Insight:** Easier leave access increases help-seeking.  
- **Action:** Simplify procedures and ensure psychological safety around taking time off.  
- **AI Opportunity:** Chatbots can explain policies, guide employees step-by-step, and help HR forecast leave demand.

3. **Expand & Communicate Care Options**  
- **Insight:** Availability of care options is a top predictor.  
- **Action:** Increase access to counseling, EAPs, and digital therapy tools; make them easy to find.  
- **AI Opportunity:** Intelligent recommendations can match employees to the right resources anonymously.

4. **Enhance Psychological Safety**  
- **Insight:** Patterns in help-seeking vary by gender and culture, indicating opportunities to tailor mental health programs to different employee needs.  
- **Action:** Build inclusive messaging and encourage leadership to model vulnerability.  
- **AI Opportunity:** Language analysis can detect stigmatizing patterns, and AI-supported training can improve manager responsiveness and empathy.

**Overall:** Combining policy improvements, empathetic leadership, and responsible AI creates a supportive, ethical, and human-centered mental health ecosystem.

## Conclusion
This project shows that personal history, workplace culture, and access to support collectively shape whether tech employees seek mental health treatment. Clear patterns from both exploration and modeling highlight the value of psychological safety, early intervention, and readily accessible resources. Logistic Regression provided strong, interpretable insights, making it ideal for translating findings into actionable workplace strategies. Ultimately, these results underscore the importance of empathy-driven policies and the potential for responsible, human-centered digital tools to enhance employee wellbeing at scale.