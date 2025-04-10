---
title: Syllabus
layout: page
--- 
# Syllabus 

TOC
{:toc}

## Overview

This course provides an introduction to building secure software applications. It examines the software development life cycle and teaches what developers can do in each step to make their software more secure. It also will cover common vulnerabilities that exist and how developers can avoid or safeguard against them.

Students completing this should be able to build and deploy software with fewer security issues.

## Learning Outcomes
By the end of this course students should be able to:

- Explain core security concepts (including the CIA triad, authentication, and authorization) and analyze the technical, psychological, and economic factors that contribute to security vulnerabilities in software systems.
- Apply secure design principles throughout the software development lifecycle, including threat modelling, architectural reviews, and cryptographic techniques, to create systems that are secure by design rather than through retrofitting.
- Identify, analyze, and mitigate common implementation-level vulnerabilities, including those related to access control, resource management, calculation errors, and improper input neutralization (such as SQL injection and XSS attacks).
- Implement a comprehensive security testing strategy that combines multiple approaches (static analysis, runtime testing, fuzzing, and security scorecards) to effectively identify and validate security vulnerabilities throughout the development process.
- Explain secure deployment practices within a DevSecOps framework, including proper secrets management, secure configuration, and continuous monitoring, while maintaining system security through updates and incident response.
- Evaluate and appropriately utilize modern development tools, including AI code generation tools, while understanding their security implications and implementing necessary safeguards to ensure the security of the resulting software.

## Intended Audience
Third or fourth year CS students (CS 489) or first year CS graduate students (CS 698)

## Pre and Corequisites
- **Corequisites:** CS454 or CS456
- **Prerequisites:** (MATH135 or MATH145) and (CS 350 or SE 350). 
- Familiarity with C and Python

## Course Outline

### Module - Foundations of Secure Programming
Jan 06
Lecture: Security Concepts and the Vulnerability Landscape
Jan 08
Lecture: Challenges and Best Practices in Secure Development

### Module - Security Architecture & Design
Jan 13
Lecture: Introduction to Security Architecture
Jan 15
Lecture: Risk Analysis and Management
Jan 20
Lecture: Architectural Review and Vulnerability Analysis
Jan 22
Lecture: Secure Design Foundations & Strategies
Jan 27
Lecture: Cryptopgraphy & Retrofitting
Jan 29
Lecture: Prototyping in Secure Software Design

### Module - Implementation-Level Vulnerabilities 
Feb 03
Lecture: Access Control and Resource Management Vulnerabilities
Feb 05
Lecture: Calculation, Protection, and Neutralization Vulnerabilities

### Module - AI Code Generation Tools
Feb 10
Lecture: Code Generation Tools and Security
Feb 12
Lecture: Current Research in AI Code Generation Tools

### READING WEEK - Feb 14 - 22

### Module - Testing
Feb 24
Lecture: Why Test & Good General Practices
Feb 26
Lecture: Static Code Analysis

### Prototype Presentations
Mar 03
Prototype Presentations Day 1
Mar 05
Prototype Presentations Day 2

### Module - Testing (continue)
Mar 10
Lecture: Security Scorecards & Profilers
Mar 12
Lecture: Fuzzing
Mar 17
Lecture: Runtime Testing

### Module - Secure Software Deployment and Maintenance
Mar 19
Lecture: Secure Deployment Practices and DevSecOps
Mar 24
Lecture: Continuous Monitoring, Incident Response, and Secure Updates
Mar 26
Lecture: Course Wrap Up

### Final Project Presentations
Mar 31
Final Project Presentations Day 1
Apr 2
Final Project Presentations Day 2


## Grading

### Mark composition
Grades will be calculated as follows:

| Component                           | Value |
| ----------------------------------- | ----- |
| Class Participation                 | 5%    |
| A1: Assignment 1                    | 15%   |
| A2: Assignment 2                    | 15%   |
| P1: Proposal Draft Document         | 5%    |
| P2: Peer Team Evaluation            | 5%    |
| P3: Prototype Demo                  | 5%    |
| P4: Proposal Document               | 5%    |
| P5: Testing Document                | 10%   |
| P6: Final Presentations             | 5%    |
| P7: Security Arch & Design Document | 10%   |
| Final Exam                          | 20%   |

{: .important }
>**For graduate students:**
>the above scaled to 80% + 20% survey paper

