---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

# For courses with a single offering in the _config.yml,
# uncomment the following line and comment out the course-multi line

#layout: course-single
layout: course-multi
---

# <a name="description">Overview</a>

{{ site.description }}

## <a name="description">Course Description</a>

* This is a Special Topics course focusing on the foundations of computer vision and machine learning/ deep learning methods for computer vision tasks. The students are expected to have obtained a solid
background in machine learning, linear algebra, and coding skills.
* This course is a combination of lectures and student presentations. We plan to read and discuss recent research papers on the intersection between computer vision and machine learning. We plan to invite internal (within the department) and external speakers to give guest lectures to give introductory and state-of-the-art developments in the area of computer vision and machine learning.
* This course satisfies the ECE graduate program requirement.
* Piazza: [https://piazza.com/ubc.ca/winterterm22022/eece570](https://piazza.com/ubc.ca/winterterm22022/eece570)

{% include resources.html content=site.goals %}

## <a name="contact">Contacts</a>
* Instructor: Dr. Xiaoxiao Li (xiaoxiao.li@ece.ubc.ca)
* TA: Chun-Yin Huang (chunyinhuang17@gmail.com)
* TA: Sana Ayromlou (ayromlous@gmail.com)
* Email: include ‘[EECE 570]’ in the subject.

{% include resources.html content=site.resources %}

## <a name="time-and-location">Time and Location</a>

* Location:
Tue/Thu ∥ 11:00 am – 12:30 pm ∥ Neville Scarfe∥ Rm 1004
* Zoom participation ID:
[https://ubc.zoom.us/j/65807504716?pwd=RnV0Z2dHR1NCMkcwcnVYVmluZ2RRdz09](https://pythonintro-yorgey.notebooks.azure.com/j/notebooks/PythonIntro.ipynb)
* TA Office Hours: TBA
* Instructor Office Hours: Thursday afternoon (by appointment only)

{% include resources.html content=site.extra-resources %}


## <a name="reading-and-presentation">Reading and Presentation</a>
* During each class meeting, we will have student presentations and discussions of selected papers.  The tentative schedule below lists tentative topics for each class and suggested papers.  

* Students taking the course are expected to read all selected papers. The presenter needs to write a review for the paper to be presented. Each review should be submitted one day before its presentation and discussion. Please refer to lecture 1's course notes on how to write a review. The review needs to cover 1) summary; 2) pros; 3) cons; and 4) future direction.

 
* There are 3 parts for each presentation: 
  * Problem statement, a brief overview of the state-of-the-art
  * Key idea of the paper
  * Strengths, weaknesses and future directions
	

* The total time allocated for each paper is 40 minutes with 25 mins presentation and 15 mins discussion.  We suggest you prepare in advance and do not exceed 40 minutes to leave 40 minutes for another presentation.

* We welcome students to suggest their interested papers.  If students are interested in substitute papers, after signing up for desired time slots, the student should discuss with the instructor at least one week in advance to have time to make an announcement.  

## <a name="grading">Grading</a>
* Paper Readings and Presentations: 30% 
  * Read the selected paper(s) and submit review
  * Present the selected paper
  * Lead discussion in the classroom


* Course participants: 10%
  * You must show up on your presentation date. No show will lead to failing the course. 
  * Grade for your classmate's presentation. If you cannot attend the presentation (two chances over the term), please let TA and instructor know. Otherwise, -1 point each time. 


* Project proposal (2 pages): 20%
* Final project (at least 4 pages): 40%
  * A computer vision project that is related to the course topic. You have the flexibility to choose the topics. More details will be released later. **No Teamwork allowed**.
  * *Passing the course does on conditional on if you pass the final project*.

* Late submission will result in *0.8 decay per day. Extension is only accepted via applying for [Academic Concession](https://academicservices.engineering.ubc.ca/exams-grades/academic-concession/).


## Computational Resources

* GPU computing is required for this class. I strongly recommend to Google Colab or use your
own/lab’s GPU since that is the most convenient way of writing and testing code with GUI. [Click
here](https://colab.research.google.com/github/cs231n/cs231n.github.io/blob/master/python-colab.ipynb) to try out the Colab tutorial. You can also consider using other computational resources
offered by UBC.

## Optional Textbooks

* Friedman, Jerome, Trevor Hastie, and Robert Tibshirani. The elements of statistical learning.
Vol. 1. No. 10. New York: Springer series in statistics, 2001.
* Richard Szeliski. Computer Vision: Algorithms and Applications , 2022.
* Goodfellow, Ian, Yoshua Bengio, Aaron Courville, and Yoshua Bengio. Deep learning. Vol.
1, no. 2. Cambridge: MIT press, 2016.
* Torfi, Amirsina. [Deep Learning Roadmap](https://www.machinelearningmindset.com/books/)


<hr>

# <a name="schedule">Schedule</a>

Our schedule will be updated during the semesber. Please frequently check the schedule here.

| Dates | Presenters        | Topics                                                               | Suggested papers | Submissions                       |
|:-------:|-------------------||:---------------------------------:|:-------------------------------------:|:-----------------------------------:|
| 1/10  | Dr. Xiaoxiao Li | Couse Introduction                                                   |                  |            Signup Piazza                       | 
| 1/12  | Dr. Xiaoxiao Li | Introduction to computer vision                                      |      <img width=400/>            | Signup presentation               |
| 1/17  | Dr. Xiaoxiao Li | Introduction to deep learning                                        |                  |                                   |
| 1/19  | Dr. Xiaoxiao Li | Edge Detector                                                        |                  |                                   |
| 1/24  |                   | Presentation – <br>  deep learning-based sketching                         |                  | Submit review <br> Submit peer-grading |
| 1/26  | Dr. Xiaoxiao Li                  | Fileters and Multi-scale Representation                              |                  |  |
| 1/31  | Dr. Xiaoxiao Li | Image Classification I Filtering                                               |                  |                                   |
| 2/1   | Dr. Xiaoxiao Li |  Image Classification II – <br>  Heterogeneity & Weakly SupervisedI                                               |                  |                                   |
| 2/7   |          |  Presentation – <br>  Advanced image classification |                  |                                   |
| 2/9   | Dr. Xiaoxiao Li | Image Classification III   – <br> Trustworthiness                          |                  |                                   |
| 2/14  |                   | Presentation – <br>  Advanced image classification                         |                  |                                   |
| 2/16  | Dr. Xiaoxiao Li | Object detection and identification                                  |                  |                                   |
| 2/24  |                   |                                                                      |                  | Submit project proposal           |
| 2/28  |                   | Presentation – <br>  Advanced object detection and identification          |                  | Submit review <br> Submit peer-grading |
| 3/2   | TEA grad student  | Trustworthy AI                                                       |                  |                                   |
| 3/7   | TEA grad student  | Trustworthy AI                                                       |                  |                                   |
| 3/9   | Dr. Xiaoxiao Li | Image Segmentation                                                   |                  | Submit review <br> Submit peer-grading |
| 3/14  |                   | Presentation – <br>  Advanced image segmentation                           |                  |                                   |
| 3/16  | Dr. Xiaoxiao Li | Image Synthesis                                                      |                  |                                   |
| 3/21  |                   | Presentation – <br>  Advanced image synthesis                              |                  | Submit review <br> Submit peer-grading |
| 3/23  | Dr. Xiaoxiao Li | Image Registration                                                   |                  | Submit review <br> Submit peer-grading |
| 3/28  |                   | Presentation – <br>  Image Registration                                    |                  |                                   |
| 4/4   | Dr. Xiaoxiao Li | Vision-Transformer                                                   |                  |                                   |
| 4/6   |                   | Presentation – <br> Vision Transformer                                      |                  | Submit review <br> Submit peer-grading |
| 4/11  | Dr. Xiaoxiao Li | Video analysis                                                       |                  |                                   |
| 4/13  |                   | Presentation – <br> Vision Analysis                                         |                  | Submit review <br> Submit peer-grading |
| 4/21  | All students      | Final project                                                        |                  | Submit final project              |

<hr>