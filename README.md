# ⚖️ LegalEase — AI-Powered Legal Document Generator

LegalEase is a Streamlit-based web application that helps users generate, customize, analyze, and export legal documents.

The application provides standard legal templates, an AI-powered custom contract drafter, contract risk auditing, and plain-English explanations of legal text.

> ⚠️ **Disclaimer:** LegalEase provides drafting assistance and educational tools. It does not constitute formal legal advice or create an attorney-client relationship. Generated documents should be reviewed by a qualified legal professional before use.

---


---

## 📌 Project Overview

LegalEase is designed to make basic legal-document drafting and understanding easier through a simple web interface.

Users can:

- Select predefined legal document templates
- Customize document information
- Generate custom legal agreements
- Use Gemini AI for advanced document generation
- Audit contracts for potential risks
- Convert complex legal language into plain English
- Edit generated documents
- Download documents in multiple formats

---

## ✨ Features

### 📝 Standard Legal Templates

The application includes predefined templates such as:

- Non-Disclosure Agreement (NDA)
- Independent Contractor Services Agreement
- Employment Offer Letter / Agreement
- Residential Lease Agreement

Users can enter their information and generate a customized document.

### 🤖 AI Custom Contract Drafter

Users can describe their contract requirements and generate a customized legal document.

The AI drafting system can consider:

- Contract type
- Governing jurisdiction
- Confidentiality
- Intellectual property
- Liability and indemnification
- Dispute resolution
- Other user-defined requirements

The application supports Google Gemini AI when an API key is provided.

### 🔍 Contract Risk Auditor

Users can paste a legal contract and analyze it for potential issues such as:

- Missing indemnification
- Missing governing jurisdiction
- Missing severability provisions
- Missing termination provisions
- Other potential contract vulnerabilities

The application also includes an offline rule-based fallback when Gemini AI is unavailable.

### 📖 Plain English Explainer

Legal text can be converted into easier-to-understand language.

The explanation focuses on areas such as:

- Executive summary
- Obligations
- Deadlines
- Payments
- Termination
- Important considerations

### ✨ AI Document Refinement

Users can provide an instruction to modify an existing document.

run :streamlit run app.py2.txt

```text
Add a confidentiality clause.
