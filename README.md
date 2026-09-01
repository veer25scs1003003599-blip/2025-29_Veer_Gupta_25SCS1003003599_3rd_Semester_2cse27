# 🌐 NetSage AI — AI-Assisted Network Troubleshooting & Diagnostic System

> **Cisco Virtual Internship Project | May 2026 – July 2026**

NetSage AI is an AI-assisted network troubleshooting and diagnostic system developed as an individual project during my **Cisco Virtual Internship**. The system is designed for Cisco-style Packet Tracer and laboratory network scenarios.

It takes network troubleshooting evidence such as symptoms, topology information, and `show` command output, and uses **Google's Gemini AI** to propose a probable root cause and the next diagnostic step.

The system keeps a **human reviewer in the loop** before any diagnosis or recommended fix is accepted.

> **A decision-support tool for troubleshooting — not an autonomous network configuration system.**

---

## 👨‍🎓 Student & Internship Details

| Details                 | Information                             |
| ----------------------- | --------------------------------------- |
| **Student Name**        | Veer Gupta                              |
| **Roll Number**         | 25SCS1003003599                         |
| **Programme**           | B.Tech — Computer Science & Engineering |
| **Semester**            | 3rd Semester                            |
| **Section**             | 2CSE27                                  |
| **University**          | IILM University, Greater Noida          |
| **Organization**        | Cisco                                   |
| **Internship Name**     | Cisco Virtual Internship                |
| **Internship Duration** | 15 May 2026 – 15 July 2026              |
| **Duration**            | 2 Months / 8 Weeks                      |
| **Mode**                | Online                                  |
| **Project**             | NetSage AI                              |
| **Project Type**        | Individual                              |
| **Mentor**              | Swati Vashishth                         |

---

# 📌 About the Internship

The **Cisco Virtual Internship** provided practical exposure to networking, artificial intelligence, data analytics, and technology-oriented problem solving.

During the internship, I worked on learning activities and project development involving network troubleshooting concepts, AI-assisted diagnosis, data analysis, and responsible use of artificial intelligence.

The internship also involved completing learning modules and earning certificates and badges in areas related to **AI and Data Analytics**.

The primary project developed as part of the internship was **NetSage AI**, an AI-assisted network troubleshooting and diagnostic system.

---

# 📌 Problem Statement

Students and junior network engineers can often run the right networking commands but struggle to connect a *symptom* to its underlying *cause*.

A single connectivity issue could stem from:

* VLAN misconfiguration
* Gateway mismatch
* DHCP failure
* Routing problems
* DNS issues
* ACL rules
* NAT misconfiguration
* Downed network interfaces
* Wireless configuration issues

NetSage AI addresses the following question:

> *How can an AI-powered system take in network troubleshooting evidence, recommend a probable cause and next step, while still keeping a human in the loop to review and accept the diagnosis?*

---

# ✨ Features

### 🔍 Case-Based Troubleshooting Desk

Users can select predefined networking problems such as:

`CASE-001 — PC1 cannot ping PC2`

Each case can contain:

* Network symptom
* Network topology
* Raw `show` command output
* Expected fault
* Troubleshooting evidence

### 🤖 AI-Powered Diagnosis

The system uses the **Gemini API** to analyze the supplied evidence and return:

* Root cause explanation
* Confidence level
* Relevant OSI layer
* Supporting evidence line
* Recommended next diagnostic command
* Step-by-step fix instructions

### 👤 Human-in-the-Loop Review

Every AI diagnosis requires explicit human review before being treated as confirmed.

The reviewer can:

* **Accept** the diagnosis
* **Edit** the diagnosis
* **Reject** the diagnosis

Corrections and rejections can also include a reason and corrected root cause.

### 📊 Responsible AI Analytics Dashboard

The dashboard tracks system performance and human oversight through:

* Total cases reviewed
* AI-accepted cases
* AI–human agreement rate
* Category-wise breakdown
* Severity-wise breakdown
* Decision breakdown
* Review history
* Responsible AI corrections log

### 🗂️ Troubleshooting Dataset

The project includes a **30-case troubleshooting dataset** covering common network faults and scenarios.

---

# 🏗️ System Workflow

```text
Network Evidence
       ↓
AI Diagnostic Engine (Gemini)
       ↓
Root Cause + Confidence + Evidence
+ Next Command + Fix Steps
       ↓
Human Review Panel
       ↓
┌────────────┬───────────┬─────────────┐
│   Accept   │   Edit    │   Reject    │
└────────────┴───────────┴─────────────┘
       ↓
Review History &
Responsible AI Corrections Log
```

### Workflow Steps

**1. Evidence Collection**

The user selects a case or provides troubleshooting evidence such as a symptom, topology information, and command output.

**2. AI Diagnosis**

