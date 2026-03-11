# Getting Started with GitHub (A Very Simple Introduction)

GitHub can feel overwhelming at first. There are repositories, branches, commits, pull requests, and a lot of terminology that can make it seem more complicated than it needs to be.

But the core ideas behind GitHub are actually very simple.

This repository is a **minimal introduction to GitHub**, designed for beginners who want to understand:

- What GitHub is
- How version control works
- How collaborators share and track code
- How to publish simple materials online using GitHub Pages

The goal is not to cover everything. Instead, it focuses on **clear definitions and practical first steps**.

---

## What This Repository Contains

This repository hosts a short tutorial built with **Quarto** and published as a simple webpage.

The tutorial includes:

- Basic explanations of Git and GitHub
- Key terminology (repositories, commits, branches, pull requests)
- How GitHub enables collaboration
- How to create a GitHub profile
- How to share code with others

The page is rendered from a Quarto file and published using **GitHub Pages**.

---

## View the Tutorial

You can view the published version of the tutorial here:

**https://madelineratoza.github.io/Github/**

---

## Files in This Repository

```
index.qmd      # Quarto source file for the tutorial
index.html     # Rendered HTML page published with GitHub Pages
README.md      # This file
```

---

## How This Page Was Built

The tutorial was created using **Quarto** and **Visual Studio Code**.

Basic workflow:

1. Write content in `index.qmd`
2. Render the HTML page:

```
quarto render index.qmd
```

3. Commit and push updates:

```
git add .
git commit -m "Update tutorial"
git push origin main
```

4. GitHub Pages automatically publishes the updated `index.html`.

---

## Why This Exists

Many people who work with data, research, or programming eventually encounter GitHub. It is a powerful platform for sharing work and collaborating on projects, but it can feel opaque to beginners.

This tutorial is intended as a **gentle first step**—a place to learn the basic concepts before diving deeper into Git workflows.

---

## A Note for Beginners

If you are new to GitHub, the most important thing to remember is:

You do not need to understand everything at once.

Start with the basic ideas:
- A **repository** stores your project.
- A **commit** records a change.
- A **push** uploads your changes to GitHub.

From there, everything else builds gradually.

---

## License

This material is shared for educational purposes. Feel free to use or adapt it for teaching and learning.
