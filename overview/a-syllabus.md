
# Syllabus: CEWA 568

## Course Overview

**Snow Hydrology - Spring Quarter, 2023**

The course will cover a number of fundamental topics related to snow hydrology including phases of water, evolution of a snowpack, mass balance, energy balance, and measuring, plotting, analyzing snow and energy balance timeseries.

| **CEWA 568A** | SLN 11962 | 3 units |
| **CEWA 568B PCE** | SLN 11963 | 3 units |


**Instructor:**      Jessica Lundquist, jdlund@uw.edu

**Lectures:**      Fridays: 9:30 am - 12:20 pm (Pacific Time)

The room location, and relevant course information are available via the [course Canvas page](https://canvas.uw.edu/) (UW NetID login required).

**Snow Hydrology Feedback Form**: Use this form to provide anonymous feedback to the TA and instructor. The link to the form is available in the copy of the syllabus on the [course Canvas page](https://canvas.uw.edu/) (UW NetID login required). 

### Learning Objectives

By the end of the course, students should be able to
 * Explain the snow mass and energy balance over a snowpack
 * Read, modify, and write computer programs to analyze snow-related data
 * Apply data analysis techniques to understand real world problems related to snow
 * Teach someone else something about snow

```note
### Guiding principles for this quarter
1. **We want to emphasize in person, experiential learning.**
  * We will have labs and field trips on campus that cannot be done remotely.
  * If something comes up so that you cannot attend class, please reach out to the professor as soon as possible.
2. **We’re all in this together**
 * If you do need to miss one week, you can best make up the material by meeting up with someone else in the class.
 * Please reach out to your fellow students and make plans to watch out for each other.
```

### Office Hours

Jessica: Fridays, immediately after class; or by appointment

```note
The UW eScience institute offers [data science office hours](https://escience.washington.edu/office-hours/) which could be useful for your projects or your own research work.
```

### Textbooks

 * **Recommended**: [*A Field Guide to Snow*](https://www.amazon.com/Field-Guide-Snow-Snowy-Owl/dp/1602234140), by Matthew Sturm
 * **Additional Course Materials** are available on the [UW Canvas site](https://canvas.uw.edu/) (UW NetID login required)


## Logistics and Grading

### Computing Resources

For lab activities and assignments, we will be using a [JupyterHub](https://spestana.github.io/data-analysis/resources/b-learning-jupyter.html) computing environment, and programming with [python](https://spestana.github.io/data-analysis/resources/a-learning-python.html). 

If you need access to a laptop computer (such as if yours breaks) you may check one out from the [Student Technology Loan Program](https://stlp.uw.edu/). Please contact me if you need help accessing a computer reliably.


### Lectures

The first hour of each class period is reserved for lectures and associated discussions. We will be using Zoom for these live lectures, and to record lectures for later viewing. Lectures will be recorded and made available afterwards. Lecture slides will be available on Canvas, along with any additional files for reading.  However, the second two hours of each class will not be recorded, so please make every effort to be there in person.


### Labs

Following a ~5 minute break after each lecture, we will reconvene for the lab portion of the class (this will not be recorded). Lab content (jupyter notebooks and data files) can be downloaded directly from the from class website. ([GitHub Option](https://spestana.github.io/data-analysis/resources/b-learning-jupyter.html#working-with-files-on-our-jupyterhub))

We will use classroom space and Slack to work in small groups on lab excercises. If you are not able to attend the lab in person, please reach out to others in the class for collaborative support. Contact the instructor or TA to be added to the Slack workspace.


### Homework Assignments

Homework assignments will be given out on Fridays at the beginning of class, and will be **due the following week on Friday at the beginning of class (9:30 am, Pacific Time)**. Homework questions are posted on the class website along with links to any data files you might need.

You are encouraged to work together on homeworks and collaborate, but you must turn in your own assignments with your own work. 

Make sure that your name and the assignment number are at the top of your notebook file in markdown text. Your answers should be clearly labeled and written in markdown cells of the notebook.

Submit your completed homework assignments via Canvas by uploading:
* Your original .ipynb jupyter notebook file(s)
  * To download your notebook file, right click on the file in the navigation pane on JupyterHub, then click *Download*
* A PDF copy of the jupyter notebook file(s)
  * To save your notebook as a PDF, go to *File* > *Export Notebook As...* > *Export Notebook to PDF*, this will download a PDF file copy of your notebook to your personal computer which you can upload to Canvas

Homework will be graded on a scale of 1 to 10, with 10 being the best. Homework handed in late will be accepted up to (but not later than) Tuesday at 5:00 pm (Pacific Time), but two grade points will be deducted from the grade for late assignments (i.e. a late assignment that would receive a 10 if handed in on time will be assigned a grade of 8). Late homework assignments will not be accepted after 5:00 pm (Pacific Time) on the Tuesday following the due date.  Everyone's lowest scoring homework assignment will be dropped, so please do not worry if one week is not going your way.

Homework solutions will be posted in the Solutions folder on [Canvas](https://canvas.uw.edu/) by the Thursday after the assignment was turned in.


### Final Project

Final projects will be completed in pairs (or individually on request), and the topic will be selected by the students in consultation with the instructor. The topic should ideally involve explaining/teaching a concept and/or snow hydrology coding problem selected from within the student’s area of interest. Updates on the project are required as part of the 2nd, 5th, and 7th homework assignments, and each student will give a short overview of their research problem and project results to the class. The project will be graded on the basis of the presentation (20%) and on the report (80%), which should be less than 10 pages long. Final reports will be due on **Wednesday, June 7, 2:30 pm (Pacific Time)**. Further details are provided on the [Course Project page](b-project.html).

### Grading Policy

* **Class Attendance and Participation: 5%**
  * Participation includes discussions in class, on Slack, and providing feedback on student presentations
  * *If you plan on attending class asynchronously by watching the recorded lectures, please let me know.*
* **Homework assignments: 70%**
  * Each of the 8 homework assignments are worth 10 points (for a total of 80 points), however your lowest assignment will be dropped, and the overall homework grade will be evaluated out of 7 assignments and 70 points total.
* **Final Project / Final Exam: 25%**
  * See the [CEWA 565 course project page](/overview/b-project.html) for grading rubric.


## Schedule

```note
This schedule is subject to change throughout the quarter. Check assignment due dates on Canvas for the updated schedule.
```

[UW Academic calendar for 2022-2023](https://www.washington.edu/students/reg/2223cal.html)

| Week | Lecture Dates | Lecture Topics | Labs | Assignments |
| --- | --- |  --- | --- | --- |
| **1** | 3/31 | What is snow?  Phases and properties of matter | Lab 1: Plotting data in Python | |
| **2** | 4/7 | Mass balance: How much snow is there? (Possible class fieldtrip day!)| Lab 2: Snow depth, snow density, snow covered area, and snow water equivalent (SWE) | 4/7: **HW1 Due** |
| **3** | 4/14 | How does a snowpack change? (Class held in UW Maker Space)| Lab 3: Snow pits, crystals, and snowpack evolution | 4/14: **HW2 Due** |
| **4** | 4/21 | Mass balance: Blowing snow & How snow smoothes landscapes | Lab 4: Blowing snow | 4/21: **HW3 Due** |
| **5** | 4/28 | Temperature above and within the snow | Lab 5: Temperature gradients and the heat equation | 4/28: **HW4 Due** |
| **6** | 5/5 | Turbulent transfer above the snow: changing mass and energy | Lab 6: Examining turbulence | 5/5: **HW5 Due** |
| **7** | 5/12 | Radiation, albedo, and the energy balance | Lab 7: Examining the energy balance | 5/12: **HW6 Due** |
| **8** | 5/19 | What makes snow melt?  | Lab 8: Putting the energy balance together | 5/19: **HW7 Due** |
| **9** | 5/26 | Trees and snow (Class held in UW Maker Space)| Project Work | 5/26: **HW8 Due** |
| **10** | 6/02 | Mountain Meteorology | Project Presentations | 6/2: **Presentations** |
| **Finals Week** | 6/07 |  |  | 12/12: **CEWA 568 - Final Project Report Due** |

## Additional Information

### Campus Community Resources

* [Student Resources](https://grad.uw.edu/equity-inclusion-and-diversity/go-map/student-resources/) from the [UW Graduate Opportunities and Minority Achievement Program (GO-MAP)](https://grad.uw.edu/equity-inclusion-and-diversity/go-map/).
* The [Q Center](https://depts.washington.edu/qcenter/wordpress/)
* The [UW Counseling Center](https://www.washington.edu/counseling/)  
* The [University District Food Bank](https://www.udistrictfoodbank.org/)
* King County COVID-19 [Child Care Financial Support](https://www.kingcounty.gov/depts/community-human-services/COVID/child-care.aspx)

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


