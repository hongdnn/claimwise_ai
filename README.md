Claimwise AI

🚀 Google Cloud BigQuery AI Hackathon Project

📌 Overview

Claimwise AI is an AI-powered Insurance Claim Assistant that leverages Google Cloud, BigQuery, and Cloud Storage to streamline the traditionally manual and time-consuming claim review process.

Insurance claim adjusters often need to:
	•	Review lengthy documents and case files
	•	Analyze photos of damages
	•	Cross-check information with third-party sources
	•	Estimate repair costs using rules and past cases

This manual process can be slow, inconsistent, and prone to missing fraud. Claimwise AI addresses these challenges by combining document summarization, case retrieval, and image-based fraud detection into a single intelligent assistant.

⸻

✨ Key Features
	•	Automated Claim Cost Estimation
	•	Uses BigQuery Vector Search on text embeddings (documents, past claims) to retrieve similar cases and estimate repair costs.
	•	Fraud Detection with Image Embeddings
	•	Uses BigQuery multimodal embeddings on claim photos stored in Cloud Storage to detect anomalies and identify potential fraud.
	•	Faster Claim Reviews
	•	Retrieval of similar claims accelerates decision-making.
	•	Consistency & Transparency
	•	Standardized AI-driven retrieval ensures more consistent claim handling.
	•	Improves transparency for customers and claim adjusters.

⸻

🛠️ Tech Stack
	•	Google Cloud Platform (GCP)
	•	BigQuery (Vector Search, Embeddings, SQL AI functions)
	•	Vertex AI (text + multimodal embedding models)
	•	Cloud Storage (image storage for claim photos)
	•	Python / Google Colab / BigQuery ML (for orchestration & testing)

⸻

📈 Impact
	•	Reduced claim cost estimation time
	•	Accelerated claim review speed
	•	Enhanced ability to identify claim fraud
	•	Improved consistency and fairness in claims processing