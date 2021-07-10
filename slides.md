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
    - H3-SRP Merit on Merkle-Damgard construction
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
  - To provide advice on how get started in coding

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

- The power to <span class="golden-font">create</span>
  - Software Engineering is very accessible
  <!-- If you have your computer, you can put together a technical solution at a very low cost. You can get feedback for your creation with stakeholders. -->
  - You can create anything with code
  <!-- If you want to implement an essay completion algorithm, you can follow resources available online to reproduce the results, modify them for your application or improve on the model. -->

- The potential to <span class="golden-font">serve</span> millions or billions
  - A small scale projects can help you and your friends
  - A large scale project (with a company) can help millions or billions
  <!-- It is easy to build something. Getting people to use is hard. Asking people to pay is harder -->

- The increasing <span class="golden-font">importance</span> of software and technology
  - The most popular professions - medicine and law are increasingly using technology
  - Successful companies need to be able to develop and use their own technology
  - One of the highest paid jobs right after undergraduate education is Software Engineering


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

<iframe width=100% height=480
src="https://www.youtube.com/embed/rR4n-0KYeKQ"
title="YouTube video player" frameborder="0"
allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

---


# How Software Engineers collaborate
<br>

What we see in the skit
- Version control
- Code testing
- Code review process
- Lack of full understanding of the codebase

Building software is a <span class="golden-font">collaborative</span> and <span class="golden-font">iterative</span> process

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

<!--
Code is usually packed in repositories. How are the repositories are edited

- Identify what to solve
  - Could be adding a simple feature, fixing an issue
  - These plans could be made at the start of the week
- Make a copy of the code (Creating a branch)
- Make edits and save edits (Making commits)
- Propose to merge edits with the main version (Make pull request)
  - Automated tests will be run to check if it breaks any existing tests
- After code review, the proposed edits are approved and combined with the main version (Merge branch), and then deployed live to serve customers (Push to Production) -->


<!-- It is true that the core of Software Engineering is coding. However, it is not about writing code all day. Here I want to give a perspective on what else goes into writing code. -->

<!-- We see that editing code is a collaborative process. There is a lot of communication and planning involved. This is what differentiate Software Engineers. When you write code, your code needs to be robust and efficient, and it has to be read and edited by future developers. -->

<!-- We also now have some sense of what measures the success of a Software Engineer. The number of lines written does not indicate the productivity or effectiveness of the Software Engineer. -->


<!-- # Tools used in a technical role -->
<!-- Another perspective of Software Engineers I want to provide is based on the tools at the Software Engineer use. -->
<!--
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
  - Other people need to understand your code and you need to explain what your code is doing -->

---

# The challenges in Software Engineering
<br>

