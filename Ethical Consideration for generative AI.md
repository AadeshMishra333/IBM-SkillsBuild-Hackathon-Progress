# Section 0: About

### Learning Outcomes
* Learn about ethics and how they are related to AI.
* Understand the core pillars of **Transparency**, **Accountability**, and **Fairness**.

---

# Section 1: What is AI Ethics?

**Ethics** is a set of moral principles that help people discern between right and wrong. 

**AI Ethics** is a multidisciplinary field that examines how to maximize the beneficial impact of AI while minimizing risks and adverse outcomes.

---

### IBM's Core Principles of Trust & Transparency
1. **Augment Human Intelligence:** The purpose of AI is to support humans, not replace them.
2. **Data & Insight Ownership:** Clients own their data and the insights derived from it.
3. **Transparent & Explainable AI:** Companies must be clear about who trains their AI systems, what training data was used, and what factors influenced algorithmic recommendations.

> **Pillars of Trustworthy AI:** *(Covered in detail in Module 1)*

---

### Core Ethical Pillars: Transparency, Accountability, and Fairness

* **Transparency:** Enables users to understand how AI works and trust its outputs.
* **Accountability:** Ensures individuals and organizations take responsibility for the outcomes of their AI systems.
* **Fairness:** Prevents bias from distorting results and ensures equal treatment.

#### 1. Building with Transparency
Transparency helps people access information to better understand how an AI system was created and how it makes decisions. People tend to trust what they understand.

**High-Stakes Applications:**
* **Healthcare:** Disease detection, segmentation, diagnosis, and treatment planning.
* **Finance:** Stock market prediction and investment guidance.
* **Human Resources:** Candidate recruitment and hiring workflows.

> **Example — Transparent AI Healthcare Tool:**  
> Doctors use a generative AI tool to recommend patient treatment plans. Each recommendation highlights specific symptoms and historical factors that influenced the decision, allowing doctors and patients to verify and trust the treatment plan.

#### 2. Taking Responsibility with Accountability
Accountability means developers and organizations take responsibility for AI outputs, including unintended negative consequences.

**Risks of Unaccountable AI:**
* **Toxic Output:** Generation of abusive, hate-filled, or obscene content.
* **Erosion of Human Agency:** Proliferation of believable yet false or misleading information.
* **Data Leakage:** Unintentional disclosure of confidential training data.

> **Example — Chatbot Monitoring:**  
> A company deploying an AI customer service chatbot establishes regular monitoring processes. The deployment team actively adjusts or retrains the model if user feedback indicates unhelpful, inaccurate, or biased responses.

#### 3. Promoting Fairness and Equal Treatment
Fair AI tools are engineered to minimize bias and promote inclusive, representative outcomes.

**Types of AI Bias:**
* **Data Bias:** Training models on skewed or unrepresentative datasets.
* **Decision Bias:** Systematically giving an unfair advantage to specific ideas or outcomes.
* **Output Bias:** Generating content that suppresses or misrepresents certain groups.

> **Example — Fair HR Tool:**  
> An AI recruiting tool evaluates candidates strictly on job-relevant criteria (skills and experience) while excluding demographic variables like age, gender, or ethnicity to ensure unbiased evaluation.

---

### Activity
* **3 Ethical Pillars in Generative AI:** Match the scenarios to the corresponding ethical pillar (*Transparency*, *Accountability*, or *Fairness*).

---

# Section 2: Data Privacy, Confidentiality & Usage Rights

**Data Privacy and Confidentiality** ensures that personal or sensitive information in AI training datasets is protected and anonymized. Sensitive data fed into public AI models can become part of the training set, leading to potential loss of organizational control over confidential data.

### Best Practices for Data Protection
* **Security Standards:** Implement robust cybersecurity controls to prevent data and metadata leakage.
* **Narrow Domain Protection:** Apply strict access rules and isolated environments for highly sensitive domain data.
* **Data Minimization:** Limit training data collection strictly to what is legally permissible and necessary.

