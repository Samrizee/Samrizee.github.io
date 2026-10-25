# Hi, I'm Samrawit Zerfu Assefa 👋

I'm a **computational data scientist and digital health researcher** moving into **AI safety research**. I build machine learning systems for public health, where predictions feed real decisions, data are incomplete, and a model that fails quietly can do real harm. That experience is why I care about how AI systems are evaluated, how they fail, and whether we can trust them.

I'm looking for mentored research opportunities in AI safety, particularly in **evaluating AI behaviour**, **reliability and robustness**, and **making AI work dependably in low-resource, multilingual, high-stakes settings**.

- 🤖 **AI safety focus:** Evaluation of AI behaviour, reliability and robustness, behaviour under distribution shift, multilingual and low-resource settings, and multi-agent interactions.
- 🔬 **Research background:** Infectious disease modelling, machine learning, epidemic early warning, and climate-sensitive disease prediction.
- 🌍 **Current research:** Climate-informed malaria prediction and cholera early warning with EDAM.
- 🎓 **Education:** MSc in Computational Data Science, Addis Ababa University; BSc in Health Informatics, University of Gondar.
- 💻 **Technical focus:** Python, machine learning, evaluation and validation, retrieval-augmented generation, health data engineering.
- 📬 **Open to:** Mentored AI safety research, research fellowships, and collaboration. [Get in touch](#-connect-with-me).

---

## 🧭 Why AI safety

Early-warning systems are a hard test of whether a model deserves trust. The data arrive late, reporting is uneven, the climate shifts under the model, and the people acting on the output cannot inspect it. In that setting, the useful questions are not only "how accurate is it?" but also:

- How does it behave when the data stop looking like the training data?
- Does it know what it doesn't know, and say so?
- Are the claims made about it supported by the evidence?
- Who can check it, and who is accountable when it is wrong?

Those are AI safety questions as much as public health ones. I want to apply the habits I've built working on high-stakes prediction (careful validation, honest reporting of limits, and attention to data quality) to the problem of making advanced AI systems reliable and well understood.

### Questions I want to work on

*These are research directions I'm exploring, not published results.*

1. **Evaluating behaviour under shift and poor data.** What can early-warning practice, such as out-of-distribution testing, uncertainty and calibration, and monitoring after deployment, teach us about evaluating AI systems?
2. **Reliability beyond English.** Do the safety behaviours and evaluations built for major languages hold up in Amharic and other African languages, with voice and retrieval-based systems?
3. **Honest evaluation and reporting.** How do we separate what a system is designed to do from what has actually been demonstrated, and make that distinction easy for decision-makers to see?
4. **Oversight of AI in high-stakes decisions.** What human-in-the-loop and verification mechanisms are needed when AI informs health and public-sector decisions in resource-constrained settings?
5. **Multi-agent systems.** How do interacting AI agents behave, and how do we evaluate failures that only appear in interaction?

---

## 🔬 Research & Selected Projects

### 🤖 1. AI Systems, Evaluation & Language Technology

#### [AI Learning Companion](https://github.com/Samrizee/AI-learning-companion)

A project exploring a voice-first, retrieval-augmented learning companion designed to make educational content more accessible in African languages.

- **Research and development focus:** Retrieval-augmented generation (RAG), multilingual educational content, and speech-based interaction.
- **Technical areas:** Python, information retrieval, language processing, and speech technologies.
- **Objective:** Explore how AI-enabled educational tools can improve access to learning resources in local languages.
- **Relevance to AI safety:** A deployed system that answers questions in low-resource languages raises direct questions about grounding, hallucination, and whether evaluation methods transfer across languages.

#### [CreditTrust RAG](https://github.com/Samrizee/credittrust-RAG)

A retrieval-augmented generation project in a financial setting, where answers need to be traceable to source material.

- **Relevance to AI safety:** Grounding outputs in retrievable evidence is a practical route to making model behaviour checkable.

#### Sentiment Analysis Projects

- [Sentiment Analysis](https://github.com/Samrizee/sentiment-analysis)
- [Financial News Sentiment Analysis](https://github.com/Samrizee/financial-news-sentiment-analysis)

Projects exploring natural language processing and sentiment analysis using textual data.

- **Technical areas:** Python, pandas, Jupyter Notebook, and NLP.
- **Focus:** Text processing, sentiment classification, and extracting useful signals from unstructured data.

### 🌍 2. Prediction Under Uncertainty: Infectious Disease Early Warning

#### [VECTRI–ML Malaria Prediction](https://github.com/Samrizee/vectri-ml-malaria)

A research project investigating a hybrid approach to climate-driven malaria prediction in the northwestern Ethiopian highlands by combining mechanistic epidemiological modelling, climate and environmental data, and machine learning.

- **Research question:** Can integrating mechanistic model outputs with machine learning improve malaria risk prediction?
- **Research focus:** Climate-sensitive malaria prediction, spatial risk assessment, and epidemic early warning.
- **Methods and tools:** Python, VECTRI, scikit-learn, climate data processing, and predictive modelling.
- **Long-term objective:** Support evidence-informed malaria surveillance and early-warning decisions in Ethiopia.
- **Relevance to AI safety:** Combining a mechanistic model with ML is a way of constraining a learned system with domain knowledge, and it forces careful thinking about validation and failure modes.

*Project status:* See the repository for the current implementation, completed analyses, and remaining modelling and validation work. Research objectives should not be interpreted as demonstrated model performance.

#### EDAM — Climate-Informed Cholera Early Warning

Working with the Ethiopian Data Analytics Consortium (EDAM), in collaboration with Imperial College London, on a cholera early-warning use case combining climate and epidemiological surveillance data.

- **Research question:** Can climate and surveillance indicators help predict cholera outbreaks in advance?
- **Research focus:** Climate-informed outbreak prediction, epidemiological surveillance, and data-driven early warning.
- **Methods:** Climate and surveillance data integration, exploratory analysis, and predictive modelling.
- **Motivation:** Investigate approaches that could support earlier public health preparedness and response.

### 🏥 3. Digital Health & Health Data Interoperability

#### [EMR-to-DHIS2](https://github.com/Samrizee/EMR-to-DHIS2)

A health informatics project focused on integrating electronic medical record data with DHIS2 to support structured health information exchange and reporting.

- **Technical focus:** Data extraction, transformation, standardisation, and integration.
- **Methods and tools:** Python, APIs, and health data interoperability concepts.
- **Objective:** Explore ways to reduce manual data transfer and improve the flow of information between health information systems.

#### Digital Health Implementations — University of Gondar, CDHI

Worked on digital health implementation and development projects involving electronic medical records, DHIS2, health data collection, and digital health workflows.

Areas of experience included:

- Bahmni/OpenMRS implementation and configuration.
- DHIS2 Tracker and Aggregate systems.
- Integration of data collection workflows with DHIS2.
- WHO Digital Adaptation Kits for antenatal care and family planning.
- REDCap, health data quality, and digital health training.

Working inside real health systems has given me first-hand context for how technology is adopted, trusted, and sometimes misused in practice, which is relevant to AI deployment and governance.

### 📊 4. Data Engineering & Risk Modelling

Additional projects explore data collection, processing, API development, and predictive analytics:

- [Telegram Data Pipeline](https://github.com/Samrizee/telegram-data-pipeline)
- [Telegram Analytical API](https://github.com/Samrizee/Telegram_Analytical_API)
- [Amharic E-commerce Data Extractor](https://github.com/Samrizee/Amharic-E-commerce-Data-Extractor)
- [Credit Risk Model](https://github.com/Samrizee/credit-risk-model)
- [Insurance Risk Analytics & Predictive Modelling](https://github.com/Samrizee/End-to-End-Insurance-Risk-Analytics-Predictive-Modeling)
- [Fraud Detection — E-commerce and Bank Transactions](https://github.com/Samrizee/fraud-cases-for-e-commerce-and-bank-transactions)

These projects cover data processing, machine learning, text analysis, risk assessment, and analytical application development, including models where the cost of errors is uneven and evaluation choices matter.

---

## 🛠️ Technical Skills

### Programming & Data Science
- Python, pandas, NumPy, scikit-learn, and statistical analysis.
- Data cleaning, exploratory data analysis, feature engineering, and model evaluation.
- SQL, PostgreSQL, and MySQL.
- Jupyter Notebook, Git, GitHub, Linux, and Bash.

### AI & NLP
- Retrieval-augmented generation and information retrieval.
- Natural language processing and sentiment classification.
- Multilingual and speech-based applications, including African-language contexts.

### Computational & Epidemiological Modelling
- Machine learning for disease prediction.
- Climate and epidemiological data integration.
- Mechanistic model and machine learning integration.
- Spatial and temporal disease-risk analysis.
- Predictive modelling, validation, and model evaluation.

### Digital Health & Interoperability
- DHIS2 Tracker and Aggregate.
- Bahmni and OpenMRS.
- HL7 FHIR fundamentals.
- REDCap and digital health workflows.
- Health data integration, standardisation, and reporting.

### Data Visualisation & Applications
- Power BI, Plotly, and Streamlit.
- Data dashboards and analytical applications.
- Data processing pipelines and API integration.

### AI Safety Interests
- Evaluation of AI behaviour.
- Reliability and robustness of AI systems.
- Computational approaches to understanding AI systems.
- Multi-agent AI systems and interactions.
- Multilingual and low-resource settings.
- AI in high-stakes public-sector and health decisions.

*I'm early in my AI safety work. These are active research interests, not claims of established AI safety research experience.*

---

## 📫 Connect With Me

If you work on AI safety, evaluation, or AI for public health and would like to talk, I'd be glad to hear from you.

- 💼 **LinkedIn:** [Samrawit Zerfu Assefa](https://www.linkedin.com/in/samrawit-zerfu-assefa-3a8478151/)
- 💻 **GitHub:** [@Samrizee](https://github.com/Samrizee)
- 📧 **Email:** [Samrawitzerfu@gmail.com](mailto:Samrawitzerfu@gmail.com)
