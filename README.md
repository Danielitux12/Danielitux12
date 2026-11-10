<div align="center">

![Header](https://capsule-render.vercel.app/api?type=waving&color=0:5C2D91,100:512BD4&height=190&section=header&text=Daniel%20Isaac%20Jaraba&fontSize=38&fontColor=ffffff&animation=fadeIn&desc=Full%20Stack%20.NET%20Developer&descAlignY=62&descSize=18)

[![Typing SVG](https://readme-typing-svg.demolab.com/?font=Fira+Code&weight=500&size=20&pause=1200&color=512BD4&center=true&vCenter=true&width=600&lines=C%23+%7C+ASP.NET+Core+%7C+React+%7C+PostgreSQL;Clean+Architecture+%26+SOLID+principles;Shipping+Reaction+Shooter+right+now)](https://git.io/typing-svg)

[![GitHub](https://img.shields.io/badge/GitHub-Danielitux12-181717?style=flat&logo=github&logoColor=white)](https://github.com/Danielitux12)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/daniel-jaraba-a627a6368/)
[![Email](https://img.shields.io/badge/Email-danielillo3609%40gmail.com-D14836?style=flat&logo=gmail&logoColor=white)](mailto:danielillo3609@gmail.com)

</div>

---

## About Me

I'm a Software Developer focused on the **.NET ecosystem**, with a strong interest in backend engineering and full stack development. I enjoy designing RESTful APIs, working with relational databases, applying object-oriented principles, and organizing applications with maintainable, scalable architectures. I also work with frontend technologies such as React and Angular to deliver complete web solutions.

### Technical Focus

- **Backend:** C#, .NET 10, ASP.NET Core, Entity Framework Core
- **Frontend:** React, Angular, TypeScript, JavaScript, HTML5, CSS3
- **Databases:** PostgreSQL
- **Architecture & Practices:** Clean Architecture, SOLID principles, RESTful APIs, OOP
- **Tools & Infrastructure:** Docker, Git, GitHub, Linux

### Currently

- Building backend and full stack applications with .NET
- Applying Clean Architecture and SOLID principles to organize application code
- Working with authentication and authorization using ASP.NET Core Identity, JWT, and cookie authentication
- Improving automated testing practices with xUnit
- Deepening Docker and deployment workflows
- Open to collaborating on backend and full stack .NET projects

---

## Spotlight Project

### [Reaction Shooter](https://github.com/Danielitux12/reaction-time-tester)

![Static Badge](https://img.shields.io/badge/status-actively%20developed-success?style=flat)
![Static Badge](https://img.shields.io/badge/rebuilt-full%20stack-blueviolet?style=flat)

A reaction-time trainer built for FPS players, rebuilt from the ground up into a full stack application: **React + TypeScript** on the frontend and **ASP.NET Core + PostgreSQL** on the backend, orchestrated with Docker Compose. What started as a simple browser game is now a proper client-server app with persisted scores and a real API behind it.

**Architecture**

- `frontend/` — React + TypeScript app built with Vite
- `backend/` — ASP.NET Core 8 API
- `docker-compose.yml` — one-command local infrastructure (API + PostgreSQL)

**API**

- `GET /api/scores?limit=10` — top reaction times
- `GET /api/scores/{id}` — retrieve one score
- `POST /api/scores` — save a score

```json
{
  "player": "guest",
  "difficulty": 2,
  "timeMs": 243,
  "attempts": 1
}
```

`React` `TypeScript` `Vite` `C#` `.NET 8` `ASP.NET Core` `PostgreSQL` `Entity Framework Core` `Docker Compose`

---

## Other Projects

### [SkillHub — Workshop & Enrollment Management Platform](https://github.com/Danielitux12/SkillHub)

A workshop management platform built with .NET 10. Supports workshop scheduling, participant enrollment, and administrative workflows while enforcing business rules to protect data consistency.

- Five-project solution following Clean Architecture: `Domain`, `Application`, `Infrastructure`, `API`, `Web`
- RESTful API with ASP.NET Core; JWT Bearer auth for the API, cookie auth for the MVC web app
- PostgreSQL with EF Core and Code First migrations
- Workshop capacity validation, duplicate-enrollment prevention, schedule-conflict rules, and a 24-hour cancellation window
- Bulk enrollment imports from Excel (ClosedXML) and PDF certificate generation (QuestPDF)

`C#` `.NET 10` `ASP.NET Core` `Clean Architecture` `EF Core` `PostgreSQL` `Identity` `JWT` `Razor Views` `ClosedXML` `QuestPDF`

### [FrameRent — Audiovisual Equipment Rental Platform](https://github.com/Danielitux12/FrameRent)

A RESTful API for managing audiovisual equipment rentals, built with .NET 10 and Clean Architecture, paired with a separate React frontend.

- Separation of concerns across `Domain`, `Application`, `Infrastructure`, `API`
- Data persistence with Entity Framework Core
- Structured development workflow using conventional commits

`C#` `.NET 10` `ASP.NET Core` `Entity Framework Core` `Clean Architecture` `React`

### [FirmezaProyect — Business Management Platform](https://github.com/Danielitux12/FirmezaProyect)

A business management and invoicing system built with .NET 10 and Clean Architecture, with ASP.NET Core MVC for the web interface.

- Five-project solution: `Firmeza.Domain`, `Firmeza.Application`, `Firmeza.Infrastructure`, `Firmeza.API`, `Firmeza.Web`
- Domain entities for Client, Product, Sale, and SaleDetail with repository interfaces
- PostgreSQL persistence via EF Core; Docker and Docker Compose for local development

`C#` `.NET 10` `ASP.NET Core` `Clean Architecture` `EF Core` `PostgreSQL` `Docker`

---

## Tech Stack

<div align="center">

**Backend**

![C#](https://img.shields.io/badge/C%23-512BD4?style=for-the-badge&logo=csharp&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![ASP.NET Core](https://img.shields.io/badge/ASP.NET_Core-5C2D91?style=for-the-badge&logo=dotnet&logoColor=white)
![EF Core](https://img.shields.io/badge/Entity_Framework_Core-512BD4?style=for-the-badge&logo=nuget&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

**Databases & Infrastructure**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

</div>

---

## GitHub Stats

<div align="center">

![Daniel's GitHub stats](https://github-readme-stats.vercel.app/api?username=Danielitux12&show_icons=true&theme=tokyonight&hide_border=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Danielitux12&layout=compact&theme=tokyonight&hide_border=true)
![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=Danielitux12&theme=tokyonight&hide_border=true)

</div>

---

## Currently Learning

- Software architecture and design patterns in .NET
- Automated testing with xUnit
- Docker, CI/CD, and application deployment
- Backend performance, reliability, and scalability

---

<div align="center">

If any of these projects caught your interest, a star is always appreciated.

![Footer](https://capsule-render.vercel.app/api?type=waving&color=0:512BD4,100:5C2D91&height=100&section=footer)

</div>
