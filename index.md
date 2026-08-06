---
layout: home
title: "Nikhil Yadav"
---

<!-- Hero with inline SVG icons and simple animations -->
<section class="hero">
	<div class="hero-inner">
		<div class="hero-left">
			<h1>👋 Hi, I’m <span class="name">Nikhil Yadav</span></h1>
			<p class="lead">Software Engineer — building practical, user-friendly products with clean, maintainable code.</p>

			<div class="social">
				<a class="social-btn" href="https://www.linkedin.com/in/nikhil-yadav-2710/" aria-label="LinkedIn">
					<svg viewBox="0 0 24 24" width="20" height="20" fill="currentColor" aria-hidden="true"><path d="M4.98 3.5C4.98 4.6 4.06 5.5 2.98 5.5 1.9 5.5 1 4.6 1 3.5 1 2.4 1.9 1.5 2.98 1.5 4.06 1.5 4.98 2.4 4.98 3.5zM.5 8.98h4.96V24H.5V8.98zM9.5 8.98h4.75v2.06h.07c.66-1.25 2.28-2.57 4.7-2.57 5.03 0 5.96 3.31 5.96 7.62V24h-4.96v-6.8c0-1.62-.03-3.7-2.26-3.7-2.26 0-2.6 1.77-2.6 3.59V24H9.5V8.98z"/></svg>
					<span>LinkedIn</span>
				</a>

				<a class="social-btn" href="https://github.com/heynik" aria-label="GitHub">
					<svg viewBox="0 0 24 24" width="20" height="20" fill="currentColor" aria-hidden="true"><path d="M12 .5C5.73.5.5 5.73.5 12c0 5.08 3.29 9.38 7.86 10.9.58.11.78-.25.78-.55 0-.27-.01-1-.02-1.95-3.2.7-3.88-1.54-3.88-1.54-.52-1.32-1.28-1.67-1.28-1.67-1.05-.72.08-.71.08-.71 1.16.08 1.77 1.2 1.77 1.2 1.03 1.77 2.71 1.26 3.37.97.1-.76.4-1.26.72-1.55-2.56-.29-5.25-1.29-5.25-5.74 0-1.27.45-2.31 1.19-3.12-.12-.29-.52-1.45.11-3.02 0 0 .97-.31 3.18 1.19a11.07 11.07 0 0 1 2.9-.39c.98 0 1.97.13 2.9.39 2.2-1.5 3.17-1.19 3.17-1.19.63 1.57.24 2.73.12 3.02.74.81 1.19 1.85 1.19 3.12 0 4.46-2.7 5.44-5.27 5.72.41.35.78 1.04.78 2.09 0 1.51-.01 2.73-.01 3.1 0 .3.2.67.79.55A11.51 11.51 0 0 0 23.5 12C23.5 5.73 18.27.5 12 .5z"/></svg>
					<span>GitHub</span>
				</a>

				<a class="social-btn" href="https://twitter.com/Heynik27" aria-label="Twitter">
					<svg viewBox="0 0 24 24" width="20" height="20" fill="currentColor" aria-hidden="true"><path d="M23 4.56c-.8.36-1.66.6-2.56.71a4.47 4.47 0 0 0-7.63 4.08A12.7 12.7 0 0 1 3.15 3.1a4.48 4.48 0 0 0 1.38 5.98c-.66-.02-1.28-.2-1.82-.5v.05c0 2.22 1.58 4.07 3.68 4.49-.38.1-.78.15-1.2.15-.29 0-.57-.03-.84-.08.57 1.8 2.23 3.12 4.19 3.16A9 9 0 0 1 1.5 19.54 12.7 12.7 0 0 0 8.29 21c7.55 0 11.68-6.26 11.68-11.7v-.53c.8-.57 1.5-1.27 2.03-2.08-.73.33-1.5.57-2.3.67z"/></svg>
					<span>Twitter</span>
				</a>
			</div>
		</div>

		<div class="hero-right">
			<div class="card">
				<h3>🏆 Certifications</h3>
				<div class="badges">
					<img alt="AZ-900" src="https://img.shields.io/badge/AZ--900-0078D4?style=flat-square&logo=microsoft-azure&logoColor=white" />
					<img alt="PL-900" src="https://img.shields.io/badge/PL--900-0078D4?style=flat-square&logo=microsoft&logoColor=white" />
					<img alt="SC-900" src="https://img.shields.io/badge/SC--900-0078D4?style=flat-square&logo=microsoft&logoColor=white" />
					<img alt="AI-900" src="https://img.shields.io/badge/AI--900-0078D4?style=flat-square&logo=microsoft&logoColor=white" />
				</div>
			</div>
		</div>
	</div>
</section>

---

