---
title: CIS 530 - Computational Linguistics - University of Pennsylvania
layout: default
img: head.png
img_link: http://emnxw.com/heads/
caption: Image credit&colon; Edwige and Xavier
active_tab: main_page 
---

<!--This course will provide an introduction to computational linguistics, focusing on algorithms, models, and applications.--> 
This course provides an overview of the field of natural language processing. The goal of the field is to build technologies that will allow machines to understand human langauges. Applications include machine translation, automatic summarization, question answering systems, and dialog systems.

<!--<div class="alert alert-success" markdown="1">
CIS 530 will be offered in the Fall by Dr. Clayton Greenberg.  He will be using the CIS waitlist system to issue permits and manage enrollment.  .
!-->
You do not need to email the instructor to receive a permit, instead you should [sign yourself up for the waitlist](https://forms.cis.upenn.edu/waitlist/index.php)
After you've added yourself to the waitlist, the instructor can issue you a permit.  You will receive an email saying permit available. You will receive another email when the permit is issued. At that point, you may register on CoursesInTouch. 


<!--

If you didn't get a permit for the course, but you're still hoping to get in, then you should follow these steps:
1. [Join the class Piazza](https://piazza.com/upenn/spring2020/cis530).
2. [Add yourself to Gradescope](https://www.gradescope.com/courses/80035) with the entry code __MGZXK3__.
3. [Complete Homework 1](http://computational-linguistics-class.org/assignment1.html) by Wednesday (Jan 22nd) before midnight.

If you don't turn in HW1 on time, then you won't be considered for enrollment if any additional permits become available. 
</div>

<div class="alert alert-info" markdown="1">
Grading updates:
* You can opt to take the course pass/fail.
* I'm giving everyone 10 extra late days. You can use up to 3 late days per HW or quiz.
* Since the team-based project is now harder to coordinate, I'm offering a HW option.  You can opt to do 4 weekly HW assignments instead of the term project.
* I'm allowing everyone to drop their lowest scoring quiz 
* I'm allowing everyone to drop their lowest scoring homework assignment (you cannot drop project milestones if you opt to do the project)
</div>

-->

<!-- Display an alert about upcoming homework assignments -->
{% capture now %}{{'now' | date: '%s'}}{% endcapture %}
{% for page in site.pages %}
{% if page.release_date and page.due_date %}
{% capture release_date %}{{page.release_date | date: '%s'}}{% endcapture %}
{% capture due_date %}{{page.due_date | date: '%s'}}{% endcapture %}
{% if release_date < now and due_date >= now %}
<div class="alert alert-info" markdown="span">
<!-- <a href="{{site.baseurl}}/{{page.url}}">{{ page.title }}</a> has been released. -->
<!-- <a href="{{site.baseurl}}+{{page.url}}">{{ page.title }}</a> has been released. -->
<!-- this is annoyingly broken. Why doesn't it render to expansions? -->
[{{page.title}}](http://markyatskar.com/cis530_sp2021/{{page.url}}) has been released.
{% if page.deliverables %}
The assignment has multiple deliverables.

{% else %}
It is due before {{ page.due_date | date: "%I:%M%p" }} on {{ page.due_date | date: "%A, %B %-d, %Y" }}.
{% endif %}
</div>
{% endif %}
{% endif %}
{% endfor %}
<!-- End alert for upcoming homework assignments -->

Course number
: CIS 530 - Computational Linguistics 

Instructor
: [Mark Yatskar](http://www.markyatskar.com/) 

Discussion Forum
: [Piazza](http://piazza.com/upenn/spring2021/cis530)

Time and place
: Spring 2021, Tuesday and Thursday 1:30-2:30pm via [Zoom](https://upenn.zoom.us/j/98444480663?pwd=R0doOXc2eGs1VXI4MEpWcTJpbm5UQT09). Attendance is optional, but the instructor will be recording lectures with those that would like to attend and ask questions. Lectures will be posted on Canvas immediately following the lecture.
: First day of class is January 21, 2021
: Last day of class is May 11, 2021


Office hours
: To join the office hour queue, please go to [OHQ.io](https://ohq.io/courses/193).
: Monday 8:30pm - 10:00pm Eastern - Pengrui
: Tuesday 10:30am - 12:00pm Eastern - Haren
: Tuesday 5:00pm - 6:30pm Eastern - Chaitanya
: Wednesday 1:30pm - 3:00pm Eastern - Mark [zoom](https://upenn.zoom.us/j/91244874322?pwd=N0txcDgzMlhjRjZuZHR2VndqZ0Zsdz09)
: Wednesday 3:00pm - 4:30pm Eastern - Yue
: Thursday 3:00pm -4:30pm Eastern - Weiqiu
: Saturday 10:00am - 11:30am Eastern - Daniel


Textbooks
: Both textbooks are available for free on the web. 
: [Speech and Language Processing (3rd edition draft) by Dan Jurafsky and James H. Martin](https://web.stanford.edu/~jurafsky/slp3/)
: [Natural Language Processing by Jacob Eisenstein](https://github.com/jacobeisenstein/gt-nlp-class/tree/master/notes)
: The course will have [weekly required readings](lectures.html).  


Grading
: The grading for the course will consist of:
    * 60% for weekly homework assignments 
    * 15% for quizzes about the readings 
    * 25% for the final project or 3 optional homeworks

: Homeworks and quizes are weighted equally within their respective categories.
: Homework will be released two weeks before it is due. There will be 8 homeworks, roughly due weekly. Please see the Schedule
: Final Project will be done in groups of 3 or more. If you cannot think of a topic, or are struggling to form a team, you can do 4 alternative homeworks.  
    


Collaboration Policy
: Unless otherwise noted, you are allowed to work in pairs on the homework assignment.  Both partners will receive the same grade.  The final projects will have larger groups. 

Late Day Policy
: Each student has ten free "late days". Homeworks can be submitted at most three days late. If you are out of late days, then you will not be able to get credit for subsequent late assignments. One “day” is defined as anytime between 1 second and 24 hours after the homework deadline. The intent of the late day policy it to allow you to take extra time due to unforseen circumstances like illnesses. You do not need to ask permission to use your late days.

