# Course Syllabus - Macroevolution

**Course**: BIOL 531  
**Time**: Monday, Wednesday, & Friday 1:30-2:30pm, Abelson 306 (WSU), LSS 277 (UI), or Zoom  
**Professors**: Prof. Katherine Corn & Prof. Luke Harmon
**Email**: katherine.corn [at] wsu.edu  & lukeh [at] uidaho.edu   
**Office hours**: By appointment

## Textbooks
None are required to be purchased; readings will be provided from the primary literature, as well as from the following texts. Purchase of these texts is optional, though they are great reference material for those interested in macroevolution.

- Revell, Liam J., and Luke J. Harmon. *Phylogenetic comparative methods in R*. Princeton University Press, 2022. [Supplementary info](http://www.phytools.org/Rbook/)
- Harmon, Luke J. *Phylogenetic Comparative Methods*. 2022. [link](https://lukejharmon.github.io/pcm/)

Readings will be provided as pdfs on Dr. Corn’s GitHub repository (https://github.com/kacorn/macroevolution_course).

## Course Description
Theory and practice of modern phylogenetic comparative methods. Students will learn about major methods of evolutionary analyses using phylogenies. We will discuss how models work, their pros and cons in implementation, read the literature of methods development and application, and practice using methods on real data. Students will conclude the course with a short project using their own datasets.

## Course Policies

### Attendance
Students should make all reasonable efforts to attend all class meetings. You are expected to participate in all discussions, have completed all readings before class, and to fully engage with the material and your classmates. However, in the event a student is unable to attend a class, it is the responsibility of the student to inform the instructor as soon as possible and make up class work missed within a reasonable amount of time. Missing more than 5 class meetings will result a reduction of the overall grade in the class due to a reduced participation score. Any relevant recordings, slides, and relevant notes will be available on Canvas or GitHub.

### Course Syllabus
The course syllabus is subject to change by the instructor. Changes will be announced in class and on Canvas.

### Student Evaluation
- **Participation**: In discussions of primary literature (100 points)
- **Final Project Presentation**: Final project presentation (50 points)
- **Project Product**: Product from final project (50 points)

#### Final Project Description
Course participants will perform a research project that will analyze phylogenetic data using the methods and techniques learned in class. This project is largely open-ended and up to the student. Suggested topics include: analyzing existing phenotypic datasets with phylogenetic comparative methods, exploring the diversification history of a clade, or conducting a simulation study of phylogenetic model behavior. Students are strongly encouraged to bring their own data for this project.

### Technology
Please respect my time and submit your own thoughts. ChatGPT and other generative artificial intelligence tools are not permitted in this course. Any use of AI tools may result in a 0 on the appropriate assignment, quiz, and/or on the course final grade.

### Academic Integrity
Academic integrity is the foundation of learning. You are responsible for reading WSU's Academic Integrity Policy, which is based on Washington State law. If you cheat in your work in this class you will:
- Receive a 0 on the appropriate assignment, quiz, presentation, or overall grade in the class.
- Be reported to the Center for Community Standards
- Have the right to appeal my decision
- Not be able to drop the course of withdraw from the course until the appeals process is finished
If you have any questions about what you can and cannot do in this course, ask me.
If you want to ask for a change in my decision about academic integrity, use the form at the Center for Community Standards website. You must submit this request within 21 calendar days of the decision.

### Expectations for Student Effort & Classroom Decorum
For each hour of lecture equivalent, students should expect to have a minimum of two hours of work outside of class.

In support of fruitful and open academic discourse, we are all are expected to engage in courteous, civil, and mutually respectful exchanges focused on and relevant to the course materials. Students should not engage in disruptive behavior which obstructs or disrupts the learning environment, including, but not limited to, dominating the classroom or online discussion, behavior that disrupts the flow of instruction, or failure to cooperate in maintaining classroom decorum. Students engaging in behavior that is disruptive to the course objectives may be asked to leave or be referred to the appropriate disciplinary process. I am similarly committed to creating a civil and productive environment for the free exchange of ideas; students who have concerns about this should contact the department chair.

### Services for Students with Disabilities (SSD)
Some materials for this course are not yet fully digitally accessible. WSU will accommodate students with disabilities to support accessing these documents – please contact Student Accommodations and Disability Resources as soon as possible for a reasonable accommodation.
Washington State University welcomes students in need of accommodations. If you are in need of special accommodations due to a disability, as recognized by the Americans with Disabilities Act, please contact the WSU Access Center to communicate your needed arrangements as soon as possible (https://accesscenter.wsu.edu.).

### University Syllabus
Students are responsible for reading and understanding all university-wide policies and resources pertaining to all courses (for instance: accommodations, care resources, policies on discrimination or harassment), which can be found in the university syllabus.

## Course Schedule (subject to change)

| Week | Dates | Lab Topic | Lab Text |  Empirical Paper | Methods Paper |  Lecture Topic   | Lecture Text |
|------|-------|-----------|----------|------------------|---------------|------------------|--------------|
| 1 | Jan 12-16 |NA | NA |  - | [Felsenstein 1985](pdfs/Fels1985.pdf); [Huey 2019](pdfs/huey2019.pdf) | Why is life so diverse? (debate) [Harmon slides](https://docs.google.com/presentation/d/1qa3edCStF0nWfGJH84RbbnQvipKaNpCV2X3_yIo7nBg/edit?usp=sharing)| Harmon [Chapter 1](https://lukejharmon.github.io/pcm/chapter1_introduction/) |
| 2 | Jan 19-23 |NA | NA | -  | [Uyeda et al 2018](pdfs/uyeda2018.pdf)  | The comparative approach in evolution [slides](https://docs.google.com/presentation/d/1Y_-f0LkPXKGh84_x4fAhUb9j0DVdqFy2cekS9yMn968/edit?usp=sharing)| Harmon [Chapter 2](https://lukejharmon.github.io/pcm/chapter2_stats/) |
| 3 | Jan 26-30 | Introduction to R | Revell & Harmon Ch 1 | [Mahler et al 2010](pdfs/Mahler2010.pdf) | [Losos 2008](pdfs/losos2008.pdf) | Brownian motion [slides](https://docs.google.com/presentation/d/10qVSk8k7qs3RdrkMyGNXERtUa5Z35ohs/edit?usp=share_link&ouid=113905662326593519868&rtpof=true&sd=true) | Harmon [Chapter 3](https://lukejharmon.github.io/pcm/chapter3_bmintro/) & [Chapter 4](https://lukejharmon.github.io/pcm/chapter4_fitbm/) |
| 4 | Feb 2-6 | Making functions in R	| Revell & Harmon Ch 2  | [Rivera et al 2024 Ecol Evol](pdfs/Rivera2024.pdf)	| -	| PICs, PGLS [slides](https://docs.google.com/presentation/d/1nBHTotGdkNCWlsGa4rcZftcjWm_KegE7WszxfXJkegU/edit?usp=sharing) |	Harmon [Chapter 5](https://lukejharmon.github.io/pcm/chapter5_mvbm/)	|
| 5 | Feb 9-13 |	Intro to trees in R |	Revell & Harmon Ch 5 |  [Miller al et Arcila 2025 Nat Eco Evo](pdfs/Miller2025.pdf) | - | Multivariate BM & Ornstein-Uhlenbeck [slides](https://docs.google.com/presentation/d/1_ea1gQvD5HyPX67YrPFRyYIMA-rOShqx/edit?usp=sharing&ouid=113905662326593519868&rtpof=true&sd=true) | Harmon [Chapter 6](https://lukejharmon.github.io/pcm/chapter6_beyondbm/) |
| 6	| Feb 16-20 |	NA |	NA | Project discussion prep | - | R catch up day: PGLS | -  |
| 7	| Feb 23 – 27 |	Fitting BM |	Revell & Harmon Ch 3 |	[Kontopoulos et al 2025 Functional Ecol](pdfs/Kontopolous2025.pdf) | - | Discrete character evolution [slides](https://docs.google.com/presentation/d/1L-4YqS_Y712pnG66-1XGgy8Bty1yNMwrGYU2lejroFg/edit?usp=sharing) |	Harmon [Chapter 7](https://lukejharmon.github.io/pcm/chapter7_introdiscrete/) & [Chapter 8](https://lukejharmon.github.io/pcm/chapter8_fitdiscrete/) |
| 8	| Mar 2-6 | Fitting Discrete Trait Models	|	Revell & Harmon Ch 3 | [Hagen & Beaulieu 2024](pdfs/HagenBeaulieu2024.pdf) | - |	Extended Mk Models & HMMs [slides](https://docs.google.com/presentation/d/1eQZtd_MSjgfSmn6fY1uQghZ6KC4kvG8n/edit?usp=share_link&ouid=113905662326593519868&rtpof=true&sd=true) |	[Harmon Ch 9](https://lukejharmon.github.io/pcm/chapter9_beyondmk/)  |
| 9	| Mar 9 – 13 | Guest: [Orlando Schwery](https://oschwery.github.io), [Intro to RevBayes (link)](https://github.com/oschwery/RevBayesIntro_UI_WSU) |	Revell & Harmon Ch 6 & 8 | [Cockx et al. 2025](pdfs/Cockx2025.pdf) |	[Bollback 2006](pdfs/Bollback2006.pdf) | 	RevBayes Intro Day 2 | -	|
| - |	Mar 16-21 |	Spring break		|
| 10 |	Mar 23-27 |		Correlated discrete models on trees | Revell & Harmon Ch 7 |	[Bars-Closel et al 2017 Evolution](/pdfs/barsclosel2017.pdf) | - | Speciation & extinction | Harmon [Chapter 11](https://lukejharmon.github.io/pcm/chapter11_fitbd/) & Harmon [Chapter 12](https://lukejharmon.github.io/pcm/chapter12_beyondbd/) |
| 11 |	Mar 30 - Apr 3 |	Estimating time-varying diversification on trees |	Revell & Harmon Ch 10 |	Project check-in meetings |	- |	 Phylogeographic models [slides](https://docs.google.com/presentation/d/1hclqJDVGYZ4jDzC8MyMolpC7U5t33Cfv/edit?usp=share_link&ouid=113905662326593519868&rtpof=true&sd=true) |	Ronquist & Sanmartín 2011 |
| 12 |	Apr 6-10 |	BiSSE |	Revell & Harmon Ch 11 |	[Zenil-Ferguson et al 2019 New Phyt](/pdfs/rzf_newphyt_2019.pdf) |	- | Cophylogenetics (treeducken!) |	[Harmon Ch 13](https://lukejharmon.github.io/pcm/chapter13_chardiv/) |
| 13 |	Apr 13 - 17 |	BioGeoBEARs |	Revell & Harmon Ch 12 |	Kawahara et al 2023 Nat Eco Evo |	- | Practical applications |	- |
| 14 | Apr 20-24 |		Mini-project planning, plotting |	Revell & Harmon Ch 13 |	TBA |	- | Course wrap up, Q&A | - |
| 15 | Apr 27 - May 1 |	Project analyses & code clinic | - | TBA |	- |	No class | -	|
| Finals Week |	May 4-8 |	Project presentations |  
