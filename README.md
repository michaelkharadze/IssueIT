# IssueIT

A discussion‑driven app for raising awareness about real‑world problems and sharing actionable solutions. Built as a MERN‑style project with a React front end and an intended Node/Express + MongoDB back end.

**Live site:** [https://stellar-kashata-4c1b75.netlify.app/](https://stellar-kashata-4c1b75.netlify.app/)

---

## Table of contents

* [Features](#features)
* [Tech stack](#tech-stack)
* [Getting started](#getting-started)
* [Project structure](#project-structure)

---

## Features

* Create an **issue** with title, description, and relevant links.
* Start a **discussion thread** focused on proposed solutions.
* **Vote** or **endorse** solutions to surface what works.
* **Tag** issues for discovery and filtering.
* **Search** by keyword or tag.
* **Auth** (sign up / sign in / sign out).
* **Profile pages** showing issues opened and solutions contributed.

---

## Tech stack

* **Frontend:** React. The repository contains a typical React app with `src/`, `public/`, and a production `build/` directory.
* **Backend (planned/current):** Node.js + Express.
* **Database (planned/current):** MongoDB.
* **Tooling:** ESLint configuration present via `.eslintrc.js`.

---

## Getting started

### 1) Clone and install

```bash
git clone https://github.com/michaelkharadze/IssueIT.git
cd IssueIT
npm install
```

### 2) Run the app

```bash
npm start
```

---

## Project structure

```
IssueIT/
├── build/             # Production build output
├── public/            # Static assets
├── src/               # React source code
├── .eslintrc.js       # ESLint rules
├── package.json
└── README.md
```
