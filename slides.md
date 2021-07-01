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
  ## Sharing on the Software Engineering Career

  A fresh graduate perspective

  by Tong Hui Kang
---

# <span class="golden-font">Sharing</span> on <span class="golden-font"> <br> Software Engineering</span>

Tong Hui Kang

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

- SUTD student 2017-2021, Engineering Systems and Design
- AJC student 2013-2014, PCME
  - Project Eureka
    - H3-SRP on Merkle-Damgard construction
    - SSEF Merit with Integer factorisation with a sum of four squares
    - Do consult me for code-based project ideas
  - See my A level notes on [owlcove.sg](https://owlcove.sg/learn)
- Technical Internships
  - 3 companies over 8 months full-time and 8 months part-time
- Interview experience
  - Interviewed with a total of 6 companies
  - Incoming Quora Software Engineer
- See my [resume](https://resume.huikang.dev) and [blog](https://blog.huikang.dev)

---


<div style="position: absolute; bottom: 50px;">

# What is <span class="ts-title">Software Engineering</span>?

- Is it all about writing code?
- It is interesting?
- Is there job security?
- Can I improve humankind?

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

# Introduction
<br>

- Motivation of this talk
  - To inform what software engineering is like
  - To describe the expectations of a technical career
  - To encourage more Singaporeans into software engineering

---

# Interesting projects
<br>

- Timetable scheduling [TODO]
  - Given constraints, suggest a timetable for the school
- Game AI playing Snake [TODO]
  - Train an AI to play snake

<!-- To add images, hopefully my friends can build the Snake game in time -->

---

# The appeal of working in software engineering
<br>

<!-- Here I explain my main motivation for working on software engineering. It is easy to explain how doctors, lawyers or teachers add value to society and find joy in the profession. -->

- The power to create
  - Software engineering is very accessible.
  <!-- If you have your computer, you can put together a technical solution at a very low cost. You can get feedback for your creation with stakeholders. -->
  - You can create anything with code.
  <!-- If you want to implement an essay completion algorithm, you can follow resources available online to reproduce the results, modify them for your application or improve on the model. -->
- The potential to serve millions or billions
  - A small scale projects can help you and your friends
  - A large scale project (with a company) can help millions or billions
  <!-- It is easy to build something. Getting people to use is hard. Asking people to pay is harder -->
- Huge opportunity
  - The most popular courses professions - medicine and law are increasingly using technology.
  - Successful companies need to be able to develop and use their own technology.
- Renumeration
  - One of the highest paid jobs after university education is software engineering.

---

# Workflow of a technical role
<br>

Code is usually packed in repositories. How are the repositories are edited

- Identify what to solve
  - Could be adding a simple feature, fixing an issue
  - These plans could be made at the start of the week
- Make a copy of the code (Creating a branch)
- Make edits and save edits (Making commits)
- Propose to merge edits with the main version (Make pull request)
  - Automated tests will be run to check if it breaks any existing tests
- After code review, the proposed edits are approved and combined with the main version (Merge branch)
- There may be a second round of checking by human testers and security analysts before it is deployed to serve customers live (production)

<!-- It is true that the core of software engineering is coding. However, it is not about writing code all day. Here I want to give a perspective on what else goes into writing code. -->

<!-- We see that editing code is a collaborative process. There is a lot of communication and planning involved. This is what differentiate software engineers. When you write code, your code needs to be robust and efficient, and it has to be read and edited by future developers. -->

<!-- We also now have some sense of what measures the success of a software engineer. The number of lines written does not indicate the productivity or effectiveness of the software engineer. -->


---

<iframe width=100% height=480
src="https://www.youtube.com/embed/rR4n-0KYeKQ"
title="YouTube video player" frameborder="0"
allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

---


# Tools used in a technical role
<br>
<!-- Another perspective of software engineers I want to provide is based on the tools at the software engineer use. -->

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

# Software engineering specialisations
<br>

Software engineering basics is required of all engineers, after which they can specialise in
  - Frontend
    - Writes the code that is run on your device (your phone, your computer)
  - Backend
    - Writes the code that is run on the company's computers (storing information, execute logic)
  - Data science / Machine learning / Artificial intelligence
    - Research, design and build predictive models
    <!-- - Engineering track and Research track
      - Research roles usually require Masters / PhD and require reading applying research papers -->
  - Data engineer
    - Prepare data for analysis or operations
  - Security engineer
    - Analyse whether the practices adhere to security standards

---

# Alternate classification of software engineering
<br>

- Note on specialisations
  - Different people have different definitions
  - Other classifications may be useful
    - "Code-first" vs "Product-first"
      https://medium.com/@zachlloyd/code-first-vs-product-first-a086d982b7d0

---

# The tech landscape in Singapore
<br>

<!-- There is a common perception that engineering in Singapore is undervalued. I would like to provide a better insight into the following points. -->

- Salaries [TODO]
  - Graduate starting salaries (Ref TBC)
  - Waterloo survey
    https://uw-se-2020-class-profile.github.io/profile.pdf
  - Levels.fyi and Singapore equivalent
  - Geographical variation
- Career progression [TODO]
  - Expectations at each level
  - https://www.quora.com/What-is-the-expectation-out-of-each-software-engineering-level-at-Facebook/answer/Dima-Korolev
  - Software engineering is a collaborative process

---
# Addressing the perceptions of software engineering
<br>

- Software can be written by the lowest bidder [TODO]
  - Vietnamese graduate salaries
  - https://www.csc.gov.sg/articles/how-to-build-good-software
- Some day we will not need software engineers anymore [TODO]
  - https://www.commitstrip.com/en/2016/08/25/a-very-comprehensive-and-precise-spec/
- The varying software engineering environments in Singapore [TODO]
  - http://elijames.org/the-two-tiers-of-singapores-tech-companies/


---
# The software engineering market
<br>

- Company types [TODO]
  - Big tech companies
  - Banks
  - Government
  - Consultancies
- FAANG-tier - Google / Facebook / Bytedance / Indeed / Stripe / Paypal
  - Google SWE interns on average have two prior internships at tech companies
  - More than half of Google / Facebook new graduate hires interned in Google / Facebook before
- Established tech companies - Grab / Go-Jek / etc
  - More than half of the interns have a strong prior internship
  - All new graduate hire at least have a prior internship at tech companies


---
# Data on the software engineering market
<br>

- Size of the Talent pool [TODO]
  - NUS CS, NTU CS enrolment, total IT enrolment
  - Compared to how many open roles and internships in the companies
- Empirical data is hard to find
  - The only empirical data is graduate starting salaries for each course


---

# The technical hiring process
<br>

<!-- Here I provide some long-term advice on how to prepare for a technical career. I will address this from the perspective of how hiring manager and recruiters choose among candidates. -->


What I describe here probably applies to all professional roles as well

- The hiring process
  - Resume screen > Online assessments > Technical Interviews > Offer
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
- Projects
  <!-- - Project choice
    - Something that interests you, start small and get advice
  - Document and explain the project
    - Writing helps to consolidate what you have learnt
    - Others cannot appreciate if you cannot show and explain what you are doing
  - Maintain a blog -->
- Certifications
  <!-- - Cloud Certificates (GCP, AWS)
  - Security Certificates (OSCP) -->
- Competitions


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
src="https://www.youtube.com/embed/pKO9UjSeLew"
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
  - After the project, document the achievements and summarise what you have learnt
- Practise for online assessments and coding interviews
- Network and share resources
  - For all my internships, referrals helped to get me an interview

---

# What you can do after Junior College
<br>

You might want to find out if coding is for you
- My suggestion is to learn Python and solve simple algorithmic tasks
  - [CodeSignal Arcade](https://app.codesignal.com/arcade/python-arcade/meet-python) introduces the concepts step by step
  - Online videos are fine too
  - Start with Python which is easy to learn, rather than say Android programming
- Coding bootcamps
  - Singaporeans might be eligible for massive discounts

If you like coding and have a lot of time
- Competitive programming (Leetcode contests, Codeforces)
  <!-- I should have practised competitive programming in NS -->
- Kaggle data science competitions
- Build coding projects (start simple and seek advice)

---

# What if you need to code for your research project
<br>

If you need to write code for a JC science project (presumably done over the December break)

- Consider if you need to write code
  - Basic data analysis (e.g. R-value) could be done on Excel
  - Algorithms could be done with code
- Choose Python
  - It is easy to pick up and learn
- How to fix your code
  - Start with a working copy
  - Edit it bit by bit and ensuring that it still works
- Seek advice
  - I am open to providing advice

---

# This could have been done with code
<br>

Fun fact - I implemented my integer factorisation algorithm on Excel, should have done it in Python


![algorithm](https://i.imgur.com/SeCDkiC.png)

---

# Summary
<br>

- Software engineering is cool and rewarding
- What software engineering actually is
- Steps to prepare for a software engineering career

---
layout: center
class: text-center
---

# Thank You

[This slides](https://tonghuikang.github.io/swe-sharing) and [source](https://github.com/tonghuikang/swe-sharing)


---

# Readings

[How to Build Good Software](https://www.csc.gov.sg/articles/how-to-build-good-software) by Li Hongyi

[TODO]

---

# Slide Templates

The following slides were from https://github.com/dizys/talk-type-system-in-typescript

I may use some of the styles.

---

# Type System

A type system defines the rules to categorize data (values, expressions).

<div grid="~ cols-2 gap-4">
<div>

### Static vs Dynamic type system

**Static typing**
- Variables have types.
- Compilers ensures (at compile time) that type rules are obeyed.

**Dynamic typing**
- Variables do not have types, values do.
- Compilers/Interpreters ensures (at run time) that type rules are obeyed.

### Structural vs Nominal

</div>
<div>


### Strong vs Weak typing

**Strong typing**

- Does not allow variables to be used in a way inconsistent with their types.

**Weak typing**

- Allows many ways to bypass the type system (e.g., pointer arithmetic).

### Subtype

A relation between types. e.g., `{a, b, c}` is a subtype of `{a, c}`, `a|c` is a subtype of `a|b|c`.

</div>
</div>

---

# Popularity

| # Ranking | Programming Language | Percentage |
| - | -------------------- | ---------- |
| 1 | JavaScript | 18.756% |
| 2 | Python | 16.628% |
| 3 | Java | 11.680% |
| 4 | Go | 7.829% |
| 5 | Ruby | 7.588% |
| 6 | C++ | 6.985% |
| 7 | <span class="ts-title">TypeScript</span> | 6.604% |
| 8 | PHP | 5.081% |

<span style="font-size: 14px; opacity: 0.3;">Courtesy of https://madnight.github.io/githut/#/pull_requests/2021/1</span>


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

# Where does TypeScript advance?

<div grid="~ cols-2 gap-4">
<div>

### Dynamic typing

In JavaScript:

```js
let user = {
  id: 1,
  username: "admin",
  password: "123456",
}

let company = {
  name: "hotstar",
  users: [user, ...],
  running: true
}

function getValue(obj, key) {
  return obj[key]
}

let username = getValue(user, "username")
let isCompanyRunning = getValue(company, "running")
```

</div>
<div>

### Static typing but lack expressiveness

In Golang:

```go
user := User{
  Id: 1,
  Username: "admin",
  Password: "123456"
}

// ...

func getValue(obj interface{}, key string) interface{} {
	objVal := reflect.ValueOf(obj)
	return objVal.FieldByName(key).Interface()
}

userId := getValue(user, "Id").(int)
isCompanyRunning := getValue(company, "Running").(bool)
```

</div>
</div>

---

# A little peek at TypeScript's solution

```ts {monaco} {height: '400px'}
let user = {
  id: 1,
  username: "admin",
  password: "123456",
}

let company = {
  name: "hotstar",
  users: [user],
  running: true
}

function getValue<T extends object, K extends keyof T>(obj: T, key: K): T[K] {
  return obj[key]
}
```

---

# TypeScript Type Features

- Erasable
- Gradual
- Structural
- Generic
- Inferable
- Expressive
- Object-oriented
- Functional

---

# TypeScript Basics

### Basic types

<div grid="~ cols-2 gap-4">
<div>

- <span class="faded-font">Boolean</span>
- <span class="faded-font">Number</span>
- <span class="faded-font">String</span>
- Array
- Tuple
- Enum
- Null and Undefined
- Object/Interface: <span class="faded-font">optional properties</span>
- Function
- Void
- <span class="golden-font">Unknown</span> = U
- <span class="golden-font">Never</span> = ∅
- <span class="golden-font">Any</span>

</div>
<div>

```ts {all|1|2|4-7|9-11}
let arr = [1, 2, 3];
let tuple: readonly [number, number, number] = [1, 2, 3];

interface User {
  name: string;
  phone?: string;
}

function test(arg1: string, arg2: number) {
  return Number(arg1) + arg2;
}

```

<br>
<PlaygroundLink href="https://embeddable.vercel.app/?code=bGV0IGFyciA9IFsxLCAyLCAzXTsKbGV0IHR1cGxlOiByZWFkb25seSBbbnVtYmVyLCBudW1iZXIsIG51bWJlcl0gPSBbMSwgMiwgM107CgppbnRlcmZhY2UgVXNlciB7CiAgbmFtZTogc3RyaW5nOwogIHBob25lPzogc3RyaW5nOwp9CgpmdW5jdGlvbiB0ZXN0KGFyZzE6IHN0cmluZywgYXJnMjogbnVtYmVyKSB7CiAgcmV0dXJuIE51bWJlcihhcmcxKSArIGFyZzI7Cn0KCnR5cGUgVGVzdEZ1bmN0aW9uID0gKGFyZzE6IHN0cmluZywgYXJnMjogbnVtYmVyKSA9PiBudW1iZXI7CgpsZXQgdGVzdDIgPSB0ZXN0Owo%3D" />

</div>
</div>

<style>
.faded-font {
  opacity: 0.5;
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

# TypeScript Basics

### Basic types

<div style="display:flex;flex-direction:row;justify-content:space-between">
<div>

- <span class="faded-font">Boolean</span>
- <span class="faded-font">Number</span>
- <span class="faded-font">String</span>
- Array
- Tuple
- Enum
- Null and Undefined
- Object/Interface: <span class="faded-font">optional properties</span>
- Function
- Void
- <span class="golden-font">Unknown</span> = U
- <span class="golden-font">Never</span> = ∅
- <span class="golden-font">Any</span>

</div>
<img style="height:400px" src="https://www.dizy.cc/talk-type-system-in-typescript/images/typescript-types.svg" />
</div>


<style>
.faded-font {
  opacity: 0.5;
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

# Union Type

`|`: "may be any one of those types"

<div grid="~ cols-3 gap-4">
<div class="col-span-2">

```ts {monaco} {height: '380px'}
interface TextMessage {
  type: "text";
  content: string;
}

interface Hotshot {
  type: "hotshot";
  imageURL: string;
}

// type Message = TextMessage | Hotshot;

function send(message?: TextMessage | Hotshot) {

}
```

</div>
<div>
<img dark="bg-white bg-opacity-30 rounded-lg" src="https://www.dizy.cc/talk-type-system-in-typescript/images/venn-union-type.svg" />
</div>
</div>

---

# Union Type

`|`: The union of type sets.

```ts {monaco} {height: '380px'}
interface User {
  name: string;
  gender: "male" | "female" | "other";
  phone?: string;
}

type Union1 = string | unknown;

type Union2 = string | never;
```

---

# Intersection Type

`&`: The intersection of type sets.


<div grid="~ cols-3 gap-4">
<div class="col-span-2">

```ts {monaco} {height: '380px'}
type I1 = string & unknown;

type I2 = string & never;

interface F {
  f: number;
  b: string;
}

interface B {
  b: string;
  c: boolean;
}

type FBI = F & B;

let fbi: FBI = {
  // ?
}
```

</div>
<div>
<img dark="bg-white bg-opacity-30 rounded-lg" src="https://www.dizy.cc/talk-type-system-in-typescript/images/venn-intersection-type.svg" />
</div>
</div>

---

# Generics

"Type variables"

```ts {monaco} {height: '380px'}
type PropertyType<T, K extends keyof T> = T[K];

interface User {
  username: string;
  age: number;
  gender: "male" | "female" | "other";
}

type AgeType = PropertyType<User, "age">


type MyPick<T, K extends keyof T> = {
  [P in K]: T[P];
};

type Picked = MyPick<User, "username" | "age">;
```

---

# Conditional Type

Ternary operator, but for types.

```ts {monaco} {height: '380px'}
interface User {
  username: string;
}

interface Admin extends User {
  admin: true;
}

type CT<T> = T extends User ? string : number;
type CT1 = CT<Admin>;

type MyNonNullable<T> = T extends null | undefined ? never : T;
type A = MyNonNullable<string | number | undefined>;
```

---

# `infer` in Condition

Declaratively introduce a new generic type variable using type inference.

```ts {monaco} {height: '380px'}
type ItemTypeOfArray<T extends any[]> = T[number];

// or use infer...

type ItemType = ItemTypeOfArray<[number, string, boolean]>;



type TestFunction = (arg1: string, arg2: number) => number;

type FuncReturnType<T> = T extends (...args: any[]) => infer R ? R : never;

type TestFunctionReturnType = FuncReturnType<TestFunction>


```

---

# Template Literal Types

THE most expressive literal typing in the world so far.

```ts {monaco} {height: '380px'}
type ChinaPhone = `+86-${number}`;
let phone: ChinaPhone = '+86-233123';

type City = 'beijing' | 'shanghai' | 'shenzhen' | 'guangzhou';
type Direction = 'east' | 'west' | 'north' | 'south';
type MyLocation = `${City}-${Direction}`;
let location1: MyLocation = 'beijing-north';

type MatchPair<S extends string> = S extends `[${infer A},${infer B}]` ? [A, B] : unknown;
type Pair1 = MatchPair<'[1,2]'>;
type Pair2 = MatchPair<'[foo,bar]'>;

```

---

# Template Literal Types

For instance, `${string}-${string}`. THE most expressive literal typing in the world so far.

```ts {monaco} {height: '380px'}
type Trim<S extends string> =
  S extends ` ${infer T}` ? Trim<T> :
  S extends `${infer T} ` ? Trim<T> :
  S;
type Trimmed1 = Trim<'     hello  '>;
type Trimmed2 = Trim<' hello       '>;

type Join<T extends unknown[], D extends string> =
  T extends [] ? '' :
  T extends [string | number | boolean | bigint] ? `${T[0]}` :
  T extends [string | number | boolean | bigint, ...infer U] ? `${T[0]}${D}${Join<U, D>}`:
  string;
type Joined1 = Join<[1, 2, 3, 4], '.'>;
type Joined2 = Join<['foo', 'bar', 'baz'], '-'>;
```

---

# Turing Completeness

TypeScript's type system used to be Turing-complete (version `2.2`) by indirect recursive generic type invocation. See the [proof](https://github.com/microsoft/TypeScript/issues/14833).

A Turing complete type system would allow infinite self-referencing.

```ts
type Foo<T extends "true", B> = {
  "true": Foo<T, Foo<T, B>>
}[T];

let f: Foo<"true", {}> = null!;
```

- Then in `2.3`, depth of recursive invocation was limited to 100 by PR [#15011](https://github.com/microsoft/TypeScript/pull/15011).

- In `3.7`, direct recursive invocation is introduced but still with depth limitation in place.

```ts
type Json = string | number | boolean | null | Json[] | {[key: string]: Json};
```

<br>

So in short, in its current state, TypeScript's type system is <span text="red-500">NOT</span> but almost Turing-complete.

---

# Type Frankenstein

<div grid="~ cols-3 gap-4">
<div class="col-span-2">

```ts {monaco} {height: '410px'}
type PathImpl<T, Key extends keyof T> =
  Key extends string
  ? T[Key] extends Record<string, any>
    ? | `${Key}.${PathImpl<T[Key], Exclude<keyof T[Key], keyof any[]>> & string}`
      | `${Key}.${Exclude<keyof T[Key], keyof any[]> & string}`
    : never
  : never;

type PathImpl2<T> = PathImpl<T, keyof T> | keyof T;

type Path<T> = PathImpl2<T> extends string | keyof T ? PathImpl2<T> : keyof T;

type PathValue<T, P extends Path<T>> =
  P extends `${infer Key}.${infer Rest}`
  ? Key extends keyof T
    ? Rest extends Path<T[Key]>
      ? PathValue<T[Key], Rest>
      : never
    : never
  : P extends keyof T
    ? T[P]
    : never;

declare function getValue<T, P extends Path<T>>(obj: T, path: P): PathValue<T, P>;

const object = {
  name: 'Diego Haz',
  age: 30,
  account: {
    username: 'diego',
    password: '123456',
  },
  projects: [
    { name: 'Reakit', contributors: 68 },
    { name: 'Constate', contributors: 12 },
  ],
} as const;

getValue(object, "account.");

//
```
</div>
<div>
<Tweet id="1309489079378219009" scale="0.9" />
</div>
</div>

---

# Practical Use Case: Routes

```ts {monaco} {height: '380px'}
type ExtractRouteParams<T extends string> =
  string extends T
  ? Record<string, string>
  : T extends `${infer Start}:${infer Param}/${infer Rest}`
  ? {[k in Param | keyof ExtractRouteParams<Rest>]: string}
  : T extends `${infer Start}:${infer Param}`
  ? {[k in Param]: string}
  : {};

declare function handleGet<Route extends string>(
  route: Route,
  handler: (params: ExtractRouteParams<Route>) => void
): void;

handleGet('/posts/:postId/:commentId', (params) => {
  console.log(params);
});
```

<span style="font-size: 14px; opacity: 0.3;">Courtesy of https://github.com/ghoullier/awesome-template-literal-types</span>

---

# Fun Projects

<div align='center'>
<a target="_blank" href="https://github.com/type-challenges/type-challenges"><img src='https://github.com/type-challenges/type-challenges/raw/master/screenshots/logo.svg' width='400'/></a>
</div>

<p align='center'>
Collection of TypeScript type challenges
<br>
Now supports TypeScript 4.1 🎉
</p>

### Easy

<div class="challenge-list"><a href="https://github.com/type-challenges/type-challenges/blob/master/questions/4-easy-pick/README.md" target="_blank"><img src="https://img.shields.io/badge/-4%E3%83%BBPick-7aad0c" alt="4・Pick"/></a><a href="https://github.com/type-challenges/type-challenges/blob/master/questions/7-easy-readonly/README.md" target="_blank"><img src="https://img.shields.io/badge/-7%E3%83%BBReadonly-7aad0c" alt="7・Readonly"/></a><a href="https://github.com/type-challenges/type-challenges/blob/master/questions/11-easy-tuple-to-object/README.md" target="_blank"><img src="https://img.shields.io/badge/-11%E3%83%BBTuple%20to%20Object-7aad0c" alt="11・Tuple to Object"/></a><a href="https://github.com/type-challenges/type-challenges/blob/master/questions/14-easy-first/README.md" target="_blank"><img src="https://img.shields.io/badge/-14%E3%83%BBFirst%20of%20Array-7aad0c" alt="14・First of Array"/></a> <a href="https://github.com/type-challenges/type-challenges/blob/master/questions/18-easy-tuple-length/README.md" target="_blank"><img src="https://img.shields.io/badge/-18%E3%83%BBLength%20of%20Tuple-7aad0c" alt="18・Length of Tuple"/></a> <a href="https://github.com/type-challenges/type-challenges/blob/master/questions/43-easy-exclude/README.md" target="_blank"><img src="https://img.shields.io/badge/-43%E3%83%BBExclude-7aad0c" alt="43・Exclude"/></a><a href="https://github.com/type-challenges/type-challenges/blob/master/questions/189-easy-awaited/README.md" target="_blank"><img src="https://img.shields.io/badge/-189%E3%83%BBAwaited-7aad0c" alt="189・Awaited"/></a> <a href="https://github.com/type-challenges/type-challenges/blob/master/questions/268-easy-if/README.md" target="_blank"><img src="https://img.shields.io/badge/-268%E3%83%BBIf-7aad0c" alt="268・If"/></a> <a href="https://github.com/type-challenges/type-challenges/blob/master/questions/533-easy-concat/README.md" target="_blank"><img src="https://img.shields.io/badge/-533%E3%83%BBConcat-7aad0c" alt="533・Concat"/></a> <a href="https://github.com/type-challenges/type-challenges/blob/master/questions/898-easy-includes/README.md" target="_blank"><img src="https://img.shields.io/badge/-898%E3%83%BBIncludes-7aad0c" alt="898・Includes"/></a></div>


### Medium

<div class="challenge-list"><a href="https://github.com/type-challenges/type-challenges/blob/master/questions/2-medium-return-type/README.md" target="_blank"><img src="https://img.shields.io/badge/-2%E3%83%BBGet%20Return%20Type-d9901a" alt="2・Get Return Type"/></a> <a href="https://github.com/type-challenges/type-challenges/blob/master/questions/3-medium-omit/README.md" target="_blank"><img src="https://img.shields.io/badge/-3%E3%83%BBOmit-d9901a" alt="3・Omit"/></a> <a href="https://github.com/type-challenges/type-challenges/blob/master/questions/8-medium-readonly-2/README.md" target="_blank"><img src="https://img.shields.io/badge/-8%E3%83%BBReadonly%202-d9901a" alt="8・Readonly 2"/></a> <a href="https://github.com/type-challenges/type-challenges/blob/master/questions/9-medium-deep-readonly/README.md" target="_blank"><img src="https://img.shields.io/badge/-9%E3%83%BBDeep%20Readonly-d9901a" alt="9・Deep Readonly"/></a> <a href="https://github.com/type-challenges/type-challenges/blob/master/questions/10-medium-tuple-to-union/README.md" target="_blank"><img src="https://img.shields.io/badge/-10%E3%83%BBTuple%20to%20Union-d9901a" alt="10・Tuple to Union"/></a> <a href="https://github.com/type-challenges/type-challenges/blob/master/questions/12-medium-chainable-options/README.md" target="_blank"><img src="https://img.shields.io/badge/-12%E3%83%BBChainable%20Options-d9901a" alt="12・Chainable Options"/></a> <a href="https://github.com/type-challenges/type-challenges/blob/master/questions/15-medium-last/README.md" target="_blank"><img src="https://img.shields.io/badge/-15%E3%83%BBLast%20of%20Array-d9901a" alt="15・Last of Array"/></a> <a href="https://github.com/type-challenges/type-challenges/blob/master/questions/16-medium-pop/README.md" target="_blank"><img src="https://img.shields.io/badge/-16%E3%83%BBPop-d9901a" alt="16・Pop"/></a> <a href="https://github.com/type-challenges/type-challenges/blob/master/questions/20-medium-promise-all/README.md" target="_blank"><img src="https://img.shields.io/badge/-20%E3%83%BBPromise.all-d9901a" alt="20・Promise.all"/></a> <a href="https://github.com/type-challenges/type-challenges/blob/master/questions/62-medium-type-lookup/README.md" target="_blank"><img src="https://img.shields.io/badge/-62%E3%83%BBType%20Lookup-d9901a" alt="62・Type Lookup"/></a> <a href="https://github.com/type-challenges/type-challenges/blob/master/questions/106-medium-trimleft/README.md" target="_blank"><img src="https://img.shields.io/badge/-106%E3%83%BBTrim%20Left-d9901a" alt="106・Trim Left"/></a> <a href="https://github.com/type-challenges/type-challenges/blob/master/questions/108-medium-trim/README.md" target="_blank"><img src="https://img.shields.io/badge/-108%E3%83%BBTrim-d9901a" alt="108・Trim"/></a> <a href="https://github.com/type-challenges/type-challenges/blob/master/questions/110-medium-capitalize/README.md" target="_blank"><img src="https://img.shields.io/badge/-110%E3%83%BBCapitalize-d9901a" alt="110・Capitalize"/></a> <a href="https://github.com/type-challenges/type-challenges/blob/master/questions/116-medium-replace/README.md" target="_blank"><img src="https://img.shields.io/badge/-116%E3%83%BBReplace-d9901a" alt="116・Replace"/></a> <a href="https://github.com/type-challenges/type-challenges/blob/master/questions/119-medium-replaceall/README.md" target="_blank"><img src="https://img.shields.io/badge/-119%E3%83%BBReplaceAll-d9901a" alt="119・ReplaceAll"/></a> <a href="https://github.com/type-challenges/type-challenges/blob/master/questions/191-medium-append-argument/README.md" target="_blank"><img src="https://img.shields.io/badge/-191%E3%83%BBAppend%20Argument-d9901a" alt="191・Append Argument"/></a> <a href="https://github.com/type-challenges/type-challenges/blob/master/questions/296-medium-permutation/README.md" target="_blank"><img src="https://img.shields.io/badge/-296%E3%83%BBPermutation-d9901a" alt="296・Permutation"/></a> <a href="https://github.com/type-challenges/type-challenges/blob/master/questions/298-medium-length-of-string/README.md" target="_blank"><img src="https://img.shields.io/badge/-298%E3%83%BBLength%20of%20String-d9901a" alt="298・Length of String"/></a> <a href="https://github.com/type-challenges/type-challenges/blob/master/questions/459-medium-flatten/README.md" target="_blank"><img src="https://img.shields.io/badge/-459%E3%83%BBFlatten-d9901a" alt="459・Flatten"/></a> <a href="https://github.com/type-challenges/type-challenges/blob/master/questions/527-medium-append-to-object/README.md" target="_blank"><img src="https://img.shields.io/badge/-527%E3%83%BBAppend%20to%20object-d9901a" alt="527・Append to object"/></a> <a href="https://github.com/type-challenges/type-challenges/blob/master/questions/529-medium-absolute/README.md" target="_blank"><img src="https://img.shields.io/badge/-529%E3%83%BBAbsolute-d9901a" alt="529・Absolute"/></a> <a href="https://github.com/type-challenges/type-challenges/blob/master/questions/531-medium-string-to-union/README.md" target="_blank"><img src="https://img.shields.io/badge/-531%E3%83%BBString%20to%20Union-d9901a" alt="531・String to Union"/></a> <a href="https://github.com/type-challenges/type-challenges/blob/master/questions/599-medium-merge/README.md" target="_blank"><img src="https://img.shields.io/badge/-599%E3%83%BBMerge-d9901a" alt="599・Merge"/></a> <a href="https://github.com/type-challenges/type-challenges/blob/master/questions/610-medium-camelcase/README.md" target="_blank"><img src="https://img.shields.io/badge/-610%E3%83%BBCamelCase-d9901a" alt="610・CamelCase"/></a> <a href="https://github.com/type-challenges/type-challenges/blob/master/questions/612-medium-kebabcase/README.md" target="_blank"><img src="https://img.shields.io/badge/-612%E3%83%BBKebabCase-d9901a" alt="612・KebabCase"/></a> <a href="https://github.com/type-challenges/type-challenges/blob/master/questions/645-medium-diff/README.md" target="_blank"><img src="https://img.shields.io/badge/-645%E3%83%BBDiff-d9901a" alt="645・Diff"/></a> <a href="https://github.com/type-challenges/type-challenges/blob/master/questions/949-medium-anyof/README.md" target="_blank"><img src="https://img.shields.io/badge/-949%E3%83%BBAnyOf-d9901a" alt="949・AnyOf"/></a> <a href="https://github.com/type-challenges/type-challenges/blob/master/questions/1042-medium-isnever/README.md" target="_blank"><img src="https://img.shields.io/badge/-1042%E3%83%BBIsNever-d9901a" alt="1042・IsNever"/></a> <a href="https://github.com/type-challenges/type-challenges/blob/master/questions/1097-medium-isunion/README.md" target="_blank"><img src="https://img.shields.io/badge/-1097%E3%83%BBIsUnion-d9901a" alt="1097・IsUnion"/></a> <a href="https://github.com/type-challenges/type-challenges/blob/master/questions/1130-medium-replacekeys/README.md" target="_blank"><img src="https://img.shields.io/badge/-1130%E3%83%BBReplaceKeys-d9901a" alt="1130・ReplaceKeys"/></a> <a href="https://github.com/type-challenges/type-challenges/blob/master/questions/1367-medium-remove-index-signature/README.md" target="_blank"><img src="https://img.shields.io/badge/-1367%E3%83%BBRemove%20Index%20Signature-d9901a" alt="1367・Remove Index Signature"/></a></div>

### hard + extreme...

<style>
.challenge-list {
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  margin-top: 5px;
}

.challenge-list a {
  border: none;
  margin-right: 5px;
  margin-bottom: 5px;
}
</style>

---

# Fun Projects: [ts-sql](https://github.com/codemix/ts-sql)

<div>

```
 ▄▄▄▄▄▄▄▄▄▄▄  ▄▄▄▄▄▄▄▄▄▄▄               ▄▄▄▄▄▄▄▄▄▄▄  ▄▄▄▄▄▄▄▄▄▄▄  ▄
▐░░░░░░░░░░░▌▐░░░░░░░░░░░▌             ▐░░░░░░░░░░░▌▐░░░░░░░░░░░▌▐░▌
 ▀▀▀▀█░█▀▀▀▀ ▐░█▀▀▀▀▀▀▀▀▀              ▐░█▀▀▀▀▀▀▀▀▀ ▐░█▀▀▀▀▀▀▀█░▌▐░▌
     ▐░▌     ▐░▌                       ▐░▌          ▐░▌       ▐░▌▐░▌
     ▐░▌     ▐░█▄▄▄▄▄▄▄▄▄  ▄▄▄▄▄▄▄▄▄▄▄ ▐░█▄▄▄▄▄▄▄▄▄ ▐░▌       ▐░▌▐░▌
     ▐░▌     ▐░░░░░░░░░░░▌▐░░░░░░░░░░░▌▐░░░░░░░░░░░▌▐░▌       ▐░▌▐░▌
     ▐░▌      ▀▀▀▀▀▀▀▀▀█░▌ ▀▀▀▀▀▀▀▀▀▀▀  ▀▀▀▀▀▀▀▀▀█░▌▐░█▄▄▄▄▄▄▄█░▌▐░▌
     ▐░▌               ▐░▌                       ▐░▌▐░░░░░░░░░░░▌▐░▌
     ▐░▌      ▄▄▄▄▄▄▄▄▄█░▌              ▄▄▄▄▄▄▄▄▄█░▌ ▀▀▀▀▀▀█░█▀▀ ▐░█▄▄▄▄▄▄▄▄▄
     ▐░▌     ▐░░░░░░░░░░░▌             ▐░░░░░░░░░░░▌        ▐░▌  ▐░░░░░░░░░░░▌
      ▀       ▀▀▀▀▀▀▀▀▀▀▀               ▀▀▀▀▀▀▀▀▀▀▀          ▀    ▀▀▀▀▀▀▀▀▀▀▀
```
This is a SQL database implemented purely in TypeScript type annotations.
This means that it operates solely on types - you define a "database" (just a type annotation) and then query it using some more type annotations.

It supports a subset of SQL, including SELECT (with conditions and joins), INSERT, UPDATE and DELETE statements.

<PlaygroundLink href="./links/ts-sql.html" />

</div>

---

# Fun Projects: Text-Based Adventure Game

Play a text adventure in vscode with the typescript type system.

<img src="https://dizy.cc/talk-type-system-in-typescript/images/screenshot-adventure-game.png" style="border-radius: 10px" />

[Original article](https://ricklove.me/typescript-type-system-adventure) by Rick Love.

---
layout: center
class: text-center
---

# Learn More

[TypeScript Handbook](https://www.typescriptlang.org/docs/handbook/intro.html) / [GitHub Repo](https://github.com/microsoft/typescript) / [This Slide](https://github.com/dizys/talk-type-system-in-typescript)
