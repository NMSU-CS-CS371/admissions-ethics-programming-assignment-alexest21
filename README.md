[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/oqKLEXJJ)
# 🎓 Ethical Admissions Algorithm Simulation

This repository is a classroom exercise exploring **ethics and fairness in algorithmic decision-making** — specifically in college admissions.

You’ll implement and reflect on how feature selection and weighting can impact fairness, transparency, and equity in automated systems.

---

## 🧩 Overview

You are part of the admissions committee for **Anonymous University**, located near Anonymous City.  
Due to a large number of applications, the committee decides to use an algorithm to help **rank and shortlist applicants**.

Your task:
- Decide which factors to include (GPA, test scores, extracurriculars, essays, recommendation letters, legacy status, income, etc.)
- Assign weights to each factor.
- Compare outcomes under two models:
  - **Blind model**: Ignores sensitive factors.
  - **Aware model**: Includes them intentionally to promote fairness (e.g., extra weight for first-gen or low-income applicants).

---

## ⚙️ How to Run

You can run the code on any online Java compiler (e.g. [Replit](https://replit.com/~) or [Programiz Java Compiler](https://www.programiz.com/java-programming/online-compiler))  
or locally via terminal:

```bash
javac Applicant.java Admissions.java Main.java
java Main

●Feature Selection & Design
-What variables did you include, and why?
I included all the regular percentages for GPA, test scores, essay, etc. However, I added income, first-gen, legacy, and local proximity to the aware model. 

-Did you exclude any sensitive features? Why or why not?
I excluded disability because I personally do not think it should factor in when applying to a job or school.

-Should “legacy” still carry a positive weight?
Yes I think legacy should carry a positive weight because in many real universities that is sometimes the case. 

-What other features (e.g., proximity, essay strength, disability) might you add or adjust?
Proximity could be changed whether or not the university wants to have deep local ties or allow for a more globally diverse campus. 

●Fairness & Outcomes
-Between the blind and aware models, which applicants benefited or lost out?
Applicants from low-income, first-generation, or local backgrounds gained from the aware model.

-Which applicants specifically benefited from the aware model?
Low-income, first-generation, or local backgrounds gained the most from the aware model

-Does adding income or first-generation status make the system fairer or less fair? Why?
I think it makes the admissions more fair because some might not have access to the same resources or have the same starting point. 

-Which model feels more fair overall, and why?
The aware model feels the most fair because it takes context into consideration and not just treat them equally like the blind model does. 

●Transparency & Accountability
-How transparent is your algorithm?
I think it is very transparent because all the features and weight is defined in the code. 

-Could you clearly explain a rejection to an applicant?
Yes I think I could clearly explain a rejection especially based on their academic stats. 

-Would you feel comfortable if this algorithm evaluated your application? Why or why
not?
Yes I would feel comfortable because it uses clear logic and everything is clear. 

●Broader Implications
-What risks might arise if such an algorithm were used in real admissions?
There could be a transparency problem if the public does not understand how scores are calculated. 

-What real-world parallels exist (e.g., hiring, policing, scholarships)?
I think this exercise is very similar to real life algorithms that are working in hiring and scholarship selection.

-What does this exercise reveal about fairness in algorithmic decision systems?
It shows that fairness is not just about removing bias, but about deciding what kind of bias we’re willing to introduce to achieve equity.

-Can algorithms ever be truly fair, or do they just shift where bias appears?
I do not think they can ever truly be fair but we can redistribute bias rather than eliminate it entirely. 

-How should fairness and accountability be balanced in automated decisions?
Fairness should guide the design and accountability should guide the use of the system.
