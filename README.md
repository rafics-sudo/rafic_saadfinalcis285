# Final Exam Development Environment (CIS 285)

This repository contains the development environment I set up for the CIS 285 final exam.  
The project was created and tested entirely inside GitHub Codespaces using the **Default Linux Universal** dev container, as required in the instructions.

---

## Overview

The main goal of this exam task was to build a consistent and isolated development environment for future web application work.  
Using the `.devcontainer` configuration, the container installs both **Vue.js** and **Flask**, giving me the tools needed for full-stack development inside one controlled space.

Everything runs inside a Linux container so the environment stays the same regardless of where it’s opened.

---

## Frontend – Vue.js

Vue.js was installed inside the dev container through the Dockerfile.  
I also created a basic Vue project located in the `frontend` folder to confirm that the installation works correctly.

To test the Vue setup:

```bash
cd frontend
npm run serve