<style>
/* Simple, self-contained styling for the hero */
:root{--accent:#0078D4;--bg1:#0f172a;--bg2:#07203a}
.hero{padding:36px 18px;margin-bottom:24px;border-radius:12px;background:linear-gradient(120deg,var(--bg1),var(--bg2));color:#e6eef8;overflow:hidden;}
.hero-inner{display:flex;gap:24px;align-items:center;max-width:1000px;margin:0 auto;animation:fadeIn .6s ease both}
.hero-left{flex:1}
.hero-right{width:320px}
.name{color:var(--accent);}
.lead{opacity:.9;margin-top:6px}
.social{display:flex;gap:12px;margin-top:18px}
.social-btn{display:inline-flex;align-items:center;gap:8px;padding:8px 12px;background:rgba(255,255,255,0.04);border-radius:8px;color:inherit;text-decoration:none;border:1px solid rgba(255,255,255,0.04);transition:transform .18s ease,background .18s ease,box-shadow .18s ease}
.social-btn svg{flex-shrink:0}
.social-btn:hover{transform:translateY(-4px);background:rgba(255,255,255,0.06);box-shadow:0 8px 20px rgba(0,0,0,0.35)}
.card{background:linear-gradient(180deg,rgba(255,255,255,0.02),rgba(255,255,255,0.01));padding:16px;border-radius:10px;border:1px solid rgba(255,255,255,0.04);backdrop-filter:blur(4px);animation:float 6s ease-in-out infinite}
.card h3{margin:0 0 10px}
.badges img{height:34px;margin:6px 6px 0 0}

@keyframes float{0%{transform:translateY(0)}50%{transform:translateY(-6px)}100%{transform:translateY(0)}}
@keyframes fadeIn{from{opacity:0;transform:translateY(6px)}to{opacity:1;transform:none}}

/* Responsive tweaks */
@media (max-width:880px){.hero-inner{flex-direction:column}.hero-right{width:100%}.badges img{height:30px}}
</style>

## 💡 About Me
I’m a **Software Engineer** passionate about building practical, user-friendly products with clean, maintainable code. I enjoy solving complex problems and creating digital experiences that make a real impact.

**Focused on:** Building modern web experiences · Writing scalable software · Continuous learning

---

## 💼 Work Experience

- 🏢 Currently working as a **Software Engineer**.
- 🌐 Worked on web development and software engineering tasks.
- 🚀 Built and improved digital products with practical engineering solutions.

---

## 🎓 Education

- 📚 Computer Science / Software Engineering background

---

## 🏆 Certifications

<div align="center">

![AZ-900](https://img.shields.io/badge/AZ--900-0078D4?style=flat-square&logo=microsoft-azure&logoColor=white) ![PL-900](https://img.shields.io/badge/PL--900-0078D4?style=flat-square&logo=microsoft&logoColor=white) ![SC-900](https://img.shields.io/badge/SC--900-0078D4?style=flat-square&logo=microsoft&logoColor=white) ![AI-900](https://img.shields.io/badge/AI--900-0078D4?style=flat-square&logo=microsoft&logoColor=white)

</div>

- ✅ AZ-900: Microsoft Azure Fundamentals
- ✅ PL-900: Microsoft Power Platform Fundamentals
- ✅ SC-900: Microsoft Security, Compliance, and Identity Fundamentals
- ✅ AI-900: Microsoft Azure AI Fundamentals

---

## 🛠️ Tech Stack

### Languages & Frameworks
![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white) ![.NET](https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=.net&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

### Frontend Development
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white) ![HTML5](https://img.shields.io/badge/HTML5-E34C26?style=for-the-badge&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

### Backend & Cloud
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white) ![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoft-azure&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-338FBD?style=for-the-badge&logo=microsoft-sql-server&logoColor=white)

### Infrastructure & DevOps
![Terraform](https://img.shields.io/badge/Terraform-623CE4?style=for-the-badge&logo=terraform&logoColor=white) ![Azure Bicep](https://img.shields.io/badge/Azure%20Bicep-0078D4?style=for-the-badge&logo=microsoft-azure&logoColor=white) ![ARM](https://img.shields.io/badge/ARM%20Templates-0078D4?style=for-the-badge&logo=microsoft-azure&logoColor=white)

### Developer Tools
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white) ![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)

---

## 📊 Technical Skills

| Category | Skills |
|----------|--------|
| **Backend** | C#, .NET, Node.js, Python |
| **Frontend** | React, JavaScript, TypeScript, HTML/CSS |
| **Database** | SQL, MongoDB |
| **Cloud & DevOps** | Azure, Terraform, Azure Bicep, ARM Templates |
| **Tools** | Git, GitHub, VS Code |

---

## 🚀 What I’m Focused On

- 🔧 Building robust, scalable cloud-native applications
- ☁️ Infrastructure as Code with Azure (Bicep, Terraform, ARM)
- 💻 Full-stack development with .NET and React
- 📈 Writing clean, maintainable, production-ready code
- 🎯 Solving real-world problems efficiently
- 🌱 Staying current with emerging technologies

---

## 📬 Let’s Connect!

**Interested in collaborating? Reach out!** [LinkedIn](https://www.linkedin.com/in/nikhil-yadav-2710/) • [GitHub](https://github.com/heynik) • [Twitter](https://twitter.com/Heynik27)

---

