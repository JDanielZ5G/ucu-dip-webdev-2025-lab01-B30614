# Lab 01 — Environment Setup & Git Workflow

## Tasks
- [x] Install Node LTS, Git, VS Code
- [x] Configure Git user and default branch  
- [x] Initialize repo and create semantic `index.html`
- [x] Create `.gitignore` and `README.md`
- [x] Open a Pull Request from a feature branch

## How to run
Open `index.html` in a browser (or use VS Code Live Server).

## Screenshots
1) PR page 
2) DevTools → Network tab (HTML request shows 200)

## Reflection (100–150 words)
- What is an HTTP request/response?
- Which status code did you see, and what does it mean?
- One thing you learned about Git today.

*[## Reflection

This lab provided an excellent introduction to modern web development workflows and Git version control. 
An HTTP request occurs when a browser asks a server for a resource (like our HTML file), and the HTTP 
response is what the server sends back, including the requested content and a status code. 
I observed status code 200, which means "OK" - indicating the server successfully found and delivered the requested file without any errors.

The most valuable lesson I learned about Git today was the importance of the branching workflow. Instead of making changes directly 
on the main branch, I created a feature branch, implemented my changes, and then merged them back through a Pull Request.
This approach promotes safer collaboration and code review practices. The branch-and-merge strategy ensures that the main branch remains 
stable while allowing developers to experiment and make changes in isolation.

Working with semantic HTML elements like `<header>`, `<nav>`, `<main>`, `<section>`, and `<footer>` reinforced the importance of writing accessible, meaningful markup. These elements provide structure and context that both browsers and assistive technologies can understand. The lab effectively demonstrated how proper development tools, version control, and semantic coding practices form the foundation of professional web development. This workflow will be essential for all future projects.]*
