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

- AJC student 2013-2014, PCME
  - Project Eureka (STEM Inc predecessor)
    - H3-SRP Merit on Merkle-Damgard construction
    - SSEF Merit with integer factorisation with a sum of four squares
  - See my A level notes on [owlcove.sg](https://owlcove.sg/learn)
- SUTD student 2017-2021, Engineering Systems and Design
- Technical internships
  - 3 companies totalling over 8 months full-time and 8 months part-time
- Interview experience
  - Interviewed with a total of 6 companies
  - Incoming Quora Software Engineer
- See my [resume](https://resume.huikang.dev) and [blog](https://blog.huikang.dev)

<!-- Mention that the links are clickable -->

---

# Introduction
<br>

- Objective of this talk
  - To <span class="golden-font">inform</span> what Software Engineering is like
  - To <span class="golden-font">describe</span> the expectations of a technical career
  - To <span class="golden-font">encourage</span> more Singapore students into Software Engineering
  - To <span class="golden-font">provide advice</span> on how get started in coding

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
  - You can create anything with code
  <!-- If you find something in the world that could be improved with software, you can build it -->
  <!-- You can find resources online that teaches you how to implement each individual component, and you can put them together -->
  - Software Engineering is very accessible
  <!-- As long as you have a computer, whatever can be created with code can be created -->

- The potential to <span class="golden-font">serve</span> millions or billions
  - A small scale project can help you and your friends
  <!-- By helping yourself or your friend, you can see impact from your work. -->
  <!-- Every now and then you can see people sharing their projects online, which can be used by anyone -->
  - A large scale project (with a company) can help millions or billions
  <!-- There is also potential to change the world. Software is easy to scale and help many people. -->

- The increasing <span class="golden-font">importance</span> of software and technology
  - The most popular professions - medicine and law are increasingly using technology
  - Successful companies need to be able to develop and use their own technology
  - One of the highest paid jobs right after undergraduate education is Software Engineering
  <!-- Software is eating up the world. -->


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

<!--
This video I am going to show very well summarise how Software Engineers operate.

I am not expecting you to get the joke, so I will explain some things we see in the video

So in this video, the main character, the junior software engineer is fixing a bug in the code.
-->

<iframe width=100% height=480
src="https://www.youtube.com/embed/rR4n-0KYeKQ"
title="YouTube video player" frameborder="0"
allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

---


# How Software Engineers collaborate
<br>

What we see in the skit
- Writing (or deleting) code
- Code testing
- Version control
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

<!-- When the junior engineer make changes, the code runs on a specific set of tests -->
<!-- When the junior engineer make changes, it happens on his version of the code -->
<!-- When the junior engineer proposes to make changes to main version of the code, the senior engineer reviews the changes -->
<!-- By both the junior and the senior software engineer -->

<!-- We see that both the junior and the senior review each others' work in fixing the code -->
<!-- The code is never done, new features are added and issues are fixed -->

---

# The future of coding?

<!--
This video I am showing you is an AI writing code

Voiceover

What we see there is that the programmer writing a piece of comment specifying the requirements

Then we see the artificial intelligence produces code fulfilling that requirements

Laypeople look at this and wonder whether will software engineers run out of jobs
-->

<iframe
  width="672" height="378"
  src="https://www.youtube.com/embed/edSZh-tpTIk?start=0&end=49"
  title="YouTube video player" frameborder="0"
  allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
  allowfullscreen></iframe>

---

# It's called [code](https://www.commitstrip.com/en/2016/08/25/a-very-comprehensive-and-precise-spec/)

<br><br>

![called-code](https://i.imgur.com/BadoBEK.png)

<!--
Read the comic
-->

---

# The challenges in Software Engineering
<br>

Software Engineering <span class="golden-font">is not only about writing code</span>.
<br>
<br>

Software Engineers need to [consider](http://codesqueeze.com/the-7-software-ilities-you-need-to-know/) the following

- Can users use the product intuitively?


- How many users can you serve at a time?


- How does your system prevent failure?


- Can the future team add modifications easily?


- Is unauthorised access prevented?


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
Can users use the product intuitively without guidance
How many database connections can you have at the same time
What happens when part of your system goes down
After you leave the company, can your successors understand what you wrote, fix bugs and add features
Is sensitive information protected

These questions require an understanding of the business use case and also techincal concepts
-->


---

# Some perspectives on Software Engineering
<br>
<br>
<br>


> 'Software Engineering' encompasses not just the act of writing code, but all of the tools and processes an organization uses to build and maintain that code over time

\- from the book [Software Engineering at Google](https://abseil.io/resources/swe_at_google.2.pdf)

<br>
<br>

> Software is about developing knowledge more than writing code

> Software should be treated not as a static product, but as a living manifestation of the development team’s collective understanding

\- from [How to Build Good Software](https://www.csc.gov.sg/articles/how-to-build-good-software) by Li Hongyi for Civil Service College

<!--
As mentioned, software is no a one-off work
The code needs to be deployed and maintained - this is software engineering

When we develop a software solution, we also develop knowledge how we approach the solution, which include knowledge on software
The team learn from what works and what does not work and it is important to keep the knowledge in the company
In the essay, Li Hongyi argues why the Singapore Government needs software engineers rather than to always simply outsource
By extension, this suggests the importance of Software Engineers in organisations that produces software
-->

---

<div style="position: absolute; bottom: 50px;">

# What are the <span class="ts-title">various roles</span> of Software Engineering?

- What are the different types of Software Engineering?
- How do Software Engineers advance in their careers?
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

<span class="golden-font">Frontend Engineer</span>

Implement user interface

<br>

<span class="golden-font">Backend Engineer</span>

Implement databases and logic

<br>

<span class="golden-font">Reliability Engineer</span>

Ensure that the product is works

</div>
<div>

<span class="golden-font">Data Scientist / ML Engineer</span>

Research, design and build predictive models

<br>

<span class="golden-font">Data Engineer</span>

Manage live data for operations or analysis

<br>

<span class="golden-font">Security Analyst</span>

Protect the product from unauthorised access


</div>
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

<!--
What you see on the website or the phone app is the work of the Frontend Engineer

Of course the phone app usually does not work by itself, it needs information, it reads information from somewhere called the database.
This is managed by the Backend Engineer

The Reliability Engineer ensures that the product works, code is deployed and downtime is avoided

The Data Scientist or ML Engineer (read slides)
The models could automate the work of humans, or example by flagging whether the content is offensive and should be reviewed

The Data Engineer (read slides)
For large companies, there is a lot of data and some solutions require using this large amount of data

The Security Analyst (read slides)
They know the industry practices and common security loopholes and they fix the loopholes.
-->

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
- You may take some time to discover the nature of the role that you prefer


<!--
People who care more about the product prefer to interact with the users and solve their problems.
People who care more about the code prefer to work with static requirements rather than uncertain preferences of the users.

Of course, ideally you want to be the type appropriate for the scenario. But some people may find the other type draining.

In the article, the author was assigned a code-first role and found little meaning in the role and reconsidered her interest in SWE.
Then when she found a product-first role she was more empowered and found meaning in her work.

We need both of these types of people.
-->

---

# The career ladder of Software Engineering
<br>

Responsibilities and Expectations increase with [each](https://blog.tryexponent.com/learn-software-engineering-levels-to-advance-your-career/) [level](https://www.quora.com/What-is-the-expectation-out-of-each-software-engineering-level-at-Facebook/answer/Dima-Korolev)
1) Write code and tests under basic supervision
2) Make minor and implement design decisions without supervision
3) Prioritize the problems to solve and manage work

<br>

Other roles that Software Engineers pivot to

- Product Manager - Manage product requirements and product schedule
- Engineering Manager - Lead the team and communicate with other teams and upper management

<br>

Usually, Software Engineers are managed by people with Software Engineering experience

<!--
(read slides)
Product Manager - there are non-technical product managers, but if a non-technical person instructs a technical team, they need to somehow get respect
-->


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
- Universities and Academia - Research Officers, PhD programmes

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

<!--
Interns
-->

---

# Base salary ranges in the Southeast Asia startups
<br>

![salary-ranges-ds](https://i.imgur.com/ZVFI5Rd.png)

![salary-ranges-swe](https://i.imgur.com/sDpYYk6.png)


From [2021 Southeast Asia Tech Talent Compensation Report](https://employers.glints.com/sg/blog/2021/03/30/2021-southeast-asia-tech-talent-compensation-report/) by Glints and Monk's Hills Ventures


<!--
We earn 1 to 4 times more than our peers in the region.

What justifies our salaries? Just because we are in Singapore? Just because we graduate from Singapore universities?

This is something that we need to answer.
-->

---

<div style="position: absolute; bottom: 50px;">

# Is Software Engineering <span class="ts-title">for me</span>?

- How do I try out coding?
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


<!--
I especially agree on the point of presistence.
For Engineering in general, either it works or does not work, unless let's say, business plans.
You need to be able to try again and again until it works. Also you need to smart enough to identify problems.
-->


---

# My Story
<br>

- Admission into SUTD with no prior coding experience
  - tried to follow tutorials for Andriod programming during NS but got nowhere
- Participated in a [Hackathon](https://www.straitstimes.com/singapore/tertiary-students-come-up-with-innovative-ideas-to-tackle-fake-news) on Fake News
  - where I found my interest in natural language processing
- [Internships](https://blog.huikang.dev/2021/05/14/internship-reflections.html)
  - where I understood how Software Engineering is actually like
  - where I found my strong preference for a technical role
- Competitive programming
  - did weekly Leetcode contests, for fun
  - currently [top 6000](https://codeforces.com/profile/huikang) on Codeforces
  - Quora Programming Contest 2021 - won a [T-shirt](https://challenge.quora.com/Division-2-End-Final-Results), interview and offer

<!--
What I want to share is that the most important thing in the internship is the lunch with your colleagues
- where you can ask questions unrelated to your work
This is what I missed most in the pandemic
-->

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
- Coding bootcamps
  - [Hackwagon](https://hackwagon.com/courses/) 101 introductory courses
  - [Rocket Academy](https://www.rocketacademy.co/courses/basics) Coding Basics
  - Singaporeans might be eligible for [massive discounts](https://hackwagon.com/data-science-101/#courseSubsidies)
- Online classes
  - [edX Harvard CS50](https://www.edx.org/course/introduction-computer-science-harvardx-cs50x)

<br>

If you like coding and have a lot of time, for example during National Service
- Competitive programming (Leetcode [contests](https://leetcode.com/contest/), [Codeforces](https://codeforces.com/))
- [Kaggle](https://www.kaggle.com/learn) data science tutorials and competitions
- Build coding projects (start simple and seek advice)

<!-- I should have practised competitive programming in NS -->

---

# What if you need to code for your research project
<br>

If you need to write code for a JC science project (presumably done over the December break)

- Consider the algorithms you want to implement with code
- Choose Python if possible
  - It is easy to pick up and learn
- Generic advice on how to fix your code
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

[2021 Southeast Asia Tech Talent Compensation Report](https://employers.glints.com/sg/blog/2021/03/30/2021-southeast-asia-tech-talent-compensation-report/) by Glints and Monk’s Hills Ventures

---

# Readings on SWE career preparation
<br>

[Evolution of Resumes - My journey through NUS Computer Science](https://luyangkenneth.github.io/evolution-of-resumes/) by Kenneth Lu

[Software Engineering 2020 Class Profile of University of Waterloo](https://uw-se-2020-class-profile.github.io/profile.pdf) by Holly Oegema et. al.

<br>

Materials to be familiar with to do well in interviews

[Tech Interview Handbook](https://github.com/yangshun/tech-interview-handbook) by Yangshun Tay et. al.

[Frontend Interview Handbook](https://github.com/yangshun/front-end-interview-handbook) by Yangshun Tay et. al.

[Machine Learning Interview Book](https://huyenchip.com/ml-interviews-book/) by Chip Huyen



<!--
# Interesting projects
<br>

- Timetable scheduling [TODO]
  - Given constraints, suggest a timetable for the school
- Game AI playing Snake [TODO]
  - Train an AI to play snake -->

<!-- To add images, hopefully my friends can build the Snake game in time -->

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
