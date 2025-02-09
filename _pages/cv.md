---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}
[Download Here](https://nguu0123.github.io/files/Anh-Dung_Nguyeb_CV.pdf)

## Education **Aalto University**

_MS in Computer Science - Algorithms, Logic, and Computation track_  
_Sept 2023 – June 2025_

- GPA: 4.63/5.0
- Coursework: Programming Parallel Computer, Programming Parallel Supercomputer, Big Data Platforms, Operating Systems

**Aalto University**  
_BS in Data Science_  
_Sept 2020 – June 2023_

- GPA: 4.61/5.0 (Graduated with Honors)
- Coursework: Software Engineering, Full Stack Web Development, Methods of Data Mining, Machine Learning: Supervised Methods

## Work Experience

**Research Assistant**  
_Aalto University, Department of Computer Science – Espoo, Finland_  
_Apr 2024 – Present_

- Focused on Machine Learning engineering in IoT-Edge-Cloud environments and big data problems in HPC.
- Improved group prototype with GitHub Actions for CI, basic testing with Pytest and tox, ruff linter, and rye for project management.
- Maintained test bed consisting of 23 edge devices and 3 servers with Ansible.
- Projects and research papers:
  - **Supporting Opportunistic Data Operations for Data-Intensive Computational Applications** (to appear in BPOD - IEEE Big Data 2024)
  - **Novel techniques in orchestrating ML models in cloud-edge continuum**
- Experience with:
  - Edge devices: Coral Dev Board, Raspberry Pi 4B/5, Jetson Nano/Xavier/Orin.
  - ML frameworks and serving: PyCoral/TFLite, ONNXRuntime with CUDA and CPU.
  - Vision model quantization with ONNX.
  - Orchestration frameworks: K8s, MicroK8s, k3s.
  - HPC systems: LUMI, Puhti, Mahti, Aalto Triton.

**Graduate Analyst Developer**  
_FNZ Group – Helsinki, Finland_  
_Nov 2022 – Oct 2023_

- Developed new features and fixed bugs in leading wealth management platforms used by top Finnish and UK financial institutions.
- Maintained and implemented new end-to-end tests using Cucumber, Selenium, and company test framework.
- Optimized SQL statements, stored procedures, and views to meet strict production requirements.
- Technologies used:
  - ASP.NET WebForms, MVC, Web API, GraphQL, and React.
  - C#, VB.NET (legacy code), JavaScript.
  - Microsoft SQL Server.
  - TeamCity, Jira, Confluence.

## Skills

- Machine Learning Engineering
- Edge Computing & HPC
- Full Stack Development
- CI/CD & Automation
- SQL Optimization
- Cloud & Container Orchestration

## Publications

<ul>{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>
