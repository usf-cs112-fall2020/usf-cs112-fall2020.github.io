---
title: Course Syllabus
hidecrumbs: true
navbar: Syllabus
layout: guides
---

# CS 112-03 Intro to Computer Science II
{: .title }

#### Fall 2020 &bull; CS 112-03 &bull; 4 Credits
{: .subtitle .has-text-weight-light }

{{ site.data.info.blurb }}

[USF Catalog](https://catalog.usfca.edu/preview_course_nopop.php?catoid=22&coid=186444)
{: .button .is-primary }


## Summary

This syllabus is similar to a contract between students and the instructor, and as such it is quite long (with many sections required by the university). A few key points from this syllabus are highlighted here:

  - We will primarily use Piazza for all asynchronous communication for this class, not email. See: [Communication Policy](#communication-policy)

  - You should be stuck for an hour on a problem before seeking help, but you should definitely seek help if you have been stuck for an hour. See: [Getting Help](#asynchronous-communication)

  - Do not cheat. This includes working too closely with your classmates or the TA. See: [Cheating Policy](#cheating-policy)

  - You must pass at least one midterm to earn a C or higher letter grade in this class. See: [Pass Requirements](#pass-requirements)

  - You must pass the final coding interview to earn a C or higher letter grade in this class. See: [Pass Requirements](#pass-requirements)

  - Attendance is required one per week and late submissions are not accepted; but there are automatic exceptions granted for certain situations. See: [Policy Exceptions](#policy-exceptions)

  - Treat this class like a part-time job and plan to spend 10 to 20 hours coding per week outside of class. See: [Credit Hour Policy](#credit-hour-policy)

You are still required to read through the entire syllabus below.

## Course Details
{: .page-header }

This section covers basic information about the course, instructor, and teacher assistants.

### Lecture Sections

This syllabus covers the following lecture sections:

<div class="columns">
  <div class="column is-narrow">
    <strong>CS 112-03 (CRN 42558)</strong><br/>
    <i class="fa-fw fas fa-calendar-alt"></i>
    <del>Mondays</del>, Wednesdays<br/>
    <i class="fa-fw fas fa-clock"></i>
    7:30pm &ndash; 9:15pm<br/>
    <i class="fa-fw fas fa-signal-stream"></i>
    Zoom: <a href="{{ site.data.info.streams.lecture1.link }}">{{ site.data.info.streams.lecture1.room }}</a>
  </div>
</div>

Generally, the last 15 minutes of the lectures will be replaced by asynchronous content such as pre-recorded videos and quizzes. See the [course schedule]({{ "/schedule.html" | relative_url }}) for details.

<i class="fas fa-info-circle"></i>
See the [Attendance Policy](#attendance-policy) for whether you can attend a section you are not enrolled.
{: class="notification" markdown="1" }

### Instructor and Assistants

The instructor and instructor office hours for this course will be:

<div class="columns">
  <div class="column is-narrow">
    <div class="box">
      <!-- nested columns for profile photo -->
      <div class="columns is-mobile is-variable is-1">
        <div class="column is-narrow">
          <div class="image is-64x64">
            <img class="is-rounded" src="https://www.cs.usfca.edu/~ejung/images/EunjinJung.png">
          </div>
        </div>

        <div class="column">
          <strong>EJ Jung</strong><br/>
          <i class="fa-fw fas fa-calendar-alt "></i>
          <span>Tuesdays and some Thursdays, 11:45am-12:45pm</span>
          <br/>

          <i class="fa-fw fas fa-calendar-alt "></i>
          <span>Wednesdays, 12-1pm</span>
          <br/>
          
          <i class="fa-fw fas fa-calendar-alt "></i>
          <span>and by appointments</span>
          <br/>


          <i class="fa-fw fas fa-signal-stream "></i>
          Appointment Calendar: <a href="https://calendar.google.com/calendar/selfsched?sstoken=UUw3eEFUQWZvRVdFfGRlZmF1bHR8MjI5MzY5MzUwMmJhNTIwMjliMjRhOTU2YjgwMjIzODg">sign up here</a>
          <br/>

        </div>
      </div>
      <!-- end nested columns -->
    </div>
  </div>
</div>

The teacher assistant and teacher assistant office hours for this course will be posted on [Piazza]({{ site.data.info.links.piazza.link }}) at the start of the semester.

<i class="fas fa-envelope-open-text"></i>
See the [Communication Policy](#communication-policy) for how to contact the instructor and TA.
{: class="notification" markdown="1" }

### Prerequisites

The prerequisite for this class is [CS 110 Intro to Computer Science I](https://catalog.usfca.edu/preview_course_nopop.php?catoid=22&coid=186443) with a letter grade of C or higher. You may not take the prerequisite at the same time as this class.

### Required Materials

This course will use [Big Java:Early Objects 6th edition](https://www.wiley.com/en-us/Big+Java:+Early+Objects,+6th+Edition-p-9781119141594) as the textbook. The [4th edition of this book](https://go.oreilly.com/university-of-san-francisco/library/view/-/9780470509487/?ar) is freely available to enrolled students through USF library. This course utilizes software that are freely available for enrolled students, such as Java SDK and Eclipse. 

### Important Dates

Below are important dates relevant to this class:

| 🚩 | Date  | Description |
|---:|:-----:|:------------|
|    | 08/18 | Fall 2020 classes begin. |
|    | 08/24 | Last day to add classes online. |
|    | 09/04 | Census date; last day to drop without a "W" appearing on transcript. |
| 🚩 | 09/17 | Midterm 1; review session on Tuesday. |
|    | 10/30 | Last day to withdraw from a class and receive a "W" on transcript. |
| 🚩 | 10/22 | Midterm 2; rreview session on Tuesday. |
|    | 11/23 | Beginning of a week-long Thanksgiving recess. |
|    | 11/30 | Classes resume following Thanksgiving recess. |
|    | 12/03 | Fall 2020 classes end. |
| 🚩 | 12/04 | Finals begin; start of individual final coding interview. |
{: class="table dates is-hoverable" style="width: auto;" }

See the [official academic calendar](https://myusf.usfca.edu/registration/academic-calendar) for other important dates.

<i class="fas fa-info-circle"></i>
There will be an individually-scheduled final coding interview instead of a final exam during finals week.
{: class="notification" markdown="1" }

## Learning and Assessment
{: .page-header }

This section covers the learning outcomes for this course and how they will be assessed.

### Learning Outcomes

At the end of this course, you should be able to:

  - Implement medium-sized Java programs with 500 to 1,000 source lines of code (SLOC)
  - Describe, trace programs using, and implement programs using the following intermediate-level programming concepts:
    - arrays 
    - File I/O
    - exception handling
    - inheritance and object-oriented design principles
    - built-in data structures and the Collections library
    - sorting and searching
    - recursion
    - linked lists

Assessment of these outcomes will be done by a combination of pass requirements, exams, labs, projects, and more. See [Grading Breakdown](#grading-breakdown) below for details.

### Pass Requirements

To ensure you are meeting the [learning outcomes](#learning-outcomes) for this course, you must meet the following minimum requirements to receive a C or higher grade in this course:

  - **Midterm Pass Requirement:** Students must receive an average C letter grade or higher on at least one midterm.

  - **Final Coding Interview Pass Requirement:** Students must receive an average C letter grade or higher on the final coding interview.

**Failure to meet 1 or more of these requirements will cap your letter grade for this course to C– maximum, regardless of whether you have a higher letter grade in Canvas.**
{: .has-text-danger }

If you are concerned about not meeting one or more of these requirements by the withdraw deadline, you are encouraged to consult with the instructor. Your best option may be to withdraw from the class. Note, however, that a W (withdraw) counts as an attempt and CS majors and minors have restrictions on how many times they may attempt CS courses.

<i class="fas fa-exclamation-triangle"></i>
Meeting the pass requirements does not guarantee a passing grade. See the [Grade Breakdown](#grade-breakdown) section below for how the final grade will be calculated.
{: class="notification" markdown="1" }

### Grading Breakdown

If you are meeting the [pass requirements](#pass-requirements), then your final letter grade for this class will be calculated as follows:

| Percent | Category        |
|--------:|:----------------|
|      5% | Attendance      |
|      5% | Participation   |
|      5% | Quizzes         |
|     10% | Exams           |
|     15% | Homework        |
|     60% | Projects        |
{: class="table is-hoverable" style="width: auto;"}

The assignments within each category are not necessarily equally weighted. For example, some participation assignments are worth more points than others.

Each of these categories are described more below.

#### Attendance (Synchronous)

You must attend and participate in *at least* one synchronous interaction per week.  The options are:

  - **Lecture:** You should ideally attend and participate in every synchronous lecture via Zoom. This includes answering questions during the Zoom meeting and participating in breakout rooms.

  - **Alternatives:** You may alternatively watch the recording and attend office hours with the instructor or teacher assistant. This must be a meaningful interaction, such as asking a question or having a discussion.

<i class="fas fa-exclamation-triangle"></i>
Misrepresenting your attendance or participation is a violation of academic integrity. See the [Cheating Policy](#cheating-policy) for possible consequences.
{: class="notification" markdown="1" }

#### Participation (Asynchronous)

This includes pass/fail assignments for completing surveys and discussions on Piazza, and participating in CS-sponsored events. 

#### Quizzes

Short quizzes are assigned throughout the week, sometimes at the start of class. You will be given an opportunity to retake those quizzes until the deadline. Quizzes will be conducted on [Canvas]({{ site.data.info.links.canvas.link }}).

#### Exams

There will be two exams. The exams are *not* comprehensive. See [Important Dates](#important-dates) for the exam dates. You must receive an average C letter grade or higher on at least one exam. See the [Pass Requirements](#pass-requirements) for more.

Instead of a final exam, students will have a final coding interview graded during finals week.

#### Labs

Lab programming assignments are assigned on a semi-weekly basis, and usually due the following week.

Partial grades are given for lab assignments; grades will be proportional to the correctly implemented functionalities.

#### Projects

Programming projects are in fact milestones towards a single big project, guiding students through milestones. Each project will be graded not only in functionality but also in code quality. 

Note that the earlier projects are basis for the later projects. If a student fails to complete project 1 by deadline, he or she will have extra work to finish project 1 before project 2 deadline. To enforce timely completion of each milestone, project deadlines are firm. 

### Grading Scale

The following is the grading scale mapping percentage to letter grade and GPA for this course:

<style>
table.gpa tbody tr:nth-child(n+9) {
  color: #CD542C;
  font-weight: 500;
}
</style>

|          | Letter |        | GPA |
|---------:|:-------|:-------|:---:|
| 97% &le; | A+     | < 100% | 4.0 |
| 94% &le; | A      | < 97%  | 4.0 |
| 90% &le; | A--    | < 94%  | 3.7 |
| 87% &le; | B+     | < 90%  | 3.3 |
| 84% &le; | B      | < 87%  | 3.0 |
| 80% &le; | B--    | < 84%  | 2.7 |
| 77% &le; | C+     | < 70%  | 2.3 |
| 74% &le; | C      | < 77%  | 2.0 |
| 70% &le; | C--    | < 74%  | 1.7 |
| 67% &le; | D+     | < 70%  | 1.3 |
| 64% &le; | D      | < 67%  | 1.0 |
| 60% &le; | D--    | < 64%  | 0.7 |
|  0% &le; | F      | < 60%  | 0.0 |
{: class="table gpa" style="width: auto;"}

Non-passing grades for undergraduate CS majors and minors are highlighted in <strong class="has-text-danger">red</strong> text. See the [Undergraduate Student Regulations](https://catalog.usfca.edu/content.php?catoid=22&navoid=3097) for more about letter grades and GPA for undergraduate students.

## Course Policies
{: .page-header }

This section includes miscellaneous policies specific to this course, including communication, attendance, credit hours, cheating, and more. These policies are in addition to the standard USF policies included later.

### Communication Policy

Email will NOT be used for communication in this course.

Instead, please see how best to communicate depending on whether you wish to communicate synchronously (live, simultaneously, in real time) or asynchronously (on your own time, without immediate responses or feedback).

##### Synchronous Communication

The synchronous communication that would have occurred in-class will be conducted during the live lectures as follows:

  - [Raise Hand](https://support.zoom.us/hc/en-us/articles/115001286183): Use the "Raise Hand" feature in Zoom to get the instructor's attention. The instructor will pause and give you an opportunity to ask a question verbally or via the chat.

  - [Meeting Chat](https://support.zoom.us/hc/en-us/articles/203650445-In-Meeting-Chat): Use the in-meeting "Chat" feature in Zoom to ask questions or make comments. These should be posted in the "Everyone" channel (not privately). If you do not want your name to appear in the main chat, you can privately chat the instructor to post the question on your behalf instead.

Office hours will also be held via Zoom. Please make appointments [here](https://calendar.google.com/calendar/selfsched?sstoken=UUw3eEFUQWZvRVdFfGRlZmF1bHR8MjI5MzY5MzUwMmJhNTIwMjliMjRhOTU2YjgwMjIzODg). If you cannot make any of the available times, please send a private messsage on [Piazza]({{ site.data.info.links.piazza.link }}) with your availability for the next 3 days. 

##### Asynchronous Communication

Most asynchronous course-related communication will be handled using [Piazza]({{ site.data.info.links.piazza.link }})—a FERPA-compliant Q&A platform that supports public, anonymous, and private posts. When making posts on Piazza, please keep the following in mind:

  - **Search other posts first.** It is possible your question has already been asked and answered in another post. There is a search feature and you can use the folders to narrow posts to a single category.

  - **Make a public post when appropriate.** You can **post anonymously** if you prefer. Your classmates will not be able to see your identity for anonymous posts, but instructors will still be able to see your name. If you make a private post that should be public, you will be asked to create a new public anonymous post before receiving an answer.

  - **Do not post code publicly on Piazza.** If you have a question regarding your specific code, please post it as a private post to all instructors. This ensures only the instructor and TA will see your code.

  - **Make posts specific to solutions or grades private** to the instructor and teacher assistants. This replaces directly emailing the instructor regarding the course. If you email the instructor directly, you will be asked to make a private post on Piazza before receiving an answer.

  - **Follow the 1 hour rule.** You should be stuck on a problem between 30 minutes to 1 hour before asking for help, but should immediately ask for help if stuck over 1 hour. Worst case, you figure out the answer before we are able to help. Best case, we can help you get unstuck!

  - **Post exact details when possible.** You will get a solution faster if you include as many details as possible when asking for help. This might include exact error messages, stack traces, which tests are failing and passing, console or log output, and more. If you forget, we will have to ask you for this detail which can extend how long it takes to get help.

In addition to [Piazza]({{ site.data.info.links.piazza.link }}), the instructor will also use [Canvas]({{ site.data.info.links.canvas.link }}) to notify students of missing assignments or warn about low grades.

<i class="fas fa-exclamation-triangle"></i>
**Under no circumstances should you reach out to the teacher assistants via any unapproved communication channel.** Instructors and teacher assistants must provide all students equal opportunity for course-related help. Using unapproved communication channels creates an unfair advantage over other students and will be treated as a violation of the [Student Conduct Code](https://myusf.usfca.edu/fogcutter).
{: .notification }

### Student Conduct

Students are required to adhere to the University's [Student Code of Conduct](https://myusf.usfca.edu/fogcutter/student-conduct). In short, students are expected to treat each other with respect at all times.

In addition, remote learning often involves a **netiquette policy**. Simply stated, "netiquette" is network etiquette—that is, the etiquette of cyberspace. And "etiquette" means "the forms required by good breeding or prescribed by authority to be required in social or official life." In other words, Netiquette is a set of rules for behaving properly online [[1](http://www.albion.com/netiquette/introduction.html)].

##### Synchronous Netiquette

Activities that are **synchronous** are those that occur live (in real-time) with everyone participating at the same time. This includes livestreamed lectures and labs on Zoom. When communicating and participating in synchronous portions of the course:

  - Arrive on time and attend for the entire session.
  - Listen and dialog with each other respectfully.
  - Participate in live polls and surveys in a timely manner.
  - Need a break? Wait until the scheduled breaks if possible. There will either be two 10 minute breaks or one 15 minute break each lecture.

It will always be OPTIONAL whether you wish to enable your audio and/or video. When enabling your audio and/or video, keep in mind the following:

  - The main livestream is sometimes recorded for students unable to attend live. If you enable your audio and/or video, it is possible it will be part of the password- protected recording.
  - Consider enabling your audio and video during small group breakout rooms or when asking a question live.
  - Keep your microphone muted unless speaking.
  - If you choose to enable your video, please make sure to present yourself appropriately (dressed as you would be in the classroom) and double-check your background environment (for example, clean up laundry, trash).
  - Be careful what you do while your video is enabled. Everyone can see you in "Gallery View" if you enable video, even if you are not currently speaking.

##### Asynchronous Netiquette

Activities that are **asynchronous** are those that occur outside of class time, usually individually on your own. This includes watching a pre-recorded lecture or participating in an online discussion board. When communicating and participating in asynchronous portions of the course:

  - Be respectful of other participants and keep your comments constructive.
  - Avoid using all caps (may be read as SHOUTING).
  - Keep subject lines clear.
  - Spelling and grammar do count; proofread your writing.
  - Be coherent and succinct.
  - Check the most recent comment/email before replying to an earlier one.
  - Do not falsify information or impersonate others online.  
  - ~~Limit use of acronyms (eg YOLO), icons and emojis.~~ If you want to use an acronym, icon, or emoji (or even a GIF) in this class to express yourself, please feel free to do so :) Just keep it appropriate!

### Attendance Policy

See the [Attendance](#attendance) requirement for this course. You are expected to be on-time to all live lectures and labs to minimize disruption.

Attend the section of lecture and lab for which you are registered. Keeping the class sizes balanced is important for interactive exercises. One-time exceptions on non-exam days are allowed with pre-approval.

Attendance is mandatory for all one-on-one code review appointments. You must be on-time to these appointments. If you arrive more than 5 minutes late, the appointment will be canceled. You risk a grade penalty for repeated canceled or missed appointments.

### Late Policy

Except for projects, late submissions are not accepted.

<i class="far fa-tired"></i>
Don't worry---you may request an exception to this late policy in certain cases. See the [Policy Exceptions](#policy-exceptions) section for details.
{: .notification }

### Cheating Policy

All students are expected to know and adhere to the University's [Honor Code](https://myusf.usfca.edu/academic-integrity/). In short, students must never represent another person's work as their own. Examples of honor code violations include (but are not limited to):

  - Copying and pasting code (especially without attribution) from the web

  - Having anyone other than yourself complete your work (including teacher assistants, tutors, and former students)

  - Working too closely with others such that your code no longer represents an individual contribution

  - Sharing your solutions with others (either directly or indirectly)

Keep in mind that unauthorized collaboration or discussion that results in the same or very similar work indicates that you have not placed enough independent thought into your submission and is a violation of the honor code, regardless of whether you directly copied!

**Flagrant or repeat violations of the honor code will result in an F in the course, a report to the Academic Integrity Committee (AIC), and a report to the Dean.**{: .has-text-danger }
At the discretion of the instructor, a less severe penalty may be imposed for minor or first offenses. This is at the sole discretion of the instructor and any violation may result in an F in the course.

<i class="fas fa-code-branch"></i>
Keep in mind that there is a history of your code development on Github. Commit and push changes often to record your incremental code development.
{: .notification }

### Credit Hour Policy

All courses must comply with the [Credit Hour Policy](https://myusf.usfca.edu/sites/default/files/usf_credit_hour_policy_0.pdf), which states:

  > "One unit of credit in lecture, seminar, and discussion work should approximate one hour of direct faculty instruction and a minimum of two hours of out-of-class student work per week through one 15-week semester."

As this is a 4 credit course, students must spend a **minimum** of 8 hours of out-of-class work per week to earn a non-failing (D&ndash; or higher) letter grade. To earn a passing C or higher letter grade (as required for the CS major and minor), students should expect to spend closer to **10 to 15 hours per week** on projects and assignments.

<i class="fas fa-hourglass-half"></i>
Think of this class like a part-time job. If you do not put in the time, you will not make it to the final project. Many students do not pass due to poor time management!
{: .notification }

## Policy Exceptions
{: .page-header }

Life sometimes (often?) interferes with learning. Several exceptions to course policies will be granted **automatically** upon request. These exceptions are requested by making a private post on [Piazza]({{ site.data.info.links.piazza.link }}) within the required timeframe. See the following sections for additional details.

### Assignment Extension

You may request to have a 48 hour extension on any participation, quiz, or homework assignment. This request will be automatically granted as long as (1) the assignment is in the appropriate category, (2) the request is made within 48 hours of the assignment deadline, and (3) you have not made any previous extension requests. This extension does not cover assignments in other categories, such as exams or projects.

### Attendance Waiver

You may request to have your attendance waived for any lecture that does not have a scheduled exam or retake. The waiver will be automatically granted if (1) it is made within 48 hours of the missed lecture, (2) there is not an exam or retake scheduled that day, and (3) you have not made any previous attendance waiver requests.

### Extra Credit Request

You may request one extra credit/makeup opportunity for assignments in the participation, homework, or project categories. You may earn up to 50% of the amount of points missed on that assignment. For example, suppose you earned 70 out of 100 points on an assignment, you can request an extra credit opportunity to make up 15 points. There is no time limit on when this request may be made.

Only one request per semester will be automatically approved; choose wisely to maximize the impact on the final grade. Extra credit requests may not be made for quizzes or exams.

### Regret Clause

Did you cross the line and violate the [Academic Honesty](https://myusf.usfca.edu/academic-integrity/) policy? You can invoke the regret clause [[2](https://www.harvardmagazine.com/2020/03/cs50-regret-clause)] to avoid the full consequences outlined in the [Cheating Policy](#cheating-policy) section. Instead, you will be able to resubmit the offending assignment with up a 20% to 40% point deduction depending on the severity of the violation.

You must *voluntarily* invoke the regret clause within 48 hours of submitting the offending assignment and attend a one-on-one appointment with the instructor to discuss the specifics of your cheating case to qualify.

You cannot retroactively invoke the regret clause. If the instructor confronts you regarding cheating after the 48 hour grace period, expect full consequences for that action. You can only invoke the regret clause once. Repeat cheating cases will immediately result in an F for the course and report to the Academic Integrity Committee.

### Other Exceptions

Additional exceptions may be requested for *any* reason, but are more likely to be approved for verifiable exceptional circumstances. To make an additional policy exception request, please make a private post on Piazza to only the course instructor.

## University Policies
{: .page-header }

This section includes [standard statements](https://myusf.usfca.edu/arts-sciences/faculty-resources/curriculum/syllabi/policies-legal-declarations) on University policies and resources.

### Students with Disabilities

The University of San Francisco is committed to providing equal access to students with disabilities. If you are a student with a disability, or if you think you may have a disability, please contact [USF Student Disability Services (SDS)](https://myusf.usfca.edu/sds) at [sds@usfca.edu](mailto:sds@usfca.edu) or call (415) 422-2613 to speak with a disability specialist. All communication with SDS is private and confidential. If you are eligible for accommodations, please request that your accommodation letter be sent to me as soon as possible, as accommodations are not retroactive. Once I have been notified by SDS of your accommodations we can discuss your accommodations and ensure your access to this class or clinical setting.

### Behavioral Expectations

All students are expected to behave in accordance with the [Student Conduct Code](https://myusf.usfca.edu/fogcutter) and other University policies.

### Academic Integrity

USF upholds the standards of honesty and integrity from all members of the academic community. All students are expected to know and adhere to the University's [Honor Code](https://myusf.usfca.edu/academic-integrity/).

### Communication

~~All course communications, like all other USF communications, will be sent to your USF official email address. You are therefore strongly encouraged to monitor that email account.~~

<i class="fas fa-info-circle"></i>
See the [Communication Policy](#communication-policy) for this course above.
{: class="notification" markdown="1"}

### Counseling and Psychological Services (CAPS)

CAPS provides confidential, [free counseling](https://myusf.usfca.edu/student-health-safety/caps) to student members of our community.

### Confidentiality, Mandatory Reporting, and Sexual Assault

For information and resources regarding sexual misconduct or assault visit the [Title IX](https://myusf.usfca.edu/TITLE-IX) coordinator or [USF's Callisto website](http://usfca.callistocampus.org/).
