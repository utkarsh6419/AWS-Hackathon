
# Sampark AI

### AI for Bharat Hackathon – Team Techtonicc

## 🚀 Overview

**Sampark AI** is an AI-powered civic assistant designed to simplify access to government services, welfare schemes, and public information for citizens across India.

It acts as a single intelligent access point that understands a user’s life situation and provides personalized, step-by-step assistance instead of just listing scheme names or links.

---

## 🎯 Problem Statement

Citizens often struggle to:

* Find accurate information about government schemes
* Understand eligibility criteria
* Avoid scams and fake agents
* Navigate complex application processes
* Access services in local languages

Many underserved communities face barriers due to low digital literacy, language limitations, and lack of awareness.

---

## 💡 Our Solution

Sampark AI provides:

* Conversational interface (Chat + Voice)
* Multilingual support
* Eligibility-based scheme matching
* Guided application assistance
* Status tracking and reminders
* Scam detection and verified information
* Access via WhatsApp, Web, SMS, and Voice

It focuses on inclusion, trust, and real-world usability.

---

## 🏗️ Architecture Overview

Sampark AI follows a serverless, scalable architecture powered by AWS.

### Core Components:

* **AWS Bedrock** – Foundation models for natural language understanding
* **AWS Lambda** – Serverless backend logic
* **Amazon Polly** – Voice-based interaction
* **Amazon S3 (Encrypted)** – Secure storage
* **AWS KMS** – Encryption key management
* **Amazon CloudWatch** – Monitoring and logging

The system collects user information, checks eligibility, provides guided support, and tracks application progress.

---

## 🔄 Process Flow

1. User interacts via Chat / Voice / WhatsApp
2. User information collected (age, occupation, location, life event)
3. Eligibility matching using government datasets
4. Guided application assistance
5. Status tracking and reminders
6. Escalation to helpdesk (if required)

---

## 🌍 Societal Impact

* Reduces information gaps
* Empowers rural and underserved communities
* Minimizes reliance on middlemen
* Prevents scam exposure
* Improves transparency and trust
* Increases welfare scheme utilization

---

## 📄 Documentation

* `requirements.md` – Functional and non-functional requirements
* `design.md` – System design and architecture details
* Hackathon submission PDF included in the repository
