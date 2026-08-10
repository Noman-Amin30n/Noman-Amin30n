<div align="center">

# Hey, I'm Noman

### Full-stack developer working mainly in Next.js, TypeScript, and MongoDB

**If you are saying "I need a working website or app and someone I can actually talk to about it," then this is for you, so please keep reading.**

[![Email](https://img.shields.io/badge/Email-nomankhan30n%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:nomankhan30n@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-nomanameen.vercel.app-000000?style=flat-square&logo=vercel&logoColor=white)](https://nomanameen.vercel.app)
[![GitHub](https://img.shields.io/badge/GitHub-Noman--Amin30n-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Noman-Amin30n)
<!-- Add your real LinkedIn once the URL is fixed:
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/YOUR-HANDLE) -->

![Experience](https://img.shields.io/badge/Experience-3%2B%20Years-2ea44f?style=flat-square)
![Availability](https://img.shields.io/badge/Availability-Open%20for%20Freelance-brightgreen?style=flat-square)
![Response Time](https://img.shields.io/badge/Response%20Time-%3C24h-blue?style=flat-square)
![Location](https://img.shields.io/badge/Based%20in-Karachi%2C%20Pakistan%20(GMT%2B5)-orange?style=flat-square)

</div>

---

## About

I've been working on web applications for more than three years now. I mostly use the Next.js, TypeScript, and MongoDB stack. I handle everything from the data model to the deployment. It's not the user interface part that I work on. A lot of the projects I do are for businesses and people who start their own businesses. These people need something that is built the first time correctly because they usually don't have the money to rebuild it again in a few months.

There are some things I always pay attention to in every project:

- I always think about the data model and the API before I start writing any code for a component. If I skip this step, the project can become a mess a few weeks later.
- Authentication, checking the inputs, and making sure the queries run fast are not things I add at the end. I include them from the beginning.
- If the work is for a client the application needs to work in production not just look good in a demo.
- I will explain things in words if you are not familiar, with technology.. If you know what you are doing I won't waste time holding your hand.

---

## What I Can Build For You

| Service | What that actually means |
|---|---|
| **Full-stack web apps** | Next.js frontend, an API layer (Express or Next.js route handlers), MongoDB behind it, deployed and working |
| **E-commerce & admin dashboards** | Storefront plus the boring-but-necessary backend: inventory, orders, customer data, basic analytics |
| **Business systems** | Inventory tracking, billing/invoicing, that kind of internal tooling most off-the-shelf software gets wrong for your specific process |
| **Frontend builds** | Turning a design or a rough idea into a working React/Next.js UI with Tailwind and ShadCN, responsive by default |
| **APIs** | REST APIs, typed Mongoose schemas, proper validation — built to be used by more than one client if needed |
| **Maintenance & new features** | Jumping into an existing Next.js/MERN codebase without breaking what already works |

---

## Some Things I've Built

**E-commerce platform + admin dashboard**
A full storefront paired with an admin side for managing products, orders, and customers. Built this as my main portfolio piece, so it's the most "finished" of everything here.
Stack: Next.js, TypeScript, MongoDB, deployed on Vercel.
→ [view repo](https://github.com/Noman-Amin30n/Ecommerce_Next)

**MedStore — stock & billing system for a pharmacy**
This one's real client work, not a portfolio project. A local medical store was tracking inventory and writing invoices by hand. Built a system that handles batch expiry (oldest stock sells first, automatically), generates PDF invoices, and keeps a full audit trail of every stock movement. Went through it in phases — auth and foundation first, then inventory, then billing.
Stack: Next.js 14, TypeScript in strict mode, MongoDB/Mongoose, Zod, JWT.
🔒 Private repo (client project) — happy to walk through it live

**AI chat platform**
Real-time chat app with an AI layer for context-aware responses.
Stack: Next.js 16, real-time messaging.
→ [view repo](https://github.com/Noman-Amin30n/AI-Chats-Next)

**Code snippets manager**
A tool for saving and organizing code snippets — auth, full CRUD, syntax highlighting across languages.
→ [view repo](https://github.com/Noman-Amin30n/Snippets-app)

<details>
<summary>A few earlier things</summary>

- A handful of clone builds (Amazon, a Facebook signup flow, and my SMIT Web Development course assignments) from earlier on, mostly frontend practice

</details>

---

## The MedStore Case Study (short version)

The store owner was tracking stock and writing invoices by hand — the usual problems: stock counts that didn't match reality, expired batches sold ahead of older ones, no record of who changed what.

I worked through it spec-first: wrote out the data model and rules before touching UI code (things like "stock quantities always stored in base units, converted for display" and "oldest-expiring batch sells first, no exceptions"). Every multi-step write — sell an item, adjust stock, log the change — happens as one atomic transaction, so a crash mid-sale can't leave the numbers wrong. Invoices are snapshotted when they're created, so they remain accurate even if a product's price changes later.

Shipped in three phases: auth and foundation, then inventory, then billing and invoicing.

---

## How I Work

Roughly, this is how a project goes:

1. **Talk it through** — what are you actually trying to solve, not just what feature you think you need
2. **Write the spec** — data model, API contract, how the screens fit together, before any real code
3. **Build in chunks** — you see working pieces along the way, not one big reveal at the end
4. **Harden it** — validation, error handling, and the security basics get checked before anything ships
5. **Ship and stick around** — help with deployment, plus a window afterward for fixes

```
Inquiry → Scope & quote → Spec → Build → Review → Deploy → Support
```

---

## 💻 Tech Stack

**Languages:** ![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

**Frontend:** ![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black) ![Next.js](https://img.shields.io/badge/-Next.js-000000?style=flat-square&logo=next.js&logoColor=white) ![Tailwind](https://img.shields.io/badge/-Tailwind%20CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white) ![ShadCN](https://img.shields.io/badge/-ShadCN%2Fui-000000?style=flat-square)

**Backend:** ![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=node.js&logoColor=white) ![Express](https://img.shields.io/badge/-Express-000000?style=flat-square&logo=express&logoColor=white)

**Database:** ![MongoDB](https://img.shields.io/badge/-MongoDB-13aa52?style=flat-square&logo=mongodb&logoColor=white) ![Mongoose](https://img.shields.io/badge/-Mongoose-880000?style=flat-square)

**Tools:** ![Git](https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white) ![Vercel](https://img.shields.io/badge/-Vercel-000000?style=flat-square&logo=vercel&logoColor=white)`

---

## Background

- Full Stack Web Development — coursework/certification
- AI agent integration & chatbot development
- Built and shipped MedStore end-to-end for a real client, spec to deployment
- Working through [100 Days of TypeScript](https://github.com/Noman-Amin30n/100-Days-Typescript-Challenge) — still going

---

## Availability

Currently open for freelance work and entry-level remote roles. Mostly targeting the US, UK, Canada, and Australia — time zone difference isn't a problem; I work async well.

`I can realistically take on 1–2 projects at a time while maintaining quality and meeting deadlines. Open to freelance contracts, part-time opportunities, and full-time entry-level roles.`

Usually reply within 24 hours.

---

## Get in Touch

Got a project in mind? The easiest way to reach me is by email.

- **[Send a project inquiry](mailto:nomankhan30n@gmail.com?subject=Project%20Inquiry)** — tell me what you're trying to build
- **[Hiring inquiry](mailto:nomankhan30n@gmail.com?subject=Hiring%20Inquiry)** — for ongoing or contract work
- **[Just want to collaborate](mailto:nomankhan30n@gmail.com?subject=Collaboration)** — open to that too

[nomankhan30n@gmail.com](mailto:nomankhan30n@gmail.com) · [nomanameen.vercel.app](https://nomanameen.vercel.app) · [github.com/Noman-Amin30n](https://github.com/Noman-Amin30n)

---

<div align="center">

### GitHub Stats

<img src="https://github-readme-stats.vercel.app/api?username=Noman-Amin30n&theme=tokyonight&show_icons=true&hide_border=true" alt="Noman's GitHub stats" width="48%" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Noman-Amin30n&theme=tokyonight&layout=compact&hide_border=true" alt="Top languages" width="45%" />

![Profile Views](https://komarev.com/ghpvc/?username=Noman-Amin30n&color=blueviolet&style=flat-square)

</div>

---

<div align="center">
<sub>If this looks like a fit for what you need, send me an email — happy to talk through the scope.</sub>
</div>