The Gemini-powered diagnostic engine analyzes the evidence and proposes:

* Probable root cause
* Confidence level
* OSI layer
* Supporting evidence
* Next diagnostic command
* Recommended fix steps

**3. Human Review**

The reviewer examines the AI-generated diagnosis and supporting evidence.

The diagnosis can then be accepted, edited, or rejected.

**4. Logging & Analytics**

Human decisions are recorded in the Review History and Responsible AI Corrections Log.

This information contributes to the analytics dashboard and helps evaluate AI performance against human judgment.

---

# 🛠️ Technology Stack

| Layer                      | Technology                                      |
| -------------------------- | ----------------------------------------------- |
| **Programming Language**   | Python                                          |
| **UI / Dashboard**         | Streamlit                                       |
| **AI / Diagnosis Engine**  | Google Generative AI (Gemini)                   |
| **Data Handling**          | pandas                                          |
| **Configuration**          | python-dotenv                                   |
| **Networking Environment** | Cisco Packet Tracer                             |
| **Network Concepts**       | VLAN, DHCP, DNS, Gateway/IP, NAT, ACL, Wireless |

---

# 📊 Dataset

A dataset of **30 network troubleshooting cases** was developed for the project.

The dataset covers categories including:

* ACL
* DHCP
* DNS
* Gateway/IP
* NAT
* VLAN
* Wireless

Each case includes information such as:

* Case ID
* Network symptom
* Troubleshooting evidence
* `show` command output
* Expected fault
* OSI layer
* Networking concept
* Severity
* Recommended diagnostic command/action

### Severity Levels

* 🔴 Critical
* 🟠 High
* 🟡 Medium
* 🟢 Low

---

# 🔒 Human-in-the-Loop Safety

NetSage AI is designed so that an AI-generated diagnosis is **not automatically treated as a confirmed network fault**.

The system presents:

* Supplied troubleshooting evidence
* AI candidate root cause
* Confidence level
* Supporting evidence
* Recommended diagnostic command
* Suggested fix steps

The human reviewer must review the diagnosis before it is treated as confirmed.

The reviewer can:

**Accept** — confirm the AI diagnosis.

**Edit** — provide a corrected diagnosis and reason.

**Reject** — reject the AI diagnosis and record a reason.

This approach helps maintain transparency, human oversight, and responsible use of AI.

---

# 📈 Responsible AI Analytics

The Analytics Dashboard evaluates AI performance against human judgment.

It tracks:

* **Total Cases Reviewed**
* **AI Accepted**
* **AI–Human Agreement Rate**
* Category-wise performance
* Severity-wise distribution
* Decision breakdown by category
* Review History
* Responsible AI Corrections Log

The Responsible AI Corrections Log compares the original AI diagnosis with human corrections and the reasons behind those corrections.

This provides a mechanism for identifying areas where the AI may require improvement.

---

# 🎓 Internship Learning Outcomes

Through the Cisco Virtual Internship and NetSage AI project, I gained practical exposure to:

* Network troubleshooting concepts
* Cisco networking concepts
* Cisco Packet Tracer
* VLAN, DHCP, DNS, NAT and ACL concepts
* AI-assisted problem solving
* Generative AI
* Prompt-based AI interaction
* Human-in-the-loop AI systems
* Responsible AI concepts
* Python programming
* Streamlit application development
* Data handling using pandas
* Structured troubleshooting datasets
* AI evaluation using human feedback
* Technical documentation
* Project presentation and reporting

---

# 🏆 Certificates & Badges

As part of the internship learning activities, I completed the following certification/learning modules.

## 📜 Certificates

The certificates are available in the [`Certificates`](./Certificates/) folder.

### 1. Apply AI: Analyze Customer Reviews

[View Certificate](./Certificates/VeerGupta_IILM%20University_apply-ai-analyze-customer-reviews)

### 2. Data Analytics Essentials

[View Certificate](./Certificates/VeerGupta_IILM%20University_data-analytics-essentials)

### 3. Introduction to Modern AI

[View Certificate](./Certificates/VeerGupta_IILM%20University_Introduction_to_Modern_AI)

---

## 🎖️ Badges

The badges earned during the internship are available in the [`Badges`](./Badges/) folder.

### 1. Apply AI: Analyze Customer Reviews

