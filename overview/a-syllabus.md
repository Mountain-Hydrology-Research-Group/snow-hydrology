
# Syllabus: CEWA 568

## Course Overview

**Snow Hydrology - Winter Quarter, 2025**

The course will cover a number of fundamental topics related to snow hydrology including phases of water, evolution of a snowpack, mass and energy balances, and field measurement techniques.

| **CEWA 568A** | SLN 11962 | 3 units |
| **CEWA 568B PCE** | SLN 11963 | 3 units |


**Instructors:**      Eli Schwat (elilouis@uw.edu) and Jessica Lundquist (jdlund@uw.edu)

**Lectures:**         10:30am - 12:20pm Tuesday/Thursday (Pacific Time)
 
The room location, and relevant course information are available via the [course Canvas page](https://canvas.uw.edu/) (UW NetID login required).

### Learning Objectives

By the end of the course, students should be able to
 * Explain the snow mass and energy balance over a snowpack
 * Read and understand research papers in the field of Snow Hydrology
 * Read, modify, and write computer programs to analyze snow-related data
 * Apply data analysis techniques to understand real world problems related to snow

> ### Guiding principles for this quarter
> **In person, experiential learning.**
>   * No zoom links.
>   * Labs and field trips cannot be completed remotely.
> 
> **We’re all in this together**
>  * No problem if you need to miss a class, just let the instructor know.
>  * Reach out to your fellow students to take notes for you.

### Office Hours

3-4pm Tuesday/Wednesday or by appointment. See Canvas for the location of office hours.

```note
The UW eScience institute offers [data science office hours](https://escience.washington.edu/office-hours/) which could be useful for your projects or your own research work.
```

### Textbooks

 * **Recommended**: [*A Field Guide to Snow*](https://www.amazon.com/Field-Guide-Snow-Snowy-Owl/dp/1602234140), by Matthew Sturm
 * **Required Course Materials** are available on the [UW Canvas site](https://canvas.uw.edu/) (UW NetID login required)


## Logistics and Grading

### Computing Resources

For lab activities and assignments, we will be using a [JupyterHub](https://spestana.github.io/data-analysis/resources/b-learning-jupyter.html) computing environment, and programming with [python](https://spestana.github.io/data-analysis/resources/a-learning-python.html). 

The JupyterHub for this course can be accessed [here](https://jupyter.rttl.uw.edu/2025-winter-cewa-568-a) with a UW net id.

If you need access to a laptop computer (such as if yours breaks) you may check one out from the [Student Technology Loan Program](https://stlp.uw.edu/). Please contact me if you need help accessing a computer reliably.


### Lectures and labs

The first half (~50 minutes) of each class period is reserved for lecture discussion. Lecture slides will be available on Canvas, along with any additional files for reading.

### Labs
After a 5 minute break, 50 minutes of class will be spent working collaboratively on labs, homeworks, and projects.
Lab content (jupyter notebooks and data files) can be downloaded directly from the class website and uploaded to your jupyter hub ([GitHub Option](https://spestana.github.io/data-analysis/resources/b-learning-jupyter.html#working-with-files-on-our-jupyterhub))

In addition to the classroom space, we will use Slack to communicate with each other about lab exercises and projects.
Contact the instructor if you need to be added to the Slack workspace.

### Homework Assignments
Homework assignments are posted on the course website on each week's module page.
Homework due dates are listed in the schedule below, as well as on the course Canvas page. Assignments should be turned in on Canvas. 
On days with assignments due, assignments should be turned in **before the beginning of class (10:30 am, Pacific Time)**. 
Homework questions are posted on the class website along with links to any data files you might need.

You are encouraged to work together on homeworks and collaborate, but you must turn in your own assignments with your own work.

Coding assignments should include your name and the assignment number at the top of the notebook (ipynb) file in markdown text. **Your answers should be clearly labeled and written in *markdown* cells of the notebook.**

Submit your completed homework assignments via Canvas by uploading:
* Your original .ipynb jupyter notebook file(s)
  * To download your notebook file, right click on the file in the navigation pane on JupyterHub, then click *Download*
* A PDF copy of the jupyter notebook file(s)
  * To save your notebook as a PDF, go to *File* > *Export Notebook As...* > *Export Notebook to PDF*, this will download a PDF file copy of your notebook to your personal computer which you can upload to Canvas

Homework will be graded on a scale of 1 to 10, with 10 being the best. Homework handed in late will be accepted up to (but not later than) the following Tuesday at the beginning of class (10:30am), but two grade points will be deducted from the grade for late assignments (i.e. a late assignment that would receive a 10 if handed in on time will be assigned a grade of 8). Everyone's lowest scoring homework assignment will be dropped, so please do not worry if one week is not going your way.

### Final Project
Final projects will be completed in pairs (or individually on request), and the topic will be selected by the students in consultation with the instructor. 
The topic should involve analyzing field measurements to answer a snow-hydrology related question.
During the final week of class, students will present their research projects to the class.
Final reports will be due on the final day of class, **March 13 2025, by 11:59pm**. 
Further details are provided in the schedule below and on the [Course Project page](b-project.html).

### Grading Policy

* **Class Attendance and Participation: 5%**
  * Participation includes discussions in class and providing feedback on student presentations
* **Homework assignments: 65%**
  * Each of the 8 homework assignments are worth 10 points (for a total of 80 points), however your lowest assignment will be dropped, and the overall homework grade will be evaluated out of 7 assignments and 70 points total.
* **Final Project: 30%**
  * See the [CEWA 565 course project page](/overview/b-project.html) for grading rubric.


## Schedule of topics and assignments
The readings, lab and homework assignments for each week are listed below. Weeks missing information will be updated as the quarter progresses.
Required readings should be completed *in advance of class*.
Labs will be completed on the day that they are listed.

Note that assigned journal articles should be read, but not obsessed over. I understand that truly reading and digesting a research article can take hours. That is not my intent in assigning these readings. I recommend skimming the articles and reading closely where you find your interest lies. Other readings (e.g. from Field Guide to Snow) should be read closely. 

Optional readings are listed for you to explore at your leisure. They also may be useful in inspiring your term projects.

### Week 1 – Properties of Snow
---
#### Day 1  – Introduction, importance of snow globally, snow science history
* **Readings**
  * Field Guide to Snow, Chapter 1 “Where Is Snow?“

* **Assignments**
  * Lab 1-1 
  * HW0 (Due January 9): Write short paragraph about answering the following questions: 1. Why do you want to take this class? 2. Are there any specific topics that you’d like covered in this class? 3. What is your preferred learning style? – I.e. what do you think about powerpoint vs chalk board lectures, use of python notebook “labs” and homeworks, term projects.

#### Day 2  – Phases of water, snowflake and snowpack properties, and SWE
* **Readings**
  * Librrecht 2007 “The formation of snow crystals”
  * Field Guide to Snow, Chapters 2, 3, and 4 “The Crystal Factory” , “Snowflakes”, and “Snow Layers and Weather”
* **Assignments**
  * Lab 1-2
  * HW1 (Due January 16)
* **Optional Readings**
  * Huss 2017 “Toward mountains without permanent snow and ice”

### Week 2 - Measurement Strategies, Basics of the Snowpack Mass and Energy Balances, and Snowpack Dynamics (compaction, metamorphism)
---
#### Day 1 – Intro to the Sublimation of Snow (SOS) Campaign, Basics of the Snowpack Mass and Energy Balances
* **Readings**
  * Lundquist 2024 “Sublimation of Snow”
* **Assignments**
  * Lab 2-1

#### Day 2  – Snowpack Dynamics (compaction, metamorphism)
* **Readings**
  * Field Guide to Snow, Chapter 5 “Metamorphism: Snow in the Crucible” but you can skip 5.1.3
* **Assignments**
  * Lab 2-2
  * HW2 (Due January 23)
  * See the course project page - your Initial Project proposal is due on January 23

### Week 3 - Surface Energy Balance over snow - The energy balance equation, radiation, optical properties of snow
---
#### Day 1 – Surface energy balance and radiation
* **Readings**
  * Warren 2019, Optical properties of ice and snow (Skip the sections “Lake ice and sea ice”, “Marine ice”, and “The transition snow–firn–glacier ice”). Note that Stephen Warren is a UW legend!
* **Assignments**
  * Lab 3-1

#### Day 2 – Optical properties of snow, applications of the energy balance
* **Assignments**
  * Lab 3-2
  * HW3 (Due January 30)
* **Optional Readings**
  * Marks and Dozier, 1992. Climate and energy exchange at the snow surface in the Alpine Region of the Sierra Nevada: 2. Snow cover energy balance

### Week 4 - Snowpack temperatures - conduction and internal energy
---
* **Assignments**
  * Lab 4-1
  * Lab 4-2
  * Lab 4-3
  * HW4 (Due February 6)
* **Optional Readings**
  * Sturm 1997. The thermal conductivity of seasonal snow.

### Week 5 - Turbulent transport - Turbulent fluxes, the eddy covariance method, and atmospheric stability
--- 
* **Assignments**
  * Lab 5-1
  * Lab 5-2
  * Lab 5-3
  * HW5 (Due February 13)

### Week 6 - Blowing snow: transport and sublimation 
---
Chapter 5 Wind Transport (pages 59-78)
* **Assignments**
  * Lab 6-1
  * Lab 6-2
  * Lab 6-3
  * HW6 (Due February 25). Due date delayed to give you time to prepare your Midterm Progress report, due February 20 (see the project page).
* **Optional Readings**
  * Highly recommended to prepare for lecture
    * Pomeroy and Gray 1995. Snowcover accumulation, relocation and management, Chapter 5 Wind Transport (pages 59--78)
  * Trouvilliez et al 2015. Evaluation of the FlowCapt Acoustic Sensor for the Aeolian Transport of Snow.
    * Comparison of modern instruments used to measure blowing snow


### Week 7 - Snow melt 
---

* **Assignments**
  * See the course project page - your Midterm Progress Report is due on February 20

### Week 8 - Snow-dominated watershed hydrology
---

### Week 9 - Snowpack structure and avalanches
---

### Week 10 - Final project presentations
---

* **Assignments**
  * See the course project page - your Presentation is due on March 11
  * See the course project page - your Final Report is due on March 13

## Additional Information

### Campus Community Resources

* [Student Resources](https://grad.uw.edu/equity-inclusion-and-diversity/go-map/student-resources/) from the [UW Graduate Opportunities and Minority Achievement Program (GO-MAP)](https://grad.uw.edu/equity-inclusion-and-diversity/go-map/).
* The [Q Center](https://depts.washington.edu/qcenter/wordpress/)
* The [UW Counseling Center](https://www.washington.edu/counseling/)  
* The [University District Food Bank](https://www.udistrictfoodbank.org/)

### Conduct

The University takes academic integrity very seriously. Behaving with integrity is part of our responsibility to our shared learning community. One example of misconduct I have observed in this particular class in the past is plagiarism (representing the work of others as your own without giving appropriate credit to the original author(s)). **If you’re uncertain about if something is academic misconduct, ask me. I am willing to discuss questions you might have.**

[Community Standards & Student Conduct](https://www.washington.edu/cssc/)

The University of Washington Student Conduct Code (WAC 478-121) defines prohibited academic and behavioral conduct and describes how the University holds students accountable as they pursue their academic goals. Allegations of misconduct by students may be referred to the appropriate campus office for investigation and resolution. More information can be found online at [https://www.washington.edu/studentconduct/](https://www.washington.edu/studentconduct/)


### Access and Accommodations

If you have already established accommodations with Disability Resources for Students (DRS), please communicate your approved accommodations to me at your earliest convenience so we can discuss your needs in this course. If you have not yet established services through DRS, but have a temporary health condition or permanent disability that requires accommodations (conditions include but not limited to; mental health, attention-related, learning, vision, hearing, physical or health impacts), you are welcome to contact DRS at 206-543-8924 or [uwdrs@uw.edu](mailto:uwdrs@uw.edu) or [disability.uw.edu](https://depts.washington.edu/uwdrs/). DRS offers resources and coordinates reasonable accommodations for students with disabilities and/or temporary health conditions.  Reasonable accommodations are established through an interactive process between you, your instructor(s) and DRS.  It is the policy and practice of the University of Washington to create inclusive and accessible learning environments consistent with federal and state law.


### Religious Accommodations

Washington state law requires that UW develop a policy for accommodation of student absences or significant hardship due to reasons of faith or conscience, or for organized religious activities. The UW’s policy, including more information about how to request an accommodation, is available at [Religious Accommodations Policy (https://registrar.washington.edu/staffandfaculty/religious-accommodations-policy/)](https://registrar.washington.edu/staffandfaculty/religious-accommodations-policy/). Accommodations must be requested within the first two weeks of this course using the [Religious Accommodations Request form (https://registrar.washington.edu/students/religious-accommodations-request/)](https://registrar.washington.edu/students/religious-accommodations-request/).


### Health and Safety

Call SafeCampus at 206-685-7233 (206-685-SAFE) anytime – no matter where you work or study – to anonymously discuss safety and well-being concerns for yourself or others. SafeCampus’s team of caring professionals will provide individualized support, while discussing short- and long-term solutions and connecting you with additional resources when requested.

Mental health resources are available at [wellbeing.uw.edu](https://wellbeing.uw.edu/topic/mental-health/). The [UW Counseling Center](https://www.washington.edu/counseling/) is also a good resource (206-543-1240). University of Washington students are eligible for services at the Counseling Center. 

Additionally, if you’re thinking about suicide, are worried about a friend or loved one, or would like emotional support, the Lifeline network is available 24/7 across the United States: National Suicide Prevention Lifeline (1-800-273-8255), Forefront Suicide Prevention (866-598-3978), and Crisis Text Line (741741). If the person you are concerned about is in immediate danger of killing them self and/or refuses to stay safe with you, call or text 911.


