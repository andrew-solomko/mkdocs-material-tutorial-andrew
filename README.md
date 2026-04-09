# Figma User Guide (Material for MkDocs Project)

This project is a structured user documentation website built using MkDocs with the Material theme. It provides a beginner-friendly guide to using Figma, specifically focusing on FigJam and Figma Design.

The documentation walks users through four practical tasks, helping users learn how to use FigJam, build flowcharts, use Figma Design, and design a basic interactive wireframe.

This project demonstrates skills in:

Technical writing
Documentation design
Static site generation (MkDocs)
UI/UX instruction using Figma

## Features
Step-by-step task-based learning structure
Visual guidance with screenshots
Admonitions for notes, warnings, and success states
Troubleshooting section for common user issues
Glossary for key terms
Clean and responsive Material for MkDocs theme

## Project structure

├── .github/
│ └── workflows/
│ └── ci.yml
├── docs/
│ ├── assets/
│ │ ├── Task1/
│ │ ├── Task2/
│ │ ├── Task3/
│ │ └── Task4/
│ ├── tasks/
│ │ ├── basic-formatting-figjam.md
│ │ ├── basic-formatting-figma-design.md
│ │ ├── first-flowchart-figjam.md
│ │ └── first-wireframe-figma-design.md
│ ├── glossary.md
│ ├── index.md
│ └── troubleshooting.md
├── template stuff/
│ ├── admonitions.md
│ ├── code-examples.md
│ ├── content-tabs.md
│ ├── diagram-examples.md
│ └── template-index.md
├── venv/
├── .gitignore
├── mkdocs.yml
└── README.md

## Getting Started

### Prerequisites

Python 3.x
pip (Python package manager)

### Installation

Clone the repository:

```
git clone <your-repo-url>
cd <your-repo-name>
```

Install dependencies:

pip install mkdocs-material pymdown-extensions

### Running the Documentation Locally

To preview the site locally:

`mkdocs serve`

Then open your browser and go to:

http://127.0.0.1:8000

## Deployment
This project uses GitHub Actions for automatic deployment.

On push to main or master, the site is deployed using:

`mkdocs gh-deploy --force`

The live site is hosted on GitHub Pages.

## Documentation Contents

The guide includes:

Home page
Formatting shapes in FigJam
Creating a flowchart in FigJam
Basic formatting in Figma Design
Building a clickable wireframe
Glossary of terms
Troubleshooting guide

## Intended Audience

This documentation is designed for:

Beginner Figma users
Students learning UI/UX basics
Users with little to no prior experience in FigJam or Figma Design

## Authors

Andrew Solomko
David Lukac
