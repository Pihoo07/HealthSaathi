🏥 HealthSaathi

HealthSaathi is an open-source web platform that helps patients identify the most suitable healthcare facility based on clinic wait times, hospital bed availability, and preferred doctor selection. The platform aims to reduce delays in accessing medical care by providing structured and transparent healthcare availability information in one place.

📌 Problem Statement

In many tier-2 and tier-3 cities, patients lack centralized and reliable access to information about clinic waiting times, hospital bed availability (including ICU beds), and doctor presence. This often forces individuals to visit multiple healthcare facilities before receiving treatment, leading to unnecessary delays, increased stress, and potential health risks—especially in urgent situations. A transparent and accessible system is needed to consolidate healthcare availability data and support timely decision-making.

💡 Solution Overview

HealthSaathi provides a web-based interface where users can input:

Location

Condition severity (Normal / Urgent)

Preferred doctor (optional)

Based on these inputs, the system evaluates:

Clinic wait times

Hospital bed availability

Doctor availability

It then generates an intelligent and explainable recommendation to guide patients toward the fastest and most appropriate care option.

🚀 Key Features

Clinic wait time monitoring

Hospital bed availability tracking (including ICU)

Preferred doctor selection and availability check

Severity-based recommendation engine

Transparent explanation for each recommendation

🏗 Technical Architecture

Frontend: React (Vite) + CSS
Backend: FastAPI
Database: SQLite
API Communication: RESTful APIs

System Flow

User Input → Frontend Form → Backend API → Database Query → Recommendation Logic → Structured Response

The recommendation logic uses rule-based filtering to prioritize healthcare facilities based on urgency, availability, and user preference.

🔓 Open Source Commitment

HealthSaathi is fully open-source and licensed under the MIT License.

Built entirely using open-source technologies

No dependency on proprietary APIs

Modular and extensible design

Open to community contributions

The goal is to create a scalable and adaptable healthcare availability system that can be customized for local deployment.
