# 🚀 Concerto Interview Dashboard

_A Full-Stack Interview Management System Built with Next.js & .NET_

![Tech Stack](https://img.shields.io/badge/-Next.js-000?style=flat&logo=next.js)
![Tech Stack](https://img.shields.io/badge/-.NET-512BD4?style=flat&logo=dotnet)
![Tech Stack](https://img.shields.io/badge/-TailwindCSS-06B6D4?style=flat&logo=tailwind-css)

---

## 🌟 **Project Overview**

**What It Does**:  
The **Concerto Interview Dashboard** helps companies streamline technical interviews by providing:

- 📅 **Interview scheduling** with candidate details
- 🎯 **Real-time status tracking** (Scheduled → In Progress → Completed)
- 📊 **Analytics dashboard** to visualise team performance
- 🔐 **Secure authentication** for recruiters & interviewers

**Why It Matters**:

- 🏢 Perfect for tech companies like [Concerto](https://www.concerto.co.uk) to showcase modern development practices
- 💡 Demonstrates **full-stack mastery** with clean architecture and best practices

---

## 🛠️ **Features**

| Frontend (Next.js)           | Backend (.NET)               |
| ---------------------------- | ---------------------------- |
| 📱 Responsive UI             | 🔐 JWT Authentication        |
| 🎨 TailwindCSS styling       | 🧩 CQRS Pattern              |
| 🔄 Real-time SignalR updates | ✅ FluentValidation          |
| 📈 Chart.js visualisations   | 🐳 Docker & Azure Deployment |

---

## ⚙️ **Tech Stack**

**Frontend**:  
![Next.js](https://img.shields.io/badge/Next.js-14-000?logo=next.js)  
![TypeScript](https://img.shields.io/badge/TypeScript-5.3-3178C6?logo=typescript)  
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-3.4-06B6D4?logo=tailwind-css)

**Backend**:  
![.NET](https://img.shields.io/badge/.NET-8-512BD4?logo=dotnet)  
![EntityFramework](https://img.shields.io/badge/EF%20Core-8-FFFFFF?logo=entity-framework)  
![SQL Server](https://img.shields.io/badge/SQL%20Server-2022-CC2927?logo=microsoft-sql-server)

**Tools**:  
![Docker](https://img.shields.io/badge/Docker-26.0-2496ED?logo=docker)  
![Azure](https://img.shields.io/badge/Azure-Cloud-0078D4?logo=microsoft-azure)

---

## 🚦 **Getting Started**

### **Prerequisites**

- Node.js ≥18.x
- .NET 8 SDK
- Docker Desktop

---

## 🔧 **Backend Setup**

```bash
# 1. Clone the repository
git clone https://github.com/your-username/concerto-interview-dashboard.git
cd concerto-interview-dashboard/src/Concerto.Interview.Api

# 2. Restore dependencies
dotnet restore

# 3. Start SQL Server in Docker
docker-compose -f ../../docker-compose.yml up -d

# 4. Run database migrations
dotnet ef database update --project ../Concerto.Interview.Infrastructure

# 5. Start the .NET API
dotnet run
```
