ProofAI | Digital Trust Layer
Hosted Prototype: [ProofAI Cloud Run](https://proofai-api-1006424774825.us-central1.run.app)
Code Repository: [GitHub Repository](https://github.com/Abezux/proofai.git)
<img width="1920" height="921" alt="{8D622E06-B69B-49DE-BEA4-525113BF7A92}" src="https://github.com/user-attachments/assets/6721a67b-1da7-40d2-bc81-894efb3abacb" />

Overview

ProofAI is a digital trust layer designed to verify documents like contracts, invoices, and news clippings. Using AI, it performs a multimodal forensic audit to detect logical inconsistencies, metadata anomalies, and visual irregularities.

⚠️ Note: Currently, the application uses a free-tier API key, so the results displayed are mock responses. In production with a paid API key, ProofAI will provide real-time, accurate analysis.

Features

Document Upload: Supports PDF, JPG, and PNG formats.
Integrity Score: Visual ring showing trustworthiness (0–100).
Executive Summary: Concise text explaining detected issues.
Risk Flags: Highlights anomalies and potential risks.
Forensic Audit Log: Detailed log of all checks performed.
Multi-Document Analysis: Easily upload and analyze multiple files.

Tech Stack

Frontend: HTML, TailwindCSS, Font Awesome, JavaScript
Backend: Python, FastAPI, Google Gemini AI SDK
Deployment: Docker & Google Cloud Run

Future Work

Integrate paid Gemini API for real analysis.
Add support for multi-page PDFs and larger file sizes.
Enhance the audit log with AI-generated explanations.

License
MIT License – Open for hackathon submission and learning purposes.