Please consult the course [weekly schedule](./schedule.html) for the assessment deadlines.

### Assignment Guidelines

{: .important }
>Please note that the following instructions pertain to assignments only. Instructions for project components may differ.

Your assignments must be submitted online to LEARN dropbox by the deadline specified in the Course Schedule and in the dropbox. Dropboxes can be accessed by clicking Submit and then Dropbox on the course navigation bar in LEARN.

### General Guidelines

- Ensure that the name of your files do not include special characters such as symbols or punctuation. Such characters may cause problems when uploading your file.
Do not zip your files.
- Keep a copy of your assignment.
- If your submission is successful, you will receive an Email Confirmation Receipt sent to your @uwaterloo.ca email address. If you do not receive an Email Confirmation Receipt, please double-check your submission and resubmit if necessary.
- Keep all Email Confirmation Receipts until the course is over as proof of submission.
- For more information about accessing and submitting to a LEARN dropbox, please see the [IST Knowledge Base: Dropboxes - Students](https://uwaterloo.atlassian.net/wiki/spaces/ISTKB/pages/1551630337/Dropboxes+-+Students)

#### Feedback

Once the due date has passed, course staff will mark your submissions. After all submissions have been marked, an announcement will be posted letting you know that your feedback is available to view. To access your feedback, follow the steps in [Viewing Feedback in a Dropbox](https://uwaterloo.atlassian.net/wiki/spaces/ISTKB/pages/1551630337/Dropboxes+-+Students#Viewing-feedback-in-a-Dropbox).

## Administrative Policies
### Assignment and Project Component deadlines
It is your responsibility to ensure that you submit your assignment or project component correctly to LEARN before the deadline. The deadline is based on the time of day in Waterloo, Ontario (Eastern Standard Time or Eastern Daylight Time, depending on the time of year). The current date and time in Waterloo are always shown at the top-right of course web pages.

{: .important }
>- **Late assignment submissions will not be accepted unless you have an accommodation** (see below). 
>- **Late project component submissions will never be accepted.** We will not grant an extension because your team was not organized enough to know who was supposed to submit the work or because that person's internet connection failed at the crucial moment of submission. Be sure to submit well in advance and to exchange contact information in the event of an issue with a submission.

### Accommodation Due to Illness
#### Missed Assignments

If you are unable to complete an assignment  because of illness, or other extenuating circumstances, submit appropriate documentation to Quest. There is no need to contact course staff for short extensions. We are notified daily of absences and at the discretion of the course staff, you will receive up to a two day extension.

Further information regarding Management of Requests for [Accommodation Due to Illness](https://uwaterloo.ca/the-centre/academics/academics-undergraduate-students/accommodation-due-illness) can be found on the Accommodation due to illness page.

#### Missed Final Examination

If you are unable to write a final examination due to illness, seek medical treatment and have a [medical practitioner](https://uwaterloo.ca/students/health-and-well-being/primary-care-appointments/student-medical-clinic) complete a [Verification of Illness Form](https://uwaterloo.ca/math/accommodations/submission). This should be submitted through Quest. 

You will be REQUIRED to hand in the completed form before you write a make-up examination.
After your completed Verification of Illness Form has been received and processed, you will be emailed your alternate exam date and time. This can take up to 2 business days.

Further information about Examination Accommodation Due to Illness regulations is available in the Undergraduate Calendar.

### Academic Integrity

In order to maintain a culture of academic integrity, members of the University of Waterloo community are expected to promote honesty, trust, fairness, respect and responsibility. [Check the [Office of Academic Integrity](https://uwaterloo.ca/academic-integrity/) for more information.]

#### Generative AI

Generative artificial intelligence (GenAI) trained using large language models (LLM) or other methods to produce text, images, music, or code, like Chat GPT, DALL-E, or GitHub CoPilot, may be used in this course with proper documentation, citation, and acknowledgement. Permitted uses of and expectations for using GenAI will discussed in class and outlined on assignment instructions. 

Recommendations for how to cite generative AI in student work at the University of Waterloo may be found through the Library: [https://subjectguides.uwaterloo.ca/chatgpt_generative_ai](https://subjectguides.uwaterloo.ca/chatgpt_generative_ai). Please be aware that generative AI is known to falsify references to other work and may fabricate facts and inaccurately express ideas. GenAI generates content based on the input of other human authors and may therefore contain inaccuracies or reflect biases. 

In addition, you should be aware that the legal/copyright status of generative AI inputs and outputs is unclear. Exercise caution when using large portions of content from AI sources, especially images. More information is available from the Copyright Advisory Committee: [https://uwaterloo.ca/copyright-at-waterloo/teaching/generative-artificial-intelligence](https://uwaterloo.ca/copyright-at-waterloo/teaching/generative-artificial-intelligence)

You are accountable for the content and accuracy of all work you submit in this class, including any supported by generative AI.

#### Discipline

A student is expected to know what constitutes academic integrity to avoid committing an academic offence, and to take responsibility for his/her actions. [Check the [Office of Academic Integrity](https://uwaterloo.ca/academic-integrity/) for more information.] 

A student who is unsure whether an action constitutes an offence, or who needs help in learning how to avoid offences (e.g., plagiarism, cheating) or about “rules” for group work/collaboration should seek guidance from the course instructor, academic advisor, or the undergraduate associate dean. 

For information on categories of offences and types of penalties, students should refer to [Policy 71](https://uwaterloo.ca/secretariat/policies-procedures-guidelines/policy-71), Student Discipline. For typical penalties check [Guidelines for the Assessment of Penalties](https://uwaterloo.ca/secretariat/guidelines/guidelines-assessment-penalties).

#### Grievance

A student who believes that a decision affecting some aspect of his/her university life has been unfair or unreasonable may have grounds for initiating a grievance. 

Read [Policy 70](https://uwaterloo.ca/secretariat/policies-procedures-guidelines/policy-70), Student Petitions and Grievances, Section 4. 

When in doubt, please be certain to contact the department’s administrative assistant who will provide further assistance. , Student Petitions and Grievances, Section 4.

#### Appeals

A decision made or penalty imposed under Policy 70 (Student Petitions and Grievances) (other than a petition) or Policy 71 (Student Discipline) may be appealed if there is a ground.

A student who believes he/she has a ground for an appeal should refer to [Policy 72 (Student Appeals)](https://uwaterloo.ca/secretariat/policies-procedures-guidelines/policy-72).

### Accommodations

AccessAbility Services, located in Needles Hall, Room 1401, collaborates with all academic departments to arrange appropriate accommodations for students with disabilities without compromising the academic integrity of the curriculum. If you require academic accommodations to lessen the impact of your disability, please register with AccessAbility Services at the beginning of each academic term.

### Diversity

It is our intent that students from all diverse backgrounds and perspectives be well served by this course and that students’ learning needs be addressed both in and out of class. We recognize the immense value of the diversity in identities, perspectives, and contributions that students bring, and the benefit it has on our educational environment. Your suggestions are encouraged and appreciated. Please let us know ways to improve the effectiveness of the course for you personally or for other students or student groups. In particular:

- We will gladly honour your request to address you by an alternate/preferred name or gender pronoun. Please advise us of this preference early in the term so we may make appropriate changes to our records.
- We will honour your religious holidays and celebrations. Please inform of us these at the start of the course.
- We will follow AccessAbility Services guidelines and protocols on how to best support students with different learning needs.

### Mental Health

If you or anyone you know experiences any academic stress, difficult life events, or feelings like anxiety or depression, we strongly encourage you to seek support.

##### On-campus Resources

- Campus Wellness: [https://uwaterloo.ca/campus-wellness/](https://uwaterloo.ca/campus-wellness/)
- Counselling Services: [counselling.services@uwaterloo.ca](mailto:counselling.services@uwaterloo.ca) / 519-888-4567 ext 32655 / Needles Hall North 2nd floor, (NH 2401)
- MATES: one-to-one peer support program offered by Waterloo Undergraduate Student Association(WUSA) and Counselling Services: [mates@uwaterloo.ca](mailto:mates@uwaterloo.ca)
- Health Services service: located across the creek from Student Life Centre, 519-888-4096.

##### Off-campus Resources

- Good2Talk (24/7): Free confidential help line for post-secondary students. Phone: 1-866-925-5454
- Here 24/7: Mental Health and Crisis Service Team. Phone: 1-844-437-3247
- OK2BME: set of support services for lesbian, gay, bisexual, transgender or questioning teens in Waterloo. Phone: 519-884-0000 extension 213
