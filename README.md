# ML Postbacc Program: Machine Learning on HPC

A 9-week machine learning program (Weeks 4 to 12 of the MSCF summer postbacc cohort) that takes students from the machine learning workflow to deploying models on production HPC, finishing with an individual capstone project and research poster.

> The program does not stop at ML concepts. Students run training jobs on Vista GPUs, containerize models, and present capstone results as a research poster.

## What This Is

A hands-on machine learning program for post-baccalaureate students. The first three weeks of the cohort are a Python Bootcamp (delivered separately), so students arrive at Week 4 able to write Python, work with data, and log in to Vista. From there, the program moves through the full ML workflow and into an individual capstone on real HPC infrastructure (Vista at TACC).

| Phase | Weeks | What You Walk Away With |
|---|---|---|
| ML Training | 4 to 9 | Models built, evaluated, tuned, and deployed; deep learning on GPUs |
| Capstone | 10 to 12 | An individual project and a research poster, presented at the program close |

## How We Work

We set up a real development workflow on day one and use it all summer:

- An editor with AI built in: VS Code or Antigravity
- Git from day one, with the GitHub CLI authenticated (`gh auth login`)
- Authenticated access to Vista (TACC) for running real jobs
- Everything lives in Git repositories for the rest of the summer

This mirrors the workflow used in the NAIRR Research Accelerator.

## Who This Is For

Post-baccalaureate students preparing for graduate study or industry careers in computational fields. The Python Bootcamp (Weeks 1 to 3) is the prerequisite; this program covers Weeks 4 to 12.

## The Site

This repository publishes the program site with GitHub Pages (Jekyll, in `docs/`):

- **Schedule** pages: day-by-day plans for Weeks 4 to 9 and 10 to 12
- **Curriculum** pages: per-topic references for the ML training and Capstone phases

Live site: https://ashleyscruse.github.io/mscf-ml-postbacc/

## Running Locally

```bash
cd docs
bundle install
bundle exec jekyll serve
```

## Author

**Ashley Scruse, Ph.D.**
Deputy Director, Morehouse Supercomputing Facility
[ashley.scruse@morehouse.edu](mailto:ashley.scruse@morehouse.edu)
