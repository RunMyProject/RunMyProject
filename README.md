# Hi, I'm Edoardo Sabatini 👋

**Senior Software Engineer · Java & Spring · Full stack · Event-driven and cloud-native systems**
Milan area, Italy · 17 years in software delivery (2009 – 2026)

[LinkedIn](https://www.linkedin.com/in/edoardofullstack/) · [edoardo.fullstack@gmail.com](mailto:edoardo.fullstack@gmail.com) · 🇮🇹 Italian · 🇬🇧 English

---

## About me

Software engineer since 2009, working on enterprise systems in **banking, insurance, energy, telecom, media, payments and transport**, in Italy and abroad.

My core is **Java and Spring** on the back end, with **Angular and React** on the front end. This profile collects my **personal projects**: about 35 public repositories from 2019 to today, each one with its date, its stack and the reason behind its main design choice. Client work is not published here.

---

## Featured projects

### 🍂 Fall-Insurance · *Sep 2026 · in progress*
Insurance back-office platform. I started with security and infrastructure, because they are the foundation and the most expensive part to change later.
- **Done:** Keycloak as OpenID Connect provider, Spring Boot API gateway as OAuth2 resource server validating JWTs, Next.js login and protected dashboard, all services on Docker Compose.
- **Next:** policies, claims and AI-assisted workflows.
- `Java 25` `Spring Boot 4` `Spring Security` `WebFlux` `Keycloak 26` `PostgreSQL` `Next.js 16` `React 19` `TypeScript`

👉 [fall-insurance](https://github.com/RunMyProject/fall-insurance)

### 🧳 FrankStack · *Aug – Nov 2025 · release candidate*
Travel booking platform built from microservices and orchestrated by a local AI assistant. The user describes the trip in plain words, and the booking moves forward with real-time WebSocket updates.
- Spring Cloud Gateway with Resilience4j circuit breakers and Prometheus metrics, plus an orchestrator for the booking flows.
- **Event-driven by design:** Kafka for hotel bookings, AWS Lambda + SNS + SQS (on LocalStack) for card payments, and PDF receipts generated with iText and stored on S3.
- Stripe payments and the AI chat channel in Node.js, with Gemma 2 running locally on Ollama (with NVIDIA GPU support).
- 69 commits in about ten weeks, with dated release notes up to RC1.
- `React` `Vite` `Node.js` `Spring Boot 3.5` `Java 21` `Kafka` `AWS (LocalStack)` `Stripe` `Ollama` `Docker Compose`

👉 [FrankStack](https://github.com/RunMyProject/FrankStack) · 🎬 [Video demo](https://youtube.com/watch?v=spZ-lbxA4w0)
A voice module is being prepared (speech synthesis with Chatterbox, transcription with Whisper): [chatterbox](https://github.com/RunMyProject/chatterbox)

### 📅 ScalaPlan AI · *Dec 2024 – Apr 2025 · live MVP*
Smart daily planner. The first version was built in Scala with Play Framework. I then moved to a lighter Node.js + vanilla JS version, so I could publish the MVP on Vercel and let anyone try it.
- Tasks are scheduled automatically from 7:00 to 23:00 in 15-minute slots. Users can group them into workspaces with drag & drop and undo the history of completed tasks.
- Three themes, Italian and English, sign-in with LinkedIn (OpenID Connect) and a guided tour with Shepherd.js.
- 117 commits, with 50 development days logged one by one. The main source code is private and available on request.
- `Scala` `Play Framework` `Node.js` `JavaScript` `CSS3` `Webpack` `Vercel`

👉 [Live demo](https://scala-plan-ai.vercel.app) · [Showcase repo](https://github.com/RunMyProject/scala-plan-ai-demo)

### 🦁 Jacob's Resilience · *Jul 2024 · hackathon*
Terminal game in C# inspired by the true story of Jacob the lion, who swam across the Kazinga Channel in Uganda at night. It was built in the ten days of a hackathon.
- Modular code (game models, controls, configuration, player state) and sound effects through `sox`.
- It ships in two forms, a Docker container on Linux and a single executable for Windows, so it runs anywhere without setup.
- `C# 12` `.NET 8` `Docker` `Bash`

👉 [JacobResilience](https://github.com/RunMyProject/JacobResilience) · 🎬 [Gameplay video](https://youtu.be/cRSOrJi2yA4)

---

## 2026 labs and technical tests

| When | Project | What it shows | Stack |
|---|---|---|---|
| May 2026 | [multi-field-time-aggregator](https://github.com/RunMyProject/multi-field-time-aggregator) | Versioned REST API (v1/v2) that aggregates worked hours by project, by employee or by both. Uses the Strategy pattern, so adding a new grouping does not change existing code. | Java 25, Spring Boot 4, Angular 21 (zoneless, signals), Vitest |
| May 2026 | [few-payments](https://github.com/RunMyProject/few-payments) | Payment simulator on a private Geth chain with an ERC20 token. Every transfer is stored on chain and in PostgreSQL, and the balances are checked by tests. | Java 25, Spring Boot 4, Web3j, Solidity, PostgreSQL, TestContainers |
| Apr 2026 | [devops](https://github.com/RunMyProject/devops) | The full release cycle run locally at no cost: CloudFormation stack on LocalStack, Ansible provisioning, Spring Boot container. | AWS CloudFormation, LocalStack, Ansible, Docker |
| Mar 2026 | [qqq](https://github.com/RunMyProject/qqq) · *Quail Quarkus Qwen* | Game driven by an AI agent that runs fully offline. A GBNF grammar constrains the model so that it can only answer with valid moves. | Quarkus, LangChain4j, llama.cpp, Qwen 2.5, Svelte 5 |
| Jan 2026 | [FractionLayer](https://github.com/RunMyProject/FractionLayer) | Prototype of a platform for real-world asset tokenization, with a React UI and a first Go service. The crypto layer is designed but not built yet. | React 19, Vite, Tailwind, Go (Fiber) |

---

## Earlier work, 2019 – 2025

<details>
<summary><b>Show all projects by year</b></summary>

**2025**
- [chatterbox](https://github.com/RunMyProject/chatterbox): multilingual text-to-speech (Chatterbox by Resemble AI) and speech-to-text (Whisper) tests for the FrankStack voice module. *Python, PyTorch, CUDA*

**2024**
- [tandc-generator](https://github.com/RunMyProject/tandc-generator): generates Terms & Conditions documents from templates and data. *PHP*
- [python-flask-backend-api-testing](https://github.com/RunMyProject/python-flask-backend-api-testing): back-end API with endpoint tests. *Python, Flask*
- [word-counter-web](https://github.com/RunMyProject/word-counter-web): containerised word-count web server. *Node.js, Docker*
- [python](https://github.com/RunMyProject/python): Python learning notes. *Python*

**2023**
- [EnchantedRealmK8s](https://github.com/RunMyProject/EnchantedRealmK8s): Spring Boot + Kafka microservice on Kubernetes, with deployment, service, Docker registry secret and rollout scripts. *Java 11, Spring Kafka, Kubernetes*
- [lake-cleaner-admin](https://github.com/RunMyProject/lake-cleaner-admin): admin panel for robot ducks that clean plastic from lakes. *Node.js, MongoDB, Mongoose*
- [news-aggregator](https://github.com/RunMyProject/news-aggregator): REST service merging Hacker News and New York Times stories. *Kotlin, Java 17, Gradle, Docker, Render*
- [dev-ops-2023](https://github.com/RunMyProject/dev-ops-2023): REST service detecting file MIME types, with JWT authentication. *Spring Security, JWT, Docker, MySQL*
- [Fullstack_2023](https://github.com/RunMyProject/Fullstack_2023): full-stack technical test. *Angular, Dropwizard*
- [Java_Technical_Test_2023](https://github.com/RunMyProject/Java_Technical_Test_2023): batch-processing technical test. *Java 7/8/9*
- [RubyPerlJan2022](https://github.com/RunMyProject/RubyPerlJan2022): the same test solved in Ruby and in Perl. *Ruby, Perl*

**2022**
- [AngularWinter2022](https://github.com/RunMyProject/AngularWinter2022): home page with sign-up and login. *Angular 13, JWT*

**2021**
- [react-project](https://github.com/RunMyProject/react-project): hooks and child-to-parent callbacks. *React*
- [OldFashionPound](https://github.com/RunMyProject/OldFashionPound): calculator for pounds, shillings and pence. *Java 8*
- [MyVaccine.com.Flask](https://github.com/RunMyProject/MyVaccine.com.Flask): quick vaccination booking. *Python, Flask, SQLAlchemy, GraphQL*
- [MyGoFlutter](https://github.com/RunMyProject/MyGoFlutter): Go back end with a Flutter Android client. *Go, Flutter, Dart*

**2020**
- [invinoveritas-node-redis-react](https://github.com/RunMyProject/invinoveritas-node-redis-react): full-stack app. *Node.js, Redis, React, Docker*
- [goose](https://github.com/RunMyProject/goose): the Game of the Goose, with BDD tests. *Java 8, Cucumber*
- [twitter-api](https://github.com/RunMyProject/twitter-api): Twitter-like social network API. *Spring Boot 2, HATEOAS, Swagger, H2*
- [MyDotNet](https://github.com/RunMyProject/MyDotNet): .NET solutions for technical interviews. *ASP.NET, C#, Razor*
- [task-tracking](https://github.com/RunMyProject/task-tracking): task tracker split into two Docker images. *Angular, .NET Core, Docker*
- [twitter-stream](https://github.com/RunMyProject/twitter-stream): streaming tweet reader. *Java 8, Docker, OAuth2*
- [api-test](https://github.com/RunMyProject/api-test): payment-order API services. *Spring, Java 8, Docker*

**2019**
- [MyAngular](https://github.com/RunMyProject/MyAngular): collection of Angular projects. *Angular*
- [RunMyBranch](https://github.com/RunMyProject/RunMyBranch): Java demo for job interviews. *Java 8*

</details>

---

## Tech I work with

**Back end:** Java (8 → 25), Spring Boot, Spring Security, Spring Cloud Gateway, WebFlux, Quarkus, Node.js, Scala / Play, Go, C# / .NET, Kotlin
**Front end:** Angular, React, Next.js, Svelte, TypeScript, JavaScript
**Data & messaging:** PostgreSQL, Oracle, MySQL, MongoDB, Redis, Kafka, SNS / SQS
**Cloud & DevOps:** Docker, Docker Compose, Kubernetes, AWS (Lambda, S3, CloudFormation via LocalStack), Ansible, Vercel, Prometheus
**Security:** Keycloak, OAuth2 / OpenID Connect, JWT
**AI:** local LLMs (Ollama, llama.cpp), LangChain4j, grammar-constrained decoding, speech-to-text and text-to-speech
**Testing:** JUnit, TestContainers, Cucumber, Vitest

---

<sub>Last updated: November 2026</sub>
