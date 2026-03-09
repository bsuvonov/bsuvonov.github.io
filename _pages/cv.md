---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Download
======
- [Download PDF CV](/files/Bunyod_Suvonov_CV_SJTU.pdf)

Education
======
- B.E. in Electrical and Computer Engineering, Minor in Computer Science
  - University of Michigan - Shanghai Jiao Tong University Joint Institute
  - September 2022 - August 2026 (expected)
  - SJTU First-Class Scholarship

Work experience
======
- Software Engineer Intern, Dlang.ai (Shanghai), December 2024 - April 2025
  - Built NL2SQL workflow with Streamlit UI, SQLAlchemy ORM, and tool-using agent components.
  - Implemented human-in-the-loop and memory features for query workflows.
  - Set up and maintained Apache Doris and MySQL databases for remote querying.

Research
======
- Research at RAP-Lab, IBDSys, and IPADS.
- Topics include LLM agent memory, secure decentralized LLM multi-agent systems, and robotics planning.

Skills
======
- Programming: C/C++, Go, Python, JavaScript, SQL, Shell
- Tools and Frameworks: Docker, Kubernetes, Hadoop ecosystem, Spark, Drill, LangGraph, ROS, Unity, Linux, Git, Vim
- Languages: Uzbek (native), English (advanced), Chinese (intermediate), Russian (intermediate)

Projects
======
- Find Next Hit: big data recommendation system on the Million Song Dataset.
  - Built SQL analytics on a four-node Drill cluster.
  - Implemented MapReduce-based recommendation and achieved 2.7x parallel speedup with Spark.
- LemonDB: multi-threaded C++20 SQL database.
  - Implemented parser and execution pipeline over in-memory tables.
  - Achieved over 2x throughput with worker-thread scheduling and semaphore-based operation control.

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
- Mentor for Teaching Assistants, Center for Learning and Teaching
