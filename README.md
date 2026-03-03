🏥 HealthSaathi

HealthSaathi is an open-source web platform that helps patients identify the most suitable healthcare facility based on clinic wait times, hospital bed availability, and preferred doctor selection. The platform aims to reduce delays in accessing medical care by providing structured and transparent healthcare availability information in one place.

📌 Problem Statement

In many tier-2 and tier-3 cities, patients lack centralized and reliable access to information about clinic waiting times, hospital bed availability, and doctor presence. This often forces individuals to visit multiple healthcare facilities before receiving treatment, leading to unnecessary delays, increased stress, and potential health risks—especially in urgent situations. A transparent and accessible system is needed to consolidate healthcare availability data and support timely decision-making.

💡 Solution Overview

HealthSaathi provides a web-based interface where users can input:

1.Location

2.Condition severity (Normal / Urgent)

3.Preferred doctor (optional)

Based on these inputs, the system evaluates:

1.Clinic wait times

2.Hospital bed availability

3.Doctor availability

It then generates an intelligent and explainable recommendation to guide patients toward the fastest and most appropriate care option.

🚀 Key Features

1.Clinic wait time monitoring

2.Hospital bed availability tracking 

3.Preferred doctor selection and availability check

4.Severity-based recommendation engine

5.Transparent explanation for each recommendation

🏗 Technical Architecture

Frontend: React (Vite) + CSS
Backend: FastAPI
Database: SQLite
API Communication: RESTful APIs

System Flow

User Input → Frontend Form → Backend API → Database Query → Recommendation Logic → Structured Response

The recommendation logic uses rule-based filtering to prioritize healthcare facilities based on urgency, availability, and user preference.

🔓 Open Source Commitment

1.HealthSaathi is fully open-source and licensed under the MIT License.

2.Built entirely using open-source technologies

3.No dependency on proprietary APIs

4.Modular and extensible design

5.Open to community contributions

The goal is to create a scalable and adaptable healthcare availability system that can be customized for local deployment.

🔮 Future Improvements

1.Real-time healthcare data integration

2.Map-based visualization

3.Role-based hospital/admin dashboard

4.Regional scalability and customization

📄 License

This project is licensed under the MIT License.
