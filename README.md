# GitHub Pages Static Website
## Task-6
---

This repository contains **Task 6** of my DevOps Internship — a static website hosted using **GitHub Pages**.  
The purpose of this task was to deploy static content for free using GitHub Pages and showcase the previous tasks completed during the internship.

## 🔗 Live Website

[View Live GitHub Page](https://mukund-p.github.io/github-pages-static-site-task/)

---

## Files Included

├── screenshots/ <br>
├── index.html – Structure of the site <br>
├── style.css – Styling and layout <br>
├── app.js – JavaScript for enhanced UI <br>
└── README.md – This file <br>

---

## Screenshot

### 1. Output :

![Output](screenshots/output.png)

---


# 📘 Interview Questions & Answers – GitHub Pages

### 1. What is GitHub Pages?
**GitHub Pages** is a free service offered by GitHub that allows you to host static websites directly from a GitHub repository.  
It supports HTML, CSS, and JavaScript content and is widely used for project documentation and personal portfolios.

---

### 2. Can you host dynamic apps here?
No, **GitHub Pages only supports static content**. It cannot run server-side code such as PHP, Node.js, or Python. For dynamic functionality, you'd need to use client-side JavaScript or external APIs.

---

### 3. What are the limits of GitHub Pages?
- Static content only (no databases or back-end logic)
- Limited storage and bandwidth (soft limit of 1 GB per repo, 100 GB/month bandwidth)
- No HTTPS support for custom domains with apex redirects without additional DNS settings
- One site per GitHub account (plus one per repo)

---

### 4. How do you update the website?
Simply **push updated files** (like `index.html`, `style.css`, etc.) to the GitHub repository. GitHub Pages will automatically rebuild and redeploy the site using the latest version on the specified branch (usually `main`).

---

### 5. What happens when you delete the repo?
If you delete the repository hosting the GitHub Pages site, the **website is deleted as well**, and the published URL becomes inaccessible.

---

### 6. What is the default file that loads?
The default file GitHub Pages looks for is:
- `index.html` in the root directory or specified folder

This file is automatically served as the homepage of your website.

---

### 7. Can you use a custom domain?
Yes, GitHub Pages allows you to use a **custom domain**.  
You can configure it in the repository settings under "Pages" and create a `CNAME` file in the root of the repo or set DNS records to point to GitHub's servers.
