---
course_id: 6-831-user-interface-design-and-implementation-spring-2011
layout: course_section
menu:
  leftnav:
    identifier: 1c9ae28587b755df3b1c2af5c1e1536c
    name: Task Analysis
    parent: 09700340607a547cda2b20b3c55a84bd
    weight: 140
parent_title: In-Class Activities
title: Task Analysis
type: course
uid: 1c9ae28587b755df3b1c2af5c1e1536c

---

![A photo of the MIT classroom in which 6.831 was taught.](/coursemedia/6-831-user-interface-design-and-implementation-spring-2011/8f71c12bec6b4381d1e1a5a840cd1386_ac6-1.jpg) The goal of this activity is to practice doing user, task and domain analysis by observing a real environment of people working. Without actual observation, task analysis is incomplete and biased. For this exercise, we'll observe the most conveniently available environment: our classroom.

Assume we're thinking of developing a system to deliver 6.831 as an _online_ course. We're not actually going to do any design in this exercise, but you should think about users, tasks, and entities from this point of view.

1\. User Analysis
-----------------

Who are the major user classes involved in the system? What are their important characteristics? Note that some relevant user classes might not have any representatives in the room right now.

2\. Task Analysis
-----------------

Pick an important user class **that you don't belong to**. Identify important tasks for this user class by observation. Structure your task analysis hierarchically, with tasks and subtasks.

A few things to think about:

*   Try to distinguish essential tasks (independent of the current in-person course) from concrete tasks (which exist in the current design, but maybe don't need to be there). Why is it important to think about this distinction?

3\. Domain Analysis
-------------------

Draw a domain model for the course. Include boxes for major user classes and for major information objects. Draw lines between the boxes for important relations. Finally, annotate the boxes with multiplicities (e.g., how many members of each user class?)