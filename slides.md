---
# try also 'default' to start simple
theme: default
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: ./images/typescript-bg.png
# apply any windi css classes to the current slide
class: 'text-center'
# https://sli.dev/custom/highlighters.html
highlighter: shiki
title: Sharing on Software Engineering
# some information about the slides, markdown enabled
monaco: true
info: |
  ## Sharing on Software Engineering

  A fresh graduate perspective

  by Tong Hui Kang
---


# <span class="golden-font">Sharing</span> on <span class="golden-font"> <br> Software Engineering</span>

A perspective of a fresh graduate<br>Tong Hui Kang

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 p-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    Press Space to advance slides <carbon:arrow-right class="inline"/>
  </span>
</div>


<div
  class="abs-bl m-6 text-sm opacity-50">
  16 July 2021
</div>

<style>
.golden-font {
  background-image: linear-gradient(45deg, #f9b208, #f98404);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>
---

# Personal Introduction
<br>

- SUTD student 2017-2021, Engineering Systems and Design
- AJC student 2013-2014, PCME
  - Project Eureka (STEM Inc predecessor)
    - H3-SRP on Merkle-Damgard construction
    - SSEF Merit with integer factorisation with a sum of four squares
  - See my A level notes on [owlcove.sg](https://owlcove.sg/learn)
- Technical internships
  - 3 companies totalling over 8 months full-time and 8 months part-time
- Interview experience
  - Interviewed with a total of 6 companies
  - Incoming Quora Software Engineer
- See my [resume](https://resume.huikang.dev) and [blog](https://blog.huikang.dev)

---

# Introduction
<br>

- Motivation of this talk
  - To inform what Software Engineering is like
  - To describe the expectations of a technical career
  - To encourage more Singaporeans into Software Engineering
  - To provide advice on how to enter the field of Software Engineering

---


<div style="position: absolute; bottom: 50px;">

# What is <span class="ts-title">Software Engineering</span>?

- What is the appeal of working as a Software Engineer?
- How do Software Engineers work?


</div>

<style>
.ts-title {
  background-image: linear-gradient(45deg, #4EC5D4, #146b8c);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
.golden-font {
  background-image: linear-gradient(45deg, #f9b208, #f98404);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>


---

# Why Computing

<iframe
  width="672" height="378"
  src="https://www.youtube.com/embed/zQSqJRdWY-o?start=0&end=70"
  title="YouTube video player" frameborder="0"
  allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
  allowfullscreen></iframe>


---

# The appeal of working in Software Engineering
<br>

<!-- Here I explain my main motivation for working on Software Engineering. It is easy to explain how doctors, lawyers or teachers add value to society and find joy in the profession. -->

- The power to create
  - Software Engineering is very accessible
  <!-- If you have your computer, you can put together a technical solution at a very low cost. You can get feedback for your creation with stakeholders. -->
  - You can create anything with code
  <!-- If you want to implement an essay completion algorithm, you can follow resources available online to reproduce the results, modify them for your application or improve on the model. -->
- The potential to serve millions or billions
  - A small scale projects can help you and your friends
  - A large scale project (with a company) can help millions or billions
  <!-- It is easy to build something. Getting people to use is hard. Asking people to pay is harder -->
- The increasing importance of software and technology
  - The most popular professions - medicine and law are increasingly using technology
  - Successful companies need to be able to develop and use their own technology
  - One of the highest paid jobs right after undergraduate education is Software Engineering


---

<iframe width=100% height=480
src="https://www.youtube.com/embed/rR4n-0KYeKQ"
title="YouTube video player" frameborder="0"
allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

---


# How Software Engineers collaborate
<br>

Code is usually packed in repositories. How are the repositories are edited

- Identify what to solve
  - Could be adding a simple feature, fixing an issue
  - These plans could be made at the start of the week
- Make a copy of the code (Creating a branch)
- Make edits and save edits (Making commits)
- Propose to merge edits with the main version (Make pull request)
  - Automated tests will be run to check if it breaks any existing tests
- After code review, the proposed edits are approved and combined with the main version (Merge branch), and then deployed live to serve customers (Push to Production)

Takeaway - building software is a **collaborative** and **iterative** process

<!-- It is true that the core of Software Engineering is coding. However, it is not about writing code all day. Here I want to give a perspective on what else goes into writing code. -->

<!-- We see that editing code is a collaborative process. There is a lot of communication and planning involved. This is what differentiate Software Engineers. When you write code, your code needs to be robust and efficient, and it has to be read and edited by future developers. -->

<!-- We also now have some sense of what measures the success of a Software Engineer. The number of lines written does not indicate the productivity or effectiveness of the Software Engineer. -->


---


# Tools used in a technical role
<br>
<!-- Another perspective of Software Engineers I want to provide is based on the tools at the Software Engineer use. -->

- Code editor
  - You definitely need to write code, in some language, the editor helps to make that easier
- Version control (git)
  - You will be collaborating with other people on the code
- Testing
  - Your code needs to work, tests are written to ensure that they work
- Automation
  - Your code needs to be run on certain computers
  - You need to configure the computer you are deploying on, and the deployment process
- Documentation
  - Other people need to understand your code and you need to explain what your code is doing

---

<div style="position: absolute; bottom: 50px;">

# What are the <span class="ts-title">various roles</span> of Software Engineering?

- What are the different types of Software Engineering?
- How do Software Engineer advance in their careers?
- How is the market for Software Engineers like in Singapore?


</div>

<style>
.ts-title {
  background-image: linear-gradient(45deg, #4EC5D4, #146b8c);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
.golden-font {
  background-image: linear-gradient(45deg, #f9b208, #f98404);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---

# Software Engineering specialisations
<br>

Software Engineering basics is required of all engineers, after which they can specialise in
  - Frontend
    - Writes the code that is run on your device (your phone, your computer)
  - Backend
    - Writes the code that is run on the company's computers (storing and searching for information)
  - Data science / Machine learning / Artificial intelligence
    - Research, design and build predictive models
      <!-- - Engineering track and Research track
      - Research roles usually require Masters / PhD and require reading applying research papers -->
  - Data engineer
    - Prepare data for analysis or operations
  - Security engineer
    - Analyse whether the practices adhere to security standards

---

# Alternate classification of Software Engineering
<br>

["Code-first" vs "Product-first"](https://medium.com/@zachlloyd/code-first-vs-product-first-a086d982b7d0)
  - There are programmers who care more about the code
  - There are programmers who care more about the product
  - "[Stop just using “frontend” or “backend” to describe the Engineering you like](https://blog.usejournal.com/stop-just-using-frontend-or-backend-to-describe-the-engineering-you-like-e8c392956ada)"

Takeaways
  - There is diversity in the psychological profiles even within a specialisation
  - Do consider more factors when choosing your career or role


---

# The career ladder of Software Engineering
<br>

Responsibilites and Expectations increase with [each](https://blog.tryexponent.com/learn-software-engineering-levels-to-advance-your-career/) [level](https://www.quora.com/What-is-the-expectation-out-of-each-software-engineering-level-at-Facebook/answer/Dima-Korolev)
- Software Engineer I - Write code and tests with under basic supervision
- Software Engineer II - Make minor and implement design decisions without supervision.
- Senior Software Engineer - Formulate new problems and manage work
- Staff Software Engineer - Lead the engineering team and coordinate with other teams
- Principal Software Engineer - Lead multiple teams and influence business strategy


---

# Companies hiring Software Engineers in Singapore
<br>

Organised by company categories with some examples
- US Big Tech - Google, Facebook, Amazon
- Chinese Big Tech - ByteDance, Tencent, Huawei, Alibaba
- ASEAN Tech Unicorns - Grab, Gojek, Shopee/SEA, Razer
- Banks and Payments - DBS, Citibank, Credit Suisse, JP Morgan, VISA, Mastercard
- Government and related - GovTech, DSTA, DSO, HTX, GIC, Temasek, Singtel/NCS, SIA
- Computer Electronics - NVIDIA, AMD, HP, ASUS
- Tech Consultancies - Hope Technik, Thales, Accenture, 2359 Media
- Business Consultancies - McKinsey, Bain, BCG, EY, KPMG, Deloitte, PwC
- Startups and SMEs - Teralytics, Versafleet, KeyReply, Traverse
- Academia - Research Officers, PhD programmes

Not all companies above offer Software Engineering roles for fresh graduates


---

# The tech landscape in Singapore
<br>

[Graduate starting salaries](https://www.straitstimes.com/singapore/new-graduates-from-4-local-universities-earned-higher-starting-salaries-but-more-working) (Median gross monthly salary)
  - All full-time permament employed undergraduates - $3700
  - Undergraduates who studied information and digital technologies - $4760

Starting salaries for selected companies
  - [DBS](https://www.nodeflair.com/companies/dbs-bank/salaries/software_engineer-junior) - $5500
  - [Shopee](https://nodeflair.com/companies/shopee/salaries/software_engineer-junior) - $6000
  - [Facebook](https://www.levels.fyi/comp.html?track=Software%20Engineer&search=Facebook&region=Singapore&yoestart=0&yoeend=1&yoeradio=New%20Grad) $7600
  - These figures should be considered with the number of available openings

Annual enrollment of computing-related courses
  - [NUS](https://www.nus.edu.sg/registrar/student-records/student-statistics) 1200, [NTU](https://www.ntu.edu.sg/about-us/facts-figures/total-graduate-output---first-degree-higher-degree) 1000, [SMU](https://www.smu.edu.sg/sites/default/files/smu/statistical_highlights_20200914_1.pdf) 250, SUTD 180

<!-- ---

# Addressing the perceptions of Software Engineering
<br>

- Software Engineering is boring
  - Yes it is
- Software can be written by the lowest bidder [TODO]
  - Vietnamese graduate salaries
  - https://www.csc.gov.sg/articles/how-to-build-good-software
- Some day we will not need Software Engineers anymore [TODO]
  - https://www.commitstrip.com/en/2016/08/25/a-very-comprehensive-and-precise-spec/
- The varying Software Engineering environments in Singapore [TODO]
  - http://elijames.org/the-two-tiers-of-singapores-tech-companies/

There is a common perception that engineering in Singapore is undervalued. I would like to provide a better insight into the following points.

I do not know how to present this. -->

---

<div style="position: absolute; bottom: 50px;">

# How do I <span class="ts-title">prepare</span> for a role in Software Engineering?

- How do companies hire?
- What do I need to do to make my job application competitive?
- Where can I start?


</div>

<style>
.ts-title {
  background-image: linear-gradient(45deg, #4EC5D4, #146b8c);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
.golden-font {
  background-image: linear-gradient(45deg, #f9b208, #f98404);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---

# The technical hiring process
<br>

<!-- Here I provide some long-term advice on how to prepare for a technical career. I will address this from the perspective of how hiring manager and recruiters choose among candidates. -->


What I describe here probably applies to many professional roles as well

- The hiring process
  - Resume screen > Online assessments > Technical interviews > Offer
  - You need to get pass the prior stage before going on to the next stage

---

## How to pass the resume filter
<br>

Primary filters
- University name and course
- Internships / Work experience
  <!-- - Usually, your course requires you to complete an internship
  - Internship will be the main differentiator of resumes
  - Recruiters will judge the quality of your internship experience
  - An endorsement by another company is a strong signal to allow your resume through the first filter
  - Spend your first summer doing a technical internship, you need to start somewhere -->

Tie breakers
- Projects, Certifications, Competitions
  <!-- - Project choice
    - Something that interests you, start small and get advice
  - Document and explain the project
    - Writing helps to consolidate what have you learnt
    - Others cannot appreciate if you cannot show and explain what you are doing
  - Maintain a blog -->
  <!-- - Cloud Certificates (GCP, AWS)
  - Security Certificates (OSCP) -->

<br><br>

The state of the market
- Google/Facebook SWE interns - have two prior internships on average
- Tech Unicorns and Banks - more than half of the interns have at least one prior internship

---

## How to pass the online assessment
<br>

- Practise coding questions
  - [Leetcode](https://leetcode.com), [BinarySearch](https://binarysearch.com)
  - Leetcode has weekly contests that simulate how online assessments work

## How to pass the coding interview
<br>

- Mock interviews
  - The best way to practise for an interview is to go for a real interview
  - The next best way is to practise interviewing with your friend



---

<iframe width=100% height=480
src="https://www.youtube.com/embed/pKO9UjSeLew?start=0&end=146"
title="YouTube video player" frameborder="0"
allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

---

# What you can do in university
<br>

- Choose a information systems related course
- Do a technical internship in every summer break if possible
  - Your application is stronger with technical internships
  - Your first internship is unlikely to be prestigious
    - Anywhere with a developer you can learn from is fine
- Take on technical projects
  - Course projects are fine if there is some degree of innovation
  - Document the achievements and summarise what have you learnt
- Practise for online assessments and coding interviews
- Network and share resources
  - For all my internships, referrals helped to get me an interview

---

# What you can do after Junior College
<br>

You might want to find out if coding is for you
- My suggestion is to learn Python and solve simple algorithmic tasks
  - Start with Python which is easy to learn, rather than, say, Android programming
  - [CodeSignal Arcade](https://app.codesignal.com/arcade/python-arcade/meet-python) introduces the concepts step by step, online videos are fine too
- [Coding](https://hackwagon.com/courses/) [bootcamps](https://www.rocketacademy.co/courses/basics) provides supervised education
  - Singaporeans might be eligible for [massive discounts](https://hackwagon.com/data-science-101/#courseSubsidies)

If you like coding and have a lot of time, for example during National Service
- Competitive programming (Leetcode [contests](https://leetcode.com/contest/), [Codeforces](https://codeforces.com/))
  <!-- I should have practised competitive programming in NS -->
- [Kaggle](https://www.kaggle.com/learn) data science courses and competitions
- Build coding projects (start simple and seek advice)

---

# What if you need to code for your research project
<br>

If you need to write code for a JC science project (presumably done over the December break)

- Consider if you need to write code
  - Basic data analysis (e.g. R-value) could be done on Excel
  - Algorithms could be done with code
- Choose Python if possible
  - It is easy to pick up and learn
- How to fix your code
  - Start with a working copy
  - Edit it bit by bit and ensuring that it still works
- Seek advice - I am open to providing advice

---

# This could have been done with code
<br>

Fun fact - I implemented my integer factorisation algorithm on Excel, should have done it in Python

![algorithm](https://i.imgur.com/SeCDkiC.png)

---

# My Story
<br>

- Admission into SUTD with no prior coding experience
- Participated in a [Hackathon](https://www.straitstimes.com/singapore/tertiary-students-come-up-with-innovative-ideas-to-tackle-fake-news) on Fake News
  - where I found my interest in natural language processing
- [Internships](https://blog.huikang.dev/2021/05/14/internship-reflections.html)
  - where I found my strong preference for a technical role
  - where I understood how Software Engineering is actually like
- Competitive programming
  - did weekly Leetcode contests, for fun
  - currently [top 6000](https://codeforces.com/profile/huikang) on Codeforces
- Quora Programming Contest 2021 - won a [T-shirt](https://challenge.quora.com/Division-2-End-Final-Results), interview and offer

---

# Whether Software Engineering is for you

<iframe
  width="672" height="378"
  src="https://www.youtube.com/embed/zQSqJRdWY-o?start=214&end=296"
  title="YouTube video player" frameborder="0"
  allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
  allowfullscreen></iframe>

---

<div style="position: absolute; bottom: 50px;">

# <span class="ts-title">Summary</span>

- Software Engineering is cool and rewarding
- What Software Engineering actually is
- Steps to prepare for a Software Engineering career


</div>

<style>
.ts-title {
  background-image: linear-gradient(45deg, #4EC5D4, #146b8c);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
.golden-font {
  background-image: linear-gradient(45deg, #f9b208, #f98404);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>


---
layout: center
class: text-center
---

# Thank You

[These slides](https://tonghuikang.github.io/swe-sharing), its [source code](https://github.com/tonghuikang/swe-sharing) and [slide template](https://github.com/dizys/talk-type-system-in-typescript)


---

# Readings on Software Engineering
<br>

[How to Build Good Software](https://www.csc.gov.sg/articles/how-to-build-good-software) by Li Hongyi

[The Two Tiers of Singapore's tech companies](http://elijames.org/the-two-tiers-of-singapores-tech-companies/) by Eli James

[Software Engineering at Google](https://abseil.io/resources/swe_at_google.2.pdf) by Titus Winters et. al.

[Code-first vs. Product-first](https://medium.com/@zachlloyd/code-first-vs-product-first-a086d982b7d0) by Zach Lloyd

[Stop just using “Frontend” or “Backend” to describe the Engineering you like](https://medium.com/@michlim97/stop-just-using-frontend-or-backend-to-describe-the-engineering-you-like-e8c392956ada) by Michelle Lim


---

# Readings on SWE career preparation
<br>

[Evolution of Resumes - My journey through NUS Computer Science](https://luyangkenneth.github.io/evolution-of-resumes/) by Kenneth Lu

[Tech Interview Handbook](https://github.com/yangshun/tech-interview-handbook) by Yangshun Tay et. al.

[Frontend Interview Handbook](https://github.com/yangshun/front-end-interview-handbook) by Yangshun Tay et. al.

[Software Engineering 2020 Class Profile of University of Waterloo](https://uw-se-2020-class-profile.github.io/profile.pdf) by Holly Oegema et. al.

<!--
# Interesting projects
<br>

- Timetable scheduling [TODO]
  - Given constraints, suggest a timetable for the school
- Game AI playing Snake [TODO]
  - Train an AI to play snake -->

<!-- To add images, hopefully my friends can build the Snake game in time -->