Software Engineering is not only about writing code.
Software Engineers need to [consider](http://codesqueeze.com/the-7-software-ilities-you-need-to-know/) the following

<div grid="~ cols-2 gap-4">
<div>

## Usability

Can users use the product intuitively?

## Scalability

How many users can you serve at a time?

## Reliability

How does your system prevent failure?

</div>
<div>

## Maintainability

Can the future team add modifications easily?

## Security

Is unauthorised access prevented?


</div>
</div>



---

# Some perspectives on Software Engineering
<br>
<br>


> 'Software Engineering' encompasses not just the act of writing code, but all of the tools and processes an organization uses to build and maintain that code over time

\- from the book [Software Engineering at Google](https://abseil.io/resources/swe_at_google.2.pdf)

<br>
<br>

> Software is about developing knowledge more than writing code

> Software should be treated not as a static product, but as a living manifestation of the development team’s collective understanding

\- from [How to Build Good Software](https://www.csc.gov.sg/articles/how-to-build-good-software) by Li Hongyi for Civil Service College




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

<div grid="~ cols-2 gap-4">
<div>

## Frontend Engineer

Implement user inferface

## Backend Engineer

Implement databases

## Reliability Engineer

Manages the code deployment process and ensure that product is working

</div>
<div>

## Data Scientist / ML Engineer

Research, design and build predictive models

## Data Engineer

Stream data for operations or analysis

## Security Analyst

Ensure that the product is protected from unauthorised access


</div>
</div>


---


# Alternate classification of Software Engineering
<br>

["Code-first" vs "Product-first"](https://medium.com/@zachlloyd/code-first-vs-product-first-a086d982b7d0)
  - There are programmers who care more about the code
  - There are programmers who care more about the product
  - "[Stop just using “frontend” or “backend” to describe the Engineering you like](https://blog.usejournal.com/stop-just-using-frontend-or-backend-to-describe-the-engineering-you-like-e8c392956ada)"

<br>

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


Usually Software Engineers are managed by more senior Software Engineers

---

# Companies hiring Software Engineers in Singapore
<br>

Organised by company categories with some examples
- US Big Tech - Google, Facebook, Amazon
- Chinese Big Tech - ByteDance, Tencent, Huawei, Alibaba
- ASEAN Tech Unicorns - Grab, Gojek, Shopee/SEA, Razer
- Banks and Payments - DBS, Citibank, Credit Suisse, JP Morgan, VISA, Mastercard, Stripe, Paypal
- Government and related - GovTech, DSTA, DSO, HTX, GIC, Temasek, Singtel/NCS, SIA
- Computer Electronics - NVIDIA, AMD, HP, ASUS
- Tech Consultancies - Hope Technik, Thales, Accenture, 2359 Media
- Business Consultancies - McKinsey, Bain, BCG, EY, KPMG, Deloitte, PwC
- Startups and SMEs - Teralytics, Versafleet, KeyReply, Traverse
- Academia - Research Officers, PhD programmes

Not all companies above offer Software Engineering roles for fresh graduates in Singapore


---

# The tech landscape in Singapore
<br>

[Graduate starting salaries](https://www.straitstimes.com/singapore/new-graduates-from-4-local-universities-earned-higher-starting-salaries-but-more-working) (Median gross monthly salary)
  - All full-time permament employed undergraduates - $3700
  - Undergraduates who studied information and digital technologies - <span class="golden-font">$4760</span>

<br>

Annual enrollment of computing-related courses
  - [NUS](https://www.nus.edu.sg/registrar/student-records/student-statistics) 1200, [NTU](https://www.ntu.edu.sg/about-us/facts-figures/total-graduate-output---first-degree-higher-degree) 1000, [SMU](https://www.smu.edu.sg/sites/default/files/smu/statistical_highlights_20200914_1.pdf) 250, SUTD 180, [SIT](https://www.singaporetech.edu.sg/sites/default/files/2021-01/SIT_Indicative_Grade_Profile_0.pdf) 350
  - Do your research on their admission criteria

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

# The tech landscape in Singapore
<br>

Starting salaries for selected companies
  - [DBS](https://www.nodeflair.com/companies/dbs-bank/salaries/software_engineer-junior) - $5500
  - [Shopee](https://nodeflair.com/companies/shopee/salaries/software_engineer-junior) - $6000
  - [Facebook](https://www.levels.fyi/comp.html?track=Software%20Engineer&search=Facebook&region=Singapore&yoestart=0&yoeend=1&yoeradio=New%20Grad) - $8400

<br>

<span class="golden-font">Caveats</span> to the figures above
- These figures should be considered with the number of available openings
- Google/Facebook SWE interns - have two prior internships on average
- Tech Unicorns and Banks SWE interns - more than half have at least one prior internship


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

# Is Software Engineering <span class="ts-title">for me</span>?

- How should I try out coding?
- Am I a good fit for a Software Engineer?

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

# My Story
<br>

- Admission into SUTD with no prior coding experience
  - tried to follow tutorials for Andriod programming during NS but got nowhere
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

# What you can do after Junior College
<br>

How to get started with coding
- [Coding](https://hackwagon.com/courses/) [bootcamps](https://www.rocketacademy.co/courses/basics) provide supervised education
  - Singaporeans might be eligible for [massive discounts](https://hackwagon.com/data-science-101/#courseSubsidies)
- If you want to self-learn, probably start with Python
  - [CodeSignal Arcade](https://app.codesignal.com/arcade/python-arcade/meet-python) introduces the Python concepts step by step

<br>

If you like coding and have a lot of time, for example during National Service
- Competitive programming (Leetcode [contests](https://leetcode.com/contest/), [Codeforces](https://codeforces.com/))
  <!-- I should have practised competitive programming in NS -->
- [Kaggle](https://www.kaggle.com/learn) data science tutorials and competitions
- Build coding projects (start simple and seek advice)

---

# What if you need to code for your research project
<br>

If you need to write code for a JC science project (presumably done over the December break)

- Consider the algorithms you want to implement with code
- Choose Python if possible
  - It is easy to pick up and learn
- How to fix your code
  - Start with a working copy
  - Edit it bit by bit for your application while ensuring that it still works
- Seek <span class="golden-font">advice</span> - ask your mentor, but I can try to advise

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

# This could have been done with code
<br>

I implemented my integer factorisation algorithm on Excel for SSEF, should have done it in Python

![algorithm](https://i.imgur.com/SeCDkiC.png)

---

<div style="position: absolute; bottom: 50px;">

# <span class="ts-title">Summary</span>

- Software Engineering is cool and rewarding
- What Software Engineering actually is
- How to get started with coding


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

[Software Engineering at Google](https://abseil.io/resources/swe_at_google.2.pdf) by Titus Winters et. al.

[The Two Tiers of Singapore's Tech Companies](http://elijames.org/the-two-tiers-of-singapores-tech-companies/) by Eli James

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

