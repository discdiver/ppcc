<!--
author:   Prefect

email:    jeff@prefect.io

version:  0.0.1

language: en

narrator: US English Female

comment:  Intro to Prefect 

link:     https://cdn.jsdelivr.net/chartist.js/latest/chartist.min.css

script:   https://cdn.jsdelivr.net/chartist.js/latest/chartist.min.js

-->

# Prefect Practioner Certification Course

Prefect Basics for Workflow Authors

## Introduction

Prefect helps teams govern compute infrastructure and understand the health of workflows across disparate systems. This brings efficiency, cost savings, and improved velocity to data teams by bringing order to chaos.

The open source [prefect Python library](https://github.com/PrefectHQ/prefect) provides everything for individuals to get started. For organizations that need organization management capabilities and who don't want to deal with hosting, [Prefect Cloud](https://app.prefect.cloud) solves your issues. Prefect Cloud also provides hosted infrastructure, incident management, and the ability to take action based on aggregate workflow health metrics.

In this introductory course you'll learn how to create workflows with Prefect. This course is aimed at data professionals who want to learn how to use Prefect to create, schedule, and monitor workflows.

Upon successful completion of the course you will receive the Prefect Practitioner Certification! You can add this digital badge to your LinkedIn profile and let the world know that you're up on the hottest ways to orchestrate your workflows! 🎉

### Structure

The course consists of the following TK modules.

1. Welcome and Setup (⭐️ You are here)
2. Flows and Tasks - flow runs
 a Logging - log_prints, logging
 b Retries,  Timeouts, Parameters
 c  Results, Caching, Artifacts
. Scheduling and Running Flows -  .serve, deployments
. Running Serverless Workflows on Prefect Cloud - .deploy, workpools, code storage
. Intro to Events and Automations - automations, triggers, actions, blocks
. HITL - pause for input, variables
. Running Serverless Workflows in Your Cloud Provider - ECS push pool
. Running Workflows with Workers - Docker
. Run a deployment in code - run_deployment
. Using info about running workflows - runtime

API - Prefect client
Capstone

 Next Steps - Where to go for Event Driven workfolws, getting your certificate, TK, Terraform Provider, GHA, Helm Chart, prefect.yaml

Throughout the course, you'll have hands-on challenges to complete with Python code and the Prefect Cloud UI. Each of the modules will contain examples that demonstrate how to accomplish a goal. Then you'll build your own in the project at the end of each module.

Many modules will also contain a check for understanding to help you cement your learning. Hands-on practice and quizzes are associated with improved learning outcomes compared to just reading along, so make sure you lean in. 🧠

This course will give you the ability to orchestrate and observe your event-driven workflows with confidence!

### Prerequisites

This course requires just a few prerequisites for success:

- Basic Python skills. If you can write and call a function, you're good to go!
- A computer that can connect to the internet, with Python 3.8 or newer installed, and the ability to install Python packages.
- The ability to connect to Prefect Cloud.
- A GitHub account.

If you've got those capabilities, this course is for you!

### Quick setup

Let's get you set up for success!

The following instructions should work for most participants. If you're newer to Python or get stuck at any point, check out the detailed tech setup instructions in the next lesson.

1. Log in to your account on Prefect Cloud at [app.prefect.cloud](https://app.prefect.cloud). If you don't already have an account, sign up for a forever free account.
2. Install an updated version of the prefect Python package in your environment. Most folks just need to run the following in a virtual environment:

```bash
pip install -U prefect
```

See the installation [docs](docs.prefect.io/getting-started//installation) if you need help.

3. Authenticate your command line to Prefect Cloud. If you are new to Prefect, you can just run the following command from your CLI to authenticate:

```bash
prefect cloud login
```

**Select Log in with a web browser** and press **Enter**. If you have an existing Prefect configuration or aren't able to use a web browser to authenticate, check out these slides on working with your Prefect settings and authenticating to Prefect Cloud:

Profiles & Connect to Prefect Cloud.pdf.

Again, if you're newer to Python or get stuck at any point, check out the detailed tech setup instructions in the next lesson. 🙂

TK

### Resources

Explore the docs at [docs.prefect.io](https://docs.prefect.io).

Check out the source code in the [GitHub repo](https://github.com/PrefectHQ/prefect), report bugs, request new features, and give the repo a star! ⭐️

The course repository with starter code is at TK You'll find code samples and exercise solutions there. We suggest forking it.🍴

Onward to Module 2, where we'll start building workflows and learning Prefect concepts!

## Quizzes

### A Textquiz

What did the **fish** say when he hit a **concrete wall**?

    [[dam]]

### Multiple Choice

Just add as many points as you wish:

    [[X]] Only the **X** marks the correct point.
    [[ ]] Empty ones are wrong.
    [[X]] ...

### Single Choice

Just add as many points as you wish:

    [( )] ...
    [(X)] <-- Only the **X** is allowed.
    [( )] ...
