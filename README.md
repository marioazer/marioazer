<div align="center">

# Hi, I'm Mario Azer 👋

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=2E9EF7&center=true&vCenter=true&width=600&lines=Software+Engineer+%7C+Full-Stack+%2B+Systems;Building+Cloud-Native+Microservices;CS+Grad+of+George+Mason+University;Java+%C2%B7+Spring+Boot+%C2%B7+React+%C2%B7+AWS" alt="Typing SVG" />
</a>

<p>
  <a href="https://www.linkedin.com/in/marioazer1/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:marioazer16@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white" /></a>
  <a href="https://github.com/marioazer"><img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" /></a>
</p>

</div>

## About Me

- 🎓 B.S. Computer Science, **George Mason University** (Spring 2026)
- 🎓 A.S. Computer Science, **Northern Virginia Community College (NOVA)** (Spring 2024)
- 🛠️ Freelance Web Developer since 2024, building and deploying React apps for local business clients
- 🏗️ Currently building **cloud-native, event-driven systems** using microservices, Kafka, Kubernetes, and Terraform
- 🖥️ Also into low-level systems: wrote a multiprogramming subsystem for the **OS/161** teaching OS in C
- 📍 Virginia, USA
- ✝️ Fun fact: Coptic Orthodox who loves to code

## Tech Stack

<div align="center">

**Languages**

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

**Frameworks & Libraries**

![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white) ![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white) ![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black) ![JUnit5](https://img.shields.io/badge/JUnit5-25A162?style=flat-square&logo=junit5&logoColor=white)

**Data & Messaging**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![Apache Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

**DevOps & Cloud**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white) ![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white) ![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

**Tools**

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

</div>

## Featured Projects

### 🏦 [Cloud-Native Banking Microservices](https://github.com/marioazer/banking-app-microservices)
`Java` `Spring Boot` `PostgreSQL` `Kafka` `Redis` `Docker` `Kubernetes` `Terraform`

Event-driven banking platform of six independently deployable Spring Boot microservices, each owning its own schema.

- Guaranteed atomic money transfers under concurrent load using pessimistic DB locking, eliminating double-spend race conditions and reserving escrow for large-transfer fraud review
- Secured every service as an OAuth2 resource server validating JWTs from a dedicated auth service, with refresh-token rotation, 2FA, and KYC enforcement gates
- Real-time alert engine pairing OpenFeign with Redis-cached lookups to evaluate transactions within a 5-second SLA
- Provisioned AWS EKS + RDS with Terraform, deployed via Helm/K8s manifests, backed by a GitHub Actions matrix running 89 JUnit 5 tests across 14 classes on every push

### 🖥️ [OS/161 Multiprogramming Kernel](https://github.com/marioazer/OS-161-Multiprogramming-Kernel)
`C` `MIPS Assembly`, Paired Project

Transformed OS/161 from a single-program environment into a fully functional multiprogramming operating system.

- Built a global PID allocation table and state-tracking with process-level mutexes/condition variables for thread-safe process creation and termination
- Implemented core UNIX syscalls, including `fork()` (deep-copying address spaces/trapframes) and `execv()` (ELF loading with EFAULT/ENOMEM validation)
- Designed deterministic parent-child sync for `waitpid()`/`_exit()`, with reliable exit codes and orphan cleanup
- Validated kernel-user boundaries via `copyin`/`copyout`; verified with 20+ self-authored tests covering fork limits and fault injection

### 🌐 [Personal Portfolio Site](https://github.com/marioazer/personal-site)
`React` `Vite`

My personal site/portfolio, built with React + Vite.

## GitHub Stats

<div align="center">

<img src="https://streak-stats.demolab.com/?user=marioazer&theme=tokyonight&hide_border=true" />

</div>

## Let's Connect

<div align="center">

📫 Reach me at **marioazer16@gmail.com** or on [LinkedIn](https://www.linkedin.com/in/marioazer1/)

</div>
