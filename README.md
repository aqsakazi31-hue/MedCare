# ⚕️ MedCare: Digital Patient Record System

> **Your Health. Your Data. In Your Pocket.**
> A Track 3 (Jan Jeevan) Hackathon Submission by Team Tech Titans.

## 📌 The Problem
In rural and informal Indian healthcare, patient histories are entirely paper-based. Handwritten prescriptions ("Parchas") are easily lost, leading to fragmented medical histories. When a patient switches doctors, the new physician lacks critical context regarding past diagnoses, prescribed dosages, and adverse drug reactions.

## 💡 Our Solution
MedCare is a dual-interface, Patient-Owned Digital Health Vault. It bridges the gap between chaotic paper records and modern healthcare analytics without forcing busy rural doctors to change their writing habits. 

### Core Features
*   **🤖 AI Parcha Digitization:** Patients upload photos of handwritten prescriptions. We utilize the **Gemini 1.5 Flash Vision API** to accurately extract the Doctor's Name, Diagnosis, and Medicines into structured JSON data.
*   **👤 Patient-Owned Vault:** Patients maintain complete control over their chronological medical history.
*   **📝 Subjective Patient Notes:** Patients can append personal feedback to AI-extracted records (e.g., *"This tablet caused severe nausea"*), providing critical context that is traditionally lost between visits.
*   **👨‍⚕️ SaaS Doctor Dashboard:** A clean, dense, professional desktop view where doctors can search a patient by Contact No. and instantly view their AI-structured history and subjective notes before prescribing new treatments.

## 🛠️ Tech Stack
*   **Frontend:** React, Tailwind CSS, Lucide React Icons
*   **AI / Backend Logic:** Google Gemini 1.5 Flash API (Multimodal Vision-to-Text extraction)
*   **Architecture:** Simulated global state for seamless Patient-to-Doctor data handoffs during the prototype phase.

## 🚀 How It Works (The User Flow)
1. **Patient Login:** Enters basic details and accesses their mobile-first vault.
2. **Scan & Extract:** Patient clicks "+ Add New Record" and uploads a prescription. The AI extracts the clinical data in seconds.
3. **Verify & Note:** Patient verifies the AI data, adds any personal side-effect notes, and saves it to the vault.
4. **Doctor Review:** The doctor logs into their desktop SaaS dashboard, searches the patient, and views a perfectly structured timeline of their medical history.