[View Badge]([./Badges/apply-ai-analyze-customer-reviews](https://www.credly.com/badges/502630a6-db6f-4632-87c5-75a16b3a2049/public_url))

### 2. Data Analytics Essentials

[View Badge]([./Badges/data-analytics-essentials](https://www.credly.com/badges/53633192-c9a4-448d-bea9-8255c18517bf/public_url))

### 3. Introduction to Modern AI

[View Badge]([./Badges/introduction-to-modern-ai](https://www.credly.com/badges/923d706f-f901-404f-88d5-61eb2e198339/public_url))

---

# 📂 Repository Contents

| Item                     | Location        | Description                            |
| ------------------------ | --------------- | -------------------------------------- |
| 📄 **Internship Report** | Root directory  | Detailed internship report             |
| 📊 **Internship PPT**    | Root directory  | Internship and project presentation    |
| 📜 **Certificates**      | `Certificates/` | Three internship learning certificates |
| 🎖️ **Badges**           | `Badges/`       | Three earned learning badges           |
| 📖 **README**            | `README.md`     | Project and internship documentation   |

---

# 📁 Project Structure

The repository currently focuses on internship documentation and project documentation.

```text
2025-29_Veer_Gupta_25SCS1003003599_3rd_Semester_2cse27/
│
├── 📁 Badges/
│   ├── apply-ai-analyze-customer-reviews
│   ├── data-analytics-essentials
│   └── introduction-to-modern-ai
│
├── 📁 Certificates/
│   ├── VeerGupta_IILM University_apply-ai-analyze-customer-reviews
│   ├── VeerGupta_IILM University_data-analytics-essentials
│   └── VeerGupta_IILM University_Introduction_to_Modern_AI
│
├── 📄 Internship_Report.pdf
├── 📊 Internship_PPT.pptx
└── 📖 README.md
```

> **Note:** The NetSage AI source code is planned to be added to this repository separately.

---

# ⚙️ Project Setup

Once the NetSage AI source code is added to the repository, the project can be configured using the following general environment.

### 1. Clone the repository

```bash
git clone https://github.com/veer25scs1003003599-blip/2025-29_Veer_Gupta_25SCS1003003599_3rd_Semester_2cse27.git
cd 2025-29_Veer_Gupta_25SCS1003003599_3rd_Semester_2cse27
```

### 2. Create a virtual environment

```bash
python -m venv venv
```

On Windows:

```bash
venv\Scripts\activate
```

### 3. Install dependencies

Once the project source code and `requirements.txt` are added:

```bash
pip install -r requirements.txt
```

### 4. Configure Gemini API

The application requires a Gemini API key.

Example:

```text
GEMINI_API_KEY=your_gemini_api_key_here
```

> ⚠️ **Never upload your actual API key to GitHub.** Keep API keys inside a local `.env` file and exclude the file using `.gitignore`.

### 5. Run the application

Once the source code is added:

```bash
streamlit run app.py
```

---

# ⚠️ Limitations

* The current troubleshooting dataset contains 30 cases and is relatively small.
* Diagnosis quality depends on the quality and specificity of the Gemini model's output.
* The system assists with diagnosis but does not directly modify configurations on live network devices.
* The project is intended primarily for academic and educational network troubleshooting scenarios.
* More extensive testing would be required before deployment in production network environments.

---

# 🚀 Future Scope

Potential future improvements include:

* Expanding the troubleshooting dataset with real-world scenarios
* Increasing coverage across VLAN, gateway, DHCP, DNS, routing, ACL, NAT, and wireless issues
* Supporting multiple network vendors and device types
* Integrating real-time Cisco device command collection
* Incorporating network topology and configuration data
* Improving confidence estimation
* Improving uncertainty detection
* Adding richer analytics
* Adding historical troubleshooting session insights
* Extending the system toward proactive network fault detection
* Adding the complete NetSage AI source code and deployment documentation to the repository

---

# 👩‍💼 Internship Mentor

**Swati Vashishth**

Mentor — Cisco Virtual Internship

---

# 👤 Author

**Veer Gupta**

**Roll No:** 25SCS1003003599

**Programme:** B.Tech — Computer Science & Engineering

**Semester:** 3rd Semester

**Section:** 2CSE27

**University:** IILM University, Greater Noida

**GitHub:** [veer25scs1003003599-blip](https://github.com/veer25scs1003003599-blip)

---

# 🔗 GitHub Repository

The complete internship documentation is available on GitHub:

**[NetSage AI — Internship Repository](https://github.com/veer25scs1003003599-blip/2025-29_Veer_Gupta_25SCS1003003599_3rd_Semester_2cse27)**

---

# 📄 Academic Disclaimer

This project was developed for **academic and educational purposes** as part of the Cisco Virtual Internship.

NetSage AI is intended as an AI-assisted decision-support system for network troubleshooting scenarios. It should not be considered a replacement for qualified network administrators or engineers, and AI-generated recommendations should be reviewed by a human before being applied to real network environments.

---

## 📅 Internship Timeline

| Milestone               | Date         |
| ----------------------- | ------------ |
| **Internship Start**    | 15 May 2026  |
| **Internship Duration** | 8 Weeks      |
| **Internship End**      | 15 July 2026 |
| **Project**             | NetSage AI   |
| **Mode**                | Online       |
| **Project Type**        | Individual   |

