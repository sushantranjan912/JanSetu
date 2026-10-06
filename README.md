# 🇮🇳 JanSetu — Connecting Problems to Solutions

### A collaborative civic innovation platform connecting **Citizens → Universities → Government → Industries** to transform real-world societal challenges into actionable solutions.

<p align="center">

**SIH 2026 · Problem Statement: SIH26043**

</p>

<p align="center">
  <img src="https://img.shields.io/badge/Smart%20India%20Hackathon-2026-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Problem%20Statement-SIH26043-orange?style=for-the-badge" />
  <img src="https://img.shields.io/badge/React-Frontend-61DAFB?style=for-the-badge&logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/Node.js-Backend-339933?style=for-the-badge&logo=node.js&logoColor=white" />
  <img src="https://img.shields.io/badge/MongoDB-Database-47A248?style=for-the-badge&logo=mongodb&logoColor=white" />

</p>

---

## 🌍 What is JanSetu?

**JanSetu** is a digital platform designed to crowdsource societal challenges and facilitate collaborative problem-solving through **citizens, universities, government administration, and industries**.

Many real-world problems remain unresolved not because solutions don't exist, but because the **right problem, people, knowledge, resources, and organizations are not connected effectively.**

JanSetu bridges this gap.

> **Citizens identify the problem.  
> Universities develop the solution.  
> Industries provide expertise and resources.  
> Administration connects the ecosystem.**

The platform focuses on challenges across areas such as:

- 🎓 Education
- 🏥 Healthcare
- 🌾 Agriculture
- 💧 Water Management
- ♻️ Sanitation & Waste Management
- 🌱 Environment
- 🏘️ Rural Development
- ♿ Accessibility
- 🏗️ Urban Infrastructure
- 🏛️ Public Service Delivery

---

# 🎯 Problem Statement

### SIH26043

> **“A digital platform to crowdsource societal challenges and facilitate collaborative problem solving through universities and industry partnerships.”**

Traditional systems often suffer from:

- Problems being reported without proper follow-up
- Lack of structured collaboration between stakeholders
- Limited participation from universities and students
- Difficulty connecting solutions with relevant industries
- Lack of transparency in the problem-solving lifecycle
- Resources and expertise remaining disconnected from real societal needs

### 💡 JanSetu's Approach

Instead of treating a problem as a simple complaint, JanSetu transforms it into a **collaborative innovation workflow**.

```text
Citizen
   ↓
Submit Societal Problem
   ↓
Admin Validation
   ↓
Relevant University
   ↓
Student Innovation Team
   ↓
Solution Proposal
   ↓
AI-based Industry Matching
   ↓
Industry Collaboration
   ↓
Implementation / Impact
```

---

# 🚀 Key Features

## 👨‍👩‍👧 Citizen Portal

Citizens can submit real-world societal problems with supporting evidence.

### Features

- Submit new societal challenges
- Add detailed problem descriptions
- Upload images/videos/evidence
- Categorize problems
- Track submitted problems
- Provide location/contextual information
- Follow the progress of reported issues

---

## 🛡️ Admin Portal

The administration acts as the central coordination layer.

### Features

- Review submitted problems
- Validate or reject problems
- Categorize and prioritize challenges
- Assign validated problems to relevant universities
- Review university proposals
- View required resources
- Coordinate university-industry collaboration
- Manage platform stakeholders

---

## 🎓 University Portal

Universities convert societal problems into structured solution proposals.

### Workflow

```text
Problem Assigned
       ↓
University Lead / Professor
       ↓
Student Team Formation
       ↓
Research & Ideation
       ↓
Solution Proposal
       ↓
Resources + Funding + Requirements
```

Student teams can prepare proposals containing:

- Proposed solution
- Technical approach
- Required resources
- Raw materials
- Estimated funding
- Implementation requirements
- Expected impact

---

## 🏭 Industry Portal

Industries can contribute expertise, resources, funding, technology, and implementation support.

### Industry Collaboration

Industries can be connected based on:

- Domain expertise
- Required technologies
- Available resources
- Industry capabilities
- Solution requirements

This helps transform university ideas into **practical, implementable solutions**.

---

# 🤖 AI-Powered Industry Matching

One of JanSetu's key innovations is its intelligent matching mechanism.

Instead of manually searching for suitable organizations, JanSetu can analyze:

### Solution Requirements

```text
Required Technology
Required Materials
Domain
Skills
Funding
Implementation Needs
```

against:

### Industry Capabilities

```text
Expertise
Technology
Resources
Domain
Experience
Available Support
```

The system can then identify industries whose capabilities are most relevant to a particular solution.

### Conceptual Flow

```text
University Proposal
        │
        ▼
Requirement Extraction
        │
        ▼
Semantic Representation
        │
        ▼
Industry Capability Analysis
        │
        ▼
Similarity / Matching Model
        │
        ▼
Relevant Industries
```

### AI / ML Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- Sentence Transformers
- Semantic similarity / matching

---

# 🏗️ System Architecture

