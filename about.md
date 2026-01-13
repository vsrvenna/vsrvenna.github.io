---
layout: page
title: About
---

I'm a Master's student in Electrical and Computer Engineering at the University of Southern California, specializing in Machine Learning and Data Science. My research sits at the intersection of neurotechnology, biosignal processing, and artificial intelligence.

Currently, I work as a graduate researcher at USC's COOR Lab and the Information Sciences Institute, where I develop ML tools for clinical biomechanics and research automation. My work focuses on making complex data analysis accessible and practical for real-world applications.

## Education

**University of Southern California**
M.S. in Electrical and Computer Engineering (ML/DS Track)
Aug 2024 - May 2026 (expected) | Los Angeles, CA

**Indian Institute of Information Technology Sri City**
B.Tech (Honours) in Electronics and Communications Engineering
Aug 2020 - May 2024 | Sri City, India

## Experience

{% for exp in site.data.experience %}
**{{ exp.organization }}**
{{ exp.role }}
{{ exp.period }}
{{ exp.description }}

{% endfor %}

## Publications

{% for pub in site.data.publications %}
**{{ pub.title }}**
{{ pub.authors }}
*{{ pub.venue }}* ({{ pub.year }})

{% endfor %}

## Projects

{% for project in site.data.projects %}
**{{ project.title }}**
{{ project.institution }} | {{ project.date }}
{{ project.description }}

{% endfor %}

## Technical Skills

**Programming:** Python, C++, MATLAB, SQL, R

**ML & Deep Learning:** PyTorch, Transformers, State-Space Models, Transfer Learning, RAG

**Tools & Frameworks:** scikit-learn, FastAPI, Docker, MLflow, W&B, Git/GitHub

**Biomedical & Neuroimaging:** BIDS, FSL, sEMG Processing, Motion Capture, HIPAA Compliance

## Beyond Research

When I'm not working on research, I enjoy exploring new technologies, contributing to open-source projects, and staying active. I'm particularly interested in the potential of AI to transform healthcare and make advanced medical technologies more accessible.

I'm currently seeking **ML engineering internships for Summer 2026**, particularly in neurotechnology, health tech, or research-focused roles.

## Contact

Email: [{{ site.author.email }}](mailto:{{ site.author.email }})
GitHub: [{{ site.author.github }}](https://github.com/{{ site.author.github }})
LinkedIn: [{{ site.author.linkedin }}](https://linkedin.com/in/{{ site.author.linkedin }})
Scholar: [Google Scholar](https://scholar.google.com/citations?user={{ site.author.scholar }})
