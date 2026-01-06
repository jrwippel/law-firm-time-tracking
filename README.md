# Law Firm Time Tracking System

## Overview

This project is a **web-based time tracking and management system** developed for a law firm to register lawyers’ working hours, monitor activities, and support **accurate billing and strategic financial decisions**.

The system is currently supporting daily operations and monthly billing processes.

---

## Business Problem

Law firms face challenges such as:

- Lack of visibility on how lawyers' time is spent
- Difficulty in closing monthly billing accurately
- Limited data to evaluate fixed-fee (retainer) vs hourly clients
- Poor insights to support financial and strategic decisions

Manual or spreadsheet-based tracking often leads to errors, revenue loss, and lack of transparency.

---

## Solution

This system provides a centralized platform where:

- Lawyers register their working time per activity and client
- Managers can analyze time distribution and productivity
- Monthly billing reports are generated with accuracy
- The firm can evaluate if:
  - Fixed-fee clients exceed agreed hours
  - Hourly clients could be migrated to monthly retainers

---

## Key Features

- ⏱️ Time tracking per lawyer, client, and activity
- 📊 Monthly billing and reporting
- 💼 Support for fixed-fee and hourly clients
- 📈 Productivity and cost analysis
- 🔐 Role-based access (lawyers, managers, administrators)
- ☁️ Cloud-hosted and scalable architecture

---

## Business Impact

- Improved billing accuracy
- Increased financial transparency
- Data-driven decision making
- Better resource allocation across the firm
- Reduced manual work and operational risk

---

## Architecture & Technologies

The system was designed with maintainability and scalability in mind, considering a real production environment.

- Backend: ASP.NET MVC (C#)
- Database: SQL Server
- Cloud Hosting: Microsoft Azure
- Authentication: ASP.NET Identity
- Version Control: Git & GitHub

The architectural decisions prioritize long-term evolution, stability, and ease of onboarding new developers.

## Security & Data Privacy

- All sensitive credentials secrets were removed
- Configuration values are managed via environment variables
- Client data was anonymized for portfolio usage
- This repository follows GitHub security and secret-scanning best practices



## My Role

I was responsible for the full lifecycle of this project, including:

- Requirements analysis with business stakeholders
- System architecture and technology decisions
- Backend development using ASP.NET MVC
- Database modeling and performance considerations
- Deployment and hosting on Microsoft Azure
- Ongoing maintenance and feature evolution

This project required balancing technical decisions with real business constraints.
---

## Screenshots

### Login Screen
<img width="1578" height="922" alt="image" src="https://github.com/user-attachments/assets/7cf2ab54-b2b6-4a00-ba20-5a58a651679d" />

### Dashboard

<img width="1699" height="589" alt="image" src="https://github.com/user-attachments/assets/1099718d-8014-4612-9d11-592a7835e384" />

### Time Tracking
  
  <img width="1481" height="692" alt="image" src="https://github.com/user-attachments/assets/731bd516-10fd-4921-9bbf-fe05f1608321" />
  
  <img width="1401" height="658" alt="image" src="https://github.com/user-attachments/assets/a83d335a-dbd1-42f6-946c-9189e57bf35d" />

  <img width="1389" height="565" alt="image" src="https://github.com/user-attachments/assets/4eba5248-a65f-4486-8486-e42f7f469d09" />


### Reports

<img width="1448" height="576" alt="image" src="https://github.com/user-attachments/assets/96a068d5-0a95-4839-9cf6-c89f4fe734b8" />

<img width="1371" height="540" alt="image" src="https://github.com/user-attachments/assets/8e323bc5-12e0-416c-96bd-d6e857a1d75f" />

<img width="1472" height="516" alt="image" src="https://github.com/user-attachments/assets/3600f1a3-fff6-45f6-bbe2-07ae97170334" />

<img width="1494" height="298" alt="image" src="https://github.com/user-attachments/assets/d680926e-f552-47c9-969d-609cf4da3f15" />

<img width="1483" height="313" alt="image" src="https://github.com/user-attachments/assets/352dd970-1685-48e4-90df-fb82e2e0dfb2" />

<img width="1467" height="284" alt="image" src="https://github.com/user-attachments/assets/dbfd7441-ce05-4192-81a4-70d96fef5e22" />

### Configuration

<img width="1500" height="519" alt="image" src="https://github.com/user-attachments/assets/8970e6d1-22ec-4dd5-9cb9-fda5d8edcf8e" />

<img width="1482" height="365" alt="image" src="https://github.com/user-attachments/assets/9c7d59e1-037b-414a-8c54-8ab5e4cb2af6" />

<img width="1287" height="394" alt="image" src="https://github.com/user-attachments/assets/643d37e3-6a1a-4fd6-ac7b-80c829691813" />

## About the Author
Software Engineer and Technical Leader with 20+ years of experience.
Background in enterprise systems, legacy modernization, and team leadership.

---

## How to Run Locally

```bash
git clone https://github.com/jrwippel/law-firm-time-tracking.git