```text
                       ┌───────────────────┐
                       │     CITIZENS      │
                       │  Report Problems  │
                       └─────────┬─────────┘
                                 │
                                 ▼
                       ┌───────────────────┐
                       │   ADMIN PORTAL    │
                       │ Validate & Assign │
                       └─────────┬─────────┘
                                 │
                    ┌────────────┴────────────┐
                    ▼                         ▼
          ┌──────────────────┐      ┌──────────────────┐
          │ UNIVERSITY PORTAL│      │  ADMIN / SYSTEM  │
          │ Build Solutions  │      │  Coordination    │
          └────────┬─────────┘      └────────┬─────────┘
                   │                         │
                   │ Solution Proposal       │
                   └────────────┬────────────┘
                                ▼
                       ┌───────────────────┐
                       │    AI MATCHING    │
                       │ Industry Matching │
                       └─────────┬─────────┘
                                 │
                                 ▼
                       ┌───────────────────┐
                       │ INDUSTRY PORTAL   │
                       │ Expertise &       │
                       │ Resource Support  │
                       └─────────┬─────────┘
                                 │
                                 ▼
                       ┌───────────────────┐
                       │ IMPLEMENTATION &  │
                       │ SOCIAL IMPACT     │
                       └───────────────────┘
```

---

# 🧩 Core Workflow

### 1️⃣ Problem Identification

A citizen identifies a real societal challenge and submits it through JanSetu.

### 2️⃣ Problem Validation

The administration reviews the submission and validates the problem.

### 3️⃣ University Assignment

The validated challenge is assigned to a university based on relevance.

### 4️⃣ Student Team Formation

A professor/university lead forms a student team to research and solve the problem.

### 5️⃣ Solution Development

Students prepare a structured solution proposal.

### 6️⃣ Resource Identification

The platform captures funding, materials, technologies, expertise, and other requirements.

### 7️⃣ AI Matching

JanSetu identifies industries whose capabilities align with the proposed solution.

### 8️⃣ Industry Collaboration

Relevant industries can collaborate by providing:

- Technology
- Expertise
- Resources
- Funding
- Mentorship
- Implementation support

### 9️⃣ Impact

The ultimate goal is to move from:

> **Problem → Idea → Collaboration → Implementation → Impact**

---

# 🛠️ Tech Stack

## Frontend

| Technology | Purpose |
|---|---|
| React.js | User interfaces |
| JavaScript | Application logic |
| CSS | Styling & responsive UI |

## Backend

| Technology | Purpose |
|---|---|
| Node.js | Server runtime |
| Express.js | REST API framework |
| REST APIs | Frontend-backend communication |

## Database

| Technology | Purpose |
|---|---|
| MongoDB Atlas | Cloud database |
| Mongoose | MongoDB object modeling |

## Authentication & Security

| Technology | Purpose |
|---|---|
| JWT | Authentication |
| bcrypt | Password hashing |
| Role-Based Access Control | User authorization |

## AI / ML

| Technology | Purpose |
|---|---|
| Python | AI/ML development |
| Pandas | Data processing |
| NumPy | Numerical computation |
| Scikit-learn | Machine learning |
| Sentence Transformers | Semantic representation |
| Semantic Similarity | Industry matching |

---

# 👥 Role-Based Ecosystem

JanSetu follows a role-based architecture.

```text
                 JANSETU
                    │
       ┌────────────┼────────────┐
       │            │            │
       ▼            ▼            ▼
   CITIZEN        ADMIN      UNIVERSITY
                                  │
                                  ▼
                              STUDENTS
                                  │
                                  ▼
                              INDUSTRY
```

Each stakeholder has a dedicated workflow and responsibility.

This ensures that users only access the functionality relevant to their role.

---

# 🔐 Security

JanSetu incorporates authentication and authorization mechanisms including:

- JWT-based authentication
- Password hashing with bcrypt
- Role-based access control
- Protected routes
- Environment variables for sensitive configuration
- Backend API validation

> **Sensitive credentials should never be committed to the repository.**

---

# 📁 Project Structure

```text
JanSetu/
│
├── citizen/                 # Citizen-facing application
│
├── admin/                   # Administration portal
│
├── university/              # University portal
│
├── industries/              # Industry portal
│
├── backend/                 # Node.js + Express backend
│
├── ai/                      # AI/ML components
│
├── android/                 # Android-related source
│
├── others/
│   └── seeds/               # Database seed utilities
│
├── README.md
├── .gitignore
└── .env.example
```

---

# ⚙️ Getting Started

## Prerequisites

Make sure you have installed:

- Node.js
- npm
- MongoDB / MongoDB Atlas
- Git
- Python 3.x (for AI components)

---

## 1. Clone the Repository

```bash
git clone https://github.com/sushantranjan912/JanSetu.git

cd JanSetu
```

---

## 2. Configure Environment Variables

Create the required `.env` files using the provided `.env.example`.

Example:

```env
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
PORT=5000
```

⚠️ **Never commit `.env` files or database credentials to GitHub.**

---

## 3. Install Dependencies

Install dependencies for the required applications:

```bash
npm install
```

If individual modules contain their own `package.json`, install dependencies inside those directories as well.

---

## 4. Start the Backend

```bash
npm run dev
```

or:

```bash
npm start
```

---

