# Hi, I'm Ridoy 👋

### Backend Developer · Node.js · NestJS · TypeScript · PostgreSQL

I'm a Backend Developer from **Dhaka, Bangladesh**, focused on building scalable, secure, and reliable server-side systems. I enjoy designing clean APIs, modeling databases that hold up under real traffic, and turning complex business logic into maintainable code.

- 💼 **Backend Developer** at Softvence Agency, building production-grade REST APIs and modular services with NestJS, Prisma, and PostgreSQL
- ⚙️ I design **RESTful APIs, microservices, and event-driven systems** with clear boundaries and consistent contracts
- 🗄️ I care about **database design and performance**: relational schemas, indexing, and query optimization
- 🔐 I build **authentication and authorization** with JWT, OAuth 2.0, RBAC, OTP, and session management
- 📨 I work with **Kafka, WebSockets, Socket.IO, and gRPC** for messaging and real-time features
- 🧪 I value **reliability**: input validation, centralized error handling, structured logging, and automated tests
- 🐳 I ship with **Docker, GitHub Actions, CI/CD pipelines, Linux, and AWS**
- 🤝 I contribute to **open source**, currently to the NestJS framework
- 🌱 Currently studying Computer Science & Technology and exploring AI-integrated backend features
- 📫 Reach me at **ridoy.babu.781@gmail.com**

---

## 🤝 Open Source Contributions