---

### Promoting Fairness & Transparency in Data Sources
Neglecting data quality leads to biased or discriminatory AI behavior.
* **Data Fairness:** Select diverse, balanced, and representative datasets.
* **Data Transparency:** Ensure data sources are documented, verified, and traceable.

#### Operational Strategies
* **Diverse Data Collection:** Gather data representative of varied populations.
* **Comprehensive Documentation:** Log data cleaning, modifications, and generation methods to enable risk assessment.
* **Inclusive Development Teams:** Build diverse teams (across culture, gender, socio-economic background, and job roles) to better identify blind spots and biases.
* **Continuous Real-World Testing:** Monitor model performance against live operational data continuously.

> **Real-World Pitfall Examples:**  
> 1. An HR screening tool penalizing female applicants due to historical hiring bias in training data.  
> 2. An AI system spreading misinformation because it was trained on unverified web sources.

---

### Complying with Data Usage Rights
Organizations must respect intellectual property (IP), licensing terms, and copyright restrictions when sourcing training data.

**Compliance Checklist:**
* Check relevant local and international data laws.
* Avoid training on or exposing proprietary Intellectual Property without authorization.
* Continually audit model outputs for potential IP infringement.

> **Example:** A company auditing its training pipeline to clear copyrighted training material before commercial model deployment.

---

### Activity
* **Ethical Considerations & Data Inputs:** Identify risks associated with data inputs in AI workflows.

---

# Section 4: Preventing Harmful & Inaccurate Content

* **Harmful Content:** Generated text, audio, images, or video that is offensive, toxic, or causes distress.
* **Inaccurate Content:** Model "hallucinations" where incorrect or fabricated information is presented as fact.

---

### Mitigation Strategies
* **Content Filtering:** Implement automated guardrails to filter out offensive or unsafe outputs.
* **Scope Definition:** Define narrow operational parameters to reduce hallucination rates.
* **Prompt Templates:** Enforce structured formats to constrain outputs within safe bounds.
* **Response Capping:** Limit output lengths to minimize context drift and ungrounded generation.
* **Continuous Human-in-the-Loop (HITL):** Perform regular human inspections and continuous model fine-tuning.

> **Examples of Output Failures:**  
> 1. A customer service chatbot responding with offensive language when prompted with edge-case inputs.  
> 2. An unmonitored automated news generator publishing hallucinated, unverified articles as factual news.

---

### Managing Output Bias & Respecting IP
* Design pipelines with inclusive principles from inception.
* Preprocess data mindfully to strip out systematic historical biases.
* Validate generated artifacts to ensure they do not replicate copyrighted works or reveal private individual data.

---

### Activity
* **Managing AI Content:** Explain the ethical implications of managing and moderating AI-generated outputs.

---

# Hackathon Tool Reference: IBM AI Risk Atlas

The [IBM AI Risk Atlas](https://www.ibm.com/docs/en/watsonx/saas?topic=ai-risk-atlas) is an interactive repository designed to help developers, researchers, and enterprise teams understand and mitigate risks associated with generative AI, foundation models, and traditional machine learning models.

### Risk Classification Framework

| Risk Category | Description |
| :--- | :--- |
| **Traditional Risks** | General risks inherent to standard machine learning and statistical models (e.g., standard data drift, basic overfitting). |
| **Amplified Risks** | Classic AI risks that become significantly magnified in scale or speed when applied to Generative AI and Large Language Models. |
| **Specific Risks** | Novel risk vectors unique to Generative AI architectures (e.g., prompt injection, training data extraction, hallucination propagation). |

> 🔗 **Resource Link:** Access the documentation directly at the [IBM AI Risk Atlas](https://www.ibm.com/docs/en/watsonx/saas?topic=ai-risk-atlas).

#### Key Takeaway
The Risk Atlas provides technical and non-technical guidance, risk taxonomy, and mitigation strategies covering transparency, accountability, and fairness across every phase of model development, deployment, and user outreach.