## 5. Start the Frontend

Navigate to the required frontend directory and run:

```bash
npm install
npm run dev
```

The application will then be available through the local development server.

---

# 📸 Screenshots

> Screenshots of the Citizen, Admin, University and Industry portals can be added here.

### 🏠 Citizen Portal

`Add screenshot here`

### 🛡️ Admin Dashboard

`Add screenshot here`

### 🎓 University Portal

`Add screenshot here`

### 🏭 Industry Portal

`Add screenshot here`

### 🤖 AI Matching

`Add screenshot here`

---

# 🌟 Innovation & Uniqueness

JanSetu is not just another complaint-management platform.

### 1. 🔗 Multi-Stakeholder Collaboration

It creates a structured bridge between:

**Citizens + Government + Universities + Industries**

---

### 2. 🎓 Experiential Learning

Real societal problems become practical projects for university students.

This promotes:

- Research
- Innovation
- Problem-solving
- Industry exposure
- Experiential learning

---

### 3. 🤖 Intelligent Industry Matching

AI can help identify organizations that are technically and practically relevant to a proposed solution.

---

### 4. 📊 Structured Problem Lifecycle

Every problem can move through a defined lifecycle:

```text
Reported
   ↓
Validated
   ↓
Assigned
   ↓
Solution Proposed
   ↓
Resources Identified
   ↓
Industry Matched
   ↓
Collaborated
   ↓
Implemented
```

---

### 5. 🌱 From Complaints to Innovation

Instead of simply collecting complaints, JanSetu aims to transform societal challenges into **innovation opportunities**.

---

# 🎓 Alignment with NEP 2020

JanSetu supports the principles of **experiential and multidisciplinary learning** by connecting students with real-world societal challenges.

Students don't just learn concepts—they get opportunities to:

- Identify real problems
- Conduct research
- Develop solutions
- Work in teams
- Collaborate with industries
- Apply technical knowledge
- Create measurable social impact

---

# 🔮 Future Scope

JanSetu can be extended with:

- 📍 GIS-based problem visualization
- 🗺️ Interactive problem heatmaps
- 🤖 Advanced AI proposal generation
- 🧠 Improved semantic industry matching
- 📊 Impact analytics dashboards
- 📱 Full-featured mobile application
- 🔔 Real-time notifications
- 💬 Stakeholder communication system
- 🏆 University innovation rankings
- 📈 Problem-resolution analytics
- 🌐 Multi-state expansion
- 🔗 Government API integrations
- 📑 Automated proposal evaluation

---

# 🧪 Development Status

| Module | Status |
|---|---|
| Citizen Portal | 🟢 Developed |
| Admin Portal | 🟢 Developed |
| University Workflow | 🟢 Developed |
| Industry Portal | 🟡 In Progress |
| Authentication | 🟢 Implemented |
| Role-Based Access | 🟢 Implemented |
| REST APIs | 🟢 Implemented |
| MongoDB Integration | 🟢 Implemented |
| AI Industry Matching | 🟡 Under Development |
| Production Deployment | 🔵 Future Scope |

---

# 👨‍💻 Team

JanSetu was developed as a **collaborative team project for Smart India Hackathon 2026**.

### Team Members

- **Sushant Ranjan**
- **Shoeb Raza**
- **Ankit Kumar**
- **Abhishek Kumar**

> This repository represents the collaborative JanSetu project. Individual contributions should be documented transparently according to each team member's role.

---

# 💡 My Contribution

As a contributor to JanSetu, my work involved contributing to the development and integration of the platform across its major components.

### Areas of Contribution

- Full-stack application development
- Frontend development
- Backend/API integration
- Database integration
- Authentication and role-based workflows
- Project architecture
- AI-based industry matching concept
- Hackathon presentation and system design

> Specific contributions can be expanded here based on the exact modules and commits handled individually.

---

# 🏆 Hackathon Context

**JanSetu** was developed for **Smart India Hackathon 2026** under:

**Problem Statement:** `SIH26043`

The project aims to create a scalable digital ecosystem where citizens can surface societal challenges and universities, industries, and administration can collaboratively work toward solving them.

---

# 📌 Vision

> ### “Har Samasya Ka Setu, Har Samadhan Ki Disha.”

JanSetu envisions a future where a citizen's problem does not stop at being reported.

It travels through a connected ecosystem of **ideas, education, technology, resources and collaboration** until it has the potential to become a real solution.

---

# 🤝 Contributing

Contributions, suggestions and improvements are welcome.

If you would like to contribute:

```bash
# Fork the repository

# Clone your fork
git clone https://github.com/sushantranjan912/JanSetu.git

# Create a feature branch
git checkout -b feature/your-feature

# Make your changes
git add .

# Commit
git commit -m "Add: your feature"

# Push
git push origin feature/your-feature

# Open a Pull Request
```

---

# 📄 License

This project is developed as part of an academic/hackathon initiative.

Add an appropriate open-source license before accepting external contributions.

---

<p align="center">

### 🇮🇳 Built for real problems. Designed for collaboration. Driven by innovation.

**JanSetu — Connecting People, Ideas & Resources for a Better Tomorrow.**

</p>


