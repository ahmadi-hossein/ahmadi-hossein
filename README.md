# Hossein Ahmadi

**Senior Machine Learning Engineer | LLM & RAG Systems | Causal Inference, MLOps & Medical AI**

Tehran, Iran | [LinkedIn](https://www.linkedin.com/in/hossein-ahmadii) | [Kaggle](https://www.kaggle.com/ahmadihossein) | eng.hosseinahmadi2@gmail.com

## About

Senior Machine Learning Engineer at Melal Bank since June 2022, and the bank's first ML hire. I founded the ML function there and set its architecture, tooling and delivery standards. My work covers Clinical NLP and LLM/RAG systems over health records, a distributed ML training platform, drift-aware MLOps, and medical imaging.

My research interest is evaluation validity in medical AI: how duplicate leakage and acquisition bias quietly inflate published results, and how to audit a dataset before trusting its numbers.

## Featured work

**[leakage-audit](https://github.com/ahmadi-hossein/leakage-audit)** - Open-source tool that audits image classification datasets in two stages: exact and near-duplicate clustering (MD5 + perceptual hashing), then an acquisition-bias probe that trains a model on crude image statistics only. It also builds leakage-free, cluster-aware train/val/test splits.
Live web app: [leakage-audit.streamlit.app](https://leakage-audit.streamlit.app/)
Built from a real audit of a public ultrasound kidney-stone dataset (9,416 images): 85.8% of a random split's test images had a duplicate in training, accuracy on a leakage-free split was 99.72%, and the bias probe reached 84.8% from image statistics alone.

**Kidney Stone Detection from Ultrasound Images** - Custom PyTorch CNN on 9,416 ultrasound images, with a duplicate-leakage audit and a leakage-free evaluation protocol. [Kaggle notebook](https://www.kaggle.com/code/ahmadihossein/kidney-stone-detection)

**[CausalSepsis-DI](https://github.com/ahmadi-hossein/CausalSepsis-DI)** - Causal inference applied to sepsis care: estimating treatment effects from observational clinical data (personal research project, also on Kaggle as CausalSepsis-DI v2).

**[Medical-Insurance](https://github.com/ahmadi-hossein/Medical-Insurance)** - Medical insurance cost prediction with careful feature engineering and model comparison.

**[EcoOpt](https://github.com/ahmadi-hossein/EcoOpt)** - Energy and carbon optimisation study; the Kaggle notebook earned a gold medal.

**Real-Time Data Drift Detection** - A tool that detects when production data drifts away from training data, making a common cause of silent model failure visible and actionable.

## Publications

- **Perfect Accuracy, Imperfect Evidence: A Duplicate-Leakage and Acquisition-Bias Audit of Ultrasound Kidney-Stone Detection** - Submitted paper (under review), 3rd International Interdisciplinary Conference on Artificial Intelligence (IICAI2027), Shahid Beheshti University, Tehran, Iran, May 2027. Paper ID 1004.
- **Data-Driven Behavioral Economics: A Theoretical Modeling of the Impact of Algorithmic Bias on Strategic Decision-Making of Managers in Open Innovation Ecosystems** - Accepted paper, 1st International Conference on Artificial Intelligence and Interdisciplinary Innovations in Science and Technology, Paris, France, July 2026 (proceedings, article code 612589).

## Core skills

- **ML & AI:** Machine Learning, Deep Learning, NLP, Computer Vision, Medical Imaging, LLM / RAG systems, AI agents, Causal Inference
- **Data & Statistics:** Statistical Inference, Time-Series Forecasting, Feature Engineering, Model Tuning & Optimisation, Bias Evaluation, Supervised & Unsupervised Learning
- **Engineering:** Python, SQL, PyTorch, scikit-learn, FastAPI, pipelines, web scraping
- **Production & MLOps:** MLOps & drift monitoring, Docker, CI/CD, distributed ML training, end-to-end ML pipelines

## Certifications & highlights

- **Machine Learning, TestDome Gold Certificate** - ranked in the top 10% of candidates (Nov 2026). [Verify](https://www.testdome.com/certificates/c25d62b3517344619a47d76263974b29)
- **AI for Medicine Specialization**, DeepLearning.AI (2025): Medical Diagnosis, Medical Prognosis, Medical Treatment
- **Kaggle Notebooks Master** - 20 public notebooks, 3 gold, 11 silver and 3 bronze medals
- **Member**, National AI Association of Iran

## Education

**Bachelor's in Software Engineering** - Miyaneh Technical and Vocational College for Boys (2019 - 2022)
GPA 3.97 / 4.00, top student in the field for all semesters.

## Languages

Persian (native), Azerbaijani (native), English (professional), Turkish, Tajik, Norwegian (limited working)

## Contact

- LinkedIn: [linkedin.com/in/hossein-ahmadii](https://www.linkedin.com/in/hossein-ahmadii)
- Kaggle: [kaggle.com/ahmadihossein](https://www.kaggle.com/ahmadihossein)
- Email: eng.hosseinahmadi2@gmail.com