| Project | Contribution | PR | Status |
|---|---|---|---|
| [**nestjs/nest**](https://github.com/nestjs/nest) | Added integration & E2E tests for the HTTP `QUERY` method (RFC 10008) lifecycle on Express and Fastify | [#17798](https://github.com/nestjs/nest/pull/17798) | ![PR status](https://img.shields.io/github/pulls/detail/state/nestjs/nest/17798) |

<details>
<summary><b>NestJS · #17798 — test(testing): add e2e tests for HTTP QUERY method lifecycle</b></summary>
<br>

Audited NestJS's support for the HTTP `QUERY` method (RFC 10008) and added test coverage proving that `@QueryMethod()` works through the full request lifecycle.

- Added a `@QueryMethod(':id')` route combining `@Param()`, `@Query()` with a pipe, `@Body()`, guards, and interceptors
- Added a `reject` route to verify exception filters work with `QUERY`
- Added matching E2E coverage for both `@nestjs/platform-express` and `@nestjs/platform-fastify`
- Verified `@Query()` (URL query string) and `@QueryMethod()` (HTTP method) work together without ambiguity
- Fixed the Express E2E `httpRequest()` helper so it preserves query strings such as `?tenant=acme`
- Results: 10/10 new tests, 808 integration tests, and 1971 package tests passing, with no breaking or public API changes

</details>

<!-- To add a new contribution: copy a table row above, and optionally a <details> block for the write-up. -->

---

## 💻 Tech Stack

**Languages**

![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E) ![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)

**Backend & APIs**

![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white) ![NestJS](https://img.shields.io/badge/nestjs-%23E0234E.svg?style=for-the-badge&logo=nestjs&logoColor=white) ![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB) ![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black) ![gRPC](https://img.shields.io/badge/gRPC-244C5A?style=for-the-badge&logo=google&logoColor=white) ![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)

**Databases & ORMs**

![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white) ![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white) ![Redis](https://img.shields.io/badge/redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white) ![Prisma](https://img.shields.io/badge/Prisma-3982CE?style=for-the-badge&logo=Prisma&logoColor=white) ![TypeORM](https://img.shields.io/badge/TypeORM-FE0803?style=for-the-badge&logo=typeorm&logoColor=white) ![Mongoose](https://img.shields.io/badge/Mongoose-880000?style=for-the-badge&logo=mongoose&logoColor=white)

**Messaging & Real-time**

![Apache Kafka](https://img.shields.io/badge/Apache%20Kafka-000?style=for-the-badge&logo=apachekafka) ![Socket.io](https://img.shields.io/badge/Socket.io-black?style=for-the-badge&logo=socket.io) ![Firebase](https://img.shields.io/badge/firebase-a08021?style=for-the-badge&logo=firebase&logoColor=ffcd34) ![Twilio](https://img.shields.io/badge/Twilio-F22F46?style=for-the-badge&logo=Twilio&logoColor=white)

**DevOps & Cloud**

![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white) ![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black) ![Nginx](https://img.shields.io/badge/nginx-%23009639.svg?style=for-the-badge&logo=nginx&logoColor=white) ![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=Cloudflare&logoColor=white) ![Render](https://img.shields.io/badge/Render-46E3B7.svg?style=for-the-badge&logo=render&logoColor=white) ![Vercel](https://img.shields.io/badge/vercel-%23000000.svg?style=for-the-badge&logo=vercel&logoColor=white) ![Netlify](https://img.shields.io/badge/netlify-%23000000.svg?style=for-the-badge&logo=netlify&logoColor=#00C7B7) ![Heroku](https://img.shields.io/badge/heroku-%23430098.svg?style=for-the-badge&logo=heroku&logoColor=white)

**Testing & Tools**

![Jest](https://img.shields.io/badge/-jest-%23C21325?style=for-the-badge&logo=jest&logoColor=white) ![Vitest](https://img.shields.io/badge/vitest-6E9F18?style=for-the-badge&logo=vitest&logoColor=white) ![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white) ![ESLint](https://img.shields.io/badge/ESLint-4B3263?style=for-the-badge&logo=eslint&logoColor=white) ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white) ![NPM](https://img.shields.io/badge/NPM-%23CB3837.svg?style=for-the-badge&logo=npm&logoColor=white) ![PNPM](https://img.shields.io/badge/pnpm-%234a4a4a.svg?style=for-the-badge&logo=pnpm&logoColor=f69220) ![Nodemon](https://img.shields.io/badge/NODEMON-%23323330.svg?style=for-the-badge&logo=nodemon&logoColor=%23BBDEAD) ![Notion](https://img.shields.io/badge/Notion-%23000000.svg?style=for-the-badge&logo=notion&logoColor=white) ![Figma](https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white)

**Frontend (when needed)**

![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB) ![Next JS](https://img.shields.io/badge/Next-black?style=for-the-badge&logo=next.js&logoColor=white) ![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white) ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white) ![Chart.js](https://img.shields.io/badge/chart.js-F5788D.svg?style=for-the-badge&logo=chart.js&logoColor=white)

---

## 📊 GitHub Stats

![GitHub stats](https://github-readme-stats.shion.dev/api?username=mdrezuanislamridoy&theme=dark&hide_border=false&include_all_commits=false&count_private=false)

![GitHub streak](https://streak-stats.demolab.com/?user=mdrezuanislamridoy&theme=dark&hide_border=false)

![Top languages](https://github-readme-stats.shion.dev/api/top-langs/?username=mdrezuanislamridoy&theme=dark&hide_border=false&layout=compact)

## 🏆 GitHub Trophies

![Trophies](https://github-profile-trophy.vercel.app/?username=mdrezuanislamridoy&theme=radical&no-frame=false&no-bg=false&margin-w=4)

## 🔝 Top Contributed Repos

![Top contributed repos](https://github-contributor-stats.vercel.app/api?username=mdrezuanislamridoy&limit=5&theme=dark&combine_all_yearly_contributions=true)

## ✍️ Random Dev Quote

![Dev quote](https://quotes-github-readme.vercel.app/api?type=horizontal&theme=tokyonight)

---

## 🌐 Connect With Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/rr-md-ridoy-babu) [![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ridoy.babu.781@gmail.com) [![Facebook](https://img.shields.io/badge/Facebook-%231877F2.svg?style=for-the-badge&logo=Facebook&logoColor=white)](https://www.facebook.com/RidoyBabu.FutureDeveloper) [![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?style=for-the-badge&logo=Instagram&logoColor=white)](https://www.instagram.com/RidoyBabu.FutureDeveloper)
