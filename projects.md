---
layout: page
title: Projects
permalink: /projects/
---

## Project Portfolio 

[General Web App](#general-web-application) || [Learning Environments](#learning-environments) || [Language Pedagogy/Resource](#language-pedagogyresource-applications)

The following summary contains links to applications I have developed or have co-developed either as an employee at the Center for Language & Technology, as an independent consultant, or as a technology consultant for the National Foreign Language Resource Center. Most projects have a corresponding github repository.

### General Web Application

---

#### National Foreign Language Resource Center website
Django based site that serves as the primary information/project portal for programs and initiatives sponsored by the NFLRC. The current version has been in production since 2014 and is under continuous development.

**URL:** [http://nflrc.hawaii.edu](http://nflrc.hawaii.edu)
**Repository:** [https://github.com/llcit/nflrcpydev](https://github.com/llcit/nflrcpydev)
**Components:** Django web application framework, python, apache2, PostgreSQL, HTML, CSS, JavaScript
**Key features:** custom search indexing and engine (Elasticsearch)

### Learning Environments

---

#### The GGV Interactive LMS
A Django-based learning management system designed to allow users access to online learning materials (worksheets, HTML 5 slide presentations, video) in preparation for the GED test. The current version has been in production since 2014 and is under continuous development. Figures 1 and 2 below provide sample screenshots of the system.

**URL:** [http://www.ggvinteractive.com](http://www.ggvinteractive.com)
**Repository:** [https://github.com/anidem/ggv-py](https://github.com/anidem/ggv-py)
**Components:** Django web application framework, python, apache2, PostgreSQL, HTML, CSS, JavaScript, Google authentication services
**Key features:** bilingual content and user interface (span/eng), instructor management system, chat interface for online tutors, pretest/posttest scoring and recommendation system, mobile compatible, student progress tracker


![image-title-here](/assets/ggv-span-sample.png){:class="img-responsive"}
*Figure 1. GGV Interactive Module Page (Spanish)*

![image-title-here](/assets/ggv-ws-sample.png){:class="img-responsive"}
*Figure 2. GGV Interactive Worksheet Question (Spanish)*


### Language Pedagogy/Resource Applications
---

The following applications were developed as sponsored projects of the NFLRC.

#### Project-Based Language Learning Repository
A web repository of project-based learning modules. System supports the creation and management of modules. In production since 2015.

**URL:** [http://nflrc.hawaii.edu/pebbles](http://nflrc.hawaii.edu/pebbles )
**Repository:** [https://github.com/llcit/nflrc-pbllrepo-dev](https://github.com/llcit/nflrc-pbllrepo-dev)
**Components:** Django web application framework, python, apache2, PostgreSQL, HTML, CSS, JavaScript, Google authentication
**Key features:** custom search indexing and engine (Elasticsearch)

#### Fundamentals of Project-Based Language Learning
A Django-based web application designed to support the NFLRC’s Fundamentals of PBLL Online Institute series from 2014 through 2018. The site design was inspired by and similarly organized to the TedED online learning resource. Figure 3 is a sample view of a Lesson. The application is currently being repurposed for another project similar in design.

**URL:** [http://nflrc.hawaii.edu/pbll-modules-2018/](http://nflrc.hawaii.edu/pbll-modules-2018/)
**Repository:** [https://github.com/llcit/nflrc-pbll-dev](https://github.com/llcit/nflrc-pbll-dev)
**Components:** Django web application framework, python, apache2, PostgreSQL, HTML, CSS, JavaScript, Google authentication
**Key features:** Discussion threads, rich-content editing


![image-title-here](/assets/pbll-lesson-sample.png){:class="img-responsive"}
*Figure 3. A Lesson in the Online Institute system.*

#### Language, Learning & Technology Journal Website

A Django-based web application designed as a user-friendly front-end to the LLT journal archives. The application is a metadata harvester from the corresponding repository hosted at the UH library’s D-Space implementation – Scholarspace. Active development and production since 2015. Future work targeted at semantic analysis of archives to allow smart search of resources.

**URL:** [https://www.lltjournal.org](https://www.lltjournal.org)
**Repository:** [https://github.com/llcit/nflrc-llt-dev](https://github.com/llcit/nflrc-llt-dev)
**Components:** Django web application framework, python, apache2, PostgreSQL, HTML, CSS, JavaScript, Open Access Initiative (OAI-PMH) protocol
**Key features:** custom search indexing and engine (Elasticsearch), OAI-PMH client to UH Scholarspace repository



