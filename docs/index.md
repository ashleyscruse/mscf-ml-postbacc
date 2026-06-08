# ML Postbacc Program: Machine Learning on HPC

A 9-week machine learning program (Weeks 4 to 12 of the MSCF summer postbacc cohort) that takes students from the machine learning workflow to deploying models on production HPC, finishing with an individual capstone project and research poster.

## Program at a Glance

| | |
|---|---|
| **Dates** | June 22 to August 21, 2026 |
| **Format** | Mon/Wed virtual, Tue/Thu in-person, Fri office hours |
| **Hours** | 10:00 AM to 4:00 PM (lunch 12:00 to 1:00) |
| **HPC system** | Vista (TACC) |
| **Capstone** | Individual projects (no teams) |

## Prerequisite

The first three weeks of the cohort are a **Python Bootcamp**, delivered separately, covering Python, data analysis, and TACC/HPC fundamentals. Students arrive at Week 4 already able to write Python, work with data in Pandas and NumPy, and log in to Vista.

## How We Work

We do not work out of notebooks on a laptop. From the start we set up a real development workflow and use it all summer:

- **An editor with AI built in:** VS Code or Antigravity
- **Git from day one:** every project lives in a repository
- **GitHub CLI authenticated** (`gh auth login`) so pushing and pulling just works
- **Authenticated access to HPC:** log in to Vista and run real jobs
- **We work out of repos for the rest of the summer.** Your code, your experiments, and your capstone all live in version control, on your laptop and on Vista.

This is the same way we work in the NAIRR Research Accelerator: set the workspace up once, then let the tools do the heavy lifting.

## The Arc

| Phase | Weeks | Dates | Focus |
|---|---|---|---|
| **ML Training** | 4 to 9 | Jun 22 to Jul 31 | Supervised and unsupervised learning, evaluation, deep learning, deployment |
| **Capstone** | 10 to 12 | Aug 3 to Aug 21 | Individual project from data to model to poster presentation |

## Weekly Schedule

| Week | Theme | Milestone |
|---|---|---|
| 4 | Introduction to machine learning | Capstone preview |
| 5 | Supervised learning | Hackathon: build best classifier |
| 6 | Unsupervised learning + project overview | Capstone project overview |
| 7 | Model evaluation and optimization | Hackathon: optimize a model |
| 8 | Deep learning | Project proposal due (Jul 23); Hackathon |
| 9 | Model deployment | Project check-in 1: data processing |
| 10 | Capstone work | Project check-in 2: ML model |
| 11 | Capstone work | Project check-in 3: tuning/deployment; poster draft due (Aug 13) |
| 12 | Final poster presentations and closing | Final posters (Aug 18); closing ceremony (Aug 20) |

Full day-by-day schedules:

- [Weeks 4 to 9: ML Training](./Schedule/weeks-4-9)
- [Weeks 10 to 12: Capstone](./Schedule/weeks-10-12)

## What You Will Learn

**Machine learning.** The full scikit-learn workflow: classification and regression, clustering and dimensionality reduction, cross-validation, and hyperparameter tuning.

**Deep learning.** Neural network fundamentals, TensorFlow/Keras, CNNs for image classification, and an introduction to PyTorch, run on Vista GPUs.

**Deployment.** Saving and serving models with Flask and FastAPI, containerizing with Docker, and deploying to the cloud.

**ML on HPC.** Running training and tuning jobs on Vista, using GPUs for deep learning, and parallelizing hyperparameter search.

## Hands-On Format

The ML phase is built around active work, not lecture:

- **3 hackathons** (Weeks 5, 7, 8): supervised learning, model optimization, and deep learning
- **Paired programming** sessions most in-person weeks
- **Breakout challenges**, bug hunts, code reviews, and dataset stations
- **Capstone**: an individual project taken from data through model, evaluation, deployment, and a research poster

## Setup Checklist

Have these ready so we can start working out of repos right away:

- [ ] Install an editor: [VS Code](https://code.visualstudio.com/) or [Antigravity](https://antigravity.google/)
- [ ] Install [Git](https://git-scm.com/downloads)
- [ ] Create a [GitHub account](https://github.com) and authenticate the [GitHub CLI](https://cli.github.com/) (`gh auth login`)
- [ ] Install [Claude Code](https://claude.ai/code) (or your AI coding tool of choice)
- [ ] A [TACC account](https://portal.tacc.utexas.edu/account-request) with MFA, and confirm you can log in to Vista

## Resources

- [NAIRR Pilot](https://nairrpilot.org/) (capstone datasets and compute)
- [TACC Vista User Guide](https://docs.tacc.utexas.edu/hpc/vista/)
- [Launching Jupyter on Vista (MSCF)](https://morehouse-supercomputing.github.io/jupyter-on-tapis/)

## Author

**Ashley Scruse, Ph.D.**
Deputy Director, Morehouse Supercomputing Facility
[ashley.scruse@morehouse.edu](mailto:ashley.scruse@morehouse.edu)
